---
title: get_DrawingGuides()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ส่งคืนคอลเลกชันของแนวทางการวาดสำหรับสไลด์มืออธิบายหลัก. อ่านอย่างเดียว IDrawingGuidesCollection
type: docs
weight: 14
url: /th/aspose.slides/imasterhandoutslide/get_drawingguides/
---
## IMasterHandoutSlide::get_DrawingGuides() เมธอด

ส่งคืนคอลเลกชันของแนวทางการวาดสำหรับสไลด์มืออธิบายหลักแบบอ่านอย่างเดียว [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::IMasterHandoutSlide::get_DrawingGuides()=0
```

## หมายเหตุ



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF notesSize = pres->get_NotesSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_MasterHandoutSlideManager()->SetDefaultMasterHandoutSlide()->get_DrawingGuides();
// Adding the new horizontal drawing guide above the slide center
guides->Add(Orientation::Horizontal, notesSize.get_Height() / 2 - 50.0f);
pres->Save(u"MasterHandoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IDrawingGuidesCollection](../../idrawingguidescollection/)
* คลาส [IMasterHandoutSlide](../)
* เนมส페ซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)