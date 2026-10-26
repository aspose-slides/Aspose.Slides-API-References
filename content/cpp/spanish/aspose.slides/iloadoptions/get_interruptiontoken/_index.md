---
title: get_InterruptionToken()
second_title: Referencia de API de Aspose.Slides para C++
description: El token para supervisar solicitudes de interrupción.
type: docs
weight: 235
url: /es/aspose.slides/iloadoptions/get_interruptiontoken/
---
## ILoadOptions::get_InterruptionToken() método


El token para supervisar solicitudes de interrupción.

```cpp
virtual System::SharedPtr<IInterruptionToken> Aspose::Slides::ILoadOptions::get_InterruptionToken()=0
```

## Observaciones


Este token gestiona la vida útil completa de la instancia [IPresentation](../../ipresentation/). Cualquier operación de larga duración, como la carga o el guardado de una presentación, será interrumpida mediante la llamada al método [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) del [IInterruptionTokenSource](../../iinterruptiontokensource/). 
## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IInterruptionToken](../../iinterruptiontoken/)
* Clase [ILoadOptions](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)