---
title: IMathMatrix
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: ระบุอ็อบเจ็กต์ Matrix ซึ่งประกอบด้วยส่วนย่อยที่จัดวางเป็นหนึ่งหรือหลายแถวและคอลัมน์.
type: docs
url: /th/com.aspose.slides/imathmatrix/
---
**อินเทอร์เฟซที่ทำงานทั้งหมด:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathMatrix extends IMathElement
```

ระบุอ็อบเจ็กต์ Matrix ซึ่งประกอบด้วยส่วนย่อยที่จัดวางเป็นหนึ่งหรือหลายแถวและคอลัมน์ ต้องระวังว่าตารางเมทริกซ์ไม่มีตัวแบ่งที่ฝังมา เพื่อใส่เมทริกซ์ในวงเล็บควรใช้วัตถุตัวแบ่ง (IMathDelimiter) สามารถใช้ค่า null เพื่อสร้างช่องว่างในเมทริกซ์ได้.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int row, int column)](#get-Item-int-int-) | ส่วนประกอบของเมทริกซ์ |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | ส่วนประกอบของเมทริกซ์ |
| [getRowCount()](#getRowCount--) | จำนวนแถวในเมทริกซ์ |
| [getColumnCount()](#getColumnCount--) | จำนวนคอลัมน์ในเมทริกซ์ |
| [getHidePlaceholders()](#getHidePlaceholders--) | ซ่อนตัวตำแหน่งสำหรับส่วนประกอบเมทริกซ์ที่ว่าง Default: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | ซ่อนตัวตำแหน่งสำหรับส่วนประกอบเมทริกซ์ที่ว่าง Default: false |
| [getBaseJustification()](#getBaseJustification--) | ระบุการจัดแนวแนวตั้งสัมพันธ์กับข้อความโดยรอบ. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | ระบุการจัดแนวแนวตั้งสัมพันธ์กับข้อความโดยรอบ. |
| [getMinColumnWidth()](#getMinColumnWidth--) | ความกว้างคอลัมน์ต่ำสุดในหน่วย twips (1/20 ของจุด) การเว้นระยะช่องว่าง (ซึ่งเรียกอีกอย่างว่า \u201cColumn Gap\u201d หรือ \u201cGap Width\u201d) จะถูกเพิ่มไปยัง MinColumnWidth เพื่อกำหนดระยะห่างคอลัมน์เมทริกซ์ทั้งหมด (ระยะระหว่างขอบเดียวกันของคอลัมน์ที่ต่างกัน). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | ความกว้างคอลัมน์ต่ำสุดในหน่วย twips (1/20 ของจุด) การเว้นระยะช่องว่าง (ซึ่งเรียกอีกอย่างว่า \u201cColumn Gap\u201d หรือ \u201cGap Width\u201d) จะถูกเพิ่มไปยัง MinColumnWidth เพื่อกำหนดระยะห่างคอลัมน์เมทริกซ์ทั้งหมด (ระยะระหว่างขอบเดียวกันของคอลัมน์ที่ต่างกัน). |
| [getColumnGapRule()](#getColumnGapRule--) | ประเภทของช่องว่างแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หน่วยช่องว่างแนวนอนสามารถเป็น ems หรือ points (เก็บเป็น twips). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | ประเภทของช่องว่างแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หน่วยช่องว่างแนวนอนสามารถเป็น ems หรือ points (เก็บเป็น twips). |
| [getColumnGap()](#getColumnGap--) | ค่าของช่องว่างแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หาก ColumnGapRule ถูกตั้งเป็น 3 (\"Exactly\"), หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก ColumnGapRule ถูกตั้งเป็น 4 (\"Multiple\"), หน่วยจะถูกตีความเป็นจำนวนของการเพิ่ม 0.5 em. |
| [setColumnGap(long value)](#setColumnGap-long-) | ค่าของช่องว่างแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หาก ColumnGapRule ถูกตั้งเป็น 3 (\"Exactly\"), หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก ColumnGapRule ถูกตั้งเป็น 4 (\"Multiple\"), หน่วยจะถูกตีความเป็นจำนวนของการเพิ่ม 0.5 em. |
| [getRowGapRule()](#getRowGapRule--) | ประเภทของช่องว่างแนวตั้งระหว่างแถวของเมทริกซ์; หน่วยช่องว่างแนวตั้งสามารถเป็น lines หรือ points (เก็บเป็น twips). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | ประเภทของช่องว่างแนวตั้งระหว่างแถวของเมทริกซ์; หน่วยช่องว่างแนวตั้งสามารถเป็น lines หรือ points (เก็บเป็น twips). |
| [getRowGap()](#getRowGap--) | ค่าของช่องว่างแนวตั้งระหว่างแถวของเมทริกซ์; หาก RowGapRule ถูกตั้งเป็น 3 (\"Exactly\"), หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก RowGapRule ถูกตั้งเป็น 4 (\"Multiple\"), หน่วยจะถูกตีความเป็น half-lines. |
| [setRowGap(long value)](#setRowGap-long-) | ค่าของช่องว่างแนวตั้งระหว่างแถวของเมทริกซ์; หาก RowGapRule ถูกตั้งเป็น 3 (\"Exactly\"), หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก RowGapRule ถูกตั้งเป็น 4 (\"Multiple\"), หน่วยจะถูกตีความเป็น half-lines. |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | รับการจัดแนวนอนของคอลัมน์ที่ระบุ |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | ตั้งค่าการจัดแนวนอนของคอลัมน์ที่ระบุ |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | ตั้งค่าการจัดแนวนอนของคอลัมน์ที่ระบุหลายคอลัมน์ |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | แทรกแถวใหม่ก่อนแถวที่ระบุ โดยเริ่มต้นทุกส่วนในแถวใหม่เป็น null. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | แทรกแถวใหม่หลังแถวที่ระบุโดยเริ่มต้นทุกส่วนในแถวใหม่เป็น null. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | ลบแถวที่ระบุ |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | แทรกคอลัมน์ใหม่ก่อนคอลัมน์ที่ระบุ โดยเริ่มต้นทุกส่วนในคอลัมน์ใหม่เป็น null. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | แทรกคอลัมน์ใหม่หลังคอลัมน์ที่ระบุ โดยเริ่มต้นทุกส่วนในคอลัมน์ใหม่เป็น null. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | ลบคอลัมน์ที่ระบุ |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public abstract IMathElement get_Item(int row, int column)
```

