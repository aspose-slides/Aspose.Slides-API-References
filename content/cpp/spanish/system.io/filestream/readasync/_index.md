---
title: ReadAsync()
second_title: Referencia de API de Aspose.Slides para C++
description: Lee de forma asíncrona una secuencia de bytes del flujo actual, avanza la posición dentro del flujo en función del número de bytes leídos y supervisa las solicitudes de cancelación.
type: docs
weight: 196
url: /es/system.io/filestream/readasync/
---
## FileStream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) método

Lee de forma asíncrona una secuencia de bytes del flujo actual, avanza la posición dentro del flujo en función del número de bytes leídos y supervisa las solicitudes de cancelación.

```cpp
RTaskPtr<int32_t> System::IO::FileStream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | La matriz de bytes donde escribir los bytes leídos. |
| offset | **int32_t** | Una posición basada en 0 en **buffer** donde comenzar a escribir. |
| count | **int32_t** | El número de bytes a leer. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | El token para monitorizar solicitudes de cancelación. |

### Valor devuelto

Una tarea que representa la operación de lectura asíncrona. El valor del parámetro TResult contiene el número total de bytes leídos en el búfer. El valor resultante puede ser menor que el número de bytes solicitado si la cantidad de bytes actualmente disponible es menor que la solicitada, o puede ser 0 (cero) si se ha alcanzado el final del flujo.

## Véase también

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [CancellationToken](../../../system.threading/cancellationtoken/)
* Clase [FileStream](../)
* Espacio de nombres [System::IO](../../)
* Library [Aspose.Slides](../../../)