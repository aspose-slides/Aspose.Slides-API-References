---
title: Portion
second_title: Aspose.Slides สำหรับ Java API Reference
description: แทนส่วนของข้อความภายในย่อหน้าข้อความ.
type: docs
url: /th/com.aspose.slides/portion/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IPortion](../../com.aspose.slides/iportion), com.aspose.slides.IDOMObject
```
public class Portion implements IPortion, IDOMObject
```

แทนส่วนของข้อความภายในย่อหน้าข้อความ.
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [Portion()](#Portion--) | สร้างอินสแตนซ์ใหม่ของ Portion คลาส. |
| [Portion(String str)](#Portion-java.lang.String-) | สร้างอินสแตนซ์ใหม่ของ Portion คลาส. |
| [Portion(Portion portion)](#Portion-com.aspose.slides.Portion-) | สร้างอินสแตนซ์ใหม่ของ Portion คลาส. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | ส่งคืนออบเจกต์การจัดรูปแบบที่มีคุณสมบัติการจัดรูปแบบที่ตั้งค่าอย่างชัดเจนของส่วนข้อความโดยไม่มีการสืบทอดใดๆ. |
| [getText()](#getText--) | ดึงหรือกำหนดข้อความธรรมดาของส่วน. |
| [setText(String value)](#setText-java.lang.String-) | ดึงหรือกำหนดข้อความธรรมดาของส่วน. |
| [getField()](#getField--) | ส่งคืนฟิลด์ของส่วนนี้. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | แปลงส่วนนี้ให้เป็นฟิลด์ที่อัปเดตอัตโนมัติ. |
| [addField(String internalString)](#addField-java.lang.String-) | แปลงส่วนนี้ให้เป็นฟิลด์ที่อัปเดตอัตโนมัติ. |
| [removeField()](#removeField--) | แปลงส่วนฟิลด์นี้เป็นส่วนธรรมดา. |
| [getRect()](#getRect--) | ดึงพิกัดของสี่เหลี่ยมที่ล้อมรอบส่วน. |
| [getCoordinates()](#getCoordinates--) | ดึงพิกัดของจุดเริ่มต้นของส่วน. |
| [getSlide()](#getSlide--) | ส่งคืนสไลด์แม่ของข้อความ. |
| [getPresentation()](#getPresentation--) | ส่งคืนการนำเสนอแม่ของข้อความ. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Portion() {#Portion--}
```
public Portion()
```

สร้างอินสแตนซ์ใหม่ของ Portion คลาส.

### Portion(String str) {#Portion-java.lang.String-}
```
public Portion(String str)
```

สร้างอินสแตนซ์ใหม่ของ Portion คลาส.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| str | java.lang.String |  |

### Portion(Portion portion) {#Portion-com.aspose.slides.Portion-}
```
public Portion(Portion portion)
```

สร้างอินสแตนซ์ใหม่ของ Portion คลาส.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) |  |

### getPortionFormat() {#getPortionFormat--}
```
public final IPortionFormat getPortionFormat()
```

ส่งคืนออบเจกต์การจัดรูปแบบที่มีคุณสมบัติการจัดรูปแบบที่ตั้งค่าอย่างชัดเจนของส่วนข้อความโดยไม่มีการสืบทอดใดๆ. อ่านอย่างเดียว [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

ออบเจกต์การจัดรูปแบบมีพารามิเตอร์การจัดรูปแบบที่กำหนดไว้สำหรับส่วนปัจจุบันเท่านั้น, ข้อมูลที่สืบทอดจะไม่ถูกนำมาใช้.

เพื่อให้ได้ค่าที่มีผลรวมถึงค่าที่สืบทอด ให้ใช้เมธอด [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective).

**ส่งคืน:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public final String getText()
```

ดึงหรือกำหนดข้อความธรรมดของส่วน. อ่าน/เขียน String.

ค่า: ข้อความ.

**ส่งคืน:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

ดึงหรือกำหนดข้อความธรรมดของส่วน. อ่าน/เขียน String.

ค่า: ข้อความ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public final IField getField()
```

ส่งคืนฟิลด์ของส่วนนี้. อ่านอย่างเดียว [IField](../../com.aspose.slides/ifield).

**ส่งคืน:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public final void addField(IFieldType fieldType)
```

แปลงส่วนนี้ให้เป็นฟิลด์ที่อัปเดตอัตโนมัติ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### addField(String internalString) {#addField-java.lang.String-}
```
public final void addField(String internalString)
```

แปลงส่วนนี้ให้เป็นฟิลด์ที่อัปเดตอัตโนมัติ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| internalString | java.lang.String | ชื่อภายในของ FieldType. |

### removeField() {#removeField--}
```
public final void removeField()
```

แปลงส่วนฟิลด์นี้เป็นส่วนธรรมดา.

### getRect() {#getRect--}
```
public final Rectangle2D.Float getRect()
```

ดึงพิกัดของสี่เหลี่ยมที่ล้อมรอบส่วน. สี่เหลี่ยมนี้รวมทุกบรรทัดของข้อความในส่วน, รวมถึงบรรทัดว่างด้วย.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try
>  {
>  	ISlide slide = pres.getSlides().get_Item(0);
>  	IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 200, 50);
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().clear();
>  	Portion portion0 = new Portion("Some text");
>  	Portion portion1 = new Portion("GetRect text");
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion0);
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion1);
>  	Rectangle2D.Float rect = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(1).getRect();
>  	...
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```


**ส่งคืน:**
java.awt.geom.Rectangle2D.Float
### getCoordinates() {#getCoordinates--}
```
public final Point2D.Float getCoordinates()
```

ดึงพิกัดของจุดเริ่มต้นของส่วน. พิกัด X ของจุดแสดงจุดเริ่มต้นของส่วนจากอักขระแรกรวมถึง left side bearing. พิกัด Y รวมถึง top side bearing.

**ส่งคืน:**
java.awt.geom.Point2D.Float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

ส่งคืนสไลด์แม่ของข้อความ. อ่านอย่างเดียว [BaseSlide](../../com.aspose.slides/baseslide).

**ส่งคืน:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ส่งคืนการนำเสนอแม่ของข้อความ. อ่านอย่างเดียว [IPresentation](../../com.aspose.slides/ipresentation).

**ส่งคืน:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

ส่งคืนอ็อบเจกต์ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**ส่งคืน:**
com.aspose.slides.IDOMObject