---
title: TryParseExact()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: พยายามแปลงสตริงที่ระบุเป็นวัตถุ DateTimeOffset โดยใช้รูปแบบที่ระบุ, ผู้ให้รูปแบบและสไตล์การจัดรูปแบบ
type: docs
weight: 742
url: /th/system/datetimeoffset/tryparseexact/
---
## DateTimeOffset::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) เมธอด

พยายามแปลงสตริงที่ระบุเป็นวัตถุ [DateTimeOffset](../) โดยใช้รูปแบบที่ระบุ, ผู้ให้รูปแบบและรูปแบบการจัดรูปแบบ

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) เพื่อแปลง. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | อาร์เรย์ของสตริงรูปแบบ. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ผู้ให้รูปแบบ. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | สไตล์การจัดรูปแบบวันที่และเวลา. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) ที่เทียบเท่ากับ **input**. |

### ค่าที่ส่งกลับ

true หาก **input** แปลงสำเร็จ, มิฉะนั้น - false.

## DateTimeOffset::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) เมธอด

พยายามแปลงสตริงที่ระบุเป็นวัตถุ [DateTimeOffset](../) โดยใช้รูปแบบที่ระบุ, ผู้ให้รูปแบบและรูปแบบการจัดรูปแบบ

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) เพื่อแปลง. |
| format | const [String](../../string/)\& | สตริงรูปแบบ. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ผู้ให้รูปแบบ. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | สไตล์การจัดรูปแบบวันที่และเวลา. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) ที่เทียบเท่ากับ **input**. |

### ค่าที่ส่งกลับ

true หาก **input** แปลงสำเร็จ, มิฉะนั้น - false.

## ดูเพิ่มเติม

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* คลาส [String](../../string/)
* คลาส [IFormatProvider](../../iformatprovider/)
* คลาส [DateTimeOffset](../)
* เนมสเปซ [System](../../)
* Library [Aspose.Slides](../../../)