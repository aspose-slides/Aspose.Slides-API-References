---
title: Parse()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ส่งคืนอ็อบเจ็กต์ที่แสดงถึงค่าของคอนสแตนต์ enumeration ของประเภท enumeration ที่ระบุด้วยชื่อที่ระบุ
type: docs
weight: 27
url: /th/system/enumvaluesbase/parse/
---
## EnumValuesBase::Parse(const TypeInfo\&, const String\&, bool) เมธอด

Returns an object that represents a value of enumeration constant of the specified enumeration type with the specified name.

```cpp
static SharedPtr<Object> System::EnumValuesBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | อ็อบเจ็กต์ [TypeInfo](../../typeinfo/) ที่แสดงถึงประเภทของค่าคอนสแตนต์ enumeration ที่จะคืนค่า |
| str | const [String](../../string/)\& | ชื่อของคอนสแตนต์ enum |
| ignoreCase | **bool** | ระบุว่าควรละเว้นการแยกตัวพิมพ์ใหญ่/เล็กหรือไม่เมื่อตีความชื่อของคอนสแตนต์ enum |

### ค่าที่คืน

อ็อบเจ็กต์ที่แสดงถึงค่าของคอนสแตนต์ enum ที่มีชื่อระบุใน **str**.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../sharedptr/)
* คลาส [Object](../../object/)
* คลาส [TypeInfo](../../typeinfo/)
* คลาส [String](../../string/)
* คลาส [EnumValuesBase](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)