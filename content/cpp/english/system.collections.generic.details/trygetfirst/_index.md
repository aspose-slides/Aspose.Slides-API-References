---
title: TryGetFirst()
second_title: Aspose.Slides for C++ API Reference
description: Tries to get the first element of the collection.
type: docs
weight: 248
url: /system.collections.generic.details/trygetfirst/
---
## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, bool\&) function


Tries to get the first element of the collection.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, bool &found)
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

Returns the first collection element. The default value of the type will be returned when the collection is empty.

## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, const Func\<T, bool\>\&, bool\&) function


Tries to get the first element of the collection, which satisfies to the predicate function.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, const Func<T, bool> &predicate, bool &found)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of the collection elements. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | The collection from which an element is to be acquired. |
| predicate | const [Func](../../system/func/)\<T, **bool**\>\& | The predicate function. |
| found | **bool**\& | The output parameter. Returns true when the collection contains any element. Otherwise false is returned. |

### Return Value

Returns the first collection element. The default value of the type will be returned when no element satisfying the specified predicate function is found.

## See Also

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Class [Func](../../system/func/)
* Namespace [System::Collections::Generic::Details](../)
* Library [Aspose.Slides](../../)