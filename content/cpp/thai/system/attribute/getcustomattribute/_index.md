---
title: GetCustomAttribute()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ส่งคืนแอตทริบิวต์แบบกำหนดเองของประเภทที่ระบุซึ่งใช้กับประเภทที่ระบุ
type: docs
weight: 1
url: /th/system/attribute/getcustomattribute/
---
## Attribute::GetCustomAttribute(const TypeInfo\&, const TypeInfo\&) เมธอด

ส่งคืนแอตทริบิวต์แบบกำหนดเองของประเภทที่ระบุซึ่งใช้กับประเภทที่ระบุ

```cpp
static Object::ptr System::Attribute::GetCustomAttribute(const TypeInfo &type, const TypeInfo &attributeType)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | แอตทริบิวต์ประเภทที่ถูกดึงคืน |
| attributeType | const [TypeInfo](../../typeinfo/)\& | ประเภทของแอตทริบิวต์ที่ต้องการดึงคืน |

### ค่าที่ส่งคืน

แอตทริบิวต์ที่ค้นคืนหรือ null หากประเภทที่ระบุไม่มีแอตทริบิวต์ของประเภทที่ระบุ

## ดูเพิ่มเติม

* Typedef [ptr](../../object/ptr/)
* Class [TypeInfo](../../typeinfo/)
* Class [Attribute](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)