---
title: CancellationTokenRegistration
second_title: Referencia de la API de Aspose.Slides para C++
description: Representa un registro para una devolución de llamada de token de cancelación.
type: docs
weight: 27
url: /es/system.threading/cancellationtokenregistration/
---
## CancellationTokenRegistration clase


Representa un registro para una devolución de llamada de token de cancelación.

```cpp
class CancellationTokenRegistration
```

## Métodos

| Método | Descripción |
| --- | --- |
| void [Dispose](./dispose/)() | Descarta el registro y elimina la devolución de llamada del [CancellationTokenSource](../cancellationtokensource/) asociado. Después de llamar a este método, la devolución de llamada registrada ya no se invocará cuando el [CancellationTokenSource](../cancellationtokensource/) asociado se cancele. |
## Observaciones


Esta clase permite la anulación del registro de una devolución de llamada de un token de cancelación. Cuando se descarta, elimina la devolución de llamada del [CancellationTokenSource](../cancellationtokensource/) asociado. 
Esta clase no debe crearse directamente - se devuelve mediante los métodos de registro [CancellationToken](../cancellationtoken/). 

## Ver también

* Espacio de nombres [System::Threading](../)
* Biblioteca [Aspose.Slides](../../)