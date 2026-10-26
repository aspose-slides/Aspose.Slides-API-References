---
title: get_DrawingGuides()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ส่งคืนคอลเลกชันของแนวการวาดสำหรับสไลด์เค้าโครง. อ่านอย่างเดียว IDrawingGuidesCollection
type: docs
weight: 79
url: /th/aspose.slides/ilayoutslide/get_drawingguides/
---
## ILayoutSlide::get_DrawingGuides() เมธอด

ส่งคืนคอลเลกชันของแนวการวาดสำหรับสไลด์เค้าโครง. อ่านอย่างเดียว [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::ILayoutSlide::get_DrawingGuides()=0
```

## หมายเหตุ

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_LayoutSlide(0)->get_DrawingGuides();
// เพิ่มแนวการวาดแนวตั้งใหม่ทางด้านซ้ายของศูนย์กลางสไลด์
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 - 20.0f);
pres->Save(u"LayoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IDrawingGuidesCollection](../../idrawingguidescollection/)
* คลาส [ILayoutSlide](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)