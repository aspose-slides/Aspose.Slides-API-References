---
title: Write()
second_title: Referencia de API de Aspose.Slides para C++
description: Escribe el subrango especificado de bytes del arreglo de bytes especificado al flujo.
type: docs
weight: 92
url: /es/system.io/memorystream/write/
---
## MemoryStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método

Escribe el subrango especificado de bytes del arreglo de bytes especificado al flujo.

```cpp
void System::IO::MemoryStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | El arreglo que contiene los bytes a escribir |
| offset | **int32_t** | Un índice basado en 0 del elemnet en **buffer** en el que comienza el subrango a escribir |
| count | **int32_t** | El número de elementos en el subrango a escribir |

## MemoryStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) método

Escribe el subrango especificado de bytes del arreglo de bytes especificado al flujo.

```cpp
void System::IO::MemoryStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | La vista del arreglo que contiene los bytes a escribir |
| offset | **int32_t** | Un índice basado en 0 del elemnet en **buffer** en el que comienza el subrango a escribir |
| count | **int32_t** | El número de elementos en el subrango a escribir |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [MemoryStream](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)