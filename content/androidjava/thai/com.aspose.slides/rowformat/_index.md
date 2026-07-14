---
title: RowFormat
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงรูปแบบของแถวตาราง.
type: docs
url: /th/com.aspose.slides/rowformat/
---
**การสืบทอด:**
java.lang.Object, com.aspose.slides.DomObject

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IRowFormat](../../com.aspose.slides/irowformat), com.aspose.slides.IPVIObject
```
public final class RowFormat extends DomObject<Row> implements IRowFormat, IPVIObject
```

แสดงรูปแบบของแถวตาราง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getEffective()](#getEffective--) | รับคุณสมบัติการจัดรูปแบบแถวตารางที่มีผลโดยคำนึงถึงการสืบทอดและสไตล์ตารางที่ใช้ |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getEffective() {#getEffective--}
```
public final IRowFormatEffectiveData getEffective()
```

รับคุณสมบัติการจัดรูปแบบแถวตารางที่มีผลโดยคำนึงถึงการสืบทอดและสไตล์ตารางที่ใช้.

--------------------

> ```
> This example demonstrates getting effective fill format for different table logic parts.
>  Please note that cell formatting always has higher priority than row formatting, row - higher than column, column - higher that whole table.
>  So finally CellFormatEffectiveData properties always used to draw the table. The following code is just an example of API.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (ITable)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).getRowFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**
[IRowFormatEffectiveData](../../com.aspose.slides/irowformateffectivedata) - หนึ่ง [IRowFormatEffectiveData](../../com.aspose.slides/irowformateffectivedata).
### getVersion() {#getVersion--}
```
public final long getVersion()
```

เวอร์ชัน. อ่านอย่างเดียว long.

**คืนค่า:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

คืนค่า parent IPresentationComponent. อ่านอย่างเดียว [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**คืนค่า:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)