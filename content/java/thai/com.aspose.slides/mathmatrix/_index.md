---
title: MathMatrix
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: ระบุอ็อบเจ็กต์ Matrix ซึ่งประกอบด้วยองค์ประกอบย่อยจัดเรียงเป็นหนึ่งหรือหลายแถวและคอลัมน์.
type: docs
url: /th/com.aspose.slides/mathmatrix/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**  
[com.aspose.slides.IMathMatrix](../../com.aspose.slides/imathmatrix), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathMatrix extends MathElementBase implements IMathMatrix, IHasControlCharacterProperties
```

ระบุออบเจ็กต์ Matrix ที่ประกอบด้วยองค์ประกอบย่อยจัดเรียงเป็นหนึ่งหรือหลายแถวและคอลัมน์ จำเป็นต้องทราบว่าเมทริกซ์ไม่มีเครื่องหมายกำหนดขอบในตัว เพื่อวางเมทริกซ์ในวงเล็บคุณควรใช้วัตถุ delimiter (IMathDelimiter) สามารถใช้ค่า null เพื่อสร้างช่องว่างในเมทริกซ์ได้

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## ตัวสร้าง

| Constructor | Description |
| --- | --- |
| [MathMatrix(int rowCount, int columnCount)](#MathMatrix-int-int-) | สร้างอินสแตนซ์ใหม่ของคลาส MathMatrix |

## เมธอด

| Method | Description |
| --- | --- |
| [getRowCount()](#getRowCount--) | จำนวนแถวในเมทริกซ์ |
| [getColumnCount()](#getColumnCount--) | จำนวนคอลัมน์ในเมทริกซ์ |
| [getHidePlaceholders()](#getHidePlaceholders--) | ซ่อนตำแหน่งที่เก็บค่า placeholder สำหรับองค์ประกอบเมทริกซ์ที่ว่าง ค่าเริ่มต้น: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | ซ่อนตำแหน่งที่เก็บค่า placeholder สำหรับองค์ประกอบเมทริกซ์ที่ว่าง ค่าเริ่มต้น: false |
| [getBaseJustification()](#getBaseJustification--) | กำหนดการจัดแนวแนวตั้งสัมพันธ์กับข้อความรอบข้าง |
| [setBaseJustification(int value)](#setBaseJustification-int-) | กำหนดการจัดแนวแนวตั้งสัมพันธ์กับข้อความรอบข้าง |
| [getMinColumnWidth()](#getMinColumnWidth--) | ความกว้างคอลัมน์ขั้นต่ำในหน่วย twips (1/20 ของจุด) ระยะห่างช่องว่าง (เรียกอีกอย่างว่า \\u201cColumn Gap\\u201d หรือ \\u201cGap Width\\u201d) จะถูกเพิ่มเข้าไปใน MinColumnWidth เพื่อกำหนดช่องว่างคอลัมน์เมทริกซ์ทั้งหมด (ระยะทางระหว่างขอบเดียวกันของคอลัมน์ต่าง ๆ) |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | ความกว้างคอลัมน์ขั้นต่ำในหน่วย twips (1/20 ของจุด) ระยะห่างช่องว่าง (เรียกอีกอย่างว่า \\u201cColumn Gap\\u201d หรือ \\u201cGap Width\\u201d) จะถูกเพิ่มเข้าไปใน MinColumnWidth เพื่อกำหนดช่องว่างคอลัมน์เมทริกซ์ทั้งหมด (ระยะทางระหว่างขอบเดียวกันของคอลัมน์ต่าง ๆ) |
| [getColumnGapRule()](#getColumnGapRule--) | ประเภทของระยะห่างแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หน่วยระยะห่างแนวนอนสามารถเป็น em หรือ points (เก็บเป็น twips) |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | ประเภทของระยะห่างแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หน่วยระยะห่างแนวนอนสามารถเป็น em หรือ points (เก็บเป็น twips) |
| [getColumnGap()](#getColumnGap--) | ค่าของระยะห่างแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หาก ColumnGapRule ตั้งค่าเป็น 3 (\"Exactly\") หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก ColumnGapRule ตั้งค่าเป็น 4 (\"Multiple\") หน่วยจะตีความเป็นจำนวนของการเพิ่ม 0.5 em |
| [setColumnGap(long value)](#setColumnGap-long-) | ค่าของระยะห่างแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หาก ColumnGapRule ตั้งค่าเป็น 3 (\"Exactly\") หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก ColumnGapRule ตั้งค่าเป็น 4 (\"Multiple\") หน่วยจะตีความเป็นจำนวนของการเพิ่ม 0.5 em |
| [getRowGapRule()](#getRowGapRule--) | ประเภทของระยะห่างแนวตั้งระหว่างแถวของเมทริกซ์; หน่วยระยะห่างแนวตั้งสามารถเป็นบรรทัดหรือ points (เก็บเป็น twips) |
| [setRowGapRule(int value)](#setRowGapRule-int-) | ประเภทของระยะห่างแนวตั้งระหว่างแถวของเมทริกซ์; หน่วยระยะห่างแนวตั้งสามารถเป็นบรรทัดหรือ points (เก็บเป็น twips) |
| [getRowGap()](#getRowGap--) | ค่าของระยะห่างแนวตั้งระหว่างแถวของเมทริกซ์; หาก RowGapRule ตั้งค่าเป็น 3 (\"Exactly\") หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก RowGapRule ตั้งค่าเป็น 4 (\"Multiple\") หน่วยจะตีความเป็นครึ่งบรรทัด |
| [setRowGap(long value)](#setRowGap-long-) | ค่าของระยะห่างแนวตั้งระหว่างแถวของเมทริกซ์; หาก RowGapRule ตั้งค่าเป็น 3 (\"Exactly\") หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก RowGapRule ตั้งค่าเป็น 4 (\"Multiple\") หน่วยจะตีความเป็นครึ่งบรรทัด |
| [get_Item(int row, int column)](#get-Item-int-int-) | องค์ประกอบของเมทริกซ์ |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | องค์ประกอบของเมทริกซ์ |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | คุณสมบัติตัวอักษรควบคุม |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | รับการจัดแนวแนวนอนของคอลัมน์ที่ระบุ |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | ตั้งค่าการจัดแนวแนวนอนของคอลัมน์ที่ระบุ |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | ตั้งค่าการจัดแนวแนวนอนของคอลัมน์ที่ระบุหลายคอลัมน์ |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | แทรกแถวใหม่ก่อนแถวที่ระบุ โดยเริ่มต้นทุกองค์ประกอบในแถวใหม่เป็น null |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | แทรกแถวใหม่หลังแถวที่ระบุ โดยเริ่มต้นทุกองค์ประกอบในแถวใหม่เป็น null |
| [deleteRow(int rowIndex)](#deleteRow-int-) | ลบแถวที่ระบุ |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | แทรกคอลัมน์ใหม่ก่อนคอลัมน์ที่ระบุ โดยเริ่มต้นทุกองค์ประกอบในคอลัมน์ใหม่เป็น null |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | แทรกคอลัมน์ใหม่หลังคอลัมน์ที่ระบุ โดยเริ่มต้นทุกองค์ประกอบในคอลัมน์ใหม่เป็น null |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | ลบคอลัมน์ที่ระบุ |
| [getChildren()](#getChildren--) | ดึงองค์ประกอบลูก |

### MathMatrix(int rowCount, int columnCount) {#MathMatrix-int-int-}
```
public MathMatrix(int rowCount, int columnCount)
```

สร้างอินสแตนซ์ใหม่ของคลาส MathMatrix

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
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

**คืนค่า:**
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

**คืนค่า:**
int
### getHidePlaceholders() {#getHidePlaceholders--}
```
public final boolean getHidePlaceholders()
```

ซ่อนตำแหน่งที่เก็บค่า placeholder สำหรับองค์ประกอบเมทริกซ์ที่ว่าง ค่าเริ่มต้น: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**คืนค่า:**
boolean
### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public final void setHidePlaceholders(boolean value)
```

