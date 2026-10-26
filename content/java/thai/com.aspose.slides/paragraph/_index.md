---
title: Paragraph
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงถึงย่อหน้าของข้อความ.
type: docs
url: /th/com.aspose.slides/paragraph/
---
**สืบทอด:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IParagraph](../../com.aspose.slides/iparagraph), com.aspose.slides.IDOMObject  
```
public final class Paragraph implements IParagraph, IDOMObject
```

แสดงถึงย่อหน้าของข้อความ.

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [Paragraph()](#Paragraph--) | เริ่มต้นอ็อบเจกต์ใหม่ของคลาส Paragraph ด้วยคุณสมบัติมาตรฐาน |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | คอนสตรัคเตอร์สำเนาที่เริ่มต้นอ็อบเจกต์ใหม่ของคลาส Paragraph |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getPortions()](#getPortions--) | ส่งคืนคอลเลกชันของส่วนข้อความ |
| [getParagraphFormat()](#getParagraphFormat--) | ส่งคืนอ็อบเจกต์การจัดรูปแบบสำหรับย่อหน้านี้ |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | รวมรันที่มีการจัดรูปแบบเดียวกัน |
| [getText()](#getText--) | รับหรือกำหนดข้อความธรรมดาของย่อหน้า |
| [setText(String value)](#setText-java.lang.String-) | รับหรือกำหนดข้อความธรรมดของย่อหน้า |
| [getRect()](#getRect--) | รับพิกัดของสี่เหลี่ยมที่ล้อมรอบย่อหน้า |
| [getLinesCount()](#getLinesCount--) | รับจำนวนบรรทัดในย่อหน้า |
| [getImage()](#getImage--) | ส่งคืนรูปภาพของย่อหน้า |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | ส่งคืนรูปภาพของย่อหน้าที่มีสเกลตามที่ระบุ |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | ระบุคุณสมบัติของส่วนที่จะใช้หากมีการแทรกส่วนใหม่หลังส่วนสุดท้าย |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | ระบุคุณสมบัติของส่วนที่จะใช้หากมีการแทรกส่วนใหม่หลังส่วนสุดท้าย |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | ส่งคืนสไลด์แม่ของย่อหน้า |
| [getPresentation()](#getPresentation--) | ส่งคืนการนำเสนอแม่ของย่อหน้า |

### Paragraph() {#Paragraph--}
```
public Paragraph()
```

เริ่มต้นอ็อบเจกต์ใหม่ของคลาส Paragraph ด้วยคุณสมบัติมาตรฐาน

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```

คอนสตรัคเตอร์สำเนาที่เริ่มต้นอ็อบเจกต์ใหม่ของคลาส Paragraph

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

อ็อบเจกต์การจัดรูปแบบมีพารามิเตอร์การจัดรูปแบบที่กำหนดไว้สำหรับย่อหน้าเดียวนี้เท่านั้น, ข้อมูลที่สืบทอดไม่ได้ถูกนำมาใช้.

เพื่อให้ได้ค่าที่มีผลรวมถึงค่าที่สืบทอดใช้เมธอด [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective)

**ส่งคืน:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

รวมรันที่มีการจัดรูปแบบเดียวกัน

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
public final Rectangle2D.Float getRect()
```

รับพิกัดของสี่เหลี่ยมที่ล้อมรอบย่อหน้า. สี่เหลี่ยมนี้รวมบรรทัดทั้งหมดของข้อความในย่อหน้า, รวมถึงบรรทัดว่าง.

**ส่งคืน:**
java.awt.geom.Rectangle2D.Float

### getLinesCount() {#getLinesCount--}
```
public final int getLinesCount()
```

รับจำนวนบรรทัดในย่อหน้า

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

### getImage() {#getImage--}
```
public final IImage getImage()
```

ส่งคืนรูปภาพของย่อหน้า

--------------------

> ```
> The following example shows how to render a paragraph as an image:
>   
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(
>          ShapeType.Rectangle, 50, 50, 150, 50);
>      IParagraph paragraph = shape.getTextFrame().getParagraphs().get_Item(0);
>      paragraph.setText("Aspose Paragraph GetImage() Example");
>      IImage paragraphImage = paragraph.getImage();
>      try {
>          paragraphImage.save("paragraph.png");
>      } finally {
>          if (paragraphImage != null) paragraphImage.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**ส่งคืน:**
[IImage](../../com.aspose.slides/iimage) - รูปภาพที่มีการแสดงผลของย่อหน้า, หรือ null หากไม่พบย่อหน้าในคอลเลกชันแม่, ไม่มีขอบเขตการแสดงผลที่ถูกต้อง, หรือเกิดข้อผิดพลาดขณะเรนเดอร์รูปภาพ

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```

ส่งคืนรูปภาพของย่อหน้าที่มีสเกลตามที่ระบุ

--------------------

> ```
> The following example shows how to render each text box paragraph on a slide as an image with custom scaling:
>   
>  Presentation pres = new Presentation("sample.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      int shapeIndex = 0;
>      for (IShape shape : slide.getShapes())
>      {
>          shapeIndex++;
>          if (shape instanceof IAutoShape) {
>              IAutoShape autoShape = (IAutoShape)shape;
>              int paragraphIndex = 0;
>              for (IParagraph paragraph : autoShape.getTextFrame().getParagraphs())
>              {
>                  paragraphIndex++;
>                  IImage paragraphImage = paragraph.getImage(2f, 2f);
>                  try {
>                      if (paragraphImage != null)
>                          paragraphImage.save("shape"+shapeIndex+"_paragraph"+paragraphIndex+".png");
> 
>                  } finally {
>                      if (paragraphImage != null) paragraphImage.dispose();
>                  }
>              }
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| scaleX | float | ปัจจัยสเกลแนวนอนที่ใช้กับรูปภาพย่อหน้า |
| scaleY | float | ปัจจัยสเกลแนวตั้งที่ใช้กับรูปภาพย่อหน้า |

**ส่งคืน:**
[IImage](../../com.aspose.slides/iimage) - รูปภาพที่มีการแสดงผลของย่อหน้า, หรือ null หากไม่พบย่อหน้าในคอลเลกชันแม่, ไม่มีขอบเขตการแสดงผลที่ถูกต้อง, หรือเกิดข้อผิดพลาดขณะเรนเดอร์รูปภาพ

### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```

ระบุคุณสมบัติของส่วนที่จะใช้หากมีการแทรกส่วนใหม่หลังส่วนสุดท้าย

**ส่งคืน:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```

ระบุคุณสมบัติของส่วนที่จะใช้หากมีการแทรกส่วนใหม่หลังส่วนสุดท้าย

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