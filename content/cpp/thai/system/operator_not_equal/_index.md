---
title: operator!=()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: 
type: docs
weight: 2055
url: /th/system/operator_not_equal/
---
## System::operator!=(ArraySegment\<T\>, ArraySegment\<T\>) ฟังก์ชัน




```cpp
template<typename T> bool System::operator!=(ArraySegment<T> a, ArraySegment<T> b)
```

## System::operator!=(std::nullptr_t, DateTime) ฟังก์ชัน




```cpp
constexpr bool System::operator!=(std::nullptr_t, DateTime)
```

## System::operator!=(std::nullptr_t, const DateTimeOffset\&) ฟังก์ชัน




```cpp
constexpr bool System::operator!=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator!=(std::nullptr_t, const Nullable\<T\>\&) ฟังก์ชัน

กำหนดว่าค่าอ็อบเจกต์ [Nullable](../nullable/) ที่ระบุเป็นค่าที่ไม่เท่ากับ null หรือไม่

```cpp
template<typename T> bool System::operator!=(std::nullptr_t, const Nullable<T> &other)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| other | std::nullptr_t | อ้างอิงคงที่ไปยังอ็อบเจกต์ [Nullable](../nullable/) เพื่อทดสอบ |

### ค่าที่ส่งกลับ

true หากอ็อบเจกต์ที่ระบุเป็นค่าที่ไม่เป็น null, false ในกรณีอื่น


## System::operator!=(const T1\&, const Nullable\<T2\>\&) ฟังก์ชัน

กำหนดว่าค่าที่ระบุไม่เท่ากับค่าที่แสดงโดยอ็อบเจกต์ [Nullable](../nullable/) ที่ระบุโดยการใช้ [operator!=()](./) กับค่าทั้งสองนี้

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator!=(const T1 &some, const Nullable<T2> &other)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภทของค่าเปรียบเทียบตัวแรก |
| T2 | ประเภทพื้นฐานของอ็อบเจกต์ [Nullable](../nullable/) ที่แสดงค่าเปรียบเทียบตัวที่สอง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| some | const T1\& | อ้างอิงคงที่ของค่าที่จะใช้เป็นค่าเปรียบเทียบตัวแรก |
| other | const [Nullable](../nullable/)\<T2\>\& | อ้างอิงคงที่ไปยังอ็อบเจกต์ [Nullable](../nullable/) ที่ค่าที่แสดงจะถูกใช้เป็นค่าเปรียบเทียบตัวที่สอง |

### ค่าที่ส่งกลับ

true หากค่าเปรียบเทียบไม่เท่ากัน, หากไม่เช่นนั้น - false


## System::operator!=(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) ฟังก์ชัน

เปรียบเทียบความไม่เท่ากันของสอง smart pointer

```cpp
template<class X,class Y> bool System::operator!=(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| X | ประเภทของวัตถุที่ pointer แรกชี้ถึง |
| Y | ประเภทของวัตถุที่ pointer ที่สองชี้ถึง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | pointer แรกสำหรับเปรียบเทียบ |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | pointer ที่สองสำหรับเปรียบเทียบ |

### ค่าที่ส่งกลับ

false หาก pointer ตรงกัน, true หากไม่ตรง


## System::operator!=(SmartPtr\<X\> const\&, std::nullptr_t) ฟังก์ชัน

ตรวจสอบว่า smart pointer ไม่เป็น null

```cpp
template<class X> bool System::operator!=(SmartPtr<X> const &x, std::nullptr_t)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| X | ประเภทของวัตถุที่ pointer ชี้ถึง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | [SmartPtr](../smartptr/)\<X\> const\& | pointer ที่จะตรวจสอบ |

### ค่าที่ส่งกลับ

false หาก pointer เป็น null, true หากไม่เป็น


## System::operator!=(std::nullptr_t, SmartPtr\<X\> const\&) ฟังก์ชัน

ตรวจสอบว่า smart pointer ไม่เป็น null

