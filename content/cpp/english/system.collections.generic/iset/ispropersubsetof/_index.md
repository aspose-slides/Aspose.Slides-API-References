---
title: IsProperSubsetOf()
second_title: Aspose.Slides for C++ API Reference
description: Checks if current set is a strict subset of other container.
type: docs
weight: 40
url: /system.collections.generic/iset/ispropersubsetof/
---
## ISet::IsProperSubsetOf(IEnumerablePtr) method


Checks if current set is a strict subset of other container.

```cpp
virtual bool System::Collections::Generic::ISet<T>::IsProperSubsetOf(IEnumerablePtr other)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| other | [IEnumerablePtr](../ienumerableptr/) | Superset to check against. |

### Return Value

True if all elements in current set are present in **other** and **other** has more elements than current set, false otherwise.

## See Also

* Typedef [IEnumerablePtr](../ienumerableptr/)
* Class [ISet](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)