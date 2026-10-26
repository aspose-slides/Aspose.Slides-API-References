---
title: IPictureFillFormat
second_title: Aspose.Slides لأندرويد عبر مرجع API لجافا
description: يمثل نمط تعبئة صورة.
type: docs
url: /ar/com.aspose.slides/ipicturefillformat/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormat extends IFillParamSource
```

يمثّل نمط تعبئة صورة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getDpi()](#getDpi--) | يعيد أو يحدد الـ dpi المستخدم لتعبئة صورة. |
| [setDpi(int value)](#setDpi-int-) | يعيد أو يحدد الـ dpi المستخدم لتعبئة صورة. |
| [getPictureFillMode()](#getPictureFillMode--) | يعيد أو يحدد وضع تعبئة الصورة. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | يعيد أو يحدد وضع تعبئة الصورة. |
| [getPicture()](#getPicture--) | يعيد الصورة. |
| [getCropLeft()](#getCropLeft--) | يعيد أو يحدد نسبة مئوية من عرض الصورة الفعلي التي يتم قصها من اليسار. |
| [setCropLeft(float value)](#setCropLeft-float-) | يعيد أو يحدد نسبة مئوية من عرض الصورة الفعلي التي يتم قصها من اليسار. |
| [getCropTop()](#getCropTop--) | يعيد أو يحدد نسبة مئوية من ارتفاع الصورة الفعلي التي يتم قصها من الأعلى. |
| [setCropTop(float value)](#setCropTop-float-) | يعيد أو يحدد نسبة مئوية من ارتفاع الصورة الفعلي التي يتم قصها من الأعلى. |
| [getCropRight()](#getCropRight--) | يعيد أو يحدد نسبة مئوية من عرض الصورة الفعلي التي يتم قصها من اليمين. |
| [setCropRight(float value)](#setCropRight-float-) | يعيد أو يحدد نسبة مئوية من عرض الصورة الفعلي التي يتم قصها من اليمين. |
| [getCropBottom()](#getCropBottom--) | يعيد أو يحدد نسبة مئوية من ارتفاع الصورة الفعلي التي يتم قصها من الأسفل. |
| [setCropBottom(float value)](#setCropBottom-float-) | يعيد أو يحدد نسبة مئوية من ارتفاع الصورة الفعلي التي يتم قصها من الأسفل. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | يعيد أو يحدد الحافة اليسرى لمستطيل التعبئة المحددة بنسبة إزاحة من الحافة اليسرى لإطار الشكل. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | يعيد أو يحدد الحافة اليسرى لمستطيل التعبئة المحددة بنسبة إزاحة من الحافة اليسرى لإطار الشكل. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | يعيد أو يحدد الحافة العلوية لمستطيل التعبئة المحددة بنسبة إزاحة من الحافة العلوية لإطار الشكل. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | يعيد أو يحدد الحافة العلوية لمستطيل التعبئة المحددة بنسبة إزاحة من الحافة العلوية لإطار الشكل. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | يعيد أو يحدد الحافة اليمنى لمستطيل التعبئة المحددة بنسبة إزاحة من الحافة اليمنى لإطار الشكل. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | يعيد أو يحدد الحافة اليمنى لمستطيل التعبئة المحددة بنسبة إزاحة من الح-edge اليمنى لإطار الشكل. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | يعيد أو يحدد الحافة السفلية لمستطيل التعبئة المحددة بنسبة إزاحة من الحافة السفلية لإطار الشكل. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | يعيد أو يحدد الحافة السفلية لمستطيل التعبئة المحددة بنسبة إزاحة من الحافة السفلية لإطار الشكل. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | احذف المناطق المقطوعة من صورة التعبئة. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | يضغط الصورة عن طريق تقليل حجمها بناءً على حجم الشكل والدقة المحددة. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | يضغط الصورة عن طريق تقليل حجمها بناءً على حجم الشكل والدقة المحددة. |
| [getTileOffsetX()](#getTileOffsetX--) | يعيد أو يحدد الإزاحة الأفقية للملمس من أصل الشكل بالنقاط. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | يعيد أو يحدد الإزاحة الأفقية للملمس من أصل الشكل بالنقاط. |
| [getTileOffsetY()](#getTileOffsetY--) | يعيد أو يحدد الإزاحة الرأسية للملمس من أصل الشكل بالنقاط. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | يعيد أو يحدد الإزاحة الرأسية للملمس من أصل الشكل بالنقاط. |
| [getTileScaleX()](#getTileScaleX--) | يعيد أو يحدد المقياس الأفقي للملمس كنسبة مئوية. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | يعيد أو يحدد المقياس الأفقي للملمس كنسبة مئوية. |
| [getTileScaleY()](#getTileScaleY--) | يعيد أو يحدد المقياس العمودي للملمس كنسبة مئوية. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | يعيد أو يحدد المقياس العمودي للملمس كنسبة مئوية. |
| [getTileAlignment()](#getTileAlignment--) | يعيد أو يحدد كيفية محاذاة الملمس داخل الشكل. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | يعيد أو يحدد كيفية محاذاة الملمس داخل الشكل. |
| [getTileFlip()](#getTileFlip--) | يقلب بلاطة الملمس حول محورها الأفقي أو العمودي أو كليهما. |
| [setTileFlip(int value)](#setTileFlip-int-) | يقلب بلاطة الملمس حول محورها الأفقي أو العمودي أو كليهما. |

### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

يعيد أو يحدد الـ dpi المستخدم لتعبئة صورة. قراءة/كتابة int.

**الإرجاع:**
int

### setDpi(int value) {#setDpi-int-}
```
public abstract void setDpi(int value)
```

يعيد أو يحدد الـ dpi المستخدم لتعبئة صورة. قراءة/كتابة int.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

يعيد أو يحدد وضع تعبئة الصورة. قراءة/كتابة [PictureFillMode](../../com.aspose.slides/picturefillmode).

**الإرجاع:**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public abstract void setPictureFillMode(int value)
```

