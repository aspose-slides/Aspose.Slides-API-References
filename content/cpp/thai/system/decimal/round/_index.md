---
title: Round()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: ปัดค่าที่ระบุให้เป็นจำนวนเต็มที่ใกล้ที่สุด พารามิเตอร์ระบุพฤติกรรมของฟังก์ชันหากค่าที่ระบุอยู่ห่างเท่า ๆ กันจากสองจำนวนที่ใกล้ที่สุด
type: docs
weight: 404
url: /th/system/decimal/round/
---
## Decimal::Round(const Decimal\&, MidpointRounding) เมธอด


ปัดค่าที่ระบุให้เป็นจำนวนเต็มที่ใกล้ที่สุด พารามิเตอร์ระบุพฤติกรรมของฟังก์ชันหากค่าที่ระบุอยู่ห่างเท่า ๆ กันจากสองจำนวนที่ใกล้ที่สุด

```cpp
static Decimal System::Decimal::Round(const Decimal &d, MidpointRounding mode=MidpointRounding::ToEven)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| d | const [Decimal](../)\& | ค่าที่จะปัด |
| mode | [MidpointRounding](../../midpointrounding/) | ระบุวิธีการทำการปัดหาก **value** อยู่ห่างเท่า ๆ กันจากสองจำนวนที่ใกล้ที่สุด |

### ค่าที่ส่งคืน

**d** ปัดเป็นจำนวนเต็มที่ใกล้ที่สุด

## Decimal::Round(const Decimal\&, int, MidpointRounding) เมธอด


ปัดค่าที่ระบุให้เป็นค่าที่ใกล้ที่สุดโดยมีจำนวนตำแหน่งทศนิยมตามที่กำหนด พารามิเตอร์ระบุพฤติกรรมของฟังก์ชันหากค่าที่ระบุอยู่ห่างเท่า ๆ กันจากสองจำนวนที่ใกล้ที่สุด

```cpp
static Decimal System::Decimal::Round(const Decimal &d, int digits, MidpointRounding mode=MidpointRounding::ToEven)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| d | const [Decimal](../)\& | ค่าที่จะปัด |
| digits | int | จำนวนตำแหน่งทศนิยมในค่าที่ปัด |
| mode | [MidpointRounding](../../midpointrounding/) | ระบุวิธีการทำการปัดหาก **value** อยู่ห่างเท่า ๆ กันจากสองจำนวนที่ใกล้ที่สุด |

### ค่าที่ส่งคืน

จำนวนที่มีจำนวนหลักทศนิยมตามที่กำหนดที่ใกล้ที่สุดกับ **value**

## ดูเพิ่มเติม

* Enum [MidpointRounding](../../midpointrounding/)
* คลาส [Decimal](../)
* เนมสเปซ [System](../../)
* Library [Aspose.Slides](../../../)