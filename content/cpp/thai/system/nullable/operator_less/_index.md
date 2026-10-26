---
title: operator<()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: จะคืนค่าเป็น false เสมอ.
type: docs
weight: 170
url: /th/system/nullable/operator_less/
---
## Nullable::operator<(std::nullptr_t) const เมธอด

จะคืนค่าเป็น false เสมอ

```cpp
bool System::Nullable<T>::operator<(std::nullptr_t) const
```

## Nullable::operator<(const T1\&) const เมธอด

กำหนดว่าค่าที่ออบเจกต์ปัจจุบันแทนเป็นค่านั้นน้อยกว่าค่าที่ระบุหรือไม่โดยใช้ [operator<()](./) กับค่าทั้งสอง

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<(const T1 &other) const
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ชนิดของค่าที่จะเปรียบเทียบกับ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| other | const T1\& | การอ้างอิงค่าสมบูรณ์ของค่าที่จะเปรียบเทียบกับ |

### ค่าส่งกลับ

True หากค่าที่อ็อบเจกต์ปัจจุบันแทนเป็นค่านั้นน้อยกว่าค่าที่ระบุ, มิฉะนั้น - false

## Nullable::operator<(const Nullable\<T1\>\&) const เมธอด

กำหนดว่าค่าที่ออบเจกต์ปัจจุบันแทนเป็นค่านั้นน้อยกว่าค่าที่ออบเจกต์ [Nullable](../) ที่ระบุหรือไม่โดยใช้ [operator<()](./) กับค่าทั้งสอง

```cpp
template<typename T1> bool System::Nullable<T>::operator<(const Nullable<T1> &other) const
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ชนิดพื้นฐานของออบเจกต์ [Nullable](../) ที่จะเปรียบเทียบกับ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | การอ้างอิงค่าสมบูรณ์ของออบเจกต์ [Nullable](../) ที่จะเปรียบเทียบกับ |

### ค่าส่งกลับ

True หากค่าที่อ็อบเจกต์ปัจจุบันแทนเป็นค่านั้นน้อยกว่าค่าที่ออบเจกต์ [Nullable](../) ที่ระบุ, มิฉะนั้น - false

## ดูเพิ่มเติม

* คลาส [Nullable](../)
* โครงสร้าง [IsNullable](../../isnullable/)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)