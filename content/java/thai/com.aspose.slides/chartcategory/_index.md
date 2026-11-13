---
title: ChartCategory
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงถึงหมวดหมู่ของแผนภูมิ.
type: docs
url: /th/com.aspose.slides/chartcategory/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ Implement ทั้งหมด:**
[com.aspose.slides.IChartCategory](../../com.aspose.slides/ichartcategory), com.aspose.slides.IDOMObject
```
public class ChartCategory implements IChartCategory, IDOMObject
```

แสดงถึงหมวดหมู่ของแผนภูมิ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getUseCell()](#getUseCell--) | ถ้าเป็น true แล้ว property AsCell จะเป็นค่าจริง |
| [getAsCell()](#getAsCell--) | คืนค่าหรือกำหนดอ็อบเจ็กต์ IChartDataCell |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | คืนค่าหรือกำหนดอ็อบเจ็กต์ IChartDataCell |
| [getAsLiteral()](#getAsLiteral--) | คืนค่า或กำหนดอ็อบเจ็กต์ AsLiteral |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | คืนค่า或กำหนดอ็อบเจ็กต์ AsLiteral |
| [getValue()](#getValue--) | ถ้า UseCell เป็น true แล้ว property นี้จะแสดงค่า property AsCell.Value |
| [setValue(Object value)](#setValue-java.lang.Object-) | ถ้า UseCell เป็น true แล้ว property นี้จะแสดงค่า property AsCell.Value |
| [getGroupingLevels()](#getGroupingLevels--) | คอนเทนเนอร์ที่จัดการค่าของระดับการจัดกลุ่มหมวดหมู่แผนภูมิ |
| [getCachedValue()](#getCachedValue--) | ดึงค่าที่แคชของหมวดหมู่แผนภูมิ |
| [remove()](#remove--) | ลบหมวดหมู่ออกจากแผนภูมิ |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```


ถ้าเป็น true แล้ว property AsCell จะเป็นค่าจริง ในอีกแง่หนึ่ง worksheet จะใช้สำหรับเก็บหมวดหมู่ (กรณีนี้รองรับหมวดหมู่หลายระดับ) หากเป็น false แล้ว property AsLiteral จะเป็นค่าจริง ในอีกแง่หนึ่ง worksheet จะไม่ใช้สำหรับเก็บหมวดหมู่ (และกรณีนี้ไม่รองรับหมวดหมู่หลายระดับ) เป็น boolean แบบอ่านอย่างเดียว

--------------------

เพื่อเปลี่ยนค่าใน property นี้ (สำหรับหมวดหมู่ทั้งหมดในคอลเล็กชัน) ให้ตั้งค่าที่ใหม่ให้กับ property ChartCategoryCollection.UseCells

**คืนค่า:**
boolean
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```


คืนค่า或กำหนดอ็อบเจ็กต์ IChartDataCell หากหมวดหมู่เป็นหลายระดับแล้วจะใช้ IChartDataCell สำหรับระดับ "0" อ่าน-เขียน [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**คืนค่า:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```


คืนค่า或กำหนดอ็อบเจ็กต์ IChartDataCell หากหมวดหมู่เป็นหลายระดับแล้วจะใช้ IChartDataCell สำหรับระดับ "0" อ่าน-เขียน [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```


คืนค่า或กำหนดอ็อบเจ็กต์ AsLiteral อ่าน-เขียน Object.

**คืนค่า:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public final void setAsLiteral(Object value)
```


คืนค่า或กำหนดอ็อบเจ็กต์ AsLiteralอ่าน-เขียน Object.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.Object |  |
### getValue() {#getValue--}
```
public final Object getValue()
```


ถ้า UseCell เป็น true แล้ว property นี้จะแทนค่า property AsCell.Value หาก UseCell เป็น false แล้ว property นี้จะแทนค่า property AsLiteral อ่าน-เขียน Object.

**คืนค่า:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


ถ้า UseCell เป็น true แล้ว property นี้จะแทนค่า property AsCell.Value หาก UseCell เป็น false แล้ว property นี้จะแทนค่า property AsLiteral อ่าน-เขียน Object.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.Object |  |
### getGroupingLevels() {#getGroupingLevels--}
```
public final IChartCategoryLevelsManager getGroupingLevels()
```


คอนเทนเนอร์ที่จัดการค่าของระดับการจัดกลุ่มหมวดหมู่แผนภูมิ หมวดหมู่หลายระดับจะมีหลายระดับการจัดกลุ่ม การจัดทำดัชนีของระดับการจัดกลุ่มเริ่มจากศูนย์ อ่าน-อย่างเดียว [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**คืนค่า:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### getCachedValue() {#getCachedValue--}
```
public final ICachedChartValue getCachedValue()
```


ดึงค่าที่แคชของหมวดหมู่แผนภูมิ อ่าน-อย่างเดียว [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx")
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
> 
>      // พิมพ์ค่าหมวดหมู่แผนภูมิที่แคชทั้งหมด.
>      for (IChartCategory category : chart.getChartData().getCategories())
>          System.out.println(category.getCachedValue().toString());
>  } finally {
>      pres.dispose();
>  }
> ```

**คืนค่า:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### remove() {#remove--}
```
public final void remove()
```


ลบหมวดหมู่ออกจากแผนภูมิ.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


คืนค่าอ็อบเจ็กต์ Parent_Immediate อ่าน-อย่างเดียว IDOMObject.

**คืนค่า:**
com.aspose.slides.IDOMObject