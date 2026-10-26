---
title: get_Brush()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt Brush op voor de IInkLine IInkBrush Alleen-lezen.
type: docs
weight: 1
url: /nl/aspose.slides.ink/inktrace/get_brush/
---
## InkTrace::get_Brush() methode

Haalt Brush op voor de IInkLine [IInkBrush](../../iinkbrush/) Alleen-lezen.

```cpp
System::SharedPtr<IInkBrush> Aspose::Slides::Ink::InkTrace::get_Brush() override
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
* Klasse [InkTrace](../)
* Naamruimte [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)