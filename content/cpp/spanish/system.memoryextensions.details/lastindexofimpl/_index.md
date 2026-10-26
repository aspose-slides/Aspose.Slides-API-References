---
title: LastIndexOfImpl()
second_title: Referencia de API de Aspose.Slides para C++
description: Busca el último índice de un valor en un span.
type: docs
weight: 14
url: /es/system.memoryextensions.details/lastindexofimpl/
---
## System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan\<T\>\&, int32_t, const T\&) función

Busca el último índice de un valor en un span.

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan<T> &searchSpace, int32_t length, const T &value)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de elementos en span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| searchSpace | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [Span](../../system/span/) para buscar |
| length | **int32_t** | Longitud dentro de la cual buscar |
| value | const T\& | Valor a encontrar |

### Valor devuelto

Último índice del valor, o -1 si no se encuentra

## Ver también

* Clase [ReadOnlySpan](../../system/readonlyspan/)
* Espacio de nombres [System::MemoryExtensions::Details](../)
* Biblioteca [Aspose.Slides](../../)