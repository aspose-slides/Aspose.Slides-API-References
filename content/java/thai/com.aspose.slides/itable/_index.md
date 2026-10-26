---
title: ITable
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงตารางบนสไลด์หนึ่งรายการ
type: docs
url: /th/com.aspose.slides/itable/
---
**All Implemented Interfaces:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface ITable extends IGraphicalObject, IBulkTextFormattable
```

แทนตารางบนสไลด์หนึ่งรายการ
## เมธอด

| Method | Description |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | คืนค่าเซลล์ที่ระบุด้วยดัชนีคอลัมน์และแถว |
| [getRows()](#getRows--) | คืนค่าชุดของแถว |
| [getColumns()](#getColumns--) | คืนค่าชุดของคอลัมน์ |
| [getTableFormat()](#getTableFormat--) | คืนค่าออบเจ็กต์ TableFormat ซึ่งมีคุณสมบัติการจัดรูปแบบสำหรับตารางนี้ |
| [getStylePreset()](#getStylePreset--) | ดึงหรือกำหนดสไตล์ตารางที่มีอยู่ในตัว |
| [setStylePreset(int value)](#setStylePreset-int-) | ดึงหรือกำหนดสไตล์ตารางที่มีอยู่ในตัว |
| [getRightToLeft()](#getRightToLeft--) | กำหนดว่าตารางมีลำดับการอ่านจากขวาไปซ้ายหรือไม่ |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | กำหนดว่าตารางมีลำดับการอ่านจากขวาไปซ้ายหรือไม่ |
| [getFirstRow()](#getFirstRow--) | กำหนดว่าการแถวแรกของตารางต้องวาดด้วยรูปแบบพิเศษหรือไม่ |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | กำหนดว่าการแถวแรกของตารางต้องวาดด้วยรูปแบบพิเศษหรือไม่ |
| [getFirstCol()](#getFirstCol--) | กำหนดว่าคอลัมน์แรกของตารางต้องวาดด้วยรูปแบบพิเศษหรือไม่ |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | กำหนดว่าคอลัมน์แรกของตารางต้องวาดด้วยรูปแบบพิเศษหรือไม่ |
| [getLastRow()](#getLastRow--) | กำหนดว่าการแถวสุดท้ายของตารางต้องวาดด้วยรูปแบบพิเศษหรือไม่ |
| [setLastRow(boolean value)](#setLastRow-boolean-) | กำหนดว่าการแถวสุดท้ายของตารางต้องวาดด้วยรูปแบบพิเศษหรือไม่ |
| [getLastCol()](#getLastCol--) | กำหนดว่าคอลัมน์สุดท้ายของตารางต้องวาดด้วยรูปแบบพิเศษหรือไม่ |
| [setLastCol(boolean value)](#setLastCol-boolean-) | กำหนดว่าคอลัมน์สุดท้ายของตารางต้องวาดด้วยรูปแบบพิเศษหรือไม่ |
| [getHorizontalBanding()](#getHorizontalBanding--) | กำหนดว่าการแถวคู่ต้องวาดด้วยรูปแบบที่แตกต่างหรือไม่ |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | กำหนดว่าการแถวคู่ต้องวาดด้วยรูปแบบที่แตกต่างหรือไม่ |
| [getVerticalBanding()](#getVerticalBanding--) | กำหนดว่าคอลัมน์คู่ต้องวาดด้วยรูปแบบที่แตกต่างหรือไม่ |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | กำหนดว่าคอลัมน์คู่ต้องวาดด้วยรูปแบบที่แตกต่างหรือไม่ |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | รวมเซลล์ที่อยู่ข้างเคียง |
### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public abstract ICell get_Item(int columnIndex, int rowIndex)
```

คืนค่าเซลล์ที่ระบุด้วยดัชนีคอลัมน์และแถว อ่านอย่างเดียว [ICell](../../com.aspose.slides/icell).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Returns:**
[ICell](../../com.aspose.slides/icell)
### getRows() {#getRows--}
```
public abstract IRowCollection getRows()
```

คืนค่าชุดของแถว อ่านอย่างเดียว [IRowCollection](../../com.aspose.slides/irowcollection).

**Returns:**
[IRowCollection](../../com.aspose.slides/irowcollection)
### getColumns() {#getColumns--}
```
public abstract IColumnCollection getColumns()
```

คืนค่าชุดของคอลัมน์ อ่านอย่างเดียว [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Returns:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)
### getTableFormat() {#getTableFormat--}
```
public abstract ITableFormat getTableFormat()
```

