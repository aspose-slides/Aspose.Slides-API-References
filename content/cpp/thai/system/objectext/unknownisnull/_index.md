---
title: UnknownIsNull()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: ตรวจสอบว่าอ็อบเจ็กต์ประเภทไม่ทราบเป็น nullptr หรือไม่ การโอเวอร์โหลดสำหรับประเภทที่ไม่ใช่สเกลาร์
type: docs
weight: 144
url: /th/system/objectext/unknownisnull/
---
## ObjectExt::UnknownIsNull(T) เมธอด

ตรวจสอบว่าอ็อบเจ็กต์ประเภทไม่ทราบเป็น nullptr หรือไม่ การโอเวอร์โหลดสำหรับประเภทที่ไม่ใช่สเกลาร์

```cpp
template<typename T> static std::enable_if<!std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | [Object](../../object/) type. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | T | [Object](../../object/) เพื่อทำการตรวจสอบ. |

### ค่าที่ส่งกลับ

True if 'obj == nullptr' is true, false otherwise.

## ObjectExt::UnknownIsNull(T) เมธอด

ตรวจสอบว่าอ็อบเจ็กต์ประเภทไม่ทราบเป็น nullptr หรือไม่ การโอเวอร์โหลดสำหรับประเภทสเกลาร์

```cpp
template<typename T> static std::enable_if<std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | [Object](../../object/) type. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | T | [Object](../../object/) เพื่อทำการตรวจสอบ. |

### ค่าที่ส่งกลับ

Always returns false.

## ดูเพิ่มเติม

* คลาส [ObjectExt](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)