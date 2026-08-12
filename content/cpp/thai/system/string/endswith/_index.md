---
title: EndsWith()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ตรวจสอบว่าข้อความมีส่วนย่อยที่ระบุเป็นส่วนสุดท้ายหรือไม่.
type: docs
weight: 482
url: /th/system/string/endswith/
---
## String::EndsWith(const String\&) const method


ตรวจสอบว่าข้อความจบด้วยส่วนย่อยที่ระบุหรือไม่.

```cpp
bool System::String::EndsWith(const String &value) const
```


### อากิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../)\& | สตริงที่ค้นหา. |

### Return Value

true หากสตริงจบด้วยส่วนย่อยที่ระบุ, false ในกรณีอื่น.

## String::EndsWith(const String\&, System::StringComparison) const method


ตรวจสอบว่าข้อความจบด้วยส่วนย่อยที่ระบุหรือไม่.

```cpp
bool System::String::EndsWith(const String &value, System::StringComparison comparisonType) const
```


### อากิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../)\& | สตริงที่ค้นหา. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mode, see [System::StringComparison](../../stringcomparison/) for details. |

### Return Value

true หากสตริงจบด้วยส่วนย่อยที่ระบุ, false ในกรณีอื่น.

## String::EndsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const method


ตรวจสอบว่าข้อความจบด้วยส่วนย่อยที่ระบุหรือไม่.

```cpp
bool System::String::EndsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```


### อากิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [String](../)\& | สติงที่ค้นหา. |
| ignoreCase | **bool** | ระบุว่าการเปรียบเทียบเป็นแบบไม่แยกแยะตัวพิมพ์ใหญ่เล็กหรือไม่. |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | วัฒนธรรมที่ใช้ขณะทำการเปรียบเทียบสติง. |

### Return Value

true หากสติงจบด้วยส่วนย่อยที่ระบุ, false ในกรณีอื่น.

## ดูเพิ่มเติม

* enum [StringComparison](../../stringcomparison/)
* typedef [SharedPtr](../../sharedptr/)
* คลาส [String](../)
* คลาส [CultureInfo](../../../system.globalization/cultureinfo/)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)