---
title: TrueForAll()
second_title: Aspose.Slides for C++ API Reference
description: Determines whether all elements in the specified array satisfy the conditions defined by specified predicate.
type: docs
weight: 651
url: /cpp/system/array/trueforall/
---
## Array::TrueForAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) method


Determines whether all elements in the specified array satisfy the conditions defined by specified predicate.

```cpp
static bool System::Array<T>::TrueForAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) elements of which to match against the conditions |
| match | [System::Predicate](../../predicate/)\<T\> | A predicate that defines the conditions to match array elements against |

### Return Value

true if all elements of the array arr satisfy the conditions defined by predicate match, otherwise false

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)