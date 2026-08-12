---
title: GetCustomAttributes()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: ส่งกลับอาร์เรย์ที่มีอ็อบเจกต์ซึ่งแสดงถึงแอตทริบิวต์แบบกำหนดเองทั้งหมดที่ถูกใช้กับชนิดนี้.
type: docs
weight: 586
url: /th/system/typeinfo/getcustomattributes/
---
## TypeInfo::GetCustomAttributes() const เมธอด


ส่งกลับอาร์เรย์ที่มีอ็อบเจกต์ซึ่งแสดงถึงแอตทริบิวต์แบบกำหนดเองทั้งหมดที่ถูกใช้กับชนิดนี้.

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes() const
```

## TypeInfo::GetCustomAttributes(const TypeInfo\&, bool) const เมธอด


ส่งกลับอาร์เรย์ที่มีอ็อบเจกต์ซึ่งแสดงถึงแอตทริบิวต์เฉพาะที่ถูกใช้กับชนิดนี้.

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit) const
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | ประเภทของแอตทริบิวต์ที่ต้องการค้นหา. |
| inherit | **bool** | กำหนดว่าจะค้นหาแอตทริบิวต์ที่สืบทอดมาด้วยหรือไม่. |

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../arrayptr/)
* Class [SmartPtr](../../smartptr/)
* Class [TypeInfo](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)