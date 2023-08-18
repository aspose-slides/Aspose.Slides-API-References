---
title: operator==()
second_title: Aspose.Slides for C++ API Reference
description: Determines if the current and the specified TypeInfo objects are equal.
type: docs
weight: 404
url: /system/typeinfo/operator_equal_equal/
---
## TypeInfo::operator==(const TypeInfo\&) const method


Determines if the current and the specified [TypeInfo](../) objects are equal.

```cpp
bool System::TypeInfo::operator==(const TypeInfo &info) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| info | const [TypeInfo](../)\& | The [TypeInfo](../) object to compare with |

### Return Value

True if the objects' hashes are equal, otherwise - false

## TypeInfo::operator==(std::nullptr_t) const method


Determines if the current [TypeInfo](../) object is a null-object, i.e. does not represent any type.

```cpp
bool System::TypeInfo::operator==(std::nullptr_t) const
```


### Return Value

True if the current [TypeInfo](../) object is a null-object, otherwise - false

## See Also

* Class [TypeInfo](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)