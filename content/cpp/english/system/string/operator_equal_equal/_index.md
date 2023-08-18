---
title: operator==()
second_title: Aspose.Slides for C++ API Reference
description: Equality comparison operator.
type: docs
weight: 287
url: /system/string/operator_equal_equal/
---
## String::operator==(const String\&) const method


Equality comparison operator.

```cpp
bool System::String::operator==(const String &str) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) to compare current one to. |

### Return Value

true if both strings are null or both are not null and match, false otherwise.

## String::operator==(std::nullptr_t) const method


Checks if string is null. Applies same logic as [IsNull()](../isnull/) call.

```cpp
bool System::String::operator==(std::nullptr_t) const
```


### Return Value

true if string is null, false otherwise.

## See Also

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)