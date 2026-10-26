---
title: get_Points()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Získá body pro IInkLine System::Drawing::PointF pouze pro čtení."
type: docs
weight: 14
url: /cs/aspose.slides.ink/inktrace/get_points/
---
## InkTrace::get_Points() metoda

Získá body pro IInkLine [System::Drawing::PointF](../../../system.drawing/pointf/) pouze pro čtení.

```cpp
System::ArrayPtr<System::Drawing::PointF> Aspose::Slides::Ink::InkTrace::get_Points() override
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

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [PointF](../../../system.drawing/pointf/)
* Třída [InkTrace](../)
* Jmenný prostor [Aspose::Slides::Ink](../../)
* Knihovna [Aspose.Slides](../../../)