---
title: IRow
second_title: Aspose.Slides สำหรับ Java เอกสารอ้างอิง API
description: แสดงถึงแถวในตาราง.
type: docs
url: /th/com.aspose.slides/irow/
---
**ส่วนต่อประสานที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IRow extends ICellCollection, IBulkTextFormattable
```

แทนแถวในตาราง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getHeight()](#getHeight--) | คืนความสูงของแถวหนึ่ง. |
| [getMinimalHeight()](#getMinimalHeight--) | คืนหรือกำหนดความสูงขั้นต่ำที่เป็นไปได้ของแถวหนึ่ง. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | คืนหรือกำหนดความสูงขั้นต่ำที่เป็นไปได้ของแถวหนึ่ง. |
| [getRowFormat()](#getRowFormat--) | คืนอ็อบเจ็กต์ RowFormat ที่มีคุณสมบัติการจัดรูปแบบสำหรับแถวนี้. |
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


คืนความสูงของแถวหนึ่ง. อ่านอย่างเดียว double.

**คืนค่า:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```


คืนหรือกำหนดความสูงขั้นต่ำที่เป็นไปได้ของแถวหนึ่ง. อ่าน/เขียนได้ double.

**คืนค่า:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public abstract void setMinimalHeight(double value)
```


คืนหรือกำหนดความสูงขั้นต่ำที่เป็นไปได้ของแถวหนึ่ง. อ่าน/เขียนได้ double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getRowFormat() {#getRowFormat--}
```
public abstract IRowFormat getRowFormat()
```


คืนอ็อบเจ็กต์ RowFormat ที่มีคุณสมบัติการจัดรูปแบบสำหรับแถวนี้. อ่านอย่างเดียว [IRowFormat](../../com.aspose.slides/irowformat).

**คืนค่า:**
[IRowFormat](../../com.aspose.slides/irowformat)