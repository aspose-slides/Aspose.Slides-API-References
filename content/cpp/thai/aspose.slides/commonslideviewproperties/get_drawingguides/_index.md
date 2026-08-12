---
title: get_DrawingGuides()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: ส่งคืนคอลเลกชันของไกด์การวาด. อ่านอย่างเดียว IDrawingGuidesCollection
type: docs
weight: 53
url: /th/aspose.slides/commonslideviewproperties/get_drawingguides/
---
## CommonSlideViewProperties::get_DrawingGuides() เมธอด


ส่งคืนชุดของไกด์การวาด. อ่านอย่างเดียว [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::CommonSlideViewProperties::get_DrawingGuides() override
```

## หมายเหตุ


ตัวอย่างโค้ดต่อไปนี้แสดงวิธีการเพิ่มไกด์การวาดใหม่ในงานนำเสนอ PowerPoint.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();

System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_ViewProperties()->get_SlideViewProperties()->get_DrawingGuides();
// Adding the new vertical drawing guide to the right of the slide center
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 12.5f);
// Adding the new horizontal drawing guide below the slide center
guides->Add(Orientation::Horizontal, slideSize.get_Height() / 2 + 12.5f);

pres->Save(u"DrawingGuides_out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IDrawingGuidesCollection](../../idrawingguidescollection/)
* คลาส [CommonSlideViewProperties](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)