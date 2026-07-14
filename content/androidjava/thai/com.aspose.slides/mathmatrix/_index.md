---
title: MathMatrix
second_title: Aspose.Slides สำหรับ Android ผ่านเอกสารอ้างอิง API Java
description: ระบุวัตถุ Matrix ที่ประกอบด้วยองค์ประกอบลูกซึ่งจัดเรียงเป็นหนึ่งหรือหลายแถวและคอลัมน์
type: docs
url: /th/com.aspose.slides/mathmatrix/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**ส่วนต่อประสานที่ทำตามทั้งหมด:**
[com.aspose.slides.IMathMatrix](../../com.aspose.slides/imathmatrix), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathMatrix extends MathElementBase implements IMathMatrix, IHasControlCharacterProperties
```

ระบุวัตถุ Matrix ซึ่งประกอบด้วยองค์ประกอบย่อยที่จัดเรียงเป็นหนึ่งหรือหลายแถวและคอลัมน์  มันสำคัญที่ต้องสังเกตว่าเมทริกซ์ไม่มีตัวคั่นในตัว  เพื่อใส่เมทริกซ์ในวงเล็บ คุณควรใช้วัตถุตัวคั่น (IMathDelimiter)  อาร์กิวเมนต์ null สามารถใช้เพื่อสร้างช่องว่างในเมทริกซ์ได้.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [MathMatrix(int rowCount, int columnCount)](#MathMatrix-int-int-) | Initialises a new instance of the MathMatrix class. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getRowCount()](#getRowCount--) | จำนวนแถวในเมทริกซ์ |
| [getColumnCount()](#getColumnCount--) | จำนวนคอลัมน์ในเมทริกซ์ |
| [getHidePlaceholders()](#getHidePlaceholders--) | ซ่อนตัวแทนตำแหน่งสำหรับองค์ประกอบเมทริกซ์ที่ว่าง เริ่มต้น: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | ซ่อนตัวแทนตำแหน่งสำหรับองค์ประกอบเมทริกซ์ที่ว่าง เริ่มต้น: false |
| [getBaseJustification()](#getBaseJustification--) | ระบุการจัดแนวแนวตั้งสัมพันธ์กับข้อความโดยรอบ |
| [setBaseJustification(int value)](#setBaseJustification-int-) | ระบุการจัดแนวแนวตั้งสัมพันธ์กับข้อความโดยรอบ |
| [getMinColumnWidth()](#getMinColumnWidth--) | ความกว้างคอลัมน์ขั้นต่ำใน twips (1/20 ของจุด) ระยะห่างช่องว่าง (เรียกอีกอย่างว่า "Column Gap" หรือ "Gap Width") จะถูกเพิ่มเข้าไปที่ MinColumnWidth เพื่อกำหนดระยะห่างคอลัมน์ทั้งหมดของเมทริกซ์ (ระยะห่างระหว่างขอบเดียวกันของคอลัมน์ต่าง ๆ) |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | ความกว้างคอลัมน์ขั้นต่ำใน twips (1/20 ของจุด) ระยะห่างช่องว่าง (เรียกอีกอย่างว่า "Column Gap" หรือ "Gap Width") จะถูกเพิ่มเข้าไปที่ MinColumnWidth เพื่อกำหนดระยะห่างคอลัมน์ทั้งหมดของเมทริกซ์ (ระยะห่างระหว่างขอบเดียวกันของคอลัมน์ต่าง ๆ) |
| [getColumnGapRule()](#getColumnGapRule--) | ประเภทของช่องว่างแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หน่วยช่องว่างแนวนอนสามารถเป็น em หรือ point (เก็บเป็น twips) |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | ประเภทของช่องว่างแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หน่วยช่องว่างแนวนอนสามารถเป็น em หรือ point (เก็บเป็น twips) |
| [getColumnGap()](#getColumnGap--) | ค่าเครื่องหมายช่องว่างแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หาก ColumnGapRule ตั้งเป็น 3 ("Exactly") หน่วยจะถือเป็น twips (1/20 ของจุด) หาก ColumnGapRule ตั้งเป็น 4 ("Multiple") หน่วยจะถือเป็นจำนวนขั้น 0.5 em. ในกรณีอื่นจะถูกละเว้น ค่าเริ่มต้น: 0 |
| [setColumnGap(long value)](#setColumnGap-long-) | ค่าเครื่องหมายช่องว่างแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หาก ColumnGapRule ตั้งเป็น 3 ("Exactly") หน่วยจะถือเป็น twips (1/20 ของจุด) หาก ColumnGapRule ตั้งเป็น 4 ("Multiple") หน่วยจะถือเป็นจำนวนขั้น 0.5 em. ในกรณีอื่นจะถูกละเว้น ค่าเริ่มต้น: 0 |
| [getRowGapRule()](#getRowGapRule--) | ประเภทของช่องว่างแนวตั้งระหว่างแถวของเมทริกซ์; หน่วยช่องว่างแนวตั้งสามารถเป็น line หรือ point (เก็บเป็น twips) |
| [setRowGapRule(int value)](#setRowGapRule-int-) | ประเภทของช่องว่างแนวตั้งระหว่างแถวของเมทริกซ์; หน่วยช่องว่างแนวตั้งสามารถเป็น line หรือ point (เก็บเป็น twips) |
| [getRowGap()](#getRowGap--) | ค่าเครื่องหมายช่องว่างแนวตั้งระหว่างแถวของเมทริกซ์; หาก RowGapRule ตั้งเป็น 3 ("Exactly") หน่วยจะถือเป็น twips (1/20 ของจุด) หาก RowGapRule ตั้งเป็น 4 ("Multiple") หน่วยจะถือเป็น half-lines. ค่าเริ่มต้น: 0 |
| [setRowGap(long value)](#setRowGap-long-) | ค่าเครื่องหมายช่องว่างแนวตั้งระหว่างแถวของเมทริกซ์; หาก RowGapRule ตั้งเป็น 3 ("Exactly") หน่วยจะถือเป็น twips (1/20 ของจุด) หาก RowGapRule ตั้งเป็น 4 ("Multiple") หน่วยจะถือเป็น half-lines. ค่าเริ่มต้น: 0 |
| [get_Item(int row, int column)](#get-Item-int-int-) | องค์ประกอบของเมทริกซ์ |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | องค์ประกอบของเมทริกซ์ |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | รับการจัดแนวแนวนอนของคอลัมน์ที่ระบุ |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | ตั้งการจัดแนวแนวนอนของคอลัมน์ที่ระบุ |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | ตั้งการจัดแนวแนวนอนของคอลัมน์ที่ระบุหลายคอลัมน์ |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | แทรกแถวใหม่ก่อนแถวที่ระบุ ทั้งหมดในแถวใหม่จะเป็น null |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | แทรกแถวใหม่หลังแถวที่ระบุ ทั้งหมดในแถวใหม่จะเป็น null |
| [deleteRow(int rowIndex)](#deleteRow-int-) | ลบแถวที่ระบุ |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | แทรกคอลัมน์ใหม่ก่อนคอลัมน์ที่ระบุ ทั้งหมดในคอลัมน์ใหม่จะเป็น null |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | แทรกคอลัมน์ใหม่หลังคอลัมน์ที่ระบุ ทั้งหมดในคอลัมน์ใหม่จะเป็น null |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | ลบคอลัมน์ที่ระบุ |
| [getChildren()](#getChildren--) | รับองค์ประกอบลูก |
### MathMatrix(int rowCount, int columnCount) {#MathMatrix-int-int-}
```
public MathMatrix(int rowCount, int columnCount)
```


Initialises a new instance of the MathMatrix class.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| rowCount | int | จำนวนแถว |
| columnCount | int | จำนวนคอลัมน์ |

### getRowCount() {#getRowCount--}
```
public final int getRowCount()
```


จำนวนแถวในเมทริกซ์

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int rowCount = matrix.getRowCount();
> ```

