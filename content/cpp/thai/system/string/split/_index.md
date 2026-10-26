---
title: Split()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: แยกสตริงตามอักขระ.
type: docs
weight: 768
url: /th/system/string/split/
---
## String::Split(char_t, StringSplitOptions) const เมธอด

แยกสตริงตามอักขระ.

```cpp
ArrayPtr<String> System::String::Split(char_t separator=u' ', StringSplitOptions opt=StringSplitOptions::None) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| separator | char_t | อักขระที่ใช้แยกสตริง |
| opt | [StringSplitOptions](../../stringsplitoptions/) | ตัวเลือกการแยก |

### ค่าที่คืนกลับ

[Array](../../array/) ของสตริงย่อย

## String::Split(char_t, int32_t, StringSplitOptions) const เมธอด

แยกสตริงตามอักขระ.

```cpp
ArrayPtr<String> System::String::Split(char_t separator, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| separator | char_t | อักขระที่ใช้แยกสตริง |
| count | **int32_t** | จำนวนสูงสุดของสตริงย่อยที่คืนกลับ |
| opt | [StringSplitOptions](../../stringsplitoptions/) | ตัวเลือกการแยก |

### ค่าที่คืนกลับ

[Array](../../array/) ของสตริงย่อย

## String::Split(char_t, char_t, StringSplitOptions) const เมธอด

แยกสตริงโดยหนึ่งในสองอักขระ.

```cpp
ArrayPtr<String> System::String::Split(char_t separatorA, char_t separatorB, StringSplitOptions opt=StringSplitOptions::None) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| separatorA | char_t | อักขระแรกที่ใช้แยกสตริง |
| separatorB | char_t | อักขระที่สองที่ใช้แยกสตริง |
| opt | [StringSplitOptions](../../stringsplitoptions/) | ตัวเลือกการแยก |

### ค่าที่คืนกลับ

[Array](../../array/) ของสตริงย่อย

## String::Split(const ArrayPtr\<char_t\>\&, StringSplitOptions) const เมธอด

แยกสตริงโดยอักขระที่ระบุ.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) ของอักขระตัวคั่น. หากว่าง, อักขระ whitespace ใดก็จะถือว่าเป็นตัวคั่น |
| opt | [StringSplitOptions](../../stringsplitoptions/) | ตัวเลือกการแยก |

### ค่าที่คืนกลับ

[Array](../../array/) ของสตริงย่อย

## String::Split(const ArrayPtr\<char_t\>\&, int32_t, StringSplitOptions) const เมธอด

แยกสตริงโดยอักขระที่ระบุ.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) ของอักขระตัวคั่น. หากว่าง, อักขระ whitespace ใดก็จะถือว่าเป็นตัวคั่น |
| count | **int32_t** | จำนวนสูงสุดของสตริงย่อยที่คืนกลับ |
| opt | [StringSplitOptions](../../stringsplitoptions/) | ตัวเลือกการแยก |

### ค่าที่คืนกลับ

[Array](../../array/) ของสตริงย่อย

## String::Split(const String\&, StringSplitOptions) const เมธอด

แยกสตริงตามสตริงย่อย.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, StringSplitOptions opt=StringSplitOptions::None) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| separator | const [String](../)\& | สตริงย่อยทำหน้าที่เป็นตัวคั่น. หากว่าง, อักขระ whitespace ทำหน้าที่เป็นตัวคั่น |
| opt | [StringSplitOptions](../../stringsplitoptions/) | ตัวเลือกการแยก |

### ค่าที่คืนกลับ

[Array](../../array/) ของสตริงย่อย

## String::Split(const String\&, int, StringSplitOptions) const เมธอด

แยกสตริงตามสตริงย่อย.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, int count, StringSplitOptions opt=StringSplitOptions::None) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| separator | const [String](../)\& | สตริงย่อยทำหน้าที่เป็นตัวคั่น. หากว่าง, อักขระ whitespace ทำหน้าที่เป็นตัวคั่น |
| count | int | จำนวนสูงสุดของสมาชิกในอาเรย์ที่แยก |
| opt | [StringSplitOptions](../../stringsplitoptions/) | ตัวเลือกการแยก |

### ค่าที่คืนกลับ

[Array](../../array/) ของสตริงย่อย

## String::Split(const ArrayPtr\<String\>\&, StringSplitOptions) const เมธอด

แยกสตริงตามสตริงย่อย.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) ของสตริงตัวคั่น. หากว่าง, จะไม่มีการแยก |
| opt | [StringSplitOptions](../../stringsplitoptions/) | ตัวเลือกการแยก |

### ค่าที่คืนกลับ

[Array](../../array/) ของสตริงย่อย

## String::Split(const ArrayPtr\<String\>\&, int, StringSplitOptions) const เมธอด

แยกสตริงตามสตริงย่อย. ปัจจุบันสนับสนุนเฉพาะอาร์เรย์ของตัวคั่นที่มีศูนย์หรือหนึ่งองค์ประกอบ.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, int count, StringSplitOptions opt=StringSplitOptions::None) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) ของสตริงตัวคั่น. หากว่าง, จะไม่มีการแยก |
| count | int | จำนวนสูงสุดของสมาชิกในอาเรย์ที่แยก |
| opt | [StringSplitOptions](../../stringsplitoptions/) | ตัวเลือกการแยก |

### ค่าที่คืนกลับ

[Array](../../array/) ของสตริงย่อย

## ดูเพิ่มเติม

* Enum [StringSplitOptions](../../stringsplitoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)