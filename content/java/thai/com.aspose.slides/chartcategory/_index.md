---
title: ChartCategory
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงถึงหมวดหมู่ของแผนภูมิ.
type: docs
url: /th/com.aspose.slides/chartcategory/
---
**การสืบทอด:**  
java.lang.Object

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**  
[com.aspose.slides.IChartCategory](../../com.aspose.slides/ichartcategory), com.aspose.slides.IDOMObject  
```
public class ChartCategory implements IChartCategory, IDOMObject
```

แสดงหมวดหมู่ของแผนภูมิ.  
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getUseCell()](#getUseCell--) | ถ้าเป็นจริงแล้วคุณสมบัติ AsCell จะเป็นค่าจริง. |
| [getAsCell()](#getAsCell--) | ส่งคืนหรือกำหนดวัตถุ IChartDataCell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | ส่งคืนหรือกำหนดวัตถุ IChartDataCell. |
| [getAsLiteral()](#getAsLiteral--) | ส่งคืนหรือกำหนดวัตถุ AsLiteral. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | ส่งคืนหรือกำหนดวัตถุ AsLiteral. |
| [getValue()](#getValue--) | ถ้า UseCell เป็นจริงแล้วคุณสมบัตินี้จะแทนคุณสมบัติ AsCell.Value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | ถ้า UseCell เป็นจริงแล้วคุณสมบัตินี้จะแทนคุณสมบัติ AsCell.Value. |
| [getGroupingLevels()](#getGroupingLevels--) | คอนเทนเนอร์ที่จัดการค่าของระดับการจัดกลุ่มหมวดหมู่ของแผนภูมิ. |
| [remove()](#remove--) | ลบหมวดหมู่ออกจากแผนภูมิ. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```

ถ้าเป็นจริงแล้วคุณสมบัติ AsCell จะเป็นค่าจริง. อีกอย่าง, แผ่นงานถูกใช้สำหรับเก็บหมวดหมู่ (กรณีนี้สนับสนุนหมวดหมู่หลายระดับ). ถ้าเป็น false แล้วคุณสมบัติ AsLiteral จะเป็นค่าจริง. อีกอย่าง, แผ่นงานไม่ได้ถูกใช้สำหรับเก็บหมวดหมู่ (และกรณีนี้ไม่สนับสนุนหมวดหมู่หลายระดับ). อ่านอย่างเดียว boolean.

--------------------

เพื่อเปลี่ยนค่าของคุณสมบัตินี้ (สำหรับหมวดหมู่ทั้งหมดในคอลเลกชัน) ตั้งค่ใหม่ให้กับคุณสมบัติ ChartCategoryCollection.UseCells.

**คืนค่า:**  
boolean

### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

ส่งคืนหรือกำหนดวัตถุ IChartDataCell. ถ้าหมวดหมู่เป็นหลายระดับแล้วจะใช้วัตถุ IChartDataCell สำหรับระดับ "0". อ่าน/เขียน [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**คืนค่า:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

ส่งคืนหรือกำหนดวัตถุ IChartDataCell. ถ้าหมวดหมู่เป็นหลายระดับแล้วจะใช้วัตถุ IChartDataCell สำหรับระดับ "0". อ่าน/เขียน [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```

ส่งคืนหรือกำหนดวัตถุ AsLiteral. อ่าน/เขียน Object.

**คืนค่า:**  
java.lang.Object

### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public final void setAsLiteral(Object value)
```

ส่งคืนหรือกำหนดวัตถุ AsLiteral. อ่าน/เขียน Object.

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

ถ้า UseCell เป็นจริงแล้วคุณสมบัตินี้จะแทนคุณสมบัติ AsCell.Value. ถ้า UseCell เป็น false แล้วคุณสมบัตินี้จะแทนคุณสมบัติ AsLiteral. อ่าน/เขียน Object.

**คืนค่า:**  
java.lang.Object

### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

ถ้า UseCell เป็นจริงแล้วคุณสมบัตินี้จะแทนคุณสมบัติ AsCell.Value. ถ้า UseCell เป็น false แล้วคุณสมบัตินี้จะแทนคุณสมบัติ AsLiteral. อ่าน/เขียน Object.

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public final IChartCategoryLevelsManager getGroupingLevels()
```

คอนเทนเนอร์ที่จัดการค่าของระดับการจัดกลุ่มหมวดหมู่ของแผนภูมิ. หมวดหมู่หลายระดับจะมีมากกว่าหนึ่งระดับการจัดกลุ่ม. การจัดลำดับระดับการจัดกลุ่มใช้เลขศูนย์เป็นฐาน. อ่านอย่างเดียว [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**คืนค่า:**  
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)

### remove() {#remove--}
```
public final void remove()
```

ลบหมวดหมู่ออกจากแผนภูมิ.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

ส่งคืนวัตถุ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**คืนค่า:**  
com.aspose.slides.IDOMObject