---
title: FindIndex()
second_title: Aspose.Slides สำหรับ C++ API เอกสารอ้างอิง
description: ค้นหาองค์ประกอบที่ตรงตามเงื่อนไขพิเศษ
type: docs
weight: 404
url: /th/system.collections.generic/list/findindex/
---
## List::FindIndex(System::Predicate\<T\>) เมธอด

ค้นหาองค์ประกอบที่ตรงตามเงื่อนไขที่กำหนด

```cpp
int System::Collections::Generic::List<T>::FindIndex(System::Predicate<T> match)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Predicate ที่ใช้ตรวจสอบองค์ประกอบ |

### ค่าที่ส่งคืน

[Index](../../../system/index/) ขององค์ประกอบที่ตรงกันหรือ -1 หากไม่พบ

## List::FindIndex(int, System::Predicate\<T\>) เมธอด

ค้นหาองค์ประกอบที่ตรงตามเงื่อนไขที่กำหนด

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, System::Predicate<T> match)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| startIndex | int | [Index](../../../system/index/) เพื่อเริ่มค้นหาจาก |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Predicate ที่ใช้ตรวจสอบองค์ประกอบ |

### ค่าที่ส่งคืน

[Index](../../../system/index/) ขององค์ประกอบที่ตรงกันหรือ -1 หากไม่พบ

## List::FindIndex(int, int, System::Predicate\<T\>) เมธอด

ค้นหาองค์ประกอบที่ตรงตามเงื่อนไขที่กำหนด

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, int count, System::Predicate<T> match)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| startIndex | int | [Index](../../../system/index/) เพื่อเริ่มค้นหาจาก |
| count | int | จำนวนขององค์ประกอบที่ต้องค้นหา |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Predicate ที่ใช้ตรวจสอบองค์ประกอบ |

### ค่าที่ส่งคืน

[Index](../../../system/index/) ขององค์ประกอบที่ตรงกันหรือ -1 หากไม่พบ

## ดูเพิ่มเติม

* Typedef [Predicate](../../../system/predicate/)
* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)