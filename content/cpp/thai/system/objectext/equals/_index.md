---
title: Equals()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: 
type: docs
weight: 14
url: /th/system/objectext/equals/
---
## ObjectExt::Equals(const T\&, const T2\&) เมธอด

```cpp
template<typename T,typename T2> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

## ObjectExt::Equals(const T\&, const T2\&) เมธอด

การแทนที่สำหรับการเรียก C# [Object.Equals](../../object/equals/) ที่ทำงานได้กับประเภทใดก็ได้ใน C++. การโอเวอร์โหลดสำหรับประเภท smart pointer.

```cpp
template<typename T,typename T2> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทวัตถุแรก |
| T2 | ประเภทวัตถุที่สอง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | const T\& | วัตถุแรก |
| another | const T2\& | วัตถุที่สอง |

### ค่าที่ส่งกลับ

เป็นค่าจริงถ้าวัตถุถือว่าเท่ากัน, เป็นค่าผิดในกรณีอื่น.

## ObjectExt::Equals(T, const T2\&) เมธอด

การแทนที่สำหรับการเรียก C# [Object.Equals](../../object/equals/) ที่ทำงานได้กับประเภทใดก็ได้ใน C++. การโอเวอร์โหลดสำหรับประเภทโครงสร้าง.

```cpp
template<typename T,typename T2> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(T obj, const T2 &another)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทวัตถุแรก |
| T2 | ประเภทวัตถุที่สอง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | T | วัตถุแรก |
| another | const T2\& | วัตถุที่สอง |

### ค่าที่ส่งกลับ

เป็นค่าจริงถ้าวัตถุถือว่าเท่ากัน, เป็นค่าผิดในกรณีอื่น.

## ObjectExt::Equals(const T\&, const T2\&) เมธอด

การแทนที่สำหรับการเรียก C# [Object.Equals](../../object/equals/) ที่ทำงานได้กับประเภทใดก็ได้ใน C++. การโอเวอร์โหลดสำหรับประเภทสเกลาร์.

```cpp
template<typename T,typename T2> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทวัตถุแรก |
| T2 | ประเภทวัตถุที่สอง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | const T\& | วัตถุแรก |
| another | const T2\& | วัตถุที่สอง |

### ค่าที่ส่งกลับ

เป็นค่าจริงถ้าวัตถุถือว่าเท่ากัน, เป็นค่าผิดในกรณีอื่น.

## ObjectExt::Equals(const char_t(&), String) เมธอด

การแทนที่สำหรับการเรียก C# [Object.Equals](../../object/equals/) ที่ทำงานได้กับประเภทใดก็ได้ใน C++. การโอเวอร์โหลดสำหรับสตริงลิเทรัลพร้อมการเปรียบเทียบสตริง.

```cpp
template<size_t> static bool System::ObjectExt::Equals(const char_t(&obj)[N], String another)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| N | [String](../../string/) ขนาดลิเทรัล |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | const char_t(&) | [String](../../string/) ลิเทรัล |
| another | [String](../../string/) | [String](../../string/) |

### ค่าที่ส่งกลับ

เป็นค่าจริงถ้าสตริงตรงกัน, เป็นค่าผิดในกรณีอื่น.

## ObjectExt::Equals(const float\&, const float\&) เมธอด

จำลองการเปรียบเทียบจำนวนทศนิยมแบบ C# ซึ่งสองค่า NaN จะถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 ค่า NaN จะไม่เท่ากับค่าหนึ่งใด รวมถึง NaN ด้วย.

```cpp
bool System::ObjectExt::Equals(const float &obj, const float &another)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | const **float**\& | ค่าจำนวนทศนิยมด้านซ้าย |
| another | const **float**\& | ค่าจำนวนทศนิยมด้านขวา |

### ค่าที่ส่งกลับ

เป็นค่าจริงถ้า **obj** และ **another** เป็น NaN ทั้งคู่หรือเท่ากัน, เป็นค่าผิดในกรณีอื่น.

## ObjectExt::Equals(const double\&, const double\&) เมธอด

จำลองการเปรียบเทียบจำนวนทศนิยมแบบ C# ซึ่งสองค่า NaN จะถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 ค่า NaN จะไม่เท่ากับค่าหนึ่งใด รวมถึง NaN ด้วย.

```cpp
bool System::ObjectExt::Equals(const double &obj, const double &another)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | const **double**\& | ค่าจำนวนทศนิยมด้านซ้าย |
| another | const **double**\& | ค่าจำนวนทศนิยมด้านขวา |

### ค่าที่ส่งกลับ

เป็นค่าจริงถ้า **obj** และ **another** เป็น NaN ทั้งคู่หรือเท่ากัน, เป็นค่าผิดในกรณีอื่น.

## ดูเพิ่มเติม

* คลาส [ObjectExt](../)
* คลาส [String](../../string/)
* โครงสร้าง [IsExceptionWrapper](../../isexceptionwrapper/)
* โครงสร้าง [IsSmartPtr](../../issmartptr/)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)