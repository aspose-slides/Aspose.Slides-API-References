---
title: GetCustomAttributes()
second_title: Aspose.Slides for C++ API Reference
description: Returns an array containing objects that represent all custom attributes applied to the type represented by the current object.
type: docs
weight: 66
url: /cpp/system.reflection/memberinfo/getcustomattributes/
---
## MemberInfo::GetCustomAttributes(const TypeInfo\&, bool) const method


Returns an array containing objects that represent all custom attributes applied to the type represented by the current object.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit=false) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| attributeType | const [TypeInfo](../../../system/typeinfo/)\& | Type of attribute to look for. |
| inherit | **bool** | Whether to check inherited attributes, too. |

## MemberInfo::GetCustomAttributes(bool) const method


Returns an array containing objects that represent all custom attributes applied to the type represented by the current object.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(bool inherit=false) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| inherit | **bool** | Whether to check inherited attributes, too. |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [MemberInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.Slides](../../../)