คืนค่าออบเจ็กต์ TableFormat ซึ่งมีคุณสมบัติการจัดรูปแบบสำหรับตารางนี้ อ่านอย่างเดียว [ITableFormat](../../com.aspose.slides/itableformat).

**Returns:**
[ITableFormat](../../com.aspose.slides/itableformat)
### getStylePreset() {#getStylePreset--}
```
public abstract int getStylePreset()
```

ดึงหรือกำหนดสไตล์ตารางที่มีอยู่ในตัว อ่าน/เขียน [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Returns:**
int
### setStylePreset(int value) {#setStylePreset-int-}
```
public abstract void setStylePreset(int value)
```

ดึงหรือกำหนดสไตล์ตารางที่มีอยู่ในตัว อ่าน/เขียน [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

กำหนดว่าตารางมีลำดับการอ่านจากขวาไปซ้ายหรือไม่ อ่าน/เขียน boolean.

**Returns:**
boolean
### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public abstract void setRightToLeft(boolean value)
```

กำหนดว่าตารางมีลำดับการอ่านจากขวาไปซ้ายหรือไม่ อ่าน/เขียน boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public abstract boolean getFirstRow()
```

กำหนดว่าการแถวแรกของตารางต้องวาดด้วยรูปแบบพิเศษหรือไม่ อ่าน/เขียน boolean.

**Returns:**
boolean
### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public abstract void setFirstRow(boolean value)
```

กำหนดว่าการแถวแรกของตารางต้องวาดด้วยรูปแบบพิเศษหรือไม่ อ่าน/เขียน boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public abstract boolean getFirstCol()
```

กำหนดว่าคอลัมน์แรกของตารางต้องวาดด้วยรูปแบบพิเศษหรือไม่ อ่าน/เขียน boolean.

**Returns:**
boolean
### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public abstract void setFirstCol(boolean value)
```

กำหนดว่าคอลัมน์แรกของตารางต้องวาดด้วยรูปแบบพิเศษหรือไม่ อ่าน/เขียน boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public abstract boolean getLastRow()
```

กำหนดว่าการแถวสุดท้ายของตารางต้องวาดด้วยรูปแบบพิเศษหรือไม่ อ่าน/เขียน boolean.

**Returns:**
boolean
### setLastRow(boolean value) {#setLastRow-boolean-}
```
public abstract void setLastRow(boolean value)
```

กำหนดว่าการแถวสุดท้ายของตารางต้องวาดด้วยรูปแบบพิเศษหรือไม่ อ่าน/เขียน boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public abstract boolean getLastCol()
```

กำหนดว่าคอลัมน์สุดท้ายของตารางต้องวาดด้วยรูปแบบพิเศษหรือไม่ อ่าน/เขียน boolean.

**Returns:**
boolean
### setLastCol(boolean value) {#setLastCol-boolean-}
```
public abstract void setLastCol(boolean value)
```

กำหนดว่าคอลัมน์สุดท้ายของตารางต้องวาดด้วยรูปแบบพิเศษหรือไม่ อ่าน/เขียน boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public abstract boolean getHorizontalBanding()
```

กำหนดว่าการแถวคู่ต้องวาดด้วยรูปแบบที่แตกต่างหรือไม่ อ่าน/เขียน boolean.

**Returns:**
boolean
### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public abstract void setHorizontalBanding(boolean value)
```

กำหนดว่าการแถวคู่ต้องวาดด้วยรูปแบบที่แตกต่างหรือไม่ อ่าน/เขียน boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public abstract boolean getVerticalBanding()
```

กำหนดว่าคอลัมน์คู่ต้องวาดด้วยรูปแบบที่แตกต่างหรือไม่ อ่าน/เขียน boolean.

**Returns:**
boolean
### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public abstract void setVerticalBanding(boolean value)
```

กำหนดว่าคอลัมน์คู่ต้องวาดด้วยรูปแบบที่แตกต่างหรือไม่ อ่าน/เขียน boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public abstract ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

รวมเซลล์ที่อยู่ข้างเคียง

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | เซลล์ที่จะรวม |
| cell2 | [ICell](../../com.aspose.slides/icell) | เซลล์ที่จะรวม |
| allowSplitting | boolean | true หากอนุญาตให้เซลล์แยกออก |

**Returns:**
[ICell](../../com.aspose.slides/icell) - เซลล์ที่รวมแล้ว.