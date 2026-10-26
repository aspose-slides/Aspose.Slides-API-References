---
title: operator-()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: คำนวณจำนวนวันระหว่างสองวันของสัปดาห์.
type: docs
weight: 2172
url: /th/system/operator_minus/
---
## System::operator-(DayOfWeek, DayOfWeek) ฟังก์ชัน


Calculates the number of days between two days of week.

```cpp
auto System::operator-(DayOfWeek a, DayOfWeek b)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| a | [DayOfWeek](../dayofweek/) | ตัวจาก |
| b | [DayOfWeek](../dayofweek/) | ตัวหัก |

### ค่าที่คืน

จำนวนวันระหว่างวันทำงาน **a** และ **b**; ค่าที่คืนเป็นค่าลบหาก *ไป* หลัง ****

## System::operator-(const T\&, const Decimal\&) ฟังก์ชัน


Returns a new instance of [Decimal](../decimal/) class that represents a value that is the result of subtraction of the value represented by the specified [Decimal](../decimal/) object from the specified value.

```cpp
template<typename T,typename _> Decimal System::operator-(const T &x, const Decimal &d)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| x | const T\& | ค่าที่ต้องลบออกจาก |
| d | const [Decimal](../decimal/)\& | วัตถุ [Decimal](../decimal/) ที่แสดงค่าที่ถูกลบ |

### ค่าที่คืน

อินสแตนซ์ใหม่ของคลาส [Decimal](../decimal/) ที่แสดงค่าเป็นผลของการลบค่าที่แสดงโดย **d** จาก **x**.

## System::operator-(MulticastDelegate\<T\>, MulticastDelegate\<T\>) ฟังก์ชัน


Disconnects all callbacks in right hand delegate from the end of left hand delegate callback list.

```cpp
template<typename T> MulticastDelegate<T> System::operator-(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | delegate ที่จะลบคอลแบ๊กออก |
| rhv | MulticastDelegate\<T\> | delegate ที่คอลแบ๊กจะถูกลบ |

### ค่าที่คืน

ส่งคืน delegate ที่มีคอลแบ๊กของค่าข้างซ้าย แต่ไม่มีคอลแบ๊กของค่าข้างขวา.

## System::operator-(const T1\&, const Nullable\<T2\>\&) ฟังก์ชัน


Subtracts non-nullable and nullable values.

```cpp
template<typename T1,typename T2,typename> auto System::operator-(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some - other.get_Value())>
```


### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภทของตัวดำเนินการซ้าย |
| T2 | ประเภทของตัวดำเนินการขวา |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| some | const T1\& | ตัวดำเนินการซ้าย |
| other | const [Nullable](../nullable/)\<T2\>\& | ตัวดำเนินการขวา |

### ค่าที่คืน

ผลลัพธ์การลบ

## ดูเพิ่มเติม

* Enum [DayOfWeek](../dayofweek/)
* คลาส [Decimal](../decimal/)
* คลาส [Nullable](../nullable/)
* เนมสเปซ [System](../)
* Library [Aspose.Slides](../../)