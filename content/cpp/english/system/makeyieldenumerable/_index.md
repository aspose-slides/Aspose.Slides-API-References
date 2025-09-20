---
title: MakeYieldEnumerable()
second_title: Aspose.Slides for C++ API Reference
description: Creates an IEnumerable from a yield function.
type: docs
weight: 2172
url: /system/makeyieldenumerable/
---
## System::MakeYieldEnumerable(const Details::YieldFunction\<T\>\&) function


Creates an IEnumerable from a yield function.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerable<T>> System::MakeYieldEnumerable(const Details::YieldFunction<T> &fnc)
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

Shared pointer to the IEnumerable

## See Also

* Typedef [SharedPtr](../sharedptr/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)