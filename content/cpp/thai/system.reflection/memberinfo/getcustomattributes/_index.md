---
title: GetCustomAttributes()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ส่งกลับอาร์เรย์ที่มีอ็อบเจ็กต์ซึ่งแสดงถึงคุณลักษณะแบบกำหนดเองทั้งหมดที่ใช้กับประเภทที่อ็อบเจ็กต์ปัจจุบันเป็นตัวแทน
type: docs
weight: 66
url: /th/system.reflection/memberinfo/getcustomattributes/
---
## MemberInfo::GetCustomAttributes(const TypeInfo\&, bool) const เมธอด

ส่งกลับอาร์เรย์ที่มีอ็อบเจ็กต์ที่แสดงถึงคุณลักษณะแบบกำหนดเองทั้งหมดที่ใช้กับประเภทที่อ็อบเจ็กต์ปัจจุบันเป็นตัวแทน

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit=false) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| attributeType | const [TypeInfo](../../../system/typeinfo/)\& | ประเภทของคุณลักษณะที่ต้องการค้นหา |
| inherit | **bool** | ว่าจะตรวจสอบคุณลักษณะที่สืบทอดด้วยหรือไม่ |

## MemberInfo::GetCustomAttributes(bool) const เมธอด

ส่งกลับอาร์เรย์ที่มีอ็อบเจ็กต์ที่แสดงถึงคุณลักษณะแบบกำหนดเองทั้งหมดที่ใช้กับประเภทที่อ็อบเจ็กต์ปัจจุบันเป็นตัวแทน

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(bool inherit=false) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| inherit | **bool** | ว่าจะตรวจสอบคุณลักษณะที่สืบทอดด้วยหรือไม่ |

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [MemberInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.Slides](../../../)