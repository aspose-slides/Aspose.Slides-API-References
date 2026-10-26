---
title: get_DrawingGuides()
second_title: Aspose.Slides dla C++ – referencja API
description: Zwraca kolekcję przewodników rysowania dla slajdu głównego. Tylko do odczytu IDrawingGuidesCollection
type: docs
weight: 170
url: /pl/aspose.slides/masterslide/get_drawingguides/
---
## MasterSlide::get_DrawingGuides() metoda


Zwraca kolekcję przewodników rysowania dla slajdu głównego. Tylko do odczytu [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::MasterSlide::get_DrawingGuides() override
```

## Uwagi



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_Master(0)->get_DrawingGuides();
// Dodawanie nowego pionowego przewodnika rysowania po prawej od środka slajdu
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 20.0f);
pres->Save(u"MasterSlideDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Klasa [MasterSlide](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)