ส่วนประกอบของเมทริกซ์

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| row | int | ดัชนีเริ่มจาก 0 ของแถวเพื่อรับรายการ |
| column | int | ดัชนีเริ่มจาก 0 ของคอลัมน์เพื่อรับรายการ |

**ค่าที่ส่งกลับ:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public abstract void set_Item(int row, int column, IMathElement value)
```

ส่วนประกอบของเมทริกซ์

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| row | int | ดัชนีเริ่มจาก 0 ของแถวเพื่อรับรายการ |
| column | int | ดัชนีเริ่มจาก 0 ของคอลัมน์เพื่อรับรายการ |
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

**ค่าที่ส่งกลับ:**
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

**ค่าที่ส่งกลับ:**
int
### getHidePlaceholders() {#getHidePlaceholders--}
```
public abstract boolean getHidePlaceholders()
```

ซ่อนตัวตำแหน่งสำหรับส่วนประกอบเมทริกซ์ที่ว่าง Default: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**ค่าที่ส่งกลับ:**
boolean
### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public abstract void setHidePlaceholders(boolean value)
```

ซ่อนตัวตำแหน่งสำหรับส่วนประกอบเมทริกซ์ที่ว่าง Default: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```

ระบุการจัดแนวแนวตั้งสัมพันธ์กับข้อความโดยรอบ. ค่าที่เป็นไปได้คือ top, bottom, และ center. Default: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**ค่าที่ส่งกลับ:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

ระบุการจัดแนวแนวตั้งสัมพันธ์กับข้อความโดยรอบ. ค่าที่เป็นไปได้คือ top, bottom, และ center. Default: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getMinColumnWidth() {#getMinColumnWidth--}
```
public abstract long getMinColumnWidth()
```

ความกว้างคอลัมน์ต่ำสุดในหน่วย twips (1/20 ของจุด) การเว้นระยะช่องว่าง (ซึ่งเรียกอีกอย่างว่า \u201cColumn Gap\u201d หรือ \u201cGap Width\u201d) จะถูกเพิ่มไปยัง MinColumnWidth เพื่อกำหนดระยะห่างคอลัมน์เมทริกซ์ทั้งหมด (ระยะระหว่างขอบเดียวกันของคอลัมน์ที่ต่างกัน). Default: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**ค่าที่ส่งกลับ:**
long
### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public abstract void setMinColumnWidth(long value)
```

ความกว้างคอลัมน์ต่ำสุดในหน่วย twips (1/20 ของจุด) การเว้นระยะช่องว่าง (ซึ่งเรียกอีกอย่างว่า \u201cColumn Gap\u201d หรือ \u201cGap Width\u201d) จะถูกเพิ่มไปยัง MinColumnWidth เพื่อกำหนดระยะห่างคอลัมน์เมทริกซ์ทั้งหมด (ระยะระหว่างขอบเดียวกันของคอลัมน์ที่ต่างกัน). Default: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | long |  |

### getColumnGapRule() {#getColumnGapRule--}
```
public abstract int getColumnGapRule()
```

