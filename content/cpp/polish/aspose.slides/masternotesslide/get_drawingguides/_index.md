---
title: get_DrawingGuides()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Zwraca kolekcję prowadnic rysunkowych dla slajdu notatek głównych. Tylko do odczytu IDrawingGuidesCollection
type: docs
weight: 66
url: /pl/aspose.slides/masternotesslide/get_drawingguides/
---
## MasterNotesSlide::get_DrawingGuides() metoda

Zwraca kolekcję prowadnic rysunkowych dla slajdu notatek głównych. Tylko do odczytu [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::MasterNotesSlide::get_DrawingGuides() override
```

## Uwagi


```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF notesSize = pres->get_NotesSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_MasterNotesSlideManager()->SetDefaultMasterNotesSlide()->get_DrawingGuides();
// Adding the new horizontal drawing guide below the slide center
guides->Add(Orientation::Horizontal, notesSize.get_Height() / 2 + 50.0f);
pres->Save(u"MasterNotesDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Klasa [MasterNotesSlide](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)