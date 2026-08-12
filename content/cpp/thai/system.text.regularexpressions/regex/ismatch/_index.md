---
title: IsMatch()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: จับคู่ regex กับสตริง.
type: docs
weight: 53
url: /th/system.text.regularexpressions/regex/ismatch/
---
## Regex::IsMatch(const String\&, int) เมธอด

ตรวจสอบ regex กับสตริง

```cpp
bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, int startat=0)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | สตริงเป้าหมาย. |
| startat | int | ดัชนีเริ่มต้น. |

### ค่าที่คืน

True หากสตริงตรงกับ regex, false ในกรณีอื่น

## Regex::IsMatch(const String\&, const String\&, RegexOptions, TimeSpan, int) เมธอด

ตรวจสอบว่าสตริงตรงกับรูปแบบหรือไม่

```cpp
static bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | สตริงอินพุต. |
| pattern | const [String](../../../system/string/)\& | รูปแบบ Regexp. |
| options | [RegexOptions](../../regexoptions/) | ตัวเลือกการจับคู่. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | เวลาหมด. |
| startat | int | [Match](../../match/) ตำแหน่งเริ่มต้น. |

### ค่าที่คืน

True หากพบการจับคู่, false หากไม่พบ

## ดูเพิ่มเติม

* Enum [RegexOptions](../../regexoptions/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)