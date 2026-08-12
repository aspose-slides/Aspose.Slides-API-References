---
title: StartsWith()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: ตรวจสอบว่า string เริ่มต้นด้วยส่วนย่อยที่ระบุ.
type: docs
weight: 469
url: /th/system/string/startswith/
---
## String::StartsWith(const String\&) const เมธอด

ตรวจสอบว่า string เริ่มต้นด้วยส่วนย่อยที่ระบุ.

```cpp
bool System::String::StartsWith(const String &value) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../)\& | สตริงค้นหา. |

### ค่าที่คืนกลับ

true หาก string เริ่มต้นด้วยส่วนย่อยที่ระบุ, false มิฉะนั้น.

## String::StartsWith(const String\&, System::StringComparison) const เมธอด

ตรวจสอบว่า string เริ่มต้นด้วยส่วนย่อยที่ระบุ.

```cpp
bool System::String::StartsWith(const String &value, System::StringComparison comparisonType) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../)\& | สตริงค้นหา. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) โหมด, ดู [System::StringComparison](../../stringcomparison/) สำหรับรายละเอียด. |

### ค่าที่คืนกลับ

true หาก string เริ่มต้นด้วยส่วนย่อยที่ระบุ, false มิฉะนั้น.

## String::StartsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const เมธอด

ตรวจสอบว่า string เริ่มต้นด้วยส่วนย่อยที่ระบุ.

```cpp
bool System::String::StartsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../)\& | สตริงค้นหา. |
| ignoreCase | **bool** | กำหนดว่าการเปรียบเทียบเป็นแบบไม่สนใจตัวพิมพ์ใหญ่หรือไม่. |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | วัฒนธรรมที่ใช้ขณะทำการเปรียบเทียบสตริง. |

### ค่าที่คืนกลับ

true หาก string เริ่มต้นด้วยส่วนย่อยที่ระบุ, false มิฉะนั้น.

## ดูเพิ่มเติม

* enum [StringComparison](../../stringcomparison/)
* typedef [SharedPtr](../../sharedptr/)
* คลาส [String](../)
* คลาส [CultureInfo](../../../system.globalization/cultureinfo/)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)