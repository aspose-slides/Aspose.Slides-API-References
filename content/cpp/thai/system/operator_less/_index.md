---
title: operator<()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: 
type: docs
weight: 2094
url: /th/system/operator_less/
---
## System::operator<(std::nullptr_t, DateTime) ฟังก์ชัน




```cpp
constexpr bool System::operator<(std::nullptr_t, DateTime)
```

## System::operator<(std::nullptr_t, const DateTimeOffset\&) ฟังก์ชัน




```cpp
constexpr bool System::operator<(std::nullptr_t, const DateTimeOffset &)
```

## System::operator<(std::nullptr_t, const Nullable\<T\>\&) ฟังก์ชัน

จะคืนค่า false เสมอ.

```cpp
template<typename T> bool System::operator<(std::nullptr_t, const Nullable<T> &)
```

## System::operator<(const T1\&, const Nullable\<T2\>\&) ฟังก์ชัน

กำหนดว่าค่าที่กำหนดไว้เป็นค่าน้อยกว่าค่าที่แสดงโดยอ็อบเจ็กต์ [Nullable](../nullable/) ที่ระบุโดยการใช้ [operator<()](./) กับค่าทั้งสองนี้.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator<(const T1 &some, const Nullable<T2> &other)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T1 | ประเภทของค่าที่เปรียบเทียบตัวแรก |
| T2 | ประเภทพื้นฐานของอ็อบเจ็กต์ [Nullable](../nullable/) ที่เป็นตัวแทนของค่าที่เปรียบเทียบตัวที่สอง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| some | const T1\& | การอ้างอิงแบบคงที่ของค่าที่จะใช้เป็นค่าที่เปรียบเทียบตัวแรก |
| other | const [Nullable](../nullable/)\<T2\>\& | การอ้างอิงแบบคงที่ของอ็อบเจ็กต์ [Nullable](../nullable/) ที่ค่าที่แสดงจะถูกใช้เป็นค่าที่เปรียบเทียบตัวที่สอง |

### ค่าที่ส่งคืน

True หากค่าที่เปรียบเทียบตัวแรกน้อยกว่าค่าที่เปรียบเทียบตัวที่สอง, มิฉะนั้น - false

## System::operator<(std::nullptr_t, TimeSpan) ฟังก์ชัน




```cpp
constexpr bool System::operator<(std::nullptr_t, TimeSpan)
```

## ดูเพิ่มเติม

* คลาส [DateTime](../datetime/)
* คลาส [DateTimeOffset](../datetimeoffset/)
* คลาส [Nullable](../nullable/)
* คลาส [TimeSpan](../timespan/)
* โครงสร้าง [IsNullable](../isnullable/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)