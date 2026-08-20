---
title: CellFormat
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงรูปแบบของเซลล์ตาราง.
type: docs
url: /th/com.aspose.slides/cellformat/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**ทุกอินเทอร์เฟซที่ทำการใช้งาน:**
[com.aspose.slides.ICellFormat](../../com.aspose.slides/icellformat)
```
public final class CellFormat extends PVIObject implements ICellFormat
```

แสดงรูปแบบของเซลล์ตาราง.
## เมธอด

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillFormat()](#getFillFormat--) | คืนค่าอ็อบเจกต์คุณสมบัติการเติมเซลล์. |
| [getBorderLeft()](#getBorderLeft--) | คืนค่าอ็อบเจกต์คุณสมบัติเส้นขอบด้านซ้าย. |
| [getBorderTop()](#getBorderTop--) | คืนค่าอ็อบเจกต์คุณสมบัติเส้นขอบด้านบน. |
| [getBorderRight()](#getBorderRight--) | คืนค่าอ็อบเจกต์คุณสมบัติเส้นขอบด้านขวา. |
| [getBorderBottom()](#getBorderBottom--) | คืนค่าอ็อบเจกต์คุณสมบัติเส้นขอบด้านล่าง. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | คืนค่าอ็อบเจกต์คุณสมบัติเส้นทแยงจากบนซ้ายไปล่างขวา. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | คืนค่าอ็อบเจกต์คุณสมบัติเส้นทแยงจากล่างซ้ายไปบนขวา. |
| [getEffective()](#getEffective--) | รับคุณสมบัติการจัดรูปแบบเซลล์ตารางที่มีผลโดยมีการสืบทอดและสไตล์ตารางที่นำมาใช้. |
| [getTransparency()](#getTransparency--) | รับหรือกำหนดความโปร่งใสของสีเติม. |
| [setTransparency(float value)](#setTransparency-float-) | รับหรือกำหนดความโปร่งใสของสีเติม. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


เวอร์ชัน. อ่านอย่างเดียว long.

**คืนค่า:**
long
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


คืนค่าอ็อบเจกต์คุณสมบัติการเติมเซลล์. อ่านอย่างเดียว [IFillFormat](../../com.aspose.slides/ifillformat).

**คืนค่า:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public final ILineFormat getBorderLeft()
```


คืนค่าอ็อบเจกต์คุณสมบัติเส้นขอบด้านซ้าย. อ่านอย่างเดียว [ILineFormat](../../com.aspose.slides/ilineformat).

**คืนค่า:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public final ILineFormat getBorderTop()
```


คืนค่าอ็อบเจกต์คุณสมบัติเส้นขอบด้านบน. อ่านอย่างเดียว [ILineFormat](../../com.aspose.slides/ilineformat).

**คืนค่า:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public final ILineFormat getBorderRight()
```


คืนค่าอ็อบเจกต์คุณสมบัติเส้นขอบด้านขวา. อ่านอย่างเดียว [ILineFormat](../../com.aspose.slides/ilineformat).

**คืนค่า:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public final ILineFormat getBorderBottom()
```


คืนค่าอ็อบเจกต์คุณสมบัติเส้นขอบด้านล่าง. อ่านอย่างเดียว [ILineFormat](../../com.aspose.slides/ilineformat).

**คืนค่า:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public final ILineFormat getBorderDiagonalDown()
```


คืนค่าอ็อบเจกต์คุณสมบัติเส้นทแยงจากบนซ้ายไปล่างขวา. อ่านอย่างเดียว [ILineFormat](../../com.aspose.slides/ilineformat).

**คืนค่า:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public final ILineFormat getBorderDiagonalUp()
```


คืนค่าอ็อบเจกต์คุณสมบัติเส้นทแยงจากล่างซ้ายไปบนขวา. อ่านอย่างเดียว [ILineFormat](../../com.aspose.slides/ilineformat).

**คืนค่า:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getEffective() {#getEffective--}
```
public final ICellFormatEffectiveData getEffective()
```


รับคุณสมบัติการจัดรูปแบบเซลล์ตารางที่มีผลโดยมีการสืบทอดและสไตล์ตารางที่นำมาใช้.

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


**คืนค่า:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - หนึ่ง [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```


รับหรือกำหนดความโปร่งใสของสีเติม. อ่าน/เขียน  float .

**คืนค่า:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```


รับหรือกำหนดความโปร่งใสของสีเติม. อ่าน/เขียน  float .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |