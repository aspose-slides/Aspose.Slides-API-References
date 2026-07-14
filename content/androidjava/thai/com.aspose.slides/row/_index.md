---
title: Row
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แทนแถวในตาราง.
type: docs
url: /th/com.aspose.slides/row/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.IRow](../../com.aspose.slides/irow)
```
public final class Row extends CellCollection implements IRow
```

แทนแถวในตาราง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getHeight()](#getHeight--) | คืนค่าความสูงของแถว. |
| [getMinimalHeight()](#getMinimalHeight--) | คืนค่าหรือกำหนดความสูงต่ำสุดที่เป็นไปได้ของแถว. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | คืนค่าหรือกำหนดความสูงต่ำสุดที่เป็นไปได้ของแถว. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | กำหนดคุณสมบัติดีไซน์ของ portion ที่กำหนดให้กับ portion ของเซลล์แถวทั้งหมด. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | กำหนดคุณสมบัติดีไซน์ของย่อหน้าที่กำหนดให้กับย่อหน้าของเซลล์แถวทั้งหมด. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | กำหนดคุณสมบัติดีไซน์ของกรอบข้อความที่กำหนดให้กับกรอบข้อความของเซลล์แถวทั้งหมด. |
| [getRowFormat()](#getRowFormat--) | คืนค่า RowFormat object ที่มีคุณสมบัติจัดรูปแบบสำหรับแถวนี้. |
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


คืนค่าหรือกำหนดความสูงต่ำสุดที่เป็นไปได้ของแถว. อ่าน/เขียน double.

**คืนค่า:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public final void setMinimalHeight(double value)
```


คืนค่าหรือกำหนดความสูงต่ำสุดที่เป็นไปได้ของแถว. อ่าน/เขียน double.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```


กำหนดคุณสมบัติดีไซน์ของ portion ที่กำหนดให้กับ portion ของเซลล์แถวทั้งหมด.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | IPortionFormat อ็อบเจ็กต์ที่ตั้งค่าคุณสมบัติที่จำเป็น. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```


กำหนดคุณสมบัติดีไซน์ของย่อหน้าที่กำหนดให้กับย่อหน้าของเซลล์แถวทั้งหมด.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | IParagraphFormat อ็อบเจ็กต์ที่ตั้งค่าคุณสมบัติที่จำเป็น. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```


กำหนดคุณสมบัติดีไซน์ของกรอบข้อความที่กำหนดให้กับกรอบข้อความของเซลล์แถวทั้งหมด.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | ITextFrameFormat อ็อบเจ็กต์ที่ตั้งค่าคุณสมบัติที่จำเป็น. |

### getRowFormat() {#getRowFormat--}
```
public final IRowFormat getRowFormat()
```


คืนค่า RowFormat object ที่มีคุณสมบัติจัดรูปแบบสำหรับแถวนี้. อ่านอย่างเดียว [IRowFormat](../../com.aspose.slides/irowformat).

**คืนค่า:**
[IRowFormat](../../com.aspose.slides/irowformat)