يعيد أو يحدد وضع تعبئة الصورة. قراءة/كتابة [PictureFillMode](../../com.aspose.slides/picturefillmode).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

يعيد الصورة. قراءة فقط [ISlidesPicture](../../com.aspose.slides/islidespicture).

**الإرجاع:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```

يعيد أو يحدد نسبة مئوية من عرض الصورة الفعلي التي يتم قصها من اليسار. قراءة/كتابة float.

**الإرجاع:**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public abstract void setCropLeft(float value)
```

يعيد أو يحدد نسبة مئوية من عرض الصورة الفعلي التي يتم قصها من اليسار. قراءة/كتابة float.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

يعيد أو يحدد نسبة مئوية من ارتفاع الصورة الفعلي التي يتم قصها من الأعلى. قراءة/كتابة float.

**الإرجاع:**
float

### setCropTop(float value) {#setCropTop-float-}
```
public abstract void setCropTop(float value)
```

يعيد أو يحدد نسبة مئوية من ارتفاع الصورة الفعلي التي يتم قصها من الأعلى. قراءة/كتابة float.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

يعيد أو يحدد نسبة مئوية من عرض الصورة الفعلي التي يتم قصها من اليمين. قراءة/كتابة float.

**الإرجاع:**
float

### setCropRight(float value) {#setCropRight-float-}
```
public abstract void setCropRight(float value)
```

يعيد أو يحدد نسبة مئوية من عرض الصورة الفعلي التي يتم قصها من اليمين. قراءة/كتابة float.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

يعيد أو يحدد نسبة مئوية من ارتفاع الصورة الفعلي التي يتم قصها من الأسفل. قراءة/كتابة float.

**الإرجاع:**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public abstract void setCropBottom(float value)
```

يعيد أو يحدد نسبة مئوية من ارتفاع الصورة الفعلي التي يتم قصها من الأسفل. قراءة/كتابة float.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetLeft() {#getStretchOffsetLeft--}
```
public abstract float getStretchOffsetLeft()
```

يعيد أو يحدد الحافة اليسرى لمستطيل التعبئة المحددة بنسبة إزاحة من الحافة اليسرى لإطار الشكل. نسبة إيجابية تعني تقليل، ونسبة سلبية تعني توسيع. قراءة/كتابة float.

**الإرجاع:**
float

### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public abstract void setStretchOffsetLeft(float value)
```

