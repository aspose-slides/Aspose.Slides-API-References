---
title: ITextFrameFormat
second_title: Aspose.Slides for Java API Reference
description: มีคุณสมบัติการจัดรูปแบบของ TextFrames.
type: docs
url: /th/com.aspose.slides/itextframeformat/
---```
public interface ITextFrameFormat
```

มีคุณสมบัติการจัดรูปแบบของ TextFrame.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | ส่งคืนสไตล์ของข้อความ. |
| [getMarginLeft()](#getMarginLeft--) | รับหรือกำหนดขอบซ้าย (จุด) ใน TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | รับหรือกำหนดขอบซ้าย (จุด) ใน TextFrame. |
| [getMarginRight()](#getMarginRight--) | รับหรือกำหนดขอบขวา (จุด) ใน TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | รับหรือกำหนดขอบขวา (จุด) ใน TextFrame. |
| [getMarginTop()](#getMarginTop--) | รับหรือกำหนดขอบบน (จุด) ใน TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | รับหรือกำหนดขอบบน (จุด) ใน TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | รับหรือกำหนดขอบล่าง (จุด) ใน TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | รับหรือกำหนดขอบล่าง (จุด) ใน TextFrame. |
| [getWrapText()](#getWrapText--) | เป็นจริงหากข้อความถูกห่อหุ้มที่ขอบของ TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | เป็นจริงหากข้อความถูกห่อหุ้มที่ขอบของ TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | รับหรือกำหนดจุดยึดแนวตั้งของข้อความใน TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | รับหรือกำหนดจุดยึดแนวตั้งของข้อความใน TextFrame. |
| [getCenterText()](#getCenterText--) | ถ้า NullableBool.True แล้วข้อความควรอยู่ตรงกลางในกล่องแนวนอน. |
| [setCenterText(byte value)](#setCenterText-byte-) | ถ้า NullableBool.True แล้วข้อความควรอยู่ตรงกลางในกล่องแนวนอน. |
| [getTextVerticalType()](#getTextVerticalType--) | กำหนดการจัดแนวข้อความ. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | กำหนดการจัดแนวข้อความ. |
| [getAutofitType()](#getAutofitType--) | รับหรือกำหนดโหมดปรับอัตโนมัติของข้อความ. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | รับหรือกำหนดโหมดปรับอัตโนมัติของข้อความ. |
| [getColumnCount()](#getColumnCount--) | รับหรือกำหนดจำนวนคอลัมน์ในพื้นที่ข้อความ. |
| [setColumnCount(int value)](#setColumnCount-int-) | รับหรือกำหนดจำนวนคอลัมน์ในพื้นที่ข้อความ. |
| [getColumnSpacing()](#getColumnSpacing--) | รับหรือกำหนดช่องว่างระหว่างคอลัมน์ข้อความในพื้นที่ข้อความ (หน่วยจุด). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | รับหรือกำหนดช่องว่างระหว่างคอลัมน์ข้อความในพื้นที่ข้อความ (หน่วยจุด). |
| [getThreeDFormat()](#getThreeDFormat--) | รับอ็อบเจ็กต์ ThreeDFormat ที่แสดงคุณสมบัติของเอฟเฟกต์ 3 มิติสำหรับข้อความ. |
| [getKeepTextFlat()](#getKeepTextFlat--) | รับหรือกำหนดการเก็บข้อความให้อยู่นอกฉาก 3 มิติโดยสมบูรณ์. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | รับหรือกำหนดการเก็บข้อความให้อยู่นอกฉาก 3 มิติโดยสมบูรณ์. |
| [getRotationAngle()](#getRotationAngle--) | ระบุการหมุนที่กำหนดเองที่นำไปใช้กับข้อความภายในกล่องขอบเขต. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | ระบุการหมุนที่กำหนดเองที่นำไปใช้กับข้อความภายในกล่องขอบเขต. |
| [getTransform()](#getTransform--) | รับหรือกำหนดรูปร่างการห่อหุ้มข้อความ. |
| [setTransform(byte value)](#setTransform-byte-) | รับหรือกำหนดรูปร่างการห่อหุ้มข้อความ. |
| [getEffective()](#getEffective--) | รับข้อมูลการจัดรูปแบบกรอบข้อความที่มีผลโดยใช้การสืบทอด. |

### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyle getTextStyle()
```

ส่งคืนสไตล์ของข้อความ. อ่านอย่างเดียว [ITextStyle](../../com.aspose.slides/itextstyle).

**คืนค่า:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

รับหรือกำหนดขอบซ้าย (จุด) ใน TextFrame. อ่าน/เขียน double.

**คืนค่า:**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

รับหรือกำหนดขอบซ้าย (จุด) ใน TextFrame. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

รับหรือกำหนดขอบขวา (จุด) ใน TextFrame. อ่าน/เขียน double.

**คืนค่า:**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

รับหรือกำหนดขอบขวา (จุด) ใน TextFrame. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

รับหรือกำหนดขอบบน (จุด) ใน TextFrame. อ่าน/เขียน double.

**คืนค่า:**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

รับหรือกำหนดขอบบน (จุด) ใน TextFrame. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

รับหรือกำหนดขอบล่าง (จุด) ใน TextFrame. อ่าน/เขียน double.

**คืนค่า:**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

รับหรือกำหนดขอบล่าง (จุด) ใน TextFrame. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

เป็นจริงหากข้อความถูกห่อหุ้มที่ขอบของ TextFrame. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte

### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

เป็นจริงหากข้อความถูกห่อหุ้มที่ขอบของ TextFrame. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

รับหรือกำหนดจุดยึดแนวตั้งของข้อความใน TextFrame. อ่าน/เขียน [TextAnchorType](../../com.aspose.slides/textanchortype).

**คืนค่า:**
byte

### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

รับหรือกำหนดจุดยึดแนวตั้งของข้อความใน TextFrame. อ่าน/เขียน [TextAnchorType](../../com.aspose.slides/textanchortype).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

ถ้า NullableBool.True แล้วข้อความควรอยู่ตรงกลางในกล่องแนวนอน. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte

### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

ถ้า NullableBool.True แล้วข้อความควรอยู่ตรงกลางในกล่องแนวนอน. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

กำหนดการจัดแนวข้อความ. ค่าที่ได้จากการหมุนที่มองเห็นของข้อความสรุปจากคุณสมบัตินี้และมุมที่กำหนดเองในคุณสมบัติ RotationAngle. อ่าน/เขียน [TextVerticalType](../../com.aspose.slides/textverticaltype).

**คืนค่า:**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

กำหนดการจัดแนวข้อความ. ค่าที่ได้จากการหมุนที่มองเห็นของข้อความสรุปจากคุณสมบัตินี้และมุมที่กำหนดเองในคุณสมบัติ RotationAngle. อ่าน/เขียน [TextVerticalType](../../com.aspose.slides/textverticaltype).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

รับหรือกำหนดโหมดปรับอัตโนมัติของข้อความ. อ่าน/เขียน [TextAutofitType](../../com.aspose.slides/textautofittype).

**คืนค่า:**
byte

### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

รับหรือกำหนดโหมดปรับอัตโนมัติของข้อความ. อ่าน/เขียน [TextAutofitType](../../com.aspose.slides/textautofittype).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

รับหรือกำหนดจำนวนคอลัมน์ในพื้นที่ข้อความ. ค่านี้ต้องเป็นจำนวนบวก มิฉะนั้นค่าจะถูกตั้งเป็นศูนย์. ค่า 0 หมายถึงค่าไม่ได้กำหนด. อ่าน/เขียน int.

**คืนค่า:**
int

### setColumnCount(int value) {#setColumnCount-int-}
```
public abstract void setColumnCount(int value)
```

รับหรือกำหนดจำนวนคอลัมน์ในพื้นที่ข้อความ. ค่านี้ต้องเป็นจำนวนบวก มิฉะนั้นค่าจะถูกตั้งเป็นศูนย์. ค่า 0 หมายถึงค่าไม่ได้กำหนด. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getColumnSpacing() {#getColumnSpacing--}
```
public abstract double getColumnSpacing()
```

รับหรือกำหนดช่องว่างระหว่างคอลัมน์ข้อความในพื้นที่ข้อความ (หน่วยจุด). ค่านี้ควรใช้เมื่อมีมากกว่าหนึ่งคอลัมน์. ค่านี้ต้องเป็นจำนวนบวก มิฉะนั้นค่าจะถูกตั้งเป็นศูนย์. อ่าน/เขียน double.

**คืนค่า:**
double

### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public abstract void setColumnSpacing(double value)
```

รับหรือกำหนดช่องว่างระหว่างคอลัมน์ข้อความในพื้นที่ข้อความ (หน่วยจุด). ค่านี้ควรใช้เมื่อมีมากกว่าหนึ่งคอลัมน์. ค่านี้ต้องเป็นจำนวนบวก มิฉะนั้นค่าจะถูกตั้งเป็นศูนย์. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

รับอ็อบเจ็กต์ ThreeDFormat ที่แสดงคุณสมบัติของเอฟเฟกต์ 3 มิติสำหรับข้อความ. อ่านอย่างเดียว [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // ตั้งค่าการแปลงข้อความ
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // ตั้งค่าการดึงออก
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // ตั้งค่าขอบ
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

### getKeepTextFlat() {#getKeepTextFlat--}
```
public abstract boolean getKeepTextFlat()
```

รับหรือกำหนดการเก็บข้อความให้อยู่นอกฉาก 3 มิติโดยสมบูรณ์. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public abstract void setKeepTextFlat(boolean value)
```

รับหรือกำหนดการเก็บข้อความให้อยู่นอกฉาก 3 มิติโดยสมบูรณ์. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

ระบุการหมุนที่กำหนดเองที่นำไปใช้กับข้อความภายในกล่องขอบเขต. หากไม่ได้ระบุ จะใช้การหมุนของรูปร่างที่แนบมานั้น. หากระบุแล้ว จะถูกนำไปใช้แยกจากรูปทรง. กล่าวคือ รูปร่างอาจมีการหมุนเพิ่มเติมในขณะที่ข้อความเองก็มีการหมุนของมันเอง. ค่าที่ได้จากการหมุนที่มองเห็นของข้อความสรุปจากคุณสมบัตินี้และประเภทแนวตั้งที่กำหนดไว้ล่วงหน้าในคุณสมบัติ TextVerticalType. อ่าน/เขียน float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```


**คืนค่า:**
float

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

ระบุการหมุนที่กำหนดเองที่นำไปใช้กับข้อความภายในกล่องขอบเขต. หากไม่ได้ระบุ จะใช้การหมุนของรูปร่างที่แนบมานั้น. หากระบุแล้ว จะถูกนำไปใช้แยกจากรูปทรง. กล่าวคือ รูปร่างอาจมีการหมุนเพิ่มเติมในขณะที่ข้อความเองก็มีการหมุนของมันเอง. ค่าที่ได้จากการหมุนที่มองเห็นของข้อความสรุปจากคุณสมบัตินี้และประเภทแนวตั้งที่กำหนดไว้ล่วงหน้าในคุณสมบัติ TextVerticalType. อ่าน/เขียน float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public abstract byte getTransform()
```

รับหรือกำหนดรูปร่างการห่อหุ้มข้อความ. อ่าน/เขียน [TextShapeType](../../com.aspose.slides/textshapetype).

**คืนค่า:**
byte

### setTransform(byte value) {#setTransform-byte-}
```
public abstract void setTransform(byte value)
```

รับหรือกำหนดรูปร่างการห่อหุ้มข้อความ. อ่าน/เขียน [TextShapeType](../../com.aspose.slides/textshapetype).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public abstract ITextFrameFormatEffectiveData getEffective()
```

รับข้อมูลการจัดรูปแบบกรอบข้อความที่มีผลโดยใช้การสืบทอด.

**คืนค่า:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).