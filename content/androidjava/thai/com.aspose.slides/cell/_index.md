---
title: Cell
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงถึงเซลล์ของตาราง.
type: docs
url: /th/com.aspose.slides/cell/
---
**การสืบทอด:**  
java.lang.Object

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**  
com.aspose.slides.IDOMObject, [com.aspose.slides.ICell](../../com.aspose.slides/icell)  
```
public class Cell implements IDOMObject, ICell
```

แสดงถึงเซลล์ของตาราง.  
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | คืนค่าระยะห่างจากด้านซ้ายของตารางถึงด้านซ้ายของเซลล์. |
| [getOffsetY()](#getOffsetY--) | คืนค่าระยะห่างจากด้านบนของตารางถึงด้านบนของเซลล์. |
| [getFirstRowIndex()](#getFirstRowIndex--) | คืนค่าดัชนีของแถวแรกที่เซลล์ครอบคลุม. |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | คืนค่าดัชนีของคอลัมน์แรกที่เซลล์ครอบคลุม. |
| [getWidth()](#getWidth--) | คืนค่าความกว้างของเซลล์. |
| [getHeight()](#getHeight--) | คืนค่าความสูงของเซลล์. |
| [getMinimalHeight()](#getMinimalHeight--) | คืนค่าความสูงต่ำสุดของเซลล์. |
| [getMarginLeft()](#getMarginLeft--) | คืนค่าหรือกำหนดระยะขอบซ้ายใน TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | คืนค่าหรือกำหนดระยะขอบซ้ายใน TextFrame. |
| [getMarginRight()](#getMarginRight--) | คืนค่าหรือกำหนดระยะขอบขวาใน TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | คืนค่าหรือกำหนดระยะขอบขวาใน TextFrame. |
| [getMarginTop()](#getMarginTop--) | คืนค่าหรือกำหนดระยะขอบบนใน TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | คืนค่าหรือกำหนดระยะขอบบนใน TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | คืนค่าหรือกำหนดระยะขอบล่างใน TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | คืนค่าหรือกำหนดระยะขอบล่างใน TextFrame. |
| [getTextVerticalType()](#getTextVerticalType--) | คืนค่าหรือกำหนดประเภทของข้อความแนวตั้ง. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | คืนค่าหรือกำหนดประเภทของข้อความแนวตั้ง. |
| [getTextAnchorType()](#getTextAnchorType--) | คืนค่าหรือกำหนดประเภทของจุดยึดข้อความ. |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | คืนค่าหรือกำหนดประเภทของจุดยึดข้อความ. |
| [getAnchorCenter()](#getAnchorCenter--) | กำหนดว่า TextBox อยู่ศูนย์กลางภายในเซลล์หรือไม่. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | กำหนดว่า TextBox อยู่ศูนย์กลางภายในเซลล์หรือไม่. |
| [getFirstRow()](#getFirstRow--) | ดึงแถวแรกของเซลล์. |
| [getFirstColumn()](#getFirstColumn--) | ดึงคอลัมน์แรกของเซลล์. |
| [getColSpan()](#getColSpan--) | คืนค่าจำนวนคอลัมน์ของกริดในตารางแม่ที่เซลล์ปัจจุบันครอบคลุม. |
| [getRowSpan()](#getRowSpan--) | คืนค่าจำนวนแถวที่เซลล์ที่รวมกันครอบคลุม. |
| [getTextFrame()](#getTextFrame--) | คืนค่ากรอบข้อความของเซลล์. |
| [getTable()](#getTable--) | คืนค่าอ็อบเจกต์ Table พาเรนต์ของเซลล์. |
| [isMergedCell()](#isMergedCell--) | คืนค่า true หากเซลล์ถูกรวมกับเซลล์ใด ๆ ที่ปรับแล้ว, false หากไม่เป็นเช่นนั้น. |
| [getCellFormat()](#getCellFormat--) | คืนค่าอ็อบเจกต์ CellFormat ที่บรรจุคุณสมบัติการจัดรูปแบบของเซลล์นี้. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | แยกเซลล์เป็นสองเซลล์ตามดัชนีของคอลัมน์. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | แยกเซลล์เป็นสองเซลล์ตามดัชนีของแถว. |
| [splitByHeight(double height)](#splitByHeight-double-) | แยกเซลล์ตามความสูง. |
| [splitByWidth(double width)](#splitByWidth-double-) | แยกเซลล์ตามความกว้าง. |
| [getSlide()](#getSlide--) | คืนค่าสไลด์พาเรนต์ของเซลล์. |
| [getPresentation()](#getPresentation--) | คืนค่าการนำเสนอพาเรนต์ของเซลล์. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getOffsetX() {#getOffsetX--}
```
public final double getOffsetX()
```

คืนค่าระยะห่างจากด้านซ้ายของตารางถึงด้านซ้ายของเซลล์. อ่านอย่างเดียว double.

**คืนค่า:**  
double

### getOffsetY() {#getOffsetY--}
```
public final double getOffsetY()
```

คืนค่าระยะห่างจากด้านบนของตารางถึงด้านบนของเซลล์. อ่านอย่างเดียว double.

**คืนค่า:**  
double

### getFirstRowIndex() {#getFirstRowIndex--}
```
public final int getFirstRowIndex()
```

คืนค่าดัชนีของแถวแรกที่เซลล์ครอบคลุม. อ่านอย่างเดียว int.

**คืนค่า:**  
int

### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public final int getFirstColumnIndex()
```

คืนค่าดัชนีของคอลัมน์แรกที่เซลล์ครอบคลุม. อ่านอย่างเดียว int.

**คืนค่า:**  
int

### getWidth() {#getWidth--}
```
public final double getWidth()
```

คืนค่าความกว้างของเซลล์. อ่านอย่างเดียว double.

**คืนค่า:**  
double

### getHeight() {#getHeight--}
```
public final double getHeight()
```

คืนค่าความสูงของเซลล์. อ่านอย่างเดียว double.

**คืนค่า:**  
double

### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

คืนค่าความสูงต่ำสุดของเซลล์. นี้คือผลรวมของความสูงต่ำสุดของแถวทั้งหมดที่เซลล์ครอบคลุม. อ่านอย่างเดียว double.

**คืนค่า:**  
double

### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

คืนค่าหรือกำหนดระยะขอบซ้ายใน TextFrame. อ่าน/เขียน double.

**คืนค่า:**  
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

คืนค่าหรือกำหนดระยะขอบซ้ายใน TextFrame. อ่าน/เขียน double.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

คืนค่าหรือกำหนดระยะขอบขวาใน TextFrame. อ่าน/เขียน double.

**คืนค่า:**  
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

คืนค่าหรือกำหนดระยะขอบขวาใน TextFrame. อ่าน/เขียน double.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

คืนค่าหรือกำหนดระยะขอบบนใน TextFrame. อ่าน/เขียน double.

**คืนค่า:**  
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

คืนค่าหรือกำหนดระยะขอบบนใน TextFrame. อ่าน/เขียน double.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

คืนค่าหรือกำหนดระยะขอบล่างใน TextFrame. อ่าน/เขียน double.

**คืนค่า:**  
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

คืนค่าหรือกำหนดระยะขอบล่างใน TextFrame. อ่าน/เขียน double.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

คืนค่าหรือกำหนดประเภทของข้อความแนวตั้ง. อ่าน/เขียน [TextVerticalType](../../com.aspose.slides/textverticaltype).

**คืนค่า:**  
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

คืนค่าหรือกำหนดประเภทของข้อความแนวตั้ง. อ่าน/เขียน [TextVerticalType](../../com.aspose.slides/textverticaltype).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getTextAnchorType() {#getTextAnchorType--}
```
public final byte getTextAnchorType()
```

คืนค่าหรือกำหนดประเภทของจุดยึดข้อความ. อ่าน/เขียน [TextAnchorType](../../com.aspose.slides/textanchortype).

**คืนค่า:**  
byte

### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public final void setTextAnchorType(byte value)
```

คืนค่าหรือกำหนดประเภทของจุดยึดข้อความ. อ่าน/เขียน [TextAnchorType](../../com.aspose.slides/textanchortype).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getAnchorCenter() {#getAnchorCenter--}
```
public final boolean getAnchorCenter()
```

กำหนดว่า TextBox อยู่ศูนย์กลางภายในเซลล์หรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**  
boolean

### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public final void setAnchorCenter(boolean value)
```

กำหนดว่า TextBox อยู่ศูนย์กลางภายในเซลล์หรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final IRow getFirstRow()
```

ดึงแถวแรกของเซลล์. อ่านอย่างเดียว [IRow](../../com.aspose.slides/irow).

**คืนค่า:**  
[IRow](../../com.aspose.slides/irow)

### getFirstColumn() {#getFirstColumn--}
```
public final IColumn getFirstColumn()
```

ดึงคอลัมน์แรกของเซลล์. อ่านอย่างเดียว [IColumn](../../com.aspose.slides/icolumn).

**คืนค่า:**  
[IColumn](../../com.aspose.slides/icolumn)

### getColSpan() {#getColSpan--}
```
public final int getColSpan()
```

คืนค่าจำนวนคอลัมน์ของกริดในตารางแม่ที่เซลล์ปัจจุบันครอบคลุม. คุณสมบัตินี้ทำให้เซลล์ดูเหมือนรวมกันโดยการครอบคลุมขอบแนวตั้งของเซลล์อื่นในตาราง. อ่านอย่างเดียว int.

**คืนค่า:**  
int

### getRowSpan() {#getRowSpan--}
```
public final int getRowSpan()
```

คืนค่าจำนวนแถวที่เซลล์ที่รวมกันครอบคลุม. นี้ใช้ร่วมกับแอตทริบิวต์ vMerge ของเซลล์อื่นเพื่อระบุเซลล์เริ่มต้นของการรวมแนวนอน. อ่านอย่างเดียว int.

**คืนค่า:**  
int

### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

คืนค่ากรอบข้อความของเซลล์. อ่านอย่างเดียว [ITextFrame](../../com.aspose.slides/itextframe).

**คืนค่า:**  
[ITextFrame](../../com.aspose.slides/itextframe)

### getTable() {#getTable--}
```
public final ITable getTable()
```

คืนค่าอ็อบเจกต์ Table พาเรนต์ของเซลล์. อ่านอย่างเดียว [ITable](../../com.aspose.slides/itable).

**คืนค่า:**  
[ITable](../../com.aspose.slides/itable)

### isMergedCell() {#isMergedCell--}
```
public final boolean isMergedCell()
```

คืนค่า true หากเซลล์ถูกรวมกับเซลล์ใด ๆ ที่ปรับแล้ว, false หากไม่เป็นเช่นนั้น. อ่านอย่างเดียว boolean.

**คืนค่า:**  
boolean

### getCellFormat() {#getCellFormat--}
```
public final ICellFormat getCellFormat()
```

คืนค่าอ็อบเจกต์ CellFormat ที่บรรจุคุณสมบัติการจัดรูปแบบของเซลล์นี้. อ่านอย่างเดียว [ICellFormat](../../com.aspose.slides/icellformat).

**คืนค่า:**  
[ICellFormat](../../com.aspose.slides/icellformat)

### splitByColSpan(int index) {#splitByColSpan-int-}
```
public final void splitByColSpan(int index)
```

แยกเซลล์เป็นสองเซลล์ตามดัชนีของคอลัมน์.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของคอลัมน์. |

### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public final void splitByRowSpan(int index)
```

แยกเซลล์เป็นสองเซลล์ตามดัชนีของแถว.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของแถว. |

### splitByHeight(double height) {#splitByHeight-double-}
```
public final void splitByHeight(double height)
```

แยกเซลล์ตามความสูง.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| height | double | ความสูงของแถว. |

### splitByWidth(double width) {#splitByWidth-double-}
```
public final void splitByWidth(double width)
```

แยกเซลล์ตามความกว้าง.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| width | double | ความกว้างของคอลัมน์. |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

คืนค่าสไลด์พาเรนต์ของเซลล์. อ่านอย่างเดียว [IBaseSlide](../../com.aspose.slides/ibaseslide).

**คืนค่า:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

คืนค่าการนำเสนอพาเรนต์ของเซลล์. อ่านอย่างเดียว [IPresentation](../../com.aspose.slides/ipresentation).

**คืนค่า:**  
[IPresentation](../../com.aspose.slides/ipresentation)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

คืนค่า Parent_Immediate object. อ่านอย่างเดียว IDOMObject.

**คืนค่า:**  
com.aspose.slides.IDOMObject