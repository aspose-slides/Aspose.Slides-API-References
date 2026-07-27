---
title: SwapIfGreaterWithValues()
second_title: Referencia de API de Aspose.Slides para C++
description: Intercambia pares clave-valor si se cumple la condición de comparación.
type: docs
weight: 53
url: /es/system.memoryextensions.details/swapifgreaterwithvalues/
---
## System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>, int32_t, int32_t) función


Intercambia pares clave-valor si se cumple la condición de comparación.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer, int32_t i, int32_t j)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TKey | El tipo de claves |
| TValue | El tipo de valores |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | El span de claves |
| values | [Span](../../system/span/)\<TValue\>\& | El span de valores |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) función para claves |
| i | **int32_t** | Primer índice a comparar |
| j | **int32_t** | Segundo índice a comparar |

## Ver también

* Clase [Span](../../system/span/)
* Espacio de nombres [System::MemoryExtensions::Details](../)
* Biblioteca [Aspose.Slides](../../)