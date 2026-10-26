---
title: CopyTo()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Copie les éléments de l'ICollection vers un System::Array, en commençant à un index particulier de System::Array."
type: docs
weight: 66
url: /fr/aspose.slides.animation/behaviorcollection/copyto/
---
## BehaviorCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IBehavior\>\>, int32_t) méthode

Copie les éléments du [ICollection](../../../system.collections.generic/icollection/) vers un [System::Array](../../../system/array/), en commençant à un index [System::Array](../../../system/array/) particulier.

```cpp
void Aspose::Slides::Animation::BehaviorCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IBehavior>> array, int32_t arrayIndex)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IBehavior](../../ibehavior/)\>\> | Le [System::Array](../../../system/array/) unidimensionnel qui est la destination des éléments copiés depuis [ICollection](../../../system.collections.generic/icollection/). Le [System::Array](../../../system/array/) doit posséder un index à base zéro. |
| arrayIndex | **int32_t** | L'index à base zéro dans *array* auquel la copie commence. |

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IBehavior](../../ibehavior/)
* Classe [BehaviorCollection](../)
* Espace de noms [Aspose::Slides::Animation](../../)
* Bibliothèque [Aspose.Slides](../../../)