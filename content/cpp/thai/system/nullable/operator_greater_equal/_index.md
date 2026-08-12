---
title: operator>=()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: จะคืนค่าเป็น false เสมอ.
type: docs
weight: 183
url: /th/system/nullable/operator_greater_equal/
---
## Nullable::operator>=(std::nullptr_t) const method


จะคืนค่าเป็น false เสมอ.

```cpp
bool System::Nullable<T>::operator>=(std::nullptr_t) const
```


### ค่าที่ส่งคืน

Always - false

## Nullable::operator>=(const T1\&) const method


กำหนดว่าค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบันมากกว่าหรือเท่ากับค่าที่แสดงโดยอ็อบเจ็กต์ที่ระบุหรือไม่โดยการใช้ [operator>=()](./) กับค่าทั้งสองนี้.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>=(const T1 &other) const
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภทพื้นฐานของค่าที่จะเปรียบเทียบกับค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| other | const T1\& | การอ้างอิงแบบคงที่ไปยังอ็อบเจ็กต์ที่ใช้เปรียบเทียบกับอ็อบเจ็กต์ปัจจุบัน |

### ค่าที่ส่งคืน

True หากค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบันมากกว่าหรือเท่ากับค่าที่แสดงโดยอ็อบเจ็กต์ที่ระบุ, ไม่เช่นนั้น - false

## Nullable::operator>=(const Nullable\<T1\>\&) const method


กำหนดว่าค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบันมากกว่าหรือเท่ากับค่าที่แสดงโดยอ็อบเจ็กต์ [Nullable](../) ที่ระบุหรือไม่โดยการใช้ [operator>=()](./) กับค่าทั้งสองนี้.

```cpp
template<typename T1> bool System::Nullable<T>::operator>=(const Nullable<T1> &other) const
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภทพื้นฐานของอ็อบเจ็กต์ [Nullable](../) ที่จะเปรียบเทียบกับ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | การอ้างอิงแบบคงที่ไปยังอ็อบเจ็กต์ [Nullable](../) ที่จะเปรียบเทียบกับ |

### ค่าที่ส่งคืน

True หากค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบันมากกว่าหรือเท่ากับค่าที่แสดงโดยอ็อบเจ็กต์ [Nullable](../) ที่ระบุ, ไม่เช่นนั้น - false

## ดูเพิ่มเติม

* คลาส [Nullable](../)
* โครงสร้าง [IsNullable](../../isnullable/)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)