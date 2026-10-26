---
title: Append()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: เพิ่มอักขระในตัวสร้าง.
type: docs
weight: 118
url: /th/system.text/stringbuilder/append/
---
## StringBuilder::Append(char_t) เมธอด


เพิ่มตัวอักษรลงใน builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| c | char_t | ค่าตัวอักษร. |

### ค่าที่ส่งคืน

ตัวชี้นี้.

## StringBuilder::Append(char_t, int) เมธอด


เพิ่มตัวอักษรหลายตัวลงใน builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c, int count)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| c | char_t | ค่าตัวอักษร. |
| count | int | จำนวนครั้งที่ต้องทำซ้ำตัวอักษรที่แทรก. |

### ค่าที่ส่งคืน

ตัวชี้นี้.

## StringBuilder::Append(const ArrayPtr\<char_t\>\&) เมธอด


เพิ่มอาร์เรย์ของตัวอักษรลงใน builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | ตัวอักษรที่จะเพิ่ม. |

### ค่าที่ส่งคืน

ตัวชี้นี้.

## StringBuilder::Append(const ArrayPtr\<char_t\>\&, int, int) เมธอด


เพิ่มส่วนย่อยของอาร์เรย์ตัวอักษรลงใน builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr, int startIndex, int charCount)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | ตัวอักษรที่จะเพิ่ม. |
| startIndex | int | ดัชนีเริ่มต้นของส่วนย่อย. |
| charCount | int | ความยาวของส่วนย่อย. |

### ค่าที่ส่งคืน

ตัวชี้นี้.

## StringBuilder::Append(const String\&) เมธอด


เพิ่มสตริงลงใน builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) เพื่อเพิ่ม. |

### ค่าที่ส่งคืน

ตัวชี้นี้.

## StringBuilder::Append(const String\&, int, int) เมธอด


เพิ่มส่วนย่อยของสตริงลงใน builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str, int startIndex, int charCount)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) เพื่อเพิ่ม. |
| startIndex | int | ดัชนีเริ่มต้นของส่วนย่อย. |
| charCount | int | ความยาวของส่วนย่อย. |

### ค่าที่ส่งคืน

ตัวชี้นี้.

## StringBuilder::Append(const SharedPtr\<T\>\&) เมธอด


เพิ่มการแสดงผลเป็นสตริงของอ็อบเจกต์ลงใน builder.

```cpp
template<class T> StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<T> &obj)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | [Object](../../../system/object/) ประเภท. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<T\>\& | [Object](../../../system/object/) เพื่อทำซีเรียลไลซ์และเพิ่ม. |

### ค่าที่ส่งคืน

ตัวชี้นี้.

## StringBuilder::Append(const SharedPtr\<StringBuilder\>\&) เมธอด


เพิ่มเนื้อหาของ builder ลงใน builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<StringBuilder> &builder)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| builder | const [SharedPtr](../../../system/sharedptr/)\<[StringBuilder](../)\>\& | Builder ที่จะเพิ่มเนื้อหามาจาก. |

### ค่าที่ส่งคืน

ตัวชี้นี้.

## StringBuilder::Append(float) เมธอด


เพิ่มค่าแบบ floating point ลงใน builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(float f)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| f | **float** | ค่าที่จะทำซีเรียลไลซ์และเพิ่ม. |

### ค่าที่ส่งคืน

ตัวชี้นี้.

## StringBuilder::Append(double) เมธอด


เพิ่มค่าแบบ floating point ลงใน builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(double df)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| df | **double** | ค่าที่จะทำซีเรียลไลซ์และเพิ่ม. |

### ค่าที่ส่งคืน

ตัวชี้นี้.

## StringBuilder::Append(int) เมธอด


เพิ่มค่าจำนวนเต็มลงใน builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(int i)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| i | int | ค่าที่จะทำซีเรียลไลซ์และเพิ่ม. |

### ค่าที่ส่งคืน

ตัวชี้นี้.

## StringBuilder::Append(T) เมธอด


เพิ่มค่าตัวเลขลงใน builder.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Append(T value)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทเชิงคณิตศาสตร์. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | T | ค่าที่จะทำซีเรียลไลซ์และเพิ่ม. |

### ค่าที่ส่งคืน

ตัวชี้นี้.

## StringBuilder::Append(E) เมธอด


เพิ่มการแสดงผลเป็นสตริงของค่า enum ลงใน builder.

```cpp
template<class E> std::enable_if<std::is_enum<E>::value, StringBuilder *>::type System::Text::StringBuilder::Append(E e)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| E | [Enum](../../../system/enum/) ประเภท. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| e | E | ค่าที่จะทำซีเรียลไลซ์และเพิ่ม. |

### ค่าที่ส่งคืน

ตัวชี้นี้.

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [StringBuilder](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [System::Text](../../)
* ไลบรารี [Aspose.Slides](../../../)