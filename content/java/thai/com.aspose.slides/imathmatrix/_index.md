---
title: IMathMatrix
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: ระบุอ็อบเจ็กต์ Matrix ที่ประกอบด้วยองค์ประกอบย่อยที่จัดวางเป็นหนึ่งหรือหลายแถวและคอลัมน์.
type: docs
url: /th/com.aspose.slides/imathmatrix/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathMatrix extends IMathElement
```

ระบุอ็อบเจ็กต์ Matrix ซึ่งประกอบด้วยองค์ประกอบย่อยที่จัดวางเป็นหนึ่งหรือหลายแถวและคอลัมน์ ต้องระบุว่าเมทริกซ์ไม่มีตัวคั่นในตัว เพื่อวางเมทริกซ์ในวงเล็บ ควรใช้วัตถุตัวคั่น (IMathDelimiter) สามารถใช้ค่า null เพื่อสร้างช่องว่างในเมทริกซ์ได้

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
```
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int row, int column)](#get-Item-int-int-) | องค์ประกอบของเมทริกซ์ |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | องค์ประกอบของเมทริกซ์ |
| [getRowCount()](#getRowCount--) | จำนวนแถวในเมทริกซ์ |
| [getColumnCount()](#getColumnCount--) | จำนวนคอลัมน์ในเมทริกซ์ |
| [getHidePlaceholders()](#getHidePlaceholders--) | ซ่อนตัวยึดสำหรับองค์ประกอบเมทริกซ์ที่ว่าง ค่าเริ่มต้น: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | ซ่อนตัวยึดสำหรับองค์ประกอบเมทริกซ์ที่ว่าง ค่าเริ่มต้น: false |
| [getBaseJustification()](#getBaseJustification--) | ระบุการจัดแนวแนวตั้งสัมพันธ์กับข้อความโดยรอบ |
| [setBaseJustification(int value)](#setBaseJustification-int-) | ระบุการจัดแนวแนวตั้งสัมพันธ์กับข้อความโดยรอบ |
| [getMinColumnWidth()](#getMinColumnWidth--) | ความกว้างคอลัมน์ขั้นต่ำเป็น twips (1/20 ของจุด) ช่องว่าง (เรียกอีกอย่างว่า \\u201cColumn Gap\\u201d หรือ \\u201cGap Width\\u201d) จะถูกเพิ่มไปยัง MinColumnWidth เพื่อกำหนดระยะห่างคอลัมน์เมทริกซ์ทั้งหมด (ระยะห่างระหว่างขอบเดียวกันของคอลัมน์ต่าง ๆ) |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | ความกว้างคอลัมน์ขั้นต่ำเป็น twips (1/20 ของจุด) ช่องว่าง (เรียกอีกอย่างว่า \\u201cColumn Gap\\u201d หรือ \\u201cGap Width\\u201d) จะถูกเพิ่มไปยัง MinColumnWidth เพื่อกำหนดระยะห่างคอลัมน์เมทริกซ์ทั้งหมด (ระยะห่างระหว่างขอบเดียวกันของคอลัมน์ต่าง ๆ) |
| [getColumnGapRule()](#getColumnGapRule--) | ประเภทของการเว้นระยะแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หน่วยการเว้นระยะแนวนอนอาจเป็น ems หรือ points (เก็บเป็น twips) |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | ประเภทของการเว้นระยะแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หน่วยการเว้นระยะแนวนอนอาจเป็น ems หรือ points (เก็บเป็น twips) |
| [getColumnGap()](#getColumnGap--) | ค่าโดยค่าการเว้นระยะแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หาก ColumnGapRule ตั้งเป็น 3 (\"Exactly\"), หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก ColumnGapRule ตั้งเป็น 4 (\"Multiple\"), หน่วยจะถูกตีความเป็นจำนวนของการเพิ่ม 0.5 em |
| [setColumnGap(long value)](#setColumnGap-long-) | ค่าโดยค่าการเว้นระยะแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หาก ColumnGapRule ตั้งเป็น 3 (\"Exactly\"), หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก ColumnGapRule ตั้งเป็น 4 (\"Multiple\"), หน่วยจะถูกตีความเป็นจำนวนของการเพิ่ม 0.5 em |
| [getRowGapRule()](#getRowGapRule--) | ประเภทของการเว้นระยะแนวตั้งระหว่างแถวของเมทริกซ์; หน่วยการเว้นระยะแนวตั้งอาจเป็น lines หรือ points (เก็บเป็น twips) |
| [setRowGapRule(int value)](#setRowGapRule-int-) | ประเภทของการเว้นระยะแนวตั้งระหว่างแถวของเมทริกซ์; หน่วยการเว้นระยะแนวตั้งอาจเป็น lines หรือ points (เก็บเป็น twips) |
| [getRowGap()](#getRowGap--) | ค่าโดยค่าการเว้นระยะแนวตั้งระหว่างแถวของเมทริกซ์; หาก RowGapRule ตั้งเป็น 3 (\"Exactly\"), หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก RowGapRule ตั้งเป็น 4 (\"Multiple\"), หน่วยจะถูกตีความเป็น half-lines |
| [setRowGap(long value)](#setRowGap-long-) | ค่าโดยค่าการเว้นระยะแนวตั้งระหว่างแถวของเมทริกซ์; หาก RowGapRule ตั้งเป็น 3 (\"Exactly\"), หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก RowGapRule ตั้งเป็น 4 (\"Multiple\"), หน่วยจะถูกตีความเป็น half-lines |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | รับการจัดแนวนอนของคอลัมน์ที่ระบุ |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | ตั้งค่าการจัดแนวนอนของคอลัมน์ที่ระบุ |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | ตั้งค่าการจัดแนวนอนของคอลัมน์ที่ระบุ |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | แทรกแถวใหม่ก่อนแถวที่ระบุ เริ่มแรกอิลีเมนต์ทั้งหมดในแถวใหม่เป็น null |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | แทรกแถวใหม่หลังจากแถวที่ระบุ เริ่มแรกอิลีเมนต์ทั้งหมดในแถวใหม่เป็น null |
| [deleteRow(int rowIndex)](#deleteRow-int-) | ลบแถวที่ระบุ |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | แทรกคอลัมน์ใหม่ก่อนคอลัมน์ที่ระบุ เริ่มแรกอิลีเมนต์ทั้งหมดในคอลัมน์ใหม่เป็น null |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | แทรกคอลัมน์ใหม่หลังจากคอลัมน์ที่ระบุ เริ่มแรกอิลีเมนต์ทั้งหมดในคอลัมน์ใหม่เป็น null |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | ลบคอลัมน์ที่ระบุ |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public abstract IMathElement get_Item(int row, int column)
```

องค์ประกอบของเมทริกซ์

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| row | int | ดัชนีฐานศูนย์ของแถวที่ต้องการรับรายการ |
| column | int | ดัชนีฐานศูนย์ของคอลัมน์ที่ต้องการรับรายการ |

**ผลลัพธ์:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement

### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public abstract void set_Item(int row, int column, IMathElement value)
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
| row | int | ดัชนีฐานศูนย์ของแถวที่ต้องการตั้งค่า |
| column | int | ดัชนีฐานศูนย์ของคอลัมน์ที่ต้องการตั้งค่า |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getRowCount() {#getRowCount--}
```
public abstract int getRowCount()
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
public abstract int getColumnCount()
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
public abstract boolean getHidePlaceholders()
```

ซ่อนตัวยึดสำหรับองค์ประกอบเมทริกซ์ที่ว่าง ค่าเริ่มต้น: false

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
public abstract void setHidePlaceholders(boolean value)
```

ซ่อนตัวยึดสำหรับองค์ประกอบเมทริกซ์ที่ว่าง ค่าเริ่มต้น: false

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
public abstract int getBaseJustification()
```

ระบุการจัดแนวแนวตั้งสัมพันธ์กับข้อความโดยรอบ ค่าที่เป็นไปได้คือ top, bottom, และ center ค่าเริ่มต้น: Center

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**ผลลัพธ์:**
int

### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

ระบุการจัดแนวแนวตั้งสัมพันธ์กับข้อความโดยรอบ ค่าที่เป็นไปได้คือ top, bottom, และ center ค่าเริ่มต้น: Center

--------------------

> ```
> ตัวอย่าง:
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
public abstract long getMinColumnWidth()
```

ความกว้างคอลัมน์ขั้นต่ำเป็น twips (1/20 ของจุด) ช่องว่าง (เรียกอีกอย่างว่า \\u201cColumn Gap\\u201d หรือ \\u201cGap Width\\u201d) จะถูกเพิ่มไปยัง MinColumnWidth เพื่อกำหนดระยะห่างคอลัมน์เมทริกซ์ทั้งหมด (ระยะห่างระหว่างขอบเดียวกันของคอลัมน์ต่าง ๆ) ค่าเริ่มต้น: 0.

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**ผลลัพธ์:**
long

### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public abstract void setMinColumnWidth(long value)
```

ความกว้างคอลัมน์ขั้นต่ำเป็น twips (1/20 ของจุด) ช่องว่าง (เรียกอีกอย่างว่า \\u201cColumn Gap\\u201d หรือ \\u201cGap Width\\u201d) จะถูกเพิ่มไปยัง MinColumnWidth เพื่อกำหนดระยะห่างคอลัมน์เมทริกซ์ทั้งหมด (ระยะห่างระหว่างขอบเดียวกันของคอลัมน์ต่าง ๆ) ค่าเริ่มต้น: 0.

--------------------

> ```
> ตัวอย่าง:
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
public abstract int getColumnGapRule()
```

ประเภทของการเว้นระยะแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หน่วยการเว้นระยะแนวนอนอาจเป็น ems หรือ points (เก็บเป็น twips) ค่าเริ่มต้น: SingleSpacingGap (0)

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
public abstract void setColumnGapRule(int value)
```

ประเภทของการเว้นระยะแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หน่วยการเว้นระยะแนวนอนอาจเป็น ems หรือ points (เก็บเป็น twips) ค่าเริ่มต้น: SingleSpacingGap (0)

--------------------

> ```
> ตัวอย่าง:
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
public abstract long getColumnGap()
```

ค่าโดยค่าการเว้นระยะแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หาก ColumnGapRule ตั้งเป็น 3 (\"Exactly\"), หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก ColumnGapRule ตั้งเป็น 4 (\"Multiple\"), หน่วยจะถูกตีความเป็นจำนวนของการเพิ่ม 0.5 em ในกรณีอื่นจะถูกละเว้น ค่าเริ่มต้น: 0

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**ผลลัพธ์:**
long

### setColumnGap(long value) {#setColumnGap-long-}
```
public abstract void setColumnGap(long value)
```

ค่าโดยค่าการเว้นระยะแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หาก ColumnGapRule ตั้งเป็น 3 (\"Exactly\"), หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก ColumnGapRule ตั้งเป็น 4 (\"Multiple\"), หน่วยจะถูกตีความเป็นจำนวนของการเพิ่ม 0.5 em ในกรณีอื่นจะถูกละเว้น ค่าเริ่มต้น: 0

--------------------

> ```
> ตัวอย่าง:
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
public abstract int getRowGapRule()
```

ประเภทของการเว้นระยะแนวตั้งระหว่างแถวของเมทริกซ์; หน่วยการเว้นระยะแนวตั้งอาจเป็น lines หรือ points (เก็บเป็น twips) ค่าเริ่มต้น: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
```

**ผลลัพธ์:**
int

### setRowGapRule(int value) {#setRowGapRule-int-}
```
public abstract void setRowGapRule(int value)
```

ประเภทของการเว้นระยะแนวตั้งระหว่างแถวของเมทริกซ์; หน่วยการเว้นระยะแนวตั้งอาจเป็น lines หรือ points (เก็บเป็น twips) ค่าเริ่มต้น: SingleSpacingGap (0)

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
public abstract long getRowGap()
```

ค่าโดยค่าการเว้นระยะแนวตั้งระหว่างแถวของเมทริกซ์; หาก RowGapRule ตั้งเป็น 3 (\"Exactly\"), หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก RowGapRule ตั้งเป็น 4 (\"Multiple\"), หน่วยจะถูกตีความเป็น half-lines ค่าเริ่มต้น: 0

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**ผลลัพธ์:**
long

### setRowGap(long value) {#setRowGap-long-}
```
public abstract void setRowGap(long value)
```

ค่าโดยค่าการเว้นระยะแนวตั้งระหว่างแถวของเมทริกซ์; หาก RowGapRule ตั้งเป็น 3 (\"Exactly\"), หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก RowGapRule ตั้งเป็น 4 (\"Multiple\"), หน่วยจะถูกตีความเป็น half-lines ค่าเริ่มต้น: 0

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | long |  |

### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public abstract int getColumnAlignment(int columnIndex)
```

รับการจัดแนวนอนของคอลัมน์ที่ระบุ

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| columnIndex | int | ดัชนีคอลัมน์ฐานศูนย์ |

**ผลลัพธ์:**
int - การจัดแนวนอนของคอลัมน์ที่ระบุ

### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public abstract void setColumnAlignment(int columnIndex, int val)
```

ตั้งค่าการจัดแนวนอนของคอลัมน์ที่ระบุ

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| columnIndex | int | ดัชนีคอลัมน์ฐานศูนย์ |
| val | int | ค่าใหม่ของการจัดแนวนอนของคอลัมน์ที่ระบุ |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public abstract void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

ตั้งค่าการจัดแนวนอนของคอลัมน์ที่ระบุ

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| columnIndex | int | ดัชนีฐานศูนย์ของคอลัมน์แรกที่ต้องการตั้งค่า |
| columnsCount | long | จำนวนคอลัมน์ที่ต้องการระบุการจัดแนว |
| val | int | ค่าใหม่ของการจัดแนวนอนของคอลัมน์ที่ระบุ |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public abstract void insertRowBefore(int rowIndex)
```

แทรกแถวใหม่ก่อนแถวที่ระบุ เริ่มแรกอิลีเมนต์ทั้งหมดในแถวใหม่เป็น null

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| rowIndex | int | ดัชนีของแถวที่ต้องการแทรกแถวใหม่ก่อนหน้า |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public abstract void insertRowAfter(int rowIndex)
```

แทรกแถวใหม่หลังจากแถวที่ระบุ เริ่มแรกอิลีเมนต์ทั้งหมดในแถวใหม่เป็น null

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| rowIndex | int | ดัชนีของแถวที่ต้องการแทรกแถวใหม่หลังจากนั้น |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public abstract void deleteRow(int rowIndex)
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
| rowIndex | int | ดัชนีฐานศูนย์ของแถวที่ต้องการลบ |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public abstract void insertColumnBefore(int columnIndex)
```

แทรกคอลัมน์ใหม่ก่อนคอลัมน์ที่ระบุ เริ่มแรกอิลีเมนต์ทั้งหมดในคอลัมน์ใหม่เป็น null

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
| columnIndex | int | ดัชนีของคอลัมน์ก่อนที่จะใส่คอลัมน์ใหม่ |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public abstract void insertColumnAfter(int columnIndex)
```

แทรกคอลัมน์ใหม่หลังจากคอลัมน์ที่ระบุ เริ่มแรกอิลีเมนต์ทั้งหมดในคอลัมน์ใหม่เป็น null

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| columnIndex | int | ดัชนีของคอลัมน์หลังจากนั้นจะใส่คอลัมน์ใหม่ |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public abstract void deleteColumn(int columnIndex)
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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| columnIndex | int | ดัชนีฐานศูนย์ของคอลัมน์ที่ต้องการลบ |