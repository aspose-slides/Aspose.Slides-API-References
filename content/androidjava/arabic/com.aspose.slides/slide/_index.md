---
title: Slide
second_title: Aspose.Slides لنظام Android عبر واجهة برمجة تطبيقات Java
description: يمثل شريحة في عرض تقديمي.
type: docs
url: /ar/com.aspose.slides/slide/
---
**الوراثة:**  
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**جميع الواجهات المنفذة:**  
[com.aspose.slides.ISlide](../../com.aspose.slides/islide)  
```
public final class Slide extends BaseSlide implements ISlide
```

يمثل شريحة في عرض تقديمي.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | إرجاع مدير HeaderFooter للشريحة. |
| [getThemeManager()](#getThemeManager--) | إرجاع مدير الثيم المتجاوز. |
| [getSlideNumber()](#getSlideNumber--) | إرجاع رقم الشريحة. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | إرجاع رقم الشريحة. |
| [getHidden()](#getHidden--) | تحديد ما إذا كانت الشريحة المحددة مخفية أثناء عرض الشرائح. |
| [setHidden(boolean value)](#setHidden-boolean-) | تحديد ما إذا كانت الشريحة المحددة مخفية أثناء عرض الشرائح. |
| [getShowMasterShapes()](#getShowMasterShapes--) | تحديد ما إذا كان يجب عرض الأشكال على الشريحة الرئيسية على الشرائح أم لا. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | تحديد ما إذا كان يجب عرض الأشكال على الشريحة الرئيسية على الشرائح أم لا. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | إرجاع كائن Thumbnail Image مع مقياس مخصص. |
| [getImage()](#getImage--) | إرجاع كائن Thumbnail Image (20% من الحجم الحقيقي). |
| [getImage(Size imageSize)](#getImage-com.aspose.slides.android.Size-) | إرجاع كائن Thumbnail Image بالحجم المحدد. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | إرجاع كائن صورة Thumbnail tiff مع معلمات محددة. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | إرجاع كائن Thumbnail Image. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | إرجاع كائن Thumbnail Image مع مقياس مخصَّص. |
| [getImage(IRenderingOptions options, Size imageSize)](#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | إرجاع كائن Thumbnail Image بالحجم المحدد. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | حفظ محتوى الشريحة كملف SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | حفظ محتوى الشريحة كملف SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | حفظ محتوى الشريحة كملف EMF. |
| [remove()](#remove--) | إزالة الشريحة من العرض التقديمي. |
| [getLayoutSlide()](#getLayoutSlide--) | إرجاع أو تعيين شريحة التخطيط للشريحة الحالية. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | إرجاع أو تعيين شريحة التخطيط للشريحة الحالية. |
| [reset()](#reset--) | إعادة ضبط الموقع والحجم والتنسيق لكل شكل لديه نموذج على LayoutSlide. |
| [getNotesSlideManager()](#getNotesSlideManager--) | السماح بالوصول إلى شريحة الملاحظات، وإضافتها وإزالتها. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | إرجاع جميع تعليقات الشريحة التي أضافها مؤلف محدد. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | دمج المقاطع ذات التنسيق نفسه في جميع الفقرات في جميع الأشكال القابلة للمعالجة. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ISlideHeaderFooterManager getHeaderFooterManager()
```

إرجاع مدير HeaderFooter للشريحة. للقراءة فقط [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**الإرجاع:**  
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

إرجاع مدير الثيم المتجاوز. للقراءة فقط [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**الإرجاع:**  
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)

### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```

إرجاع رقم الشريحة. فهرس الشريحة في مجموعة [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) يساوي دائمًا SlideNumber - Presentation.FirstSlideNumber. قابل للقراءة والكتابة int.

**الإرجاع:**  
int

### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```

إرجاع رقم الشريحة. فهرس الشريحة في مجموعة [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) يساوي دائمًا SlideNumber - Presentation.FirstSlideNumber. قابل للقراءة والكتابة int.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

تحديد ما إذا كانت الشريحة المحددة مخفية أثناء عرض الشرائح. قابل للقراءة والكتابة boolean.

**الإرجاع:**  
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

تحديد ما إذا كانت الشريحة المحددة مخفية أثناء عرض الشرائح. قابل للقراءة والكتابة boolean.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

تحديد ما إذا كان يجب عرض الأشكال على الشريحة الرئيسية على الشرائح أم لا. قابل للقراءة والكتابة boolean.

**الإرجاع:**  
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

تحديد ما إذا كان يجب عرض الأشكال على الشريحة الرئيسية على الشرائح أم لا. قابل للقراءة والكتابة boolean.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```

إرجاع كائن Thumbnail Image مع مقياس مخصص.

--------------------

> ```
> The following example shows how to generate thumbnails from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("ThumbnailFromSlide.pptx");
>  try {
>      // الوصول إلى الشريحة الأولى
>      ISlide sld = pres.getSlides().get_Item(0);
>      // إنشاء صورة بمقياس كامل
>      IImage bmp = sld.getImage(1f, 1f);
>      // حفظ الصورة على القرص بصيغة JPEG
>      bmp.save("Thumbnail_out.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to converting slides to bitmap and saving the images in PNG.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // تحويل الشريحة الأولى في العرض التقديمي إلى كائن Bitmap
>      IImage bmp = pres.getSlides().get_Item(0).getImage();
>      // حفظ الصورة بصيغة PNG
>      bmp.save("Slide_0.png", ImageFormat.Png);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint PPT/PPTX to JPG.
>  
>  Presentation pres = new Presentation("PowerPoint-Presentation.ppt");
>  try {
>      for (ISlide sld : pres.getSlides())
>      {
>          // إنشاء صورة بمقياس كامل
>          IImage bmp = sld.getImage(1f, 1f);
>          // حفظ الصورة على القرص بصيفة JPEG
>          bmp.save("Slide_"+sld.getSlideNumber()+"0.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint PPT/PPTX to JPG with customized dimensions.
>  
>  Presentation pres = new Presentation("PowerPoint-Presentation.pptx");
>  try {
>      // تحديد الأبعاد
>      int desiredX = 1200;
>      int desiredY = 800;
>      // الحصول على القيم المقاسة للـ X و Y
>      float ScaleX = (float)(1.0 / pres.getSlideSize().getSize().getWidth()) * desiredX;
>      float ScaleY = (float)(1.0 / pres.getSlideSize().getSize().getHeight()) * desiredY;
>      for (ISlide sld : pres.getSlides())
>      {
>          // إنشاء صورة بمقياس كامل
>          IImage bmp = sld.getImage(ScaleX, ScaleY);
>          // حفظ الصورة على القرص بصيغة JPEG
>          bmp.save("Slide.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
> ```


**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| scaleX | float | القيمة التي يتم بها تكبير هذه الصورة المصغرة في اتجاه المحور السيني. |
| scaleY | float | القيمة التي يتم بها تكبير هذه الصورة المصغرة في اتجاه المحور الصادي. |

**الإرجاع:**  
[IImage](../../com.aspose.slides/iimage) - IImage object.

### getImage() {#getImage--}
```
public final IImage getImage()
```

إرجاع كائن Thumbnail Image (20% من الحجم الحقيقي).

**الإرجاع:**  
[IImage](../../com.aspose.slides/iimage)

### getImage(Size imageSize) {#getImage-com.aspose.slides.android.Size-}
```
public final IImage getImage(Size imageSize)
```

إرجاع كائن Thumbnail Image بالحجم المحدد.

--------------------

> ```
> The following example shows how to converting slides to images with custom sizes using C#.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // يحول الشريحة الأولى في العرض التقديمي إلى كائن Bitmap بالحجم المحدد
>      IImage bmp = pres.getSlides().get_Item(0).getImage(new com.aspose.slides.android.Size(1820, 1040));
>      // يحفظ الصورة بصيغة JPEG
>      bmp.save("Slide_0.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
> ```

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| imageSize | [Size](../../com.aspose.slides.android/size) | حجم الصورة لإنشائها. |

**الإرجاع:**  
[IImage](../../com.aspose.slides/iimage) - Image object.

### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public final IImage getImage(ITiffOptions options)
```

إرجاع كائن صورة Thumbnail tiff مع معلمات محددة.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | خيارات Tiff. |

**الإرجاع:**  
[IImage](../../com.aspose.slides/iimage) - Image object.

### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public final IImage getImage(IRenderingOptions options)
```

إرجاع كائن Thumbnail Image.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات العرض. |

**الإرجاع:**  
[IImage](../../com.aspose.slides/iimage) - Image object.

### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

إرجاع كائن Thumbnail Image مع مقياس مخصَّص.

--------------------

> ```
> The following example shows how to converting slides With notes and comments to Images.
>  
>  Presentation pres = new Presentation("PresentationNotesComments.pptx");
>  try {
>      // إنشاء خيارات العرض
>      IRenderingOptions options = new RenderingOptions();
>      // إنشاء خيارات تخطيط الملاحظات والتعليقات
>      NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
>      // تعيين موضع الملاحظات على الصفحة
>      notesCommentsLayouting.setNotesPosition(NotesPositions.BottomTruncated);
>      // تعيين موضع التعليقات على الصفحة
>      notesCommentsLayouting.setCommentsPosition(CommentsPositions.Right);
>      // تعيين عرض منطقة مخرجات التعليقات
>      notesCommentsLayouting.setCommentsAreaWidth(500);
>      // تعيين اللون لمنطقة التعليقات
>      notesCommentsLayouting.setCommentsAreaColor(Color.WHITE);
>      // تعيين خيارات التخطيط للعرض
>      options.setSlidesLayoutOptions(notesCommentsLayouting);
>      // تحويل الشريحة الأولى في العرض التقديمي إلى كائن android.graphics.Bitmap
>      IImage image = pres.getSlides().get_Item(0).getImage(options, 2f, 2f);
>      // حفظ الصورة بصيغة GIF
>      image.save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات العرض. |
| scaleX | float | القيمة التي يتم بها تكبير هذه الصورة المصغرة في اتجاه المحور السيني. |
| scaleY | float | القيمة التي يتم بها تكبير هذه الصورة المصغرة في اتجاه المحور الصادي. |

**الإرجاع:**  
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.

### getImage(IRenderingOptions options, Size imageSize) {#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public final IImage getImage(IRenderingOptions options, Size imageSize)
```

إرجاع كائن Thumbnail Image بالحجم المحدد.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات العرض. |
| imageSize | [Size](../../com.aspose.slides.android/size) | حجم الصورة لإنشائها. |

**الإرجاع:**  
[IImage](../../com.aspose.slides/iimage) - Image object.

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

حفظ محتوى الشريحة كملف SVG.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.svg");
>      {
>          // حفظ الشريحة الأولى كملف SVG
>          pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | دفق الهدف |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

حفظ محتوى الشريحة كملف SVG.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file with options.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide1.svg");
>      SVGOptions options = new SVGOptions();
>      options.setVectorizeText(true);
>      // حفظ الشريحة الأولى كملف SVG
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | دفق الهدف |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | خيارات إنشاء SVG |

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

حفظ محتوى الشريحة كملف EMF.

--------------------

> ```
> المثال التالي يوضح كيفية تحويل الشريحة الأولى من عرض PowerPoint إلى ملف ميتا.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.emf");
>      {
>          // حفظ الشريحة الأولى كملف ميتا
>          pres.getSlides().get_Item(0).writeAsEmf(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | دفق الهدف |

### remove() {#remove--}
```
public final void remove()
```

إزالة الشريحة من العرض التقديمي.

### getLayoutSlide() {#getLayoutSlide--}
```
public final ILayoutSlide getLayoutSlide()
```

إرجاع أو تعيين شريحة التخطيط للشريحة الحالية. قابل للقراءة والكتابة [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**الإرجاع:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public final void setLayoutSlide(ILayoutSlide value)
```

إرجاع أو تعيين شريحة التخطيط للشريحة الحالية. قابل للقراءة والكتابة [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |

### reset() {#reset--}
```
public final void reset()
```

إعادة ضبط الموقع والحجم والتنسيق لكل شكل لديه نموذج على LayoutSlide.

### getNotesSlideManager() {#getNotesSlideManager--}
```
public final INotesSlideManager getNotesSlideManager()
```

السماح بالوصول إلى شريحة الملاحظات، وإضافتها وإزالتها. للقراءة فقط [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**الإرجاع:**  
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)

### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public final IComment[] getSlideComments(ICommentAuthor author)
```

إرجاع جميع تعليقات الشريحة التي أضافها مؤلف محدد.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | مؤلف التعليقات للبحث عنها أو null لإرجاع جميع التعليقات. |

**الإرجاع:**  
com.aspose.slides.IComment[] - مصفوفة من [Comment](../../com.aspose.slides/comment).

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

دمج المقاطع ذات التنسيق نفسه في جميع الفقرات في جميع الأشكال القابلة للمعالجة.