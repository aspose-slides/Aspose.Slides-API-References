---
title: Portion
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API Java
description: แสดงส่วนของข้อความภายในย่อหน้าข้อความ.
type: docs
url: /th/com.aspose.slides/portion/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IPortion](../../com.aspose.slides/iportion), com.aspose.slides.IDOMObject
```
public class Portion implements IPortion, IDOMObject
```

แสดงส่วนของข้อความภายในย่อหน้าข้อความ.
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [Portion()](#Portion--) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส Portion. |
| [Portion(String str)](#Portion-java.lang.String-) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส Portion. |
| [Portion(Portion portion)](#Portion-com.aspose.slides.Portion-) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส Portion. |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | คืนค่าอ็อบเจ็กต์การจัดรูปแบบที่บรรจุคุณลักษณะการจัดรูปแบบที่ตั้งค่าโดยเฉพาะของส่วนข้อความโดยไม่มีการสืบทอดใดๆ ถูกนำมาใช้. |
| [getText()](#getText--) | รับหรือกำหนดข้อความธรรมดาของส่วน. |
| [setText(String value)](#setText-java.lang.String-) | รับหรือกำหนดข้อความธรรมดาของส่วน. |
| [getField()](#getField--) | คืนค่า ฟิลด์ของส่วนนี้. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | แปลงส่วนนี้เป็นฟิลด์ที่อัปเดตโดยอัตโนมัติ. |
| [addField(String internalString)](#addField-java.lang.String-) | แปลงส่วนนี้เป็นฟิลด์ที่อัปเดตโดยอัตโนมัติ. |
| [removeField()](#removeField--) | แปลงส่วนฟิลด์นี้เป็นส่วนธรรมดา. |
| [getRect()](#getRect--) | รับพิกัดของสี่เหลี่ยมที่ล้อมรอบส่วน. |
| [getCoordinates()](#getCoordinates--) | รับพิกัดของจุดเริ่มต้นของส่วน. |
| [getSlide()](#getSlide--) | คืนค่าสไลด์แม่ของข้อความ. |
| [getPresentation()](#getPresentation--) | คืนค่าการนำเสนอแม่ของข้อความ. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### Portion() {#Portion--}
```
public Portion()
```

เริ่มต้นอินสแตนซ์ใหม่ของคลาส Portion.

### Portion(String str) {#Portion-java.lang.String-}
```
public Portion(String str)
```

เริ่มต้นอินสแตนซ์ใหม่ของคลาส Portion.

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| str | java.lang.String |  |

### Portion(Portion portion) {#Portion-com.aspose.slides.Portion-}
```
public Portion(Portion portion)
```

เริ่มต้นอินสแตนซ์ใหม่ของคลาส Portion.

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) |  |

### getPortionFormat() {#getPortionFormat--}
```
public final IPortionFormat getPortionFormat()
```

คืนค่าอ็อบเจ็กต์การจัดรูปแบบที่บรรจุคุณลักษณะการจัดรูปแบบที่ตั้งค่าโดยเฉพาะของส่วนข้อความโดยไม่มีการสืบทอดใดๆ ถูกนำมาใช้ อ่านอย่างเดียว [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

อ็อบเจ็กต์การจัดรูปแบบนี้บรรจุพารามิเตอร์การจัดรูปแบบที่กำหนดไว้สำหรับส่วนปัจจุบันเท่านั้น ข้อมูลที่สืบทอดจะไม่ถูกนำมาใช้.

เพื่อให้ได้ค่าที่มีผลรวมถึงค่าที่สืบทอด ให้ใช้เมธอด [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective).

**คืนค่า:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getText() {#getText--}
```
public final String getText()
```

รับหรือกำหนดข้อความธรรมดาของส่วน อ่าน/เขียน String.

ค่า: ข้อความ.

**คืนค่า:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

รับหรือกำหนดข้อความธรรมดของส่วน อ่าน/เขียน String.

ค่า: ข้อความ.

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public final IField getField()
```

คืนค่า ฟิลด์ของส่วนนี้ อ่านอย่างเดียว [IField](../../com.aspose.slides/ifield).

**คืนค่า:**
[IField](../../com.aspose.slides/ifield)

### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public final void addField(IFieldType fieldType)
```

แปลงส่วนนี้เป็นฟิลด์ที่อัปเดตโดยอัตโนมัติ.

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### addField(String internalString) {#addField-java.lang.String-}
```
public final void addField(String internalString)
```

แปลงส่วนนี้เป็นฟิลด์ที่อัปเดตโดยอัตโนมัติ.

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| internalString | java.lang.String | ชื่อภายในของ FieldType. |

### removeField() {#removeField--}
```
public final void removeField()
```

แปลงส่วนฟิลด์นี้เป็นส่วนธรรมดา.

### getRect() {#getRect--}
```
public final RectF getRect()
```

รับพิกัดของสี่เหลี่ยมที่ล้อมรอบส่วน. สี่เหลี่ยมรวมบรรทัดข้อความทั้งหมดในส่วน รวมถึงบรรทัดว่างด้วย.

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
>  	android.graphics.RectF rect = shape.getTextFrame().getParagraphs().get_Item(1).getPortions().get_Item(1).getRect();
>  	...
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**
android.graphics.RectF

### getCoordinates() {#getCoordinates--}
```
public final PointF getCoordinates()
```

รับพิกัดของจุดเริ่มต้นของส่วน. พิกัด X ของจุดแสดงจุดเริ่มต้นของส่วนตั้งแต่ตัวอักษรแรกรวมถึง left side bearing. พิกัด Y รวมถึง top side bearing.

**คืนค่า:**
android.graphics.PointF

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

คืนค่าสไลด์แม่ของข้อความ อ่านอย่างเดียว [BaseSlide](../../com.aspose.slides/baseslide).

**คืนค่า:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

คืนค่าการนำเสนอแม่ของข้อความ อ่านอย่างเดียว [IPresentation](../../com.aspose.slides/ipresentation).

**คืนค่า:**
[IPresentation](../../com.aspose.slides/ipresentation)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

คืนค่าอ็อบเจ็กต์ Parent_Immediate อ่านอย่างเดียว IDOMObject.

**คืนค่า:**
com.aspose.slides.IDOMObject