---
title: get_DrawingGuides()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zwraca kolekcję przewodników rysunkowych dla slajdu notatek głównych. Tylko do odczytu IDrawingGuidesCollection
type: docs
weight: 27
url: /pl/aspose.slides/imasternotesslide/get_drawingguides/
---
## IMasterNotesSlide::get_DrawingGuides() metoda


Zwraca kolekcję przewodników rysunkowych dla slajdu notatek głównych. Tylko do odczytu [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::IMasterNotesSlide::get_DrawingGuides()=0
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
* Klasa [IMasterNotesSlide](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)