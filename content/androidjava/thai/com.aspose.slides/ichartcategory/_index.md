---
title: IChartCategory
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงหมวดหมู่แผนภูมิ
type: docs
url: /th/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

แสดงหมวดหมู่แผนภูมิ
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getUseCell()](#getUseCell--) | หากเป็น true แล้ว property AsCell เป็นค่าที่ใช้งานได้ |
| [getAsCell()](#getAsCell--) | คืนค่า หรือ ตั้งค่า วัตถุ IChartDataCell |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | คืนค่า หรือ ตั้งค่า วัตถุ IChartDataCell |
| [getAsLiteral()](#getAsLiteral--) | คืนค่า หรือ ตั้งค่า AsLiteral หาก UseCell เป็น false |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | คืนค่า หรือ ตั้งค่า AsLiteral หาก UseCell เป็น false |
| [getValue()](#getValue--) | หาก UseCell เป็น true แล้ว property นี้แสดง property AsCell.Value |
| [setValue(Object value)](#setValue-java.lang.Object-) | หาก UseCell เป็น true แล้ว property นี้แสดง property AsCell.Value |
| [getGroupingLevels()](#getGroupingLevels--) | คอนเทนเนอร์ที่จัดการค่าของระดับการจัดกลุ่มหมวดหมู่แผนภูมิ |
| [remove()](#remove--) | ลบหมวดหมู่ออกจากแผนภูมิ |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```

หากเป็น true แล้ว property AsCell จะเป็นค่าที่ใช้งานได้. ด้วยความหมายอื่น แผ่นงานถูกใช้เพื่อเก็บหมวดหมู่ (กรณีนี้สนับสนุนหมวดหมู่หลายระดับ). หากเป็น false แล้ว property AsLiteral จะเป็นค่าที่ใช้งานได้. ด้วยความหมายอื่น แผ่นงานไม่ได้ใช้เพื่อเก็บหมวดหมู่ (และกรณีนี้ไม่สนับสนุนหมวดหมู่หลายระดับ). บูลีนแบบอ่านอย่างเดียว.

--------------------

เพื่อเปลี่ยนค่าของ property นี้ (สำหรับทุกหมวดหมู่ในคอลเลกชัน) ตั้งค่ใหม่ให้กับ property [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--).

**คืนค่า:**  
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```

คืนค่า หรือ ตั้งค่า วัตถุ IChartDataCell. หากหมวดหมู่อยู่หลายระดับ จะใช้วัตถุ IChartDataCell สำหรับระดับ "0". อ่าน/เขียน [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**คืนค่า:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```

คืนค่า หรือ ตั้งค่า วัตถุ IChartDataCell. หากหมวดหมู่อยู่หลายระดับ จะใช้วัตถุ IChartDataCell สำหรับระดับ "0". อ่าน/เขียน [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```

คืนค่า หรือ ตั้งค่า AsLiteral หาก UseCell เป็น false. อ่าน/เขียน Object.

**คืนค่า:**  
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```

คืนค่า หรือ ตั้งค่า AsLiteral หาก UseCell เป็น false. อ่าน/เขียน Object.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.Object |  |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

หาก UseCell เป็น true แล้ว property นี้แสดง property AsCell.Value. หาก UseCell เป็น false แล้ว property นี้แสดง property AsLiteral. อ่าน/เขียน Object.

**คืนค่า:**  
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

หาก UseCell เป็น true แล้ว property นี้แสดง property AsCell.Value. หาก UseCell เป็น false แล้ว property นี้แสดง property AsLiteral. อ่าน/เขียน Object.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.Object |  |
### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```

คอนเทนเนอร์ที่จัดการค่าของระดับการจัดกลุ่มหมวดหมู่แผนภูมิ. หมวดหมู่หลายระดับมีมากกว่าหนึ่งระดับการจัดกลุ่ม. ดัชนีระดับการจัดกลุ่มเริ่มจากศูนย์. อ่านอย่างเดียว [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**คืนค่า:**  
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```

ลบหมวดหมู่ออกจากแผนภูมิ.