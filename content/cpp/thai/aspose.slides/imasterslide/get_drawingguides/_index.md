---
title: get_DrawingGuides()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ส่งคืนคอลเลกชันของแนวทางการวาดสำหรับสไลด์แม่ อ่านอย่างเดียว IDrawingGuidesCollection
type: docs
weight: 105
url: /th/aspose.slides/imasterslide/get_drawingguides/
---
## IMasterSlide::get_DrawingGuides() เมธอด


Returns a collection of drawing guides for the master slide. อ่านอย่างเดียว [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::IMasterSlide::get_DrawingGuides()=0
```

## หมายเหตุ



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_Master(0)->get_DrawingGuides();
// เพิ่มแนวนำทางการวาดแนวตั้งใหม่ไปทางขวาของศูนย์สไลด์
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 20.0f);
pres->Save(u"MasterSlideDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IDrawingGuidesCollection](../../idrawingguidescollection/)
* คลาส [IMasterSlide](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)