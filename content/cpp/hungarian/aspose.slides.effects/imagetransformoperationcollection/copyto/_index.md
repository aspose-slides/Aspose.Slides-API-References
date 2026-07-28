---
title: CopyTo()
second_title: Aspose.Slides for C++ API Referencia
description: "Átmásolja az ICollection elemeit egy System::Array-be, egy adott System::Array indexnél kezdve."
type: docs
weight: 326
url: /hu/aspose.slides.effects/imagetransformoperationcollection/copyto/
---
## ImageTransformOperationCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IImageTransformOperation\>\>, int32_t) method

Másolja a [ICollection](../../../system.collections.generic/icollection/) elemeit egy [System::Array](../../../system/array/)-ba, egy adott [System::Array](../../../system/array/) indextől kezdve.

```cpp
void Aspose::Slides::Effects::ImageTransformOperationCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IImageTransformOperation>> array, int32_t arrayIndex) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IImageTransformOperation](../../iimagetransformoperation/)\>\> | Az egydimenziós [System::Array](../../../system/array/), amely a [ICollection](../../../system.collections.generic/icollection/)-ből másolt elemek célpontja. A [System::Array](../../../system/array/) nullás indexelésű kell legyen. |
| arrayIndex | **int32_t** | A nullás index a *array* tömbben, ahol a másolás kezdődik. |

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImageTransformOperation](../../iimagetransformoperation/)
* Class [ImageTransformOperationCollection](../)
* Namespace [Aspose::Slides::Effects](../../)
* Library [Aspose.Slides](../../../)