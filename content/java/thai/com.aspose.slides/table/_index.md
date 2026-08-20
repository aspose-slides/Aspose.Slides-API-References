---
title: Table
second_title: Aspose.Slides สำหรับ Java API อ้างอิง
description: แทนตารางบนสไลด์.
type: docs
url: /th/com.aspose.slides/table/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.ITable](../../com.aspose.slides/itable)
```
public final class Table extends GraphicalObject implements ITable
```

แทนตารางบนสไลด์.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | คืนค่าเซลล์ที่ตำแหน่งคอลัมน์และแถวที่ระบุ |
| [getRows()](#getRows--) | คืนค่าชุดของแถว |
| [getColumns()](#getColumns--) | คืนค่าชุดของคอลัมน์ |
| [getTableFormat()](#getTableFormat--) | คืนค่าอ็อบเจ็กต์ TableFormat ที่บรรจุคุณสมบัติการจัดรูปแบบสำหรับตารางนี้ |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | รวมเซลล์ที่อยู่ใกล้กัน |
| [getStylePreset()](#getStylePreset--) | รับหรือกำหนดสไตล์ตารางในตัว |
| [setStylePreset(int value)](#setStylePreset-int-) | รับหรือกำหนดสไตล์ตารางในตัว |
| [getRightToLeft()](#getRightToLeft--) | กำหนดว่าตารางมีลำดับการอ่านจากขวาไปซ้ายหรือไม่ |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | กำหนดว่าตารางมีลำดับการอ่านจากขวาไปซ้ายหรือไม่ |
| [getFirstRow()](#getFirstRow--) | กำหนดว่าแถวแรกของตารางต้องวาดด้วยการจัดรูปแบบพิเศษหรือไม่ |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | กำหนดว่าแถวแรกของตารางต้องวาดด้วยการจัดรูปแบบพิเศษหรือไม่ |
| [getFirstCol()](#getFirstCol--) | กำหนดว่าคอลัมน์แรกของตารางต้องวาดด้วยการจัดรูปแบบพิเศษหรือไม่ |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | กำหนดว่าคอลัมน์แรกของตารางต้องวาดด้วยการจัดรูปแบบพิเศษหรือไม่ |
| [getLastRow()](#getLastRow--) | กำหนดว่าแถวสุดท้ายของตารางต้องวาดด้วยการจัดรูปแบบพิเศษหรือไม่ |
| [setLastRow(boolean value)](#setLastRow-boolean-) | กำหนดว่าแถวสุดท้ายของตารางต้องวาดด้วยการจัดรูปแบบพิเศษหรือไม่ |
| [getLastCol()](#getLastCol--) | กำหนดว่าคอลัมน์สุดท้ายของตารางต้องวาดด้วยการจัดรูปแบบพิเศษหรือไม่ |
| [setLastCol(boolean value)](#setLastCol-boolean-) | กำหนดว่าคอลัมน์สุดท้ายของตารางต้องวาดด้วยการจัดรูปแบบพิเศษหรือไม่ |
| [getHorizontalBanding()](#getHorizontalBanding--) | กำหนดว่าแถวคู่ต้องวาดด้วยการจัดรูปแบบที่แตกต่างหรือไม่ |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | กำหนดว่าแถวคู่ต้องวาดด้วยการจัดรูปแบบที่แตกต่างหรือไม่ |
| [getVerticalBanding()](#getVerticalBanding--) | กำหนดว่าคอลัมน์คู่ต้องวาดด้วยการจัดรูปแบบที่แตกต่างหรือไม่ |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | กำหนดว่าคอลัมน์คู่ต้องวาดด้วยการจัดรูปแบบที่แตกต่างหรือไม่ |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | กำหนดคุณสมบัติการจัดรูปแบบส่วนที่กำหนดให้กับส่วนย่อยทั้งหมดของเซลล์ตาราง |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | กำหนดคุณสมบัติการจัดรูปแบบย่อหน้าที่กำหนดให้กับย่อหน้าทั้งหมดของเซลล์ตาราง |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | กำหนดคุณสมบัติการจัดรูปแบบกรอบข้อความที่กำหนดให้กับกรอบข้อความทั้งหมดของเซลล์ตาราง |
| [getFillFormat()](#getFillFormat--) | คืนค่าอ็อบเจ็กต์ TableFormat.FillFormat ที่บรรจุการจัดรูปแบบการเติมสีสำหรับตาราง |

### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public final ICell get_Item(int columnIndex, int rowIndex)
```

คืนค่าเซลล์ที่ตำแหน่งคอลัมน์และแถวที่ระบุ. อ่านอย่างเดียว [Cell](../../com.aspose.slides/cell).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**ผลลัพธ์:**
[ICell](../../com.aspose.slides/icell)

### getRows() {#getRows--}
```
public final IRowCollection getRows()
```

คืนค่าชุดของแถว. อ่านอย่างเดียว [IRowCollection](../../com.aspose.slides/irowcollection).

**ผลลัพธ์:**
[IRowCollection](../../com.aspose.slides/irowcollection)

### getColumns() {#getColumns--}
```
public final IColumnCollection getColumns()
```

คืนค่าชุดของคอลัมน์. อ่านอย่างเดียว [IColumnCollection](../../com.aspose.slides/icolumncollection).

**ผลลัพธ์:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)

### getTableFormat() {#getTableFormat--}
```
public final ITableFormat getTableFormat()
```

คืนค่าอ็อบเจ็กต์ TableFormat ที่บรรจุคุณสมบัติการจัดรูปแบบสำหรับตารางนี้. อ่านอย่างเดียว [ITableFormat](../../com.aspose.slides/itableformat).

**ผลลัพธ์:**
[ITableFormat](../../com.aspose.slides/itableformat)

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public final ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

รวมเซลล์ที่อยู่ใกล้กัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | เซลล์ที่จะรวม |
| cell2 | [ICell](../../com.aspose.slides/icell) | เซลล์ที่จะรวม |
| allowSplitting | boolean | True เพื่ออนุญาตให้เซลล์แยกได้ |

**ผลลัพธ์:**
[ICell](../../com.aspose.slides/icell) - เซลล์ที่รวมแล้ว

### getStylePreset() {#getStylePreset--}
```
public final int getStylePreset()
```

รับหรือกำหนดสไตล์ตารางในตัว. อ่าน/เขียน [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**ผลลัพธ์:**
int

### setStylePreset(int value) {#setStylePreset-int-}
```
public final void setStylePreset(int value)
```

รับหรือกำหนดสไตล์ตารางในตัว. อ่าน/เขียน [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public final boolean getRightToLeft()
```

กำหนดว่าตารางมีลำดับการอ่านจากขวาไปซ้ายหรือไม่. อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean

### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public final void setRightToLeft(boolean value)
```

กำหนดว่าตารางมีลำดับการอ่านจากขวาไปซ้ายหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final boolean getFirstRow()
```

กำหนดว่าแถวแรกของตารางต้องวาดด้วยการจัดรูปแบบพิเศษหรือไม่. อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean

### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public final void setFirstRow(boolean value)
```

กำหนดว่าแถวแรกของตารางต้องวาดด้วยการจัดรูปแบบพิเศษหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public final boolean getFirstCol()
```

กำหนดว่าคอลัมน์แรกของตารางต้องวาดด้วยการจัดรูปแบบพิเศษหรือไม่. อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean

### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public final void setFirstCol(boolean value)
```

กำหนดว่าคอลัมน์แรกของตารางต้องวาดด้วยการจัดรูปแบบพิเศษหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public final boolean getLastRow()
```

กำหนดว่าแถวสุดท้ายของตารางต้องวาดด้วยการจัดรูปแบบพิเศษหรือไม่. อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean

### setLastRow(boolean value) {#setLastRow-boolean-}
```
public final void setLastRow(boolean value)
```

กำหนดว่าแถวสุดท้ายของตารางต้องวาดด้วยการจัดรูปแบบพิเศษหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public final boolean getLastCol()
```

กำหนดว่าคอลัมน์สุดท้ายของตารางต้องวาดด้วยการจัดรูปแบบพิเศษหรือไม่. อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean

### setLastCol(boolean value) {#setLastCol-boolean-}
```
public final void setLastCol(boolean value)
```

กำหนดว่าคอลัมน์สุดท้ายของตารางต้องวาดด้วยการจัดรูปแบบพิเศษหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public final boolean getHorizontalBanding()
```

กำหนดว่าแถวคู่ต้องวาดด้วยการจัดรูปแบบที่แตกต่างหรือไม่. อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean

### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public final void setHorizontalBanding(boolean value)
```

กำหนดว่าแถวคู่ต้องวาดด้วยการจัดรูปแบบที่แตกต่างหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public final boolean getVerticalBanding()
```

กำหนดว่าคอลัมน์คู่ต้องวาดด้วยการจัดรูปแบบที่แตกต่างหรือไม่. อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean

### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public final void setVerticalBanding(boolean value)
```

กำหนดว่าคอลัมน์คู่ต้องวาดด้วยการจัดรูปแบบที่แตกต่างหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

กำหนดคุณสมบัติการจัดรูปแบบส่วนที่กำหนดให้กับส่วนย่อยทั้งหมดของเซลล์ตาราง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | อ็อบเจ็กต์ IPortionFormat ที่ตั้งค่าคุณสมบัติที่จำเป็นแล้ว |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

กำหนดคุณสมบัติการจัดรูปแบบย่อหน้าที่กำหนดให้กับย่อหน้าทั้งหมดของเซลล์ตาราง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | อ็อบเจ็กต์ IParagraphFormat ที่ตั้งค่าคุณสมบัติที่จำเป็นแล้ว |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

กำหนดคุณสมบัติการจัดรูปแบบกรอบข้อความที่กำหนดให้กับกรอบข้อความทั้งหมดของเซลล์ตาราง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | อ็อบเจ็กต์ ITextFrameFormat ที่ตั้งค่าคุณสมบัติที่จำเป็นแล้ว |

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

คืนค่าอ็อบเจ็กต์ TableFormat.FillFormat ที่บรรจุการจัดรูปแบบการเติมสีสำหรับตาราง. อ่านอย่างเดียว [IFillFormat](../../com.aspose.slides/ifillformat).

**ผลลัพธ์:**
[IFillFormat](../../com.aspose.slides/ifillformat)