---
title: operator==()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: 
type: docs
weight: 2042
url: /th/system/operator_equal_equal/
---
## System::operator==(ArraySegment\<T\>, ArraySegment\<T\>) ฟังก์ชัน




```cpp
template<typename T> bool System::operator==(ArraySegment<T> a, ArraySegment<T> b)
```

## System::operator==(std::nullptr_t, DateTime) ฟังก์ชัน




```cpp
constexpr bool System::operator==(std::nullptr_t, DateTime)
```

## System::operator==(std::nullptr_t, const DateTimeOffset\&) ฟังก์ชัน




```cpp
constexpr bool System::operator==(std::nullptr_t, const DateTimeOffset &)
```

## System::operator==(std::nullptr_t, const Nullable\<T\>\&) ฟังก์ชัน


กำหนดว่าวัตถุ [Nullable](../nullable/) ที่ระบุเป็นค่าที่เท่ากับ null หรือไม่

```cpp
template<typename T> bool System::operator==(std::nullptr_t, const Nullable<T> &other)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| other | std::nullptr_t | การอ้างอิงคงที่ไปยังวัตถุ [Nullable](../nullable/) เพื่อทดสอบ |

### ค่าที่คืน

True if the specified object represents null value, false otherwise

## System::operator==(const T1\&, const Nullable\<T2\>\&) ฟังก์ชัน


กำหนดว่าค่าที่ระบุเท่ากับค่าที่แทนโดยวัตถุ [Nullable](../nullable/) ที่ระบุโดยการนำ [operator==()](./) ไปใช้กับค่าเหล่านี้

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator==(const T1 &some, const Nullable<T2> &other)
```


### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ชนิดของค่าที่เปรียบเทียบตัวแรก |
| T2 | ชนิดพื้นฐานของวัตถุ [Nullable](../nullable/) ที่แทนค่าที่เปรียบเทียบตัวที่สอง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| some | const T1\& | การอ้างอิงคงที่ไปยังค่าที่จะใช้เป็นค่าที่เปรียบเทียบตัวแรก |
| other | const [Nullable](../nullable/)\<T2\>\& | การอ้างอิงคงที่ไปยังวัตถุ [Nullable](../nullable/) ที่ค่าที่แทนจะใช้เป็นค่าที่เปรียบเทียบตัวที่สอง |

### ค่าที่คืน

True if the comparands are equal, otherwise - false

## System::operator==(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) ฟังก์ชัน


เปรียบเทียบความเท่าเทียมของสมาร์ทพอยน์เตอร์สองตัว

```cpp
template<class X,class Y> bool System::operator==(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| X | ประเภทของพอยน์เตอร์ที่อ้างอิงแรก |
| Y | ประเภทของพอยน์เตอร์ที่อ้างอิงที่สอง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | พอยน์เตอร์แรกที่เปรียบเทียบ |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | พอยน์เตอร์ที่สองที่เปรียบเทียบ |

### ค่าที่คืน

True if pointers match, false otherwise.

## System::operator==(std::nullptr_t, SmartPtr\<X\> const\&) ฟังก์ชัน


ตรวจสอบว่าสมาร์ทพอยน์เตอร์เป็น null หรือไม่

```cpp
template<class X> bool System::operator==(std::nullptr_t, SmartPtr<X> const &x)
```


### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| X | ประเภทของพอยน์เตอร์ที่อ้างอิง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | std::nullptr_t | พอยน์เตอร์ที่ต้องตรวจสอบ |

### ค่าที่คืน

True if pointer is null, false otherwise.

## System::operator==(const SmartPtr\<X\>\&, const Y *) ฟังก์ชัน


การเปรียบเทียบความเท่าเทียมของสมาร์ทพอยน์เตอร์กับพอยน์เตอร์ (C) ธรรมดา

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const SmartPtr<X> &x, const Y *y)
```


### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| X | ประเภทของสมาร์ทพอยน์เตอร์ |
| Y | ประเภทของพอยน์เตอร์ธรรมดา |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | สมาร์ทพอยน์เตอร์ที่เปรียบเทียบ (ด้านซ้าย) |
| y | const Y * | พอยน์เตอร์ที่เปรียบเทียบ (ด้านขวา) |

### ค่าที่คืน

True if pointers match, false otherwise.

## System::operator==(const X *, const SmartPtr\<Y\>\&) ฟังก์ชัน


