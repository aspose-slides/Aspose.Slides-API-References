---
title: NullableBoolHelper()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ฟังก์ชันช่วยเหลือเพื่อตรวจสอบว่า this และ other ทั้งสองไม่เป็น null และเรียก lambda หากเป็นเช่นนั้น ใช้ใน implementation.s.
type: docs
weight: 105
url: /th/system/nullable/nullableboolhelper/
---
## Nullable::NullableBoolHelper(const T1\&, const std::function\<bool()>\&, bool) const เมธอด

ฟังก์ชันช่วยเหลือเพื่อตรวจสอบว่า this และ **other** ทั้งสองไม่เป็น null และเรียก lambda หากเป็นเช่นนั้น ใช้ใน implementation.s.

```cpp
template<typename T1> bool System::Nullable<T>::NullableBoolHelper(const T1 &other, const std::function<bool()> &f, bool default_if_both_are_null=false) const
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภท nullable อื่น |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| other | const T1\& | ค่า nullable อื่นที่เปรียบเทียบกับ |
| f | const std::function\<**bool**()>\& | Lambda ที่จะเรียกใช้หาก **this** และ **other** ทั้งสองไม่เป็น null |
| default_if_both_are_null | **bool** | ค่าที่ส่งคืนหากค่าทั้งสองเป็น null |

### ค่าที่ส่งคืน

false หาก **this** หรือ **other** เป็น null; **default_if_both_are_null** หากทั้งสองเป็น null; ผลลัพธ์ของการเรียก **f** หากทั้งสองไม่เป็น null

## ดูเพิ่มเติม

* คลาส [Nullable](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)