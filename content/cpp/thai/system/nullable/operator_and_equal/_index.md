---
title: operator&=()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: นำ operator&=() ไปใช้กับค่าที่อ็อบเจ็กต์ปัจจุบันเป็นตัวแทนโดยใช้ค่าที่ระบุเป็นอาร์กิวเมนต์ด้านขวา
type: docs
weight: 274
url: /th/system/nullable/operator_and_equal/
---
## Nullable::operator&=(bool) เมธอด


นำ [operator&=()](./) ไปใช้กับค่าที่อ็อบเจกต์ปัจจุบันโดยใช้ค่าที่ระบุเป็นอาร์กิวเมนต์ด้านขวา.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator&=(bool other)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | พารามิเตอร์แม่แบบที่ทำให้ SFINAE ทำงาน |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| other | **bool** | ค่าบูลีนที่ใช้เป็นค่าด้านขวาของ [operator&=()](./) ที่นำไปใช้กับค่าที่อ็อบเจกต์ปัจจุบันเป็นตัวแทน |

### ค่าที่ส่งคืน

อ้างอิงถึงตัวเอง.

## ดูเพิ่มเติม

* คลาส [Nullable](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)