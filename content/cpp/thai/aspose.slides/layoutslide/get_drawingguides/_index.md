---
title: get_DrawingGuides()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ส่งคืนคอลเลกชันของแนวทางการวาดสำหรับสไลด์เลย์เอาต์. อ่านอย่างเดียว IDrawingGuidesCollection
type: docs
weight: 118
url: /th/aspose.slides/layoutslide/get_drawingguides/
---
## LayoutSlide::get_DrawingGuides() เมธอด


ส่งคืนคอลเลกชันของแนวทางการวาดสำหรับสไลด์เลย์เอาต์. อ่านอย่างเดียว [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::LayoutSlide::get_DrawingGuides() override
```

## หมายเหตุ



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_LayoutSlide(0)->get_DrawingGuides();
// เพิ่มไกด์การวาดแนวตั้งใหม่ทางด้านซ้ายของจุดกึ่งกลางสไลด์
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 - 20.0f);
pres->Save(u"LayoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IDrawingGuidesCollection](../../idrawingguidescollection/)
* คลาส [LayoutSlide](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)