---
title: operator+()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: คืนค่าอินสแตนซ์ใหม่ของคลาส Decimal ซึ่งแสดงค่าที่เป็นผลรวมของค่าที่ระบุและค่าที่แสดงโดยอ็อบเจ็กต์ Decimal ที่ระบุ
type: docs
weight: 2185
url: /th/system/operator_plus/
---
## System::operator+(const T\&, const Decimal\&) ฟังก์ชัน

คืนค่าอินสแตนซ์ใหม่ของคลาส [Decimal](../decimal/) ที่แสดงค่าที่เป็นผลรวมของค่าที่ระบุและค่าที่แสดงโดยอ็อบเจ็กต์ [Decimal](../decimal/) ที่ระบุ.

```cpp
template<typename T,typename _> Decimal System::operator+(const T &x, const Decimal &d)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| x | const T\& | ตัวบวกแรก |
| d | const [Decimal](../decimal/)\& | การอ้างอิงคงที่ไปยังอ็อบเจ็กต์ [Decimal](../decimal/) ที่แสดงผลบวกชิ้นที่สอง |

### ค่าที่คืน

อินสแตนซ์ใหม่ของคลาส [Decimal](../decimal/) ที่แสดงค่าที่เป็นผลรวมของ **x** และค่าที่แสดงโดย **d**.

## System::operator+(MulticastDelegate\<T\>, MulticastDelegate\<T\>) ฟังก์ชัน

เชื่อมต่อคอลแบ็กทั้งหมดจาก delegate ด้านขวาไปยังส่วนท้ายของรายการคอลแบ็กของ delegate ด้านซ้าย.

```cpp
template<typename T> MulticastDelegate<T> System::operator+(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | Delegate ที่คอลแบ็กถูกเพิ่มเข้าไป |
| rhv | MulticastDelegate\<T\> | Delegate ที่คอลแบ็กกำลังถูกเพิ่ม |

### ค่าที่คืน

คืนค่า delegate ที่มีคอลแบ็กของค่าฝั่งซ้ายและตามด้วยคอลแบ็กของฝั่งขวา.

## System::operator+(const T1\&, const Nullable\<T2\>\&) ฟังก์ชัน

บวกค่าที่ไม่เป็น null และค่า nullable.

```cpp
template<typename T1,typename T2,typename> auto System::operator+(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some+other.get_Value())>
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | รายละเอียด |
| --- | --- |
| T1 | ชนิดของตัวกระทำซ้าย |
| T2 | ชนิดของตัวกระทำขวา |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| some | const T1\& | ตัวกระทำซ้าย |
| other | const [Nullable](../nullable/)\<T2\>\& | ตัวกระทำขวา |

### ค่าที่คืน

ผลลัพธ์การบวก

## System::operator+(T\&, const String\&) ฟังก์ชัน

[String](../string/) การต่อ

```cpp
template<typename T> std::enable_if<IsStringLiteral<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | รายละเอียด |
| --- | --- |
| T | [String](../string/) ประเภทลิเทอรัล |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| left | T\& | ลิเทอรัลเพื่อเชื่อมต่อกับสตริง |
| right | const [String](../string/)\& | [String](../string/) เพื่อเชื่อมต่อ |

### ค่าที่คืน

สตริงที่ต่อแล้ว

## System::operator+(T\&, const String\&) ฟังก์ชัน

[String](../string/) การต่อ

```cpp
template<typename T> std::enable_if<IsStringPointer<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | รายละเอียด |
| --- | --- |
| T | [String](../string/) ประเภทพอยน์เตอร์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| left | T\& | [String](../string/) พอยน์เตอร์เพื่อเชื่อมต่อกับสตริง |
| right | const [String](../string/)\& | [String](../string/) เพื่อเชื่อมต่อ |

### ค่าที่คืน

สตริงที่ต่อแล้ว

## System::operator+(const char_t, const String\&) ฟังก์ชัน

[String](../string/) การต่อ

```cpp
String System::operator+(const char_t left, const String &right)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| left | const char_t | อักขระเพื่อเชื่อมต่อกับสตริง |
| right | const [String](../string/)\& | [String](../string/) เพื่อเชื่อมต่อ |

### ค่าที่คืน

สตริงที่ต่อแล้ว

## ดูเพิ่มเติม

* คลาส [Decimal](../decimal/)
* คลาส [Nullable](../nullable/)
* คลาส [String](../string/)
* โครงสร้าง [IsStringLiteral](../isstringliteral/)
* โครงสร้าง [IsStringPointer](../isstringpointer/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)