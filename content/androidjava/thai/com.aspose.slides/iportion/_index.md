---
title: IPortion
second_title: Aspose.Slides สำหรับ Android ผ่านเอกสารอ้างอิง API ของ Java
description: แสดงส่วนของข้อความภายในย่อหน้าข้อความ.
type: docs
url: /th/com.aspose.slides/iportion/
---
**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IPortion extends ISlideComponent
```

แสดงส่วนของข้อความภายในย่อหน้าข้อความ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | คืนอ็อบเจ็กต์การจัดรูปแบบที่มีคุณสมบัติการจัดรูปแบบที่ตั้งค่าโดยตรงของส่วนข้อความโดยไม่มีการสืบทอดใด ๆ |
| [getText()](#getText--) | รับหรือกำหนดข้อความธรรมดาของส่วน |
| [setText(String value)](#setText-java.lang.String-) | รับหรือกำหนดข้อความธรรมดาของส่วน |
| [getField()](#getField--) | คืนฟิลด์ของส่วนนี้ |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | แปลงส่วนนี้เป็นฟิลด์ที่อัปเดตอัตโนมัติ |
| [addField(String internalString)](#addField-java.lang.String-) | แปลงส่วนนี้เป็นฟิลด์ที่อัปเดตอัตโนมัติ |
| [removeField()](#removeField--) | แปลงส่วนฟิลด์นี้เป็นส่วนแบบธรรมดา |
| [getRect()](#getRect--) | รับพิกัดของสี่เหลี่ยมที่ล้อมรอบส่วน |
| [getCoordinates()](#getCoordinates--) | รับพิกัดของจุดเริ่มต้นของส่วน |

### getPortionFormat() {#getPortionFormat--}
```
public abstract IPortionFormat getPortionFormat()
```

คืนอ็อบเจ็กต์การจัดรูปแบบที่มีคุณสมบัติการจัดรูปแบบที่ตั้งค่าโดยตรงของส่วนข้อความโดยไม่มีการสืบทอดใด ๆ อ่านอย่างเดียว [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

อ็อบเจ็กต์การจัดรูปแบบมีพารามิเตอร์การจัดรูปแบบที่กำหนดไว้สำหรับส่วนปัจจุบันเท่านั้น ไม่ได้ใช้ข้อมูลที่สืบทอด

เพื่อให้ได้ค่าที่มีผลรวมถึงค่าที่สืบทอด ให้ใช้เมธอด [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective).

**คืนค่า:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getText() {#getText--}
```
public abstract String getText()
```

รับหรือกำหนดข้อความธรรมดาของส่วน อ่าน/เขียน String.

ค่า: ข้อความ.

**คืนค่า:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

รับหรือกำหนดข้อความธรรมดาของส่วน อ่าน/เขียน String.

ค่า: ข้อความ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public abstract IField getField()
```

คืนฟิลด์ของส่วนนี้ อ่านอย่างเดียว [IField](../../com.aspose.slides/ifield).

**คืนค่า:**
[IField](../../com.aspose.slides/ifield)

### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public abstract void addField(IFieldType fieldType)
```

แปลงส่วนนี้เป็นฟิลด์ที่อัปเดตอัตโนมัติ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) | ประเภทของฟิลด์ [IFieldType](../../com.aspose.slides/ifieldtype) |

### addField(String internalString) {#addField-java.lang.String-}
```
public abstract void addField(String internalString)
```

แปลงส่วนนี้เป็นฟิลด์ที่อัปเดตอัตโนมัติ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| internalString | java.lang.String | ชื่อภายในของ FieldTypeEx String |

### removeField() {#removeField--}
```
public abstract void removeField()
```

แปลงส่วนฟิลด์นี้เป็นส่วนแบบธรรมดา.

### getRect() {#getRect--}
```
public abstract RectF getRect()
```

รับพิกัดของสี่เหลี่ยมที่ล้อมรอบส่วน สี่เหลี่ยมนี้รวมทุกบรรทัดของข้อความในส่วนรวมถึงบรรทัดว่างด้วย.

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
>  	android.graphics.RectF rect = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(1).getRect();
>  	...
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**
android.graphics.RectF - สี่เหลี่ยมที่ล้อมรอบส่วน android.graphics.RectF

### getCoordinates() {#getCoordinates--}
```
public abstract PointF getCoordinates()
```

รับพิกัดของจุดเริ่มต้นของส่วน พิกัด X ของจุดแสดงตำแหน่งเริ่มต้นของส่วนตั้งแต่ตัวอักษรแรกรวมถึงการเว้นด้านซ้าย พิกัด Y รวมถึงการเว้นด้านบน

**คืนค่า:**
android.graphics.PointF - พิกัดของจุดเริ่มต้นของส่วน android.graphics.PointF