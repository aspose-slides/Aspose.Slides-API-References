---
title: PictureFrame
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: یک قاب را که داخل آن یک تصویر قرار دارد نشان می‌دهد.
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

یک قاب را که داخل آن یک تصویر قرار دارد نشان می‌دهد.

--------------------

> ```
> The following examples shows how to change Audio Frame Thumbnail.
>  
>  Presentation presentation = new Presentation();
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // یک فریم صوتی را به اسلاید با موقعیت و اندازه مشخص اضافه می‌کند.
>      FileInputStream audioStream = new FileInputStream("sample2.mp3");
>      IAudioFrame audioFrame = slide.getShapes().addAudioFrameEmbedded(150, 100, 50, 50, audioStream);
>      audioStream.close();
>      // یک تصویر را به منابع ارائه اضافه می‌کند.
>      FileInputStream imageStream = new FileInputStream("eagle.jpeg");
>      IPPImage audioImage = presentation.getImages().addImage(imageStream);
>      imageStream.close();
>      // تصویر را برای فریم صوتی تنظیم می‌کند.
>      audioFrame.getPictureFormat().getPicture().setImage(audioImage);
>      //ذخیره ارائهٔ تغییر یافته در دیسک
>      presentation.save("example_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

## متدها

| Method | Description |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | قفل‌های شکل را برمی‌گرداند. |
| [getShapeType()](#getShapeType--) |  |
| [setShapeType(int value)](#setShapeType-int-) |  |
| [getPictureFormat()](#getPictureFormat--) | شیء PictureFillFormat را برای یک قاب تصویر برمی‌گرداند. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | مقیاس ارتفاع (نسبت به اندازهٔ تصویر اصلی) قاب تصویر را برمی‌گرداند یا تنظیم می‌کند. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | مقیاس ارتفاع (نسبت به اندازهٔ تصویر اصلی) قاب تصویر را برمی‌گرداند یا تنظیم می‌کند. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | مقیاس عرض (نسبت به اندازهٔ تصویر اصلی) قاب تصویر را برمی‌گرداند یا تنظیم می‌کند. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | مقیاس عرض (نسبت به اندازهٔ تصویر اصلی) قاب تصویر را برمی‌گرداند یا تنظیم می‌کند. |
| [isCameo()](#isCameo--) | تعیین می‌کند که آیا PictureFrame یک شیء Cameo است یا نه. |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public final IPictureFrameLock getPictureFrameLock()
```


قفل‌های شکل را برمی‌گرداند. فقط خواندنی [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**باز می‌گرداند:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```


نوع AutoShape را برای یک PictureFrame برمی‌گرداند یا تنظیم می‌کند. تمام موارد قابل‌استفاده در مجموعهٔ [ShapeType](../../com.aspose.slides/shapetype) هستند، به‌جز انواع خط‌ها:

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

خواندنی/نوشتنی [ShapeType](../../com.aspose.slides/shapetype).

**باز می‌گرداند:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```


نوع AutoShape را برای یک PictureFrame برمی‌گرداند یا تنظیم می‌کند. تمام موارد قابل‌استفاده در مجموعهٔ [ShapeType](../../com.aspose.slides/shapetype) هستند، به‌جز انواع خط‌ها:

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

خواندنی/نوشتنی [ShapeType](../../com.aspose.slides/shapetype).

پارامترها:
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPictureFormat() {#getPictureFormat--}
```
public final IPictureFillFormat getPictureFormat()
```


شیء PictureFillFormat را برای یک قاب تصویر برمی‌گرداند. فقط خواندنی [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**باز می‌گرداند:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public final float getRelativeScaleHeight()
```


مقیاس ارتفاع (نسبت به اندازهٔ تصویر اصلی) قاب تصویر را برمی‌گرداند یا تنظیم می‌کند. مقدار 1.0 برابر با 100٪ است. خواندنی/نوشتنی  float .

**باز می‌گرداند:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public final void setRelativeScaleHeight(float value)
```


مقیاس ارتفاع (نسبت به اندازهٔ تصویر اصلی) قاب تصویر را برمی‌گرداند یا تنظیم می‌کند. مقدار 1.0 برابر با 100٪ است. خواندنی/نوشتنی  float .

پارامترها:
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public final float getRelativeScaleWidth()
```


مقیاس عرض (نسبت به اندازهٔ تصویر اصلی) قاب تصویر را برمی‌گرداند یا تنظیم می‌کند. مقدار 1.0 برابر با 100٪ است. خواندنی/نوشتنی  float .

**باز می‌گرداند:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public final void setRelativeScaleWidth(float value)
```


مقیاس عرض (نسبت به اندازهٔ تصویر اصلی) قاب تصویر را برمی‌گرداند یا تنظیم می‌کند. مقدار 1.0 برابر با 100٪ است. خواندنی/نوشتنی  float .

پارامترها:
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### isCameo() {#isCameo--}
```
public final boolean isCameo()
```


تعیین می‌کند که آیا PictureFrame یک شیء Cameo است یا نه. فقط خواندنی boolean.

**باز می‌گرداند:**
boolean