การเปรียบเทียบความเท่าเทียมของสมาร์ทพอยน์เตอร์กับพอยน์เตอร์ (C) ธรรมดา

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const X *x, const SmartPtr<Y> &y)
```


### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| X | ประเภทของพอยน์เตอร์ธรรมดา |
| Y | ประเภทของสมาร์ทพอยน์เตอร์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | const X * | พอยน์เตอร์ที่เปรียบเทียบ (ด้านขวา) |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | สมาร์ทพอยน์เตอร์ที่เปรียบเทียบ (ด้านซ้าย) |

### ค่าที่คืน

True if pointers match, false otherwise.

## System::operator==(T const\&, std::nullptr_t) ฟังก์ชัน


ตรวจสอบว่าวัตถุประเภทค่า (เช่น โครงสร้าง C# ที่แปลง) เป็น null หรือไม่

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(T const &x, std::nullptr_t)
```


### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทค่า |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | T const\& | [Object](../object/) ที่ต้องตรวจสอบ |

### ค่าที่คืน

True if object is null, false otherwise.

## System::operator==(std::nullptr_t, T const\&) ฟังก์ชัน


ตรวจสอบว่าวัตถุประเภทค่า (เช่น โครงสร้าง C# ที่แปลง) เป็น null หรือไม่

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(std::nullptr_t, T const &x)
```


### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทค่า |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | std::nullptr_t | [Object](../object/) ที่ต้องตรวจสอบ |

### ค่าที่คืน

True if object is null, false otherwise.

## System::operator==(Chars\&, const String\&) ฟังก์ชัน


การเปรียบเทียบ [String](../string/)

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator==(Chars &left, const String &right)
```


### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Chars | ชนิดตัวอักษรลิตเชอรัล [String](../string/) |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| left | Chars\& | ลิตเชอรัล [String](../string/) ที่ต้องเปรียบเทียบ |
| right | const [String](../string/)\& | [String](../string/) ที่ต้องเปรียบเทียบ |

### ค่าที่คืน

true if strings match, false otherwise.

## System::operator==(T\&, const String\&) ฟังก์ชัน


การเปรียบเทียบ [String](../string/)

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator==(T &left, const String &right)
```


### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดพอยน์เตอร์ [String](../string/) |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| left | T\& | พอยน์เตอร์ [String](../string/) ที่ต้องเปรียบเทียบ |
| right | const [String](../string/)\& | [String](../string/) ที่ต้องเปรียบเทียบ |

### ค่าที่คืน

true if strings match, false otherwise.

## System::operator==(const SharedPtr\<Object\>\&, const String\&) ฟังก์ชัน


การเปรียบเทียบ [Object](../object/) และสตริง

```cpp
bool System::operator==(const SharedPtr<Object> &left, const String &right)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | [Object](../object/) เพื่อแปลงเป็นสตริงและเปรียบเทียบ |
| right | const [String](../string/)\& | [String](../string/) ที่ต้องเปรียบเทียบ |

### ค่าที่คืน

true if object string representation equals to string, false otherwise.

## System::operator==(std::nullptr_t, const String\&) ฟังก์ชัน


ตรวจสอบว่าสตริงเป็น null หรือไม่

```cpp
bool System::operator==(std::nullptr_t, const String &str)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| str | std::nullptr_t | [String](../string/) ที่ต้องตรวจสอบ |

### ค่าที่คืน

true if string is null, false otherwise.

## System::operator==(std::nullptr_t, TimeSpan) ฟังก์ชัน




```cpp
constexpr bool System::operator==(std::nullptr_t, TimeSpan)
```

## System::operator==(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) ฟังก์ชัน


กำหนดว่าที่อยู่ URI ที่แทนโดยวัตถุปัจจุบันและวัตถุที่ระบุเป็นเท่ากันหรือไม่

```cpp
bool System::operator==(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | วัตถุ [Uri](../uri/) ตัวแรกที่ต้องเปรียบเทียบ |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | วัตถุ [Uri](../uri/) ตัวที่สองที่ต้องเปรียบเทียบ |

### ค่าที่คืน

True if URIs are equal, otherwise - false

## ดูเพิ่มเติม

* Typedef [SharedPtr](../sharedptr/)
* Class [ArraySegment](../arraysegment/)
* Class [DateTime](../datetime/)
* Class [DateTimeOffset](../datetimeoffset/)
* Class [Nullable](../nullable/)
* Class [SmartPtr](../smartptr/)
* Class [Object](../object/)
* Class [String](../string/)
* Class [TimeSpan](../timespan/)
* Class [Uri](../uri/)
* Struct [IsNullable](../isnullable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)