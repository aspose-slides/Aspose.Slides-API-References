---
title: CopyTo()
second_title: Riferimento API di Aspose.Slides per C++
description: "Copia gli elementi della ICollection in un System::Array, iniziando da un indice specifico di System::Array."
type: docs
weight: 66
url: /it/aspose.slides.animation/behaviorcollection/copyto/
---
## BehaviorCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IBehavior\>\>, int32_t) metodo

Copia gli elementi del [ICollection](../../../system.collections.generic/icollection/) in un [System::Array](../../../system/array/), a partire da un indice [System::Array](../../../system/array/) specifico.

```cpp
void Aspose::Slides::Animation::BehaviorCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IBehavior>> array, int32_t arrayIndex)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IBehavior](../../ibehavior/)\>\> | Il [System::Array](../../../system/array/) unidimensionale che è la destinazione degli elementi copiati da [ICollection](../../../system.collections.generic/icollection/). Il [System::Array](../../../system/array/) deve avere un'indicizzazione a base zero. |
| arrayIndex | **int32_t** | L'indice a base zero in *array* al quale inizia la copia. |

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IBehavior](../../ibehavior/)
* Classe [BehaviorCollection](../)
* Spazio dei nomi [Aspose::Slides::Animation](../../)
* Libreria [Aspose.Slides](../../../)