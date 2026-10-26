---
title: Cell
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงถึงเซลล์ของตาราง.
type: docs
url: /th/com.aspose.slides/cell/
---
**Inheritance:**  
การสืบทอด

**All Implemented Interfaces:**  
All Implemented Interfaces: [com.aspose.slides.ICell](../../com.aspose.slides/icell)
```
public class Cell implements IDOMObject, ICell
```

แสดงถึงเซลล์ของตาราง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | คืนค่าระยะทางจากด้านซ้ายของตารางถึงด้านซ้ายของเซลล์ |
| [getOffsetY()](#getOffsetY--) | คืนค่าระยะทางจากด้านบนของตารางถึงด้านบนของเซลล์ |
| [getFirstRowIndex()](#getFirstRowIndex--) | คืนค่าดัชนีของแถวแรกที่ครอบคลุมโดยเซลล์ |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | คืนค่าดัชนีของคอลัมน์แรกที่ครอบคลุมโดยเซลล์ |
| [getWidth()](#getWidth--) | คืนค่าความกว้างของเซลล์ |
| [getHeight()](#getHeight--) | คืนค่าความสูงของเซลล์ |
| [getMinimalHeight()](#getMinimalHeight--) | คืนค่าความสูงขั้นต่ำของเซลล์ |
| [getMarginLeft()](#getMarginLeft--) | คืนค่าหรือกำหนดระยะขอบด้านซ้ายใน TextFrame |
| [setMarginLeft(double value)](#setMarginLeft-double-) | คืนค่าหรือกำหนดระยะขอบด้านซ้ายใน TextFrame |
| [getMarginRight()](#getMarginRight--) | คืนค่าหรือกำหนดระยะขอบด้านขวาใน TextFrame |
| [setMarginRight(double value)](#setMarginRight-double-) | คืนค่าหรือกำหนดระยะขอบด้านขวาใน TextFrame |
| [getMarginTop()](#getMarginTop--) | คืนค่าหรือกำหนดระยะขอบด้านบนใน TextFrame |
| [setMarginTop(double value)](#setMarginTop-double-) | คืนค่าหรือกำหนดระยะขอบด้านบนใน TextFrame |
| [getMarginBottom()](#getMarginBottom--) | คืนค่าหรือกำหนดระยะขอบด้านล่างใน TextFrame |
| [setMarginBottom(double value)](#setMarginBottom-double-) | คืนค่าหรือกำหนดระยะขอบด้านล่างใน TextFrame |
| [getTextVerticalType()](#getTextVerticalType--) | คืนค่าหรือกำหนดประเภทของข้อความแนวตั้ง |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | คืนค่าหรือกำหนดประเภทของข้อความแนวตั้ง |
| [getTextAnchorType()](#getTextAnchorType--) | คืนค่าหรือกำหนดประเภทของการยึดข้อความ |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | คืนค่าหรือกำหนดประเภทของการยึดข้อความ |
| [getAnchorCenter()](#getAnchorCenter--) | กำหนดว่ากล่องข้อความอยู่ตรงกลางภายในเซลล์หรือไม่ |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | กำหนดว่ากล่องข้อความอยู่ตรงกลางภายในเซลล์หรือไม่ |
| [getFirstRow()](#getFirstRow--) | รับแถวแรกของเซลล์ |
| [getFirstColumn()](#getFirstColumn--) | รับคอลัมน์แรกของเซลล์ |
| [getColSpan()](#getColSpan--) | คืนค่าจำนวนคอลัมน์กริดในตารางแม่ซึ่งเซลล์ปัจจุบันจะครอบคลุม |
| [getRowSpan()](#getRowSpan--) | คืนค่าจำนวนแถวที่เซลล์ที่รวมกันครอบคลุม |
| [getTextFrame()](#getTextFrame--) | คืนค่า TextFrame ของเซลล์ |
| [getTable()](#getTable--) | คืนค่าออบเจ็กต์ Table พาเรนท์สำหรับเซลล์ |
| [isMergedCell()](#isMergedCell--) | คืนค่า true หากเซลล์ถูกรวมกับเซลล์ที่ปรับแล้ว, false ในกรณีอื่น |
| [getCellFormat()](#getCellFormat--) | คืนค่าออบเจ็กต์ CellFormat ที่มีคุณสมบัติการจัดรูปแบบสำหรับเซลล์นี้ |
| [splitByColSpan(int index)](#splitByColSpan-int-) | แบ่งเซลล์เป็นสองเซลล์โดยดัชนีของคอลัมน์ |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | แบ่งเซลล์เป็นสองเซลล์โดยดัชนีของแถว |
| [splitByHeight(double height)](#splitByHeight-double-) | แบ่งเซลล์ตามความสูง |
| [splitByWidth(double width)](#splitByWidth-double-) | แบ่งเซลล์ตามความกว้าง |
| [getSlide()](#getSlide--) | คืนค่าหนังสือสไลด์พาเรนท์ของเซลล์ |
| [getPresentation()](#getPresentation--) | คืนค่าการนำเสนอพาเรนท์ของเซลล์ |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getOffsetX() {#getOffsetX--}
```
public final double getOffsetX()
```

คืนค่าระยะทางจากด้านซ้ายของตารางถึงด้านซ้ายของเซลล์ อ่านอย่างเดียว double.

**คืนค่า:**  
double

### getOffsetY() {#getOffsetY--}
```
public final double getOffsetY()
```

คืนค่าระยะทางจากด้านบนของตารางถึงด้านบนของเซลล์ อ่านอย่างเดียว double.

**คืนค่า:**  
double

### getFirstRowIndex() {#getFirstRowIndex--}
```
public final int getFirstRowIndex()
```

คืนค่าดัชนีของแถวแรกที่ครอบคลุมโดยเซลล์ อ่านอย่างเดียว int.

**คืนค่า:**  
int

### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public final int getFirstColumnIndex()
```

คืนค่าดัชนีของคอลัมน์แรกที่ครอบคลุมโดยเซลล์ อ่านอย่างเดียว int.

**คืนค่า:**  
int

### getWidth() {#getWidth--}
```
public final double getWidth()
```

คืนค่าความกว้างของเซลล์ อ่านอย่างเดียว double.

**คืนค่า:**  
double

### getHeight() {#getHeight--}
```
public final double getHeight()
```

คืนค่าความสูงของเซลล์ อ่านอย่างเดียว double.

**คืนค่า:**  
double

### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

คืนค่าความสูงขั้นต่ำของเซลล์ นี้คือผลรวมของความสูงขั้นต่ำของทุกแถวที่เซลล์ครอบคลุม อ่านอย่างเดียว double.

**คืนค่า:**  
double

### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

คืนค่าหรือกำหนดระยะขอบด้านซ้ายใน TextFrame อ่าน/เขียน double.

**คืนค่า:**  
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

คืนค่าหรือกำหนดระยะขอบด้านซ้ายใน TextFrame อ่าน/เขียน double.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

คืนค่าหรือกำหนดระยะขอบด้านขวาใน TextFrame อ่าน/เขียน double.

**คืนค่า:**  
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

คืนค่าหรือกำหนดระยะขอบด้านขวาใน TextFrame อ่าน/เขียน double.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

คืนค่าหรือกำหนดระยะขอบด้านบนใน TextFrame อ่าน/เขียน double.

**คืนค่า:**  
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

คืนค่าหรือกำหนดระยะขอบด้านบนใน TextFrame อ่าน/เขียน double.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

คืนค่าหรือกำหนดระยะขอบด้านล่างใน TextFrame อ่าน/เขียน double.

**คืนค่า:**  
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

คืนค่าหรือกำหนดระยะขอบด้านล่างใน TextFrame อ่าน/เขียน double.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

คืนค่าหรือกำหนดประเภทของข้อความแนวตั้ง อ่าน/เขียน [TextVerticalType](../../com.aspose.slides/textverticaltype).

**คืนค่า:**  
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

คืนค่าหรือกำหนดประเภทของข้อความแนวตั้ง อ่าน/เขียน [TextVerticalType](../../com.aspose.slides/textverticaltype).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getTextAnchorType() {#getTextAnchorType--}
```
public final byte getTextAnchorType()
```

คืนค่าหรือกำหนดประเภทของการยึดข้อความ อ่าน/เขียน [TextAnchorType](../../com.aspose.slides/textanchortype).

**คืนค่า:**  
byte

### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public final void setTextAnchorType(byte value)
```

คืนค่าหรือกำหนดประเภทของการยึดข้อความ อ่าน/เขียน [TextAnchorType](../../com.aspose.slides/textanchortype).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getAnchorCenter() {#getAnchorCenter--}
```
public final boolean getAnchorCenter()
```

กำหนดว่ากล่องข้อความอยู่ตรงกลางภายในเซลล์หรือไม่ อ่าน/เขียน boolean.

**คืนค่า:**  
boolean

### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public final void setAnchorCenter(boolean value)
```

กำหนดว่ากล่องข้อความอยู่ตรงกลางภายในเซลล์หรือไม่ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final IRow getFirstRow()
```

รับแถวแรกของเซลล์ อ่านอย่างเดียว [IRow](../../com.aspose.slides/irow).

**คืนค่า:**  
[IRow](../../com.aspose.slides/irow)

### getFirstColumn() {#getFirstColumn--}
```
public final IColumn getFirstColumn()
```

รับคอลัมน์แรกของเซลล์ อ่านอย่างเดียว [IColumn](../../com.aspose.slides/icolumn).

**คืนค่า:**  
[IColumn](../../com.aspose.slides/icolumn)

### getColSpan() {#getColSpan--}
```
public final int getColSpan()
```

คืนค่าจำนวนคอลัมน์กริดในตารางแม่ซึ่งเซลล์ปัจจุบันจะครอบคลุม นี้เป็นคุณสมบัติที่ทำให้เซลล์ดูเหมือนถูกรวมโดยการครอบคลุมขอบแนวตั้งของเซลล์อื่นในตาราง อ่านอย่างเดียว int.

**คืนค่า:**  
int

### getRowSpan() {#getRowSpan--}
```
public final int getRowSpan()
```

คืนค่าจำนวนแถวที่เซลล์ที่รวมกันครอบคลุม นี้ใช้ร่วมกับแอตทริบิวต์ vMerge ในเซลล์อื่นเพื่อระบุเซลล์เริ่มต้นของการรวมแนวนอน อ่านอย่างเดียว int.

**คืนค่า:**  
int

### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

คืนค่า TextFrame ของเซลล์ อ่านอย่างเดียว [ITextFrame](../../com.aspose.slides/itextframe).

**คืนค่า:**  
[ITextFrame](../../com.aspose.slides/itextframe)

### getTable() {#getTable--}
```
public final ITable getTable()
```

คืนค่าออบเจ็กต์ Table พาเรนท์สำหรับเซลล์ อ่านอย่างเดียว [ITable](../../com.aspose.slides/itable).

**คืนค่า:**  
[ITable](../../com.aspose.slides/itable)

### isMergedCell() {#isMergedCell--}
```
public final boolean isMergedCell()
```

คืนค่า true หากเซลล์ถูกรวมกับเซลล์ที่ปรับแล้ว, false ในกรณีอื่น อ่านอย่างเดียว boolean.

**คืนค่า:**  
boolean

### getCellFormat() {#getCellFormat--}
```
public final ICellFormat getCellFormat()
```

คืนค่าออบเจ็กต์ CellFormat ที่มีคุณสมบัติการจัดรูปแบบสำหรับเซลล์นี้ อ่านอย่างเดียว [ICellFormat](../../com.aspose.slides/icellformat).

**คืนค่า:**  
[ICellFormat](../../com.aspose.slides/icellformat)

### splitByColSpan(int index) {#splitByColSpan-int-}
```
public final void splitByColSpan(int index)
```

แบ่งเซลล์เป็นสองเซลล์โดยดัชนีของคอลัมน์.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีของคอลัมน์ |

### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public final void splitByRowSpan(int index)
```

แบ่งเซลล์เป็นสองเซลล์โดยดัชนีของแถว.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีของแถว |

### splitByHeight(double height) {#splitByHeight-double-}
```
public final void splitByHeight(double height)
```

แบ่งเซลล์ตามความสูง.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| height | double | ความสูงของแถว |

### splitByWidth(double width) {#splitByWidth-double-}
```
public final void splitByWidth(double width)
```

แบ่งเซลล์ตามความกว้าง.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | double | ความกว้างของคอลัมน์ |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

คืนค่าหนังสือสไลด์พาเรนท์ของเซลล์ อ่านอย่างเดียว [IBaseSlide](../../com.aspose.slides/ibaseslide).

**คืนค่า:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

คืนค่าการนำเสนอพาเรนท์ของเซลล์ อ่านอย่างเดียว [IPresentation](../../com.aspose.slides/ipresentation).

**คืนค่า:**  
[IPresentation](../../com.aspose.slides/ipresentation)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

คืนค่าออบเจ็กต์ Parent_Immediate อ่านอย่างเดียว IDOMObject.

**คืนค่า:**  
com.aspose.slides.IDOMObject