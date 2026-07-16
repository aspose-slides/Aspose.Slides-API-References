---
title: CopyTo()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Copie les éléments de l'ICollection vers un System::Array, en commençant à un index System::Array particulier."
type: docs
weight: 118
url: /fr/aspose.slides/portioncollection/copyto/
---
## PortionCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IPortion\>\>, int32_t) méthode


Copie les éléments du [ICollection](../../../system.collections.generic/icollection/) vers un [System::Array](../../../system/array/), en commençant à un index [System::Array](../../../system/array/) particulier.

```cpp
void Aspose::Slides::PortionCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IPortion>> array, int32_t arrayIndex)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\>\> | Le [System::Array](../../../system/array/) unidimensionnel qui est la destination des éléments copiés depuis [ICollection](../../../system.collections.generic/icollection/). Le [System::Array](../../../system/array/) doit être indexé à base zéro. |
| arrayIndex | **int32_t** | L'index à base zéro dans *array* où la copie commence. |

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPortion](../../iportion/)
* Classe [PortionCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)