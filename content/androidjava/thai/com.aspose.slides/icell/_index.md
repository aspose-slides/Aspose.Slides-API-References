---
title: ICell
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API Java
description: เป็นการแทนเซลล์ในตาราง.
type: docs
url: /th/com.aspose.slides/icell/
---
**อินเทอร์เฟซที่นำมาใช้ทั้งหมด:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ICell extends ISlideComponent
```

เป็นการแทนเซลล์ในตาราง.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | ส่งคืนระยะทางจากด้านซ้ายของตารางถึงด้านซ้ายของเซลล์. |
| [getOffsetY()](#getOffsetY--) | ส่งคืนระยะทางจากด้านบนของตารางถึงด้านบนของเซลล์. |
| [getFirstRowIndex()](#getFirstRowIndex--) | ส่งคืนดัชนีของแถวแรกที่เซลล์ครอบคลุม. |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | ส่งคืนดัชนีของคอลัมน์แรกที่เซลล์ครอบคลุม. |
| [getWidth()](#getWidth--) | ส่งคืนความกว้างของเซลล์. |
| [getHeight()](#getHeight--) | ส่งคืนความสูงของเซลล์. |
| [getMinimalHeight()](#getMinimalHeight--) | ส่งคืนความสูงต่ำสุดของเซลล์. |
| [getMarginLeft()](#getMarginLeft--) | ส่งคืนหรือกำหนดระยะขอบซ้ายใน TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | ส่งคืนหรือกำหนดระยะขอบซ้ายใน TextFrame. |
| [getMarginRight()](#getMarginRight--) | ส่งคืนหรือกำหนดระยะขอบขวาใน TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | ส่งคืนหรือกำหนดระยะขอบขวาใน TextFrame. |
| [getMarginTop()](#getMarginTop--) | ส่งคืนหรือกำหนดระยะขอบบนใน TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | ส่งคืนหรือกำหนดระยะขอบบนใน TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | ส่งคืนหรือกำหนดระยะขอบล่างใน TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | ส่งคืนหรือกำหนดระยะขอบล่างใน TextFrame. |
| [getTextVerticalType()](#getTextVerticalType--) | ส่งคืนหรือกำหนดประเภทของข้อความแนวตั้ง. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | ส่งคืนหรือกำหนดประเภทของข้อความแนวตั้ง. |
| [getTextAnchorType()](#getTextAnchorType--) | ส่งคืนหรือกำหนดประเภทของจุดยึดข้อความ. |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | ส่งคืนหรือกำหนดประเภทของจุดยึดข้อความ. |
| [getAnchorCenter()](#getAnchorCenter--) | กำหนดว่ากล่องข้อความอยู่กึ่งกลางภายในเซลล์หรือไม่. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | กำหนดว่ากล่องข้อความอยู่กึ่งกลางภายในเซลล์หรือไม่. |
| [getFirstColumn()](#getFirstColumn--) | ดึงคอลัมน์แรกของเซลล์. |
| [getFirstRow()](#getFirstRow--) | ดึงแถวแรกของเซลล์. |
| [getColSpan()](#getColSpan--) | ส่งคืนจำนวนคอลัมน์ในกริดของตารางแม่ที่เซลล์ปัจจุบันครอบคลุม. |
| [getRowSpan()](#getRowSpan--) | ส่งคืนจำนวนแถวที่เซลล์ที่รวมกันครอบคลุม. |
| [getTextFrame()](#getTextFrame--) | ส่งคืน TextFrame ของเซลล์. |
| [getTable()](#getTable--) | ส่งคืนออบเจ็กต์ Table พ่อแม่ของเซลล์. |
| [isMergedCell()](#isMergedCell--) | ส่งคืนค่า true หากเซลล์ถูกรวบรวมกับเซลล์ใด ๆ ที่ปรับแล้ว, มิฉะนั้นส่งคืน false. |
| [getCellFormat()](#getCellFormat--) | ส่งคืนออบเจ็กต์ CellFormat ที่ประกอบด้วยคุณสมบัติการจัดรูปแบบสำหรับเซลล์นี้. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | แยกเซลล์เป็นสองเซลล์ตามดัชนีของคอลัมน์. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | แยกเซลล์เป็นสองเซลล์ตามดัชนีของแถว. |
| [splitByHeight(double height)](#splitByHeight-double-) | แยกเซลล์ตามความสูง. |
| [splitByWidth(double width)](#splitByWidth-double-) | แยกเซลล์ตามความกว้าง. |
### getOffsetX() {#getOffsetX--}
```
public abstract double getOffsetX()
```

ส่งคืนระยะทางจากด้านซ้ายของตารางถึงด้านซ้ายของเซลล์. อ่านอย่างเดียว double.

**ส่งคืน:**
double
### getOffsetY() {#getOffsetY--}
```
public abstract double getOffsetY()
```

ส่งคืนระยะทางจากด้านบนของตารางถึงด้านบนของเซลล์. อ่านอย่างเดียว double.

**ส่งคืน:**
double
### getFirstRowIndex() {#getFirstRowIndex--}
```
public abstract int getFirstRowIndex()
```

ส่งคืนดัชนีของแถวแรกที่เซลล์ครอบคลุม. อ่านอย่างเดียว int.

**ส่งคืน:**
int
### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public abstract int getFirstColumnIndex()
```

