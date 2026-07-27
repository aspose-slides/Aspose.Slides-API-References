---
title: Read()
second_title: Referencia de la API de Aspose.Slides para C++
description: Lee la cantidad especificada de bytes del flujo y los escribe en el arreglo de bytes especificado.
type: docs
weight: 27
url: /es/system.io/stream/read/
---
## Stream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método

Lee la cantidad especificada de bytes del flujo y los escribe en el arreglo de bytes especificado.

```cpp
virtual int32_t System::IO::Stream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | El arreglo de bytes donde se escribirán los bytes leídos |
| offset | **int32_t** | Una posición basada en 0 en **buffer** donde comenzar a escribir |
| count | **int32_t** | El número de bytes a leer |

### Valor de retorno

El número de bytes leídos

## Stream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) método

Lee la cantidad especificada de bytes del flujo y los escribe en el arreglo de bytes especificado.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | La vista del arreglo de bytes donde se escribirán los bytes leídos |
| offset | **int32_t** | Una posición basada en 0 en **buffer** donde comenzar a escribir |
| count | **int32_t** | El número de bytes a leer |

### Valor de retorno

El número de bytes leídos

## Stream::Read(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) método

Lee la cantidad especificada de bytes del flujo y los escribe en el arreglo de bytes especificado.

```cpp
template<std::size_t> int32_t System::IO::Stream::Read(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| N | El tamaño del arreglo de pila |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | El arreglo de pila de bytes donde se escribirán los bytes leídos |
| offset | **int32_t** | Una posición basada en 0 en **buffer** donde comenzar a escribir |
| count | **int32_t** | El número de bytes a leer |

### Valor de retorno

El número de bytes leídos

## Stream::Read(const System::Span\<uint8_t\>\&) método

Lee la cantidad especificada de bytes del flujo y los escribe en el span de bytes especificado.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Span<uint8_t> &buffer)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [System::Span](../../../system/span/)\<**uint8_t**\>\& | El span de bytes donde se escribirán los bytes leídos |

### Valor de retorno

El número de bytes leídos

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [Stream](../)
* Clase [Span](../../../system/span/)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)