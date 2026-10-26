---
title: Match()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: จับคู่ regex กับสตริง.
type: docs
weight: 66
url: /th/system.text.regularexpressions/regex/match/
---
## Regex::Match(const String\&) เมธอด

จับคู่ regex กับสตริง.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | สตริงเป้าหมาย. |

### ค่าที่ส่งกลับ

[Match](../../match/) value containing match status and submatches.

## Regex::Match(const String\&, int, int) เมธอด

จับคู่ regex กับสตริง.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, int startat, int length=0)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | สตริงเป้าหมาย. |
| startat | int | ดัชนีเริ่มต้น. |
| length | int | จำนวนอักขระที่จะตรวจสอบ (0 เพื่อดูทั้งหมดของสตริง). |

### ค่าที่ส่งกลับ

[Match](../../match/) value containing match status and submatches.

## Regex::Match(const String\&, const String\&, RegexOptions, TimeSpan, int, int) เมธอด

จับคู่สตริงและรูปแบบ.

```cpp
static MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | สตริงอินพุต. |
| pattern | const [String](../../../system/string/)\& | แพทเทิร์น Regexp. |
| options | [RegexOptions](../../regexoptions/) | ตัวเลือกการจับคู่. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | เวลาหมด. |
| startat | int | [Match](../../match/) ตำแหน่งเริ่มต้น. |
| length | int | จำนวนอักขระที่จะตรวจสอบ (0 ปิดการจำกัด). |

### ค่าที่ส่งกลับ

พบการจับคู่แรก.

## ดูเพิ่มเติม

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchPtr](../../matchptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)