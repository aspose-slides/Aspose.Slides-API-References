---
title: get_DrawingGuides()
second_title: Aspose.Slides dla C++ – odniesienie do API
description: Zwraca kolekcję przewodników rysunkowych dla slajdu układu. Tylko do odczytu IDrawingGuidesCollection
type: docs
weight: 118
url: /pl/aspose.slides/layoutslide/get_drawingguides/
---
## LayoutSlide::get_DrawingGuides() metoda


Zwraca kolekcję przewodników rysunkowych dla slajdu układu. Tylko do odczytu [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::LayoutSlide::get_DrawingGuides() override
```

## Uwagi



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_LayoutSlide(0)->get_DrawingGuides();
// Dodawanie nowej pionowej linii prowadzącej po lewej stronie środka slajdu
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 - 20.0f);
pres->Save(u"LayoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Klasa [LayoutSlide](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)