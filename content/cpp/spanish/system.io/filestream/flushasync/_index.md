---
title: FlushAsync()
second_title: Referencia de la API de Aspose.Slides para C++
description: Borra de forma asíncrona todos los buffers de este flujo, hace que cualquier dato almacenado en el búfer se escriba en el dispositivo subyacente y supervisa las solicitudes de cancelación.
type: docs
weight: 157
url: /es/system.io/filestream/flushasync/
---
## FileStream::FlushAsync(const Threading::CancellationToken\&) método

Borra de forma asíncrona todos los buffers de este flujo, hace que cualquier dato almacenado en búfer se escriba en el dispositivo subyacente y supervisa las solicitudes de cancelación.

```cpp
TaskPtr System::IO::FileStream::FlushAsync(const Threading::CancellationToken &cancellationToken) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | El token para supervisar las solicitudes de cancelación. |

### Valor de retorno

Una tarea que representa la operación de vaciado asíncrona.

## Véase también

* Typedef [TaskPtr](../../../system/taskptr/)
* Clase [CancellationToken](../../../system.threading/cancellationtoken/)
* Clase [FileStream](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)