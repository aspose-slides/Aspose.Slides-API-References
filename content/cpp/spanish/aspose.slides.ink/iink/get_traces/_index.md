---
title: get_Traces()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene todas las trazas contenidas en el elemento IInk IInkTrace. Solo lectura.
type: docs
weight: 1
url: /es/aspose.slides.ink/iink/get_traces/
---
## IInk::get_Traces() método

Obtiene todas las trazas contenidas en el elemento [IInk](../) [IInkTrace](../../iinktrace/). Solo lectura.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::IInk::get_Traces()=0
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
* Clase [IInk](../)
* Espacio de nombres [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)