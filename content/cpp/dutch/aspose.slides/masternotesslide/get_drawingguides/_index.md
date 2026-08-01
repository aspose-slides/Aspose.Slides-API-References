---
title: get_DrawingGuides()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een verzameling tekenrichtlijnen voor de masternotitieslide. Alleen-lezen IDrawingGuidesCollection
type: docs
weight: 66
url: /nl/aspose.slides/masternotesslide/get_drawingguides/
---
## MasterNotesSlide::get_DrawingGuides() methode


Retourneert een verzameling tekenrichtlijnen voor de masternotitieslide. Alleen-lezen [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::MasterNotesSlide::get_DrawingGuides() override
```

## Opmerkingen



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF notesSize = pres->get_NotesSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_MasterNotesSlideManager()->SetDefaultMasterNotesSlide()->get_DrawingGuides();
// Adding the new horizontal drawing guide below the slide center
guides->Add(Orientation::Horizontal, notesSize.get_Height() / 2 + 50.0f);
pres->Save(u"MasterNotesDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Klasse [MasterNotesSlide](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)