---
title: GetCustomAttribute()
second_title: Aspose.Slides for C++ API Reference
description: Searches for the custom attribute applied having the specified type and applied to the type reprsented by the current object.
type: docs
weight: 521
url: /cpp/system/typeinfo/getcustomattribute/
---
## TypeInfo::GetCustomAttribute(const TypeInfo\&) const method


Searches for the custom attribute applied having the specified type and applied to the type reprsented by the current object.

```cpp
ObjectPtr System::TypeInfo::GetCustomAttribute(const TypeInfo &attributeType) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | The constant reference to the [TypeInfo](../) object representing the type of the attribute to search |

### Return Value

A pointer to an object representing the found attribute, or null-pointer if no attribute was foud matching the search criteria

## See Also

* Class [SmartPtr](../../smartptr/)
* Class [TypeInfo](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)