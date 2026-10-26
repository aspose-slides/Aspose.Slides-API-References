---
title: ParseExact()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: แปลงสตริงที่ระบุเป็นอ็อบเจกต์ DateTimeOffset โดยใช้รูปแบบที่ระบุ, ตัวให้บริการรูปแบบ และสไตล์การจัดรูปแบบ
type: docs
weight: 716
url: /th/system/datetimeoffset/parseexact/
---
## DateTimeOffset::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) เมธอด

แปลงสตริงที่กำหนดเป็นอ็อบเจกต์ [DateTimeOffset](../) โดยใช้รูปแบบที่ระบุ, ผู้ให้บริการรูปแบบ และสไตล์การจัดรูปแบบ

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### พารามิเตอร์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) เพื่อแปลง. |
| format | const [String](../../string/)\& | สตริงรูปแบบ. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ผู้ให้บริการรูปแบบ. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | สไตล์การจัดรูปแบบวันที่และเวลา. |

### ค่าที่ส่งคืน

[DateTimeOffset](../) ที่เทียบเท่ากับ **input**.

## DateTimeOffset::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) เมธอด

แปลงสตริงที่กำหนดเป็นอ็อบเจกต์ [DateTimeOffset](../) โดยใช้รูปแบบที่ระบุหลายรูปแบบ, ผู้ให้บริการรูปแบบ และสไตล์การจัดรูปแบบ

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```

### พารามิเตอร์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) เพื่อแปลง. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) ของสตริงรูปแบบ. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ผู้ให้บริการรูปแบบ. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | สไตล์การจัดรูปแบบวันที่และเวลา. |

### ค่าที่ส่งคืน

[DateTimeOffset](../) ที่เทียบเท่ากับ **input**.

## ดูเพิ่มเติม

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* คลาส [DateTimeOffset](../)
* คลาส [String](../../string/)
* คลาส [IFormatProvider](../../iformatprovider/)
* เนมสเปซ [System](../../)
* Library [Aspose.Slides](../../../)