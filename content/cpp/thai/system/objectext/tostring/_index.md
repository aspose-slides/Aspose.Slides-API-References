---
title: ToString()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: การแทนที่เมธอด ToString ของ C# เพื่อให้ทำงานกับประเภท C++ ใดก็ได้
type: docs
weight: 27
url: /th/system/objectext/tostring/
---
## ObjectExt::ToString(const char_t *) เมธอด

การแทนที่เมธอด ToString ของ C# เพื่อให้ทำงานกับประเภท C++ ใดก็ได้

```cpp
static String System::ObjectExt::ToString(const char_t *obj)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | const char_t * | [String](../../string/) ลิเทอรัลที่จะแปลงเป็นสตริง. |

### ค่าที่ส่งกลับ

[String](../../string/) การแสดงผลของ **obj**.

## ObjectExt::ToString(const Nullable\<T\>\&) เมธอด

การแทนที่เมธอด ToString ของ C# เพื่อให้ทำงานกับประเภท C++ ใดก็ได้

```cpp
template<typename T> static String System::ObjectExt::ToString(const Nullable<T> &obj)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | [Nullable](../../nullable/) ประเภท. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | const [Nullable](../../nullable/)\<T\>\& | [Nullable](../../nullable/) อ็อบเจกต์ที่จะแปลงเป็นสตริง. |

### ค่าที่ส่งกลับ

[String](../../string/) การแสดงผลของ **obj**.

## ObjectExt::ToString(const T\&) เมธอด

การแทนที่เมธอด ToString ของ C# เพื่อให้ทำงานกับประเภท C++ ใดก็ได้

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | [Enum](../../enum/) ประเภท. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | const T\& | [Enum](../../enum/) ค่าเพื่อแปลงเป็นสตริง. |

### ค่าที่ส่งกลับ

[String](../../string/) การแสดงผลของ **obj**.

## ObjectExt::ToString(const T\&) เมธอด

การแทนที่เมธอด ToString ของ C# เพื่อให้ทำงานกับประเภท C++ ใดก็ได้

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภท Smart pointer. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | const T\& | [SmartPtr](../../smartptr/) ค่าเพื่อแปลงเป็นสตริง. |

### ค่าที่ส่งกลับ

[String](../../string/) การแสดงผลของ **obj**.

## ObjectExt::ToString(T\&) เมธอด

การแทนที่เมธอด ToString ของ C# เพื่อให้ทำงานกับประเภท C++ ใดก็ได้

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value||std::is_pointer<T>::value||IsExceptionWrapper<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภท Smart pointer หรือ [ExceptionWrapper](../../exceptionwrapper/). |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | T\& | Smart pointer หรือ [ExceptionWrapper](../../exceptionwrapper/) เพื่อแปลงเป็นสตริง. |

### ค่าที่ส่งกลับ

[String](../../string/) การแสดงผลของ **obj**.

## ObjectExt::ToString(T\&) เมธอด

การแทนที่เมธอด ToString ของ C# เพื่อให้ทำงานกับประเภท C++ ใดก็ได้

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทสเกลาร์. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | T\& | ค่าชนิดสเกลาร์เพื่อแปลงเป็นสตริง. |

### ค่าที่ส่งกลับ

[String](../../string/) การแสดงผลของ **obj**.

## ObjectExt::ToString(T\&&) เมธอด

การแทนที่เมธอด ToString ของ C# เพื่อให้ทำงานกับประเภท C++ ใดก็ได้

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทสเกลาร์. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | T\&& | ค่าชนิดสเกลาร์เพื่อแปลงเป็นสตริง. |

### ค่าที่ส่งกลับ

[String](../../string/) การแสดงผลของ **obj**.

## ObjectExt::ToString(T\&) เมธอด

การแทนที่เมธอด ToString ของ C# เพื่อให้ทำงานกับประเภท C++ ใดก็ได้

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทโครงสร้าง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | T\& | ค่าประเภทโครงสร้างเพื่อแปลงเป็นสตริง. |

### ค่าที่ส่งกลับ

[String](../../string/) การแสดงผลของ **obj**.

## ObjectExt::ToString(const T\&) เมธอด

การแทนที่เมธอด ToString ของ C# เพื่อให้ทำงานกับประเภท C++ ใดก็ได้

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทโครงสร้าง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | const T\& | ค่าประเภทโครงสร้างเพื่อแปลงเป็นสตริง. |

### ค่าที่ส่งกลับ

[String](../../string/) การแสดงผลของ **obj**.

## ObjectExt::ToString(T\&&) เมธอด

การแทนที่เมธอด ToString ของ C# เพื่อให้ทำงานกับประเภท C++ ใดก็ได้

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value &&!std::is_reference<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทสเกลาร์. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | T\&& | ค่าชนิดสเกลาร์เพื่อแปลงเป็นสตริง. |

### ค่าที่ส่งกลับ

[String](../../string/) การแสดงผลของ **obj**.

## ดูเพิ่มเติม

* คลาส [String](../../string/)
* คลาส [ObjectExt](../)
* คลาส [Nullable](../../nullable/)
* โครงสร้าง [IsSmartPtr](../../issmartptr/)
* โครงสร้าง [IsExceptionWrapper](../../isexceptionwrapper/)
* โครงสร้าง [IsNullable](../../isnullable/)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)