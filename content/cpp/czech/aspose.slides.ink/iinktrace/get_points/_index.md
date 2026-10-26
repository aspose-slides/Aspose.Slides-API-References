---
title: get_Points()
second_title: Aspose.Slides pro C++ API Reference
description: "Získá body pro IInkLine System::Drawing::PointF pouze pro čtení."
type: docs
weight: 14
url: /cs/aspose.slides.ink/iinktrace/get_points/
---
## IInkTrace::get_Points() metoda


Získá body pro IInkLine [System::Drawing::PointF](../../../system.drawing/pointf/) pouze pro čtení.

```cpp
virtual System::ArrayPtr<System::Drawing::PointF> Aspose::Slides::Ink::IInkTrace::get_Points()=0
```

## Poznámky


Příklad: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::ArrayPtr<System::Drawing::PointF> points = traces[0]->get_Points();
```

## Viz také

* Definice typu [ArrayPtr](../../../system/arrayptr/)
* Třída [PointF](../../../system.drawing/pointf/)
* Třída [IInkTrace](../)
* Jmenný prostor [Aspose::Slides::Ink](../../)
* Knihovna [Aspose.Slides](../../../)