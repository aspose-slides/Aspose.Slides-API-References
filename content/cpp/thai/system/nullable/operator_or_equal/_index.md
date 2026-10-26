---
title: operator|=()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ใช้ operator|=() กับค่าที่ตัวอ็อบเจ็กต์ปัจจุบันแสดงโดยใช้ค่าที่กำหนดเป็นอาร์กิวเมนต์ด้านขวา.
type: docs
weight: 261
url: /th/system/nullable/operator_or_equal/
---
## Nullable::operator|=(bool) เมธอด

Applies [operator|=()](./) to the value represented by the current object using the specified value as a right-side argument.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator|=(bool other)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T1 | พารามิเตอร์แม่แบบเพื่อทำให้ SFINAE ทำงาน |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| other | **bool** | ค่าบูลีนที่ใช้เป็นค่าข้างขวาของ [operator|=()](./) ที่นำไปใช้กับค่าที่ตัวอ็อบเจ็กต์ปัจจุบันแสดง |

### ค่าที่ส่งคืน

อ้างอิงถึงออบเจ็กต์ตัวเอง

## ดูเพิ่มเติม

* คลาส [Nullable](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)