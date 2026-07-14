---
title: ITable
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงตารางบนสไลด์
type: docs
url: /th/com.aspose.slides/itable/
---
**All Implemented Interfaces:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface ITable extends IGraphicalObject, IBulkTextFormattable
```

แสดงตารางบนสไลด์.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | คืนเซลที่ตำแหน่งคอลัมน์และแถวที่ระบุ. |
| [getRows()](#getRows--) | คืนคอลเลกชันของแถว. |
| [getColumns()](#getColumns--) | คืนคอลเลกชันของคอลัมน์. |
| [getTableFormat()](#getTableFormat--) | คืนอ็อบเจกต์ TableFormat ซึ่งบรรจุคุณสมบัติการจัดรูปแบบสำหรับตารางนี้. |
| [getStylePreset()](#getStylePreset--) | รับหรือกำหนดสไตล์ตารางที่สร้างไว้ในตัว. |
| [setStylePreset(int value)](#setStylePreset-int-) | รับหรือกำหนดสไตล์ตารางที่สร้างไว้ในตัว. |
| [getRightToLeft()](#getRightToLeft--) | กำหนดว่าตารางมีลำดับการอ่านจากขวาไปซ้ายหรือไม่. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | กำหนดว่าตารางมีลำดับการอ่านจากขวาไปซ้ายหรือไม่. |
| [getFirstRow()](#getFirstRow--) | กำหนดว่าต้องวาดแถวแรกของตารางด้วยการจัดรูปแบบพิเศษหรือไม่. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | กำหนดว่าต้องวาดแถวแรกของตารางด้วยการจัดรูปแบบพิเศษหรือไม่. |
| [getFirstCol()](#getFirstCol--) | กำหนดว่าต้องวาดคอลัมน์แรกของตารางด้วยการจัดรูปแบบพิเศษหรือไม่. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | กำหนดว่าต้องวาดคอลัมน์แรกของตารางด้วยการจัดรูปแบบพิเศษหรือไม่. |
| [getLastRow()](#getLastRow--) | กำหนดว่าต้องวาดแถวสุดท้ายของตารางด้วยการจัดรูปแบบพิเศษหรือไม่. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | กำหนดว่าต้องวาดแถวสุดท้ายของตารางด้วยการจัดรูปแบบพิเศษหรือไม่. |
| [getLastCol()](#getLastCol--) | กำหนดว่าต้องวาดคอลัมน์สุดท้ายของตารางด้วยการจัดรูปแบบพิเศษหรือไม่. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | กำหนดว่าต้องวาดคอลัมน์สุดท้ายของตารางด้วยการจัดรูปแบบพิเศษหรือไม่. |
| [getHorizontalBanding()](#getHorizontalBanding--) | กำหนดว่าต้องวาดแถวคู่ของตารางด้วยการจัดรูปแบบที่แตกต่างหรือไม่. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | กำหนดว่าต้องวาดแถวคู่ของตารางด้วยการจัดรูปแบบที่แตกต่างหรือไม่. |
| [getVerticalBanding()](#getVerticalBanding--) | กำหนดว่าต้องวาดคอลัมน์คู่ของตารางด้วยการจัดรูปแบบที่แตกต่างหรือไม่. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | กำหนดว่าต้องวาดคอลัมน์คู่ของตารางด้วยการจัดรูปแบบที่แตกต่างหรือไม่. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | ผสานเซลล์ที่อยู่ใกล้เคียง. |

### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public abstract ICell get_Item(int columnIndex, int rowIndex)
```

คืนเซลที่ตำแหน่งคอลัมน์และแถวที่ระบุ. อ่านอย่างเดียว [ICell](../../com.aspose.slides/icell).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**คืนค่า:**
[ICell](../../com.aspose.slides/icell)

### getRows() {#getRows--}
```
public abstract IRowCollection getRows()
```

คืนคอลเลกชันของแถว. อ่านอย่างเดียว [IRowCollection](../../com.aspose.slides/irowcollection).

**คืนค่า:**
[IRowCollection](../../com.aspose.slides/irowcollection)

