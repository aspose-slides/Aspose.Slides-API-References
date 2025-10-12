---
title: operator!=()
second_title: Aspose.Slides for C++ API Reference
description: Non-equality comparison operator.
type: docs
weight: 313
url: /system/string/operator_not_equal/
---
## String::operator!=(const String\&) const method


Non-equality comparison operator.

```cpp
bool System::String::operator!=(const String &str) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) to compare current one to. |

### Return Value

false if both strings are null or both are not null and match, true otherwise.

## String::operator!=(std::nullptr_t) const method


Checks if string is not null. Applies same logic as [IsNull()](../isnull/) call.

```cpp
bool System::String::operator!=(std::nullptr_t) const
```


### Return Value

false if string is null, true otherwise.

## See Also

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)