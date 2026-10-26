---
title: get_Points()
second_title: Aspose.Slides für C++ API-Referenz
description: "Ermittelt Punkte für die IInkLine System::Drawing::PointF Nur-Lesen."
type: docs
weight: 14
url: /de/aspose.slides.ink/iinktrace/get_points/
---
## IInkTrace::get_Points() Methode


Ermittelt Punkte für die IInkLine [System::Drawing::PointF](../../../system.drawing/pointf/) Nur-Lesen.

```cpp
virtual System::ArrayPtr<System::Drawing::PointF> Aspose::Slides::Ink::IInkTrace::get_Points()=0
```

## Bemerkungen


Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::ArrayPtr<System::Drawing::PointF> points = traces[0]->get_Points();
```

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [PointF](../../../system.drawing/pointf/)
* Klasse [IInkTrace](../)
* Namensraum [Aspose::Slides::Ink](../../)
* Bibliothek [Aspose.Slides](../../../)