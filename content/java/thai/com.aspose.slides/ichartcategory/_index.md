---
title: IChartCategory
second_title: Aspose.Slides for Java API Reference
description: เป็นตัวแทนของหมวดหมู่แผนภูมิ
type: docs
url: /th/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

เป็นตัวแทนของหมวดหมู่แผนภูมิ
## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| [getUseCell()](#getUseCell--) | ถ้าเป็น true แล้วคุณสมบัติ AsCell จะเป็นค่าจริง. |
| [getAsCell()](#getAsCell--) | ส่งกลับหรือกำหนดอ็อบเจกต์ IChartDataCell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | ส่งกลับหรือกำหนดอ็อบเจกต์ IChartDataCell. |
| [getAsLiteral()](#getAsLiteral--) | ส่งกลับหรือกำหนด AsLiteral หาก UseCell เป็น false. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | ส่งกลับหรือกำหนด AsLiteral หาก UseCell เป็น false. |
| [getValue()](#getValue--) | ถ้า UseCell เป็น true แล้วคุณสมบัตินี้จะเป็นตัวแทนของคุณสมบัติ AsCell.Value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | ถ้า UseCell เป็น true แล้วคุณสมบัตินี้จะเป็นตัวแทนของคุณสมบัติ AsCell.Value. |
| [getCachedValue()](#getCachedValue--) | ดึงค่าที่แคชของหมวดหมู่แผนภูมิ. |
| [getGroupingLevels()](#getGroupingLevels--) | คอนเทนเนอร์ที่จัดการค่าของระดับการจัดกลุ่มหมวดหมู่แผนภูมิ. |
| [remove()](#remove--) | ลบหมวดหมู่ออกจากแผนภูมิ. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```


ถ้าเป็น true แล้วคุณสมบัติ AsCell จะเป็นค่าจริง ในทางอื่น worksheet จะถูกใช้เพื่อจัดเก็บหมวดหมู่ (กรณีนี้สนับสนุนหมวดหมู่หลายระดับ) หากเป็น false แล้วคุณสมบัติ AsLiteral จะเป็นค่าจริง ในทางอื่น worksheet จะไม่ถูกใช้เพื่อจัดเก็บหมวดหมู่ (และกรณีนี้ไม่สนับสนุนหมวดหมู่หลายระดับ) บูลีนอ่านเท่านั้น.

--------------------

เพื่อเปลี่ยนค่าของคุณสมบัตินี้ (สำหรับทุกหมวดหมู่ในคอลเลกชัน) ให้ตั้งค่ใหม่ให้กับคุณสมบัติ [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--).

**คืนค่า:**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```


ส่งกลับหรือกำหนดอ็อบเจกต์ IChartDataCell หากหมวดหมู่เป็นหลายระดับจะใช้ IChartDataCell สำหรับระดับ "0". อ่าน/เขียน [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**คืนค่า:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```


ส่งกลับหรือกำหนดอ็อบเจกต์ IChartDataCell หากหมวดหมู่เป็นหลายระดับจะใช้ IChartDataCell สำหรับระดับ "0". อ่าน/เขียน [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```


ส่งกลับหรือกำหนด AsLiteral หาก UseCell เป็น false. อ่าน/เขียน Object.

**คืนค่า:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```


ส่งกลับหรือกำหนด AsLiteral หาก UseCell เป็น false. อ่าน/เขียน Object.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```


ถ้า UseCell เป็น true แล้วคุณสมบัตินี้จะเป็นตัวแทนของคุณสมบัติ AsCell.Value หาก UseCell เป็น false แล้วคุณสมบัตินี้จะเป็นตัวแทนของคุณสมบัติ AsLiteral. อ่าน/เขียน Object.

**คืนค่า:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


ถ้า UseCell เป็น true แล้วคุณสมบัตินี้จะเป็นตัวแทนของคุณสมบัติ AsCell.Value หาก UseCell เป็น false แล้วคุณสมบัตินี้จะเป็นตัวแทนของคุณสมบัติ AsLiteral. อ่าน/เขียน Object.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.Object |  |

### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
```


ดึงค่าที่แคชของหมวดหมู่แผนภูมิ. อ่านเท่านั้น [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
> 
>      // พิมพ์ค่าที่แคชทั้งหมดของหมวดหมู่แผนภูมิ.
>      for (IChartCategory category : chart.getChartData().getCategories())
>          System.out.println(category.getCachedValue().toString());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```


คอนเทนเนอร์ที่จัดการค่ของระดับการจัดกลุ่มหมวดหมู่แผนภูมิ. หมวดหมู่หลายระดับประกอบด้วยระดับการจัดกลุ่มมากกว่าหนึ่งระดับ. การจัดลำดับระดับการจัดกลุ่มเริ่มจากศูนย์. อ่านเท่านั้น [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**คืนค่า:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```


ลบหมวดหมู่ออกจากแผนภูมิ.