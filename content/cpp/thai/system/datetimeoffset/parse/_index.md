---
title: Parse()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แปลงสตริงที่ระบุตให้เป็นค่าเทียบเท่า DateTimeOffset.
type: docs
weight: 703
url: /th/system/datetimeoffset/parse/
---
## DateTimeOffset::Parse(const String\&) เมธอด


แปลงสตริงที่กำหนดให้เป็นค่าเทียบเท่า [DateTimeOffset](../).

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input)
```


### อาร์กิวเมนท์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) เพื่อแปลง. |

### ค่าที่ส่งคืน

[DateTimeOffset](../) ที่เทียบเท่ากับ **input**.

## DateTimeOffset::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) เมธอด


แปลงสตริงที่กำหนดให้เป็นอ็อบเจ็กต์ [DateTimeOffset](../) โดยใช้ผู้ให้บริการรูปแบบและสไตล์การจัดรูปแบบที่ระบุ.

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


### อาร์กิวเมนท์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) เพื่อแปลง. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ผู้ให้บริการรูปแบบ. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | สไตล์การจัดรูปแบบวันและเวลา. |

### ค่าที่ส่งคืน

[DateTimeOffset](../) ที่เทียบเท่ากับ **input**.

## ดูเพิ่มเติม

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* คลาส [DateTimeOffset](../)
* คลาส [String](../../string/)
* คลาส [IFormatProvider](../../iformatprovider/)
* เนมสเปซ [System](../../)
* Library [Aspose.Slides](../../../)