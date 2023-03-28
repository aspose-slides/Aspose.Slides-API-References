---
title: GetCustomAttributes()
second_title: Aspose.Slides for C++ API Reference
description: Returns an array containing objects that represent all custom attributes applied to the type.
type: docs
weight: 534
url: /cpp/system/typeinfo/getcustomattributes/
---
## TypeInfo::GetCustomAttributes() const method


Returns an array containing objects that represent all custom attributes applied to the type.

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes() const
```

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [SmartPtr](../../smartptr/)
* Class [TypeInfo](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## TypeInfo::GetCustomAttributes(const [TypeInfo](../)\&, **bool**) const method


Returns an array containing objects that represent specific attributes applied to the type.

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | Type of the attribute to look for. |
| inherit | **bool** | Whether to look for inherited attributes as well. |

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [SmartPtr](../../smartptr/)
* Class [TypeInfo](../)
* Class [TypeInfo](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
