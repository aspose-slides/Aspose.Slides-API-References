---
title: operator!=()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: กำหนดว่าค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบันไม่เป็น null.
type: docs
weight: 144
url: /th/system/nullable/operator_not_equal/
---
## Nullable::operator!=(std::nullptr_t) const เมธอด


ตรวจสอบว่าค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบันไม่เป็น null.

```cpp
bool System::Nullable<T>::operator!=(std::nullptr_t) const
```


### ค่าที่ส่งคืน

True if the value represented by the current object is not null, otherwise - false

## Nullable::operator!=(const T1\&) const เมธอด


ตรวจสอบว่าค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบันไม่เท่ากับค่าที่ระบุ

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator!=(const T1 &other) const
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | The type of the value to compare with |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| other | const T1\& | A constant reference to the value to compare with |

### ค่าที่ส่งคืน

True if the value represented by the current object is not equal to the specified value, otherwise - false

## Nullable::operator!=(const Nullable\<T1\>\&) const เมธอด


ตรวจสอบว่าค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบันไม่เท่ากับค่าที่แสดงโดยอ็อบเจ็กต์ [Nullable](../) ที่ระบุ

```cpp
template<typename T1> bool System::Nullable<T>::operator!=(const Nullable<T1> &other) const
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | The underlying type of the [Nullable](../) object to compare with |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | A constant reference to the [Nullable](../) object to compare with |

### ค่าที่ส่งคืน

True if the value represented by the current object is not equal to the value represented by the specified [Nullable](../) object, otherwise - false

## ดูเพิ่มเติม

* คลาส [Nullable](../)
* โครงสร้าง [IsNullable](../../isnullable/)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)