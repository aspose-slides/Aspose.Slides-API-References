---
title: Heapify()
second_title: Referencia de API de Aspose.Slides para C++
description: Mantiene la propiedad de heap para pares clave-valor.
type: docs
weight: 92
url: /es/system.memoryextensions.details/heapify/
---
## System::MemoryExtensions::Details::Heapify(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) función

Mantiene la propiedad de heap para pares clave-valor.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::Heapify(Span<TKey> &keys, Span<TValue> &values, int32_t n, int32_t i, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TKey | El tipo de claves |
| TValue | El tipo de valores |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | El span de claves en el heap |
| values | [Span](../../system/span/)\<TValue\>\& | El span de valores en el heap |
| n | **int32_t** | Tamaño del heap |
| i | **int32_t** | [Index](../../system/index/) para heapificar desde |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) función para claves |

## Ver también

* Clase [Span](../../system/span/)
* Espacio de nombres [System::MemoryExtensions::Details](../)
* Biblioteca [Aspose.Slides](../../)