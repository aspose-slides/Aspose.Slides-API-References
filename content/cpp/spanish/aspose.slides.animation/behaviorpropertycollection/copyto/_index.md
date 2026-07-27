---
title: CopyTo()
second_title: Referencia de API de Aspose.Slides para C++
description: "Copia los elementos de la ICollection a un System::Array, comenzando en un índice particular de System::Array."
type: docs
weight: 66
url: /es/aspose.slides.animation/behaviorpropertycollection/copyto/
---
## BehaviorPropertyCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IBehaviorProperty\>\>, int32_t) método


Copia los elementos del [ICollection](../../../system.collections.generic/icollection/) a un [System::Array](../../../system/array/), comenzando en un índice [System::Array](../../../system/array/) particular.

```cpp
void Aspose::Slides::Animation::BehaviorPropertyCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IBehaviorProperty>> array, int32_t arrayIndex) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\> | El [System::Array](../../../system/array/) unidimensional que es el destino de los elementos copiados desde [ICollection](../../../system.collections.generic/icollection/). El [System::Array](../../../system/array/) debe tener indexación basada en cero. |
| arrayIndex | **int32_t** | El índice basado en cero en *array* donde comienza la copia. |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IBehaviorProperty](../../ibehaviorproperty/)
* Clase [BehaviorPropertyCollection](../)
* Espacio de nombres [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)