يعيد أو يحدد الحافة اليسرى لمستطيل التعبئة المحددة بنسبة إزاحة من الحافة اليسرى لإطار الشكل. نسبة إيجابية تعني تقليل، ونسبة سلبية تعني توسيع. قراءة/كتابة float.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetTop() {#getStretchOffsetTop--}
```
public abstract float getStretchOffsetTop()
```

يعيد أو يحدد الحافة العلوية لمستطيل التعبئة المحددة بنسبة إزاحة من الحافة العلوية لإطار الشكل. نسبة إيجابية تعني تقليل، ونسبة سلبية تعني توسيع. قراءة/كتابة float.

**الإرجاع:**
float

### setStretchOffsetTop(float value) {#setStretchOffsetTop-float-}
```
public abstract void setStretchOffsetTop(float value)
```

يعيد أو يحدد الحافة العلوية لمستطيل التعبئة المحددة بنسبة إزاحة من الحافة العلوية لإطار الشكل. نسبة إيجابية تعني تقليل، ونسبة سلبية تعني توسيع. قراءة/كتابة float.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetRight() {#getStretchOffsetRight--}
```
public abstract float getStretchOffsetRight()
```

يعيد أو يحدد الحافة اليمنى لمستطيل التعبئة المحددة بنسبة إزاحة من الحافة اليمنى لإطار الشكل. نسبة إيجابية تعني تقليل، ونسبة سلبية تعني توسيع. قراءة/كتابة float.

**الإرجاع:**
float

### setStretchOffsetRight(float value) {#setStretchOffsetRight-float-}
```
public abstract void setStretchOffsetRight(float value)
```

يعيد أو يحدد الحافة اليمنى لمستطيل التعبئة المحددة بنسبة إزاحة من الحافة اليمنى لإطار الشكل. نسبة إيجابية تعني تقليل، ونسبة سلبية تعني توسيع. قراءة/كتابة float.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetBottom() {#getStretchOffsetBottom--}
```
public abstract float getStretchOffsetBottom()
```

يعيد أو يحدد الحافة السفلية لمستطيل التعبئة المحددة بنسبة إزاحة من الحافة السفلية لإطار الشكل. نسبة إيجابية تعني تقليل، ونسبة سلبية تعني توسيع. قراءة/كتابة float.

**الإرجاع:**
float

### setStretchOffsetBottom(float value) {#setStretchOffsetBottom-float-}
```
public abstract void setStretchOffsetBottom(float value)
```

يعيد أو يحدد الحافة السفلية لمستطيل التعبئة المحددة بنسبة إزاحة من الحافة السفلية لإطار الشكل. نسبة إيجابية تعني تقليل، ونسبة سلبية تعني توسيع. قراءة/كتابة float.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public abstract IPPImage deletePictureCroppedAreas()
```

احذف المناطق المقطوعة من صورة التعبئة.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // يحصل على PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // يحذف المناطق المقطوعة من صورة PictureFrame
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**الإرجاع:**
[IPPImage](../../com.aspose.slides/ippimage) - صورة مقطوعة أو الصورة الأصلية إذا لم يكن القطع ضروريًا.

--------------------

هذه الطريقة تحوّل ملفات WMF/EMF إلى صورة PNG نقطية مع القطع.
### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

يضغط الصورة عن طريق تقليل حجمها بناءً على حجم الشكل والدقة المحددة. يمكنه أيضًا حذف المناطق المقطوعة.

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` طريقة لتقليل حجم صورة في عرض تقديمي عن طريق تعيين دقة مستهدفة وإزالة المناطق المقطوعة:
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
> المثال التالي يوضح كيفية استخدام طريقة ```
> CompressImage
> ```
 لتقليل حجم صورة في عرض تقديمي عن طريق تعيين دقة مستهدفة وإزالة المناطق المقطوعة:
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
### setTileScaleY(float value) {#setTileScaleY-float-}
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

**المعلمات:**
| المعلمة | النوع | الوصف |
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

القيمة الافتراضية هي [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |