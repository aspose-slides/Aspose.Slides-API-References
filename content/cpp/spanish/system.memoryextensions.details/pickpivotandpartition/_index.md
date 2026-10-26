---
title: PickPivotAndPartition()
second_title: Referencia de API de Aspose.Slides para C++
description: Selecciona pivote y particiona pares clave-valor para quicksort.
type: docs
weight: 105
url: /es/system.memoryextensions.details/pickpivotandpartition/
---
## System::MemoryExtensions::Details::PickPivotAndPartition(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) function


Selecciona un pivote y particiona pares clave-valor para quicksort.

```cpp
template<typename TKey,typename TValue> int32_t System::MemoryExtensions::Details::PickPivotAndPartition(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TKey | El tipo de claves |
| TValue | El tipo de valores |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | El rango de claves a particionar |
| values | [Span](../../system/span/)\<TValue\>\& | El rango de valores a particionar |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) función para claves |

### Valor devuelto

El índice del pivote después de la partición

## Véase también

* Clase [Span](../../system/span/)
* Espacio de nombres [System::MemoryExtensions::Details](../)
* Biblioteca [Aspose.Slides](../../)