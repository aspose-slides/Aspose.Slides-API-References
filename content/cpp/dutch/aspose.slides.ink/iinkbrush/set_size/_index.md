---
title: set_Size()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de penseelgrootte voor een lijn in punten in.
type: docs
weight: 40
url: /nl/aspose.slides.ink/iinkbrush/set_size/
---
## IInkBrush::set_Size(System::Drawing::SizeF) method


Stelt de penseelgrootte voor een lijn in punten in.

```cpp
virtual void Aspose::Slides::Ink::IInkBrush::set_Size(System::Drawing::SizeF value)=0
```

## Opmerkingen


Voorbeeld: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::SizeF brushSize = brush->get_Size();
brush->set_Size(System::Drawing::SizeF(5.0f, 10.0f));
```

## Zie ook

* Klasse [SizeF](../../../system.drawing/sizef/)
* Klasse [IInkBrush](../)
* Namespace [Aspose::Slides::Ink](../../)
* Bibliotheek [Aspose.Slides](../../../)