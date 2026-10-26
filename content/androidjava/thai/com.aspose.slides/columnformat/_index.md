---
title: ColumnFormat
second_title: Aspose.Slides สำหรับ Android ผ่านอ้างอิง API ของ Java
description: แสดงรูปแบบของคอลัมน์ตาราง.
type: docs
url: /th/com.aspose.slides/columnformat/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IColumnFormat](../../com.aspose.slides/icolumnformat), com.aspose.slides.IPVIObject
```
public final class ColumnFormat extends DomObject<Column> implements IColumnFormat, IPVIObject
```

แสดงรูปแบบของคอลัมน์ตาราง.
## เมธอด

| Method | Description |
| --- | --- |
| [getEffective()](#getEffective--) | ดึงคุณสมบัติการจัดรูปแบบคอลัมน์ตารางที่มีผลโดยใช้การสืบทอดและสไตล์ของตาราง |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getEffective() {#getEffective--}
```
public final IColumnFormatEffectiveData getEffective()
```


ดึงคุณสมบัติการจัดรูปแบบคอลัมน์ตารางที่มีผลโดยใช้การสืบทอดและสไตล์ของตาราง

--------------------

> ```
> ตัวอย่างนี้แสดงการรับรูปแบบการเติมที่มีผลสำหรับส่วนต่าง ๆ ของตรรกะตาราง.
>  โปรดทราบว่าการจัดรูปแบบเซลล์จะมีลำดับความสำคัญสูงกว่าการจัดรูปแบบแถว, แถวสูงกว่าคอลัมน์, คอลัมน์สูงกว่าตารางทั้งหมด.
>  ดังนั้นในที่สุดคุณสมบัติ CellFormatEffectiveData จะถูกใช้เสมอสำหรับวาดตาราง. โค้ดต่อไปนี้เป็นเพียงตัวอย่างของ API.
>  
>  Presentation pres = new Presentation(@"MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (Table)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).getRowFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**
[IColumnFormatEffectiveData](../../com.aspose.slides/icolumnformateffectivedata) - เป็น [IColumnFormatEffectiveData](../../com.aspose.slides/icolumnformateffectivedata).
### getVersion() {#getVersion--}
```
public final long getVersion()
```


เวอร์ชัน. long ที่อ่านอย่างเดียว

**คืนค่า:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


คืนค่าพาเรนต์ IPresentationComponent. อ่านอย่างเดียว [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**คืนค่า:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)