---
title: get_Points()
second_title: Aspose.Slides für C++ API-Referenz
description: "Liest Punkte für die IInkLine System::Drawing::PointF Nur-Lesen."
type: docs
weight: 14
url: /de/aspose.slides.ink/inktrace/get_points/
---
## InkTrace::get_Points() Methode

Liest Punkte für die IInkLine [System::Drawing::PointF](../../../system.drawing/pointf/) Nur-Lesen.

```cpp
System::ArrayPtr<System::Drawing::PointF> Aspose::Slides::Ink::InkTrace::get_Points() override
```

## Anmerkungen


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
* Klasse [InkTrace](../)
* Namensraum [Aspose::Slides::Ink](../../)
* Bibliothek [Aspose.Slides](../../../)