---
title: get_DrawingGuides()
second_title: Aspose.Slides dla C++ Referencja API
description: Zwraca kolekcję prowadnic rysunkowych dla slajdu głównego. Tylko do odczytu IDrawingGuidesCollection
type: docs
weight: 105
url: /pl/aspose.slides/imasterslide/get_drawingguides/
---
## IMasterSlide::get_DrawingGuides() metoda


Zwraca kolekcję prowadnic rysunkowych dla slajdu głównego. Tylko do odczytu [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::IMasterSlide::get_DrawingGuides()=0
```

## Uwagi



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_Master(0)->get_DrawingGuides();
// Dodawanie nowej pionowej prowadnicy rysunkowej po prawej stronie środka slajdu
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 20.0f);
pres->Save(u"MasterSlideDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Klasa [IMasterSlide](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)