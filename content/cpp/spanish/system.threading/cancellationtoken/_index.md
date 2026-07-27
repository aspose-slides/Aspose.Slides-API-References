---
title: CancellationToken
second_title: Referencia de API de Aspose.Slides para C++
description: Propaga la notificación de que las operaciones deben cancelarse. Esta clase proporciona un mecanismo para la cancelación cooperativa entre hilos, permitiendo que un hilo notifique a otros que una operación debe cancelarse.
type: docs
weight: 14
url: /es/system.threading/cancellationtoken/
---
## CancellationToken clase

Propaga la notificación de que las operaciones deben cancelarse. Esta clase proporciona un mecanismo para la cancelación cooperativa entre hilos, permitiendo que un hilo notifique a otros que una operación debe cancelarse.

```cpp
class CancellationToken : public System::Details::BoxableObjectBase
```

## Métodos

| Método | Descripción |
| --- | --- |
|  [CancellationToken](./cancellationtoken/)() | Constructor predeterminado. |
| **bool** [get_CanBeCanceled](./get_canbecanceled/)() const | Obtiene si este token es capaz de estar en el estado cancelado. |
| **bool** [get_IsCancellationRequested](./get_iscancellationrequested/)() const | Obtiene si se ha solicitado la cancelación para este token. |
| static [CancellationToken](./) [get_None](./get_none/)() | Devuelve un valor [System::Threading::CancellationToken](./) vacío. |
| [CancellationTokenRegistration](../cancellationtokenregistration/) [Register](./register/)(const [Action](../../system/action/)<>\&) const | Registra una devolución de llamada que será invocada cuando se solicite la cancelación. |
| void [ThrowIfCancellationRequested](./throwifcancellationrequested/)() const | Lanza una OperationCanceledException si se ha solicitado la cancelación. |
## Observaciones

Un [CancellationToken](./) solo puede cancelarse a través de su [CancellationTokenSource](../cancellationtokensource/) asociado. 

## Ver también

* Espacio de nombres [System::Threading](../)
* Biblioteca [Aspose.Slides](../../)