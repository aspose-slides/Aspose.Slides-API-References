---
title: CopyTo()
second_title: Aspose.Slides for C++ API Reference
description: "Copies the elements of the ICollection to an System::Array, starting at a particular System::Array index."
type: docs
weight: 118
url: /aspose.slides.charts/piesplitcustompointcollection/copyto/
---
## PieSplitCustomPointCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IChartDataPoint\>\>, int32_t) method


Copies the elements of the [ICollection](../../../system.collections.generic/icollection/) to an [System::Array](../../../system/array/), starting at a particular [System::Array](../../../system/array/) index.

```cpp
void Aspose::Slides::Charts::PieSplitCustomPointCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IChartDataPoint>> array, int32_t arrayIndex) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IChartDataPoint](../../ichartdatapoint/)\>\> | The one-dimensional [System::Array](../../../system/array/) that is the destination of the elements copied from [ICollection](../../../system.collections.generic/icollection/). The [System::Array](../../../system/array/) must have zero-based indexing. |
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
* Class [IChartDataPoint](../../ichartdatapoint/)
* Class [PieSplitCustomPointCollection](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)