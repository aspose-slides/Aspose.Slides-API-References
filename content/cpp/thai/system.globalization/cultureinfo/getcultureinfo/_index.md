---
title: GetCultureInfo()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ดึงข้อมูลวัฒนธรรมโดยใช้ชื่อ. เหมือนกับ CreateSpecificCulture.
type: docs
weight: 586
url: /th/system.globalization/cultureinfo/getcultureinfo/
---
## CultureInfo::GetCultureInfo(const String\&) เมธอด


ดึงข้อมูลวัฒนธรรมโดยใช้ชื่อ. เหมือนกับ CreateSpecificCulture.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | ชื่อวัฒนธรรมที่กำหนดไว้ล่วงหน้าหรือชื่อของออบเจ็กต์วัฒนธรรมที่มีอยู่. |

### ค่าที่ส่งคืน

ออบเจ็กต์วัฒนธรรมที่สร้างใหม่.

## CultureInfo::GetCultureInfo(const String\&, const String\&) เมธอด


ดึงข้อมูลวัฒนธรรมโดยใช้ชื่อ.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name, const String &text_and_compare_culture_name)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | ชื่อวัฒนธรรม. |
| text_and_compare_culture_name | const [String](../../../system/string/)\& | ชื่อวัฒนธรรมที่ใช้สำหรับ [TextInfo](../../textinfo/) และ [CompareInfo](../../compareinfo/) ออบเจ็กต์. |

### ค่าที่ส่งคืน

ออบเจ็กต์วัฒนธรรม.

## CultureInfo::GetCultureInfo(int32_t) เมธอด


ดึงข้อมูลวัฒนธรรมโดยใช้รหัส.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(int32_t culture)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| culture | **int32_t** | ตัวระบุวัฒนธรรม. |

### ค่าที่ส่งคืน

ออบเจ็กต์วัฒนธรรมที่สร้างใหม่.

## ดูเพิ่มเติม

* Typedef [CultureInfoPtr](../../cultureinfoptr/)
* คลาส [String](../../../system/string/)
* คลาส [CultureInfo](../)
* เนมสเปส [System::Globalization](../../)
* ไลบรารี [Aspose.Slides](../../../)