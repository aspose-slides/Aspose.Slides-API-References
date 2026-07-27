---
title: AsSpan()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea un span a partir de una matriz.
type: docs
weight: 1
url: /es/system.memoryextensions/asspan/
---
## System::MemoryExtensions::AsSpan(const ArrayPtr\<T\>\&, int32_t, int32_t) function


Crea un span a partir de una matriz.

```cpp
template<typename T> Span<T> System::MemoryExtensions::AsSpan(const ArrayPtr<T> &array, int32_t start=0, int32_t length=-1)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en la matriz. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | La matriz de origen. |
| start | **int32_t** | El índice inicial en la matriz. |
| length | **int32_t** | La longitud del span. |

### Valor devuelto

Span<T> que abarca la porción especificada de la matriz.

## System::MemoryExtensions::AsSpan(const String\&, int32_t, int32_t) function


Crea un span de solo lectura a partir de una cadena.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::AsSpan(const String &text, int32_t start=0, int32_t length=-1)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | const [String](../../system/string/)\& | La cadena de origen. |
| start | **int32_t** | El índice inicial en la cadena. |
| length | **int32_t** | La longitud del span. |

### Valor devuelto

ReadOnlySpan<char16_t> que abarca la porción especificada de la cadena.

## Véase también

* Typedef [ArrayPtr](../../system/arrayptr/)
* Clase [Span](../../system/span/)
* Clase [ReadOnlySpan](../../system/readonlyspan/)
* Clase [String](../../system/string/)
* Espacio de nombres [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)