---
title: Paragraph
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นตัวแทนของย่อหน้าข้อความ
type: docs
url: /th/com.aspose.slides/paragraph/
---
**การสืบทอด:**
java.lang.Object

**ทุกอินเทอร์เฟซที่ทำการ Implement:**
[com.aspose.slides.IParagraph](../../com.aspose.slides/iparagraph), com.aspose.slides.IDOMObject
```
public final class Paragraph implements IParagraph, IDOMObject
```

แสดงย่อหน้าข้อความหนึ่ง.

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [Paragraph()](#Paragraph--) | สร้างอินสแตนซ์ใหม่ของคลาส Paragraph ด้วยคุณสมบัติปริยาย |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | คอนสตรัคเตอร์คัดลอกที่สร้างอินสแตนซ์ใหม่ของคลาส Paragraph |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getPortions()](#getPortions--) | ส่งคืนคอลเลกชันของส่วนข้อความ |
| [getParagraphFormat()](#getParagraphFormat--) | ส่งคืนอ็อบเจกต์การจัดรูปแบบสำหรับย่อหน้านี้ |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | รวมรันที่มีการจัดรูปแบบเดียวกัน |
| [getText()](#getText--) | รับหรือกำหนดข้อความธรรมดาของย่อหน้า |
| [setText(String value)](#setText-java.lang.String-) | รับหรือกำหนดข้อความธรรมดของย่อหน้า |
| [getRect()](#getRect--) | รับพิกัดของสี่เหลี่ยมที่ขอบเขตย่อหน้า |
| [getLinesCount()](#getLinesCount--) | รับจำนวนบรรทัดในย่อหน้า |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | ระบุคุณสมบัติของ portion ที่จะใช้หากมีการแทรก portion อื่นหลังจากส่วนสุดท้าย |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | ระบุคุณสมบัติของ portion ที่จะใช้หากมีการแทรก portion อื่นหลังจากส่วนสุดท้าย |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | ส่งคืนสไลด์แม่ของย่อหน้า |
| [getPresentation()](#getPresentation--) | ส่งคืนการนำเสนอแม่ของย่อหน้า |

### Paragraph() {#Paragraph--}
```
public Paragraph()
```

สร้างอินสแตนซ์ใหม่ของคลาส Paragraph ด้วยคุณสมบัติปริยาย

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```

คอนสตรัคเตอร์คัดลอกที่สร้างอินสแตนซ์ใหม่ของคลาส Paragraph

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) |  |

### getPortions() {#getPortions--}
```
public final IPortionCollection getPortions()
```

ส่งคืนคอลเลกชันของส่วนข้อความ. อ่านอย่างเดียว [IPortionCollection](../../com.aspose.slides/iportioncollection).

**ส่งคืน:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```

ส่งคืนอ็อบเจกต์การจัดรูปแบบสำหรับย่อหน้านี้. อ่านอย่างเดียว [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

--------------------

อ็อบเจกต์การจัดรูปแบบประกอบด้วยพารามิเตอร์การจัดรูปแบบที่กำหนดไว้สำหรับย่อหน้าปัจจุบันเท่านั้น, ข้อมูลที่สืบทอดจะไม่ถูกนำมาใช้.

เพื่อให้ได้ค่าที่มีผลรวมถึงค่าที่สืบทอด ให้ใช้เมธอด [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective).

**ส่งคืน:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

รวมรันที่มีการจัดรูปแบบเดียวกัน.

### getText() {#getText--}
```
public final String getText()
```

รับหรือกำหนดข้อความธรรมดของย่อหน้า. อ่าน/เขียน String.

ค่า: ข้อความ.

**ส่งคืน:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

รับหรือกำหนดข้อความธรรมดของย่อหน้า. อ่าน/เขียน String.

ค่า: ข้อความ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public final RectF getRect()
```

รับพิกัดของสี่เหลี่ยมที่ขอบเขตย่อหน้า. สี่เหลี่ยมนี้รวมทุกบรรทัดของข้อความในย่อหน้า, รวมถึงบรรทัดที่ว่างด้วย.

**ส่งคืน:**
android.graphics.RectF
### getLinesCount() {#getLinesCount--}
```
public final int getLinesCount()
```

รับจำนวนบรรทัดในย่อหน้า.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      IParagraph para = ashp.getTextFrame().getParagraphs().get_Item(0);
>      IPortion portion = para.getPortions().get_Item(0);
>      portion.setText("Aspose Paragraph GetLinesCount() Example");
>      System.out.println("Lines Count = " + para.getLinesCount());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**ส่งคืน:**
int - จำนวนบรรทัดในย่อหน้า
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```

ระบุคุณสมบัติของ portion ที่จะใช้หากมีการแทรก portion อื่นหลังจากส่วนสุดท้าย.

**ส่งคืน:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```

ระบุคุณสมบัติของ portion ที่จะใช้หากมีการแทรก portion อื่นหลังจากส่วนสุดท้าย.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

ส่งคืนอ็อบเจกต์ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**ส่งคืน:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

ส่งคืนสไลด์แม่ของย่อหน้า. อ่านอย่างเดียว [BaseSlide](../../com.aspose.slides/baseslide).

**ส่งคืน:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ส่งคืนการนำเสนอแม่ของย่อหน้า. อ่านอย่างเดียว [IPresentation](../../com.aspose.slides/ipresentation).

**ส่งคืน:**
[IPresentation](../../com.aspose.slides/ipresentation)