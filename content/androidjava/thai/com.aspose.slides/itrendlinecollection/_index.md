---
title: ITrendlineCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงคอลเลกชันของ TrendlineEx
type: docs
url: /th/com.aspose.slides/itrendlinecollection/
---
**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ITrendlineCollection extends System.Collections.Generic.IGenericEnumerable<ITrendline>
```

แสดงถึงคอลเลกชันของ TrendlineEx
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ดึงรายการที่ตำแหน่งที่ระบุ. |
| [getCount()](#getCount--) | ดึงจำนวนของรายการที่มีอยู่จริงในคอลเลกชัน. |
| [add(int trendlineType)](#add-int-) | เพิ่ม Trendline ใหม่ที่ส่วนท้ายของคอลเลกชันและคืนค่า. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | ลบค่าที่ระบุ. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITrendline get_Item(int index)
```

ดึงรายการที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [ITrendline](../../com.aspose.slides/itrendline).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[ITrendline](../../com.aspose.slides/itrendline)
### getCount() {#getCount--}
```
public abstract int getCount()
```

ดึงจำนวนของรายการที่มีอยู่จริงในคอลเลกชัน. อ่านอย่างเดียว int.

**คืนค่า:**
int
### add(int trendlineType) {#add-int-}
```
public abstract ITrendline add(int trendlineType)
```

เพิ่ม Trendline ใหม่ที่ส่วนท้ายของคอลเลกชันและคืนค่า.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| trendlineType | int | ชนิด Trendline [TrendlineType](../../com.aspose.slides/trendlinetype) |

**คืนค่า:**
[ITrendline](../../com.aspose.slides/itrendline) - Trendline ใหม่ [ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public abstract void remove(ITrendline value)
```

ลบค่าที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) | Trendline ที่ต้องลบ [ITrendline](../../com.aspose.slides/itrendline) |