---
title: Replace()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แทนที่การจับคู่ทั้งหมดของ regex ในสตริงด้วยสตริงการแทนที่.
type: docs
weight: 92
url: /th/system.text.regularexpressions/regex/replace/
---
## Regex::Replace(const String\&, const String\&) method

แทนที่การจับคู่ทั้งหมดของ regex ในสตริงด้วยสตริงการแทนที่.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | สตริงอินพุต. |
| replacement | const [String](../../../system/string/)\& | สตริงการแทนที่. |

### ค่าที่ส่งคืน

สตริงอินพุตที่มีการแทนที่ทั้งหมดของ regex ด้วยสตริงการแทนที่.

## Regex::Replace(const String\&, const char_t *) method

แทนที่การจับคู่ทั้งหมดของ regex ในสตริงด้วยสตริงการแทนที่.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *replacement)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | สตริงอินพุต. |
| replacement | const char_t * | สตริงการแทนที่. |

### ค่าที่ส่งคืน

สตริงอินพุตที่มีการแทนที่ทั้งหมดของ regex ด้วยสตริงการแทนที่.

## Regex::Replace(const String\&, const MatchEvaluator\&) method

แทนที่การจับคู่ทั้งหมดในสตริงด้วยสตริงการแทนที่ที่สร้างโดย delegate.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | สตริงอินพุต. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegate เพื่อสร้างสตริงการแทนที่ตามการจับคู่. |

### ค่าที่ส่งคืน

สตริงอินพุตที่มีการแทนที่ทั้งหมด.

## Regex::Replace(const String\&, const MatchEvaluator\&, int) method

แทนที่การจับคู่ทั้งหมดในสตริงด้วยสตริงการแทนที่ที่สร้างโดย delegate.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | สตริงอินพุต. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegate เพื่อสร้างสตริงการแทนที่ตามการจับคู่. |
| count | int | จำนวนครั้งจำกัดของการแทนที่. |

### ค่าที่ส่งคืน

สตริงอินพุตที่มีการแทนที่ทั้งหมด.

## Regex::Replace(const String\&, const MatchEvaluator\&, int, int) method

แทนที่การจับคู่ทั้งหมดในสตริงด้วยสตริงการแทนที่ที่สร้างโดย delegate.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count, int startat)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | สตริงอินพุต. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegate เพื่อสร้างสตริงการแทนที่ตามการจับคู่. |
| count | int | จำนวนครั้งจำกัดของการแทนที่. |
| startat | int | [Index](../../../system/index/) ในสตริงอินพุตเพื่อเริ่มการแทนที่ที่. |

### ค่าที่ส่งคืน

สตริงอินพุตที่มีการแทนที่ทั้งหมด.

## Regex::Replace(const String\&, const String\&, int) method

แทนที่ส่วนย่อยในสตริง. ยังไม่ได้ทำ.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count)
```

## Regex::Replace(const String\&, const String\&, int, int) method

แทนที่ส่วนย่อยในสตริง. ยังไม่ได้ทำ.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count, int startat)
```

## Regex::Replace(const String\&, const char_t *, const char_t *) method

แทนที่การจับคู่ทั้งหมดของ regex ในสตริงด้วยสตริงการแทนที่.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *pattern, const char_t *replacement)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | สตริงอินพุต. |
| pattern | const char_t * | [Regex](../) รูปแบบ. |
| replacement | const char_t * | สตริงการแทนที่. |

### ค่าที่ส่งคืน

สตริงอินพุตที่มีการแทนที่ทั้งหมดของ regex ด้วยสตริงการแทนที่.

## Regex::Replace(const String\&, const String\&, const char_t *) method

แทนที่การจับคู่ทั้งหมดของ regex ในสตริงด้วยสตริงการแทนที่.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const char_t *replacement)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | สตริงอินพุต. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) รูปแบบ. |
| replacement | const char_t * | สตริงการแทนที่. |

### ค่าที่ส่งคืน

สตริงอินพุตที่มีการแทนที่ทั้งหมดของ regex ด้วยสตริงการแทนที่.

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&, RegexOptions) method

แทนที่การจับคู่ทั้งหมดในสตริงด้วยสตริงการแทนที่ที่สร้างโดย delegate (ฟังก์ชัน static).

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator, RegexOptions options)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | สตริงอินพุต. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) รูปแบบ. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegate เพื่อสร้างสตริงการแทนที่ตามการจับคู่. |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) ตัวเลือก. |

### ค่าที่ส่งคืน

สตริงอินพุตที่มีการแทนที่ทั้งหมด.

## Regex::Replace(const String\&, const String\&, const String\&, RegexOptions) method

แทนที่การจับคู่ทั้งหมดของ regex ในสตริงด้วยสตริงการแทนที่.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement, RegexOptions options)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | สตริงอินพุต. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) รูปแบบ. |
| replacement | const [String](../../../system/string/)\& | สตริงการแทนที่. |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) ตัวเลือก. |

### ค่าที่ส่งคืน

สตริงอินพุตที่มีการแทนที่ทั้งหมดของ regex ด้วยสตริงการแทนที่.

## Regex::Replace(const String\&, const String\&, const String\&) method

แทนที่การจับคู่ของ regex.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | สตริงอินพุต. |
| pattern | const [String](../../../system/string/)\& | รูปแบบ Regexp. |
| replacement | const [String](../../../system/string/)\& | สตริงการแทนที่. |

### ค่าที่ส่งคืน

[String](../../../system/string/) ที่มีการแทนที่ทั้งหมด.

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&) method

แทนที่การจับคู่ของ regex.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | สตริงอินพุต. |
| pattern | const [String](../../../system/string/)\& | รูปแบบ Regexp. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegate เพื่อสร้างสตริงการแทนที่สำหรับแต่ละการจับคู่. |

### ค่าที่ส่งคืน

[String](../../../system/string/) ที่มีการแทนที่ทั้งหมด.

## ดูเพิ่มเติม

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)