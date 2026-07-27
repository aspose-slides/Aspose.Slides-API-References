---
title: get_InterruptionToken()
second_title: Referencia de API de Aspose.Slides para C++
description: El token para monitorizar solicitudes de interrupción.
type: docs
weight: 235
url: /es/aspose.slides/loadoptions/get_interruptiontoken/
---
## LoadOptions::get_InterruptionToken() método


El token para monitorizar solicitudes de interrupción.

```cpp
System::SharedPtr<IInterruptionToken> Aspose::Slides::LoadOptions::get_InterruptionToken() override
```

## Comentarios


Este token gestiona la vida útil completa de la instancia [IPresentation](../../ipresentation/). Cualquier operación de larga duración, como la carga o el guardado de una presentación, será interrumpida mediante la llamada al método [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) del [InterruptionTokenSource](../../interruptiontokensource/). 
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IInterruptionToken](../../iinterruptiontoken/)
* Clase [LoadOptions](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)