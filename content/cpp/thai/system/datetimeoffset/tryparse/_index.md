---
title: TryParse()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: พยายามแปลงสตริงที่ระบุเป็นอ็อบเจกต์ DateTimeOffset
type: docs
weight: 729
url: /th/system/datetimeoffset/tryparse/
---
## DateTimeOffset::TryParse(const String\&, DateTimeOffset\&) เมธอด

พยายามแปลงสตริงที่ระบุเป็นอ็อบเจกต์ [DateTimeOffset](../).

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, DateTimeOffset &result)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) ที่จะแปลง. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) ที่เทียบเท่ากับ **input**. |

### ค่าที่คืน

true หาก **input** แปลงสำเร็จ, ไม่เช่นนั้น - false.

## DateTimeOffset::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) เมธอด

พยายามแปลงสตริงที่ระบุเป็นอ็อบเจกต์ [DateTimeOffset](../) โดยใช้ผู้ให้รูปแบบที่ระบุและรูปแบบการจัดรูปแบบ.

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) ที่จะแปลง. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ผู้ให้รูปแบบ. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | รูปแบบการจัดรูปแบบวันที่และเวลา. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) ที่เทียบเท่ากับ **input**. |

### ค่าที่คืน

true หาก **input** แปลงสำเร็จ, ไม่เช่นนั้น - false.

## ดูเพิ่มเติม

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* คลาส [String](../../string/)
* คลาส [DateTimeOffset](../)
* คลาส [IFormatProvider](../../iformatprovider/)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)