### getColumns() {#getColumns--}
```
public abstract IColumnCollection getColumns()
```

คืนคอลเลกชันของคอลัมน์. อ่านอย่างเดียว [IColumnCollection](../../com.aspose.slides/icolumncollection).

**คืนค่า:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)

### getTableFormat() {#getTableFormat--}
```
public abstract ITableFormat getTableFormat()
```

คืนอ็อบเจกต์ TableFormat ซึ่งบรรจุคุณสมบัติการจัดรูปแบบสำหรับตารางนี้. อ่านอย่างเดียว [ITableFormat](../../com.aspose.slides/itableformat).

**คืนค่า:**
[ITableFormat](../../com.aspose.slides/itableformat)

### getStylePreset() {#getStylePreset--}
```
public abstract int getStylePreset()
```

รับหรือกำหนดสไตล์ตารางที่สร้างไว้ในตัว. อ่าน/เขียน [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**คืนค่า:**
int

### setStylePreset(int value) {#setStylePreset-int-}
```
public abstract void setStylePreset(int value)
```

รับหรือกำหนดสไตล์ตารางที่สร้างไว้ในตัว. อ่าน/เขียน [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

กำหนดว่าตารางมีลำดับการอ่านจากขวาไปซ้ายหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public abstract void setRightToLeft(boolean value)
```

กำหนดว่าตารางมีลำดับการอ่านจากขวาไปซ้ายหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public abstract boolean getFirstRow()
```

กำหนดว่าต้องวาดแถวแรกของตารางด้วยการจัดรูปแบบพิเศษหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public abstract void setFirstRow(boolean value)
```

กำหนดว่าต้องวาดแถวแรกของตารางด้วยการจัดรูปแบบพิเศษหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public abstract boolean getFirstCol()
```

กำหนดว่าต้องวาดคอลัมน์แรกของตารางด้วยการจัดรูปแบบพิเศษหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public abstract void setFirstCol(boolean value)
```

กำหนดว่าต้องวาดคอลัมน์แรกของตารางด้วยการจัดรูปแบบพิเศษหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public abstract boolean getLastRow()
```

กำหนดว่าต้องวาดแถวสุดท้ายของตารางด้วยการจัดรูปแบบพิเศษหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setLastRow(boolean value) {#setLastRow-boolean-}
```
public abstract void setLastRow(boolean value)
```

กำหนดว่าต้องวาดแถวสุดท้ายของตารางด้วยการจัดรูปแบบพิเศษหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public abstract boolean getLastCol()
```

กำหนดว่าต้องวาดคอลัมน์สุดท้ายของตารางด้วยการจัดรูปแบบพิเศษหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setLastCol(boolean value) {#setLastCol-boolean-}
```
public abstract void setLastCol(boolean value)
```

กำหนดว่าต้องวาดคอลัมน์สุดท้ายของตารางด้วยการจัดรูปแบบพิเศษหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public abstract boolean getHorizontalBanding()
```

กำหนดว่าต้องวาดแถวคู่ของตารางด้วยการจัดรูปแบบที่แตกต่างหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public abstract void setHorizontalBanding(boolean value)
```

กำหนดว่าต้องวาดแถวคู่ของตารางด้วยการจัดรูปแบบที่แตกต่างหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public abstract boolean getVerticalBanding()
```

กำหนดว่าต้องวาดคอลัมน์คู่ของตารางด้วยการจัดรูปแบบที่แตกต่างหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public abstract void setVerticalBanding(boolean value)
```

กำหนดว่าต้องวาดคอลัมน์คู่ของตารางด้วยการจัดรูปแบบที่แตกต่างหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public abstract ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

ผสานเซลล์ที่อยู่ใกล้เคียง.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | เซลล์ที่จะผสาน. |
| cell2 | [ICell](../../com.aspose.slides/icell) | เซลล์ที่จะผสาน. |
| allowSplitting | boolean | True เพื่ออนุญาตให้เซลล์แยกออก. |

**คืนค่า:**
[ICell](../../com.aspose.slides/icell) - เซลล์ที่ผสานแล้ว.