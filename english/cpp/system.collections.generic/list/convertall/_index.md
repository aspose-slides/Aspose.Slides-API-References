---
title: ConvertAll()
second_title: Aspose.Slides for C++ API Reference
description: Creates a list of elements converted to different type.
type: docs
weight: 352
url: /cpp/system.collections.generic/list/convertall/
---
## List::ConvertAll(Converter\<T, OutputType\>) method


Creates a list of elements converted to different type.

```cpp
template<typename OutputType> SharedPtr<List<OutputType>> System::Collections::Generic::List<T>::ConvertAll(Converter<T, OutputType> converter)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| OutputType | Output list element type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| converter | [Converter](../../../system/converter/)\<T, OutputType\> | Converter to use for items conversion. |

### Return Value

A newly created list of converted elements.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Converter](../../../system/converter/)
* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)