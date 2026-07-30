---
title: CopyTo()
second_title: Riferimento API di Aspose.Slides per C++
description: "Copia gli elementi di ICollection in un System::Array, iniziando da un indice specifico di System::Array."
type: docs
weight: 66
url: /it/aspose.slides.animation/behaviorpropertycollection/copyto/
---
## BehaviorPropertyCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IBehaviorProperty\>\>, int32_t) metodo

Copia gli elementi di [ICollection](../../../system.collections.generic/icollection/) in un [System::Array](../../../system/array/), iniziando da un indice [System::Array](../../../system/array/) particolare.

```cpp
void Aspose::Slides::Animation::BehaviorPropertyCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IBehaviorProperty>> array, int32_t arrayIndex) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\> | Il [System::Array](../../../system/array/) monodimensionale che è la destinazione degli elementi copiati da [ICollection](../../../system.collections.generic/icollection/). Il [System::Array](../../../system/array/) deve avere un'indicizzazione a zero. |
| arrayIndex | **int32_t** | L'indice a base zero in *array* al quale inizia la copia. |

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IBehaviorProperty](../../ibehaviorproperty/)
* Classe [BehaviorPropertyCollection](../)
* Namespace [Aspose::Slides::Animation](../../)
* Libreria [Aspose.Slides](../../../)