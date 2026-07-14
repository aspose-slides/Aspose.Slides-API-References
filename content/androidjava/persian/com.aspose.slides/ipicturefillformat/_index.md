---
title: IPictureFillFormat
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: یک سبک پر کردن تصویر را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/ipicturefillformat/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormat extends IFillParamSource
```

نمایانگر یک سبک پر کردن تصویر است.
## متدها

| متد | توضیح |
| --- | --- |
| [getDpi()](#getDpi--) | مقدار dpi را که برای پر کردن تصویر استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [setDpi(int value)](#setDpi-int-) | مقدار dpi را که برای پر کردن تصویر استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [getPictureFillMode()](#getPictureFillMode--) | حالت پر کردن تصویر را برمی‌گرداند یا تنظیم می‌کند. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | حالت پر کردن تصویر را برمی‌گرداند یا تنظیم می‌کند. |
| [getPicture()](#getPicture--) | تصویر را برمی‌گرداند. |
| [getCropLeft()](#getCropLeft--) | درصد-های عرض واقعی تصویر که از سمت چپ تصویر برش خورده‌اند را برمی‌گرداند یا تنظیم می‌کند. |
| [setCropLeft(float value)](#setCropLeft-float-) | درصد-های عرض واقعی تصویر که از سمت چپ تصویر برش خورده‌اند را برمی‌گرداند یا تنظیم می‌کند. |
| [getCropTop()](#getCropTop--) | درصد-های ارتفاع واقعی تصویر که از سمت بالا تصویر برش خورده‌اند را برمی‌گرداند یا تنظیم می‌کند. |
| [setCropTop(float value)](#setCropTop-float-) | درصد-های ارتفاع واقعی تصویر که از سمت بالا تصویر برش خورده‌اند را برمی‌گرداند یا تنظیم می‌کند. |
| [getCropRight()](#getCropRight--) | درصد-های عرض واقعی تصویر که از سمت راست تصویر برش خورده‌اند را برمی‌گرداند یا تنظیم می‌کند. |
| [setCropRight(float value)](#setCropRight-float-) | درصد-های عرض واقعی تصویر که از سمت راست تصویر برش خورده‌اند را برمی‌گرداند یا تنظیم می‌کند. |
| [getCropBottom()](#getCropBottom--) | درصد-های ارتفاع واقعی تصویر که از سمت پایین تصویر برش خورده‌اند را برمی‌گرداند یا تنظیم می‌کند. |
| [setCropBottom(float value)](#setCropBottom-float-) | درصد-های ارتفاع واقعی تصویر که از سمت پایین تصویر برش خورده‌اند را برمی‌گرداند یا تنظیم می‌کند. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | لبهٔ چپ مستطیل پرکننده را که با درصدی نسبت به لبهٔ چپ جعبهٔ مرزی شکل تعریف می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | لبهٔ چپ مستطیل پرکننده را که با درصدی نسبت به لبهٔ چپ جعبهٔ مرزی شکل تعریف می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | لبهٔ بالای مستطیل پرکننده را که با درصدی نسبت به لبهٔ بالا جعبهٔ مرزی شکل تعریف می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | لبهٔ بالای مستطیل پرکننده را که با درصدی نسبت به لبهٔ بالا جعبهٔ مرزی شکل تعریف می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | لبهٔ راست مستطیل پرکننده را که با درصدی نسبت به لبهٔ راست جعبهٔ مرزی شکل تعریف می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | لبهٔ راست مستطیل پرکننده را که با درصدی نسبت به لبهٔ راست جعبهٔ مرزی شکل تعریف می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | لبهٔ پایین مستطیل پرکننده را که با درصدی نسبت به لبهٔ پایین جعبهٔ مرزی شکل تعریف می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | لبهٔ پایین مستطیل پرکننده را که با درصدی نسبت به لبهٔ پایین جعبهٔ مرزی شکل تعریف می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | نواحی برش‌خوردهٔ Picture را حذف می‌کند. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | تصویر را با کاهش اندازهٔ آن بر اساس اندازهٔ شکل و وضوح مشخص‌شده فشرده می‌کند. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | تصویر را با کاهش اندازهٔ آن بر اساس اندازهٔ شکل و وضوح مشخص‌شده فشرده می‌کند. |
| [getTileOffsetX()](#getTileOffsetX--) | افست افقی تکستچر نسبت به مبدأ شکل را بر حسب نقطه برمی‌گرداند یا تنظیم می‌کند. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | افست افقی تکستچر نسبت به مبدأ شکل را بر حسب نقطه برمی‌گرداند یا تنظیم می‌کند. |
| [getTileOffsetY()](#getTileOffsetY--) | افست عمودی تکستچر نسبت به مبدأ شکل را بر حسب نقطه برمی‌گرداند یا تنظیم می‌کند. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | افست عمودی تکستچر نسبت به مبدأ شکل را بر حسب نقطه برمی‌گرداند یا تنظیم می‌کند. |
| [getTileScaleX()](#getTileScaleX--) | مقیاس افقی پر کردن تکستچر را به‌صورت درصد برمی‌گرداند یا تنظیم می‌کند. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | مقیاس افقی پر کردن تکستچر را به‌صورت درصد برمی‌گرداند یا تنظیم می‌کند. |
| [getTileScaleY()](#getTileScaleY--) | مقیاس عمودی پر کردن تکستچر را به‌صورت درصد برمی‌گرداند یا تنظیم می‌کند. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | مقیاس عمودی پر کردن تکستچر را به‌صورت درصد برمی‌گرداند یا تنظیم می‌کند. |
| [getTileAlignment()](#getTileAlignment--) | نحوهٔ تراز تکستچر داخل شکل را برمی‌گرداند یا تنظیم می‌کند. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | نحوهٔ تراز تکستچر داخل شکل را برمی‌گرداند یا تنظیم می‌کند. |
| [getTileFlip()](#getTileFlip--) | کاشی تکستچر را حول محور افقی، عمودی یا هر دو محور می‌چرخاند. |
| [setTileFlip(int value)](#setTileFlip-int-) | کاشی تکستچر را حول محور افقی، عمودی یا هر دو محور می‌چرخاند. |

### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

مقدار dpi را که برای پر کردن تصویر استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی int.

**بازگشت:**
int

### setDpi(int value) {#setDpi-int-}
```
public abstract void setDpi(int value)
```

مقدار dpi را که برای پر کردن تصویر استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

حالت پر کردن تصویر را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [PictureFillMode](../../com.aspose.slides/picturefillmode).

**بازگشت:**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public abstract void setPictureFillMode(int value)
```

