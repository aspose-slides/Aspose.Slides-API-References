---
title: IsDefined()
second_title: Aspose.Slides for C++ API Reference
description: NOT IMPLEMENTED. Indicates whether one or more attributes of the specified type or of its derived types is applied to this member.
type: docs
weight: 157
url: /system/typeinfo/isdefined/
---
## TypeInfo::IsDefined(const TypeInfo\&, bool) const method


NOT IMPLEMENTED. Indicates whether one or more attributes of the specified type or of its derived types is applied to this member.

```cpp
bool System::TypeInfo::IsDefined(const TypeInfo &attributeType, bool inherit) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | The type of custom attribute to search for. The search includes derived types. |
| inherit | **bool** | true to search this member's inheritance chain to find the attributes; otherwise, false. This parameter is ignored for properties and events. |

### Return Value

true if one or more instances of attributeType or any of its derived types is applied to this member; otherwise, false.

## See Also

* Class [TypeInfo](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)