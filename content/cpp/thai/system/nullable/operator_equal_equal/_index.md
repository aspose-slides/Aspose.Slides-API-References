---
title: operator==()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดว่าค่าที่อ็อบเจกต์ปัจจุบันแสดงเป็น null หรือไม่.
type: docs
weight: 118
url: /th/system/nullable/operator_equal_equal/
---
## Nullable::operator==(std::nullptr_t) const เมธอด

กำหนดว่าค่าที่แสดงโดยอ็อบเจกต์ปัจจุบันเป็น null หรือไม่.

```cpp
bool System::Nullable<T>::operator==(std::nullptr_t) const
```

### ค่าที่ส่งกลับ

จริง หากค่าที่แสดงโดยอ็อบเจกต์ปัจจุบันเป็น null, มิฉะนั้น - เท็จ

## Nullable::operator==(const T1\&) const เมธอด

กำหนดว่าค่าที่แสดงโดยอ็อบเจกต์ปัจจุบันเท่ากับค่าที่ระบุหรือไม่.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator==(const T1 &other) const
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภทของค่าที่จะเปรียบเทียบกับ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| other | const T1\& | อ้างอิงค่าคงที่ไปยังค่าที่จะเปรียบเทียบกับ |

### ค่าที่ส่งกลับ

จริง หากค่าที่แสดงโดยอ็อบเจกต์ปัจจุบันเท่ากับค่าที่ระบุ, มิฉะนั้น - เท็จ

## Nullable::operator==(const Nullable\<T1\>\&) const เมธอด

กำหนดว่าค่าที่แสดงโดยอ็อบเจกต์ปัจจุบันเท่ากับค่าที่แสดงโดยอ็อบเจกต์ [Nullable](../) ที่ระบุหรือไม่.

```cpp
template<typename T1> bool System::Nullable<T>::operator==(const Nullable<T1> &other) const
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภทพื้นฐานของอ็อบเจกต์ [Nullable](../) ที่จะเปรียบเทียบกับ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | อ้างอิงค่าคงที่ไปยังอ็อบเจกต์ [Nullable](../) ที่จะเปรียบเทียบกับ |

### ค่าที่ส่งกลับ

จริง หากค่าที่แสดงโดยอ็อบเจกต์ปัจจุบันเท่ากับค่าที่แสดงโดยอ็อบเจกต์ [Nullable](../) ที่ระบุ, มิฉะนั้น - เท็จ

## ดูเพิ่มเติม

* คลาส [Nullable](../)
* โครงสร้าง [IsNullable](../../isnullable/)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)