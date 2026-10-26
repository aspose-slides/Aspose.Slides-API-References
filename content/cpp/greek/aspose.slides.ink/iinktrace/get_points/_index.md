---
title: get_Points()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Αποκτά σημεία για το IInkLine System::Drawing::PointF Μόνο ανάγνωση."
type: docs
weight: 14
url: /el/aspose.slides.ink/iinktrace/get_points/
---
## IInkTrace::get_Points() μέθοδος


Λαμβάνει σημεία για το IInkLine [System::Drawing::PointF](../../../system.drawing/pointf/) Μόνο ανάγνωση.

```cpp
virtual System::ArrayPtr<System::Drawing::PointF> Aspose::Slides::Ink::IInkTrace::get_Points()=0
```

## Σχόλια


Παράδειγμα:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::ArrayPtr<System::Drawing::PointF> points = traces[0]->get_Points();
```

## Δείτε επίσης

* Ορισμός τύπου [ArrayPtr](../../../system/arrayptr/)
* Κλάση [PointF](../../../system.drawing/pointf/)
* Κλάση [IInkTrace](../)
* Χώρος ονομάτων [Aspose::Slides::Ink](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)