---
title: TextFrameFormat
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: ประกอบด้วยคุณสมบัติ formatTextFrameFormatting ของ TextFrames.
type: docs
url: /th/com.aspose.slides/textframeformat/
---
**สืบทอด:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**ส่วนต่อประสานที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.ITextFrameFormat](../../com.aspose.slides/itextframeformat), [com.aspose.slides.IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
```
public final class TextFrameFormat extends PVIObject implements ITextFrameFormat, IChartTextBlockFormat
```

ประกอบด้วยคุณสมบัติ formatTextFrameFormatting ของ TextFrame.
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [TextFrameFormat()](#TextFrameFormat--) | สร้างอินสแตนซ์ใหม่ของ [TextFrameFormat](../../com.aspose.slides/textframeformat) class. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getTextStyle()](#getTextStyle--) | คืนค่าสไตล์ของข้อความ. |
| [getThreeDFormat()](#getThreeDFormat--) | คืนค่าอ็อบเจกต์ ThreeDFormat ที่แสดงคุณสมบัติโผล 3 มิติสำหรับข้อความ. |
| [getMarginLeft()](#getMarginLeft--) | คืนค่าหรือกำหนดระยะขอบซ้าย (จุด) ใน TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | คืนค่าหรือกำหนดระยะขอบซ้าย (จุด) ใน TextFrame. |
| [getMarginRight()](#getMarginRight--) | คืนค่าหรือกำหนดระยะขอบขวา (จุด) ใน TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | คืนค่าหรือกำหนดระยะขอบขวา (จุด) ใน TextFrame. |
| [getMarginTop()](#getMarginTop--) | คืนค่าหรือกำหนดระยะขอบบน (จุด) ใน TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | คืนค่าหรือกำหนดระยะขอบบน (จุด) ใน TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | คืนค่าหรือกำหนดระยะขอบล่าง (จุด) ใน TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | คืนค่าหรือกำหนดระยะขอบล่าง (จุด) ใน TextFrame. |
| [getWrapText()](#getWrapText--) | จริงหากข้อความถูกตัดบรรทัดที่ขอบของ TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | จริงหากข้อความถูกตัดบรรทัดที่ขอบของ TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | คืนค่าหรือกำหนดตำแหน่งยึดแนวตั้งของข้อความใน TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | คืนค่าหรือกำหนดตำแหน่งยึดแนวตั้งของข้อความใน TextFrame. |
| [getCenterText()](#getCenterText--) | ถ้า NullableBool.True แล้วข้อความควรอยู่กึ่งกลางกล่องในแนวนอน. |
| [setCenterText(byte value)](#setCenterText-byte-) | ถ้า NullableBool.True แล้วข้อความควรอยู่กึ่งกลางกล่องในแนวนอน. |
| [getTextVerticalType()](#getTextVerticalType--) | กำหนดการวางแนวข้อความ. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | กำหนดการวางแนวข้อความ. |
| [getAutofitType()](#getAutofitType--) | คืนค่าหรือกำหนดโหมด autofit ของข้อความ. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | คืนค่าหรือกำหนดโหมด autofit ของข้อความ. |
| [getColumnCount()](#getColumnCount--) | คืนค่าหรือกำหนดจำนวนคอลัมน์ในพื้นที่ข้อความ. |
| [setColumnCount(int value)](#setColumnCount-int-) | คืนค่าหรือกำหนดจำนวนคอลัมน์ในพื้นที่ข้อความ. |
| [getColumnSpacing()](#getColumnSpacing--) | คืนค่าหรือกำหนดระยะห่างระหว่างคอลัมน์ข้อความในพื้นที่ข้อความ (จุด). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | คืนค่าหรือกำหนดระยะห่างระหว่างคอลัมน์ข้อความในพื้นที่ข้อความ (จุด). |
| [getRotationAngle()](#getRotationAngle--) | ระบุการหมุนแบบกำหนดเองที่ใช้กับข้อความภายในกล่องขอบเขต. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | ระบุการหมุนแบบกำหนดเองที่ใช้กับข้อความภายในกล่องขอบเขต. |
| [getTransform()](#getTransform--) | รับหรือกำหนดรูปแบบการห่อข้อความ. |
| [setTransform(byte value)](#setTransform-byte-) | รับหรือกำหนดรูปแบบการห่อข้อความ. |
| [getKeepTextFlat()](#getKeepTextFlat--) | รับหรือกำหนดให้ข้อความคงแบนแม้ว่าจะมีเอฟเฟกต์การหมุน 3-มิติ. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | รับหรือกำหนดให้ข้อความคงแบนแม้ว่าจะมีเอฟเฟกต์การหมุน 3-มิติ. |
| [getEffective()](#getEffective--) | รับข้อมูลการจัดรูปแบบ TextFrame ที่มีผลกับการสืบทอดที่นำไปใช้. |

### TextFrameFormat() {#TextFrameFormat--}
```
public TextFrameFormat()
```

Initializes a new instance of [TextFrameFormat](../../com.aspose.slides/textframeformat) class.

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. อ่านอย่างเดียว long.

**คืนค่า:**
long
### getTextStyle() {#getTextStyle--}
```
public final ITextStyle getTextStyle()
```

Returns text's style. อ่านอย่างเดียว [ITextStyle](../../com.aspose.slides/itextstyle).

**คืนค่า:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getThreeDFormat() {#getThreeDFormat--}
```
public final IThreeDFormat getThreeDFormat()
```

Returns the ThreeDFormat object that represents 3d effect properties for a text. อ่านอย่างเดียว [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // ตั้งค่าการแปลงข้อความ
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // ตั้งค่า Extrusion
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // ตั้งค่าคอนท้อร์
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // ตั้งค่าความลึก
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // ตั้งค่าวัสดุ
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      // ตั้งค่าแสงสว่าง
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      // ตั้งค่าชนิดกล้อง
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

คืนค่าหรือกำหนดระยะขอบซ้าย (จุด) ใน TextFrame. อ่าน/เขียน double.

**คืนค่า:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

คืนค่าหรือกำหนดระยะขอบซ้าย (จุด) ใน TextFrame. อ่าน/เขียน double.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

คืนค่าหรือกำหนดระยะขอบขวา (จุด) ใน TextFrame. อ่าน/เขียน double.

**คืนค่า:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

คืนค่าหรือกำหนดระยะขอบขวา (จุด) ใน TextFrame. อ่าน/เขียน double.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

คืนค่าหรือกำหนดระยะขอบบน (จุด) ใน TextFrame. อ่าน/เขียน double.

**คืนค่า:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

คืนค่าหรือกำหนดระยะขอบบน (จุด) ใน TextFrame. อ่าน/เขียน double.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

คืนค่าหรือกำหนดระยะขอบล่าง (จุด) ใน TextFrame. อ่าน/เขียน double.

**คืนค่า:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

คืนค่าหรือกำหนดระยะขอบล่าง (จุด) ใน TextFrame. อ่าน/เขียน double.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public final byte getWrapText()
```

จริงหากข้อความถูกตัดบรรทัดที่ขอบของ TextFrame. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> โค้ดตัวอย่างต่อไปนี้แสดงวิธีห่อข้อความใน Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setWrapText(NullableBool.True);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public final void setWrapText(byte value)
```

จริงหากข้อความถูกตัดบรรทัดที่ขอบของ TextFrame. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> โค้ดตัวอย่างต่อไปนี้แสดงวิธีห่อข้อความใน Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setWrapText(NullableBool.True);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getAnchoringType() {#getAnchoringType--}
```
public final byte getAnchoringType()
```

คืนค่าหรือกำหนดตำแหน่งยึดแนวตั้งของข้อความใน TextFrame. อ่าน/เขียน [TextAnchorType](../../com.aspose.slides/textanchortype).

**คืนค่า:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public final void setAnchoringType(byte value)
```

คืนค่าหรือกำหนดตำแหน่งยึดแนวตั้งของข้อความใน TextFrame. อ่าน/เขียน [TextAnchorType](../../com.aspose.slides/textanchortype).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public final byte getCenterText()
```

ถ้า NullableBool.True แล้วข้อความควรอยู่กึ่งกลางกล่องในแนวนอน. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public final void setCenterText(byte value)
```

ถ้า NullableBool.True แล้วข้อความควรอยู่กึ่งกลางกล่องในแนวนอน. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

กำหนดการวางแนวข้อความ. ค่าที่ได้จากการหมุนภาพข้อความที่สรุปจากคุณสมบัตินี้และมุมที่กำหนดในคุณสมบัติ RotationAngle. อ่าน/เขียน [TextVerticalType](../../com.aspose.slides/textverticaltype).

**คืนค่า:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

กำหนดการวางแนวข้อความ. ค่าที่ได้จากการหมุนภาพข้อความที่สรุปจากคุณสมบัตินี้และมุมที่กำหนดในคุณสมบัติ RotationAngle. อ่าน/เขียน [TextVerticalType](../../com.aspose.slides/textverticaltype).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public final byte getAutofitType()
```

คืนค่าหรือกำหนดโหมด autofit ของข้อความ. อ่าน/เขียน [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> โค้ดตัวอย่างต่อไปนี้แสดงวิธีปรับขนาดรูปร่างให้พอดีกับข้อความใน PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Shape);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  โค้ดตัวอย่างต่อไปนี้แสดงวิธีย่อข้อความเมื่อเกินขนาด.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Normal);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public final void setAutofitType(byte value)
```

คืนค่าหรือกำหนดโหมด autofit ของข้อความ. อ่าน/เขียน [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> โค้ดตัวอย่างต่อไปนี้แสดงวิธีปรับขนาดรูปร่างให้พอดีกับข้อความใน PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Shape);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  โค้ดตัวอย่างต่อไปนี้แสดงวิธีย่อข้อความเมื่อเกินขนาด.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Normal);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```

คืนค่าหรือกำหนดจำนวนคอลัมน์ในพื้นที่ข้อความ. ค่านี้ต้องเป็นจำนวนเต็มบวก มิฉะนั้นจะตั้งเป็นศูนย์. ค่า 0 หมายถึงค่าไม่กำหนด. อ่าน/เขียน int.

--------------------

> ```
> โค้ดตัวอย่างต่อไปนี้แสดงวิธีเพิ่มคอลัมน์ใน Text frame ภายใน PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape1 = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      TextFrameFormat format = (TextFrameFormat)shape1.getTextFrame().getTextFrameFormat();
>      format.setColumnCount(2);
>      format.setColumnSpacing(20);
>      shape1.getTextFrame().setText("All these columns are forced to stay within a single text container -- " +
>      "you can add or delete text - and the new or remaining text automatically adjusts " +
>      "itself to stay within the container. You cannot have text spill over from one container " +
>      "to other, though -- because PowerPoint's column options for text are limited!");
>      pres.save("Columns_output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**
int
### setColumnCount(int value) {#setColumnCount-int-}
```
public final void setColumnCount(int value)
```

คืนค่าหรือกำหนดจำนวนคอลัมน์ในพื้นที่ข้อความ. ค่านี้ต้องเป็นจำนวนเต็มบวก มิฉะนั้นจะตั้งเป็นศูนย์. ค่า 0 หมายถึงค่าไม่กำหนด. อ่าน/เขียน int.

--------------------

> ```
> The following sample code shows how to add column in Text frame inside a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape1 = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      TextFrameFormat format = (TextFrameFormat)shape1.getTextFrame().getTextFrameFormat();
>      format.setColumnCount(2);
>      format.setColumnSpacing(20);
>      shape1.getTextFrame().setText("All these columns are forced to stay within a single text container -- " +
>      "you can add or delete text - and the new or remaining text automatically adjusts " +
>      "itself to stay within the container. You cannot have text spill over from one container " +
>      "to other, though -- because PowerPoint's column options for text are limited!");
>      pres.save("Columns_output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getColumnSpacing() {#getColumnSpacing--}
```
public final double getColumnSpacing()
```

คืนค่าหรือกำหนดระยะห่างระหว่างคอลัมน์ข้อความในพื้นที่ข้อความ (จุด). ควรใช้เมื่อมีมากกว่าหนึ่งคอลัมน์. ค่านี้ต้องเป็นจำนวนเต็มบวก มิฉะนั้นจะตั้งเป็นศูนย์. อ่าน/เขียน double.

**คืนค่า:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public final void setColumnSpacing(double value)
```

คืนค่าหรือกำหนดระยะห่างระหว่างคอลัมน์ข้อความในพื้นที่ข้อความ (จุด). ควรใช้เมื่อมีมากกว่าหนึ่งคอลัมน์. ค่านี้ต้องเป็นจำนวนเต็มบวก มิฉะนั้นจะตั้งเป็นศูนย์. อ่าน/เขียน double.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getRotationAngle() {#getRotationAngle--}
```
public final float getRotationAngle()
```

ระบุการหมุนแบบกำหนดเองที่ใช้กับข้อความภายในกล่องขอบเขต. หากไม่ได้ระบุจะใช้การหมุนของรูปร่างที่แนบมาด้วย. หากระบุแล้วจะถูกนำไปใช้แยกจากรูปร่าง. นั่นหมายความว่ารูปร่างสามารถมีการหมุนเพิ่มพร้อมกับข้อความที่มีการหมุนของตนเอง. ค่าที่ได้จากการหมุนภาพข้อความที่สรุปจากคุณสมบัตินี้และประเภทแนวตั้งที่กำหนดไว้ล่วงหน้าในคุณสมบัติ TextVerticalType. อ่าน/เขียน float.

--------------------

> ```
> พิจารณากรณีที่รูปทรงมีการหมุน 90 องศาตามเข็มนาฬิกา 
>  นอกจากนี้ข้อความเองยังมีการหมุน -90 องศาตามทวนเข็มนาฬิกา 
>  จากนั้นรูปทรงที่ได้จะดูเหมือนหมุนแต่ข้อความภายในจะดูเหมือนว่าไม่ได้รับการหมุนเลย
> ```

**คืนค่า:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public final void setRotationAngle(float value)
```

ระบุการหมุนแบบกำหนดเองที่ใช้กับข้อความภายในกล่องขอบเขต. หากไม่ได้ระบุจะใช้การหมุนของรูปร่างที่แนบมาด้วย. หากระบุแล้วจะถูกนำไปใช้แยกจากรูปร่าง. นั่นหมายความว่ารูปร่างสามารถมีการหมุนเพิ่มพร้อมกับข้อความที่มีการหมุนของตนเอง. ค่าที่ได้จากการหมุนภาพข้อความที่สรุปจากคุณสมบัตินี้และประเภทแนวตั้งที่กำหนดไว้ล่วงหน้าในคุณสมบัติ TextVerticalType. อ่าน/เขียน float.

--------------------

> ```
> พิจารณากรณีที่รูปทรงมีการหมุน 90 องศาตามเข็มนาฬิกา 
>  นอกจากนี้ข้อความเองมีการหมุน -90 องศา 
>  ตามแนวทวนเข็มนาฬิกา จากนั้นรูปทรงที่ได้จะดูเหมือนว่า 
>  ถูกหมุน แต่ข้อความภายในจะดูเหมือนว่าไม่ได้รับการหมุนเลย
> ```


**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public final byte getTransform()
```

รับหรือกำหนดรูปแบบการห่อข้อความ. อ่าน/เขียน [TextShapeType](../../com.aspose.slides/textshapetype).

**คืนค่า:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public final void setTransform(byte value)
```

รับหรือกำหนดรูปแบบการห่อข้อความ. อ่าน/เขียน [TextShapeType](../../com.aspose.slides/textshapetype).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getKeepTextFlat() {#getKeepTextFlat--}
```
public final boolean getKeepTextFlat()
```

รับหรือกำหนดให้ข้อความคงแบนแม้ว่าจะมีเอฟเฟกต์การหมุน 3-มิติ. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public final void setKeepTextFlat(boolean value)
```

รับหรือกำหนดให้ข้อความคงแบนแม้ว่าจะมีเอฟเฟกต์การหมุน 3-มิติ. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final ITextFrameFormatEffectiveData getEffective()
```

รับข้อมูลการจัดรูปแบบ TextFrame ที่มีผลกับการสืบทอดที่นำไปใช้.

--------------------

> ```
> ตัวอย่างนี้แสดงการดึงคุณสมบัติการจัดรูปแบบ Text Frame ที่มีผลบางส่วน.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      ITextFrameFormatEffectiveData effectiveTextFrameFormat = shape.getTextFrame().getTextFrameFormat().getEffective();
>     
>      System.out.println("Anchoring type: " + effectiveTextFrameFormat.getAnchoringType());
>      System.out.println("Autofit type: " + effectiveTextFrameFormat.getAutofitType());
>      System.out.println("Text vertical type: " + effectiveTextFrameFormat.getTextVerticalType());
>      System.out.println("Margins");
>      System.out.println("   Left: " + effectiveTextFrameFormat.getMarginLeft());
>      System.out.println("   Top: " + effectiveTextFrameFormat.getMarginTop());
>      System.out.println("   Right: " + effectiveTextFrameFormat.getMarginRight());
>      System.out.println("   Bottom: " + effectiveTextFrameFormat.getMarginBottom());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).