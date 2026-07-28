---
title: get_DrawingGuides()
second_title: Aspose.Slides C++ API referencia
description: Visszaad egy gyűjteményt a mester kézjegyzet dia rajzoló segédvonalairól. Írásvédett IDrawingGuidesCollection
type: docs
weight: 53
url: /hu/aspose.slides/masterhandoutslide/get_drawingguides/
---
## MasterHandoutSlide::get_DrawingGuides() metódus


Visszaad egy gyűjteményt a mester kézjegyzet dia rajzoló segédvonalairól. Írásvédett [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::MasterHandoutSlide::get_DrawingGuides() override
```

## Megjegyzések


```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF notesSize = pres->get_NotesSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_MasterHandoutSlideManager()->SetDefaultMasterHandoutSlide()->get_DrawingGuides();
// Adding the new horizontal drawing guide above the slide center
guides->Add(Orientation::Horizontal, notesSize.get_Height() / 2 - 50.0f);
pres->Save(u"MasterHandoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Osztály [MasterHandoutSlide](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)