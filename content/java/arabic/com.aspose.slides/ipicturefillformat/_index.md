---
title: IPictureFillFormat
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل نمط تعبئة صورة.
type: docs
url: /ar/com.aspose.slides/ipicturefillformat/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormat extends IFillParamSource
```

يمثل نمط تعبئة صورة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getDpi()](#getDpi--) | إرجاع أو تعيين قيمة الـ dpi المستخدمة لتعبئة الصورة. |
| [setDpi(int value)](#setDpi-int-) | إرجاع أو تعيين قيمة الـ dpi المستخدمة لتعبئة الصورة. |
| [getPictureFillMode()](#getPictureFillMode--) | إرجاع أو تعيين نمط تعبئة الصورة. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | إرجاع أو تعيين نمط تعبئة الصورة. |
| [getPicture()](#getPicture--) | إرجاع الصورة. |
| [getCropLeft()](#getCropLeft--) | إرجاع أو تعيين عدد النسب المئوية لعرض الصورة الحقيقي المقطوع من يسار الصورة. |
| [setCropLeft(float value)](#setCropLeft-float-) | إرجاع أو تعيين عدد النسب المئوية لعرض الصورة الحقيقي المقطوع من يسار الصورة. |
| [getCropTop()](#getCropTop--) | إرجاع أو تعيين عدد النسب المئوية لارتفاع الصورة الحقيقي المقطوع من أعلى الصورة. |
| [setCropTop(float value)](#setCropTop-float-) | إرجاع أو تعيين عدد النسب المئوية لارتفاع الصورة الحقيقي المقطوع من أعلى الصورة. |
| [getCropRight()](#getCropRight--) | إرجاع أو تعيين عدد النسب المئوية لعرض الصورة الحقيقي المقطوع من يمين الصورة. |
| [setCropRight(float value)](#setCropRight-float-) | إرجاع أو تعيين عدد النسب المئوية لعرض الصورة الحقيقي المقطوع من يمين الصورة. |
| [getCropBottom()](#getCropBottom--) | إرجاع أو تعيين عدد النسب المئوية لارتفاع الصورة الحقيقي المقطوع من أسفل الصورة. |
| [setCropBottom(float value)](#setCropBottom-float-) | إرجاع أو تعيين عدد النسب المئوية لارتفاع الصورة الحقيقي المقطوع من أسفل الصورة. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | إرجاع أو تعيين الحد الأيسر لمستطيل التعبئة المحدد بإزاحة نسبية من الحد الأيسر لمربع حدود الشكل. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | إرجاع أو تعيين الحد الأيسر لمستطيل التعبئة المحدد بإزاحة نسبية من الحد الأيسر لمربع حدود الشكل. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | إرجاع أو تعيين الحد العلوي لمستطيل التعبئة المحدد بإزاحة نسبية من الحد العلوي لمربع حدود الشكل. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | إرجاع أو تعيين الحد العلوي لمستطيل التعبئة المحدد بإزاحة نسبية من الحد العلوي لمربع حدود الشكل. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | إرجاع أو تعيين الحد الأيمن لمستطيل التعبئة المحدد بإزاحة نسبية من الحد الأيمن لمربع حدود الشكل. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | إرجاع أو تعيين الحد الأيمن لمستطيل التعبئة المحدد بإزاحة نسبية من الحد الأيمن لمربع حدود الشكل. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | إرجاع أو تعيين الحد السفلي لمستطيل التعبئة المحدد بإزاحة نسبية من الحد السفلي لمربع حدود الشكل. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | إرجاع أو تعيين الحد السفلي لمستطيل التعبئة المحدد بإزاحة نسبية من الحد السفلي لمربع حدود الشكل. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | حذف المناطق المقصوصة من الصورة المملوءة. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | ضغط الصورة عن طريق تقليل حجمها بناءً على حجم الشكل والدقة المحددة. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | ضغط الصورة عن طريق تقليل حجمها بناءً على حجم الشكل والدقة المحددة. |
| [getTileOffsetX()](#getTileOffsetX--) | إرجاع أو تعيين الإزاحة الأفقية للنقش من أصل الشكل بالنقاط. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | إرجاع أو تعيين الإزاحة الأفقية للنقش من أصل الشكل بالنقاط. |
| [getTileOffsetY()](#getTileOffsetY--) | إرجاع أو تعيين الإزاحة العمودية للنقش من أصل الشكل بالنقاط. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | إرجاع أو تعيين الإزاحة العمودية للنقش من أصل الشكل بالنقاط. |
| [getTileScaleX()](#getTileScaleX--) | إرجاع أو تعيين المقياس الأفقي لتعبئة النقش كنسبة مئوية. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | إرجاع أو تعيين المقياس الأفقي لتعبئة النقش كنسبة مئوية. |
| [getTileScaleY()](#getTileScaleY--) | إرجاع أو تعيين المقياس العمودي لتعبئة النقش كنسبة مئوية. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | إرجاع أو تعيين المقياس العمودي لتعبئة النقش كنسبة مئوية. |
| [getTileAlignment()](#getTileAlignment--) | إرجاع أو تعيين كيفية محاذاة النقش داخل الشكل. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | إرجاع أو تعيين كيفية محاذاة النقش داخل الشكل. |
| [getTileFlip()](#getTileFlip--) | قلب بلاطة النقش حول محورها الأفقي أو العمودي أو كليهما. |
| [setTileFlip(int value)](#setTileFlip-int-) | قلب بلاطة النقش حول محورها الأفقي أو العمودي أو كليهما. |

### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

إرجاع أو تعيين الـ dpi المستخدم لتعبئة الصورة. قراءة/كتابة int.

**الإرجاع:**
int

### setDpi(int value) {#setDpi-int-}
```
public abstract void setDpi(int value)
```

إرجاع أو تعيين الـ dpi المستخدم لتعبئة الصورة. قراءة/كتابة int.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

إرجاع أو تعيين نمط تعبئة الصورة. قراءة/كتابة [PictureFillMode](../../com.aspose.slides/picturefillmode).

**الإرجاع:**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public abstract void setPictureFillMode(int value)
```

