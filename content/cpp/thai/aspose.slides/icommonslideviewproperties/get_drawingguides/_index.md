---
title: get_DrawingGuides()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: ส่งคืนคอลเลกชันของคู่มือการวาด. อ่านอย่างเดียว IDrawingGuidesCollection
type: docs
weight: 53
url: /th/aspose.slides/icommonslideviewproperties/get_drawingguides/
---
## ICommonSlideViewProperties::get_DrawingGuides() เมธอด


ส่งคืนคอลเลกชันของคู่มือการวาด. อ่านอย่างเดียว [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::ICommonSlideViewProperties::get_DrawingGuides()=0
```

## หมายเหตุ


โค้ดตัวอย่างต่อไปนี้แสดงวิธีเพิ่มคู่มือการวาดใหม่ในงานนำเสนอ PowerPoint. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();

System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_ViewProperties()->get_SlideViewProperties()->get_DrawingGuides();
// เพิ่มแนวทางการวาดแนวตั้งใหม่ทางขวาของศูนย์สไลด์
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 12.5f);
// เพิ่มแนวทางการวาดแนวนอนใหม่ด้านล่างของศูนย์สไลด์
guides->Add(Orientation::Horizontal, slideSize.get_Height() / 2 + 12.5f);

pres->Save(u"DrawingGuides_out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IDrawingGuidesCollection](../../idrawingguidescollection/)
* คลาส [ICommonSlideViewProperties](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)