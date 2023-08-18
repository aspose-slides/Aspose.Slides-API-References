---
title: operator!=()
second_title: Aspose.Slides for C++ API Reference
description: Determines if the current and the specified TypeInfo objects are not equal.
type: docs
weight: 417
url: /system/typeinfo/operator_not_equal/
---
## TypeInfo::operator!=(const TypeInfo\&) const method


Determines if the current and the specified [TypeInfo](../) objects are not equal.

```cpp
bool System::TypeInfo::operator!=(const TypeInfo &info) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| info | const [TypeInfo](../)\& | The [TypeInfo](../) object to compare with |

### Return Value

True if the objects' hashes are not equal, otherwise - false

## TypeInfo::operator!=(std::nullptr_t) const method


Determines if the current [TypeInfo](../) object is not a null-object, i.e. it represents some type.

```cpp
bool System::TypeInfo::operator!=(std::nullptr_t) const
```


### Return Value

True if the current [TypeInfo](../) object is not a null-object, otherwise - false

## See Also

* Class [TypeInfo](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)