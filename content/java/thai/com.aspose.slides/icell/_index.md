---
title: ICell
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: เป็นตัวแทนของเซลล์ในตาราง.
type: docs
url: /th/com.aspose.slides/icell/
---
**ทุกอินเทอร์เฟซที่ใช้:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ICell extends ISlideComponent
```

เป็นตัวแทนของ cell ใน table.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | คืนค่าระยะทางจากด้านซ้ายของ table ไปยังด้านซ้ายของ cell. |
| [getOffsetY()](#getOffsetY--) | คืนค่าระยะทางจากด้านบนของ table ไปยังด้านบนของ cell. |
| [getFirstRowIndex()](#getFirstRowIndex--) | คืนค่าดัชนีของแถวแรกที่ cell ครอบคลุม. |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | คืนค่าดัชนีของคอลัมน์แรกที่ cell ครอบคลุม. |
| [getWidth()](#getWidth--) | คืนค่าความกว้างของ cell. |
| [getHeight()](#getHeight--) | คืนค่าความสูงของ cell. |
| [getMinimalHeight()](#getMinimalHeight--) | คืนค่าความสูงขั้นต่ำของ cell. |
| [getMarginLeft()](#getMarginLeft--) | คืนค่า หรือกำหนดระยะขอบซ้ายใน TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | คืนค่า หรือกำหนดระยะขอบซ้ายใน TextFrame. |
| [getMarginRight()](#getMarginRight--) | คืนค่า หรือกำหนดระยะขอบขวาใน TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | คืนค่า หรือกำหนดระยะขอบขวาใน TextFrame. |
| [getMarginTop()](#getMarginTop--) | คืนค่า หรือกำหนดระยะขอบบนใน TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | คืนค่า หรือกำหนดระยะขอบบนใน TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | คืนค่า หรือกำหนดระยะขอบล่างใน TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | คืนค่า หรือกำหนดระยะขอบล่างใน TextFrame. |
| [getTextVerticalType()](#getTextVerticalType--) | คืนค่า หรือกำหนดประเภทของข้อความแนวตั้ง. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | คืนค่า หรือกำหนดประเภทของข้อความแนวตั้ง. |
| [getTextAnchorType()](#getTextAnchorType--) | คืนค่า หรือกำหนดประเภทของจุดยึดข้อความ. |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | คืนค่า หรือกำหนดประเภทของจุดยึดข้อความ. |
| [getAnchorCenter()](#getAnchorCenter--) | กำหนดว่ากล่องข้อความถูกจัดกึ่งกลางภายใน cell หรือไม่. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | กำหนดว่ากล่องข้อความถูกจัดกึ่งกลางภายใน cell หรือไม่. |
| [getFirstColumn()](#getFirstColumn--) | รับค่าคอลัมน์แรกของ cell. |
| [getFirstRow()](#getFirstRow--) | รับค่าแถวแรกของ cell. |
| [getColSpan()](#getColSpan--) | คืนค่าจำนวนคอลัมน์ในตารางกริดของ parent table ที่จะถูกครอบคลุมโดย cell ปัจจุบัน. |
| [getRowSpan()](#getRowSpan--) | คืนค่าจำนวนแถวที่ cell ที่รวมกันครอบคลุม. |
| [getTextFrame()](#getTextFrame--) | คืนค่า TextFrame ของ cell. |
| [getTable()](#getTable--) | คืนค่าอ็อบเจกต์ Table พาเรนต์สำหรับ cell. |
| [isMergedCell()](#isMergedCell--) | คืนค่า true หาก cell ถูกรวมกับ cell ที่ปรับปรุงแล้ว, false ในกรณีอื่น. |
| [getCellFormat()](#getCellFormat--) | คืนค่าอ็อบเจกต์ CellFormat ที่มีคุณสมบัติการจัดรูปแบบสำหรับ cell นี้. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | แยก cell เป็นสอง cell ตามดัชนีของคอลัมน์. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | แยก cell เป็นสอง cell ตามดัชนีของแถว. |
| [splitByHeight(double height)](#splitByHeight-double-) | แยก cell ตามความสูง. |
| [splitByWidth(double width)](#splitByWidth-double-) | แยก cell ตามความกว้าง. |

### getOffsetX() {#getOffsetX--}
```
public abstract double getOffsetX()
```

คืนค่าระยะทางจากด้านซ้ายของ table ไปยังด้านซ้ายของ cell. อ่านอย่างเดียว double.

**คืนค่า:**
double

### getOffsetY() {#getOffsetY--}
```
public abstract double getOffsetY()
```

คืนค่าระยะทางจากด้านบนของ table ไปยังด้านบนของ cell. อ่านอย่างเดียว double.

**คืนค่า:**
double

### getFirstRowIndex() {#getFirstRowIndex--}
```
public abstract int getFirstRowIndex()
```

คืนค่าดัชนีของแถวแรกที่ cell ครอบคลุม. อ่านอย่างเดียว int.

**คืนค่า:**
int

### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public abstract int getFirstColumnIndex()
```

คืนค่าดัชนีของคอลัมน์แรกที่ cell ครอบคลุม. อ่านอย่างเดียว int.

**คืนค่า:**
int

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

คืนค่าความกว้างของ cell. อ่านอย่างเดียว double.

**คืนค่า:**
double

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```

คืนค่าความสูงของ cell. อ่านอย่างเดียว double.

**คืนค่า:**
double

### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```

คืนค่าความสูงขั้นต่ำของ cell. นี่คือผลรวมของความสูงขั้นต่ำของทุกแถวที่ cell ครอบคลุม. อ่านอย่างเดียว double.

