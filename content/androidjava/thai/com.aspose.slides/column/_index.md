---
title: Column
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API อ้างอิง
description: แสดงถึงคอลัมน์ในตาราง.
type: docs
url: /th/com.aspose.slides/column/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**อินเทอร์เฟซที่ติดตั้งทั้งหมด:**  
[com.aspose.slides.IColumn](../../com.aspose.slides/icolumn)  
```
public final class Column extends CellCollection implements IColumn
```

แสดงถึงคอลัมน์ในตาราง.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getWidth()](#getWidth--) | ส่งคืนหรือกำหนดค่าความกว้างของคอลัมน์. |
| [setWidth(double value)](#setWidth-double-) | ส่งคืนหรือกำหนดค่าความกว้างของคอลัมน์. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | ตั้งค่าลักษณะการจัดรูปแบบส่วนที่กำหนดให้กับส่วนของเซลล์คอลัมน์ทั้งหมด. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | ตั้งค่าลักษณะการจัดรูปแบบย่อหน้าที่กำหนดให้กับย่อหน้าของเซลล์คอลัมน์ทั้งหมด. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | ตั้งค่าลักษณะการจัดรูปแบบกรอบข้อความที่กำหนดให้กับกรอบข้อความของเซลล์คอลัมน์ทั้งหมด. |
| [getColumnFormat()](#getColumnFormat--) | ส่งคืนอ็อบเจกต์ ColumnFormat ที่มีลักษณะการจัดรูปแบบสำหรับคอลัมน์นี้. |

### getWidth() {#getWidth--}
```
public final double getWidth()
```

ส่งคืนหรือกำหนดค่าความกว้างของคอลัมน์. อ่าน/เขียน double.

**คืนค่า:**  
double

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

ส่งคืนหรือกำหนดค่าความกว้างของคอลัมน์. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

ตั้งค่าลักษณะการจัดรูปแบบส่วนที่กำหนดให้กับส่วนของเซลล์คอลัมน์ทั้งหมด.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | อ็อบเจกต์ IPortionFormat ที่ตั้งค่าคุณลักษณะที่จำเป็นไว้แล้ว. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

ตั้งค่าลักษณะการจัดรูปแบบย่อหน้าที่กำหนดให้กับย่อหน้าของเซลล์คอลัมน์ทั้งหมด.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | อ็อบเจกต์ IParagraphFormat ที่ตั้งค่าคุณลักษณะที่จำเป็นไว้แล้ว. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

ตั้งค่าลักษณะการจัดรูปแบบกรอบข้อความที่กำหนดให้กับกรอบข้อความของเซลล์คอลัมน์ทั้งหมด.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | อ็อบเจกต์ ITextFrameFormat ที่ตั้งค่าคุณลักษณะที่จำเป็นไว้แล้ว. |

### getColumnFormat() {#getColumnFormat--}
```
public final IColumnFormat getColumnFormat()
```

ส่งคืนอ็อบเจกต์ ColumnFormat ที่มีลักษณะการจัดรูปแบบสำหรับคอลัมน์นี้ อ่านอย่างเดียว [IColumnFormat](../../com.aspose.slides/icolumnformat).

**คืนค่า:**  
[IColumnFormat](../../com.aspose.slides/icolumnformat)