حالت پر کردن تصویر را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [PictureFillMode](../../com.aspose.slides/picturefillmode).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

تصویر را برمی‌گرداند. فقط-خواندنی [ISlidesPicture](../../com.aspose.slides/islidespicture).

**بازگشت:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```

درصد-های عرض واقعی تصویر که از سمت چپ تصویر برش خورده‌اند را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

**بازگشت:**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public abstract void setCropLeft(float value)
```

درصد-های عرض واقعی تصویر که از سمت چپ تصویر برش خورده‌اند را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

درصد-های ارتفاع واقعی تصویر که از سمت بالا تصویر برش خورده‌اند را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

**بازگشت:**
float

### setCropTop(float value) {#setCropTop-float-}
```
public abstract void setCropTop(float value)
```

درصد-های ارتفاع واقعی تصویر که از سمت بالا تصویر برش خورده‌اند را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

درصد-های عرض واقعی تصویر که از سمت راست تصویر برش خورده‌اند را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

**بازگشت:**
float

### setCropRight(float value) {#setCropRight-float-}
```
public abstract void setCropRight(float value)
```

درصد-های عرض واقعی تصویر که از سمت راست تصویر برش خورده‌اند را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

درصد-های ارتفاع واقعی تصویر که از سمت پایین تصویر برش خورده‌اند را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

**بازگشت:**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public abstract void setCropBottom(float value)
```

درصد-های ارتفاع واقعی تصویر که از سمت پایین تصویر برش خورده‌اند را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetLeft() {#getStretchOffsetLeft--}
```
public abstract float getStretchOffsetLeft()
```

لبهٔ چپ مستطیل پرکننده را که با درصدی نسبت به لبهٔ چپ جعبهٔ مرزی شکل تعریف می‌شود، برمی‌گرداند یا تنظیم می‌کند. درصد مثبت نشاندهندهٔ داخل‌زدن، درصد منفی نشاندهندهٔ بیرون‌زدن است. خواندنی/نوشتنی float.

**بازگشت:**
float

### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public abstract void setStretchOffsetLeft(float value)
```

