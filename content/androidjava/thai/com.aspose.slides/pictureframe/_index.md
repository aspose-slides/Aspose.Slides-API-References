---
title: PictureFrame
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นเฟรมที่มีรูปภาพอยู่ภายใน.
type: docs
url: /th/com.aspose.slides/pictureframe/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**All Implemented Interfaces:**  
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)  
```
public class PictureFrame extends GeometryShape implements IPictureFrame
```

แทนความหมายของเฟรมที่มีรูปภาพอยู่ภายใน.

--------------------

> ```
> The following examples shows how to change Audio Frame Thumbnail.
>  
>  Presentation presentation = new Presentation();
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // เพิ่ม audio frame ลงในสไลด์ด้วยตำแหน่งและขนาดที่ระบุ.
>      FileInputStream audioStream = new FileInputStream("sample2.mp3");
>      IAudioFrame audioFrame = slide.getShapes().addAudioFrameEmbedded(150, 100, 50, 50, audioStream);
>      audioStream.close();
>      // เพิ่มรูปภาพลงในทรัพยากรของงานนำเสนอ.
>      FileInputStream imageStream = new FileInputStream("eagle.jpeg");
>      IPPImage audioImage = presentation.getImages().addImage(imageStream);
>      imageStream.close();
>      // ตั้งค่ารูปภาพสำหรับ audio frame.
>      audioFrame.getPictureFormat().getPicture().setImage(audioImage);
>      //บันทึกงานนำเสนอที่แก้ไขแล้วลงดิสก์
>      presentation.save("example_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | ส่งคืนล็อคของ shape. |
| [getShapeType()](#getShapeType--) |  |
| [setShapeType(int value)](#setShapeType-int-) |  |
| [getPictureFormat()](#getPictureFormat--) | ส่งคืนอ็อบเจ็กต์ PictureFillFormat สำหรับ picture frame. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | ส่งคืนหรือกำหนดสเกลของความสูง (อ้างอิงจากขนาดรูปภาพต้นฉบับ) ของ picture frame. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | ส่งคืนหรือกำหนดสเกลของความสูง (อ้างอิงจากขนาดรูปภาพต้นฉบับ) ของ picture frame. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | ส่งคืนหรือกำหนดสเกลของความกว้าง (อ้างอิงจากขนาดรูปภาพต้นฉบับ) ของ picture frame. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | ส่งคืนหรือกำหนดสเกลของความกว้าง (อ้างอิงจากขนาดรูปภาพต้นฉบับ) ของ picture frame. |
| [isCameo()](#isCameo--) | กำหนดว่า PictureFrame เป็นอ็อบเจ็กต์ Cameo หรือไม่. |

### getPictureFrameLock() {#getPictureFrameLock--}
```
public final IPictureFrameLock getPictureFrameLock()
```

ส่งคืนล็อคของ shape. อ่านอย่างเดียว [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**คืนค่า:**  
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)

### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

ส่งคืนหรือกำหนดประเภท AutoShape สำหรับ PictureFrame. มีรายการที่อนุญาตทั้งหมดในชุด [ShapeType](../../com.aspose.slides/shapetype) ยกเว้นประเภทของเส้นทั้งหมด:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5.

อ่าน/เขียน [ShapeType](../../com.aspose.slides/shapetype).

**คืนค่า:**  
int

### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

ส่งคืนหรือกำหนดประเภท AutoShape สำหรับ PictureFrame. มีรายการที่อนุญาตทั้งหมดในชุด [ShapeType](../../com.aspose.slides/shapetype) ยกเว้นประเภทของเส้นทั้งหมด:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5.

อ่าน/เขียน [ShapeType](../../com.aspose.slides/shapetype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPictureFormat() {#getPictureFormat--}
```
public final IPictureFillFormat getPictureFormat()
```

ส่งคืนอ็อบเจ็กต์ PictureFillFormat สำหรับ picture frame. อ่านอย่างเดียว [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**คืนค่า:**  
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public final float getRelativeScaleHeight()
```

ส่งคืนหรือกำหนดสเกลของความสูง (อ้างอิงจากขนาดรูปภาพต้นฉบับ) ของ picture frame. ค่า 1.0 สอดคล้องกับ 100%. อ่าน/เขียน  float .

**คืนค่า:**  
float

### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public final void setRelativeScaleHeight(float value)
```

ส่งคืนหรือกำหนดสเกลของความสูง (อ้างอิงจากขนาดรูปภาพต้นฉบับ) ของ picture frame. ค่า 1.0 สอดคล้องกับ 100%. อ่าน/เขียน  float .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public final float getRelativeScaleWidth()
```

ส่งคืนหรือกำหนดสเกลของความกว้าง (อ้างอิงจากขนาดรูปภาพต้นฉบับ) ของ picture frame. ค่า 1.0 สอดคล้องกับ 100%. อ่าน/เขียน  float .

**คืนค่า:**  
float

### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public final void setRelativeScaleWidth(float value)
```

ส่งคืนหรือกำหนดสเกลของความกว้าง (อ้างอิงจากขนาดรูปภาพต้นฉบับ) ของ picture frame. ค่า 1.0 สอดคล้องกับ 100%. อ่าน/เขียน  float .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### isCameo() {#isCameo--}
```
public final boolean isCameo()
```

กำหนดว่า PictureFrame เป็นอ็อบเจ็กต์ Cameo หรือไม่. อ่านอย่างเดียว boolean.

**คืนค่า:**  
boolean