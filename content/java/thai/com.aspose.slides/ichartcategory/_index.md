---
title: IChartCategory
second_title: Aspose.Slides for Java API Reference
description: Represents chart categories.
type: docs
url: /th/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

Represents chart categories.
## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| [getUseCell()](#getUseCell--) | หากเป็น true แล้วคุณสมบัติ AsCell จะเป็นค่าจริง |
| [getAsCell()](#getAsCell--) | ส่งคืนหรือกำหนดวัตถุ IChartDataCell |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | ส่งคืนหรือกำหนดวัตถุ IChartDataCell |
| [getAsLiteral()](#getAsLiteral--) | ส่งคืนหรือกำหนด AsLiteral หาก UseCell เป็น false |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | ส่งคืนหรือกำหนด AsLiteral หาก UseCell เป็น false |
| [getValue()](#getValue--) | หาก UseCell เป็น true แล้วคุณสมบัตินี้แทนคุณสมบัติ AsCell.Value |
| [setValue(Object value)](#setValue-java.lang.Object-) | หาก UseCell เป็น true แล้วคุณสมบัตินี้แทนคุณสมบัติ AsCell.Value |
| [getGroupingLevels()](#getGroupingLevels--) | คอนเทนเนอร์ที่จัดการค่าของระดับการจัดกลุ่มของประเภทแผนภูมิ |
| [remove()](#remove--) | ลบประเภทออกจากแผนภูมิ |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```


หากเป็น true แล้วคุณสมบัติ AsCell จะเป็นค่าจริง กล่าวคือ worksheet จะใช้สำหรับจัดเก็บประเภท (กรณีนี้รองรับประเภทหลายระดับ) หากเป็น false แล้วคุณสมบัติ AsLiteral จะเป็นค่าจริง กล่าวคือ worksheet จะไม่ใช้สำหรับจัดเก็บประเภท (และกรณีนี้ไม่สนับสนุนประเภทหลายระดับ) boolean แบบอ่านอย่างเดียว.

--------------------

เพื่อเปลี่ยนค่าของคุณสมบัตินี้ (สำหรับทุกประเภทในคอลเลกชัน) ให้ตั้งค่ใหม่ให้กับคุณสมบัติ [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--).

**คืนค่า:**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```


ส่งคืนหรือกำหนดวัตถุ IChartDataCell หากประเภทเป็นหลายระดับแล้วจะใช้วัตถุ IChartDataCell สำหรับระดับ “0”. อ่าน/เขียน [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**คืนค่า:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```


ส่งคืนหรือกำหนดวัตถุ IChartDataCell หากประเภทเป็นหลายระดับแล้วจะใช้วัตถุ IChartDataCell สำหรับระดับ “0”. อ่าน/เขียน [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```


ส่งคืนหรือกำหนด AsLiteral หาก UseCell เป็น false. อ่าน/เขียน Object.

**คืนค่า:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```


ส่งคืนหรือกำหนด AsLiteral หาก UseCell เป็น false. อ่าน/เขียน Object.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```


หาก UseCell เป็น true แล้วคุณสมบัตินี้แทนคุณสมบัติ AsCell.Value. หาก UseCell เป็น false แล้วคุณสมบัตินี้แทนคุณสมบัติ AsLiteral. อ่าน/เขียน Object.

**คืนค่า:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


หาก UseCell เป็น true แล้วคุณสมบัตินี้แทนคุณสมบัติ AsCell.Value. หาก UseCell เป็น false แล้วคุณสมบัตินี้แทนคุณสมบัติ AsLiteral. อ่าน/เขียน Object.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```


คอนเทนเนอร์ที่จัดการค่าของระดับการจัดกลุ่มของประเภทแผนภูมิ. ประเภทหลายระดับมีมากกว่าหนึ่งระดับการจัดกลุ่ม. ดัชนีระดับการจัดกลุ่มเริ่มที่ศูนย์. อ่านอย่างเดียว [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**คืนค่า:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```


ลบประเภทออกจากแผนภูมิ.