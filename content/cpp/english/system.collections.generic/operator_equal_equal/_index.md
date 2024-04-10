---
title: operator==()
second_title: Aspose.Slides for C++ API Reference
description: Compares two key-value pairs using 'equals' semantics. Uses operator == or EqualsTo method for both keys and values, whichever is defined.
type: docs
weight: 677
url: /system.collections.generic/operator_equal_equal/
---
## System::Collections::Generic::operator==(const KeyValuePair\<TKey, TValue\>\&, const KeyValuePair\<TKey, TValue\>\&) function


Compares two key-value pairs using 'equals' semantics. Uses operator == or EqualsTo method for both keys and values, whichever is defined.

```cpp
template<typename TKey,typename TValue> bool System::Collections::Generic::operator==(const KeyValuePair<TKey, TValue> &left, const KeyValuePair<TKey, TValue> &right)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TKey | Key type. |
| TValue | Value type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| left | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | LHS operand. |
| right | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | RHS operand. |

### Return Value

True if both keys and values match, false otherwise.

## See Also

* Class [KeyValuePair](../keyvaluepair/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.Slides](../../)