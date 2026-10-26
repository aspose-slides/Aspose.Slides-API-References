---
title: get_Traces()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene todas las trazas contenidas en el elemento IInk IInkTrace. Solo lectura.
type: docs
weight: 1
url: /es/aspose.slides.ink/ink/get_traces/
---
## Ink::get_Traces() método

Obtiene todas las trazas que contiene el elemento [IInk](../../iink/) [IInkTrace](../../iinktrace/). Sólo lectura.

```cpp
System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::Ink::get_Traces() override
```

## Observaciones

Ejemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<Aspose::Slides::Ink::IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
```

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IInkTrace](../../iinktrace/)
* Clase [Ink](../)
* Espacio de nombres [Aspose::Slides::Ink](../../)
* Biblioteca [Aspose.Slides](../../../)