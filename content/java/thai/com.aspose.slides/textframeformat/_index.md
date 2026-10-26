---
title: TextFrameFormat
second_title: Aspose.Slides สำหรับ Java อ้างอิง API
description: มีคุณสมบัติ formatTextFrameFormatting ของ TextFrames.
type: docs
url: /th/com.aspose.slides/textframeformat/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.ITextFrameFormat](../../com.aspose.slides/itextframeformat), [com.aspose.slides.IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
```
public final class TextFrameFormat extends PVIObject implements ITextFrameFormat, IChartTextBlockFormat
```

มีคุณสมบัติ formatTextFrameFormatting ของ TextFrame.

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [TextFrameFormat()](#TextFrameFormat--) | สร้างอินสแตนซ์ใหม่ของคลาส [TextFrameFormat](../../com.aspose.slides/textframeformat) |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getTextStyle()](#getTextStyle--) | คืนค่าสไตล์ของข้อความ. |
| [getThreeDFormat()](#getThreeDFormat--) | คืนค่าอ็อบเจ็กต์ ThreeDFormat ที่แสดงคุณสมบัติเอฟเฟกต์ 3 มิติสำหรับข้อความ. |
| [getMarginLeft()](#getMarginLeft--) | คืนค่าหรือกำหนดระยะขอบซ้าย (หน่วยจุด) ใน TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | คืนค่าหรือกำหนดระยะขอบซ้าย (หน่วยจุด) ใน TextFrame. |
| [getMarginRight()](#getMarginRight--) | คืนค่าหรือกำหนดระยะขอบขวา (หน่วยจุด) ใน TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | คืนค่าหรือกำหนดระยะขอบขวา (หน่วยจุด) ใน TextFrame. |
| [getMarginTop()](#getMarginTop--) | คืนค่าหรือกำหนดระยะขอบบน (หน่วยจุด) ใน TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | คืนค่าหรือกำหนดระยะขอบบน (หน่วยจุด) ใน TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | คืนค่าหรือกำหนดระยะขอบล่าง (หน่วยจุด) ใน TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | คืนค่าหรือกำหนดระยะขอบล่าง (หน่วยจุด) ใน TextFrame. |
| [getWrapText()](#getWrapText--) | เป็นจริงหากข้อความถูกแรปที่ขอบของ TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | เป็นจริงหากข้อความถูกแรปที่ขอบของ TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | คืนค่าหรือกำหนดการยึดแนวตั้งของข้อความใน TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | คืนค่าหรือกำหนดการยึดแนวตั้งของข้อความใน TextFrame. |
| [getCenterText()](#getCenterText--) | หาก NullableBool.True แล้วข้อความควรอยู่กึ่งกลางในกล่องในแนวนอน. |
| [setCenterText(byte value)](#setCenterText-byte-) | หาก NullableBool.True แล้วข้อความควรอยู่กึ่งกลางในกล่องในแนวนอน. |
| [getTextVerticalType()](#getTextVerticalType--) | กำหนดทิศทางของข้อความ. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | กำหนดทิศทางของข้อความ. |
| [getAutofitType()](#getAutofitType--) | คืนค่าหรือกำหนดโหมด autofit ของข้อความ. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | คืนค่าหรือกำหนดโหมด autofit ของข้อความ. |
| [getColumnCount()](#getColumnCount--) | คืนค่าหรือกำหนดจำนวนคอลัมน์ในพื้นที่ข้อความ. |
| [setColumnCount(int value)](#setColumnCount-int-) | คืนค่าหรือกำหนดจำนวนคอลัมน์ในพื้นที่ข้อความ. |
| [getColumnSpacing()](#getColumnSpacing--) | คืนค่าหรือกำหนดระยะห่างระหว่างคอลัมน์ข้อความในพื้นที่ข้อความ (หน่วยจุด). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | คืนค่าหรือกำหนดระยะห่างระหว่างคอลัมน์ข้อความในพื้นที่ข้อความ (หน่วยจุด). |
| [getRotationAngle()](#getRotationAngle--) | ระบุการหมุนที่กำหนดเองที่ใช้กับข้อความภายในกล่องขอบเขต. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | ระบุการหมุนที่กำหนดเองที่ใช้กับข้อความภายในกล่องขอบเขต. |
| [getTransform()](#getTransform--) | รับหรือกำหนดรูปร่างการแรปข้อความ. |
| [setTransform(byte value)](#setTransform-byte-) | รับหรือกำหนดรูปร่างการแรปข้อความ. |
| [getKeepTextFlat()](#getKeepTextFlat--) | รับหรือกำหนดให้ข้อความคงแบนราบแม้ว่าจะมีเอฟเฟกต์การหมุน 3-D ถูกใช้. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | รับหรือกำหนดให้ข้อความคงแบนราบแม้ว่าจะมีเอฟเฟกต์การหมุน 3-D ถูกใช้. |
| [getEffective()](#getEffective--) | รับข้อมูลการจัดรูปแบบ TextFrame ที่มีผลโดยการสืบทอด. |

### TextFrameFormat() {#TextFrameFormat--}
```
public TextFrameFormat()
```

สร้างอินสแตนซ์ใหม่ของคลาส [TextFrameFormat](../../com.aspose.slides/textframeformat).

### getVersion() {#getVersion--}
```
public long getVersion()
```

เวอร์ชัน. อ่านอย่างเดียว long.

**คืนค่า:**
long

### getTextStyle() {#getTextStyle--}
```
public final ITextStyle getTextStyle()
```

คืนค่าสไตล์ของข้อความ. อ่านอย่างเดียว [ITextStyle](../../com.aspose.slides/itextstyle).

**คืนค่า:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getThreeDFormat() {#getThreeDFormat--}
```
public final IThreeDFormat getThreeDFormat()
```

คืนค่าอ็อบเจ็กต์ ThreeDFormat ที่แสดงคุณสมบัติเอฟเฟกต์ 3 มิติสำหรับข้อความ. อ่านอย่างเดียว [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // ตั้งค่าการแปลงข้อความ
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // ตั้งค่าการดันออก
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // ตั้งค่าขอบรูป
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // ตั้งค่าความลึก
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // ตั้งค่าวัสดุ
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      // ตั้งค่าแสง
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

คืนค่าหรือกำหนดระยะขอบซ้าย (หน่วยจุด) ใน TextFrame. อ่าน/เขียน double.

**คืนค่า:**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

คืนค่าหรือกำหนดระยะขอบซ้าย (หน่วยจุด) ใน TextFrame. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

คืนค่าหรือกำหนดระยะขอบขวา (หน่วยจุด) ใน TextFrame. อ่าน/เขียน double.

**คืนค่า:**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

คืนค่าหรือกำหนดระยะขอบขวา (หน่วยจุด) ใน TextFrame. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

คืนค่าหรือกำหนดระยะขอบบน (หน่วยจุด) ใน TextFrame. อ่าน/เขียน double.

**คืนค่า:**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

คืนค่าหรือกำหนดระยะขอบบน (หน่วยจุด) ใน TextFrame. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

คืนค่าหรือกำหนดระยะขอบล่าง (หน่วยจุด) ใน TextFrame. อ่าน/เขียน double.

**คืนค่า:**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

คืนค่าหรือกำหนดระยะขอบล่าง (หน่วยจุด) ใน TextFrame. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public final byte getWrapText()
```

เป็นจริงหากข้อความถูกแรปที่ขอบของ TextFrame. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> The following sample code shows how to wrap text in Presentation.
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

เป็นจริงหากข้อความถูกแรปที่ขอบของ TextFrame. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> The following sample code shows how to wrap text in Presentation.
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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getAnchoringType() {#getAnchoringType--}
```
public final byte getAnchoringType()
```

คืนค่าหรือกำหนดการยึดแนวตั้งของข้อความใน TextFrame. อ่าน/เขียน [TextAnchorType](../../com.aspose.slides/textanchortype).

**คืนค่า:**
byte

### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public final void setAnchoringType(byte value)
```

คืนค่าหรือกำหนดการยึดแนวตั้งของข้อความใน TextFrame. อ่าน/เขียน [TextAnchorType](../../com.aspose.slides/textanchortype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public final byte getCenterText()
```

หาก NullableBool.True แล้วข้อความควรอยู่กึ่งกลางในกล่องในแนวนอน. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte

### setCenterText(byte value) {#setCenterText-byte-}
```
public final void setCenterText(byte value)
```

หาก NullableBool.True แล้วข้อความควรอยู่กึ่งกลางในกล่องในแนวนอน. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

กำหนดทิศทางของข้อความ. ค่าที่ได้จากการหมุนภาพของข้อความสรุปจากคุณสมบัตินี้และมุมที่กำหนดเองในคุณสมบัติ RotationAngle. อ่าน/เขียน [TextVerticalType](../../com.aspose.slides/textverticaltype).

**คืนค่า:**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

กำหนดทิศทางของข้อความ. ค่าที่ได้จากการหมุนภาพของข้อความสรุปจากคุณสมบัตินี้และมุมที่กำหนดเองในคุณสมบัติ RotationAngle. อ่าน/เขียน [TextVerticalType](../../com.aspose.slides/textverticaltype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public final byte getAutofitType()
```

คืนค่าหรือกำหนดโหมด autofit ของข้อความ. อ่าน/เขียน [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> The following sample code shows how to resize shape to Fit Text in a PowerPoint Presentation.
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
>  The following sample code shows how to shrink text on overflow.
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
> The following sample code shows how to resize shape to Fit Text in a PowerPoint Presentation.
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
>  The following sample code shows how to shrink text on overflow.
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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```

คืนค่าหรือกำหนดจำนวนคอลัมน์ในพื้นที่ข้อความ. ค่าต้องเป็นจำนวนบวก มิฉะนั้นค่าจะถูกตั้งเป็นศูนย์. ค่า 0 หมายถึงค่าที่ไม่ได้กำหนด. อ่าน/เขียน int.

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


**คืนค่า:**
int

### setColumnCount(int value) {#setColumnCount-int-}
```
public final void setColumnCount(int value)
```

คืนค่าหรือกำหนดจำนวนคอลัมน์ในพื้นที่ข้อความ. ค่าต้องเป็นจำนวนบวก มิฉะนั้นค่าจะถูกตั้งเป็นศูนย์. ค่า 0 หมายถึงค่าที่ไม่ได้กำหนด. อ่าน/เขียน int.

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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getColumnSpacing() {#getColumnSpacing--}
```
public final double getColumnSpacing()
```

คืนค่าหรือกำหนดระยะห่างระหว่างคอลัมน์ข้อความในพื้นที่ข้อความ (หน่วยจุด). ควรใช้เฉพาะเมื่อมีมากกว่าหนึ่งคอลัมน์. ค่าต้องเป็นจำนวนบวก มิฉะนั้นค่าจะถูกตั้งเป็นศูนย์. อ่าน/เขียน double.

**คืนค่า:**
double

### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public final void setColumnSpacing(double value)
```

คืนค่าหรือกำหนดระยะห่างระหว่างคอลัมน์ข้อความในพื้นที่ข้อความ (หน่วยจุด). ควรใช้เฉพาะเมื่อมีมากกว่าหนึ่งคอลัมน์. ค่าต้องเป็นจำนวนบวก มิฉะนั้นค่าจะถูกตั้งเป็นศูนย์. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getRotationAngle() {#getRotationAngle--}
```
public final float getRotationAngle()
```

ระบุการหมุนที่กำหนดเองที่ใช้กับข้อความภายในกล่องขอบเขต. หากไม่ได้ระบุ จะใช้การหมุนของรูปร่างที่ผูกอยู่. หากระบุ จะถูกนำไปใช้แยกจากรูปร่าง. นั่นคือรูปร่างอาจมีการหมุนเพิ่มเติมขณะที่ข้อความเองก็มีการหมุน. ค่าที่ได้จากการหมุนภาพของข้อความสรุปจากคุณสมบัตินี้และประเภทแนวตั้งที่กำหนดไว้ในคุณสมบัติ TextVerticalType. อ่าน/เขียน float.

--------------------

> ```
> พิจารณากรณีที่รูปทรงมีการหมุน 90 องศา ตามเข็มนาฬิกา. 
>  นอกจากนี้ ตัวข้อความเองมีการหมุน -90 องศา 
>  ตามทวนเข็มนาฬิกาให้กับมัน แล้วรูปที่ได้จะปรากฏว่า
>  ถูกหมุน แต่ข้อความภายในนั้นดูเหมือนว่าไม่ได้หมุนเลย.
```

**คืนค่า:**
float

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public final void setRotationAngle(float value)
```

ระบุการหมุนที่กำหนดเองที่ใช้กับข้อความภายในกล่องขอบเขต. หากไม่ได้ระบุ จะใช้การหมุนของรูปร่างที่ผูกอยู่. หากระบุ จะถูกนำไปใช้แยกจากรูปร่าง. นั่นคือรูปร่างอาจมีการหมุนเพิ่มเติมขณะที่ข้อความเองก็มีการหมุน. ค่าที่ได้จากการหมุนภาพของข้อความสรุปจากคุณสมบัตินี้และประเภทแนวตั้งที่กำหนดไว้ในคุณสมบัติ TextVerticalType. อ่าน/เขียน float.

--------------------

> ```
> พิจารณากรณีที่รูปทรงมีการหมุน 90 องศาตามเข็มนาฬิกา 
>  นอกจากนี้ ตัวข้อความเองมีการหมุน -90 องศาตามทวนเข็มนาฬิกาให้กับมัน. แล้วรูปที่ได้จะปรากฏว่า
>  ถูกหมุน แต่ข้อความภายในดูเหมือนว่าไม่ได้หมุนเลย.
```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public final byte getTransform()
```

รับหรือกำหนดรูปร่างการแรปข้อความ. อ่าน/เขียน [TextShapeType](../../com.aspose.slides/textshapetype).

**คืนค่า:**
byte

### setTransform(byte value) {#setTransform-byte-}
```
public final void setTransform(byte value)
```

รับหรือกำหนดรูปร่างการแรปข้อความ. อ่าน/เขียน [TextShapeType](../../com.aspose.slides/textshapetype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getKeepTextFlat() {#getKeepTextFlat--}
```
public final boolean getKeepTextFlat()
```

รับหรือกำหนดให้ข้อความคงแบนราบแม้ว่าจะมีเอฟเฟกต์การหมุน 3-D ถูกใช้. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public final void setKeepTextFlat(boolean value)
```

รับหรือกำหนดให้ข้อความคงแบนราบแม้ว่าจะมีเอฟเฟกต์การหมุน 3-D ถูกใช้. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final ITextFrameFormatEffectiveData getEffective()
```

รับข้อมูลการจัดรูปแบบ TextFrame ที่มีผลโดยการสืบทอด.

--------------------

> ```
> This example demonstrates getting some of effective text frame formatting properties.
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