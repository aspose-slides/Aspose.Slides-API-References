---
title: IColumn
second_title: Aspose.Slides สำหรับอ้างอิง API ของ Java
description: แสดงถึงคอลัมน์ในตาราง.
type: docs
url: /th/com.aspose.slides/icolumn/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IColumn extends ICellCollection, IBulkTextFormattable
```

แสดงถึงคอลัมน์ในตาราง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getWidth()](#getWidth--) | ส่งคืนหรือกำหนดความกว้างของคอลัมน์. |
| [setWidth(double value)](#setWidth-double-) | ส่งคืนหรือกำหนดความกว้างของคอลัมน์. |
| [getColumnFormat()](#getColumnFormat--) | ส่งคืนออบเจ็กต์ ColumnFormat ที่มีคุณสมบัติการจัดรูปแบบสำหรับคอลัมน์นี้. |
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

ส่งคืนหรือกำหนดความกว้างของคอลัมน์ อ่าน/เขียน double.

**ส่งคืน:**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

ส่งคืนหรือกำหนดความกว้างของคอลัมน์ อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getColumnFormat() {#getColumnFormat--}
```
public abstract IColumnFormat getColumnFormat()
```

ส่งคืนออบเจ็กต์ ColumnFormat ที่มีคุณสมบัติการจัดรูปแบบสำหรับคอลัมน์นี้ อ่านอย่างเดียว [IColumnFormat](../../com.aspose.slides/icolumnformat).

**ส่งคืน:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)