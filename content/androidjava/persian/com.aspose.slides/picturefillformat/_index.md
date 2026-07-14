---
title: PictureFillFormat
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایانگر یک سبک پر کردن تصویر است.
type: docs
url: /fa/com.aspose.slides/picturefillformat/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**تمام اینترفیس‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
```
public final class PictureFillFormat extends PVIObject implements IPictureFillFormat
```

نمایانگر یک سبک پرکردن تصویر است.
## متدها

| متد | توضیح |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDpi()](#getDpi--) | dpi را که برای پرکردن تصویر استفاده می‌شود، بر می‌گرداند یا تنظیم می‌کند. |
| [setDpi(int value)](#setDpi-int-) | dpi را که برای پرکردن تصویر استفاده می‌شود، بر می‌گرداند یا تنظیم می‌کند. |
| [getPictureFillMode()](#getPictureFillMode--) | حالت پرکردن تصویر را بر می‌گرداند یا تنظیم می‌کند. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | حالت پرکردن تصویر را بر می‌گرداند یا تنظیم می‌کند. |
| [getPicture()](#getPicture--) | تصویر را بر می‌گرداند. |
| [getCropLeft()](#getCropLeft--) | درصد عرض واقعی تصویر که از سمت چپ تصویر برش می‌خورد را بر می‌گرداند یا تنظیم می‌کند. |
| [setCropLeft(float value)](#setCropLeft-float-) | درصد عرض واقعی تصویر که از سمت چپ تصویر برش می‌خورد را بر می‌گرداند یا تنظیم می‌کند. |
| [getCropTop()](#getCropTop--) | درصد ارتفاع واقعی تصویر که از بالای تصویر برش می‌خورد را بر می‌گرداند یا تنظیم می‌کند. |
| [setCropTop(float value)](#setCropTop-float-) | درصد ارتفاع واقعی تصویر که از بالای تصویر برش می‌خورد را بر می‌گرداند یا تنظیم می‌کند. |
| [getCropRight()](#getCropRight--) | درصد عرض واقعی تصویر که از سمت راست تصویر برش می‌خورد را بر می‌گرداند یا تنظیم می‌کند. |
| [setCropRight(float value)](#setCropRight-float-) | درصد عرض واقعی تصویر که از سمت راست تصویر برش می‌خورد را بر می‌گرداند یا تنظیم می‌کند. |
| [getCropBottom()](#getCropBottom--) | درصد ارتفاع واقعی تصویر که از پایین تصویر برش می‌خورد را بر می‌گرداند یا تنظیم می‌کند. |
| [setCropBottom(float value)](#setCropBottom-float-) | درصد ارتفاع واقعی تصویر که از پایین تصویر برش می‌خورد را بر می‌گرداند یا تنظیم می‌کند. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | ناحیه‌های برش‌خورده‌ی تصویر پرکننده را حذف می‌کند. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | تصویر را با کاهش اندازه آن بر اساس اندازه شکل و وضوح مشخص‌شده فشرده می‌کند. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | تصویر را با کاهش اندازه آن بر اساس اندازه شکل و وضوح مشخص‌شده فشرده می‌کند. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | لبهٔ چپ مستطیل پرکننده را که با درصدی از لبهٔ چپ جعبهٔ محدودهٔ شکل تعریف می‌شود، بر می‌گرداند یا تنظیم می‌کند. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | لبهٔ چپ مستطیل پرکننده را که با درصدی از لبهٔ چپ جعبهٔ محدودهٔ شکل تعریف می‌شود، بر می‌گرداند یا تنظیم می‌کند. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | لبهٔ بالای مستطیل پرکننده را که با درصدی از لبهٔ بالای جعبهٔ محدودهٔ شکل تعریف می‌شود، بر می‌گرداند یا تنظیم می‌کند. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | لبهٔ بالای مستطیل پرکننده را که با درصدی از لبهٔ بالای جعبهٔ محدودهٔ شکل تعریف می‌شود، بر می‌گرداند یا تنظیم می‌کند. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | لبهٔ راست مستطیل پرکننده را که با درصدی از لبهٔ راست جعبهٔ محدودهٔ شکل تعریف می‌شود، بر می‌گرداند یا تنظیم می‌کند. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | لبهٔ راست مستطیل پرکننده را که با درصدی از لبهٔ راست جعبهٔ محدودهٔ شکل تعریف می‌شود، بر می‌گرداند یا تنظیم می‌کند. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | لبهٔ پایین مستطیل پرکننده را که با درصدی از لبهٔ پایین جعبهٔ محدودهٔ شکل تعریف می‌شود، بر می‌گرداند یا تنظیم می‌کند. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | لبهٔ پایین مستطیل پرکننده را که با درصدی از لبهٔ پایین جعبهٔ محدودهٔ شکل تعریف می‌شود، بر می‌گرداند یا تنظیم می‌کند. |
| [getTileOffsetX()](#getTileOffsetX--) | جابجایی افقی بافت از مبدأ شکل بر حسب نقطه را بر می‌گرداند یا تنظیم می‌کند. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | جابجایی افقی بافت از مبدأ شکل بر حسب نقطه را بر می‌گرداند یا تنظیم می‌کند. |
| [getTileOffsetY()](#getTileOffsetY--) | جابجایی عمودی بافت از مبدأ شکل بر حسب نقطه را بر می‌گرداند یا تنظیم می‌کند. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | جابجایی عمودی بافت از مبدأ شکل بر حسب نقطه را بر می‌گرداند یا تنظیم می‌کند. |
| [getTileScaleX()](#getTileScaleX--) | مقیاس افقی بافت به صورت درصد را بر می‌گرداند یا تنظیم می‌کند. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | مقیاس افقی بافت به صورت درصد را بر می‌گرداند یا تنظیم می‌کند. |
| [getTileScaleY()](#getTileScaleY--) | مقیاس عمودی بافت به صورت درصد را بر می‌گرداند یا تنظیم می‌کند. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | مقیاس عمودی بافت به صورت درصد را بر می‌گرداند یا تنظیم می‌کند. |
| [getTileAlignment()](#getTileAlignment--) | نحوهٔ تراز بافت درون شکل را بر می‌گرداند یا تنظیم می‌کند. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | نحوهٔ تراز بافت درون شکل را بر می‌گرداند یا تنظیم می‌کند. |
| [getTileFlip()](#getTileFlip--) | کاشی بافت را حول محور افقی، عمودی یا هر دو محور می‌چرخاند. |
| [setTileFlip(int value)](#setTileFlip-int-) | کاشی بافت را حول محور افقی، عمودی یا هر دو محور می‌چرخاند. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

نسخه. فقط-خواندنی long.

**بازگشت:**
long

### getDpi() {#getDpi--}
```
public final int getDpi()
```

dpi را که برای پرکردن تصویر استفاده می‌شود، بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی int.

**بازگشت:**
int

### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```

dpi را که برای پرکردن تصویر استفاده می‌شود، بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public final int getPictureFillMode()
```

حالت پرکردن تصویر را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [PictureFillMode](../../com.aspose.slides/picturefillmode).

**بازگشت:**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public final void setPictureFillMode(int value)
```

حالت پرکردن تصویر را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [PictureFillMode](../../com.aspose.slides/picturefillmode).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

تصویر را بر می‌گرداند. فقط-خواندنی [ISlidesPicture](../../com.aspose.slides/islidespicture).

**بازگشت:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public final float getCropLeft()
```

درصد عرض واقعی تصویر که از سمت چپ تصویر برش می‌خورد را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

**بازگشت:**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public final void setCropLeft(float value)
```

درصد عرض واقعی تصویر که از سمت چپ تصویر برش می‌خورد را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public final float getCropTop()
```

درصد ارتفاع واقعی تصویر که از بالای تصویر برش می‌خورد را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

**بازگشت:**
float

### setCropTop(float value) {#setCropTop-float-}
```
public final void setCropTop(float value)
```

درصد ارتفاع واقعی تصویر که از بالای تصویر برش می‌خورد را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public final float getCropRight()
```

درصد عرض واقعی تصویر که از سمت راست تصویر برش می‌خورد را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

**بازگشت:**
float

### setCropRight(float value) {#setCropRight-float-}
```
public final void setCropRight(float value)
```

درصد عرض واقعی تصویر که از سمت راست تصویر برش می‌خورد را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public final float getCropBottom()
```

درصد ارتفاع واقعی تصویر که از پایین تصویر برش می‌خورد را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

**بازگشت:**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public final void setCropBottom(float value)
```

درصد ارتفاع واقعی تصویر که از پایین تصویر برش می‌خورد را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public final IPPImage deletePictureCroppedAreas()
```

ناحیه‌های برش‌خورده‌ی تصویر پرکننده را حذف می‌کند.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // دریافت PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // ناحیه‌های برش‌خورده تصویر PictureFrame را حذف می‌کند
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**بازگشت:**
[IPPImage](../../com.aspose.slides/ippimage) - تصویر برش‌خورده یا تصویر اصلی اگر برش لازم نباشد.

--------------------

این متد فایل‌های متافایل WMF/EMF را به تصویر رستر PNG تبدیل می‌کند در حالی که برش می‌دهد.
### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public final boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

تصویر را با کاهش اندازه آن بر اساس اندازه شکل و وضوح مشخص‌شده فشرده می‌کند. به‌صورت اختیاری، ناحیه‌های برش‌خورده را نیز حذف می‌کند.

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` متد برای کاهش اندازهٔ یک تصویر در ارائه با تنظیم وضوح هدف و حذف ناحیه‌های برش‌خورده:
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
boolean - A boolean indicating whether the image was successfully compressed. Returns   if the image was resized or cropped, otherwise  .
### compressImage(boolean deleteCroppedAreasOfImage, float resolution) {#compressImage-boolean-float-}
```
public final boolean compressImage(boolean deleteCroppedAreasOfImage, float resolution)
```


Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas.

--------------------

> ```
> مثال زیر نشان می‌دهد که چگونه از متد ```
> CompressImage
> ```
 برای کاهش اندازهٔ یک تصویر در یک ارائه با تنظیم وضوح هدف و حذف ناحیه‌های برش‌خورده استفاده می‌شود:
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
boolean - A  boolean  indicating whether the image was successfully compressed. Returns   if the image was resized or cropped, otherwise  .
### getStretchOffsetLeft() {#getStretchOffsetLeft--}
```
public final float getStretchOffsetLeft()
```

Returns or sets left edge of the fill rectangle that is defined by a percentage offset from the left edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Returns:**
float
### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public final void setStretchOffsetLeft(float value)
```

بازگشت یا تنظیم لبهٔ چپ مستطیل پرکننده که با درصدی از لبهٔ چپ جعبهٔ محدودکنندهٔ شکل تعریف می‌شود. درصد مثبت یک تورفتگی را مشخص می‌کند، در حالی که درصد منفی یک برآمدگی را مشخص می‌کند. خواندنی/نوشتنی float .

**بازگشت:**
float
### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public final float getStretchOffsetTop()
```

Returns or sets top edge of the fill rectangle that is defined by a percentage offset from the top edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Returns:**
float
### setStretchOffsetTop(float value) {#setStretchOffsetTop-float-}
```
public final void setStretchOffsetTop(float value)
```

Returns or sets top edge of the fill rectangle that is defined by a percentage offset from the top edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetRight() {#getStretchOffsetRight--}
```
public final float getStretchOffsetRight()
```
Returns or sets right edge of the fill rectangle that is defined by a percentage offset from the right edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Returns:**
float
### setStretchOffsetRight(float value) {#setStretchOffsetRight-float-}
```
public final void setStretchOffsetRight(float value)
```

Returns or sets right edge of the fill rectangle that is defined by a percentage offset from the right edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetBottom() {#getStretchOffsetBottom--}
```
public final float getStretchOffsetBottom()
```

Returns or sets bottom edge of the fill rectangle that is defined by a percentage offset from the bottom edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Returns:**
float
### setStretchOffsetBottom(float value) {#setStretchOffsetBottom-float-}
```
public final void setStretchOffsetBottom(float value)
```

Returns or sets bottom edge of the fill rectangle that is defined by a percentage offset from the bottom edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTileOffsetX() {#getTileOffsetX--}
```
public final float getTileOffsetX()
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
public final void setTileOffsetX(float value)
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
public final float getTileOffsetY()
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
public final void setTileOffsetY(float value)
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
public final float getTileScaleX()
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

**Returns:
float
### setTileScaleX(float value) {#setTileScaleX-float-}
```
public final void setTileScaleX(float value)
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
public final float getTileScaleY()
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
### setTileScaleY(float value) {#setTileScaleY-float-}
```
public final void setTileScaleY(float value)
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
public final byte getTileAlignment()
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
public final void setTileAlignment(byte value)
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
public final int getTileFlip()
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
پیش‌فرض است [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**بازگشت:**
int
### setTileFlip(int value) {#setTileFlip-int-}
```
public final void setTileFlip(int value)
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