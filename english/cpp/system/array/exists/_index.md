---
title: Exists()
second_title: Aspose.Slides for C++ API Reference
description: Determines if the specified Array object contains an element that satisfies requirements of the specified predicate.
type: docs
weight: 742
url: /cpp/system/array/exists/
---
## Array::Exists([ArrayPtr](../../arrayptr/)\<T\>, std::function\<**bool**(T)>) method


Determines if the specified [Array](../) object contains an element that satisfies requirements of the specified predicate.

```cpp
static bool System::Array<T>::Exists(ArrayPtr<T> arr, std::function<bool(T)> match)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | The array to look for the element in |
| match | std::function\<**bool**(T)> | Function object that defines requirements and checks if an element satisfies them |

### Return Value

True if **arr** contains an element that satisfies requirements defined by **match**

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
