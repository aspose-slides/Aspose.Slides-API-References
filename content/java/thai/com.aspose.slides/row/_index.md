---
title: Row
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงถึงแถวในตาราง.
type: docs
url: /th/com.aspose.slides/row/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**อินเทอร์เฟซที่ Implement ทั้งหมด:**
[com.aspose.slides.IRow](../../com.aspose.slides/irow)
```
public final class Row extends CellCollection implements IRow
```

แสดงถึงแถวในตาราง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getHeight()](#getHeight--) | คืนค่าความสูงของแถว. |
| [getMinimalHeight()](#getMinimalHeight--) | คืนค่าหรือกำหนดความสูงขั้นต่ำสุดที่เป็นไปได้ของแถว. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | คืนค่าหรือกำหนดความสูงขั้นต่ำสุดที่เป็นไปได้ของแถว. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | ตั้งค่าคุณสมบัติรูปแบบส่วนที่กำหนดให้กับส่วนของเซลล์ทั้งหมดในแถว. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | ตั้งค่าคุณสมบัติรูปแบบย่อหน้าที่กำหนดให้กับย่อหน้าของเซลล์ทั้งหมดในแถว. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | ตั้งค่าคุณสมบัติรูปแบบเฟรมข้อความที่กำหนดให้กับเฟรมข้อความของเซลล์ทั้งหมดในแถว. |
| [getRowFormat()](#getRowFormat--) | คืนค่าอ็อบเจกต์ RowFormat ที่บรรจุคุณสมบัติการจัดรูปแบบสำหรับแถวนี้. |
### getHeight() {#getHeight--}
```
public final double getHeight()
```


คืนค่าความสูงของแถว. อ่านอย่างเดียว double.

**คืนค่า:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```


คืนค่าหรือกำหนดความสูงขั้นต่ำสุดที่เป็นไปได้ของแถว. อ่าน/เขียน double.

**คืนค่า:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public final void setMinimalHeight(double value)
```


คืนค่าหรือกำหนดความสูงขั้นต่ำสุดที่เป็นไปได้ของแถว. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```


ตั้งค่าคุณสมบัติรูปแบบส่วนที่กำหนดให้กับส่วนของเซลล์ทั้งหมดในแถว.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | IPortionFormat object ที่ตั้งค่าคุณสมบัติที่จำเป็น |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```


ตั้งค่าคุณสมบัติรูปแบบย่อหน้าที่กำหนดให้กับย่อหน้าของเซลล์ทั้งหมดในแถว.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | IParagraphFormat object ที่ตั้งค่าคุณสมบัติที่จำเป็น |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFrameFormat(ITextFrameFormat source)
```


ตั้งค่าคุณสมบัติรูปแบบเฟรมข้อความที่กำหนดให้กับเฟรมข้อความของเซลล์ทั้งหมดในแถว.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | ITextFrameFormat object ที่ตั้งค่าคุณสมบัติที่จำเป็น |

### getRowFormat() {#getRowFormat--}
```
public final IRowFormat getRowFormat()
```


คืนค่าอ็อบเจกต์ RowFormat ที่บรรจุคุณสมบัติการจัดรูปแบบสำหรับแถวนี้. อ่านอย่างเดียว [IRowFormat](../../com.aspose.slides/irowformat).

**คืนค่า:**
[IRowFormat](../../com.aspose.slides/irowformat)