---
title: get_DrawingGuides()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Zwraca kolekcję przewodników rysowania. Tylko do odczytu IDrawingGuidesCollection
type: docs
weight: 53
url: /pl/aspose.slides/icommonslideviewproperties/get_drawingguides/
---
## ICommonSlideViewProperties::get_DrawingGuides() metoda


Zwraca kolekcję przewodników rysowania. Tylko do odczytu [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::ICommonSlideViewProperties::get_DrawingGuides()=0
```

## Uwagi


Poniższy przykładowy kod pokazuje, jak dodać nowe przewodniki rysowania w prezentacji PowerPoint. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();

System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_ViewProperties()->get_SlideViewProperties()->get_DrawingGuides();
// Dodawanie nowego pionowego przewodnika rysowania po prawej stronie środka slajdu
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 12.5f);
// Dodawanie nowego poziomego przewodnika rysowania poniżej środka slajdu
guides->Add(Orientation::Horizontal, slideSize.get_Height() / 2 + 12.5f);

pres->Save(u"DrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Klasa [ICommonSlideViewProperties](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)