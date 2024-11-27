---
title: GetMember()
second_title: Aspose.Slides for C++ API Reference
description: Gets list of the members with specified name.
type: docs
weight: 495
url: /system/typeinfo/getmember/
---
## TypeInfo::GetMember(const String\&) const method


Gets list of the members with specified name.

```cpp
ArrayPtr<SharedPtr<System::Reflection::MemberInfo>> System::TypeInfo::GetMember(const String &name) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../string/)\& | Name of the member to get. |

### Return Value

[Array](../../array/) of member descriptors (empty if no member is found).

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [MemberInfo](../../../system.reflection/memberinfo/)
* Class [String](../../string/)
* Class [TypeInfo](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)