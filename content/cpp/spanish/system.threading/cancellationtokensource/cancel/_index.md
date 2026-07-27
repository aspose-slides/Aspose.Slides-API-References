---
title: Cancel()
second_title: Referencia de API de Aspose.Slides para C++
description: Comunica una solicitud de cancelación.
type: docs
weight: 40
url: /es/system.threading/cancellationtokensource/cancel/
---
## CancellationTokenSource::Cancel() método


Comunica una solicitud de cancelación.

```cpp
void System::Threading::CancellationTokenSource::Cancel()
```

## Observaciones



Todas las funciones de devolución de llamada registradas serán invocadas. 

Las llamadas posteriores a [get_IsCancellationRequested()](../get_iscancellationrequested/) devolverán true. 

Las funciones de devolución de llamada se ejecutan de forma síncrona durante esta llamada. 

## Ver también

* Clase [CancellationTokenSource](../)
* Espacio de nombres [System::Threading](../../)
* Biblioteca [Aspose.Slides](../../../)