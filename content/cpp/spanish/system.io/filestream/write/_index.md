---
title: Write()
second_title: Referencia de API de Aspose.Slides para C++
description: Escribe el subrango especificado de bytes del arreglo de bytes especificado al flujo.
type: docs
weight: 248
url: /es/system.io/filestream/write/
---
## FileStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método

Escribe el subrango especificado de bytes del arreglo de bytes especificado al flujo.

```cpp
void System::IO::FileStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | El arreglo que contiene los bytes a escribir. |
| offset | **int32_t** | Un índice basado en 0 del elemento en **buffer** en el que comienza el subrango a escribir. |
| count | **int32_t** | El número de elementos en el subrango a escribir. |

## FileStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) método

Escribe el subrango especificado de bytes del arreglo de bytes especificado al flujo.

```cpp
void System::IO::FileStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | La vista del arreglo que contiene los bytes a escribir. |
| offset | **int32_t** | Un índice basado en 0 del elemento en **buffer** en el que comienza el subrango a escribir. |
| count | **int32_t** | El número de elementos en el subrango a escribir. |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [FileStream](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)