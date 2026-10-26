---
title: operator=()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: กำหนดค่า null ให้กับอ็อบเจกต์ปัจจุบัน.
type: docs
weight: 14
url: /th/system/nullable/operator_equal/
---
## Nullable::operator=(std::nullptr_t) เมธอด

กำหนดค่า null ให้กับอ็อบเจกต์ปัจจุบัน.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator=(std::nullptr_t)
```

### ค่าที่ส่งกลับ

อ็อบเจกต์ [Nullable](../) ที่แสดงค่า null-value.

## Nullable::operator=(const T1\&) เมธอด

แทนที่ค่าที่อ็อบเจกต์กำลังแสดงอยู่ด้วยค่าที่ระบุ

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value &&!std::is_null_pointer<T1>::value, Nullable<T> &>::type System::Nullable<T>::operator=(const T1 &x)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| The | ประเภทของค่าที่ใหม่ที่จะถูกแสดงโดยอ็อบเจกต์ปัจจุบัน |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | const T1\& | ค่าที่ใหม่ที่จะถูกแสดงโดยอ็อบเจกต์ปัจจุบัน |

### ค่าที่ส่งกลับ

อ้างอิงถึงตัวเอง

## Nullable::operator=(const Nullable\<T1\>\&) เมธอด

แทนที่ค่าที่อ็อบเจกต์กำลังแสดงอยู่ด้วยค่าที่ระบุ

```cpp
template<typename T1> Nullable<T> & System::Nullable<T>::operator=(const Nullable<T1> &x)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| The | ประเภทของค่าที่ใหม่ที่จะถูกแสดงโดยอ็อบเจกต์ปัจจุบัน |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | const [Nullable](../)\<T1\>\& | ค่าที่ใหม่ที่จะถูกแสดงโดยอ็อบเจกต์ปัจจุบัน |

### ค่าที่ส่งกลับ

อ้างอิงถึงตัวเอง

## ดูเพิ่มเติม

* คลาส [Nullable](../)
* โครงสร้าง [IsNullable](../../isnullable/)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)