---
title: set_InterruptionToken()
second_title: Referencia de API de Aspose.Slides para C++
description: El token para supervisar las solicitudes de interrupción.
type: docs
weight: 248
url: /es/aspose.slides/iloadoptions/set_interruptiontoken/
---
## ILoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) método

El token para supervisar las solicitudes de interrupción.

```cpp
virtual void Aspose::Slides::ILoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value)=0
```

## Observaciones

Este token gestiona toda la vida útil de la instancia [IPresentation](../../ipresentation/). Cualquier operación de larga duración, como la carga o el guardado de presentaciones, será interrumpida mediante la llamada al método [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) del [IInterruptionTokenSource](../../iinterruptiontokensource/).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IInterruptionToken](../../iinterruptiontoken/)
* Clase [ILoadOptions](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)