---
title: IColumn
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงถึงคอลัมน์ในตาราง.
type: docs
url: /th/com.aspose.slides/icolumn/
---
**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IColumn extends ICellCollection, IBulkTextFormattable
```

แสดงถึงคอลัมน์ในตาราง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getWidth()](#getWidth--) | คืนค่า หรือกำหนดความกว้างของคอลัมน์ |
| [setWidth(double value)](#setWidth-double-) | คืนค่า หรือกำหนดความกว้างของคอลัมน์ |
| [getColumnFormat()](#getColumnFormat--) | คืนค่าอ็อบเจ็กต์ ColumnFormat ที่มีคุณสมบัติการจัดรูปแบบสำหรับคอลัมน์นี้ |

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

คืนค่า หรือกำหนดความกว้างของคอลัมน์ อ่าน/เขียน double.

**คืนค่า:**
double

### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

คืนค่า หรือกำหนดความกว้างของคอลัมน์ อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getColumnFormat() {#getColumnFormat--}
```
public abstract IColumnFormat getColumnFormat()
```

คืนค่าอ็อบเจ็กต์ ColumnFormat ที่มีคุณสมบัติการจัดรูปแบบสำหรับคอลัมน์นี้ อ่านอย่างเดียว [IColumnFormat](../../com.aspose.slides/icolumnformat).

**คืนค่า:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)