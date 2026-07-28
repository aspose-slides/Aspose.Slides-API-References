---
title: get_Points()
second_title: Aspose.Slides for C++ API-referencia
description: "Visszaadja a IInkLine System::Drawing::PointF pontjait. Csak olvasható."
type: docs
weight: 14
url: /hu/aspose.slides.ink/inktrace/get_points/
---
## InkTrace::get_Points() metódus


Visszaadja a IInkLine [System::Drawing::PointF](../../../system.drawing/pointf/) pontjait. Csak olvasható.

```cpp
System::ArrayPtr<System::Drawing::PointF> Aspose::Slides::Ink::InkTrace::get_Points() override
```

## Megjegyzések


Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::ArrayPtr<System::Drawing::PointF> points = traces[0]->get_Points();
```

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [PointF](../../../system.drawing/pointf/)
* Osztály [InkTrace](../)
* Névterület [Aspose::Slides::Ink](../../)
* Könyvtár [Aspose.Slides](../../../)