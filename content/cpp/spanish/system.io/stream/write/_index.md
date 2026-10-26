---
title: Write()
second_title: Referencia de API de Aspose.Slides para C++
description: Escribe el subrango especificado de bytes del array de bytes especificado en el flujo.
type: docs
weight: 53
url: /es/system.io/stream/write/
---
## Stream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método

Escribe el subrango especificado de bytes del array de bytes especificado en el flujo.

```cpp
virtual void System::IO::Stream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | El array que contiene los bytes a escribir |
| offset | **int32_t** | Un índice basado en cero del elemento en **buffer** en el que comienza el subrango a escribir |
| count | **int32_t** | El número de elementos en el subrango a escribir |

## Stream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) método

Escribe el subrango especificado de bytes del array de bytes especificado en el flujo.

```cpp
virtual void System::IO::Stream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | La vista del array que contiene los bytes a escribir |
| offset | **int32_t** | Un índice basado en cero del elemento en **buffer** en el que comienza el subrango a escribir |
| count | **int32_t** | El número de elementos en el subrango a escribir |

## Stream::Write(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) método

Escribe el subrango especificado de bytes del array de bytes especificado en el flujo.

```cpp
template<std::size_t> void System::IO::Stream::Write(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| N | El tamaño del array de pila |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | El array de pila que contiene los bytes a escribir |
| offset | **int32_t** | Un índice basado en cero del elemento en **buffer** en el que comienza el subrango a escribir |
| count | **int32_t** | El número de elementos en el subrango a escribir |

## Stream::Write(const System::ReadOnlySpan\<uint8_t\>\&) método

Escribe el subrango especificado de bytes del span de bytes especificado en el flujo.

```cpp
virtual void System::IO::Stream::Write(const System::ReadOnlySpan<uint8_t> &buffer)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [System::ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | El span de bytes del cual leer los bytes escritos |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [Stream](../)
* Clase [ReadOnlySpan](../../../system/readonlyspan/)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)