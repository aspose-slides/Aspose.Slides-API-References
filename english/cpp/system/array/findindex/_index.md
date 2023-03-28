---
title: FindIndex()
second_title: Aspose.Slides for C++ API Reference
description: Searches for the first element in the specified array that satisfies the conditions of the specified predicate.
type: docs
weight: 612
url: /cpp/system/array/findindex/
---
## Array::FindIndex([System::ArrayPtr](../../arrayptr/)\<T\>, [System::Predicate](../../predicate/)\<T\>) method


Searches for the first element in the specified array that satisfies the conditions of the specified predicate.

```cpp
static int System::Array<T>::FindIndex(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) to search an element in |
| match | [System::Predicate](../../predicate/)\<T\> | A predicate that defines the conditions to match array elements against |

### Return Value

The index of the first element in the array that satisfies the conditions defined by predicate, otherwise -1

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
