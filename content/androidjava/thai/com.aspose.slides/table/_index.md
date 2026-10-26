---
title: Table
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นตัวแทนของตารางบนสไลด์
type: docs
url: /th/com.aspose.slides/table/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**  
[com.aspose.slides.ITable](../../com.aspose.slides/itable)  
```
public final class Table extends GraphicalObject implements ITable
```

แทนตารางบนสไลด์หนึ่ง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | ส่งคืนเซลล์ที่ตำแหน่งคอลัมน์และแถวที่ระบุ. |
| [getRows()](#getRows--) | ส่งคืนคอลเลกชันของแถว. |
| [getColumns()](#getColumns--) | ส่งคืนคอลเลกชันของคอลัมน์. |
| [getTableFormat()](#getTableFormat--) | ส่งคืนอ็อบเจกต์ TableFormat ที่มีคุณสมบัติการจัดรูปแบบสำหรับตารางนี้. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | รวมเซลล์ที่อยู่ใกล้เคียง. |
| [getStylePreset()](#getStylePreset--) | รับหรือกำหนดสไตล์ตารางที่มีมาในตัว. |
| [setStylePreset(int value)](#setStylePreset-int-) | รับหรือกำหนดสไตล์ตารางที่มีมาในตัว. |
| [getRightToLeft()](#getRightToLeft--) | กำหนดว่าตารางมีลำดับการอ่านจากขวาไปซ้ายหรือไม่. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | กำหนดว่าตารางมีลำดับการอ่านจากขวาไปซ้ายหรือไม่. |
| [getFirstRow()](#getFirstRow--) | กำหนดว่าแถวแรกของตารางต้องแสดงด้วยรูปแบบพิเศษหรือไม่. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | กำหนดว่าแถวแรกของตารางต้องแสดงด้วยรูปแบบพิเศษหรือไม่. |
| [getFirstCol()](#getFirstCol--) | กำหนดว่าคอลัมน์แรกของตารางต้องแสดงด้วยรูปแบบพิเศษหรือไม่. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | กำหนดว่าคอลัมน์แรกของตารางต้องแสดงด้วยรูปแบบพิเศษหรือไม่. |
| [getLastRow()](#getLastRow--) | กำหนดว่าแถวสุดท้ายของตารางต้องแสดงด้วยรูปแบบพิเศษหรือไม่. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | กำหนดว่าแถวสุดท้ายของตารางต้องแสดงด้วยรูปแบบพิเศษหรือไม่. |
| [getLastCol()](#getLastCol--) | กำหนดว่าคอลัมน์สุดท้ายของตารางต้องแสดงด้วยรูปแบบพิเศษหรือไม่. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | กำหนดว่าคอลัมน์สุดท้ายของตารางต้องแสดงด้วยรูปแบบพิเศษหรือไม่. |
| [getHorizontalBanding()](#getHorizontalBanding--) | กำหนดว่าแถวคู่ต้องแสดงด้วยรูปแบบที่แตกต่างหรือไม่. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | กำหนดว่าแถวคู่ต้องแสดงด้วยรูปแบบที่แตกต่างหรือไม่. |
| [getVerticalBanding()](#getVerticalBanding--) | กำหนดว่าคอลัมน์คู่ต้องแสดงด้วยรูปแบบที่แตกต่างหรือไม่. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | กำหนดว่าคอลัมน์คู่ต้องแสดงด้วยรูปแบบที่แตกต่างหรือไม่. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | กำหนดคุณสมบัติรูปแบบส่วนที่กำหนดไว้ให้กับส่วนทั้งหมดของเซลล์ตาราง. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | กำหนดคุณสมบัติรูปแบบย่อหน้าที่กำหนดไว้ให้กับย่อหน้าทั้งหมดของเซลล์ตาราง. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | กำหนดคุณสมบัติรูปแบบกรอบข้อความที่กำหนดไว้ให้กับกรอบข้อความทั้งหมดของเซลล์ตาราง. |
| [getFillFormat()](#getFillFormat--) | ส่งคืนอ็อบเจกต์ TableFormat.FillFormat ที่มีรูปแบบการเติมสำหรับตาราง. |
### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public final ICell get_Item(int columnIndex, int rowIndex)
```

ส่งคืนเซลล์ที่ตำแหน่งคอลัมน์และแถวที่ระบุ. อ่านอย่างเดียว [Cell](../../com.aspose.slides/cell).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**คืนค่า:**
[ICell](../../com.aspose.slides/icell)
### getRows() {#getRows--}
```
public final IRowCollection getRows()
```

ส่งคืนคอลเลกชันของแถว. อ่านอย่างเดียว [IRowCollection](../../com.aspose.slides/irowcollection).

**คืนค่า:**
[IRowCollection](../../com.aspose.slides/irowcollection)
### getColumns() {#getColumns--}
```
public final IColumnCollection getColumns()
```

ส่งคืนคอลเลกชันของคอลัมน์. อ่านอย่างเดียว [IColumnCollection](../../com.aspose.slides/icolumncollection).

**คืนค่า:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)
### getTableFormat() {#getTableFormat--}
```
public final ITableFormat getTableFormat()
```

ส่งคืนอ็อบเจกต์ TableFormat ที่มีคุณสมบัติการจัดรูปแบบสำหรับตารางนี้. อ่านอย่างเดียว [ITableFormat](../../com.aspose.slides/itableformat).

**คืนค่า:**
[ITableFormat](../../com.aspose.slides/itableformat)
### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public final ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

รวมเซลล์ที่อยู่ใกล้เคียง.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | เซลล์ที่จะรวม. |
| cell2 | [ICell](../../com.aspose.slides/icell) | เซลล์ที่จะรวม. |
| allowSplitting | boolean | True เพื่ออนุญาตให้เซลล์แยกออก. |

**คืนค่า:**
[ICell](../../com.aspose.slides/icell) - เซลล์ที่รวมแล้ว.
### getStylePreset() {#getStylePreset--}
```
public final int getStylePreset()
```

รับหรือกำหนดสไตล์ตารางที่มีมาในตัว. อ่าน/เขียน [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**คืนค่า:**
int
### setStylePreset(int value) {#setStylePreset-int-}
```
public final void setStylePreset(int value)
```

รับหรือกำหนดสไตล์ตารางที่มีมาในตัว. อ่าน/เขียน [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getRightToLeft() {#getRightToLeft--}
```
public final boolean getRightToLeft()
```

กำหนดว่าตารางมีลำดับการอ่านจากขวาไปซ้ายหรือไม่. อ่าน-เขียน  boolean .

**คืนค่า:**
boolean
### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public final void setRightToLeft(boolean value)
```

กำหนดว่าตารางมีลำดับการอ่านจากขวาไปซ้ายหรือไม่. อ่าน-เขียน  boolean .

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getFirstRow() {#getFirstRow--}
```
public final boolean getFirstRow()
```

กำหนดว่าแถวแรกของตารางต้องแสดงด้วยรูปแบบพิเศษหรือไม่. อ่าน/เขียน  boolean .

**คืนค่า:**
boolean
### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public final void setFirstRow(boolean value)
```

กำหนดว่าแถวแรกของตารางต้องแสดงด้วยรูปแบบพิเศษหรือไม่. อ่าน/เขียน  boolean .

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getFirstCol() {#getFirstCol--}
```
public final boolean getFirstCol()
```

กำหนดว่าคอลัมน์แรกของตารางต้องแสดงด้วยรูปแบบพิเศษหรือไม่. อ่าน/เขียน  boolean .

**คืนค่า:**
boolean
### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public final void setFirstCol(boolean value)
```

กำหนดว่าคอลัมน์แรกของตารางต้องแสดงด้วยรูปแบบพิเศษหรือไม่. อ่าน/เขียน  boolean .

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getLastRow() {#getLastRow--}
```
public final boolean getLastRow()
```

กำหนดว่าแถวสุดท้ายของตารางต้องแสดงด้วยรูปแบบพิเศษหรือไม่. อ่าน/เขียน  boolean .

**คืนค่า:**
boolean
### setLastRow(boolean value) {#setLastRow-boolean-}
```
public final void setLastRow(boolean value)
```

กำหนดว่าแถวสุดท้ายของตารางต้องแสดงด้วยรูปแบบพิเศษหรือไม่. อ่าน/เขียน  boolean .

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getLastCol() {#getLastCol--}
```
public final boolean getLastCol()
```

กำหนดว่าคอลัมน์สุดท้ายของตารางต้องแสดงด้วยรูปแบบพิเศษหรือไม่. อ่าน/เขียน  boolean .

**คืนค่า:**
boolean
### setLastCol(boolean value) {#setLastCol-boolean-}
```
public final void setLastCol(boolean value)
```

กำหนดว่าคอลัมน์สุดท้ายของตารางต้องแสดงด้วยรูปแบบพิเศษหรือไม่. อ่าน/เขียน  boolean .

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getHorizontalBanding() {#getHorizontalBanding--}
```
public final boolean getHorizontalBanding()
```

กำหนดว่าแถวคู่ต้องแสดงด้วยรูปแบบที่แตกต่างหรือไม่. อ่าน/เขียน  boolean .

**คืนค่า:**
boolean
### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public final void setHorizontalBanding(boolean value)
```

กำหนดว่าแถวคู่ต้องแสดงด้วยรูปแบบที่แตกต่างหรือไม่. อ่าน/เขียน  boolean .

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBanding() {#getVerticalBanding--}
```
public final boolean getVerticalBanding()
```

กำหนดว่าคอลัมน์คู่ต้องแสดงด้วยรูปแบบที่แตกต่างหรือไม่. อ่าน/เขียน  boolean .

**คืนค่า:**
boolean
### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public final void setVerticalBanding(boolean value)
```

กำหนดว่าคอลัมน์คู่ต้องแสดงด้วยรูปแบบที่แตกต่างหรือไม่. อ่าน/เขียน  boolean .

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

กำหนดคุณสมบัติรูปแบบส่วนที่กำหนดไว้ให้กับส่วนทั้งหมดของเซลล์ตาราง.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | IPortionFormat object with necessary properties set. |
### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

กำหนดคุณสมบัติรูปแบบย่อหน้าที่กำหนดไว้ให้กับย่อหน้าทั้งหมดของเซลล์ตาราง.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | IParagraphFormat object with necessary properties set. |
### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

กำหนดคุณสมบัติรูปแบบกรอบข้อความที่กำหนดไว้ให้กับกรอบข้อความทั้งหมดของเซลล์ตาราง.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | ITextFrameFormat object with necessary properties set. |
### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

ส่งคืนอ็อบเจกต์ TableFormat.FillFormat ที่มีรูปแบบการเติมสำหรับตาราง. อ่านอย่างเดียว [IFillFormat](../../com.aspose.slides/ifillformat).

**คืนค่า:**
[IFillFormat](../../com.aspose.slides/ifillformat)