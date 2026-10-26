---
title: MakeArray()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ฟังก์ชันแฟกทอรีที่สร้างอ็อบเจ็กต์ Array ใหม่ เติมด้วยองค์ประกอบจากรายการกำหนดค่าเริ่มต้นที่ระบุและคืนค่า smart pointer ที่ชี้ไปยังอ็อบเจ็กต์ Array.
type: docs
weight: 2029
url: /th/system/makearray/
---
## System::MakeArray(std::initializer_list\<T\>) function

ฟังก์ชันแฟกทอรีที่สร้างอ็อบเจ็กต์ [Array](../array/) ใหม่ เติมด้วยองค์ประกอบจากรายการกำหนดค่าเริ่มต้นที่ระบุและคืนค่า smart pointer ที่ชี้ไปยังอ็อบเจ็กต์ [Array](../array/)

```cpp
template<typename T> ArrayPtr<T> System::MakeArray(std::initializer_list<T> init)
```

### Template parameters

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบของอ็อบเจ็กต์ [Array](../array/) ที่ฟังก์ชันสร้าง |

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| init | std::initializer_list\<T\> | รายการกำหนดค่าเริ่มต้นที่มีองค์ประกอบที่จะเติมลงในอาร์เรย์ |

### ค่าที่ส่งกลับ

smart pointer ที่ชี้ไปยังอ็อบเจ็กต์ [Array](../array/) ที่สร้างขึ้น

## System::MakeArray(Args\&&...) function

ฟังก์ชันแฟกทอรีที่สร้างอ็อบเจ็กต์ [Array](../array/) ใหม่โดยส่งอาร์กิวเมนต์ที่ระบุไปยังคอนสตรัคเตอร์ของมัน

```cpp
template<class T,class...> ArrayPtr<T> System::MakeArray(Args &&... args)
```

### Template parameters

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบของอ็อบเจ็กต์ [Array](../array/) ที่ฟังก์ชันสร้าง |

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| args | Args\&&... | อาร์กิวเมนต์ที่ส่งไปยังคอนสตรัคเตอร์ของอ็อบเจ็กต์ [Array](../array/) ที่กำลังสร้าง |

### ค่าที่ส่งกลับ

smart pointer ที่ชี้ไปยังอ็อบเจ็กต์ [Array](../array/) ที่สร้างขึ้น

## System::MakeArray(Integral, Args\&&...) function

ฟังก์ชันแฟกทอรีที่สร้างอ็อบเจ็กต์ [Array](../array/) ใหม่โดยส่งอาร์กิวเมนต์ที่ระบุไปยังคอนสตรัคเตอร์ของมัน

```cpp
template<class T,class Integral,class...> std::enable_if<std::is_integral<Integral>::value, ArrayPtr<T>>::type System::MakeArray(Integral size, Args &&... args)
```

### Template parameters

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบของอ็อบเจ็กต์ [Array](../array/) ที่ฟังก์ชันสร้าง |
| Integral | ประเภทของขนาดอาร์เรย์ |

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| size | Integral | ขนาดของอาร์เรย์ที่กำลังสร้าง |
| args | Args\&&... | อาร์กิวเมนต์ที่ส่งไปยังคอนสตรัคเตอร์ของอ็อบเจ็กต์ [Array](../array/) ที่กำลังสร้าง |

### ค่าที่ส่งกลับ

smart pointer ที่ชี้ไปยังอ็อบเจ็กต์ [Array](../array/) ที่สร้างขึ้น

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../arrayptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)