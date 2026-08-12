---
title: get_DrawingGuides()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: คืนคอลเลกชันของไกด์การวาดสำหรับสไลด์มาสเตอร์แฮนด์เอาต์. อ่านอย่างเดียว IDrawingGuidesCollection
type: docs
weight: 53
url: /th/aspose.slides/masterhandoutslide/get_drawingguides/
---
## MasterHandoutSlide::get_DrawingGuides() เมธอด

คืนคอลเลกชันของไกด์การวาดสำหรับสไลด์มาสเตอร์แฮนด์เอาต์. อ่านอย่างเดียว [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::MasterHandoutSlide::get_DrawingGuides() override
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
* คลาส [MasterHandoutSlide](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)