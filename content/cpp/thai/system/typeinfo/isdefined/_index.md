---
title: IsDefined()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ยังไม่ได้ดำเนินการ. ระบุว่าหนึ่งหรือหลายคุณลักษณะของประเภทที่ระบุหรือของประเภทที่สืบทอดมาถูกนำไปใช้กับสมาชิกนี้หรือไม่.
type: docs
weight: 157
url: /th/system/typeinfo/isdefined/
---
## TypeInfo::IsDefined(const TypeInfo\&, bool) const เมธอด

ยังไม่ได้ดำเนินการ. ระบุว่าหนึ่งหรือหลายคุณลักษณะของประเภทที่ระบุหรือของประเภทที่สืบทอดมาถูกนำไปใช้กับสมาชิกนี้หรือไม่.

```cpp
bool System::TypeInfo::IsDefined(const TypeInfo &attributeType, bool inherit) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | ประเภทของแอตทริบิวต์ที่กำหนดเองเพื่อค้นหา การค้นหารวมถึงประเภทที่สืบทอด |
| inherit | **bool** | true เพื่อค้นหาห่วงโซ่การสืบทอดของสมาชิกนี้เพื่อค้นหาแอตทริบิวต์; มิฉะนั้น false. พารามิเตอร์นี้จะถูกละเว้นสำหรับ properties และ events |

### ค่าที่ส่งคืน

true หากมีหนึ่งหรือหลายอินสแตนซ์ของ attributeType หรือประเภทที่สืบทอดใด ๆ ถูกนำไปใช้กับสมาชิกนี้; มิฉะนั้น false.

## ดูเพิ่มเติม

* คลาส [TypeInfo](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)