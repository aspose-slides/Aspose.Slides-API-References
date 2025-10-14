---
title: MakeYieldEnumerator()
second_title: Aspose.Slides for C++ API Reference
description: Creates an IEnumerator from a yield function.
type: docs
weight: 2211
url: /system/makeyieldenumerator/
---
## System::MakeYieldEnumerator(const Details::YieldFunction\<T\>\&) function


Creates an IEnumerator from a yield function.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerator<T>> System::MakeYieldEnumerator(const Details::YieldFunction<T> &fnc)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the sequence |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | The yield function to execute |

### Return Value

Shared pointer to the IEnumerator

## See Also

* Typedef [SharedPtr](../sharedptr/)
* Class [IEnumerator](../../system.collections.generic/ienumerator/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)