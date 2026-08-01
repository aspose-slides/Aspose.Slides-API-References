---
title: get_Size()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de penseelgrootte voor een lijn op in punten.
type: docs
weight: 27
url: /nl/aspose.slides.ink/iinkbrush/get_size/
---
## IInkBrush::get_Size() methode


Haalt de penseelgrootte voor een lijn op in punten.

```cpp
virtual System::Drawing::SizeF Aspose::Slides::Ink::IInkBrush::get_Size()=0
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
* Naamruimte [Aspose::Slides::Ink](../../)
* Bibliotheek [Aspose.Slides](../../../)