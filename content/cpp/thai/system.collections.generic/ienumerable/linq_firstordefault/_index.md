---
title: LINQ_FirstOrDefault()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: ส่งคืนอิลิเมนต์แรกของลำดับ, หรือค่าดีฟอลต์หากลำดับว่างเปล่า.
type: docs
weight: 66
url: /th/system.collections.generic/ienumerable/linq_firstordefault/
---
## IEnumerable::LINQ_FirstOrDefault() เมธอด

ส่งคืนอิลิเมนต์แรกของลำดับ, หรือค่าดีฟอลต์หากลำดับว่างเปล่า.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault()
```

### ค่าที่ส่งกลับ

อิลิเมนต์แรกในลำดับหรือค่าที่สร้างโดยค่าเริ่มต้นหากลำดับว่างเปล่า.

## IEnumerable::LINQ_FirstOrDefault(std::function\<bool(T)>) เมธอด

ส่งคืนอิลิเมนต์แรกของลำดับที่ตรงตามเงื่อนไขหรือค่าดีฟอลต์หากไม่พบอิลิเมนต์ดังกล่าว.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault(std::function<bool(T)> predicate)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | ฟังก์ชันที่ใช้ทดสอบแต่ละอิลิเมนต์ตามเงื่อนไข. |

### ค่าที่ส่งกลับ

default(T) หาก source ว่างเปล่าหรือไม่มีอิลิเมนต์ใดผ่านการทดสอบที่ระบุโดย predicate; มิฉะนั้น, จะเป็นอิลิเมนต์แรกใน source ที่ผ่านการทดสอบที่ระบุโดย predicate.

## ดูเพิ่มเติม

* คลาส [IEnumerable](../)
* เนมสเปซ [System::Collections::Generic](../../)
* ไลบรารี [Aspose.Slides](../../../)