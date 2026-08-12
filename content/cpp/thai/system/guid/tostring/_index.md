---
title: ToString()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แปลง GUID ที่เป็นตัวแทนของอ็อบเจ็กต์ปัจจุบันเป็นรูปแบบสตริงของมัน
type: docs
weight: 79
url: /th/system/guid/tostring/
---
## Guid::ToString() const เมธอด

แปลง GUID ที่เป็นตัวแทนของอ็อบเจ็กต์ปัจจุบันเป็นรูปแบบสตริงของมัน

```cpp
String System::Guid::ToString() const
```

## Guid::ToString(const String\&) const เมธอด

แปลง GUID ที่เป็นตัวแทนของอ็อบเจ็กต์ปัจจุบันเป็นรูปแบบสตริงโดยใช้รูปแบบสตริงที่ระบุ

```cpp
String System::Guid::ToString(const String &format) const
```

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| format | const [String](../../string/)\& | รูปแบบที่ใช้ |

### Return Value

การแสดงผลสตริงของค่าตัว GUID ที่เป็นตัวแทนของอ็อบเจ็กต์ปัจจุบัน

## Guid::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const เมธอด

แปลง GUID ที่เป็นตัวแทนของอ็อบเจ็กต์ปัจจุบันเป็นรูปแบบสตริงโดยใช้รูปแบบสตริงและ Culture ที่ระบุ

```cpp
String System::Guid::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| format | const [String](../../string/)\& | รูปแบบที่ใช้ |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | วัฒนธรรมที่ใช้ |

### Return Value

การแสดงผลสตริงของค่าตัว GUID ที่เป็นตัวแทนของอ็อบเจ็กต์ปัจจุบัน

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Guid](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)