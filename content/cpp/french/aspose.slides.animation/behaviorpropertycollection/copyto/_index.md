---
title: CopyTo()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Copie les éléments de l'ICollection vers un System::Array, en commençant à un index particulier du System::Array."
type: docs
weight: 66
url: /fr/aspose.slides.animation/behaviorpropertycollection/copyto/
---
## BehaviorPropertyCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IBehaviorProperty\>\>, int32_t) méthode

Copie les éléments du [ICollection](../../../system.collections.generic/icollection/) dans un [System::Array](../../../system/array/), en commençant à un index [System::Array](../../../system/array/) particulier.

```cpp
void Aspose::Slides::Animation::BehaviorPropertyCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IBehaviorProperty>> array, int32_t arrayIndex) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\> | Le [System::Array](../../../system/array/) unidimensionnel qui est la destination des éléments copiés depuis [ICollection](../../../system.collections.generic/icollection/). Le [System::Array](../../../system/array/) doit disposer d'un index basé sur zéro. |
| arrayIndex | **int32_t** | L'index basé sur zéro dans *array* à partir duquel la copie commence. |

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IBehaviorProperty](../../ibehaviorproperty/)
* Class [BehaviorPropertyCollection](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)