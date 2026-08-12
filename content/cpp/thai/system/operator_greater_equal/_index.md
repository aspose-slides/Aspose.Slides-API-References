---
title: operator>=()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: 
type: docs
weight: 2133
url: /th/system/operator_greater_equal/
---
## System::operator>=(std::nullptr_t, DateTime) ฟังก์ชัน




```cpp
constexpr bool System::operator>=(std::nullptr_t, DateTime)
```

## System::operator>=(std::nullptr_t, const DateTimeOffset\&) ฟังก์ชัน




```cpp
constexpr bool System::operator>=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator>=(std::nullptr_t, const Nullable\<T\>\&) ฟังก์ชัน


จะคืนค่า false เสมอ

```cpp
template<typename T> bool System::operator>=(std::nullptr_t, const Nullable<T> &)
```

## System::operator>=(const T1\&, const Nullable\<T2\>\&) ฟังก์ชัน


กำหนดว่าค่าที่ระบุมีค่ามากกว่าหรือเท่ากับค่าที่แสดงโดยวัตถุ [Nullable](../nullable/) ที่ระบุโดยการประยุกต์ [operator>=()](./) กับค่าทั้งสองนี้

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator>=(const T1 &some, const Nullable<T2> &other)
```


### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ชนิดของค่าตัวเปรียบเทียบแรก |
| T2 | ชนิดพื้นฐานของวัตถุ [Nullable](../nullable/) ที่แสดงค่าตัวเปรียบเทียบที่สอง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| some | const T1\& | การอ้างอิงคงที่ไปยังค่าที่จะใช้เป็นตัวเปรียบเทียบแรก |
| other | const [Nullable](../nullable/)\<T2\>\& | การอ้างอิงคงที่ไปยังวัตถุ [Nullable](../nullable/) ที่แสดงค่าที่จะใช้เป็นตัวเปรียบเทียบที่สอง |

### ค่าที่คืน

True หากค่าตัวเปรียบเทียบแรกมากกว่าหรือเท่ากับค่าตัวเปรียบเทียบที่สอง, มิฉะนั้น - false

## System::operator>=(std::nullptr_t, TimeSpan) ฟังก์ชัน




```cpp
constexpr bool System::operator>=(std::nullptr_t, TimeSpan)
```

## ดูเพิ่มเติม

* คลาส [DateTime](../datetime/)
* คลาส [DateTimeOffset](../datetimeoffset/)
* คลาส [Nullable](../nullable/)
* คลาส [TimeSpan](../timespan/)
* โครงสร้าง [IsNullable](../isnullable/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)