---
title: Parse()
second_title: Aspose.Slides สำหรับ C++ – อ้างอิง API
description: บรรจุค่าของค่าคงที่ enumeration ที่ระบุด้วยชื่อที่กำหนด พารามิเตอร์ระบุว่าจะละเว้นการแยกแยะตัวอักษรใหญ่/เล็กหรือไม่เมื่อแปลงสตริงที่ระบุชื่อของค่าคงที่ของ enumeration
type: docs
weight: 53
url: /th/system/boxedvaluebase/parse/
---
## BoxedValueBase::Parse(const TypeInfo\&, const String\&, bool) เมธอด


ทำการบรรจุค่าของค่าคงที่ของ enumeration ที่ระบุด้วยชื่อที่กำหนดไว้ พารามิเตอร์ระบุว่าจะละเว้นการแยกแยะตัวอักษรใหญ่/เล็กหรือไม่เมื่อแปลงสตริงที่ระบุชื่อของค่าคงที่ของ enumeration

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | ระบุประเภทของ enumeration |
| str | const [String](../../string/)\& | ชื่อของค่าคงที่ของ enumeration ที่ต้องบรรจุค่า |
| ignoreCase | **bool** | ระบุว่าควรละเว้นการแยกแยะตัวอักษรใหญ่/เล็กหรือไม่เมื่อแปลงสตริงที่แสดงชื่อของค่าคงที่ของ enumeration |

### ค่าที่ส่งกลับ

shared pointer ไปยังอ็อบเจกต์ที่แสดงค่าที่บรรจุของค่าคงที่ของ enumeration ที่ระบุ

## BoxedValueBase::Parse(const TypeInfo\&, const String\&) เมธอด


ทำการบรรจุค่ของค่าคงที่ของ enumeration ที่ระบุด้วยชื่อที่กำหนด

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | ระบุประเภทของ enumeration |
| str | const [String](../../string/)\& | ชื่อของค่าคงที่ของ enumeration ที่ต้องบรรจุค่า |

### ค่าที่ส่งกลับ

shared pointer ไปยังอ็อบเจกต์ที่แสดงค่าที่บรรจุของค่าคงที่ของ enumeration ที่ระบุ

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../sharedptr/)
* คลาส [Object](../../object/)
* คลาส [TypeInfo](../../typeinfo/)
* คลาส [String](../../string/)
* คลาส [BoxedValueBase](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)