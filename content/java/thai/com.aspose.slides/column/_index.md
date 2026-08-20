---
title: Column
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: แทนคอลัมน์ในตาราง.
type: docs
url: /th/com.aspose.slides/column/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**All Implemented Interfaces:**  
[com.aspose.slides.IColumn](../../com.aspose.slides/icolumn)  
```
public final class Column extends CellCollection implements IColumn
```

แทนคอลัมน์ในตาราง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getWidth()](#getWidth--) | คืนค่า หรือกำหนดความกว้างของคอลัมน์. |
| [setWidth(double value)](#setWidth-double-) | คืนค่า หรือกำหนดความกว้างของคอลัมน์. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | ตั้งค่าคุณสมบัติการจัดรูปแบบส่วนที่กำหนดไว้ให้กับส่วนของเซลล์คอลัมน์ทั้งหมด. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | ตั้งค่าคุณสมบัติการจัดรูปแบบย่อหน้าที่กำหนดไว้ให้กับย่อหน้าของเซลล์คอลัมน์ทั้งหมด. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | ตั้งค่าคุณสมบัติการจัดรูปแบบกรอบข้อความที่กำหนดไว้ให้กับกรอบข้อความของเซลล์คอลัมน์ทั้งหมด. |
| [getColumnFormat()](#getColumnFormat--) | คืนค่าออบเจ็กต์ ColumnFormat ที่มีคุณสมบัติการจัดรูปแบบสำหรับคอลัมน์นี้. |
### getWidth() {#getWidth--}
```
public final double getWidth()
```


คืนค่า หรือกำหนดความกว้างของคอลัมน์. อ่าน/เขียน double.

**คืนค่า:**  
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


คืนค่า หรือกำหนดความกว้างของคอลัมน์. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```


ตั้งค่าคุณสมบัติการจัดรูปแบบส่วนที่กำหนดไว้ให้กับส่วนของเซลล์คอลัมน์ทั้งหมด.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | อ็อบเจ็กต์ IPortionFormat ที่มีคุณสมบัติเจ้าจำเป็นตั้งค่าไว้ |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```


ตั้งค่าคุณสมบัติการจัดรูปแบบย่อหน้าที่กำหนดไว้ให้กับย่อหน้าของเซลล์คอลัมน์ทั้งหมด.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | อ็อบเจ็กต์ IParagraphFormat ที่มีคุณสมบัติเจ้าจำเป็นตั้งค่าไว้ |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```


ตั้งค่าคุณสมบัติการจัดรูปแบบกรอบข้อความที่กำหนดไว้ให้กับกรอบข้อความของเซลล์คอลัมน์ทั้งหมด.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | อ็อบเจ็กต์ ITextFrameFormat ที่มีคุณสมบัติเจ้าจำเป็นตั้งค่าไว้ |

### getColumnFormat() {#getColumnFormat--}
```
public final IColumnFormat getColumnFormat()
```


คืนค่าออบเจ็กต์ ColumnFormat ที่มีคุณสมาบัติการจัดรูปแบบสำหรับคอลัมน์นี้. อ่านอย่างเดียว [IColumnFormat](../../com.aspose.slides/icolumnformat).

**คืนค่า:**  
[IColumnFormat](../../com.aspose.slides/icolumnformat)