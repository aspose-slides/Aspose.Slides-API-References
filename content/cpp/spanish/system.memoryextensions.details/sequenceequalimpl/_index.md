---
title: SequenceEqualImpl()
second_title: Referencia de API de Aspose.Slides para C++
description: Comprueba si dos spans son iguales a partir de posiciones especificadas.
type: docs
weight: 27
url: /es/system.memoryextensions.details/sequenceequalimpl/
---
## System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan\<T\>\&, const int32_t, int32_t, const ReadOnlySpan\<T\>\&) función

Comprueba si dos spans son iguales a partir de posiciones especificadas.

```cpp
template<typename T> bool System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan<T> &first, const int32_t start, int32_t length, const ReadOnlySpan<T> &second)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Type of elements in spans |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Primer span |
| start | const **int32_t** | Índice inicial en el primer span |
| length | **int32_t** | Número de elementos a comparar |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Segundo span |

### Valor de retorno

true si los rangos especificados son iguales, false en caso contrario

## Ver también

* Clase [ReadOnlySpan](../../system/readonlyspan/)
* Espacio de nombres [System::MemoryExtensions::Details](../)
* Biblioteca [Aspose.Slides](../../)