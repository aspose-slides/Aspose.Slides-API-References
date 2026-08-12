---
title: Unbox()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ทำการ Unbox ชนิดค่าหลังจากแปลงเป็น Object. การทำงานสำหรับชนิด enum.
type: docs
weight: 53
url: /th/system/objectext/unbox/
---
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) เมธอด

ทำการ Unbox ชนิดค่าหลังจากแปลงเป็น [Object](../../object/). การทำงานสำหรับชนิด enum.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | [Enum](../../enum/) ชนิด. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) เพื่อทำการ Unbox. |

### ค่าที่ส่งกลับ

[Enum](../../enum/) ค่า.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) เมธอด

ทำการ Unbox ชนิดค่าหลังจากแปลงเป็น [Object](../../object/). การทำงานสำหรับชนิดที่ไม่ใช่ enum และไม่เป็น nullable.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดค่า. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) เพื่อทำการ Unbox. |

### ค่าที่ส่งกลับ

ค่าที่ทำการ Unbox.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) เมธอด

ทำการ Unbox ชนิดค่าหลังจากแปลงเป็น [Object](../../object/). การทำงานสำหรับชนิดที่ไม่ใช่ enum และไม่เป็น nullable.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดค่า. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) เพื่อทำการ Unbox. |

### ค่าที่ส่งกลับ

ค่าที่ทำการ Unbox.

## ObjectExt::Unbox(E) เมธอด

ทำการ Unbox ชนิด enum เป็นจำนวนเต็ม.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::numeric_limits<T>::is_integer, T>::type System::ObjectExt::Unbox(E e)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดจำนวนเต็มปลายทาง. |
| E | ชนิด enum ต้นทาง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| e | E | ค่าเพื่อทำการ Unbox. |

### ค่าที่ส่งกลับ

การแสดงผลแบบจำนวนเต็มของ enum.

## ObjectExt::Unbox(E) เมธอด

แปลงชนิด enum.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(E e)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิด enum ปลายทาง. |
| E | ชนิด enum ต้นทาง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| e | E | ค่าเพื่อทำการ Unbox. |

### ค่าที่ส่งกลับ

ค่า enum ที่แปลงแล้ว.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) เมธอด

ทำการ Unbox ค่า string.

```cpp
String System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) เพื่อทำการ Unbox |

### ค่าที่ส่งกลับ

[String](../../string/) การแสดงผลของสตริงที่บรรจุในกล่อง, สามารถเป็น null ได้หากสตริงที่บรรจุเป็น null.

## ดูเพิ่มเติม

* คลาส [SmartPtr](../../smartptr/)
* คลาส [Object](../../object/)
* คลาส [ObjectExt](../)
* คลาส [String](../../string/)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)