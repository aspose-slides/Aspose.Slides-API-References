---
title: get_Points()
second_title: Referencia de API de Aspose.Slides para C++
description: "Obtiene los puntos para el IInkLine System::Drawing::PointF de solo lectura."
type: docs
weight: 14
url: /es/aspose.slides.ink/iinktrace/get_points/
---
## IInkTrace::get_Points() método


Obtiene los puntos para el IInkLine [System::Drawing::PointF](../../../system.drawing/pointf/) de solo lectura.

```cpp
virtual System::ArrayPtr<System::Drawing::PointF> Aspose::Slides::Ink::IInkTrace::get_Points()=0
```

## Observaciones


Ejemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::ArrayPtr<System::Drawing::PointF> points = traces[0]->get_Points();
```

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [PointF](../../../system.drawing/pointf/)
* Clase [IInkTrace](../)
* Espacio de nombres [Aspose::Slides::Ink](../../)
* Biblioteca [Aspose.Slides](../../../)