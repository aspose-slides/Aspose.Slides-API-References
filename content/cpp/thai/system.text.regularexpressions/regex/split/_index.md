---
title: Split()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แยกสตริงตามการจับคู่ของ regex.
type: docs
weight: 105
url: /th/system.text.regularexpressions/regex/split/
---
## Regex::Split(const String\&) เมธอด


แยกสตริงตามการจับคู่ของ regex.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) เพื่อแยก. |

### ค่าที่คืนกลับ

[Array](../../../system/array/) ของสตริงย่อยระหว่างการจับคู่.

## Regex::Split(const String\&, int) เมธอด


แยกสตริงตามการจับคู่ของ regex.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) เพื่อแยก. |
| count | int | จำนวนสตริงย่อยจำกัด. |

### ค่าที่คืนกลับ

[Array](../../../system/array/) ของสตริงย่อยระหว่างการจับคู่.

## Regex::Split(const String\&, int, int) เมธอด


แยกสตริงอินพุตเป็นจำนวนครั้งสูงสุดที่กำหนดเป็นอาเรย์ของสตริงย่อย ตามตำแหน่งที่กำหนดโดยนิพจน์ปกติที่ระบุในคอนสตรัคเตอร์ [Regex](../). การค้นหาลวดลายของนิพจน์ปกติจะเริ่มที่ตำแหน่งอักขระที่ระบุในสตริงอินพุต.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count, int startat)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | สตริงที่จะถูกแยก. |
| count | int | จำนวนสูงสุดที่การแยกสามารถเกิดขึ้นได้. |
| startat | int | ตำแหน่งอักขระในสตริงอินพุตที่การค้นหาจะเริ่มต้น. |

### ค่าที่คืนกลับ

อาเรย์ของสตริง.

## Regex::Split(const String\&, const String\&, RegexOptions, TimeSpan) เมธอด


แยกสตริงตาม regexp.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | สตริงอินพุต. |
| pattern | const [String](../../../system/string/)\& | ลวดลาย Regexp. |
| options | [RegexOptions](../../regexoptions/) | ตัวเลือกการจับคู่. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | หมดเวลา. |

### ค่าที่คืนกลับ

[Array](../../../system/array/) ของสตริงระหว่างการจับคู่.

## Regex::Split(const String\&, const String\&, int, RegexOptions, TimeSpan) เมธอด


แยกสtring ตาม regexp.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, int count, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | สตริงอินพุต. |
| pattern | const [String](../../../system/string/)\& | ลวดลาย Regexp. |
| count | int | [Match](../../match/) ข้อจำกัดจำนวน. |
| options | [RegexOptions](../../regexoptions/) | ตัวเลือกการจับคู่. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | หมดเวลา. |

### ค่าที่คืนกลับ

[Array](../../../system/array/) ของสตริงระหว่างการจับคู่.

## ดูเพิ่มเติม

* เอนัม [RegexOptions](../../regexoptions/)
* ประเภทกำหนด [ArrayPtr](../../../system/arrayptr/)
* คลาส [String](../../../system/string/)
* คลาส [Regex](../)
* คลาส [TimeSpan](../../../system/timespan/)
* เนมสเปซ [System::Text::RegularExpressions](../../)
* ไลบรารี [Aspose.Slides](../../../)