---
title: FlushAsync()
second_title: Referencia de API de Aspose.Slides para C++
description: Borra de forma asíncrona todos los búferes de este flujo, hace que los datos almacenados en búfer se escriban en el dispositivo subyacente y monitoriza las solicitudes de cancelación.
type: docs
weight: 118
url: /es/system.io/stream/flushasync/
---
## Stream::FlushAsync(const Threading::CancellationToken\&) método

Borra de forma asíncrona todos los búferes de este flujo, hace que los datos almacenados en búfer se escriban en el dispositivo subyacente y monitoriza las solicitudes de cancelación.

```cpp
virtual TaskPtr System::IO::Stream::FlushAsync(const Threading::CancellationToken &cancellationToken)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | El token que se monitoriza para detectar solicitudes de cancelación. |

### Valor devuelto

La tarea que representa la operación de vaciado asíncrono.

## Stream::FlushAsync() método

Borra de forma asíncrona todos los búferes de este flujo, hace que los datos almacenados en búfer se escriban en el dispositivo subyacente y monitoriza las solicitudes de cancelación.

```cpp
TaskPtr System::IO::Stream::FlushAsync()
```

### Valor devuelto

La tarea que representa la operación de vaciado asíncrono.

## Ver también

* Typedef [TaskPtr](../../../system/taskptr/)
* Clase [CancellationToken](../../../system.threading/cancellationtoken/)
* Clase [Stream](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)