**ผลลัพธ์:**
int
### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```


จำนวนคอลัมน์ในเมทริกซ์

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int columnCount = matrix.getColumnCount();
> ```

**ผลลัพธ์:**
int
### getHidePlaceholders() {#getHidePlaceholders--}
```
public final boolean getHidePlaceholders()
```


ซ่อนตัวแทนตำแหน่งสำหรับองค์ประกอบเมทริกซ์ที่ว่าง เริ่มต้น: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**ผลลัพธ์:**
boolean
### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public final void setHidePlaceholders(boolean value)
```


ซ่อนตัวแทนตำแหน่งสำหรับองค์ประกอบเมทริกซ์ที่ว่าง เริ่มต้น: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```


ระบุการจัดแนวแนวตั้งสัมพันธ์กับข้อความโดยรอบ ค่าที่เป็นไปได้คือ top, bottom, และ center ค่าเริ่มต้น: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**ผลลัพธ์:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```


ระบุการจัดแนวแนวตั้งสัมพันธ์กับข้อความโดยรอบ ค่าที่เป็นไปได้คือ top, bottom, และ center ค่าเริ่มต้น: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getMinColumnWidth() {#getMinColumnWidth--}
```
public final long getMinColumnWidth()
```


ความกว้างคอลัมน์ขั้นต่ำใน twips (1/20 ของจุด) ระยะห่างช่องว่าง (เรียกอีกอย่างว่า "Column Gap" หรือ "Gap Width") จะถูกเพิ่มเข้าไปที่ MinColumnWidth เพื่อกำหนดระยะห่างคอลัมน์ทั้งหมดของเมทริกซ์ (ระยะห่างระหว่างขอบเดียวกันของคอลัมน์ต่าง ๆ) ค่าเริ่มต้น: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**ผลลัพธ์:**
long
### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public final void setMinColumnWidth(long value)
```


ความกว้างคอลัมน์ขั้นต่ำใน twips (1/20 ของจุด) ระยะห่างช่องว่าง (เรียกอีกอย่างว่า "Column Gap" หรือ "Gap Width") จะถูกเพิ่มเข้าไปที่ MinColumnWidth เพื่อกำหนดระยะห่างคอลัมน์ทั้งหมดของเมทริกซ์ (ระยะห่างระหว่างขอบเดียวกันของคอลัมน์ต่าง ๆ) ค่าเริ่มต้น: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | long |  |

### getColumnGapRule() {#getColumnGapRule--}
```
public final int getColumnGapRule()
```


ประเภทของช่องว่างแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หน่วยช่องว่างแนวนอนสามารถเป็น em หรือ point (เก็บเป็น twips) ค่าเริ่มต้น: SingleSpacingGap (0)

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**ผลลัพธ์:**
int
### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public final void setColumnGapRule(int value)
```


ประเภทของช่องว่างแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หน่วยช่องว่างแนวนอนสามารถเป็น em หรือ point (เก็บเป็น twips) ค่าเริ่มต้น: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getColumnGap() {#getColumnGap--}
```
public final long getColumnGap()
```


ค่าเครื่องหมายช่องว่างแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หาก ColumnGapRule ตั้งเป็น 3 ("Exactly") หน่วยจะถือเป็น twips (1/20 ของจุด) หาก ColumnGapRule ตั้งเป็น 4 ("Multiple") หน่วยจะถือเป็นจำนวนขั้น 0.5 em. ในกรณีอื่นจะถูกละเว้น ค่าเริ่มต้น: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**ผลลัพธ์:**
long
### setColumnGap(long value) {#setColumnGap-long-}
```
public final void setColumnGap(long value)
```


ค่าเครื่องหมายช่องว่างแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หาก ColumnGapRule ตั้งเป็น 3 ("Exactly") หน่วยจะถือเป็น twips (1/20 ของจุด) หาก ColumnGapRule ตั้งเป็น 4 ("Multiple") หน่วยจะถือเป็นจำนวนขั้น 0.5 em. ในกรณีอื่นจะถูกละเว้น ค่าเริ่มต้น: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | long |  |

### getRowGapRule() {#getRowGapRule--}
```
public final int getRowGapRule()
```


ประเภทของช่องว่างแนวตั้งระหว่างแถวของเมทริกซ์; หน่วยช่องว่างแนวตั้งสามารถเป็น line หรือ point (เก็บเป็น twips) ค่าเริ่มต้น: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**ผลลัพธ์:**
int
### setRowGapRule(int value) {#setRowGapRule-int-}
```
public final void setRowGapRule(int value)
```


ประเภทของช่องว่างแนวตั้งระหว่างแถวของเมทริกซ์; หน่วยช่องว่างแนวตั้งสามารถเป็น line หรือ point (เก็บเป็น twips) ค่าเริ่มต้น: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getRowGap() {#getRowGap--}
```
public final long getRowGap()
```


ค่าเครื่องหมายช่องว่างแนวตั้งระหว่างแถวของเมทริกซ์; หาก RowGapRule ตั้งเป็น 3 ("Exactly") หน่วยจะถือเป็น twips (1/20 ของจุด) หาก RowGapRule ตั้งเป็น 4 ("Multiple") หน่วยจะถือเป็น half-lines. ค่าเริ่มต้น: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**ผลลัพธ์:**
long
### setRowGap(long value) {#setRowGap-long-}
```
public final void setRowGap(long value)
```


ค่าเครื่องหมายช่องว่างแนวตั้งระหว่างแถวของเมทริกซ์; หาก RowGapRule ตั้งเป็น 3 ("Exactly") หน่วยจะถือเป็น twips (1/20 ของจุด) หาก RowGapRule ตั้งเป็น 4 ("Multiple") หน่วยจะถือเป็น half-lines. ค่าเริ่มต้น: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | long |  |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public final IMathElement get_Item(int row, int column)
```


องค์ประกอบของเมทริกซ์

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| row | int | ดัชนีเริ่มต้นที่ 0 ของแถวที่ต้องการดึงรายการ |
| column | int | ดัชนีเริ่มต้นที่ 0 ของคอลัมน์ที่ต้องการดึงรายการ |

**ผลลัพธ์:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int row, int column, IMathElement value)
```


องค์ประกอบของเมทริกซ์

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| row | int | ดัชนีเริ่มต้นที่ 0 ของแถวที่ต้องการดึงรายการ |
| column | int | ดัชนีเริ่มต้นที่ 0 ของคอลัมน์ที่ต้องการดึงรายการ |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Control Character Properties

**ผลลัพธ์:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public final int getColumnAlignment(int columnIndex)
```


รับการจัดแนวแนวนอนของคอลัมน์ที่ระบุ

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| columnIndex | int | ดัชนีคอลัมน์เริ่มต้นที่ 0 |

**ผลลัพธ์:**
int - การจัดแนวแนวนอนของคอลัมน์ที่ระบุ
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public final void setColumnAlignment(int columnIndex, int val)
```


ตั้งการจัดแนวแนวนอนของคอลัมน์ที่ระบุ

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| columnIndex | int | ดัชนีคอลัมน์เริ่มต้นที่ 0 |
| val | int | ค่าใหม่ของการจัดแนวแนวนอนของคอลัมน์ที่ระบุ |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public final void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```


ตั้งการจัดแนวแนวนอนของคอลัมน์ที่ระบุหลายคอลัมน์

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| columnIndex | int | ดัชนีเริ่มต้นที่ 0 ของคอลัมน์แรกที่ต้องการตั้งค่าการจัดแนว |
| columnsCount | long | จำนวนคอลัมน์ที่กำหนดการจัดแนว |
| val | int | ค่าใหม่ของการจัดแนวแนวนอนของคอลัมน์ที่ระบุ |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public final void insertRowBefore(int rowIndex)
```


แทรกแถวใหม่ก่อนแถวที่ระบุ ทั้งหมดในแถวใหม่จะเป็น null

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| rowIndex | int | ดัชนีของแถวก่อนหน้าที่จะทำการแทรกแถวใหม่ |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public final void insertRowAfter(int rowIndex)
```


แทรกแถวใหม่หลังแถวที่ระบุ ทั้งหมดในแถวใหม่จะเป็น null

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| rowIndex | int | ดัชนีของแถวหลังจากนั้นจะทำการแทรกแถวใหม่ |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public final void deleteRow(int rowIndex)
```


ลบแถวที่ระบุ

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| rowIndex | int | ดัชนีเริ่มต้นที่ 0 ของแถวที่ต้องการลบ |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public final void insertColumnBefore(int columnIndex)
```


แทรกคอลัมน์ใหม่ก่อนคอลัมน์ที่ระบุ ทั้งหมดในคอลัมน์ใหม่จะเป็น null

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| columnIndex | int | ดัชนีของคอลัมน์ก่อนหน้าที่จะทำการแทรกคอลัมน์ใหม่ |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public final void insertColumnAfter(int columnIndex)
```


แทรกคอลัมน์ใหม่หลังคอลัมน์ที่ระบุ ทั้งหมดในคอลัมน์ใหม่จะเป็น null

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| columnIndex | int | ดัชนีของคอลัมน์หลังจากนั้นจะทำการแทรกคอลัมน์ใหม่ |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public final void deleteColumn(int columnIndex)
```


ลบคอลัมน์ที่ระบุ

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| columnIndex | int | ดัชนีเริ่มต้นที่ 0 ของคอลัมน์ที่ต้องการลบ |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


รับองค์ประกอบลูก

**ผลลัพธ์:**
com.aspose.slides.IMathElement[]