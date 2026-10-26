---
title: Matches()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: รับการจับคู่ทั้งหมดของ regex ในสตริงที่กำหนดโดยทำการจับคู่ซ้ำหลายครั้ง.
type: docs
weight: 79
url: /th/system.text.regularexpressions/regex/matches/
---
## Regex::Matches(const String\&, int) เมธอด

รับการจับคู่ทั้งหมดของ regex ในสตริงที่ให้โดยทำการจับคู่ซ้ำหลายครั้ง

```cpp
MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, int startat=0)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | สตริงอินพุต. |
| startat | int | [Index](../../../system/index/) เพื่อเริ่มจับคู่ที่. |

### ค่าที่ส่งกลับ

คอลเลกชันของการจับคู่ทั้งหมดที่พบ.

## Regex::Matches(const String\&, const String\&, RegexOptions, TimeSpan, int, int) เมธอด

รับการจับคู่ทั้งหมดระหว่างสตริงและรูปแบบ

```cpp
static MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | สตริงอินพุต. |
| pattern | const [String](../../../system/string/)\& | รูปแบบ Regexp. |
| options | [RegexOptions](../../regexoptions/) | ตัวเลือกการจับคู่. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | หมดเวลา. |
| startat | int | [Match](../../match/) ตำแหน่งเริ่มต้น. |
| length | int | จำนวนอักขระที่ต้องตรวจสอบ (0 ปิดการจำกัด). |

### ค่าที่ส่งกลับ

การจับคู่ทั้งหมดที่พบโดยการจับคู่ซ้ำ.

## ดูเพิ่มเติม

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchCollectionPtr](../../matchcollectionptr/)
* คลาส [String](../../../system/string/)
* คลาส [Regex](../)
* คลาส [TimeSpan](../../../system/timespan/)
* เนมสเปซ [System::Text::RegularExpressions](../../)
* ไลบรารี [Aspose.Slides](../../../)