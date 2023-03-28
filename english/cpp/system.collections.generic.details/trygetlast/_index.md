---
title: TryGetLast()
second_title: Aspose.Slides for C++ API Reference
description: Tries to get the last element of the collection.
type: docs
weight: 261
url: /cpp/system.collections.generic.details/trygetlast/
---
## System::Collections::Generic::Details::TryGetLast([IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) function


Tries to get the last element of the collection.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetLast(IEnumerable<T> &enumerable, bool &found)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of the collection elements. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | The collection from which an element is to be acquired. |
| found | **bool**\& | The output parameter. Returns true when the collection contains any element. Otherwise false is returned. |

### Return Value

Returns the last collection element. The default value of the type will be returned when the collection is empty.

## See Also

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Collections::Generic::Details](../)
* Library [Aspose.Slides](../../)
