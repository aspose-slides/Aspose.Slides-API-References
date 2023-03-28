---
title: FindAll()
second_title: Aspose.Slides for C++ API Reference
description: Retrieves all the elements that match the conditions defined by the specified predicate.
type: docs
weight: 638
url: /cpp/system/array/findall/
---
## Array::FindAll([System::ArrayPtr](../../arrayptr/)\<T\>, [System::Predicate](../../predicate/)\<T\>) method


Retrieves all the elements that match the conditions defined by the specified predicate.

```cpp
static System::ArrayPtr<T> System::Array<T>::FindAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) to search an elements in |
| match | [System::Predicate](../../predicate/)\<T\> | A predicate that defines the conditions to match array elements against |

### Return Value

An [Array](../) containing all the elements that match the conditions defined by the specified predicate, if found; otherwise, an empty [Array](../).

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
