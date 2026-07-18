---
title: get_Points()
second_title: Αναφορά API Aspose.Slides για C++
description: "Λαμβάνει σημεία για το IInkLine System::Drawing::PointF Μόνο ανάγνωση."
type: docs
weight: 14
url: /el/aspose.slides.ink/inktrace/get_points/
---
## InkTrace::get_Points() method

Λαμβάνει σημεία για το IInkLine [System::Drawing::PointF](../../../system.drawing/pointf/) Μόνο ανάγνωση.

```cpp
System::ArrayPtr<System::Drawing::PointF> Aspose::Slides::Ink::InkTrace::get_Points() override
```

## Παρατηρήσεις

Παράδειγμα:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::ArrayPtr<System::Drawing::PointF> points = traces[0]->get_Points();
```

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PointF](../../../system.drawing/pointf/)
* Class [InkTrace](../)
* Namespace [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)