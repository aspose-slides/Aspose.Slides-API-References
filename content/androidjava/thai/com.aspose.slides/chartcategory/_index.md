---
title: ChartCategory
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงถึงหมวดหมู่ของแผนภูมิ.
type: docs
url: /th/com.aspose.slides/chartcategory/
---
**การสืบทอด:**  
java.lang.Object

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**  
[com.aspose.slides.IChartCategory](../../com.aspose.slides/ichartcategory), com.aspose.slides.IDOMObject  
```
public class ChartCategory implements IChartCategory, IDOMObject
```

แสดงถึงหมวดหมู่ของแผนภูมิ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getUseCell()](#getUseCell--) | หากเป็น true แล้วคุณสมบัติ AsCell จะเป็นค่าที่ใช้งานจริง. |
| [getAsCell()](#getAsCell--) | คืนค่า หรือกำหนดอ็อบเจกต์ IChartDataCell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | คืนค่า หรือกำหนดอ็อบเจกต์ IChartDataCell. |
| [getAsLiteral()](#getAsLiteral--) | คืนค่า หรือกำหนดอ็อบเจกต์ AsLiteral. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | คืนค่า หรือกำหนดอ็อบเจกต์ AsLiteral. |
| [getValue()](#getValue--) | หาก UseCell เป็น true แล้วคุณสมบัตินี้จะแทนคุณสมบัติ AsCell.Value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | หาก UseCell เป็น true แล้วคุณสมบัตินี้จะแทนคุณสมบัติ AsCell.Value. |
| [getGroupingLevels()](#getGroupingLevels--) | คอนเทนเนอร์ที่จัดการค่าของระดับการจัดกลุ่มหมวดหมู่แผนภูมิ. |
| [remove()](#remove--) | ลบหมวดหมู่ออกจากแผนภูมิ. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```

หากเป็น true แล้วคุณสมบัติ AsCell จะเป็นค่าที่ใช้งานจริง ในกรณีอื่นหมายความว่า worksheet ถูกใช้เพื่อเก็บหมวดหมู่ (กรณีนี้สนับสนุนหมวดหมู่หลายระดับ) หากเป็น false แล้วคุณสมบัติ AsLiteral จะเป็นค่าที่ใช้งานจริง ในกรณีอื่นหมายความว่า worksheet ไม่ได้ถูกใช้เพื่อเก็บหมวดหมู่ (และกรณีนี้ไม่สนับสนุนหมวดหมู่หลายระดับ) บูลีนแบบอ่านอย่างเดียว.

--------------------

เพื่อเปลี่ยนค่าของคุณสมบัตินี้ (สำหรับหมวดหมู่ทั้งหมดในคอลเลกชัน) ตั้งค่าที่ใหม่ให้กับคุณสมบัติ ChartCategoryCollection.UseCells

**คืนค่า:**  
boolean

### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

คืนค่า หรือกำหนดอ็อบเจกต์ IChartDataCell. หากหมวดหมู่เป็นหลายระดับจะใช้อ็อบเจกต์ IChartDataCell สำหรับระดับ "0". อ่าน/เขียน [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**คืนค่า:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

คืนค่า หรือกำหนดอ็อบเจกต์ IChartDataCell. หากหมวดหมู่เป็นหลายระดับจะใช้อ็อบเจกต์ IChartDataCell สำหรับระดับ "0". อ่าน/เขียน [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```

คืนค่า หรือกำหนดอ็อบเจกต์ AsLiteral. อ่าน/เขียน Object.

**คืนค่า:**  
java.lang.Object

### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public final void setAsLiteral(Object value)
```

คืนค่า หรือกำหนดอ็อบเจกต์ AsLiteral. อ่าน/เขียน Object.

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

หาก UseCell เป็น true แล้วคุณสมบัตินี้จะแทนคุณสมบัติ AsCell.Value. หาก UseCell เป็น false แล้วคุณสมบัตินี้จะแทนคุณสมบัติ AsLiteral. อ่าน/เขียน Object.

**คืนค่า:**  
java.lang.Object

### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

หาก UseCell เป็น true แล้วคุณสมบัตินี้จะแทนคุณสมบัติ AsCell.Value. หาก UseCell เป็น false แล้วคุณสมบัตินี้จะแทนคุณสมบัติ AsLiteral. อ่าน/เขียน Object.

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public final IChartCategoryLevelsManager getGroupingLevels()
```

คอนเทนเนอร์ที่จัดการค่าของระดับการจัดกลุ่มหมวดหมู่แผนภูมิ. หมวดหมู่หลายระดับมีมากกว่าหนึ่งระดับการจัดกลุ่ม. การทำดัชนีระดับการจัดกลุ่มเริ่มจากศูนย์. แบบอ่านอย่างเดียว [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

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

คืนค่าอ็อบเจกต์ Parent_Immediate. แบบอ่านอย่างเดียว IDOMObject.

**คืนค่า:**  
com.aspose.slides.IDOMObject