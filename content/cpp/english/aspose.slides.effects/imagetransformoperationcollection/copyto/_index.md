---
title: CopyTo()
second_title: Aspose.Slides for C++ API Reference
description: "Copies the elements of the ICollection to an System::Array, starting at a particular System::Array index."
type: docs
weight: 326
url: /aspose.slides.effects/imagetransformoperationcollection/copyto/
---
## ImageTransformOperationCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IImageTransformOperation\>\>, int32_t) method


Copies the elements of the [ICollection](../../../system.collections.generic/icollection/) to an [System::Array](../../../system/array/), starting at a particular [System::Array](../../../system/array/) index.

```cpp
void Aspose::Slides::Effects::ImageTransformOperationCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IImageTransformOperation>> array, int32_t arrayIndex) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IImageTransformOperation](../../iimagetransformoperation/)\>\> | The one-dimensional [System::Array](../../../system/array/) that is the destination of the elements copied from [ICollection](../../../system.collections.generic/icollection/). The [System::Array](../../../system/array/) must have zero-based indexing. |
| arrayIndex | **int32_t** | The zero-based index in *array*  at which copying begins. |

### Exceptions

| Exception | Description |
| --- | --- |
| [System::ArgumentNullException](../../../system/argumentnullexception/) | *array*  is null. |
| [System::ArgumentOutOfRangeException](../../../system/argumentoutofrangeexception/) | *arrayIndex*  is less than 0. |
| [System::ArgumentException](../../../system/argumentexception/) | The number of elements in the source [ICollection](../../../system.collections.generic/icollection/) is greater than the available space from *arrayIndex*  to the end of the destination *array* . |


## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImageTransformOperation](../../iimagetransformoperation/)
* Class [ImageTransformOperationCollection](../)
* Namespace [Aspose::Slides::Effects](../../)
* Library [Aspose.Slides](../../../)