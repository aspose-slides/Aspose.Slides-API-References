---
title: get_DrawingGuides()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Zwraca kolekcję przewodników rysowania. Tylko do odczytu IDrawingGuidesCollection
type: docs
weight: 53
url: /pl/aspose.slides/commonslideviewproperties/get_drawingguides/
---
## CommonSlideViewProperties::get_DrawingGuides() metoda


Zwraca kolekcję przewodników rysowania. Tylko do odczytu [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::CommonSlideViewProperties::get_DrawingGuides() override
```

## Uwagi


Poniższy przykładowy kod pokazuje, jak dodać nowe przewodniki rysowania w prezentacji PowerPoint. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF slideSize = pres->get_SlideSize()->get_Size();

System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_ViewProperties()->get_SlideViewProperties()->get_DrawingGuides();
// Dodawanie nowego pionowego przewodnika rysunkowego po prawej stronie środka slajdu
guides->Add(Orientation::Vertical, slideSize.get_Width() / 2 + 12.5f);
// Dodawanie nowego poziomego przewodnika rysunkowego poniżej środka slajdu
guides->Add(Orientation::Horizontal, slideSize.get_Height() / 2 + 12.5f);

pres->Save(u"DrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Class [CommonSlideViewProperties](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)