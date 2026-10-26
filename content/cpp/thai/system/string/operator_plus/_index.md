---
title: operator+()
second_title: Aspose.Slides สำหรับ C++: เอกสารอ้างอิง API
description: ตัวดำเนินการต่อเชื่อมสตริง.
type: docs
weight: 274
url: /th/system/string/operator_plus/
---
## String::operator+(const String\&) const เมธอด


[String](../) ตัวดำเนินการต่อเชื่อม.

```cpp
String System::String::operator+(const String &str) const
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) เพื่อเพิ่มต่อท้ายของปัจจุบัน |

### ค่าที่ส่งกลับ

สตริงที่ต่อเชื่อม.

## String::operator+(const T\&) const เมธอด


[String](../) การต่อเชื่อมกับสตริงลิเทอรัลหรือพอยน์เตอร์สตริงอักขระ.

```cpp
template<typename T,std::enable_if_t< IsStringLiteral< T, char_t >::value > *> String System::String::operator+(const T &arg) const
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | หนึ่งในรูปแบบสตริงลิเทอรัลหรือพอยน์เตอร์สตริงอักขระ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| arg | const T\& | วัตถุเพื่อต่อเชื่อมกับสตริงปัจจุบัน |

### ค่าที่ส่งกลับ

สตริงที่ต่อเชื่อม.

## String::operator+(char_t) const เมธอด


เพิ่มอักขระต่อท้ายของสตริง.

```cpp
String System::String::operator+(char_t x) const
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| x | char_t | อักขระที่ต้องการเพิ่ม |

### ค่าที่ส่งกลับ

[String](../) ผลลัพธ์ของการต่อเชื่อม.

## String::operator+(int) const เมธอด


เพิ่มการแปลงค่าเต็มเป็นสตริงต่อท้ายของสตริง.

```cpp
String System::String::operator+(int i) const
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| i | int | ค่าจำนวนเต็มเพื่อแปลงเป็นสตริงและเพิ่ม |

### ค่าที่ส่งกลับ

[String](../) ผลลัพธ์ของการต่อเชื่อม.

## String::operator+(uint32_t) const เมธอด


เพิ่มการแสดงค่า unsigned integer เป็นสตริงต่อท้ายของสตริง.

```cpp
String System::String::operator+(uint32_t i) const
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| i | **uint32_t** | ค่าที่ต้องการแปลงเป็นสตริงและเพิ่ม |

### ค่าที่ส่งกลับ

[String](../) ผลลัพธ์ของการต่อเชื่อม.

## String::operator+(double) const เมธอด


เพิ่มการแสดงค่าทศนิยมเป็นสตริงต่อท้ายของสตริง.

```cpp
String System::String::operator+(double d) const
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| d | **double** | ค่าที่ต้องการแปลงเป็นสตริงและเพิ่ม |

### ค่าที่ส่งกลับ

[String](../) ผลลัพธ์ของการต่อเชื่อม.

## String::operator+(int64_t) const เมธอด


เพิ่มการแปลงค่าเต็มเป็นสตริงต่อท้ายของสตริง.

```cpp
String System::String::operator+(int64_t v) const
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| v | **int64_t** | ค่าที่ต้องการแปลงเป็นสตริงและเพิ่ม |

### ค่าที่ส่งกลับ

[String](../) ผลลัพธ์ของการต่อเชื่อม.

## String::operator+(const T\&) const เมธอด


เพิ่มการแสดงวัตถุประเภทอ้างอิงเป็นสตริงต่อท้ายของสตริง.

```cpp
template<typename T,std::enable_if_t< IsSmartPtr< T >::value > *> String System::String::operator+(const T &value) const
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทพอยน์เตอร์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) เพื่อแปลงเป็นสตริงโดยใช้การเรียก [ToString()](../tostring/) และเพิ่มไปยังสตริงปัจจุบัน |

### ค่าที่ส่งกลับ

[String](../) ผลลัพธ์ของการต่อเชื่อม.

## String::operator+(const T\&) const เมธอด


เพิ่มการแสดงวัตถุประเภทค่าเป็นสตริงต่อท้ายของสตริง.

```cpp
template<typename T,std::enable_if_t<!IsSmartPtr< T >::value &&!std::is_scalar< T >::value &&!std::is_array< T >::value > *> String System::String::operator+(const T &value) const
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทค่าที่จะเรียก [ToString()](../tostring/) |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) เพื่อแปลงเป็นสตริงโดยใช้การเรียก [ToString()](../tostring/) และเพิ่มไปยังสตริงปัจจุบัน |

### ค่าที่ส่งกลับ

[String](../) ผลลัพธ์ของการต่อเชื่อม.

## String::operator+(T) const เมธอด


เพิ่มการแสดงค่า boolean เป็นสตริงต่อท้ายของสตริง.

```cpp
template<typename T,std::enable_if_t< std::is_same< T, bool >::value > *> String System::String::operator+(T arg) const
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทค่าที่จะต่อเชื่อมกับสตริง ต้องเป็น bool |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| arg | T | [Boolean](../../boolean/) ค่าเพื่อแปลงเป็นสตริงและเพิ่ม |

### ค่าที่ส่งกลับ

[String](../) ผลลัพธ์ของการต่อเชื่อม.

## ดูเพิ่มเติม

* คลาส [String](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)