---
title: WriteAsync()
second_title: Referencia de API de Aspose.Slides para C++
description: Escribe de forma asíncrona una secuencia de bytes en el flujo actual, avanza la posición actual dentro de este flujo en la cantidad de bytes escritos y monitoriza las solicitudes de cancelación.
type: docs
weight: 261
url: /es/system.io/filestream/writeasync/
---
## FileStream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) method

Escribe de forma asíncrona una secuencia de bytes en el flujo actual, avanza la posición actual dentro de este flujo en la cantidad de bytes escritos y monitoriza las solicitudes de cancelación.

```cpp
TaskPtr System::IO::FileStream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | El arreglo que contiene los bytes a escribir. |
| offset | **int32_t** | Un índice basado en 0 del elemento en **buffer** donde comienza el subrango a escribir. |
| count | **int32_t** | El número de elementos en el subrango a escribir. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | El token para monitorizar las solicitudes de cancelación. |

### Valor devuelto

Una tarea que representa la operación de escritura asíncrona.

## Ver también

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [CancellationToken](../../../system.threading/cancellationtoken/)
* Clase [FileStream](../)
* Espacio de nombres [System::IO](../../)
* Library [Aspose.Slides](../../../)