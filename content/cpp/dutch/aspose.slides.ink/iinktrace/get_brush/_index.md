---
title: get_Brush()
second_title: Aspose.Slides voor C++ API-referentie
description: Verkrijgt Brush voor de IInkLine IInkBrush Alleen-lezen.
type: docs
weight: 1
url: /nl/aspose.slides.ink/iinktrace/get_brush/
---
## IInkTrace::get_Brush() method

Verkrijgt Brush voor de IInkLine [IInkBrush](../../iinkbrush/) Alleen-lezen.

```cpp
virtual System::SharedPtr<IInkBrush> Aspose::Slides::Ink::IInkTrace::get_Brush()=0
```

## Opmerkingen

Voorbeeld:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IInkBrush](../../iinkbrush/)
* Klasse [IInkTrace](../)
* Naamruimte [Aspose::Slides::Ink](../../)
* Bibliotheek [Aspose.Slides](../../../)