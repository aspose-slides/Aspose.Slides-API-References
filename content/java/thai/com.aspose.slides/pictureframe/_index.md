---
title: PictureFrame
second_title: Aspose.Slides สำหรับอ้างอิง API ของ Java
description: แสดงถึงเฟรมที่มีรูปภาพอยู่ภายใน
type: docs
url: /th/com.aspose.slides/pictureframe/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public class PictureFrame extends GeometryShape implements IPictureFrame
```

แสดงถึงเฟรมที่มีรูปภาพอยู่ภายใน.

--------------------

> ```
> The following examples shows how to change Audio Frame Thumbnail.
>  
>  Presentation presentation = new Presentation();
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Adds an audio frame to the slide with a specified position and size.
>      // เพิ่มกรอบเสียงลงในสไลด์ด้วยตำแหน่งและขนาดที่กำหนด.
>      FileInputStream audioStream = new FileInputStream("sample2.mp3");
>      IAudioFrame audioFrame = slide.getShapes().addAudioFrameEmbedded(150, 100, 50, 50, audioStream);
>      audioStream.close();
>      // Adds an image to presentation resources.
>      // เพิ่มภาพลงในทรัพยากรของงานนำเสนอ.
>      FileInputStream imageStream = new FileInputStream("eagle.jpeg");
>      IPPImage audioImage = presentation.getImages().addImage(imageStream);
>      imageStream.close();
>      // Sets the image for the audio frame.
>      // ตั้งค่าภาพสำหรับกรอบเสียง.
>      audioFrame.getPictureFormat().getPicture().setImage(audioImage);
>      //Saves the modified presentation to disk
>      //บันทึกงานนำเสนอที่แก้ไขแล้วลงดิสก์
>      presentation.save("example_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

## เมธอด

| Method | Description |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | คืนค่า lock ของ shape. |
| [getShapeType()](#getShapeType--) |  |
| [setShapeType(int value)](#setShapeType-int-) |  |
| [getPictureFormat()](#getPictureFormat--) | คืนค่าวัตถุ PictureFillFormat สำหรับเฟรมรูปภาพ. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | คืนค่า หรือ ตั้งสเกลของความสูง (สัมพันธ์กับขนาดรูปภาพต้นฉบับ) ของเฟรมรูปภาพ. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | คืนค่า หรือ ตั้งสเกลของความสูง (สัมพันธ์กับขนาดรูปภาพต้นฉบับ) ของเฟรมรูปภาพ. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | คืนค่า หรือ ตั้งสเกลของความกว้าง (สัมพันธ์กับขนาดรูปภาพต้นฉบับ) ของเฟรมรูปภาพ. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | คืนค่า หรือ ตั้งสเกลของความกว้าง (สัมพันธ์กับขนาดรูปภาพต้นฉบับ) ของเฟรมรูปภาพ. |
| [isCameo()](#isCameo--) | กำหนดว่าผลลัพธ์ PictureFrame เป็นอ็อบเจ็กต์ Cameo หรือไม่. |

### getPictureFrameLock() {#getPictureFrameLock--}
```
public final IPictureFrameLock getPictureFrameLock()
```

คืนค่า lock ของ shape. อ่านอย่างเดียว [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**คืนค่า:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)

### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

คืนค่า หรือ ตั้งค่าชนิด AutoShape สำหรับ PictureFrame. มีรายการที่อนุญาตทั้งหมดในเซ็ต [ShapeType](../../com.aspose.slides/shapetype) ยกเว้นประเภทของเส้นต่าง ๆ:

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

อ่านเขียน [ShapeType](../../com.aspose.slides/shapetype).

**คืนค่า:**
int

### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

คืนค่า หรือ ตั้งค่าชนิด AutoShape สำหรับ PictureFrame. มีรายการที่อนุญาตทั้งหมดในเซ็ต [ShapeType](../../com.aspose.slides/shapetype) ยกเว้นประเภทของเส้นต่าง ๆ:

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

อ่านเขียน [ShapeType](../../com.aspose.slides/shapetype).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPictureFormat() {#getPictureFormat--}
```
public final IPictureFillFormat getPictureFormat()
```

คืนค่าวัตถุ PictureFillFormat สำหรับเฟรมรูปภาพ. อ่านอย่างเดียว [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**คืนค่า:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public final float getRelativeScaleHeight()
```

คืนค่า หรือ ตั้งสเกลของความสูง (สัมพันธ์กับขนาดรูปภาพต้นฉบับ) ของเฟรมรูปภาพ. ค่า 1.0 เท่ากับ 100%. อ่านเขียน  float .

**คืนค่า:**
float

### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public final void setRelativeScaleHeight(float value)
```

คืนค่า หรือ ตั้งสเกลของความสูง (สัมพันธ์กับขนาดรูปภาพต้นฉบับ) ของเฟรมรูปภาพ. ค่า 1.0 เท่ากับ 100%. อ่านเขียน  float .

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public final float getRelativeScaleWidth()
```

คืนค่า หรือ ตั้งสเกลของความกว้าง (สัมพันธ์กับขนาดรูปภาพต้นฉบับ) ของเฟรมรูปภาพ. ค่า 1.0 เท่ากับ 100%. อ่านเขียน  float .

**คืนค่า:**
float

### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public final void setRelativeScaleWidth(float value)
```

คืนค่า หรือ ตั้งสเกลของความกว้าง (สัมพันธ์กับขนาดรูปภาพต้นฉบับ) ของเฟรมรูปภาพ. ค่า 1.0 เท่ากับ 100%. อ่านเขียน  float .

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### isCameo() {#isCameo--}
```
public final boolean isCameo()
```

กำหนดว่าผลลัพธ์ PictureFrame เป็นอ็อบเจ็กต์ Cameo หรือไม่. อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean