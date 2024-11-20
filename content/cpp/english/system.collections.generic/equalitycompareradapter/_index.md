---
title: EqualityComparerAdapter
second_title: Aspose.Slides for C++ API Reference
description: "Adapter making it possible using IEqualityComparer with STL-styled collections and algorithms. Uses IEqualityComparer, if set. If not set, uses operator ==, Object::Equals or T::Equals, whichever is available."
type: docs
weight: 664
url: /system.collections.generic/equalitycompareradapter/
---
## EqualityComparerAdapter struct


Adapter making it possible using [IEqualityComparer](../iequalitycomparer/) with STL-styled collections and algorithms. Uses [IEqualityComparer](../iequalitycomparer/), if set. If not set, uses operator ==, [Object::Equals](../../system/object/equals/) or T::Equals, whichever is available.

```cpp
template<class T>class EqualityComparerAdapter
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Type being compared. |
## Methods

| Method | Description |
| --- | --- |
|  [EqualityComparerAdapter](./equalitycompareradapter/)() | Creates adapter not using any comparator. |
|  [EqualityComparerAdapter](./equalitycompareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Creates adapter with given comparator. |
| **bool** [operator()](./operator_call/)(const T\&, const T\&) const | Compares two objects. |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Sets comparator. |

## See Also

* Namespace [System::Collections::Generic](../)
* Library [Aspose.Slides](../../)