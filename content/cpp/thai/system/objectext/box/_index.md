---
title: Box()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: บ็อกซ์ค่าแบบ value types เพื่อแปลงเป็น Object. การดำเนินการสำหรับประเภท enum.
type: docs
weight: 40
url: /th/system/objectext/box/
---
## ObjectExt::Box(const T\&) เมธอด


บ็อกซ์ค่าแบบ value types เพื่อแปลงเป็น [Object](../../object/). การดำเนินการสำหรับประเภท enum.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T | [Enum](../../enum/) ชนิด. |

### พารามิเตอร์

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | [Enum](../../enum/) ค่าที่จะบ็อกซ์. |

### ค่าที่ส่งกลับ

Smart pointer ไปยังอ็อบเจกต์ที่เก็บค่าที่บ็อกซ์ไว้.

## ObjectExt::Box(const T\&) เมธอด


บ็อกซ์ค่าแบบ value types เพื่อแปลงเป็น [Object](../../object/). การดำเนินการสำหรับประเภทที่ไม่ใช่ enum.

```cpp
template<typename T> static std::enable_if<!std::is_enum<T>::value &&!IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T | ชนิดของค่า. |

### พารามิเตอร์

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | ค่าที่จะบ็อกซ์. |

### ค่าที่ส่งกลับ

Smart pointer ไปยังอ็อบเจกต์ที่เก็บค่าที่บ็อกซ์ไว้.

## ObjectExt::Box(const T\&) เมธอด


บ็อกซ์ประเภท [Nullable](../../nullable/) เพื่อแปลงเป็น [Object](../../object/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T | ชนิดของค่า. |

### พารามิเตอร์

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | ค่าที่จะบ็อกซ์. |

### ค่าที่ส่งกลับ

Smart pointer ไปยังอ็อบเจกต์ที่เก็บค่าที่บ็อกซ์ไว้.

## ObjectExt::Box(const String\&) เมธอด


บ็อกซ์ค่าชนิดสตริง.

```cpp
SmartPtr<Object> System::ObjectExt::Box(const String &value)
```


### พารามิเตอร์

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | ค่าที่จะบ็อกซ์. |

### ค่าที่ส่งกลับ

ค่าที่บ็อกซ์หรือ null หากสตริงต้นทางเป็น null.

## ดูเพิ่มเติม

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Class [String](../../string/)
* Struct [IsNullable](../../isnullable/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)