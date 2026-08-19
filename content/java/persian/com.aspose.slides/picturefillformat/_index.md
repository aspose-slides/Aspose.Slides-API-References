---
title: PictureFillFormat
second_title: Aspose.Slides برای مرجع API جاوا
description: نمایانگر یک سبک پر کردن با تصویر است.
type: docs
url: /fa/com.aspose.slides/picturefillformat/
---
**ارث‌بری:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
```
public final class PictureFillFormat extends PVIObject implements IPictureFillFormat
```

نمایانگر یک سبک پر کردن با تصویر است.

## متدها

| متد | توضیح |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDpi()](#getDpi--) | مقدار dpi را که برای پر کردن تصویر استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [setDpi(int value)](#setDpi-int-) | مقدار dpi را که برای پر کردن تصویر استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [getPictureFillMode()](#getPictureFillMode--) | حالت پر کردن تصویر را برمی‌گرداند یا تنظیم می‌کند. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | حالت پر کردن تصویر را برمی‌گرداند یا تنظیم می‌کند. |
| [getPicture()](#getPicture--) | تصویر را برمی‌گرداند. |
| [getCropLeft()](#getCropLeft--) | درصدی از عرض واقعی تصویر که از سمت چپ تصویر بریده می‌شود را برمی‌گرداند یا تنظیم می‌کند. |
| [setCropLeft(float value)](#setCropLeft-float-) | درصدی از عرض واقعی تصویر که از سمت چپ تصویر بریده می‌شود را برمی‌گرداند یا تنظیم می‌کند. |
| [getCropTop()](#getCropTop--) | درصدی از ارتفاع واقعی تصویر که از سمت بالا تصویر بریده می‌شود را برمی‌گرداند یا تنظیم می‌کند. |
| [setCropTop(float value)](#setCropTop-float-) | درصدی از ارتفاع واقعی تصویر که از سمت بالا تصویر بریده می‌شود را برمی‌گرداند یا تنظیم می‌کند. |
| [getCropRight()](#getCropRight--) | درصدی از عرض واقعی تصویر که از سمت راست تصویر بریده می‌شود را برمی‌گرداند یا تنظیم می‌کند. |
| [setCropRight(float value)](#setCropRight-float-) | درصدی از عرض واقعی تصویر که از سمت راست تصویر بریده می‌شود را برمی‌گرداند یا تنظیم می‌کند. |
| [getCropBottom()](#getCropBottom--) | درصدی از ارتفاع واقعی تصویر که از سمت پایین تصویر بریده می‌شود را برمی‌گرداند یا تنظیم می‌کند. |
| [setCropBottom(float value)](#setCropBottom-float-) | درصدی از ارتفاع واقعی تصویر که از سمت پایین تصویر بریده می‌شود را برمی‌گرداند یا تنظیم می‌کند. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | ناحیه‌های بریده‌شده از تصویر پرکننده را حذف می‌کند. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | تصویر را با کاهش اندازه آن بر اساس اندازه شکل و وضوح مشخص‌شده فشرده می‌کند. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | تصویر را با کاهش اندازه آن بر اساس اندازه شکل و وضوح مشخص‌شده فشرده می‌کند. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | لبه چپ مستطیل پرکننده که توسط افست درصدی از لبه چپ جعبه محاطی شکل تعریف شده است را برمی‌گرداند یا تنظیم می‌کند. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | لبه چپ مستطیل پرکننده که توسط افست درصدی از لبه چپ جعبه محاطی شکل تعریف شده است را برمی‌گرداند یا تنظیم می‌کند. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | لبه بالای مستطیل پرکننده که توسط افست درصدی از لبه بالای جعبه محاطی شکل تعریف شده است را برمی‌گرداند یا تنظیم می‌کند. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | لبه بالای مستطیل پرکننده که توسط افست درصدی از لبه بالای جعبه محاطی شکل تعریف شده است را برمی‌گرداند یا تنظیم می‌کند. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | لبه راست مستطیل پرکننده که توسط افست درصدی از لبه راست جعبه محاطی شکل تعریف شده است را برمی‌گرداند یا تنظیم می‌کند. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | لبه راست مستطیل پرکننده که توسط افست درصدی از لبه راست جعبه محاطی شکل تعریف شده است را برمی‌گرداند یا تنظیم می‌کند. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | لبه پایین مستطیل پرکننده که توسط افست درصدی از لبه پایین جعبه محاطی شکل تعریف شده است را برمی‌گرداند یا تنظیم می‌کند. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | لبه پایین مستطیل پرکننده که توسط افست درصدی از لبه پایین جعبه محاطی شکل تعریف شده است را برمی‌گرداند یا تنظیم می‌کند. |
| [getTileOffsetX()](#getTileOffsetX--) | افست افقی بافت را از مبدأ شکل بر حسب نقاط برمی‌گرداند یا تنظیم می‌کند. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | افست افقی بافت را از مبدأ شکل بر حسب نقاط برمی‌گرداند یا تنظیم می‌کند. |
| [getTileOffsetY()](#getTileOffsetY--) | افست عمودی بافت را از مبدأ شکل بر حسب نقاط برمی‌گرداند یا تنظیم می‌کند. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | افست عمودی بافت را از مبدأ شکل بر حسب نقاط برمی‌گرداند یا تنظیم می‌کند. |
| [getTileScaleX()](#getTileScaleX--) | مقیاس افقی پر کردن بافت را به صورت درصد برمی‌گرداند یا تنظیم می‌کند. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | مقیاس افقی پر کردن بافت را به صورت درصد برمی‌گرداند یا تنظیم می‌کند. |
| [getTileScaleY()](#getTileScaleY--) | مقیاس عمودی پر کردن بافت را به صورت درصد برمی‌گرداند یا تنظیم می‌کند. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | مقیاس عمودی پر کردن بافت را به صورت درصد برمی‌گرداند یا تنظیم می‌کند. |
| [getTileAlignment()](#getTileAlignment--) | نحوه‌ٔ تراز بافت درون شکل را برمی‌گرداند یا تنظیم می‌کند. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | نحوه‌ٔ تراز بافت درون شکل را برمی‌گرداند یا تنظیم می‌کند. |
| [getTileFlip()](#getTileFlip--) | قاب بافت را حول محور افقی، عمودی یا هر دو محور می‌چرخاند. |
| [setTileFlip(int value)](#setTileFlip-int-) | قاب بافت را حول محور افقی، عمودی یا هر دو محور می‌چرخاند. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

نسخه. فقط-خواندنی long.

**بازمی‌گرداند:**
long

### getDpi() {#getDpi--}
```
public final int getDpi()
```

مقدار dpi را که برای پر کردن تصویر استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. Read/write int.

**بازمی‌گرداند:**
int

### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```

مقدار dpi را که برای پر کردن تصویر استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. Read/write int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public final int getPictureFillMode()
```

حالت پر کردن تصویر را برمی‌گرداند یا تنظیم می‌کند. Read/write [PictureFillMode](../../com.aspose.slides/picturefillmode).

**بازمی‌گرداند:**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public final void setPictureFillMode(int value)
```

حالت پر کردن تصویر را برمی‌گرداند یا تنظیم می‌کند. Read/write [PictureFillMode](../../com.aspose.slides/picturefillmode).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

تصویر را برمی‌گرداند. فقط-خواندنی [ISlidesPicture](../../com.aspose.slides/islidespicture).

**بازمی‌گرداند:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public final float getCropLeft()
```

درصدی از عرض واقعی تصویر که از سمت چپ تصویر بریده می‌شود را برمی‌گرداند یا تنظیم می‌کند. Read/write float.

**بازمی‌گرداند:**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public final void setCropLeft(float value)
```

درصدی از عرض واقعی تصویر که از سمت چپ تصویر بریده می‌شود را برمی‌گرداند یا تنظیم می‌کند. Read/write float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public final float getCropTop()
```

درصدی از ارتفاع واقعی تصویر که از سمت بالا تصویر بریده می‌شود را برمی‌گرداند یا تنظیم می‌کند. Read/write float.

**بازمی‌گرداند:**
float

### setCropTop(float value) {#setCropTop-float-}
```
public final void setCropTop(float value)
```

درصدی از ارتفاع واقعی تصویر که از سمت بالا تصویر بریده می‌شود را برمی‌گرداند یا تنظیم می‌کند. Read/write float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public final float getCropRight()
```

درصدی از عرض واقعی تصویر که از سمت راست تصویر بریده می‌شود را برمی‌گرداند یا تنظیم می‌کند. Read/write float.

**بازمی‌گرداند:**
float

### setCropRight(float value) {#setCropRight-float-}
```
public final void setCropRight(float value)
```

درصدی از عرض واقعی تصویر که از سمت راست تصویر بریده می‌شود را برمی‌گرداند یا تنظیم می‌کند. Read/write float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public final float getCropBottom()
```

درصدی از ارتفاع واقعی تصویر که از سمت پایین تصویر بریده می‌شود را برمی‌گرداند یا تنظیم می‌کند. Read/write float.

**بازمی‌گرداند:**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public final void setCropBottom(float value)
```

درصدی از ارتفاع واقعی تصویر که از سمت پایین تصویر بریده می‌شود را برمی‌گرداند یا تنظیم می‌کند. Read/write float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public final IPPImage deletePictureCroppedAreas()
```

ناحیه‌های بریده‌شده از تصویر پرکننده را حذف می‌کند.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // دریافت PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // حذف نواحی بریده‌شده تصویر PictureFrame
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**بازمی‌گرداند:**
[IPPImage](../../com.aspose.slides/ippimage) - تصویر بریده‌شده یا تصویر اصلی اگر برش لازم نباشد.

--------------------

این متد فایل‌های متا‌فایل WMF/EMF را به تصویر PNG شطرنجی تبدیل می‌کند در حالی که برش می‌دهد.

### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public final boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

تصویر را با کاهش اندازه آن بر اساس اندازه شکل و وضوح مشخص‌شده فشرده می‌کند. به‌صورت اختیاری ناحیه‌های بریده‌شده را نیز حذف می‌کند.

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` method to reduce the size of an image in a presentation by setting a target resolution and removing cropped areas:
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
> مثال زیر نشان می‌دهد چطور می‌توان از متد ```
> CompressImage
> ``` برای کاهش اندازه یک تصویر در یک ارائه با تنظیم وضوح هدف و حذف نواحی بریده‌شده استفاده کرد:
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

لبهٔ چپ مستطیل پرکننده را که با یک افست درصدی از لبهٔ چپ جعبهٔ محدودکنندهٔ شکل تعریف می‌شود، برمی‌گرداند یا تنظیم می‌کند. یک درصد مثبت تو رفتگی را مشخص می‌کند، در حالی که درصد منفی برآمدگی را تعیین می‌کند. Read/write float .

**Returns:**
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

**پارامترها:**
| پارامتر | نوع | توضیح |
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
**پارامترها:**
| پارامتر | نوع | توضیح |
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

**Returns:**
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

Default is [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**Returns:**
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