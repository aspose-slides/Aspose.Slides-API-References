---
title: CellFormat
second_title: Aspose.Slides สำหรับ Android ผ่านเอกสารอ้างอิง Java API
description: แสดงรูปแบบของเซลล์ตาราง.
type: docs
url: /th/com.aspose.slides/cellformat/
---
**Inheritance:**  
การสืบทอด: java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**  
อินเทอร์เฟซที่นำไปใช้ทั้งหมด:  
[com.aspose.slides.ICellFormat](../../com.aspose.slides/icellformat)  
```
public final class CellFormat extends PVIObject implements ICellFormat
```

แทนรูปแบบของเซลล์ตาราง.
## Methods

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillFormat()](#getFillFormat--) | คืนค่าอ็อบเจกต์คุณสมบัติการเติมเซลล์ |
| [getBorderLeft()](#getBorderLeft--) | คืนค่าอ็อบเจกต์คุณสมบัติเส้นขอบซ้าย |
| [getBorderTop()](#getBorderTop--) | คืนค่าอ็อบเจกต์คุณสมบัติเส้นขอบบน |
| [getBorderRight()](#getBorderRight--) | คืนค่าอ็อบเจกต์คุณสมบัติเส้นขอบขวา |
| [getBorderBottom()](#getBorderBottom--) | คืนค่าอ็อบเจกต์คุณสมบัติเส้นขอบล่าง |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | คืนค่าอ็อบเจกต์คุณสมบัติเส้นทแยงมุมจากซ้ายบนไปขวาล่าง |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | คืนค่าอ็อบเจกต์คุณสมบัติเส้นทแยงมุมจากซ้ายล่างไปขวาบน |
| [getEffective()](#getEffective--) | ดึงคุณสมบัติการจัดรูปแบบเซลล์ตารางที่มีผลโดยคำนึงถึงการสืบทอดและสไตล์ของตารางที่ใช้ |
| [getTransparency()](#getTransparency--) | ดึงหรือกำหนดความโปร่งใสของสีเติม |
| [setTransparency(float value)](#setTransparency-float-) | ดึงหรือกำหนดความโปร่งใสของสีเติม |
### getVersion() {#getVersion--}
```
public long getVersion()
```

เวอร์ชัน. อ่านอย่างเดียว long.

**Returns:**  
คืนค่า:  
long
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

คืนค่าอ็อบเจกต์คุณสมบัติการเติมเซลล์. อ่านอย่างเดียว [IFillFormat](../../com.aspose.slides/ifillformat).

**Returns:**  
คืนค่า:  
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public final ILineFormat getBorderLeft()
```

คืนค่าอ็อบเจกต์คุณสมบัติเส้นขอบซ้าย. อ่านอย่างเดียว [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**  
คืนค่า:  
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public final ILineFormat getBorderTop()
```

คืนค่าอ็อบเจกต์คุณสมบัติเส้นขอบบน. อ่านอย่างเดียว [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**  
คืนค่า:  
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public final ILineFormat getBorderRight()
```

คืนค่าอ็อบเจกต์คุณสมบัติเส้นขอบขวา. อ่านอย่างเดียว [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**  
คืนค่า:  
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public final ILineFormat getBorderBottom()
```

คืนค่าอ็อบเจกต์คุณสมบัติเส้นขอบล่าง. อ่านอย่างเดียว [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**  
คืนค่า:  
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public final ILineFormat getBorderDiagonalDown()
```

คืนค่าอ็อบเจกต์คุณสมบัติเส้นทแยงมุมจากซ้ายบนไปขวาล่าง. อ่านอย่างเดียว [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**  
คืนค่า:  
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public final ILineFormat getBorderDiagonalUp()
```

คืนค่าอ็อบเจกต์คุณสมบัติเส้นทแยงมุมจากซ้ายล่างไปขวาบน. อ่านอย่างเดียว [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**  
คืนค่า:  
[ILineFormat](../../com.aspose.slides/ilineformat)
### getEffective() {#getEffective--}
```
public final ICellFormatEffectiveData getEffective()
```

ดึงคุณสมบัติการจัดรูปแบบเซลล์ตารางที่มีผลโดยคำนึงถึงการสืบทอดและสไตล์ของตารางที่ใช้.

--------------------

> ```
> This example demonstrates getting effective fill format for different table logic parts.
>  Please note that cell formatting always has higher priority than row formatting, row - higher than column, column - higher that whole table.
>  So finally CellFormatEffectiveData properties always used to draw the table. The following code is just an example of API.
>  
>  Presentation pres = new Presentation(@"MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (ITable) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).RowFormat.GetEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returns:**  
คืนค่า:  
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - A [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```

ดึงหรือกำหนดความโปร่งใสของสีเติม. อ่าน/เขียน  float .

**Returns:**  
คืนค่า:  
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```

ดึงหรือกำหนดความโปร่งใสของสีเติม. อ่าน/เขียน  float .

**Parameters:**  
พารามิเตอร์:  
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |