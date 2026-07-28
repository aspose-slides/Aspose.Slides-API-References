---
title: get_Points()
second_title: Aspose.Slides C++ API referenciája
description: "Az IInkLine System::Drawing::PointF pontjait adja vissza csak olvasható módon."
type: docs
weight: 14
url: /hu/aspose.slides.ink/iinktrace/get_points/
---
## IInkTrace::get_Points() metódus


Az IInkLine [System::Drawing::PointF](../../../system.drawing/pointf/) pontjait adja vissza csak olvasható.

```cpp
virtual System::ArrayPtr<System::Drawing::PointF> Aspose::Slides::Ink::IInkTrace::get_Points()=0
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

* Típusdefiníció [ArrayPtr](../../../system/arrayptr/)
* Osztály [PointF](../../../system.drawing/pointf/)
* Osztály [IInkTrace](../)
* Névtér [Aspose::Slides::Ink](../../)
* Könyvtár [Aspose.Slides](../../../)