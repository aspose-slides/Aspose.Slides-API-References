---
title: operator!=()
second_title: Aspose.Slides for C++ API Reference
description: Compares two key-value pairs using inverse 'equals' semantics.
type: docs
weight: 638
url: /cpp/system.collections.generic/operator_not_equal/
---
## System::Collections::Generic::operator!=(const KeyValuePair\<TKey, TValue\>\&, const KeyValuePair\<TKey, TValue\>\&) function


Compares two key-value pairs using inverse 'equals' semantics.

```cpp
template<typename TKey,typename TValue> bool System::Collections::Generic::operator!=(const KeyValuePair<TKey, TValue> &left, const KeyValuePair<TKey, TValue> &right)
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

True if both keys and values don't match, false otherwise.

## See Also

* Class [KeyValuePair](../keyvaluepair/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.Slides](../../)