---
title: set_InterruptionToken()
second_title: Referencia de la API de Aspose.Slides para C++
description: El token para monitorizar solicitudes de interrupción.
type: docs
weight: 248
url: /es/aspose.slides/loadoptions/set_interruptiontoken/
---
## LoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) método

El token para monitorizar solicitudes de interrupción.

```cpp
void Aspose::Slides::LoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value) override
```

## Observaciones

Este token gestiona la vida completa de la instancia [IPresentation](../../ipresentation/). Cualquier operación prolongada, como cargar o guardar una presentación, será interrumpida mediante la llamada al método [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) del [InterruptionTokenSource](../../interruptiontokensource/).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IInterruptionToken](../../iinterruptiontoken/)
* Clase [LoadOptions](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)