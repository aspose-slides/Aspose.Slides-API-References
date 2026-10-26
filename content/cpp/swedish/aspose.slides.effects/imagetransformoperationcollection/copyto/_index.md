---
title: CopyTo()
second_title: Aspose.Slides för C++ API-referens
description: "Kopierar elementen i ICollection till en System::Array, med början vid ett specifikt System::Array-index."
type: docs
weight: 326
url: /sv/aspose.slides.effects/imagetransformoperationcollection/copyto/
---
## ImageTransformOperationCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IImageTransformOperation\>\>, int32_t) metod


Kopierar elementen från [ICollection](../../../system.collections.generic/icollection/) till en [System::Array](../../../system/array/), med början vid ett särskilt [System::Array](../../../system/array/) index.

```cpp
void Aspose::Slides::Effects::ImageTransformOperationCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IImageTransformOperation>> array, int32_t arrayIndex) override
```


### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IImageTransformOperation](../../iimagetransformoperation/)\>\> | Den endimensionella [System::Array](../../../system/array/) som är destinationen för elementen som kopieras från [ICollection](../../../system.collections.generic/icollection/). [System::Array](../../../system/array/) måste ha nollbaserad indexering. |
| arrayIndex | **int32_t** | Det nollbaserade indexet i *array* där kopieringen börjar. |

## Se också

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IImageTransformOperation](../../iimagetransformoperation/)
* Klass [ImageTransformOperationCollection](../)
* Namnrymd [Aspose::Slides::Effects](../../)
* Bibliotek [Aspose.Slides](../../../)