ซ่อนตำแหน่งที่เก็บค่า placeholder สำหรับองค์ประกอบเมทริกซ์ที่ว่าง ค่าเริ่มต้น: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```

กำหนดการจัดแนวแนวตั้งสัมพันธ์กับข้อความรอบข้าง ค่าที่เป็นไปได้คือ top, bottom, และ center ค่าเริ่มต้น: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**คืนค่า:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```

กำหนดการจัดแนวแนวตั้งสัมพันธ์กับข้อความรอบข้าง ค่าที่เป็นไปได้คือ top, bottom, และ center ค่าเริ่มต้น: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMinColumnWidth() {#getMinColumnWidth--}
```
public final long getMinColumnWidth()
```

ความกว้างคอลัมน์ขั้นต่ำในหน่วย twips (1/20 ของจุด) ระยะห่างช่องว่าง (เรียกอีกอย่างว่า \\u201cColumn Gap\\u201d หรือ \\u201cGap Width\\u201d) จะถูกเพิ่มเข้าไปใน MinColumnWidth เพื่อกำหนดช่องว่างคอลัมน์เมทริกซ์ทั้งหมด (ระยะทางระหว่างขอบเดียวกันของคอลัมน์ต่าง ๆ) ค่าเริ่มต้น: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**คืนค่า:**
long
### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public final void setMinColumnWidth(long value)
```

ความกว้างคอลัมน์ขั้นต่ำในหน่วย twips (1/20 ของจุด) ระยะห่างช่องว่าง (เรียกอีกอย่างว่า \\u201cColumn Gap\\u201d หรือ \\u201cGap Width\\u201d) จะถูกเพิ่มเข้าไปใน MinColumnWidth เพื่อกำหนดช่องว่างคอลัมน์เมทริกซ์ทั้งหมด (ระยะทางระหว่างขอบเดียวกันของคอลัมน์ต่าง ๆ) ค่าเริ่มต้น: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getColumnGapRule() {#getColumnGapRule--}
```
public final int getColumnGapRule()
```

ประเภทของระยะห่างแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หน่วยระยะห่างแนวนอนสามารถเป็น em หรือ points (เก็บเป็น twips) ค่าเริ่มต้น: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**คืนค่า:**
int
### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public final void setColumnGapRule(int value)
```

ประเภทของระยะห่างแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หน่วยระยะห่างแนวนอนสามารถเป็น em หรือ points (เก็บเป็น twips) ค่าเริ่มต้น: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getColumnGap() {#getColumnGap--}
```
public final long getColumnGap()
```

ค่าของระยะห่างแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หาก ColumnGapRule ตั้งค่าเป็น 3 (\"Exactly\") หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก ColumnGapRule ตั้งค่าเป็น 4 (\"Multiple\") หน่วยจะตีความเป็นจำนวนของการเพิ่ม 0.5 em In other cases ignored. ค่าเริ่มต้น: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**คืนค่า:**
long
### setColumnGap(long value) {#setColumnGap-long-}
```
public final void setColumnGap(long value)
```

ค่าของระยะห่างแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หาก ColumnGapRule ตั้งค่าเป็น 3 (\"Exactly\") หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก ColumnGapRule ตั้งค่าเป็น 4 (\"Multiple\") หน่วยจะตีความเป็นจำนวนของการเพิ่ม 0.5 em In other cases ignored. ค่าเริ่มต้น: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getRowGapRule() {#getRowGapRule--}
```
public final int getRowGapRule()
```

ประเภทของระยะห่างแนวตั้งระหว่างแถวของเมทริกซ์; หน่วยระยะห่างแนวตั้งสามารถเป็นบรรทัดหรือ points (เก็บเป็น twips) ค่าเริ่มต้น: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**คืนค่า:**
int
### setRowGapRule(int value) {#setRowGapRule-int-}
```
public final void setRowGapRule(int value)
```

ประเภทของระยะห่างแนวตั้งระหว่างแถวของเมทริกซ์; หน่วยระยะห่างแนวตั้งสามารถเป็นบรรทัดหรือ points (เก็บเป็น twips) ค่าเริ่มต้น: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRowGap() {#getRowGap--}
```
public final long getRowGap()
```

ค่าของระยะห่างแนวตั้งระหว่างแถวของเมทริกซ์; หาก RowGapRule ตั้งค่าเป็น 3 (\"Exactly\") หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก RowGapRule ตั้งค่าเป็น 4 (\"Multiple\") หน่วยจะตีความเป็นครึ่งบรรทัด ค่าเริ่มต้น: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**คืนค่า:**
long
### setRowGap(long value) {#setRowGap-long-}
```
public final void setRowGap(long value)
```

ค่าของระยะห่างแนวตั้งระหว่างแถวของเมทริกซ์; หาก RowGapRule ตั้งค่าเป็น 3 (\"Exactly\") หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก RowGapRule ตั้งค่าเป็น 4 (\"Multiple\") หน่วยจะตีความเป็นครึ่งบรรทัด ค่าเริ่มต้น: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| row | int | ดัชนีฐานศูนย์ของแถวที่ต้องการดึงค่า |
| column | int | ดัชนีฐานศูนย์ของคอลัมน์ที่ต้องการดึงค่า |

**คืนค่า:**
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
| Parameter | Type | Description |
| --- | --- | --- |
| row | int | ดัชนีฐานศูนย์ของแถวที่ต้องการดึงค่า |
| column | int | ดัชนีฐานศูนย์ของคอลัมน์ที่ต้องการดึงค่า |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

คุณสมบัติตัวอักษรควบคุม

**คืนค่า:**
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
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | ดัชนีคอลัมน์ฐานศูนย์ |

**คืนค่า:**
int - การจัดแนวแนวนอนของคอลัมน์ที่ระบุ
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public final void setColumnAlignment(int columnIndex, int val)
```

ตั้งค่าการจัดแนวแนวนอนของคอลัมน์ที่ระบุ

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | ดัชนีคอลัมน์ฐานศูนย์ |
| val | int | ค่าการจัดแนวแนวนอนใหม่ของคอลัมน์ที่ระบุ |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public final void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

ตั้งค่าการจัดแนวแนวนอนของคอลัมน์ที่ระบุหลายคอลัมน์

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | ดัชนีฐานศูนย์ของคอลัมน์แรกที่ต้องการตั้งค่า |
| columnsCount | long | จำนวนคอลัมน์ที่ต้องการกำหนดการจัดแนว |
| val | int | ค่าการจัดแนวแนวนอนใหม่ของคอลัมน์ที่ระบุ |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public final void insertRowBefore(int rowIndex)
```

แทรกแถวใหม่ก่อนแถวที่ระบุ โดยเริ่มต้นทุกองค์ประกอบในแถวใหม่เป็น null

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| rowIndex | int | ดัชนีของแถวที่ต้องการแทรกแถวใหม่ก่อนหน้า |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public final void insertRowAfter(int rowIndex)
```

แทรกแถวใหม่หลังแถวที่ระบุ โดยเริ่มต้นทุกองค์ประกอบในแถวใหม่เป็น null

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| rowIndex | int | ดัชนีของแถวที่ต้องการแทรกแถวใหม่หลังจากนั้น |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public final void deleteRow(int rowIndex)
```

ลบแถวที่ระบุ

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| rowIndex | int | ดัชนีฐานศูนย์ของแถวที่ต้องการลบ |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public final void insertColumnBefore(int columnIndex)
```

แทรกคอลัมน์ใหม่ก่อนคอลัมน์ที่ระบุ โดยเริ่มต้นทุกองค์ประกอบในคอลัมน์ใหม่เป็น null

--------------------

> ```
> Example:
>  
  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | ดัชนีของคอลัมน์ที่ต้องการแทรกคอลัมน์ใหม่ก่อนหน้า |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public final void insertColumnAfter(int columnIndex)
```

แทรกคอลัมน์ใหม่หลังคอลัมน์ที่ระบุ โดยเริ่มต้นทุกองค์ประกอบในคอลัมน์ใหม่เป็น null

--------------------

> ```
> Example:
>  
  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | ดัชนีของคอลัมน์ที่ต้องการแทรกคอลัมน์ใหม่หลังจากนั้น |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public final void deleteColumn(int columnIndex)
```

ลบคอลัมน์ที่ระบุ

--------------------

> ```
> ตัวอย่าง:
>  
  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | ดัชนีฐานศูนย์ของคอลัมน์ที่ต้องการลบ |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

ดึงองค์ประกอบลูก

**คืนค่า:**
com.aspose.slides.IMathElement[]