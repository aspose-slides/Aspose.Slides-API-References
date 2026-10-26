---
title: operator>()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: 
type: docs
weight: 2120
url: /th/system/operator_greater/
---
## System::operator>(std::nullptr_t, DateTime) ฟังก์ชัน




```cpp
constexpr bool System::operator>(std::nullptr_t, DateTime)
```

## System::operator>(std::nullptr_t, const DateTimeOffset\&) ฟังก์ชัน




```cpp
constexpr bool System::operator>(std::nullptr_t, const DateTimeOffset &)
```

## System::operator>(std::nullptr_t, const Nullable\<T\>\&) ฟังก์ชัน


จะคืนค่า false เสมอ

```cpp
template<typename T> bool System::operator>(std::nullptr_t, const Nullable<T> &)
```

## System::operator>(const T1\&, const Nullable\<T2\>\&) ฟังก์ชัน


กำหนดว่าค่าเฉพาะที่ระบุมีค่ามากกว่าค่าที่แทนด้วยวัตถุ [Nullable](../nullable/) ที่ระบุโดยการใช้ [operator>()](./) กับค่าทั้งสองนี้

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator>(const T1 &some, const Nullable<T2> &other)
```


### พารามิเตอร์ของเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ชนิดของค่าตัวเปรียบเทียบแรก |
| T2 | ชนิดพื้นฐานของวัตถุ [Nullable](../nullable/) ที่แทนค่าตัวเปรียบเทียบที่สอง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| some | const T1\& | การอ้างอิงคงที่ไปยังค่าที่ใช้เป็นตัวเปรียบเทียบแรก |
| other | const [Nullable](../nullable/)\<T2\>\& | การอ้างอิงคงที่ไปยังวัตถุ [Nullable](../nullable/) ที่แทนค่าซึ่งใช้เป็นตัวเปรียบเทียบที่สอง |

### ค่าที่ส่งคืน

True หากตัวเปรียบเทียบแรกมีค่ามากกว่าตัวเปรียบเทียบที่สอง, มิฉะนั้น - false

## System::operator>(std::nullptr_t, TimeSpan) ฟังก์ชัน




```cpp
constexpr bool System::operator>(std::nullptr_t, TimeSpan)
```

## ดูเพิ่มเติม

* Class [DateTime](../datetime/)
* Class [DateTimeOffset](../datetimeoffset/)
* Class [Nullable](../nullable/)
* Class [TimeSpan](../timespan/)
* Struct [IsNullable](../isnullable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)