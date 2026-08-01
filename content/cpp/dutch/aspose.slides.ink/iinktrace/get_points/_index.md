---
title: get_Points()
second_title: Aspose.Slides voor C++ API-referentie
description: "Verkrijgt punten voor de IInkLine System::Drawing::PointF Alleen-lezen."
type: docs
weight: 14
url: /nl/aspose.slides.ink/iinktrace/get_points/
---
## IInkTrace::get_Points() methode


Verkrijgt punten voor de IInkLine [System::Drawing::PointF](../../../system.drawing/pointf/) Alleen-lezen.

```cpp
virtual System::ArrayPtr<System::Drawing::PointF> Aspose::Slides::Ink::IInkTrace::get_Points()=0
```

## Opmerkingen


Voorbeeld:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::ArrayPtr<System::Drawing::PointF> points = traces[0]->get_Points();
```

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [PointF](../../../system.drawing/pointf/)
* Klasse [IInkTrace](../)
* Naamruimte [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)