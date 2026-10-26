---
title: TableFormat
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงรูปแบบของตาราง.
type: docs
url: /th/com.aspose.slides/tableformat/
---
**การสืบทอด:**  
java.lang.Object, com.aspose.slides.DomObject

**ทั้งหมดที่ทำตามอินเทอร์เฟซ:**  
[com.aspose.slides.ITableFormat](../../com.aspose.slides/itableformat), com.aspose.slides.IPVIObject  
```
public final class TableFormat extends DomObject<Table> implements ITableFormat, IPVIObject
```

แสดงรูปแบบของตาราง.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | ส่งคืนอ็อบเจ็กต์คุณสมบัติการเติมของตาราง. |
| [getTransparency()](#getTransparency--) | รับหรือกำหนดความโปร่งใสของสีเติม. |
| [setTransparency(float value)](#setTransparency-float-) | รับหรือกำหนดความโปร่งใสของสีเติม. |
| [getEffective()](#getEffective--) | รับคุณสมบัติการจัดรูปแบบตารางที่มีผลกับการสืบทอดและสไตล์ของตารางที่ถูกนำไปใช้. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

ส่งคืนอ็อบเจ็กต์คุณสมบัติการเติมของตาราง. อ่านอย่างเดียว [IFillFormat](../../com.aspose.slides/ifillformat).

**ส่งคืน:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```

รับหรือกำหนดความโปร่งใสของสีเติม. อ่าน/เขียน  float .

**ส่งคืน:**  
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

### getEffective() {#getEffective--}
```
public final ITableFormatEffectiveData getEffective()
```

รับคุณสมบัติการจัดรูปแบบตารางที่มีผลกับการสืบทอดและสไตล์ของตารางที่ถูกนำไปใช้.

--------------------

> ```markdown
> ตัวอย่างนี้แสดงการรับรูปแบบการเติมที่มีประสิทธิภาพสำหรับส่วนตรรกะของตารางที่ต่างกัน.
>  โปรดทราบว่าการจัดรูปแบบเซลล์มีลำดับความสำคัญสูงกว่าการจัดรูปแบบแถว, แถวนั้นสูงกว่าคอลัมน์, คอลัมน์สูงกว่าตารางทั้งหมด.
>  ดังนั้นคุณลักษณะ CellFormatEffectiveData จะถูกใช้เสมอเพื่อวาดตาราง. โค้ดต่อไปนี้เป็นเพียงตัวอย่างของ API.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
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


**ส่งคืน:**  
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - หนึ่ง [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).

### getVersion() {#getVersion--}
```
public final long getVersion()
```

เวอร์ชัน. อ่านอย่างเดียว long.

**ส่งคืน:**  
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

ส่งคืนส่วนแม่ IPresentationComponent. อ่านอย่างเดียว [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**ส่งคืน:**  
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)