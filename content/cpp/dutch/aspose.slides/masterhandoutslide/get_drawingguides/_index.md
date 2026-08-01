---
title: get_DrawingGuides()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een collectie tekenrichtlijnen voor de masterhandoutdia. Alleen-lezen IDrawingGuidesCollection
type: docs
weight: 53
url: /nl/aspose.slides/masterhandoutslide/get_drawingguides/
---
## MasterHandoutSlide::get_DrawingGuides() methode


Retourneert een verzameling tekenlijnen voor de masterhandoutdia. Alleen-lezen [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::MasterHandoutSlide::get_DrawingGuides() override
```

## Opmerkingen



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF notesSize = pres->get_NotesSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_MasterHandoutSlideManager()->SetDefaultMasterHandoutSlide()->get_DrawingGuides();
// Adding the new horizontal drawing guide above the slide center
guides->Add(Orientation::Horizontal, notesSize.get_Height() / 2 - 50.0f);
pres->Save(u"MasterHandoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Klasse [MasterHandoutSlide](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)