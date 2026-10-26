---
title: InsertionSort()
second_title: Referencia de API de Aspose.Slides for C++
description: Realiza una ordenación por inserción en pares clave-valor.
type: docs
weight: 66
url: /es/system.memoryextensions.details/insertionsort/
---
## System::MemoryExtensions::Details::InsertionSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) función


Realiza una ordenación por inserción en pares clave-valor.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::InsertionSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TKey | El tipo de claves |
| TValue | El tipo de valores |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | El span de claves a ordenar |
| values | [Span](../../system/span/)\<TValue\>\& | El span de valores a ordenar |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) función para claves |

## Véase también

* Clase [Span](../../system/span/)
* Espacio de nombres [System::MemoryExtensions::Details](../)
* Biblioteca [Aspose.Slides](../../)