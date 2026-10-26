---
title: PictureFillFormat
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل نمط تعبئة الصورة.
type: docs
url: /ar/com.aspose.slides/picturefillformat/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
```
public final class PictureFillFormat extends PVIObject implements IPictureFillFormat
```

يمثل نمط تعبئة الصورة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDpi()](#getDpi--) | يرجع أو يضبط الـ dpi المستخدم لتعبئة الصورة. |
| [setDpi(int value)](#setDpi-int-) | يررج أو يضبط الـ dpi المستخدم لتعبئة الصورة. |
| [getPictureFillMode()](#getPictureFillMode--) | يررج أو يضبط وضع تعبئة الصورة. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | يررج أو يضبط وضع تعبئة الصورة. |
| [getPicture()](#getPicture--) | يررج الصورة. |
| [getCropLeft()](#getCropLeft--) | يررج أو يضبط نسبة مئوية من عرض الصورة الحقيقي التي يتم قصها من اليسار. |
| [setCropLeft(float value)](#setCropLeft-float-) | يررج أو يضبط نسبة مئوية من عرض الصورة الحقيقي التي يتم قصها من اليسار. |
| [getCropTop()](#getCropTop--) | يررج أو يضبط نسبة مئوية من ارتفاع الصورة الحقيقي التي يتم قصها من الأعلى. |
| [setCropTop(float value)](#setCropTop-float-) | يررج أو يضبط نسبة مئوية من ارتفاع الصورة الحقيقي التي يتم قصها من الأعلى. |
| [getCropRight()](#getCropRight--) | يررج أو يضبط نسبة مئوية من عرض الصورة الحقيقي التي يتم قصها من اليمين. |
| [setCropRight(float value)](#setCropRight-float-) | يررج أو يضبط نسبة مئوية من عرض الصورة الحقيقي التي يتم قصها من اليمين. |
| [getCropBottom()](#getCropBottom--) | يررج أو يضبط نسبة مئوية من ارتفاع الصورة الحقيقي التي يتم قصها من الأسفل. |
| [setCropBottom(float value)](#setCropBottom-float-) | يررج أو يضبط نسبة مئوية من ارتفاع الصورة الحقيقي التي يتم قصها من الأسفل. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | احذف مناطق القص من صورة التعبئة. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | يضغط الصورة عن طريق تقليل حجمها بناءً على حجم الشكل والدقة المحددة. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | يضغط الصورة عن طريق تقليل حجمها بناءً على حجم الشكل والدقة المحددة. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | يررج أو يضبط الحافة اليسرى لمستطيل التعبئة المعرفة بنسبة إزاحة من الحافة اليسرى لمربع إطارات الشكل. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | يررج أو يضبط الحافة اليسرى لمستطيل التعبئة المعرفة بنسبة إزاحة من الحافة اليسرى لمربع إطارات الشكل. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | يررج أو يضبط الحافة العليا لمستطيل التعبئة المعرفة بنسبة إزاحة من الحافة العليا لمربع إطارات الشكل. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | يررج أو يضبط الحافة العليا لمستطيل التعبئة المعرفة بنسبة إزاحة من الحافة العليا لمربع إطارات الشكل. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | يررج أو يضبط الحافة اليمنى لمستطيل التعبئة المعرفة بنسبة إزاحة من الحافة اليمنى لمربع إطارات الشكل. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | يررج أو يضبط الحافة اليمنى لمستطيل التعبئة المعرفة بنسبة إزاحة من الحافة اليمنى لمربع إطارات الشكل. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | يررج أو يضبط الحافة السفلية لمستطيل التعبئة المعرفة بنسبة إزاحة من الحافة السفلية لمربع إطارات الشكل. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | يررج أو يضبط الحافة السفلية لمستطيل التعبئة المعرفة بنسبة إزاحة من الحافة السفلية لمربع إطارات الشكل. |
| [getTileOffsetX()](#getTileOffsetX--) | يررج أو يضبط الإزاحة الأفقية للملمس من أصل الشكل بالنقاط. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | يررج أو يضبط الإزاحة الأفقية للملمس من أصل الشكل بالنقاط. |
| [getTileOffsetY()](#getTileOffsetY--) | يررج أو يضبط الإزاحة العمودية للملمس من أصل الشكل بالنقاط. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | يررج أو يضبط الإزاحة العمودية للملمس من أصل الشكل بالنقاط. |
| [getTileScaleX()](#getTileScaleX--) | يررج أو يضبط المقياس الأفقي للملمس كنسبة مئوية. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | يررج أو يضبط المقياس الأفقي للملمس كنسبة مئوية. |
| [getTileScaleY()](#getTileScaleY--) | يررج أو يضبط المقياس العمودي للملمس كنسبة مئوية. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | يررج أو يضبط المقياس العمودي للملمس كنسبة مئوية. |
| [getTileAlignment()](#getTileAlignment--) | يررج أو يضبط كيفية محاذاة الملمس داخل الشكل. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | يررج أو يضبط كيفية محاذاة الملمس داخل الشكل. |
| [getTileFlip()](#getTileFlip--) | يقلب بلاط الملمس حول محوره الأفقي أو العمودي أو كليهما. |
| [setTileFlip(int value)](#setTileFlip-int-) | يقلب بلاط الملمس حول محوره الأفقي أو العمودي أو كليهما. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

الإصدار. قراءة فقط long.

**القيمة المرجعة:**
long

### getDpi() {#getDpi--}
```
public final int getDpi()
```

يررج أو يضبط الـ dpi المستخدم لتعبئة الصورة. قراءة/كتابة int .

**القيمة المرجعة:**
int

### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```

يررج أو يضبط الـ dpi المستخدم لتعبئة الصورة. قراءة/كتابة int .

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public final int getPictureFillMode()
```

يررج أو يضبط وضع تعبئة الصورة. قراءة/كتابة [PictureFillMode](../../com.aspose.slides/picturefillmode).

**القيمة المرجعة:**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public final void setPictureFillMode(int value)
```

يررج أو يضبط وضع تعبئة الصورة. قراءة/كتابة [PictureFillMode](../../com.aspose.slides/picturefillmode).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

يررج الصورة. قراءة فقط [ISlidesPicture](../../com.aspose.slides/islidespicture).

**القيمة المرجعة:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public final float getCropLeft()
```

يررج أو يضبط نسبة مئوية من عرض الصورة الحقيقي التي يتم قصها من اليسار. قراءة/كتابة float .

**القيمة المرجعة:**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public final void setCropLeft(float value)
```

يررج أو يضبط نسبة مئوية من عرض الصورة الحقيقي التي يتم قصها من اليسار. قراءة/كتابة float .

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public final float getCropTop()
```

يررج أو يضبط نسبة مئوية من ارتفاع الصورة الحقيقي التي يتم قصها من الأعلى. قراءة/كتابة float .

**القيمة المرجعة:**
float

### setCropTop(float value) {#setCropTop-float-}
```
public final void setCropTop(float value)
```

يررج أو يضبط نسبة مئوية من ارتفاع الصورة الحقيقي التي يتم قصها من الأعلى. قراءة/كتابة float .

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public final float getCropRight()
```

يررج أو يضبط نسبة مئوية من عرض الصورة الحقيقي التي يتم قصها من اليمين. قراءة/كتابة float .

**القيمة المرجعة:**
float

### setCropRight(float value) {#setCropRight-float-}
```
public final void setCropRight(float value)
```

يررج أو يضبط نسبة مئوية من عرض الصورة الحقيقي التي يتم قصها من اليمين. قراءة/كتابة float .

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public final float getCropBottom()
```

يررج أو يضبط نسبة مئوية من ارتفاع الصورة الحقيقي التي يتم قصها من الأسفل. قراءة/كتابة float .

**القيمة المرجعة:**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public final void setCropBottom(float value)
```

يررج أو يضبط نسبة مئوية من ارتفاع الصورة الحقيقي التي يتم قصها من الأسفل. قراءة/كتابة float .

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public final IPPImage deletePictureCroppedAreas()
```

احذف مناطق القص من صورة التعبئة.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // يحصل على PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // يحذف مناطق القص من صورة PictureFrame
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**القيمة المرجعة:**
[IPPImage](../../com.aspose.slides/ippimage) - صورة مقطوعة أو الصورة الأصلية إذا لم يكن القص ضروريًا.

--------------------

هذه الطريقة تقوم بتحويل ملفات WMF/EMF إلى صورة PNG نقطية مع قصها.
### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public final boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

يضغط الصورة عن طريق تقليل حجمها بناءً على حجم الشكل والدقة المحددة. يمكنه أيضًا حذف مناطق القص.

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` طريقة لتقليل حجم صورة في عرض تقديمي عن طريق تعيين دقة مستهدفة وإزالة مناطق القص:
>  
>  Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // ضغط الصورة بدقة مستهدفة 150 DPI (دقة الويب) وإزالة مناطق القص
>      boolean result = picFrame.getPictureFormat().compressImage(true, PicturesCompression.Dpi150);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| deleteCroppedAreasOfImage | boolean | إذا كان true، ستقوم الطريقة بحذف مناطق القص من الصورة، مما قد يقلل حجمها أكثر. |
| resolution | int | الدقة المستهدفة للضغط، محددة كقيمة من تعداد [PicturesCompression](../../com.aspose.slides/picturescompression) |

--------------------

تغيّر هذه الطريقة حجم الصورة ودقتها بطريقة مشابهة لميزة PowerPoint "Picture Format -> Compress Pictures".

**القيمة المرجعة:**
boolean - قيمة منطقية تشير إلى ما إذا تم ضغط الصورة بنجاح. تُعيد true إذا تم تعديل حجم الصورة أو قصها، وإلا false.

### compressImage(boolean deleteCroppedAreasOfImage, float resolution) {#compressImage-boolean-float-}
```
public final boolean compressImage(boolean deleteCroppedAreasOfImage, float resolution)
```


Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas.

--------------------

> ```
> المثال التالي يوضح كيفية استخدام الطريقة ```
> CompressImage
> ``` لتقليل حجم صورة في عرض تقديمي عن طريق تعيين دقة مستهدفة وإزالة مناطق القص:
>   
>  Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // يحصل على تنسيق تعبئة الصورة للشكل
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // يضبط وضع تعبئة الصورة إلى Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // يضبط الإزاحة الأفقية للملمس إلى 20 نقطة
>      pictureFillFormat.setTileOffsetX(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| deleteCroppedAreasOfImage | boolean | إذا كان true، ستقوم الطريقة بحذف مناطق القص من الصورة، مما قد يقلل حجمها أكثر. |
| resolution | float | الدقة المستهدفة بوحدة DPI. يجب أن تكون القيمة موجبة وتحدد كيف سيتم تعديل حجم الصورة.

--------------------

تغيّر هذه الطريقة حجم الصورة ودقتها بطريقة مشابهة لميزة PowerPoint "Picture Format -> Compress Pictures". |

**القيمة المرجعة:**
boolean - قيمة منطقية تشير إلى ما إذا تم ضغط الصورة بنجاح. تُعيد true إذا تم تعديل حجم الصورة أو قصها، وإلا false.
### getStretchOffsetLeft() {#getStretchOffsetLeft--}
```
public final float getStretchOffsetLeft()
```

يرجع أو يضبط الحافة اليسرى لمستطيل التعبئة الذي يتم تعريفه بنسبة إزاحة من الحافة اليسرى لمربع حدود الشكل. النسبة المئوية الإيجابية تحدد تدخلاً، بينما النسبة السالبة تحدد امتدادًا. Read/write  float .

**Returns:**
float
### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public final void setStretchOffsetLeft(float value)
```

يرجع أو يضبط الحافة اليسرى لمستطيل التعبئة الذي يتم تعريفه بنسبة إزاحة من الحافة اليسرى لمربع حدود الشكل. النسبة المئوية الإيجابية تحدد تدخلاً، بينما النسبة السالبة تحدد امتدادًا. قراءة/كتابة float .

**المعلمات:**
| المعامل | النوع | الوصف |
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

يرجع أو يضبط الحافة العليا لمستطيل التعبئة الذي يتم تعريفه بنسبة إزاحة من الحافة العليا لمربع حدود الشكل. النسبة المئوية الإيجابية تحدد تدخلاً، بينما النسبة السالبة تحدد امتدادًا. قراءة/كتابة  float .

**المعلمات:**
| المعامل | النوع | الوصف |
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

يرجع أو يضبط الحافة اليمنى لمستطيل التعبئة الذي يتم تعريفه بنسبة إزاحة من الحافة اليمنى لمربع حدود الشكل. النسبة المئوية الإيجابية تحدد تدخلاً، بينما النسبة السالبة تحدد امتدادًا. قراءة/كتابة  float .

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetBottom() {#getStretchOffsetBottom--}
```
public final float getStretchOffsetBottom()
```

يرجع أو يضبط الحافة السفلية لمستطيل التعبئة الذي يتم تعريفه بنسبة إزاحة من الحافة السفلية لمربع حدود الشكل. النسبة المئوية الإيجابية تحدد إدخالًا، بينما النسبة السالبة تحدد امتدادًا. قراءة/كتابة  float .

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
>      // يحصل على تنسيق تعبئة الصورة للشكل
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // يضبط وضع تعبئة الصورة إلى Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // يضبط الإزاحة الأفقية للملمس إلى 20 نقطة
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
>      // يحصل على تنسيق تعبئة الصورة للشكل
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // يضبط وضع تعبئة الصورة إلى Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // يضبط الإزاحة الأفقية للملمس إلى 20 نقطة
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
>      // يحصل على تنسيق تعبئة الصورة للشكل
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // يضبط وضع تعبئة الصورة إلى Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // يضبط الإزاحة العمودية للملمس إلى -50 نقطة
>      pictureFillFormat.setTileOffsetY(-50);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**القيمة المرجعة:**
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
>      // يحصل على تنسيق تعبئة الصورة للشكل
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // يضبط وضع تعبئة الصورة إلى Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // يضبط الإزاحة العمودية للملمس إلى -50 نقطة
>      pictureFillFormat.setTileOffsetY(-50);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**المعلمات:**
| المعامل | النوع | الوصف |
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
>      // يحصل على تنسيق تعبئة الصورة للشكل
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // يضبط وضع تعبئة الصورة إلى Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // يضبط المقياس الأفقي للملمس إلى 120٪
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
>      // يحصل على تنسيق تعبئة الصورة للشكل
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // يضبط وضع تعبئة الصورة إلى Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // يضبط المقياس الأفقي للملمس إلى 120٪
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
>      // يحصل على تنسيق تعبئة الصورة للشكل
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // يضبط وضع تعبئة الصورة إلى Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // يضبط المقياس العمودي للملمس إلى 120٪
>      pictureFillFormat.setTileScaleY(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**القيمة المرجعة:**
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
>      // يحصل على تنسيق تعبئة الصورة للشكل
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // يضبط وضع تعبئة الصورة إلى Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // يضبط المقياس العمودي للملمس إلى 120٪
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
>      // يحصل على تنسيق تعبئة الصورة للشكل
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // يضبط وضع تعبئة الصورة إلى Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // يضبط المحاذاة للبلاط إلى الأسفل اليمين
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
>      // يحصل على تنسيق تعبئة الصورة للشكل
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // يضبط وضع تعبئة الصورة إلى Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // يضبط المحاذاة للبلاط إلى الأسفل اليمين
>      pictureFillFormat.setTileAlignment(RectangleAlignment.BottomRight);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
--------------------

الافتراضي هو [RectangleAlignment.TopLeft](../../com.aspose.slides/rectanglealignment\#TopLeft).

**المعلمات:**
| المعامل | النوع | الوصف |
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
>      // يحصل على تنسيق تعبئة الصورة للشكل
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // يضبط وضع تعبئة الصورة إلى Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // يقلب البلاط القماشي حول محوره العمودي.
>      pictureFillFormat.setTileFlip(TileFlip.FlipY);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
--------------------

الافتراضي هو [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**القيمة المرجعة:**
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
>      // يحصل على تنسيق تعبئة الصورة للشكل
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // يضبط وضع تعبئة الصورة إلى Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // يقلب البلاط القماشي حول محوره العمودي.
>      pictureFillFormat.setTileFlip(TileFlip.FlipY);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

--------------------

القيمة الافتراضية هي [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |