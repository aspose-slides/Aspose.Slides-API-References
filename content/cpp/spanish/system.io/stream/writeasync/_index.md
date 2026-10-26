---
title: WriteAsync()
second_title: Referencia de la API de Aspose.Slides para C++
description: Escribe de forma asíncrona una secuencia de bytes en el flujo actual, avanza la posición actual dentro de este flujo en la cantidad de bytes escritos y supervisa las solicitudes de cancelación.
type: docs
weight: 66
url: /es/system.io/stream/writeasync/
---
## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) método

Escribe de forma asíncrona una secuencia de bytes en el flujo actual, avanza la posición actual dentro de este flujo en la cantidad de bytes escritos y supervisa las solicitudes de cancelación.

```cpp
virtual TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | El arreglo que contiene los bytes a escribir. |
| offset | **int32_t** | Un índice basado en cero del elemento en **buffer** en el que comienza el subrango a escribir. |
| count | **int32_t** | El número de elementos en el subrango a escribir. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | El token para supervisar las solicitudes de cancelación. |

### Valor devuelto

Una tarea que representa la operación de escritura asíncrona.

## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método

Escribe de forma asíncrona una secuencia de bytes en el flujo actual, avanza la posición actual dentro de este flujo en la cantidad de bytes escritos y supervisa las solicitudes de cancelación.

```cpp
TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | El arreglo que contiene los bytes a escribir. |
| offset | **int32_t** | Un índice basado en cero del elemento en **buffer** en el que comienza el subrango a escribir. |
| count | **int32_t** | El número de elementos en el subrango a escribir. |

### Valor devuelto

Una tarea que representa la operación de escritura asíncrona.

## Ver también

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [CancellationToken](../../../system.threading/cancellationtoken/)
* Clase [Stream](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)