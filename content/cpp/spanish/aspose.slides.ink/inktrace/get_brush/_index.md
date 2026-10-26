---
title: get_Brush()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene Brush para el IInkLine IInkBrush solo lectura.
type: docs
weight: 1
url: /es/aspose.slides.ink/inktrace/get_brush/
---
## InkTrace::get_Brush() método


Obtiene Brush para el IInkLine [IInkBrush](../../iinkbrush/) solo lectura.

```cpp
System::SharedPtr<IInkBrush> Aspose::Slides::Ink::InkTrace::get_Brush() override
```

## Observaciones


Ejemplo:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IInkBrush](../../iinkbrush/)
* Clase [InkTrace](../)
* Espacio de nombres [Aspose::Slides::Ink](../../)
* Biblioteca [Aspose.Slides](../../../)