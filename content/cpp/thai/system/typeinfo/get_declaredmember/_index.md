---
title: get_DeclaredMember()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: รับรายการของสมาชิกที่มีชื่อที่ระบุ
type: docs
weight: 508
url: /th/system/typeinfo/get_declaredmember/
---
## TypeInfo::get_DeclaredMember(const String\&) const เมธอด

รับรายการของสมาชิกที่มีชื่อที่ระบุ.

```cpp
ArrayPtr<SharedPtr<System::Reflection::MemberInfo>> System::TypeInfo::get_DeclaredMember(const String &name) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | const [String](../../string/)\& | ชื่อของสมาชิกที่ต้องการรับ. |

### ค่าที่ส่งคืน

[Array](../../array/) ของตัวบรรยายสมาชิก (ว่างหากไม่พบสมาชิก).

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* คลาส [MemberInfo](../../../system.reflection/memberinfo/)
* คลาส [String](../../string/)
* คลาส [TypeInfo](../)
* เนมสเปซ [System](../../)
* Library [Aspose.Slides](../../../)