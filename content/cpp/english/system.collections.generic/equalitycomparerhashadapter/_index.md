---
title: EqualityComparerHashAdapter
second_title: Aspose.Slides for C++ API Reference
description: Adapter to use IEqualityComparer for hashing. Uses comparator object, if set; otherwise, uses available hash method selected using DictionaryHashSelector struct.
type: docs
weight: 664
url: /system.collections.generic/equalitycomparerhashadapter/
---
## EqualityComparerHashAdapter struct


Adapter to use [IEqualityComparer](../iequalitycomparer/) for hashing. Uses comparator object, if set; otherwise, uses available hash method selected using [DictionaryHashSelector](../dictionaryhashselector/) struct.

```cpp
template<typename T>class EqualityComparerHashAdapter
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Hashed | type. |
## Methods

| Method | Description |
| --- | --- |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)() | Creates adapter with no comparator to use. |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Creates adapter with given comparator to use. |
| std::size_t [operator()](./operator_call/)(const T\&) const | Calculates hash value. |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Sets comparator to use. |

## See Also

* Namespace [System::Collections::Generic](../)
* Library [Aspose.Slides](../../)