ส่งคืนดัชนีของคอลัมน์แรกที่เซลล์ครอบคลุม. อ่านอย่างเดียว int.

**ส่งคืน:**
int
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

ส่งคืนความกว้างของเซลล์. อ่านอย่างเดียว double.

**ส่งคืน:**
double
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```

ส่งคืนความสูงของเซลล์. อ่านอย่างเดียว double.

**ส่งคืน:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```

ส่งคืนความสูงต่ำสุดของเซลล์. นี้เป็นผลรวมของความสูงต่ำสุดของทุกแถวที่เซลล์ครอบคลุม. อ่านอย่างเดียว double.

**ส่งคืน:**
double
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

ส่งคืนหรือกำหนดระยะขอบซ้ายใน TextFrame. อ่าน/เขียน double.

**ส่งคืน:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

ส่งคืนหรือกำหนดระยะขอบซ้ายใน TextFrame. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

ส่งคืนหรือกำหนดระยะขอบขวาใน TextFrame. อ่าน/เขียน double.

**ส่งคืน:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

ส่งคืนหรือกำหนดระยะขอบขวาใน TextFrame. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

ส่งคืนหรือกำหนดระยะขอบบนใน TextFrame. อ่าน/เขียน double.

**ส่งคืน:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

ส่งคืนหรือกำหนดระยะขอบบนใน TextFrame. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

ส่งคืนหรือกำหนดระยะขอบล่างใน TextFrame. อ่าน/เขียน double.

**ส่งคืน:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

ส่งคืนหรือกำหนดระยะขอบล่างใน TextFrame. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

ส่งคืนหรือกำหนดประเภทของข้อความแนวตั้ง. อ่าน/เขียน [TextVerticalType](../../com.aspose.slides/textverticaltype).

**ส่งคืน:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

