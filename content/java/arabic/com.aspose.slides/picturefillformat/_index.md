---
title: PictureFillFormat
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل نمط تعبئة صورة.
type: docs
url: /ar/com.aspose.slides/picturefillformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
```
public final class PictureFillFormat extends PVIObject implements IPictureFillFormat
```

يمثل نمط تعبئة الصورة.
## Methods

| الطريقة | الوصف |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDpi()](#getDpi--) | إرجاع أو تعيين الـ dpi المستخدم لملء الصورة. |
| [setDpi(int value)](#setDpi-int-) | إرجاع أو تعيين الـ dpi المستخدم لملء الصورة. |
| [getPictureFillMode()](#getPictureFillMode--) | إرجاع أو تعيين وضع تعبئة الصورة. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | إرجاع أو تعيين وضع تعبئة الصورة. |
| [getPicture()](#getPicture--) | إرجاع الصورة. |
| [getCropLeft()](#getCropLeft--) | إرجاع أو تعيين عدد النسب المئوية لعرض الصورة الفعلي التي يتم قطعها من اليسار. |
| [setCropLeft(float value)](#setCropLeft-float-) | إرجاع أو تعيين عدد النسب المئوية لعرض الصورة الفعلي التي يتم قطعها من اليسار. |
| [getCropTop()](#getCropTop--) | إرجاع أو تعيين عدد النسب المئوية لارتفاع الصورة الفعلي التي يتم قطعها من الأعلى. |
| [setCropTop(float value)](#setCropTop-float-) | إرجاع أو تعيين عدد النسب المئوية لارتفاع الصورة الفعلي التي يتم قطعها من الأعلى. |
| [getCropRight()](#getCropRight--) | إرجاع أو تعيين عدد النسب المئوية لعرض الصورة الفعلي التي يتم قطعها من اليمين. |
| [setCropRight(float value)](#setCropRight-float-) | إرجاع أو تعيين عدد النسب المئوية لعرض الصورة الفعلي التي يتم قطعها من اليمين. |
| [getCropBottom()](#getCropBottom--) | إرجاع أو تعيين عدد النسب المئوية لارتفاع الصورة الفعلي التي يتم قطعها من الأسفل. |
| [setCropBottom(float value)](#setCropBottom-float-) | إرجاع أو تعيين عدد النسب المئوية لارتفاع الصورة الفعلي التي يتم قطعها من الأسفل. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | حذف المناطق المقصوصة من صورة التعبئة. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | ضغط الصورة عن طريق تقليل حجمها بناءً على حجم الشكل والدقة المحددة. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | ضغط الصورة عن طريق تقليل حجمها بناءً على حجم الشكل والدقة المحددة. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | إرجاع أو تعيين الحافة اليسرى لمستطيل التعبئة التي تُحدَّد بنسبة مئوية من حافة الشكل اليسرى. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | إرجاع أو تعيين الحافة اليسرى لمستطيل التعبئة التي تُحدَّد بنسبة مئوية من حافة الشكل اليسرى. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | إرجاع أو تعيين الحافة العليا لمستطيل التعبئة التي تُحدَّد بنسبة مئوية من حافة الشكل العليا. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | إرجاع أو تعيين الحافة العليا لمستطيل التعبئة التي تُحدَّد بنسبة مئوية من حافة الشكل العليا. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | إرجاع أو تعيين الحافة اليمنى لمستطيل التعبئة التي تُحدَّد بنسبة مئوية من حافة الشكل اليمنى. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | إرجاع أو تعيين الحافة اليمنى لمستطيل التعبئة التي تُحدَّد بنسبة مئوية من حافة الشكل اليمنى. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | إرجاع أو تعيين الحافة السفلية لمستطيل التعبئة التي تُحدَّد بنسبة مئوية من حافة الشكل السفلية. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | إرجاع أو تعيين الحافة السفلية لمستطيل التعبئة التي تُحدَّد بنسبة مئوية من حافة الشكل السفلية. |
| [getTileOffsetX()](#getTileOffsetX--) | إرجاع أو تعيين الإزاحة الأفقية للنقش من أصل الشكل بالنقاط. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | إرجاع أو تعيين الإزاحة الأفقية للنقش من أصل الشكل بالنقاط. |
| [getTileOffsetY()](#getTileOffsetY--) | إرجاع أو تعيين الإزاحة الرأسية للنقش من أصل الشكل بالنقاط. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | إرجاع أو تعيين الإزاحة الرأسية للنقش من أصل الشكل بالنقاط. |
| [getTileScaleX()](#getTileScaleX--) | إرجاع أو تعيين المقياس الأفقي لتعبئة النقش كنسبة مئوية. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | إرجاع أو تعيين المقياس الأفقي لتعبئة النقش كنسبة مئوية. |
| [getTileScaleY()](#getTileScaleY--) | إرجاع أو تعيين المقياس الرأسي لتعبئة النقش كنسبة مئوية. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | إرجاع أو تعيين المقياس الرأسي لتعبئة النقش كنسبة مئوية. |
| [getTileAlignment()](#getTileAlignment--) | إرجاع أو تعيين طريقة محاذاة النقش داخل الشكل. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | إرجاع أو تعيين طريقة محاذاة النقش داخل الشكل. |
| [getTileFlip()](#getTileFlip--) | قلب بلاطة النقش حول محورها الأفقي أو الرأسي أو كليهما. |
| [setTileFlip(int value)](#setTileFlip-int-) | قلب بلاطة النقش حول محورها الأفقي أو الرأسي أو كليهما. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

الإصدار. للقراءة فقط long.

**الإرجاع:**
long

### getDpi() {#getDpi--}
```
public final int getDpi()
```

إرجاع أو تعيين الـ dpi المستخدم لملء الصورة. للقراءة/الكتابة int.

**الإرجاع:**
int

### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```

إرجاع أو تعيين الـ dpi المستخدم لملء الصورة. للقراءة/الكتابة int.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public final int getPictureFillMode()
```

إرجاع أو تعيين وضع تعبئة الصورة. للقراءة/الكتابة [PictureFillMode](../../com.aspose.slides/picturefillmode).

**الإرجاع:**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public final void setPictureFillMode(int value)
```

إرجاع أو تعيين وضع تعبئة الصورة. للقراءة/الكتابة [PictureFillMode](../../com.aspose.slides/picturefillmode).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

إرجاع الصورة. للقراءة فقط [ISlidesPicture](../../com.aspose.slides/islidespicture).

**الإرجاع:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public final float getCropLeft()
```

إرجاع أو تعيين عدد النسب المئوية لعرض الصورة الفعلي التي يتم قطعها من اليسار. للقراءة/الكتابة float.

**الإرجاع:**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public final void setCropLeft(float value)
```

إرجاع أو تعيين عدد النسب المئوية لعرض الصورة الفعلي التي يتم قطعها من اليسار. للقراءة/الكتابة float.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public final float getCropTop()
```

إرجاع أو تعيين عدد النسب المئوية لارتفاع الصورة الفعلي التي يتم قطعها من الأعلى. للقراءة/الكتابة float.

**الإرجاع:**
float

### setCropTop(float value) {#setCropTop-float-}
```
public final void setCropTop(float value)
```

إرجاع أو تعيين عدد النسب المئوية لارتفاع الصورة الفعلي التي يتم قطعها من الأعلى. للقراءة/الكتابة float.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public final float getCropRight()
```

إرجاع أو تعيين عدد النسب المئوية لعرض الصورة الفعلي التي يتم قطعها من اليمين. للقراءة/الكتابة float.

**الإرجاع:**
float

### setCropRight(float value) {#setCropRight-float-}
```
public final void setCropRight(float value)
```

إرجاع أو تعيين عدد النسب المئوية لعرض الصورة الفعلي التي يتم قطعها من اليمين. للقراءة/الكتابة float.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public final float getCropBottom()
```

إرجاع أو تعيين عدد النسب المئوية لارتفاع الصورة الفعلي التي يتم قطعها من الأسفل. للقراءة/الكتابة float.

**الإرجاع:**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public final void setCropBottom(float value)
```

إرجاع أو تعيين عدد النسب المئوية لارتفاع الصورة الفعلي التي يتم قطعها من الأسفل. للقراءة/الكتابة float.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public final IPPImage deletePictureCroppedAreas()
```

حذف المناطق المقصوصة من صورة التعبئة.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // يحصل على PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // يحذف المناطق المقصوصة من صورة PictureFrame
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**الإرجاع:**
[IPPImage](../../com.aspose.slides/ippimage) - الصورة المقصوصة أو الصورة الأصلية إذا لم يكن القص ضروريًا.

--------------------

تحول هذه الطريقة ملفات WMF/EMF الوصفية إلى صورة PNG نقطية مع القص.

### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public final boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

يضغط الصورة عن طريق تقليل حجمها بناءً على حجم الشكل والدقة المحددة. اختياريًا، يقوم أيضًا بحذف المناطق المقصوصة.

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` طريقة لتقليل حجم صورة في عرض تقديمي عن طريق تعيين دقة الهدف وإزالة المناطق المقصوصة:
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
> المثال التالي يوضح كيفية استخدام طريقة ```
> CompressImage
> ``` لتقليل حجم صورة في عرض تقديمي عن طريق تعيين دقة الهدف وإزالة المناطق المقصوصة:
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

Returns or sets left edge of the fill rectangle that is defined by a percentage offset from the left edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetTop() {#getStretchOffsetTop--}
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

إرجاع أو تعيين الحافة السفلية لمستطيل التعبئة التي تُحدَّد بنسبة إزاحة من الحافة السفلية لمربع حد الشكل. النسبة المئوية الإيجابية تحدد إدخالًا، بينما النسبة السلبية تحدد بروزًا. قراءة/كتابة  float .

**الإرجاع:**
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

**Returns:
float
### setTileOffsetY(float value) {#setTileOffsetY-float-}
```
public final void setTileOffsetY(float value)
```
إرجاع إنّ  الإزم  النع
```
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
**الإرجاع:**
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
**الإرجاع:**
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
 
--------------------

Default is [RectangleAlignment.TopLeft](../../com.aspose.slides/rectanglealignment\#TopLeft).

**Returns:**
byte
### setTileAlignment(byte value) {#setTileAlignment-byte-}
```
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

الافتراضي هو [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |