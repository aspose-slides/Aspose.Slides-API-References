---
title: IntroSort()
second_title: Referencia de API de Aspose.Slides para C++
description: Implementación interna del algoritmo introsort para pares clave-valor.
type: docs
weight: 40
url: /es/system.memoryextensions.details/introsort/
---
## System::MemoryExtensions::Details::IntroSort(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) función


Implementación interna del algoritmo introsort para pares clave-valor.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::IntroSort(Span<TKey> &keys, Span<TValue> &values, int32_t depthLimit, std::function<int32_t(const TKey &, const TKey &)> comparer)
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
| depthLimit | **int32_t** | Profundidad máxima de recursión antes de cambiar a heapsort |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) función para claves |

## Ver también

* Clase [Span](../../system/span/)
* Espacio de nombres [System::MemoryExtensions::Details](../)
* Biblioteca [Aspose.Slides](../../)