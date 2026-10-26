---
title: ITrendlineCollection
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงถึงคอลเลกชันของ TrendlineEx
type: docs
url: /th/com.aspose.slides/itrendlinecollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ITrendlineCollection extends System.Collections.Generic.IGenericEnumerable<ITrendline>
```

แสดงถึงคอลเลกชันของ TrendlineEx
## Methods

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | รับองค์ประกอบที่ตำแหน่งดัชนีที่ระบุ |
| [getCount()](#getCount--) | รับจำนวนขององค์ประกอบที่มีอยู่ในคอลเลกชันจริง |
| [add(int trendlineType)](#add-int-) | เพิ่ม Trendline ใหม่ที่ส่วนท้ายของคอลเลกชันและส่งกลับมัน |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | ลบค่าที่ระบุ |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITrendline get_Item(int index)
```


รับองค์ประกอบที่ตำแหน่งดัชนีที่ระบุ อ่านได้อย่างเดียว [ITrendline](../../com.aspose.slides/itrendline).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ค่าที่ส่งกลับ:**
[ITrendline](../../com.aspose.slides/itrendline)
### getCount() {#getCount--}
```
public abstract int getCount()
```


รับจำนวนขององค์ประกอบที่มีอยู่ในคอลเลกชันจริง อ่านได้อย่างเดียว int.

**ค่าที่ส่งกลับ:**
int
### add(int trendlineType) {#add-int-}
```
public abstract ITrendline add(int trendlineType)
```


เพิ่ม Trendline ใหม่ที่ส่วนท้ายของคอลเลกชันและส่งกลับมัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| trendlineType | int | ประเภท Trendline [TrendlineType](../../com.aspose.slides/trendlinetype) |

**ค่าที่ส่งกลับ:**
[ITrendline](../../com.aspose.slides/itrendline) - Trendline ใหม่ [ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public abstract void remove(ITrendline value)
```


ลบค่าที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) | Trendline ที่จะลบ [ITrendline](../../com.aspose.slides/itrendline) |