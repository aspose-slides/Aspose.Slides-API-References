---
title: CopyTo()
second_title: Aspose.Slides für C++ API-Referenz
description: "Kopiert die Elemente der ICollection in ein System::Array, beginnend bei einem bestimmten System::Array-Index."
type: docs
weight: 66
url: /de/aspose.slides.animation/behaviorpropertycollection/copyto/
---
## BehaviorPropertyCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IBehaviorProperty\>\>, int32_t) Methode


Kopiert die Elemente von [ICollection](../../../system.collections.generic/icollection/) in ein [System::Array](../../../system/array/), beginnend bei einem bestimmten [System::Array](../../../system/array/) Index.

```cpp
void Aspose::Slides::Animation::BehaviorPropertyCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IBehaviorProperty>> array, int32_t arrayIndex) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\> | Das ein-dimensionale [System::Array](../../../system/array/), das das Ziel der von [ICollection](../../../system.collections.generic/icollection/) kopierten Elemente ist. Der [System::Array](../../../system/array/) muss nullbasierte Indizierung haben. |
| arrayIndex | **int32_t** | Der nullbasierte Index in *array* an dem das Kopieren beginnt. |

## Siehe Auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IBehaviorProperty](../../ibehaviorproperty/)
* Klasse [BehaviorPropertyCollection](../)
* Namensraum [Aspose::Slides::Animation](../../)
* Bibliothek [Aspose.Slides](../../../)