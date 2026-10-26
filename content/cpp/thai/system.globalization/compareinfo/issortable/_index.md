---
title: IsSortable()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ตรวจสอบว่าตัวอักษรที่ระบุสามารถเรียงลำดับได้หรือไม่.
type: docs
weight: 196
url: /th/system.globalization/compareinfo/issortable/
---
## CompareInfo::IsSortable(char16_t) เมธอด


ตรวจสอบว่าตัวอักษรที่ระบุสามารถเรียงลำดับได้หรือไม่.

```cpp
static bool System::Globalization::CompareInfo::IsSortable(char16_t ch)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| ch | char16_t | อักขระ Unicode. |

### ค่าที่คืนกลับ

True หาก **ch** สามารถเรียงลำดับได้; มิฉะนั้น false.

## CompareInfo::IsSortable(const String\&) เมธอด


ตรวจสอบว่าสตริงที่ระบุสามารถเรียงลำดับได้หรือไม่.

```cpp
static bool System::Globalization::CompareInfo::IsSortable(const String &text)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | const [String](../../../system/string/)\& | สตริง. |

### ค่าที่คืนกลับ

True หาก **text** ไม่ว่างและอักขระทั้งหมดใน **text** สามารถเรียงลำดับได้; มิฉะนั้น false.

## ดูเพิ่มเติม

* คลาส [CompareInfo](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [System::Globalization](../../)
* ไลบรารี [Aspose.Slides](../../../)