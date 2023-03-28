---
title: KeyValuePair
second_title: Aspose.Slides for C++ API Reference
description: "Pair of key and value. This type should be allocated on stack and passed to functions by value or by reference. Never use System::SmartPtr class to manage objects of this type."
type: docs
weight: 352
url: /cpp/system.collections.generic/keyvaluepair/
---
## KeyValuePair class


Pair of key and value. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../../system/smartptr/) class to manage objects of this type.

```cpp
template<typename TKey,typename TValue>class KeyValuePair
```

## Methods

| Method | Description |
| --- | --- |
| const TKey\& [get_Key](./get_key/)() const | Gets key. |
| const TValue\& [get_Value](./get_value/)() const | Gets value. |
| int [GetHashCode](./gethashcode/)() const | Calculates key-value pair hash by xoring key's and value's hashes. |
| **bool** [IsNull](./isnull/)() const | Always returns false. |
|  [KeyValuePair](./keyvaluepair/)() | Null key-value pair initializer. |
|  [KeyValuePair](./keyvaluepair/)(const TKey\&, const TValue\&) | Constructor. |
|  [KeyValuePair](./keyvaluepair/)(const std::pair\<OtherK, OtherV\>\&) | Type conversion constructor. |
| **bool** [operator<](./operator_less/)(const [KeyValuePair](./)\&) const | Patch for classes inherited from IComparer<KeyValuePair<TKey, TValue>>, doesn't compare anything. |
| [String](../../system/string/) [ToString](./tostring/)() const | Converts key-value pair to string. |

## See Also

* Namespace [System::Collections::Generic](../)
* Library [Aspose.Slides](../../)
