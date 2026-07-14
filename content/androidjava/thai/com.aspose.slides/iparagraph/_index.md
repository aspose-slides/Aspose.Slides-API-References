---
title: IParagraph
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงถึงย่อหน้าของข้อความ.
type: docs
url: /th/com.aspose.slides/iparagraph/
---
**ส่วนต่อประสานที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

แสดงถึงย่อหน้าของข้อความ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getPortions()](#getPortions--) | คืนคอลเลกชันของส่วนข้อความ. |
| [getParagraphFormat()](#getParagraphFormat--) | คืนอ็อบเจกต์การจัดรูปแบบสำหรับย่อหน้านี้. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | รวมรันที่มีการจัดรูปแบบเดียวกัน. |
| [getText()](#getText--) | รับหรือกำหนดข้อความแบบธรรมดาของย่อหน้า. |
| [setText(String value)](#setText-java.lang.String-) | รับหรือกำหนดข้อความแบบธรรมดของย่อหน้า. |
| [getRect()](#getRect--) | รับพิกัดของสี่เหลี่ยมที่ล้อมรอบย่อหน้า. |
| [getLinesCount()](#getLinesCount--) | รับจำนวนบรรทัดในย่อหน้า. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | กำหนดคุณสมบัติของส่วนที่จะใช้หากมีการแทรกส่วนอื่นหลังจากส่วนสุดท้าย. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | กำหนดคุณสมบัติของส่วนที่จะใช้หากมีการแทรกส่วนอื่นหลังจากส่วนสุดท้าย. |
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

คืนอ็อบเจกต์การจัดรูปแบบสำหรับย่อหน้านี้. อ่านอย่างเดียว [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

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

รับหรือกำหนดข้อความแบบธรรมดของย่อหน้า. อ่าน/เขียน String.

ค่า: ข้อความ.

**คืนค่า:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

รับหรือกำหนดข้อความแบบธรรมดของย่อหน้า. อ่าน/เขียน String.

ค่า: ข้อความ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public abstract RectF getRect()
```

รับพิกัดของสี่เหลี่ยมที่ล้อมรอบย่อหน้า. สี่เหลี่ยมนี้รวมบรรทัดข้อความทั้งหมดในย่อหน้า รวมถึงบรรทัดที่ว่างอยู่ด้วย.

**คืนค่า:**
android.graphics.RectF - สี่เหลี่ยมที่ล้อมรอบย่อหน้า android.graphics.RectF
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
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public abstract IPortionFormat getEndParagraphPortionFormat()
```

กำหนดคุณสมบัติของส่วนที่จะใช้หากมีการแทรกส่วนอื่นหลังจากส่วนสุดท้าย.

**คืนค่า:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```

กำหนดคุณสมบัติของส่วนที่จะใช้หากมีการแทรกส่วนอื่นหลังจากส่วนสุดท้าย.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |