---
title: Read()
second_title: Referencia de la API de Aspose.Slides para C++
description: Lee la cantidad especificada de bytes del flujo y los escribe en el array de bytes especificado.
type: docs
weight: 144
url: /es/system.io/unmanagedmemorystream/read/
---
## UnmanagedMemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método

Lee la cantidad especificada de bytes del flujo y los escribe en el array de bytes especificado.

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | El array de bytes donde escribir los bytes leídos |
| offset | **int32_t** | Una posición basada en cero en **buffer** donde comenzar a escribir |
| count | **int32_t** | El número de bytes a leer |

### Valor de retorno

El número de bytes leídos

## UnmanagedMemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) método

Lee la cantidad especificada de bytes del flujo y los escribe en el array de bytes especificado.

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | La vista del array de bytes donde escribir los bytes leídos |
| offset | **int32_t** | Una posición basada en cero en **buffer** donde comenzar a escribir |
| count | **int32_t** | El número de bytes a leer |

### Valor de retorno

El número de bytes leídos

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [UnmanagedMemoryStream](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)