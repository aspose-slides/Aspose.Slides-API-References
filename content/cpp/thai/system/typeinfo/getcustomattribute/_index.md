---
title: GetCustomAttribute()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ค้นหาแอตทริบิวต์ที่กำหนดเองที่ใช้กับประเภทที่ระบุและใช้กับประเภทที่แสดงโดยวัตถุปัจจุบัน
type: docs
weight: 573
url: /th/system/typeinfo/getcustomattribute/
---
## TypeInfo::GetCustomAttribute(const TypeInfo\&) const เมธอด

Searches for the custom attribute applied having the specified type and applied to the type reprsented by the current object.

```cpp
ObjectPtr System::TypeInfo::GetCustomAttribute(const TypeInfo &attributeType) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | อ้างอิงคงที่ไปยังวัตถุ [TypeInfo](../) ที่แสดงประเภทของแอททริบิวต์เพื่อค้นหา |

### ค่าที่ส่งกลับ

ตัวชี้ไปยังวัตถุที่แสดงแอตทริบิวต์ที่ค้นพบ, หรือ null-pointer หากไม่มีแอตทริบิวต์ที่ตรงตามเงื่อนไขการค้นหา

## ดูเพิ่มเติม

* คลาส [SmartPtr](../../smartptr/)
* คลาส [TypeInfo](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)