إرجاع أو تعيين نمط تعبئة الصورة. قراءة/كتابة [PictureFillMode](../../com.aspose.slides/picturefillmode).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

إرجاع الصورة. للقراءة فقط [ISlidesPicture](../../com.aspose.slides/islidespicture).

**الإرجاع:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```

إرجاع أو تعيين عدد النسب المئوية لعرض الصورة الحقيقي المقطوع من يسار الصورة. قراءة/كتابة float.

**الإرجاع:**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public abstract void setCropLeft(float value)
```

إرجاع أو تعيين عدد النسب المئوية لعرض الصورة الحقيقي المقطوع من يسار الصورة. قراءة/كتابة float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

إرجاع أو تعيين عدد النسب المئوية لارتفاع الصورة الحقيقي المقطوع من أعلى الصورة. قراءة/كتابة float.

**الإرجاع:**
float

### setCropTop(float value) {#setCropTop-float-}
```
public abstract void setCropTop(float value)
```

إرجاع أو تعيين عدد النسب المئوية لارتفاع الصورة الحقيقي المقطوع من أعلى الصورة. قراءة/كتابة float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

إرجاع أو تعيين عدد النسب المئوية لعرض الصورة الحقيقي المقطوع من يمين الصورة. قراءة/كتابة float.

**الإرجاع:**
float

### setCropRight(float value) {#setCropRight-float-}
```
public abstract void setCropRight(float value)
```

إرجاع أو تعيين عدد النسب المئوية لعرض الصورة الحقيقي المقطوع من يمين الصورة. قراءة/كتابة float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

إرجاع أو تعيين عدد النسب المئوية لارتفاع الصورة الحقيقي المقطوع من أسفل الصورة. قراءة/كتابة float.

**الإرجاع:**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public abstract void setCropBottom(float value)
```

إرجاع أو تعيين عدد النسب المئوية لارتفاع الصورة الحقيقي المقطوع من أسفل الصورة. قراءة/كتابة float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetLeft() {#getStretchOffsetLeft--}
```
public abstract float getStretchOffsetLeft()
```

إرجاع أو تعيين الحد الأيسر لمستطيل التعبئة المحدد بإزاحة نسبية من الحد الأيسر لمربع حدود الشكل. النسبة المئوية الإيجابية تشير إلى تقليل، بينما السلبية تشير إلى توسيع. قراءة/كتابة float.

**الإرجاع:**
float

### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public abstract void setStretchOffsetLeft(float value)
```

