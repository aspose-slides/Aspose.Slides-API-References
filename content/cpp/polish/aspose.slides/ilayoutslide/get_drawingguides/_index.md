---
title: get_DrawingGuides()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zwraca kolekcję prowadnic rysowania dla slajdu układu. Tylko do odczytu IDrawingGuidesCollection
type: docs
weight: 79
url: /pl/aspose.slides/ilayoutslide/get_drawingguides/
---
## ILayoutSlide::get_DrawingGuides() metoda


Zwraca kolekcję prowadnic rysowania dla slajdu układu. Tylko do odczytu [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::ILayoutSlide::get_DrawingGuides()=0
```

## Uwagi



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_LayoutSlide(0)->get_DrawingGuides();
// Dodawanie nowej pionowej prowadnicy rysowania po lewej stronie środka slajdu
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 - 20.0f);
pres->Save(u"LayoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Klasa [ILayoutSlide](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)