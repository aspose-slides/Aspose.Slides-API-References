---
title: BinarySearchImpl()
second_title: Referencia de API de Aspose.Slides para C++
description: Implementación común de búsqueda binaria.
type: docs
weight: 118
url: /es/system.memoryextensions.details/binarysearchimpl/
---
## System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan\<T\>\&, const TValue\&, TCompareFunc) function

Common binary search implementation.

```cpp
template<typename T,typename TValue,typename TCompareFunc> int32_t System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan<T> &span, const TValue &value, TCompareFunc compareFunc)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de los elementos en span |
| TValue | Tipo del valor a buscar |
| TCompareFunc | Tipo de función para la comparación |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span a buscar |
| value | const TValue\& | El valor a buscar |
| compareFunc | TCompareFunc | Función que compara el valor con el elemento del span y devuelve **int32_t** (-1, 0, 1) |

### Valor devuelto

[Index](../../system/index/) del elemento encontrado o el complemento a nivel de bits del punto de inserción

## Ver también

* Clase [ReadOnlySpan](../../system/readonlyspan/)
* Espacio de nombres [System::MemoryExtensions::Details](../)
* Biblioteca [Aspose.Slides](../../)