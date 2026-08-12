---
title: Equals()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: เปรียบเทียบวัตถุโดยใช้วัตถุนัยของ C# Object.Equals
type: docs
weight: 157
url: /th/system/object/equals/
---
## Object::Equals(ptr) เมธอด


เปรียบเทียบวัตถุโดยใช้วัตถุนัยของ C# [Object.Equals](./) semantics.

```cpp
virtual bool System::Object::Equals(ptr obj)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | [ptr](../ptr/) | [Object](../) เพื่อเปรียบเทียบกับอ็อบเจ็กต์ปัจจุบัน |

### ค่าที่ส่งกลับ

คืนค่า True ถ้าวัตถุถือว่าเท่ากันและ false หากไม่เท่าเทียม

## Object::Equals(T1 const\&, T2 const\&) เมธอด


เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ของ C#.

```cpp
template<typename T1,typename T2> static std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```


### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภทของวัตถุแรกที่ต้องการเปรียบเทียบ. |
| T2 | ประเภทของวัตถุที่สองที่ต้องการเปิบเทียบ. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| objA | T1 const\& | วัตถุแรกที่ต้องการเปรียบเทียบ. |
| objB | T2 const\& | วัตถุที่สองที่ต้องการเปรียบเทียบ. |

### ค่าที่ส่งกลับ

คืนค่า True หากวัตถุตรงกันโดยอ้างอิงหรือเชิงความหมาย (โดยการเปรียบเทียบแบบ [Object.Equals](./)-คล้าย), false ในกรณีอื่น

## Object::Equals(T1 const\&, T2 const\&) เมธอด


เปรียบเทียบวัตถุประเภทค่าในสไตล์ของ C#.

```cpp
template<typename T1,typename T2> static std::enable_if<!IsSmartPtr<T1>::value &&!IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```


### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภทของวัตถุแรกที่ต้องการเปรียบเทียบ. |
| T2 | ประเภทของวัตถุที่สองที่ต้องการเปรียบเทียบ. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิก | คำอธิบาย |
| --- | --- | --- |
| objA | T1 const\& | วัตถุแรกที่ต้องการเปรียบเทียบ. |
| objB | T2 const\& | วัตถุที่สองที่ต้องการเปรียบเทียบ. |

### ค่าที่ส่งกลับ

คืนค่า True หากวัตถุถือว่าเท่ากันด้วยตัวดำเนินการเปรียบเทียบที่มีอยู่, false ในกรณีอื่น

## Object::Equals(float const\&, float const\&) เมธอด


จำลองการเปรียบเทียบจำนวนทศนิยมแบบ C# โดยที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย

```cpp
bool System::Object::Equals(float const &objA, float const &objB)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิก | คำอธิบาย |
| --- | --- | --- |
| objA | **float** const\& | ค่าทศนิยมฝั่งซ้าย. |
| objB | **float** const\& | ค่าทศนิยมฝั่งขวา. |

### ค่าที่ส่งกลับ

คืนค่า True หาก **objA** และ **objB** เป็น NaN ทั้งสองหรือเท่ากัน, false ในกรณีอื่น

## Object::Equals(double const\&, double const\&) เมธอด


จำลองการเปรียบเทียบจำนวนทศนิยมแบบ C# โดยที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย

```cpp
bool System::Object::Equals(double const &objA, double const &objB)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิก | คำอธิบาย |
| --- | --- | --- |
| objA | **double** const\& | ค่าทศนิยมฝั่งซ้าย. |
| objB | **double** const\& | ค่าทศนิยมฝั่งขวา. |

### ค่าที่ส่งกลับ

คืนค่า True หาก **objA** และ **objB** เป็น NaN ทั้งสองหรือเท่ากัน, false ในกรณีอื่น

## ดูเพิ่มเติม

* การพิมพ์นิยาม [ptr](../ptr/)
* คลาส [Object](../)
* โครงสร้าง [IsSmartPtr](../../issmartptr/)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)