ประเภทของช่องว่างแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หน่วยช่องว่างแนวนอนสามารถเป็น ems หรือ points (เก็บเป็น twips). Default: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**ค่าที่ส่งกลับ:**
int
### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public abstract void setColumnGapRule(int value)
```

ประเภทของช่องว่างแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หน่วยช่องว่างแนวนอนสามารถเป็น ems หรือ points (เก็บเป็น twips). Default: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getColumnGap() {#getColumnGap--}
```
public abstract long getColumnGap()
```

ค่าของช่องว่างแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หาก ColumnGapRule 被ตั้งเป็น 3 (\"Exactly\"), หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก ColumnGapRule 被ตั้งเป็น 4 (\"Multiple\"), หน่วยจะถูกตีความเป็นจำนวนของการเพิ่ม 0.5 em. ในกรณีอื่นๆ จะถูกละเว้น. Default: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**ค่าที่ส่งกลับ:**
long
### setColumnGap(long value) {#setColumnGap-long-}
```
public abstract void setColumnGap(long value)
```

ค่าของช่องว่างแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หาก ColumnGapRule 被ตั้งเป็น 3 (\"Exactly\"), หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก ColumnGapRule 被ตั้งเป็น 4 (\"Multiple\"), หน่วยจะถูกตีความเป็นจำนวนของการเพิ่ม 0.5 em. ในกรณีอื่นๆ จะถูกละเว้น. Default: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | long |  |

### getRowGapRule() {#getRowGapRule--}
```
public abstract int getRowGapRule()
```

ประเภทของช่องว่างแนวตั้งระหว่างแถวของเมทริกซ์; หน่วยช่องว่างแนวตั้งสามารถเป็น lines หรือ points (เก็บเป็น twips). Default: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**ค่าที่ส่งกลับ:**
int
### setRowGapRule(int value) {#setRowGapRule-int-}
```
public abstract void setRowGapRule(int value)
```

ประเภทของช่องว่างแนวตั้งระหว่างแถวของเมทริกซ์; หน่วยช่องว่างแนวตั้งสามารถเป็น lines หรือ points (เก็บเป็น twips). Default: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getRowGap() {#getRowGap--}
```
public abstract long getRowGap()
```

ค่าของช่องว่างแนวตั้งระหว่างแถวของเมทริกซ์; หาก RowGapRule 被ตั้งเป็น 3 (\"Exactly\"), หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก RowGapRule 被ตั้งเป็น 4 (\"Multiple\"), หน่วยจะถูกตีความเป็น half-lines. Default: 0

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**ค่าที่ส่งกลับ:**
long
### setRowGap(long value) {#setRowGap-long-}
```
public abstract void setRowGap(long value)
```

ค่าของช่องว่างแนวตั้งระหว่างแถวของเมทริกซ์; หาก RowGapRule 被ตั้งเป็น 3 (\"Exactly\"), หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก RowGapRule 被ตั้งเป็น 4 (\"Multiple\"), หน่วยจะถูกตีความเป็น half-lines. Default: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| columnIndex | int | ดัชนีคอลัมน์เริ่มจาก 0 |

**ค่าที่ส่งกลับ:**
int - Horizontal Alignment of specified column
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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| columnIndex | int | ดัชนีคอลัมน์เริ่มจาก 0 |
| val | int | ค่าการจัดแนวนอนใหม่ของคอลัมน์ที่ระบุ |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public abstract void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

ตั้งค่าการจัดแนวนอนของคอลัมน์ที่ระบุหลายคอลัมน์

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| columnIndex | int | ดัชนีคอลัมน์แรกที่ต้องการตั้งค่าการจัดแนว |
| columnsCount | long | จำนวนคอลัมน์ที่ต้องการกำหนดการจัดแนว |
| val | int | ค่าการจัดแนวนอนใหม่ของคอลัมน์ที่ระบุ |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public abstract void insertRowBefore(int rowIndex)
```

แทรกแถวใหม่ก่อนแถวที่ระบุ โดยเริ่มต้นทุกส่วนในแถวใหม่เป็น null.

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| rowIndex | int | ดัชนีของแถวที่ต้องการแทรกแถวใหม่ข้างหน้า |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public abstract void insertRowAfter(int rowIndex)
```

แทรกแถวใหม่หลังแถวที่ระบุ โดยเริ่มต้นทุกส่วนในแถวใหม่เป็น null.

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| rowIndex | int | ดัชนีของแถวที่ต้องการแทรกแถวใหม่ข้างหลัง |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public abstract void deleteRow(int rowIndex)
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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| rowIndex | int | ดัชนีเริ่มจาก 0 ของแถวที่ต้องการลบ. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public abstract void insertColumnBefore(int columnIndex)
```

แทรกคอลัมน์ใหม่ก่อนคอลัมน์ที่ระบุ โดยเริ่มต้นทุกส่วนในคอลัมน์ใหม่เป็น null.

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| columnIndex | int | ดัชนีของคอลัมน์ที่ต้องการแทรกคอลัมน์ใหม่ข้างหน้า |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public abstract void insertColumnAfter(int columnIndex)
```

แทรกคอลัมน์ใหม่หลังคอลัมน์ที่ระบุ โดยเริ่มต้นทุกส่วนในคอลัมน์ใหม่เป็น null.

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| columnIndex | int | ดัชนีของคอลัมน์ที่ต้องการแทรกคอลัมน์ใหม่ข้างหลัง |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public abstract void deleteColumn(int columnIndex)
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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| columnIndex | int | ดัชนีเริ่มจาก 0 ของคอลัมน์ที่ต้องการลบ. |