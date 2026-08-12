---
title: UnknownToObject()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แปลงประเภทที่ไม่ทราบเป็น Object โดยรองรับทั้งกรณีประเภท smart pointer และ value type
type: docs
weight: 118
url: /th/system/objectext/unknowntoobject/
---
## ObjectExt::UnknownToObject(T) เมธอด

แปลงประเภทที่ไม่ทราบเป็น [Object](../../object/) โดยรองรับทั้งกรณีประเภท smart pointer และ value type.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(T obj)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทที่จะทำการแปลงเป็น [Object](../../object/). |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | T | [Object](../../object/) เพื่อแปลง. |

### ค่าที่ส่งคืน

Smart pointer ไปยัง [Object](../../object/) ซึ่งอาจเป็น pointer ที่แปลงแล้วหรือค่าที่บรรจุแบบ boxed.

## ObjectExt::UnknownToObject(const T\&) เมธอด

แปลงประเภทที่ไม่ทราบเป็น [Object](../../object/) โดยรองรับทั้งกรณีประเภท smart pointer และ value type.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(const T &obj)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทที่จะทำการแปลงเป็น [Object](../../object/). |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) เพื่อแปลง. |

### ค่าที่ส่งคืน

Smart pointer ไปยัง [Object](../../object/) ซึ่งอาจเป็น pointer ที่แปลงแล้วหรือค่าที่บรรจุแบบ boxed.

## ดูเพิ่มเติม

* คลาส [SmartPtr](../../smartptr/)
* คลาส [Object](../../object/)
* คลาส [ObjectExt](../)
* โครงสร้าง [IsSmartPtr](../../issmartptr/)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)