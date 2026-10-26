---
title: PictureFrame
second_title: مرجع API Aspose.Slides برای جاوا
description: یک فریم با تصویر درون آن را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/pictureframe/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public class PictureFrame extends GeometryShape implements IPictureFrame
```

یک قاب حاوی تصویر را نشان می‌دهد.

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
## متدها

| متد | توضیح |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | قفل‌های شکل را باز می‌گرداند. |
| [getShapeType()](#getShapeType--) |  |
| [setShapeType(int value)](#setShapeType-int-) |  |
| [getPictureFormat()](#getPictureFormat--) | شیء PictureFillFormat را برای یک قاب تصویر باز می‌گرداند. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | مقیاس ارتفاع (نسبت به اندازه اصلی تصویر) قاب تصویر را باز می‌گرداند یا تنظیم می‌کند. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | مقیاس ارتفاع (نسبت به اندازه اصلی تصویر) قاب تصویر را باز می‌گرداند یا تنظیم می‌کند. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | مقیاس عرض (نسبت به اندازه اصلی تصویر) قاب تصویر را باز می‌گرداند یا تنظیم می‌کند. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | مقیاس عرض (نسبت به اندازه اصلی تصویر) قاب تصویر را باز می‌گرداند یا تنظیم می‌کند. |
| [isCameo()](#isCameo--) | تعیین می‌کند که آیا PictureFrame یک شیء Cameo است یا خیر. |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public final IPictureFrameLock getPictureFrameLock()
```


قفل‌های شکل را باز می‌گرداند. فقط-خواندنی [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**باز می‌گرداند:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```


نوع AutoShape را برای یک PictureFrame باز می‌گرداند یا تنظیم می‌کند. تمامی موارد قابل استفاده مجموعه [ShapeType](../../com.aspose.slides/shapetype) هستند، به‌جز انواع خط‌ها:

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

خواندنی-نوشتنی [ShapeType](../../com.aspose.slides/shapetype).

**باز می‌گرداند:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```


نوع AutoShape را برای یک PictureFrame باز می‌گرداند یا تنظیم می‌کند. تمامی موارد قابل استفاده مجموعه [ShapeType](../../com.aspose.slides/shapetype) هستند، به‌جز انواع خط‌ها:

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

خواندنی-نوشتنی [ShapeType](../../com.aspose.slides/shapetype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getPictureFormat() {#getPictureFormat--}
```
public final IPictureFillFormat getPictureFormat()
```


شیء PictureFillFormat را برای یک قاب تصویر باز می‌گرداند. فقط-خواندنی [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**باز می‌گرداند:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public final float getRelativeScaleHeight()
```


مقیاس ارتفاع (نسبت به اندازه اصلی تصویر) قاب تصویر را باز می‌گرداند یا تنظیم می‌کند. مقدار 1.0 برابر با 100٪ است. خواندنی-نوشتنی float .

**باز می‌گرداند:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public final void setRelativeScaleHeight(float value)
```


مقیاس ارتفاع (نسبت به اندازه اصلی تصویر) قاب تصویر را باز می‌گرداند یا تنظیم می‌کند. مقدار 1.0 برابر با 100٪ است. خواندنی-نوشتنی float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |
### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public final float getRelativeScaleWidth()
```


مقیاس عرض (نسبت به اندازه اصلی تصویر) قاب تصویر را باز می‌گرداند یا تنظیم می‌کند. مقدار 1.0 برابر با 100٪ است. خواندنی-نوشتنی float .

**باز می‌گرداند:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public final void setRelativeScaleWidth(float value)
```


مقیاس عرض (نسبت به اندازه اصلی تصویر) قاب تصویر را باز می‌گرداند یا تنظیم می‌کند. مقدار 1.0 برابر با 100٪ است. خواندنی-نوشتنی float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |
### isCameo() {#isCameo--}
```
public final boolean isCameo()
```


تشخیص می‌دهد که آیا PictureFrame یک شیء Cameo است یا خیر. فقط-خواندنی boolean.

**باز می‌گرداند:**
boolean