لبهٔ چپ مستطیل پرکننده را که با درصدی نسبت به لبهٔ چپ جعبهٔ مرزی شکل تعریف می‌شود، برمی‌گرداند یا تنظیم می‌کند. درصد مثبت نشاندهندهٔ داخل‌زدن، درصد منفی نشاندهندهٔ بیرون‌زدن است. خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetTop() {#getStretchOffsetTop--}
```
public abstract float getStretchOffsetTop()
```

لبهٔ بالای مستطیل پرکننده را که با درصدی نسبت به لبهٔ بالا جعبهٔ مرزی شکل تعریف می‌شود، برمی‌گرداند یا تنظیم می‌کند. درصد مثبت نشاندهندهٔ داخل‌زدن، درصد منفی نشاندهندهٔ بیرون‌زدن است. خواندنی/نوشتنی float.

**بازگشت:**
float

### setStretchOffsetTop(float value) {#setStretchOffsetTop-float-}
```
public abstract void setStretchOffsetTop(float value)
```

لبهٔ بالای مستطیل پرکننده را که با درصدی نسبت به لبهٔ بالا جعبهٔ مرزی شکل تعریف می‌شود، برمی‌گرداند یا تنظیم می‌کند. درصد مثبت نشاندهندهٔ داخل‌زدن، درصد منفی نشاندهندهٔ بیرون‌زدن است. خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetRight() {#getStretchOffsetRight--}
```
public abstract float getStretchOffsetRight()
```

لبهٔ راست مستطیل پرکننده را که با درصدی نسبت به لبهٔ راست جعبهٔ مرزی شکل تعریف می‌شود، برمی‌گرداند یا تنظیم می‌کند. درصد مثبت نشاندهندهٔ داخل‌زدن، درصد منفی نشاندهندهٔ بیرون‌زدن است. خواندنی/نوشتنی float.

**بازگشت:**
float

### setStretchOffsetRight(float value) {#setStretchOffsetRight-float-}
```
public abstract void setStretchRight(float value)
```

لبهٔ راست مستطیل پرکننده را که با درصدی نسبت به لبهٔ راست جعبهٔ مرزی شکل تعریف می‌شود، برمی‌گرداند یا تنظیم می‌کند. درصد مثبت نشاندهندهٔ داخل‌زدن، درصد منفی نشاندهندهٔ بیرون‌زدن است. خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetBottom() {#getStretchOffsetBottom--}
```
public abstract float getStretchOffsetBottom()
```

لبهٔ پایین مستطیل پرکننده را که با درصدی نسبت به لبهٔ پایین جعبهٔ مرزی شکل تعریف می‌شود، برمی‌گرداند یا تنظیم می‌کند. درصد مثبت نشاندهندهٔ داخل‌زدن، درصد منفی نشاندهندهٔ بیرون‌زدن است. خواندنی/نوشتنی float.

**بازگشت:**
float

### setStretchOffsetBottom(float value) {#setStretchOffsetBottom-float-}
```
public abstract void setStretchOffsetBottom(float value)
```

لبهٔ پایین مستطیل پرکننده را که با درصدی نسبت به لبهٔ پایین جعبهٔ مرزی شکل تعریف می‌شود، برمی‌گرداند یا تنظیم می‌کند. درصد مثبت نشاندهندهٔ داخل‌زدن، درصد منفی نشاندهندهٔ بیرون‌زدن است. خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public abstract IPPImage deletePictureCroppedAreas()
```

ناحیه‌های برش‌خوردهٔ Picture را حذف می‌کند.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // دریافت PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // ناحیه‌های برش‌خوردهٔ تصویر PictureFrame را حذف می‌کند
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**بازگشت:**
[IPPImage](../../com.aspose.slides/ippimage) - تصویر برش‌خورده یا تصویر اصلی اگر برش لازم نباشد.

--------------------

این متد فایل‌های متافایل WMF/EMF را به تصویر raster PNG تبدیل می‌کند و در هنگام تبدیل آن را برش می‌دهد.
### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

تصویر را با کاهش اندازهٔ آن بر اساس اندازهٔ شکل و وضوح مشخص‌شده فشرده می‌کند. در صورت نیاز، نواحی برش‌خورده را نیز حذف می‌کند.

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` متد برای کاهش حجم یک تصویر در ارائه با تنظیم وضوح هدف و حذف نواحی برش‌خورده:
>  
>  Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Compress the image with a target resolution of 150 DPI (Web resolution) and remove cropped areas
>      boolean result = picFrame.getPictureFormat().compressImage(true, PicturesCompression.Dpi150);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| deleteCroppedAreasOfImage | boolean | If true, the method will remove the cropped areas of the image, potentially further reducing its size. |
| resolution | int | The target resolution for compression, specified as a value of the [PicturesCompression](../../com.aspose.slides/picturescompression) enum.

--------------------

This method changes the image's size and resolution similar to PowerPoint's "Picture Format -> Compress Pictures" feature. |

**Returns:**
boolean - A boolean indicating whether the image was successfully compressed. Returns true if the image was resized or cropped, otherwise false.
### compressImage(boolean deleteCroppedAreasOfImage, float resolution) {#compressImage-boolean-float-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, float resolution)
```


Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas.

--------------------

> ```
> مثال زیر نشان می‌دهد چگونه می‌توان از متد ```
> CompressImage
> ``` برای کاهش حجم تصویر در ارائه با تنظیم وضوح هدف و حذف نواحی برش‌خورده استفاده کرد:
>   
>  Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Compress the image with a target resolution of 150 DPI (Web resolution) and remove cropped areas
>      boolean result = picFrame.getPictureFormat().compressImage(true, 150f); // Web resolution
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| deleteCroppedAreasOfImage | boolean | If true, the method will remove the cropped areas of the image, potentially further reducing its size. |
| resolution | float | The target resolution in DPI. This value must be positive and defines how the image will be resized.

--------------------

This method changes the image's size and resolution similar to PowerPoint's "Picture Format -> Compress Pictures" feature. |

**Returns:**
boolean - A boolean indicating whether the image was successfully compressed. Returns true if the image was resized or cropped, otherwise false.
### getTileOffsetX() {#getTileOffsetX--}
```
public abstract float getTileOffsetX()
```


Returns or sets the horizontal offset of the texture from the shape's origin in points. A positive value moves the texture to the right, while a negative value moves it to the left. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the horizontal offset of the texture to 20 points
>      pictureFillFormat.setTileOffsetX(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
float
### setTileOffsetX(float value) {#setTileOffsetX-float-}
```
public abstract void setTileOffsetX(float value)
```


Returns or sets the horizontal offset of the texture from the shape's origin in points. A positive value moves the texture to the right, while a negative value moves it to the left. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the horizontal offset of the texture to 20 points
>      pictureFillFormat.setTileOffsetX(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTileOffsetY() {#getTileOffsetY--}
```
public abstract float getTileOffsetY()
```


Returns or sets the vertical offset of the texture from the shape's origin in points. A positive value moves the texture down, while a negative value moves it up. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the vertical offset of the texture to -50 points
>      pictureFillFormat.setTileOffsetY(-50);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
float
### setTileOffsetY(float value) {#setTileOffsetY-float-}
```
public abstract void setTileOffsetY(float value)
```


Returns or sets the vertical offset of the texture from the shape's origin in points. A positive value moves the texture down, while a negative value moves it up. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the vertical offset of the texture to -50 points
>      pictureFillFormat.setTileOffsetY(-50);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTileScaleX() {#getTileScaleX--}
```
public abstract float getTileScaleX()
```


Returns or sets the horizontal scale for the texture fill as a percentage. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the horizontal scale for the texture to 120 percents
>      pictureFillFormat.setTileScaleX(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**Returns:**
float
### setTileScaleX(float value) {#setTileScaleX-float-}
```
public abstract void setTileScaleX(float value)
```


Returns or sets the horizontal scale for the texture fill as a percentage. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the horizontal scale for the texture to 120 percents
>      pictureFillFormat.setTileScaleX(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTileScaleY() {#getTileScaleY--}
```
public abstract float getTileScaleY()
```


Returns or sets the vertical scale for the texture fill as a percentage. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the vertical scale for the texture to 120 percents
>      pictureFillFormat.setTileScaleY(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
float
### setTileScaleY(float value) {#setTileOffsetY-float-}
```
public abstract void setTileScaleY(float value)
```


Returns or sets the vertical scale for the texture fill as a percentage. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the vertical scale for the texture to 120 percents
>      pictureFillFormat.setTileScaleY(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTileAlignment() {#getTileAlignment--}
```
public abstract byte getTileAlignment()
```


Returns or sets how the texture is aligned within the shape. This setting controls the starting point of the texture pattern and how it repeats across the shape. Read/write [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the alignment for the tiling to the right bottom
>      pictureFillFormat.setTileAlignment(RectangleAlignment.BottomRight);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
--------------------

Default is [RectangleAlignment.TopLeft](../../com.aspose.slides/rectanglealignment\#TopLeft).

**Returns:**
byte
### setTileAlignment(byte value) {#setTileAlignment-byte-}
```
public abstract void setTileAlignment(byte value)
```


Returns or sets how the texture is aligned within the shape. This setting controls the starting point of the texture pattern and how it repeats across the shape. Read/write [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the alignment for the tiling to the right bottom
>      pictureFillFormat.setTileAlignment(RectangleAlignment.BottomRight);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
--------------------

Default is [RectangleAlignment.TopLeft](../../com.aspose.slides/rectanglealignment\#TopLeft).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```


Flips the texture tile around its horizontal, vertical or both axis. Read/write [TileFlip](../../com.aspose.slides/tileflip).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Flips the texture tile around its vertical axis.
>      pictureFillFormat.setTileFlip(TileFlip.FlipY);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
--------------------

Default is [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**Returns:**
int
### setTileFlip(int value) {#setTileFlip-int-}
```
public abstract void setTileFlip(int value)
```


Flips the texture tile around its horizontal, vertical or both axis. Read/write [TileFlip](../../com.aspose.slides/tileflip).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Flips the texture tile around its vertical axis.
>      pictureFillFormat.setTileFlip(TileFlip.FlipY);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

--------------------

پیش‌فرض [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip) است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |