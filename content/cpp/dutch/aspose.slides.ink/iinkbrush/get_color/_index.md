---
title: get_Color()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de kwastkleur op voor een lijn.
type: docs
weight: 1
url: /nl/aspose.slides.ink/iinkbrush/get_color/
---
## IInkBrush::get_Color() methode

Haalt de kwastkleur op voor een lijn.

```cpp
virtual System::Drawing::Color Aspose::Slides::Ink::IInkBrush::get_Color()=0
```

## Opmerkingen

Voorbeeld:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::Color brushColor = brush->get_Color();
brush->set_Color(System::Drawing::Color::get_Red());
```

## Zie ook

* Klasse [Color](../../../system.drawing/color/)
* Klasse [IInkBrush](../)
* Naamruimte [Aspose::Slides::Ink](../../)
* Bibliotheek [Aspose.Slides](../../../)