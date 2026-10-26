---
title: Read()
second_title: Referencia de API de Aspose.Slides para C++
description: Lee el número especificado de bytes del flujo y los escribe en el array de bytes especificado.
type: docs
weight: 79
url: /es/system.io/memorystream/read/
---
## MemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Lee el número especificado de bytes del flujo y los escribe en el array de bytes especificado.

```cpp
int32_t System::IO::MemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | El array de bytes donde escribir los bytes leídos |
| offset | **int32_t** | Una posición basada en cero en **buffer** donde comenzar a escribir |
| count | **int32_t** | El número de bytes a leer |

### Valor devuelto

El número de bytes leídos

## MemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Lee el número especificado de bytes del flujo y los escribe en el array de bytes especificado.

```cpp
int32_t System::IO::MemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | La vista del array de bytes donde escribir los bytes leídos |
| offset | **int32_t** | Una posición basada en cero en **buffer** donde comenzar a escribir |
| count | **int32_t** | El número de bytes a leer |

### Valor devuelto

El número de bytes leídos

## Véase también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [MemoryStream](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)