ส่งคืนหรือกำหนดประเภทของข้อความแนวตั้ง. อ่าน/เขียน [TextVerticalType](../../com.aspose.slides/textverticaltype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |
### getTextAnchorType() {#getTextAnchorType--}
```
public abstract byte getTextAnchorType()
```

ส่งคืนหรือกำหนดประเภทของจุดยึดข้อความ. อ่าน/เขียน [TextAnchorType](../../com.aspose.slides/textanchortype).

**ส่งคืน:**
byte
### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public abstract void setTextAnchorType(byte value)
```

ส่งคืนหรือกำหนดประเภทของจุดยึดข้อความ. อ่าน/เขียน [TextAnchorType](../../com.aspose.slides/textanchortype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |
### getAnchorCenter() {#getAnchorCenter--}
```
public abstract boolean getAnchorCenter()
```

กำหนดว่ากล่องข้อความอยู่กึ่งกลางภายในเซลล์หรือไม่. อ่าน/เขียน boolean.

**ส่งคืน:**
boolean
### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public abstract void setAnchorCenter(boolean value)
```

กำหนดว่ากล่องข้อความอยู่กึ่งกลางภายในเซลล์หรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getFirstColumn() {#getFirstColumn--}
```
public abstract IColumn getFirstColumn()
```

ดึงคอลัมน์แรกของเซลล์. อ่านอย่างเดียว [IColumn](../../com.aspose.slides/icolumn).

**ส่งคืน:**
[IColumn](../../com.aspose.slides/icolumn)
### getFirstRow() {#getFirstRow--}
```
public abstract IRow getFirstRow()
```

ดึงแถวแรกของเซลล์. อ่านอย่างเดียว [IRow](../../com.aspose.slides/irow).

**ส่งคืน:**
[IRow](../../com.aspose.slides/irow)
### getColSpan() {#getColSpan--}
```
public abstract int getColSpan()
```

ส่งคืนจำนวนคอลัมน์ในกริดของตารางแม่ที่เซลล์ปัจจุบันครอบคลุม. คุณสมบัตินี้ทำให้เซลล์ดูเหมือนว่าถูกรวมกันโดยครอบคลุมขอบแนวตั้งของเซลล์อื่นในตาราง. อ่านอย่างเดียว int.

**ส่งคืน:**
int
### getRowSpan() {#getRowSpan--}
```
public abstract int getRowSpan()
```

ส่งคืนจำนวนแถวที่เซลล์ที่รวมกันครอบคลุม. นี้ใช้ร่วมกับแอตทริบิวต์ vMerge ในเซลล์อื่นเพื่อระบุเซลล์เริ่มต้นของการรวมแนวนอน. อ่านอย่างเดียว int.

**ส่งคืน:**
int
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

ส่งคืน TextFrame ของเซลล์. อ่านอย่างเดียว [ITextFrame](../../com.aspose.slides/itextframe).

**ส่งคืน:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTable() {#getTable--}
```
public abstract ITable getTable()
```

ส่งคืนออบเจ็กต์ Table พ่อแม่ของเซลล์. อ่านอย่างเดียว [ITable](../../com.aspose.slides/itable).

**ส่งคืน:**
[ITable](../../com.aspose.slides/itable)
### isMergedCell() {#isMergedCell--}
```
public abstract boolean isMergedCell()
```

ส่งคืนค่า true หากเซลล์ถูกรวบรวมกับเซลล์ใด ๆ ที่ปรับแล้ว, มิฉะนั้นส่งคืน false. อ่านอย่างเดียว boolean.

**ส่งคืน:**
boolean
### getCellFormat() {#getCellFormat--}
```
public abstract ICellFormat getCellFormat()
```

ส่งคืนออบเจ็กต์ CellFormat ที่ประกอบด้วยคุณสมบัติการจัดรูปแบบสำหรับเซลล์นี้. อ่านอย่างเดียว [ICellFormat](../../com.aspose.slides/icellformat).

**ส่งคืน:**
[ICellFormat](../../com.aspose.slides/icellformat)
### splitByColSpan(int index) {#splitByColSpan-int-}
```
public abstract void splitByColSpan(int index)
```

แยกเซลล์เป็นสองเซลล์ตามดัชนีของคอลัมน์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของคอลัมน์. |
### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public abstract void splitByRowSpan(int index)
```

แยกเซลล์เป็นสองเซลล์ตามดัชนีของแถว.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของแถว. |
### splitByHeight(double height) {#splitByHeight-double-}
```
public abstract void splitByHeight(double height)
```

แยกเซลล์ตามความสูง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| height | double | ความสูงของแถว. |
### splitByWidth(double width) {#splitByWidth-double-}
```
public abstract void splitByWidth(double width)
```

แยกเซลล์ตามความกว้าง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| width | double | ความกว้างของคอลัมน์. |