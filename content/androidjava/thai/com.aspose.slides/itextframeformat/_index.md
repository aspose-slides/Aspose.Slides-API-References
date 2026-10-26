---
title: ITextFrameFormat
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: ประกอบด้วยคุณสมบัติการจัดรูปแบบของ TextFrames.
type: docs
url: /th/com.aspose.slides/itextframeformat/
---```
public interface ITextFrameFormat
```

ประกอบด้วยคุณสมบัติการจัดรูปแบบของ TextFrame.
## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | คืนค่ารูปแบบของข้อความ. |
| [getMarginLeft()](#getMarginLeft--) | คืนค่าหรือกำหนดระยะขอบซ้าย (points) ใน TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | คืนค่าหรือกำหนดระยะขอบซ้าย (points) ใน TextFrame. |
| [getMarginRight()](#getMarginRight--) | คืนค่าหรือกำหนดระยะขอบขวา (points) ใน TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | คืนค่าหรือกำหนดระยะขอบขวา (points) ใน TextFrame. |
| [getMarginTop()](#getMarginTop--) | คืนค่าหรือกำหนดระยะขอบบน (points) ใน TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | คืนค่าหรือกำหนดระยะขอบบน (points) ใน TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | คืนค่าหรือกำหนดระยะขอบล่าง (points) ใน TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | คืนค่า หรือกำหนดระยะขอบล่าง (points) ใน TextFrame. |
| [getWrapText()](#getWrapText--) | True หากข้อความถูกห่อหุ้มที่ขอบของ TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | True หากข้อความถูกห่อหุ้มที่ขอบของ TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | คืนค่า หรือกำหนดตำแหน่งยึดแนวตั้งของข้อความใน TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | คืนค่า หรือกำหนดตำแหน่งยึดแนวตั้งของข้อความใน TextFrame. |
| [getCenterText()](#getCenterText--) | If NullableBool.True then text should be centered in box horizontally. |
| [setCenterText(byte value)](#setCenterText-byte-) | If NullableBool.True then text should be centered in box horizontally. |
| [getTextVerticalType()](#getTextVerticalType--) | กำหนดการวางแนวข้อความ. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | กำหนดการวางแนวข้อความ. |
| [getAutofitType()](#getAutofitType--) | คืนค่า หรือกำหนดโหมด autofit ของข้อความ. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | คืนค่า หรือกำหนดโหมด autofit ของข้อความ. |
| [getColumnCount()](#getColumnCount--) | คืนค่า หรือกำหนดจำนวนคอลัมน์ในพื้นที่ข้อความ. |
| [setColumnCount(int value)](#setColumnCount-int-) | คืนค่า หรือกำหนดจำนวนคอลัมน์ในพื้นที่ข้อความ. |
| [getColumnSpacing()](#getColumnSpacing--) | คืนค่า หรือกำหนดระยะห่างระหว่างคอลัมน์ข้อความในพื้นที่ข้อความ (points). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | คืนค่า หรือกำหนดระยะห่างระหว่างคอลัมน์ข้อความในพื้นที่ข้อความ (points). |
| [getThreeDFormat()](#getThreeDFormat--) | คืนค่าออบเจกต์ ThreeDFormat ที่แสดงคุณสมบัติเพื่อสร้างเอฟเฟกต์ 3 มิติสำหรับข้อความ. |
| [getKeepTextFlat()](#getKeepTextFlat--) | คืนค่า หรือกำหนดการเก็บข้อความให้อยู่นอกฉาก 3D ทั้งหมด. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | คืนค่า หรือกำหนดการเก็บข้อความให้อยู่นอกฉาก 3D ทั้งหมด. |
| [getRotationAngle()](#getRotationAngle--) | ระบุการหมุนแบบกำหนดเองที่นำไปใช้กับข้อความภายในกล่องรอบขอบ. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | ระบุการหมุนแบบกำหนดเองที่นำไปใช้กับข้อความภายในกล่องรอบขอบ. |
| [getTransform()](#getTransform--) | รับหรือกำหนดรูปแบบการห่อหุ้มข้อความ. |
| [setTransform(byte value)](#setTransform-byte-) | รับหรือกำหนดรูปแบบการห่อหุ้มข้อความ. |
| [getEffective()](#getEffective--) | รับข้อมูลการจัดรูปแบบของ text frame ที่มีการสืบทอดค่าแล้ว. |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyle getTextStyle()
```


คืนค่ารูปแบบของข้อความ. อ่านอย่างเดียว [ITextStyle](../../com.aspose.slides/itextstyle).

**คืนค่า:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```


คืนค่า หรือกำหนดระยะขอบซ้าย (points) ใน TextFrame. อ่าน/เขียน double.

**คืนค่า:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```


คืนค่า หรือกำหนดระยะขอบซ้าย (points) ใน TextFrame. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```


คืนค่า หรือกำหนดระยะขอบขวา (points) ใน TextFrame. อ่าน/เขียน double.

**คืนค่า:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```


คืนค่า หรือกำหนดระยะขอบขวา (points) ใน TextFrame. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```


คืนค่า หรือกำหนดระยะขอบบน (points) ใน TextFrame. อ่าน/เขียน double.

**คืนค่า:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```


คืนค่า หรือกำหนดระยะขอบบน (points) ใน TextFrame. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```


คืนค่า หรือกำหนดระยะขอบล่าง (points) ใน TextFrame. อ่าน/เขียน double.

**คืนค่า:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```


คืนค่า หรือกำหนดระยะขอบล่าง (points) ใน TextFrame. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```


True หากข้อความถูกห่อหุ้มที่ขอบของ TextFrame. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```


True หากข้อความถูกห่อหุ้มที่ขอบของ TextFrame. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```


คืนค่า หรือกำหนดตำแหน่งยึดแนวตั้งของข้อความใน TextFrame. อ่าน/เขียน [TextAnchorType](../../com.aspose.slides/textanchortype).

**คืนค่า:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```


คืนค่า หรือกำหนดตำแหน่งยึดแนวตั้งของข้อความใน TextFrame. อ่าน/เขียน [TextAnchorType](../../com.aspose.slides/textanchortype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```


If NullableBool.True then text should be centered in box horizontally. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```


If NullableBool.True then text should be centered in box horizontally. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```


กำหนดการวางแนวข้อความ. ค่าที่ได้ของการหมุนข้อความที่มองเห็นสรุปจากคุณสมบัตินี้และมุมที่กำหนดเองในคุณสมบัติ RotationAngle. อ่าน/เขียน [TextVerticalType](../../com.aspose.slides/textverticaltype).

**คืนค่า:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```


กำหนดการวางแนวข้อความ. ค่าที่ได้ของการหมุนข้อความที่มองเห็นสรุปจากคุณสมบัตินี้และมุมที่กำหนดเองในคุณสมบัติ RotationAngle. อ่าน/เขียน [TextVerticalType](../../com.aspose.slides/textverticaltype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```


คืนค่า หรือกำหนดโหมด autofit ของข้อความ. อ่าน/เขียน [TextAutofitType](../../com.aspose.slides/textautofittype).

**คืนค่า:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```


คืนค่า หรือกำหนดโหมด autofit ของข้อความ. อ่าน/เขียน [TextAutofitType](../../com.aspose.slides/textautofittype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```


คืนค่า หรือกำหนดจำนวนคอลัมน์ในพื้นที่ข้อความ. ค่านี้ต้องเป็นจำนวนบวก มิฉะนั้นจะตั้งค่าเป็นศูนย์. ค่า 0 หมายถึงค่าไม่กำหนด. อ่าน/เขียน int.

**คืนค่า:**
int
### setColumnCount(int value) {#setColumnCount-int-}
```
public abstract void setColumnCount(int value)
```


คืนค่า หรือกำหนดจำนวนคอลัมน์ในพื้นที่ข้อความ. ค่านี้ต้องเป็นจำนวนบวก มิฉะนั้นจะตั้งค่าเป็นศูนย์. ค่า 0 หมายถึงค่าไม่กำหนด. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getColumnSpacing() {#getColumnSpacing--}
```
public abstract double getColumnSpacing()
```


คืนค่า หรือกำหนดระยะห่างระหว่างคอลัมน์ข้อความในพื้นที่ข้อความ (points). ควรใช้เฉพาะเมื่อมีคอลัมน์มากกว่า 1. ค่านี้ต้องเป็นจำนวนบวก มิฉะนั้นจะตั้งค่าเป็นศูนย์. อ่าน/เขียน double.

**คืนค่า:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public abstract void setColumnSpacing(double value)
```


คืนค่า หรือกำหนดระยะห่างระหว่างคอลัมน์ข้อความในพื้นที่ข้อความ (points). ควรใช้เฉพาะเมื่อมีคอลัมน์มากกว่า 1. ค่านี้ต้องเป็นจำนวนบวก มิฉะนั้นจะตั้งค่าเป็นศูนย์. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```


คืนค่าออบเจกต์ ThreeDFormat ที่แสดงคุณสมบัติเพื่อสร้างเอฟเฟกต์ 3 มิติสำหรับข้อความ. อ่านอย่างเดียว [IThreeDFormat](../../com.aspose.slides/ithreedformat).

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
>      // ตั้งค่า Contour
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // ตั้งค่า Depth
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // ตั้งค่า Material
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      // ตั้งค่า Lighting
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      // ตั้งค่า camera type
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


คืนค่า หรือกำหนดการเก็บข้อความให้อยู่นอกฉาก 3D ทั้งหมด. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public abstract void setKeepTextFlat(boolean value)
```


คืนค่า หรือกำหนดการเก็บข้อความให้อยู่นอกฉาก 3D ทั้งหมด. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```


ระบุการหมุนแบบกำหนดเองที่นำไปใช้กับข้อความภายในกล่องรอบขอบ. หากไม่ได้ระบุ จะใช้การหมุนของรูปร่างที่เกี่ยวข้อง. หากระบุแล้ว จะถูกนำไปใช้แยกจากรูปร่าง. นั่นคือรูปร่างอาจมีการหมุนเพิ่มเติมในขณะที่ข้อความเองก็มีการหมุนของมันเอง. ค่าที่ได้ของการหมุนข้อความที่มองเห็นสรุปจากคุณสมบัตินี้และประเภทแนวตั้งที่กำหนดไว้ในคุณสมบัติ TextVerticalType. อ่าน/เขียน float.

--------------------

> ```
> พิจารณากรณีที่รูปทรงมีการหมุน 90 องศาตามเข็มนาฬิกา
>  นอกจากนี้ ส่วนข้อความเองยังมีการหมุน -90 องศาตรงกันข้าม
>  จากนั้นรูปทรงที่ได้จะดูเหมือนถูกหมุน
>  แต่ข้อความภายในจะดูเหมือนว่าไม่ได้ถูกหมุนเลย
```

**คืนค่า:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```


ระบุการหมุนแบบกำหนดเองที่นำไปใช้กับข้อความภายในกล่องรอบขอบ. หากไม่ได้ระบุ จะใช้การหมุนของรูปร่างที่เกี่ยวข้อง. หากระบุแล้ว จะถูกนำไปใช้แยกจากรูปร่าง. นั่นคือรูปร่างอาจมีการหมุนเพิ่มเติมในขณะที่ข้อความเองก็มีการหมุนของมันเอง. ค่าที่ได้ของการหมุนข้อความที่มองเห็นสรุปจากคุณสมบัตินี้และประเภทแนวตั้งที่กำหนดไว้ในคุณสมบัติ TextVerticalType. อ่าน/เขียน float.

--------------------

> ```
> พิจารณากรณีที่รูปทรงมีการหมุน 90 องศาตามเข็มนาฬิกา 
>  นอกจากนี้ ส่วนข้อความเองยังมีการหมุน -90 องศาตรงกันข้าม 
>  จากนั้นรูปทรงที่ได้จะดูเหมือนถูกหมุน 
>  แต่ข้อความภายในจะดูเหมือนว่าไม่ได้ถูกหมุนเลย
```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public abstract byte getTransform()
```


รับหรือกำหนดรูปแบบการห่อหุ้มข้อความ. อ่าน/เขียน [TextShapeType](../../com.aspose.slides/textshapetype).

**คืนค่า:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public abstract void setTransform(byte value)
```


รับหรือกำหนดรูปแบบการห่อหุ้มข้อความ. อ่าน/เขียน [TextShapeType](../../com.aspose.slides/textshapetype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public abstract ITextFrameFormatEffectiveData getEffective()
```


รับข้อมูลการจัดรูปแบบของ text frame ที่มีการสืบทอดค่าแล้ว.

**คืนค่า:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).