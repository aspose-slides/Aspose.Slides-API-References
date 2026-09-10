---
title: IParagraph
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงถึงย่อหน้าของข้อความ.
type: docs
url: /th/com.aspose.slides/iparagraph/
---
**อินเตอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

แสดงถึงย่อหน้าของข้อความ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getPortions()](#getPortions--) | คืนคอลเลกชันของส่วนข้อความ. |
| [getParagraphFormat()](#getParagraphFormat--) | คืนอ็อบเจ็กต์การจัดรูปแบบสำหรับย่อหน้านี้. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | รวมรันที่มีการจัดรูปแบบเดียวกัน. |
| [getText()](#getText--) | รับหรือกำหนดข้อความธรรมดาของย่อหน้า. |
| [setText(String value)](#setText-java.lang.String-) | รับหรือกำหนดข้อความธรรมดของย่อหน้า. |
| [getRect()](#getRect--) | รับพิกัดของสี่เหลี่ยมที่ครอบย่อหน้า. |
| [getLinesCount()](#getLinesCount--) | รับจำนวนบรรทัดในย่อหน้า. |
| [getImage()](#getImage--) | คืนรูปภาพของย่อหน้า. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | คืนรูปภาพของย่อหน้าด้วยสเกลที่ระบุ. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | ระบุคุณสมบัติของส่วนที่จะใช้หากมีการแทรกส่วนอื่นหลังส่วนสุดท้าย. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | ระบุคุณสมบัติของส่วนที่จะใช้หากมีการแทรกส่วนอื่นหลังส่วนสุดท้าย. |
### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```

คืนคอลเลกชันของส่วนข้อความ. อ่านอย่างเดียว [IPortionCollection](../../com.aspose.slides/iportioncollection).

**คืนค่า:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```

คืนอ็อบเจ็กต์การจัดรูปแบบสำหรับย่อหน้านี้. อ่านอย่างเดียว [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**คืนค่า:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

รวมรันที่มีการจัดรูปแบบเดียวกัน.
### getText() {#getText--}
```
public abstract String getText()
```

รับหรือกำหนดข้อความธรรมดของย่อหน้า. อ่าน/เขียน String.

ค่า: ข้อความ.

**คืนค่า:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

รับหรือกำหนดข้อความธรรมดของย่อหน้า. อ่าน/เขียน String.

ค่า: ข้อความ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |
### getRect() {#getRect--}
```
public abstract RectF getRect()
```

รับพิกัดของสี่เหลี่ยมที่ครอบย่อหน้า. สี่เหลี่ยมรวมบรรทัดทั้งหมดของข้อความในย่อหน้า, รวมถึงบรรทัดว่างด้วย.

**คืนค่า:**
android.graphics.RectF - สี่เหลี่ยมที่ครอบย่อหน้า android.graphics.RectF
### getLinesCount() {#getLinesCount--}
```
public abstract int getLinesCount()
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

**คืนค่า:**
int - จำนวนบรรทัดในย่อหน้า
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

คืนรูปภาพของย่อหน้า.

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

**คืนค่า:**
[IImage](../../com.aspose.slides/iimage) - ภาพที่มีย่อหน้าที่เรนเดอร์ไว้, หรือ null หากไม่พบย่อหน้าในคอลเลกชันแม่, ไม่มีขอบเขตการเรนเดอร์ที่ถูกต้อง, หรือเกิดข้อผิดพลาดขณะเรนเดอร์ภาพ.
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```

คืนรูปภาพของย่อหน้าด้วยสเกลที่ระบุ.

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
| scaleX | float | ปัจจัยสเกลแนวนอนที่ใช้กับรูปภาพย่อหน้า. |
| scaleY | float | ปัจจัยสเกลแนวตั้งที่ใช้กับรูปภาพย่อหน้า. |

**คืนค่า:**
[IImage](../../com.aspose.slides/iimage) - ภาพที่มีย่อหน้าที่เรนเดอร์ไว้, หรือ null หากไม่พบย่อหน้าในคอลเลกชันแม่, ไม่มีขอบเขตการเรนเดอร์ที่ถูกต้อง, หรือเกิดข้อผิดพลาดขณะเรนเดอร์ภาพ.
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public abstract IPortionFormat getEndParagraphPortionFormat()
```

ระบุคุณสมบัติของส่วนที่จะใช้หากมีการแทรกส่วนอื่นหลังส่วนสุดท้าย.

**คืนค่า:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```

ระบุคุณสมบัติของส่วนที่จะใช้หากมีการแทรกส่วนอื่นหลังส่วนสุดท้าย.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |