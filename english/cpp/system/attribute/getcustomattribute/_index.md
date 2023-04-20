---
title: GetCustomAttribute()
second_title: Aspose.Slides for C++ API Reference
description: Returns a custom attribute of a specified type appllied to specified type.
type: docs
weight: 1
url: /cpp/system/attribute/getcustomattribute/
---
## Attribute::GetCustomAttribute(const TypeInfo\&, const TypeInfo\&) method


Returns a custom attribute of a specified type appllied to specified type.

```cpp
static Object::ptr System::Attribute::GetCustomAttribute(const TypeInfo &type, const TypeInfo &attributeType)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Type attribute of which is retrieved |
| attributeType | const [TypeInfo](../../typeinfo/)\& | Type of the attribute to retrieve |

### Return Value

A retrieved attribute or null if specified type does not have attribute of specified type.

## See Also

* Typedef [ptr](../../object/ptr/)
* Class [TypeInfo](../../typeinfo/)
* Class [Attribute](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)