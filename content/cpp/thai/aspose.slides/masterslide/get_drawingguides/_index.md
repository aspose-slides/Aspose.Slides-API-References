---
title: get_DrawingGuides()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: ส่งคืนคอลเลกชันของไกด์การวาดสำหรับสไลด์หลัก. อ่านอย่างเดียว IDrawingGuidesCollection
type: docs
weight: 170
url: /th/aspose.slides/masterslide/get_drawingguides/
---
## MasterSlide::get_DrawingGuides() เมธอด


ส่งคืนคอลเลกชันของไกด์การวาดสำหรับสไลด์หลัก. อ่านอย่างเดียว [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::MasterSlide::get_DrawingGuides() override
```

## หมายเหตุ



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_Master(0)->get_DrawingGuides();
// เพิ่มไกด์การวาดแนวตั้งใหม่ไปทางด้านขวาของจุดกึ่งกลางสไลด์
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 20.0f);
pres->Save(u"MasterSlideDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IDrawingGuidesCollection](../../idrawingguidescollection/)
* คลาส [MasterSlide](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)