إرجاع أو تعيين الحد الأيسر لمستطيل التعبئة المحدد بإزاحة نسبية من الحد الأيسر لمربع حدود الشكل. النسبة المئوية الإيجابية تشير إلى تقليل، بينما السلبية تشير إلى توسيع. قراءة/كتابة float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetTop() {#getStretchOffsetTop--}
```
public abstract float getStretchOffsetTop()
```

إرجاع أو تعيين الحد العلوي لمستطيل التعبئة المحدد بإزاحة نسبية من الحد العلوي لمربع حدود الشكل. النسبة المئوية الإيجابية تشير إلى تقليل، بينما السلبية تشير إلى توسيع. قراءة/كتابة float.

**الإرجاع:**
float

### setStretchOffsetTop(float value) {#setStretchOffsetTop-float-}
```
public abstract void setStretchOffsetTop(float value)
```

إرجاع أو تعيين الحد العلوي لمستطيل التعبئة المحدد بإزاحة نسبية من الحد العلوي لمربع حدود الشكل. النسبة المئوية الإيجابية تشير إلى تقليل، بينما السلبية تشير إلى توسيع. قراءة/كتابة float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetRight() {#getStretchOffsetRight--}
```
public abstract float getStretchOffsetRight()
```

إرجاع أو تعيين الحد الأيمن لمستطيل التعبئة المحدد بإزاحة نسبية من الحد الأيمن لمربع حدود الشكل. النسبة المئوية الإيجابية تشير إلى تقليل، بينما السلبية تشير إلى توسيع. قراءة/كتابة float.

**الإرجاع:**
float

### setStretchOffsetRight(float value) {#setStretchOffsetRight-float-}
```
public abstract void setStretchOffsetRight(float value)
```

إرجاع أو تعيين الحد الأيمن لمستطيل التعبئة المحدد بإزاحة نسبية من الحد الأيمن لمربع حدود الشكل. النسبة المئوية الإيجابية تشير إلى تقليل، بينما السلبية تشير إلى توسيع. قراءة/كتابة float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetBottom() {#getStretchOffsetBottom--}
```
public abstract float getStretchOffsetBottom()
```

إرجاع أو تعيين الحد السفلي لمستطيل التعبئة المحدد بإزاحة نسبية من الحد السفلي لمربع حدود الشكل. النسبة المئوية الإيجابية تشير إلى تقليل، بينما السلبية تشير إلى توسيع. قراءة/كتابة float.

**الإرجاع:**
float

### setStretchOffsetBottom(float value) {#setStretchOffsetBottom-float-}
```
public abstract void setStretchOffsetBottom(float value)
```

إرجاع أو تعيين الحد السفلي لمستطيل التعبئة المحدد بإزاحة نسبية من الحد السفلي لمربع حدود الشكل. النسبة المئوية الإيجابية تشير إلى تقليل، بينما السلبية تشير إلى توسيع. قراءة/كتابة float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public abstract IPPImage deletePictureCroppedAreas()
```

حذف المناطق المقصوصة من الصورة المملوءة.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // الحصول على PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // حذف المناطق المقتطعة من صورة PictureFrame
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**الإرجاع:**
[IPPImage](../../com.aspose.slides/ippimage) - الصورة المقصوصة أو الصورة الأصلية إذا لم يكن القص ضرورياً.

--------------------

هذه الطريقة تحول ملفات WMF/EMF إلى صورة PNG نقطية مع القص.

### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

ضغط الصورة عن طريق تقليل حجمها بناءً على حجم الشكل والدقة المحددة. يمكن أيضاً حذف المناطق المقصوصة.

--------------------

> طريقة ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` لتقليل حجم صورة في عرض تقديمي عن طريق تحديد دقة مستهدفة وإزالة المناطق المقصوصة:
>  
>  Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // ضغط الصورة بدقة مستهدفة 150 DPI (دقة الويب) وإزالة المناطق المقصوصة
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
 لتقليل حجم صورة في عرض تقديمي عن طريق تحديد دقة مستهدفة وإزالة المناطق المقصوصة:
>   
>  Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // الحصول على PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // ضغط الصورة بدقة مستهدفة 150 DPI (دقة الويب) وإزالة المناطق المقصوصة
>      boolean result = picFrame.getPictureFormat().compressImage(true, 150f); // دقة الويب
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| deleteCroppedAreasOfImage | boolean | إذا كان true، فإن الطريقة ستحذف المناطق المقتطعة من الصورة، مما قد يقلل حجمها أكثر. |
| resolution | float | الدقة المستهدفة بوحدة DPI. يجب أن تكون هذه القيمة موجبة وتحدد كيفية تغيير حجم الصورة. |

--------------------

تُغيّر هذه الطريقة حجم الصورة ودقتها مشابهة لميزة PowerPoint "Picture Format -> Compress Pictures". |

**الإرجاع:**
boolean - قيمة منطقية تشير إلى ما إذا تم ضغط الصورة بنجاح. تُعيد true إذا تم تعديل حجم الصورة أو قصها، وإلا تُعيد false.
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
>      // الحصول على تنسيق تعبئة الصورة للشكل
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // تعيين نمط تعبئة الصورة إلى Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // تعيين الإزاحة الأفقية للنقش إلى 20 نقطة
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
>      // الحصول على تنسيق تعبئة الصورة للشكل
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // تعيين نمط تعبئة الصورة إلى Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // تعيين الإزاحة الأفقية للنقش إلى 20 نقطة
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
>      // الحصول على تنسيق تعبئة الصورة للشكل
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // تعيين نمط تعبئة الصورة إلى Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // تعيين الإزاحة العمودية للنقش إلى -50 نقطة
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
>      // الحصول على تنسيق تعبئة الصورة للشكل
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // تعيين نمط تعبئة الصورة إلى Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // تعيين الإزاحة العمودية للنقش إلى -50 نقطة
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
public abstract float getTileScaleX()
```


Returns or sets the horizontal scale for the texture fill as a percentage. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // الحصول على تنسيق تعبئة الصورة للشكل
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // تعيين نمط تعبئة الصورة إلى Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // تعيين المقياس الأفقي للنقش إلى 120 بالمائة
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
>      // الحصول على تنسيق تعبئة الصورة للشكل
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // تعيين نمط تعبئة الصورة إلى Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // تعيين المقياس الأفقي للنقش إلى 120 بالمائة
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
>      // الحصول على تنسيق تعبئة الصورة للشكل
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // تعيين نمط تعبئة الصورة إلى Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // تعيين المقياس العمودي للنقش إلى 120 بالمائة
>      pictureFillFormat.setTileScaleY(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**Returns:
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
>      // الحصول على تنسيق تعبئة الصورة للشكل
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // تعيين نمط تعبئة الصورة إلى Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // تعيين المقياس العمودي للنقش إلى 120 بالمائة
>      pictureFillFormat.setTileScaleY(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**المعلمات:**
| المعامل | النوع | الوصف |
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
>      // الحصول على تنسيق تعبئة الصورة للشكل
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // تعيين نمط تعبئة الصورة إلى Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // تعيين المحاذاة لتجميع البلاط إلى الزاوية اليمنى السفلى
>      pictureFillFormat.setTileAlignment(RectangleAlignment.BottomRight);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
--------------------

القيمة الافتراضية هي [RectangleAlignment.TopLeft](../../com.aspose.slides/rectanglealignment\#TopLeft).

**الإرجاع:**
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
>      // الحصول على تنسيق تعبئة الصورة للشكل
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // تعيين نمط تعبئة الصورة إلى Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // تعيين المحاذاة لتجميع البلاط إلى الزاوية اليمنى السفلى
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
>      // الحصول على تنسيق تعبئة الصورة للشكل
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // تعيين نمط تعبئة الصورة إلى Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // قلب بلاطة النقش حول محورها العمودي.
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
>      // الحصول على تنسيق تعبئة الصورة للشكل
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // تعيين نمط تعبئة الصورة إلى Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // قلب بلاطة النقش حول محورها العمودي.
>      pictureFillFormat.setTileFlip(TileFlip.FlipY);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

--------------------

الافتراضي هو [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |