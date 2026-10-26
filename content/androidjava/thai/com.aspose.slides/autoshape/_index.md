---
title: AutoShape
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นตัวแทนของ AutoShape.
type: docs
url: /th/com.aspose.slides/autoshape/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IAutoShape](../../com.aspose.slides/iautoshape)
```
public final class AutoShape extends GeometryShape implements IAutoShape
```

เป็น AutoShape.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | คืนค่าล็อกของ shape. |
| [getAutoShapeLock()](#getAutoShapeLock--) | คืนค่าล็อกของ autoshape. |
| [getTextFrame()](#getTextFrame--) | คืนค่าอ็อบเจกต์ TextFrame สำหรับ AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | กำหนดว่าควรเติม autoshape นี้ด้วยการเติมพื้นหลังของ slide แทนที่จะระบุโดยสไตล์หรือรูปแบบการเติมหรือไม่. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | กำหนดว่าควรเติม autoshape นี้ด้วยการเติมพื้นหลังของ slide แทนที่จะระบุโดยสไตล์หรือรูปแบบการเติมหรือไม่. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | เพิ่ม TextFrame ใหม่ให้กับ shape. |
| [isTextBox()](#isTextBox--) | ระบุว่า shape เป็นกล่องข้อความหรือไม่. |
### getShapeLock() {#getShapeLock--}
```
public final IAutoShapeLock getShapeLock()
```


คืนค่าล็อกของ shape. อ่านอย่างเดียว [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**คืนค่า:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getAutoShapeLock() {#getAutoShapeLock--}
```
public final IAutoShapeLock getAutoShapeLock()
```


คืนค่าล็อกของ autoshape. อ่านอย่างเดียว [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**คืนค่า:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```


คืนค่าอ็อบเจกต์ TextFrame สำหรับ AutoShape. อ่านอย่างเดียว [ITextFrame](../../com.aspose.slides/itextframe).

**คืนค่า:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public final boolean getUseBackgroundFill()
```


กำหนดว่าควรเติม autoshape นี้ด้วยการเติมพื้นหลังของ slide แทนที่จะระบุโดยสไตล์หรือรูปแบบการเติมหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public final void setUseBackgroundFill(boolean value)
```


กำหนดว่าควรเติม autoshape นี้ด้วยการเติมพื้นหลังของ slide แทนที่จะระบุโดยสไตล์หรือรูปแบบการเติมหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public final ITextFrame addTextFrame(String text)
```


เพิ่ม TextFrame ใหม่ให้กับ shape หาก shape มี TextFrame อยู่แล้วก็จะเปลี่ยนข้อความนั้นเท่านั้น.

--------------------

> ```
> The following sample code shows how to add watermark text in PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape watermarkShape = slide.getShapes().addAutoShape(ShapeType.Triangle, 0, 0, 150, 50);
>      ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to create Text Box on Slide.
>  
>  // สร้างอินสแตนซ์ Presentation
>  Presentation pres = new Presentation();
>  try {
>      // ดึงสไลด์แรกในงานนำเสนอ
>      ISlide sld = pres.getSlides().get_Item(0);
>      // เพิ่ม AutoShape โดยกำหนดประเภทเป็น Rectangle
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      // เพิ่ม TextFrame ให้กับ Rectangle
>      ashp.addTextFrame(" ");
>      // เข้าถึง text frame
>      ITextFrame txtFrame = ashp.getTextFrame();
>      // สร้างอ็อบเจกต์ Paragraph สำหรับ text frame
>      IParagraph para = txtFrame.getParagraphs().get_Item(0);
>      // สร้างอ็อบเจกต์ Portion สำหรับ paragraph
>      IPortion portion = para.getPortions().get_Item(0);
>      // ตั้งค่าข้อความ
>      portion.setText("Aspose TextBox");
>      // บันทึกงานนำเสนอลงดิสก์
>      pres.save("TextBox_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add column in Text Box.
>  
>  Presentation pres = new Presentation();
>  try {
>      // ดึงสไลด์แรกในงานนำเสนอ
>      ISlide slide = pres.getSlides().get_Item(0);
>      // เพิ่ม AutoShape โดยกำหนดประเภทเป็น Rectangle
>      IAutoShape aShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      // เพิ่ม TextFrame ให้กับ Rectangle
>      aShape.addTextFrame("All these columns are limited to be within a single text container -- " +
>      "you can add or delete text and the new or remaining text automatically adjusts " +
>      "itself to flow within the container. You cannot have text flow from one container " +
>      "to other though -- we told you PowerPoint's column options for text are limited!");
>      // ดึงรูปแบบข้อความของ TextFrame
>      ITextFrameFormat format = aShape.getTextFrame().getTextFrameFormat();
>      // กำหนดจำนวนคอลัมน์ใน TextFrame
>      format.setColumnCount(3);
>      // กำหนดระยะห่างระหว่างคอลัมน์
>      format.setColumnSpacing(10);
>      // บันทึกงานนำเสนอ
>      pres.save("ColumnCount.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความเริ่มต้นสำหรับ TextFrame ใหม่. |

**คืนค่า:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isTextBox() {#isTextBox--}
```
public final boolean isTextBox()
```


ระบุว่า shape เป็นกล่องข้อความหรือไม่.

--------------------

หาก shape ไม่ได้ระบุให้เป็นกล_bboxข้อความไม่ได้หมายความว่าไม่สามารถมีข้อความแนบอยู่ได้ กล่องข้อความเป็นเพียงรูปทรงที่มีคุณสมบัติเฉพาะเท่านั้น.

**คืนค่า:**
boolean