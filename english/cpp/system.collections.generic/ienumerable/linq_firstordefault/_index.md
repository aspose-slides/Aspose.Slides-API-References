---
title: LINQ_FirstOrDefault()
second_title: Aspose.Slides for C++ API Reference
description: Returns the first element of a sequence, or a default value if the sequence is empty.
type: docs
weight: 40
url: /cpp/system.collections.generic/ienumerable/linq_firstordefault/
---
## IEnumerable::LINQ_FirstOrDefault() method


Returns the first element of a sequence, or a default value if the sequence is empty.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault()
```


### Return Value

First element in the sequence or default-constructed value if the sequence is empty.

## IEnumerable::LINQ_FirstOrDefault(std::function\<bool(T)>) method


Returns the first element of the sequence that satisfies a condition or a default value if no such element is found.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault(std::function<bool(T)> predicate)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | A function to test each element for a condition. |

### Return Value

default(T) if source is empty or if no element passes the test specified by predicate; otherwise, the first element in source that passes the test specified by predicate.

## See Also

* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)