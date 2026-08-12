---
title: operator<=()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: จะคืนค่า false เสมอ.
type: docs
weight: 196
url: /th/system/nullable/operator_less_equal/
---
## Nullable::operator<=(std::nullptr_t) const เมธอด

จะคืนค่า false เสมอ.

```cpp
bool System::Nullable<T>::operator<=(std::nullptr_t) const
```

## Nullable::operator<=(const T1\&) const เมธอด

กำหนดว่าค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบันน้อยกว่าหรือเท่ากับค่าที่ระบุโดยการใช้ [operator<=()](./) กับค่าทั้งสองนี้.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<=(const T1 &other) const
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภทของค่าที่จะเปรียบเทียบกับ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| other | const T1\& | อ้างอิงคงที่ไปยังค่าที่จะเปรียบเทียบกับ |

### ค่าที่ส่งกลับ

True หากค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบันน้อยกว่าหรือเท่ากับค่าที่ระบุ, มิฉะนั้น - false

## Nullable::operator<=(const Nullable\<T1\>\&) const เมธอด

กำหนดว่าค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบันน้อยกว่าหรือเท่ากับค่าที่แสดงโดยอ็อบเจ็กต์ [Nullable](../) ที่ระบุโดยการใช้ [operator<=()](./) กับค่าทั้งสองนี้.

```cpp
template<typename T1> bool System::Nullable<T>::operator<=(const Nullable<T1> &other) const
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภทพื้นฐานของอ็อบเจ็กต์ [Nullable](../) ที่จะเปรียบเทียบกับ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | อ้างอิงคงที่ไปยังอ็อบเจ็กต์ [Nullable](../) ที่จะเปรียบเทียบกับ |

### ค่าที่ส่งกลับ

True หากค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบันน้อยกว่าหรือเท่ากับค่าที่แสดงโดยอ็อบเจ็กต์ [Nullable](../) ที่ระบุ, มิฉะนั้น - false

## ดูเพิ่มเติม

* คลาส [Nullable](../)
* โครงสร้าง [IsNullable](../../isnullable/)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)