```cpp
template<class X> bool System::operator!=(std::nullptr_t, SmartPtr<X> const &x)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| X | ประเภทของวัตถุที่ pointer ชี้ถึง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | std::nullptr_t | pointer ที่จะตรวจสอบ |

### ค่าที่ส่งกลับ

false หาก pointer เป็น null, true หากไม่เป็น


## System::operator!=(const SmartPtr\<X\>\&, const Y *) ฟังก์ชัน

การเปรียบเทียบความไม่เท่ากันของ smart pointer กับ pointer ธรรมดา (C)

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const SmartPtr<X> &x, const Y *y)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| X | ประเภทของ smart pointer |
| Y | ประเภทของ pointer ธรรมดา |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | smart pointer สำหรับเปรียบเทียบ (ด้านซ้าย) |
| y | const Y * | pointer สำหรับเปรียบเทียบ (ด้านขวา) |

### ค่าที่ส่งกลับ

false หาก pointer ตรงกัน, true หากไม่ตรง


## System::operator!=(const X *, const SmartPtr\<Y\>\&) ฟังก์ชัน

การเปรียบเทียบความเท่าเทียมของ smart pointer กับ pointer ธรรมดา (C)

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const X *x, const SmartPtr<Y> &y)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| X | ประเภทของ pointer ธรรมดา |
| Y | ประเภทของ smart pointer |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | const X * | pointer สำหรับเปรียบเทียบ (ด้านขวา) |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | smart pointer สำหรับเปรียบเทียบ (ด้านซ้าย) |

### ค่าที่ส่งกลับ

false หาก pointer ตรงกัน, true หากไม่ตรง


## System::operator!=(Chars\&, const String\&) ฟังก์ชัน

[String](../string/) การเปรียบเทียบ

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator!=(Chars &left, const String &right)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Chars | [String](../string/) ประเภทลิเทรัล |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| left | Chars\& | [String](../string/) ลิเทรัลสำหรับเปรียบเทียบ |
| right | const [String](../string/)\& | [String](../string/) สำหรับเปรียบเทียบ |

### ค่าที่ส่งกลับ

false หากสตริงตรงกัน, true หากไม่ตรง


## System::operator!=(T\&, const String\&) ฟังก์ชัน

[String](../string/) การเปรียบเทียบ

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator!=(T &left, const String &right)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | [String](../string/) ประเภทของ pointer |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| left | T\& | [String](../string/) pointer สำหรับเปรียบเทียบ |
| right | const [String](../string/)\& | [String](../string/) สำหรับเปรียบเทียบ |

### ค่าที่ส่งกลับ

false หากสตริงตรงกัน, true หากไม่ตรง


## System::operator!=(const SharedPtr\<Object\>\&, const String\&) ฟังก์ชัน

[Object](../object/) และการเปรียบเทียบสตริง

```cpp
bool System::operator!=(const SharedPtr<Object> &left, const String &right)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | [Object](../object/) เพื่อแปลงเป็นสตริงและเปรียบเทียบ |
| right | const [String](../string/)\& | [String](../string/) เพื่อเปรียบเทียบ |

### ค่าที่ส่งกลับ

false หากการแสดงผลเป็นสตริงของอ็อบเจกต์เท่ากับสตริง, true หากไม่เท่า


## System::operator!=(std::nullptr_t, const String\&) ฟังก์ชัน

ตรวจสอบว่า string เป็น null หรือไม่

```cpp
bool System::operator!=(std::nullptr_t, const String &str)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| str | std::nullptr_t | [String](../string/) เพื่อการตรวจสอบ |

### ค่าที่ส่งกลับ

false หาก string เป็น null, true หากไม่เป็น


## System::operator!=(std::nullptr_t, TimeSpan) ฟังก์ชัน




```cpp
constexpr bool System::operator!=(std::nullptr_t, TimeSpan)
```


## System::operator!=(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) ฟังก์ชัน

กำหนดว่า URIs ที่แสดงโดยอ็อบเจกต์ปัจจุบันและอ็อบเจกต์ที่ระบุไม่เท่ากันหรือไม่

```cpp
bool System::operator!=(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | อ็อบเจกต์ [Uri](../uri/) ตัวแรกสำหรับเปรียบเทียบ |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | อ็อบเจกต์ [Uri](../uri/) ตัวที่สองสำหรับเปรียบเทียบ |

### ค่าที่ส่งกลับ

true หาก URIs ไม่เท่ากัน, หากไม่เช่นนั้น - false


## ดูเพิ่มเติม

* Typedef [SharedPtr](../sharedptr/)
* คลาส [ArraySegment](../arraysegment/)
* คลาส [DateTime](../datetime/)
* คลาส [DateTimeOffset](../datetimeoffset/)
* คลาส [Nullable](../nullable/)
* คลาส [SmartPtr](../smartptr/)
* คลาส [Object](../object/)
* คลาส [String](../string/)
* คลาส [TimeSpan](../timespan/)
* คลาส [Uri](../uri/)
* Struct [IsNullable](../isnullable/)
* เนมสเปซ [System](../)
* Library [Aspose.Slides](../../)