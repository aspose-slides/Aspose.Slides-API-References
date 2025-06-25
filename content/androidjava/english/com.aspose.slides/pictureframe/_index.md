---
title: PictureFrame
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a frame with a picture inside.
type: docs
url: /com.aspose.slides/pictureframe/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**All Implemented Interfaces:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public class PictureFrame extends GeometryShape implements IPictureFrame
```

Represents a frame with a picture inside.

--------------------

> ```
> The following examples shows how to change Audio Frame Thumbnail.
>  
>  Presentation presentation = new Presentation();
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Adds an audio frame to the slide with a specified position and size.
>      FileInputStream audioStream = new FileInputStream("sample2.mp3");
>      IAudioFrame audioFrame = slide.getShapes().addAudioFrameEmbedded(150, 100, 50, 50, audioStream);
>      audioStream.close();
>      // Adds an image to presentation resources.
>      FileInputStream imageStream = new FileInputStream("eagle.jpeg");
>      IPPImage audioImage = presentation.getImages().addImage(imageStream);
>      imageStream.close();
>      // Sets the image for the audio frame.
>      audioFrame.getPictureFormat().getPicture().setImage(audioImage);
>      //Saves the modified presentation to disk
>      presentation.save("example_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
## Methods

| Method | Description |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | Returns shape's locks. |
| [getShapeType()](#getShapeType--) |  |
| [setShapeType(int value)](#setShapeType-int-) |  |
| [getPictureFormat()](#getPictureFormat--) | Returns the PictureFillFormat object for a picture frame. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | Returns or sets the scale of height(relative to original picture size) of the picture frame. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | Returns or sets the scale of height(relative to original picture size) of the picture frame. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | Returns or sets the scale of width (relative to original picture size) of the picture frame. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | Returns or sets the scale of width (relative to original picture size) of the picture frame. |
| [isCameo()](#isCameo--) | Determines whether the PictureFrame is Cameo object or not. |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public final IPictureFrameLock getPictureFrameLock()
```


Returns shape's locks. Read-only [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**Returns:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```


Returns or sets the AutoShape type for a PictureFrame. There are allowable all items of the set [ShapeType](../../com.aspose.slides/shapetype), except all sorts of lines:

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

Read/write [ShapeType](../../com.aspose.slides/shapetype).

**Returns:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```


Returns or sets the AutoShape type for a PictureFrame. There are allowable all items of the set [ShapeType](../../com.aspose.slides/shapetype), except all sorts of lines:

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

Read/write [ShapeType](../../com.aspose.slides/shapetype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPictureFormat() {#getPictureFormat--}
```
public final IPictureFillFormat getPictureFormat()
```


Returns the PictureFillFormat object for a picture frame. Read-only [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Returns:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public final float getRelativeScaleHeight()
```


Returns or sets the scale of height(relative to original picture size) of the picture frame. Value 1.0 corresponds to 100%. Read/write  float .

**Returns:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public final void setRelativeScaleHeight(float value)
```


Returns or sets the scale of height(relative to original picture size) of the picture frame. Value 1.0 corresponds to 100%. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public final float getRelativeScaleWidth()
```


Returns or sets the scale of width (relative to original picture size) of the picture frame. Value 1.0 corresponds to 100%. Read/write  float .

**Returns:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public final void setRelativeScaleWidth(float value)
```


Returns or sets the scale of width (relative to original picture size) of the picture frame. Value 1.0 corresponds to 100%. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### isCameo() {#isCameo--}
```
public final boolean isCameo()
```


Determines whether the PictureFrame is Cameo object or not. Read only boolean.

**Returns:**
boolean
