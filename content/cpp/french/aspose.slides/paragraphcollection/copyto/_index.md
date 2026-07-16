---
title: CopyTo()
second_title: Référence API Aspose.Slides pour C++
description: "Copie les éléments de l'ICollection vers un System::Array, en commençant à un index particulier du System::Array."
type: docs
weight: 105
url: /fr/aspose.slides/paragraphcollection/copyto/
---
## ParagraphCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IParagraph\>\>, int32_t) méthode

Copie les éléments du [ICollection](../../../system.collections.generic/icollection/) vers un [System::Array](../../../system/array/), en commençant à un index [System::Array](../../../system/array/) particulier.

```cpp
void Aspose::Slides::ParagraphCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IParagraph>> array, int32_t arrayIndex)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\>\> | Le [System::Array](../../../system/array/) unidimensionnel qui est la destination des éléments copiés depuis [ICollection](../../../system.collections.generic/icollection/). Le [System::Array](../../../system/array/) doit avoir un indexage à base zéro. |
| arrayIndex | **int32_t** | L'index basé sur zéro dans *array* à partir duquel la copie commence. |

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IParagraph](../../iparagraph/)
* Classe [ParagraphCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)