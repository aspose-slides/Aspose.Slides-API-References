---
title: IRow
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงถึงแถวในตาราง.
type: docs
url: /th/com.aspose.slides/irow/
---
**All Implemented Interfaces:**  
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IRow extends ICellCollection, IBulkTextFormattable
```

แสดงถึงแถวในตาราง.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getHeight()](#getHeight--) | คืนค่าสูงของแถว. |
| [getMinimalHeight()](#getMinimalHeight--) | คืนค่าหรือกำหนดความสูงขั้นต่ำที่เป็นไปได้ของแถว. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | คืนค่าหรือกำหนดความสูงขั้นต่ำที่เป็นไปได้ของแถว. |
| [getRowFormat()](#getRowFormat--) | คืนออบเจกต์ RowFormat ที่มีคุณสมบัติการจัดรูปแบบสำหรับแถวนี้. |
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```

คืนค่าสูงของแถว. อ่านอย่างเดียว double.

**คืนค่า:**  
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```

คืนค่าหรือกำหนดความสูงขั้นต่ำที่เป็นไปได้ของแถว. อ่าน/เขียน double.

**คืนค่า:**  
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public abstract void setMinimalHeight(double value)
```

คืนค่าหรือกำหนดความสูงขั้นต่ำที่เป็นไปได้ของแถว. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getRowFormat() {#getRowFormat--}
```
public abstract IRowFormat getRowFormat()
```

คืนออบเจกต์ RowFormat ที่มีคุณสมบัติการจัดรูปแบบสำหรับแถวนี้. อ่านอย่างเดียว [IRowFormat](../../com.aspose.slides/irowformat).

**คืนค่า:**  
[IRowFormat](../../com.aspose.slides/irowformat)