**คืนค่า:**
double

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

คืนค่า หรือกำหนดระยะขอบซ้ายใน TextFrame. อ่าน/เขียน double.

**คืนค่า:**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

คืนค่า หรือกำหนดระยะขอบซ้ายใน TextFrame. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

คืนค่า หรือกำหนดระยะขอบขวาใน TextFrame. อ่าน/เขียน double.

**คืนค่า:**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

คืนค่า หรือกำหนดระยะขอบขวาใน TextFrame. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

คืนค่า หรือกำหนดระยะขอบบนใน TextFrame. อ่าน/เขียน double.

**คืนค่า:**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

คืนค่า หรือกำหนดระยะขอบบนใน TextFrame. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

คืนค่า หรือกำหนดระยะขอบล่างใน TextFrame. อ่าน/เขียน double.

**คืนค่า:**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

คืนค่า หรือกำหนดระยะขอบล่างใน TextFrame. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

คืนค่า หรือกำหนดประเภทของข้อความแนวตั้ง. อ่าน/เขียน [TextVerticalType](../../com.aspose.slides/textverticaltype).

**คืนค่า:**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

คืนค่า หรือกำหนดประเภทของข้อความแนวตั้ง. อ่าน/เขียน [TextVerticalType](../../com.aspose.slides/textverticaltype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getTextAnchorType() {#getTextAnchorType--}
```
public abstract byte getTextAnchorType()
```

คืนค่า หรือกำหนดประเภทของจุดยึดข้อความ. อ่าน/เขียน [TextAnchorType](../../com.aspose.slides/textanchortype).

**คืนค่า:**
byte

### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public abstract void setTextAnchorType(byte value)
```

คืนค่า หรือกำหนดประเภทของจุดยึดข้อความ. อ่าน/เขียน [TextAnchorType](../../com.aspose.slides/textanchortype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getAnchorCenter() {#getAnchorCenter--}
```
public abstract boolean getAnchorCenter()
```

กำหนดว่ากล่องข้อความถูกจัดกึ่งกลางภายใน cell หรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public abstract void setAnchorCenter(boolean value)
```

กำหนดว่ากล่องข้อความถูกจัดกึ่งกลางภายใน cell หรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getFirstColumn() {#getFirstColumn--}
```
public abstract IColumn getFirstColumn()
```

รับค่าคอลัมน์แรกของ cell. อ่านอย่างเดียว [IColumn](../../com.aspose.slides/icolumn).

**คืนค่า:**
[IColumn](../../com.aspose.slides/icolumn)

### getFirstRow() {#getFirstRow--}
```
public abstract IRow getFirstRow()
```

รับค่าแถวแรกของ cell. อ่านอย่างเดียว [IRow](../../com.aspose.slides/irow).

**คืนค่า:**
[IRow](../../com.aspose.slides/irow)

### getColSpan() {#getColSpan--}
```
public abstract int getColSpan()
```

คืนค่าจำนวนคอลัมน์ในตารางกริดของ parent table ที่จะถูกครอบคลุมโดย cell ปัจจุบัน. คุณสมบัตินี้ทำให้ cell ดูเหมือนว่าถูกผสานโดยการขยายขอบแนวตั้งของ cell อื่นในตาราง. อ่านอย่างเดียว int.

**คืนค่า:**
int

### getRowSpan() {#getRowSpan--}
```
public abstract int getRowSpan()
```

คืนค่าจำนวนแถวที่ cell ที่รวมกันครอบคลุม. ใช้ร่วมกับแอตทริบิวต์ vMerge บน cell อื่นเพื่อระบุ cell เริ่มต้นของการผสานแนวนอน. อ่านอย่างเดียว int.

**คืนค่า:**
int

### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

คืนค่า TextFrame ของ cell. อ่านอย่างเดียว [ITextFrame](../../com.aspose.slides/itextframe).

**คืนค่า:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTable() {#getTable--}
```
public abstract ITable getTable()
```

คืนค่าอ็อบเจกต์ Table พาเรนต์สำหรับ cell. อ่านอย่างเดียว [ITable](../../com.aspose.slides/itable).

**คืนค่า:**
[ITable](../../com.aspose.slides/itable)

### isMergedCell() {#isMergedCell--}
```
public abstract boolean isMergedCell()
```

คืนค่า true หาก cell ถูกรวมกับ cell ที่ปรับปรุงแล้ว, false ในกรณีอื่น. อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean

### getCellFormat() {#getCellFormat--}
```
public abstract ICellFormat getCellFormat()
```

คืนค่าอ็อบเจกต์ CellFormat ที่มีคุณสมบัติการจัดรูปแบบสำหรับ cell นี้. อ่านอย่างเดียว [ICellFormat](../../com.aspose.slides/icellformat).

**คืนค่า:**
[ICellFormat](../../com.aspose.slides/icellformat)

### splitByColSpan(int index) {#splitByColSpan-int-}
```
public abstract void splitByColSpan(int index)
```

แยก cell เป็นสอง cell ตามดัชนีของคอลัมน์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของคอลัมน์. |

### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public abstract void splitByRowSpan(int index)
```

แยก cell เป็นสอง cell ตามดัชนีของแถว.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของแถว. |

### splitByHeight(double height) {#splitByHeight-double-}
```
public abstract void splitByHeight(double height)
```

แยก cell ตามความสูง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| height | double | ความสูงของแถว. |

### splitByWidth(double width) {#splitByWidth-double-}
```
public abstract void splitByWidth(double width)
```

แยก cell ตามความกว้าง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| width | double | ความกว้างของคอลัมน์. |