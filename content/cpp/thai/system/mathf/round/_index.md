---
title: Round()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ปัดค่าที่ระบุให้เป็นค่าจำนวนเต็มที่ใกล้ที่สุด
type: docs
weight: 157
url: /th/system/mathf/round/
---
## MathF::Round(float) เมธอด


ปัดค่าที่ระบุให้เป็นค่าจำนวนเต็มที่ใกล้ที่สุด

```cpp
static float System::MathF::Round(float a)
```


### อาร์กิวเมนท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| a | **float** | ค่าที่จะปัด |

### ค่าที่ส่งกลับ

**a** ปัดเป็นค่าจำนวนเต็มที่ใกล้ที่สุด

## MathF::Round(float, int) เมธอด


ปัดค่าที่ระบุให้เป็นค่าที่ใกล้ที่สุดโดยกำหนดจำนวนตำแหน่งทศนิยม

```cpp
static float System::MathF::Round(float value, int digits)
```


### อาร์กิวเมนท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | **float** | ค่าที่จะปัด |
| digits | int | จำนวนตำแหน่งทศนิยมในค่าที่ปัดแล้ว |

### ค่าที่ส่งกลับ

จำนวนที่มีจำนวนหลักที่ระบุโดยใกล้ที่สุดกับ **value**

## MathF::Round(float, MidpointRounding) เมธอด


ปัดค่าที่ระบุให้เป็นค่าจำนวนเต็มที่ใกล้ที่สุด พารามิเตอร์กำหนดพฤติกรรมของฟังก์ชันเมื่อค่าที่ระบุอยู่ห่างเท่ากันจากสองค่าที่ใกล้ที่สุด

```cpp
static float System::MathF::Round(float value, MidpointRounding mode)
```


### อาร์กิวเมนท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | **float** | ค่าที่จะปัด |
| mode | [MidpointRounding](../../midpointrounding/) | ระบุวิธีการปัดเมื่อ **value** อยู่ห่างเท่ากันจากสองค่าที่ใกล้ที่สุด |

### ค่าที่ส่งกลับ

**value** ปัดเป็นค่าจำนวนเต็มที่ใกล้ที่สุด

## MathF::Round(float, int, MidpointRounding) เมธอด


ปัดค่าที่ระบุให้เป็นค่าที่ใกล้ที่สุดโดยกำหนดจำนวนตำแหน่งทศนิยม พารามิเตอร์กำหนดพฤติกรรมของฟังก์ชันเมื่อค่าที่ระบุอยู่ห่างเท่ากันจากสองค่าที่ใกล้ที่สุด

```cpp
static float System::MathF::Round(float value, int digits, MidpointRounding mode)
```


### อาร์กิวเมนท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | **float** | ค่าที่จะปัด |
| digits | int | จำนวนตำแหน่งทศนิยมในค่าที่ปัดแล้ว |
| mode | [MidpointRounding](../../midpointrounding/) | ระบุวิธีการปัดเมื่อ **value** อยู่ห่างเท่ากันจากสองค่าที่ใกล้ที่สุด |

### ค่าที่ส่งกลับ

จำนวนที่มีจำนวนหลักที่ระบุโดยใกล้ที่สุดกับ **value**

## ดูเพิ่มเติม

* Enum [MidpointRounding](../../midpointrounding/)
* Struct [MathF](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)