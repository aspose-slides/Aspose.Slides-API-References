---
title: CopyTo()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Copie les éléments de l'ICollection vers un System::Array, en commençant à un index particulier du System::Array."
type: docs
weight: 326
url: /fr/aspose.slides.effects/imagetransformoperationcollection/copyto/
---
## ImageTransformOperationCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IImageTransformOperation\>\>, int32_t) méthode

Copie les éléments du [ICollection](../../../system.collections.generic/icollection/) vers un [System::Array](../../../system/array/), en commençant à un index [System::Array](../../../system/array/) particulier.

```cpp
void Aspose::Slides::Effects::ImageTransformOperationCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IImageTransformOperation>> array, int32_t arrayIndex) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IImageTransformOperation](../../iimagetransformoperation/)\>\> | Le [System::Array](../../../system/array/) unidimensionnel qui est la destination des éléments copiés depuis [ICollection](../../../system.collections.generic/icollection/). Le [System::Array](../../../system/array/) doit avoir un index basé sur zéro. |
| arrayIndex | **int32_t** | L'index basé sur zéro dans *array* à partir duquel la copie commence. |

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IImageTransformOperation](../../iimagetransformoperation/)
* Classe [ImageTransformOperationCollection](../)
* Espace de noms [Aspose::Slides::Effects](../../)
* Bibliothèque [Aspose.Slides](../../../)