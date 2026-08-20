---
title: Slide
second_title: مرجع API لـ Aspose.Slides للغة Java
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

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | يرجع مدير HeaderFooter للشريحة. |
| [getThemeManager()](#getThemeManager--) | يرجع مدير الثيم المتجاوز. |
| [getSlideNumber()](#getSlideNumber--) | يرجع رقم الشريحة. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | يرجع رقم الشريحة. |
| [getHidden()](#getHidden--) | يحدد ما إذا كانت الشريحة المحددة مخفية أثناء عرض الشرائح. |
| [setHidden(boolean value)](#setHidden-boolean-) | يحدد ما إذا كانت الشريحة المحددة مخفية أثناء عرض الشرائح. |
| [getShowMasterShapes()](#getShowMasterShapes--) | يحدد ما إذا كان يجب عرض الأشكال على الشريحة الأساسية على الشرائح أم لا. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | يحدد ما إذا كان يجب عرض الأشكال على الشريحة الأساسية على الشرائح أم لا. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | يرجع كائن Thumbnail Image مع مقياس مخصص. |
| [getImage()](#getImage--) | يرجع كائن Thumbnail Image (20 % من الحجم الحقيقي). |
| [getImage(Dimension imageSize)](#getImage-java.awt.Dimension-) | يرجع كائن Thumbnail Image بالحجم المحدد. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | يرجع كائن صورة Thumbnail tiff بالمعلمات المحددة. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | يرجع كائن Thumbnail Image. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | يرجع كائن Thumbnail Image مع مقياس مخصص. |
| [getImage(IRenderingOptions options, Dimension imageSize)](#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | يرجع كائن Thumbnail Image بالحجم المحدد. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | يحفظ محتوى الشريحة كملف SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | يحفظ محتوى الشريحة كملف SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | يحفظ محتوى الشريحة كملف EMF. |
| [remove()](#remove--) | يزيل الشريحة من العرض التقديمي. |
| [getLayoutSlide()](#getLayoutSlide--) | يرجع أو يضبط شريحة التخطيط للشريحة الحالية. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | يرجع أو يضبط شريحة التخطيط للشريحة الحالية. |
| [reset()](#reset--) | يعيد ضبط الموضع والحجم والتنسيق لكل شكل له نموذج على LayoutSlide. |
| [getNotesSlideManager()](#getNotesSlideManager--) | يسمح بالوصول إلى شريحة الملاحظات، وإضافتها وإزالتها. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | يرجع كل تعليقات الشريحة التي أضافها مؤلف معين. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | يجمع القطاعات ذات التنسيق المتطابق في جميع الفقرات بجميع الأشكال المقبولة. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ISlideHeaderFooterManager getHeaderFooterManager()
```

يرجع مدير HeaderFooter للشريحة. للقراءة فقط [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**الإرجاع:**  
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

يرجع مدير الثيم المتجاوز. للقراءة فقط [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**الإرجاع:**  
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)

### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```

يرجع رقم الشريحة. الفهرس في مجموعة [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) يساوي دائمًا SlideNumber - Presentation.FirstSlideNumber. قراءة/كتابة int.

**الإرجاع:**  
int

### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```

يرجع رقم الشريحة. الفهرس في مجموعة [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) يساوي دائمًا SlideNumber - Presentation.FirstSlideNumber. قراءة/كتابة int.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

يحدد ما إذا كانت الشريحة المحددة مخفية أثناء عرض الشرائح. قراءة/كتابة boolean.

**الإرجاع:**  
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

يحدد ما إذا كانت الشريحة المحددة مخفية أثناء عرض الشرائح. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

يحدد ما إذا كان يجب عرض الأشكال على الشريحة الأساسية على الشرائح أم لا. قراءة/كتابة boolean.

**الإرجاع:**  
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

يحدد ما إذا كان يجب عرض الأشكال على الشريحة الأساسية على الشرائح أم لا. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```

يرجع كائن Thumbnail Image مع مقياس مخصص.

--------------------

> ```
> The following example shows how to generate thumbnails from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("ThumbnailFromSlide.pptx");
>  try {
>      // الوصول إلى الشريحة الأولى
>      ISlide sld = pres.getSlides().get_Item(0);
>      // إنشاء صورة بالحجم الكامل
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
>          // إنشاء صورة بالحجم الكامل
>          IImage bmp = sld.getImage(1f, 1f);
>          // حفظ الصورة على القرص بصيغة JPEG
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
>      // تعريف الأبعاد
>      int desiredX = 1200;
>      int desiredY = 800;
>      // الحصول على القيم المقاسة لـ X و Y
>      float ScaleX = (float)(1.0 / pres.getSlideSize().getSize().getWidth()) * desiredX;
>      float ScaleY = (float)(1.0 / pres.getSlideSize().getSize().getHeight()) * desiredY;
>      for (ISlide sld : pres.getSlides())
>      {
>          // إنشاء صورة بالحجم الكامل
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
| scaleX | float | القيمة التي يُقاس بها هذا Thumbnail على محور x. |
| scaleY | float | القيمة التي يُقاس بها هذا Thumbnail على محور y. |

**الإرجاع:**  
[IImage](../../com.aspose.slides/iimage) - كائن IImage.

### getImage() {#getImage--}
```
public final IImage getImage()
```

يرجع كائن Thumbnail Image (20 % من الحجم الحقيقي).

**الإرجاع:**  
[IImage](../../com.aspose.slides/iimage)

### getImage(Dimension imageSize) {#getImage-java.awt.Dimension-}
```
public final IImage getImage(Dimension imageSize)
```

يرجع كائن Thumbnail Image بالحجم المحدد.

--------------------

> ```
> The following example shows how to converting slides to images with custom sizes using C#.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // يحول الشريحة الأولى في العرض التقديمي إلى صورة Bitmap بالحجم المحدد
>      IImage bmp = pres.getSlides().get_Item(0).getImage(new Dimension(1820, 1040));
>      // يحفظ الصورة بصيغة JPEG
>      bmp.save("Slide_0.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| imageSize | java.awt.Dimension | حجم الصورة التي سيتم إنشاؤها. |

**الإرجاع:**  
[IImage](../../com.aspose.slides/iimage) - كائن Image.

### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public final IImage getImage(ITiffOptions options)
```

يرجع كائن صورة Thumbnail tiff بالمعلمات المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | خيارات Tiff. |

**الإرجاع:**  
[IImage](../../com.aspose.slides/iimage) - كائن Image.

### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public final IImage getImage(IRenderingOptions options)
```

يرجع كائن Thumbnail Image.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات التصيير. |

**الإرجاع:**  
[IImage](../../com.aspose.slides/iimage) - كائن Image.

### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

يرجع كائن Thumbnail Image مع مقياس مخصص.

--------------------

> ```
> The following example shows how to converting slides With notes and comments to Images.
>  
>  Presentation pres = new Presentation("PresentationNotesComments.pptx");
>  try {
>      // Create the rendering options
>      IRenderingOptions options = new RenderingOptions();
>      // Create notes and comments layouting options
>      NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
>      // Sets the position of the notes on the page
>      notesCommentsLayouting.setNotesPosition(NotesPositions.BottomTruncated);
>      // Sets the position of the comments on the page
>      notesCommentsLayouting.setCommentsPosition(CommentsPositions.Right);
>      // Sets the width of the comment output area
>      notesCommentsLayouting.setCommentsAreaWidth(500);
>      // Sets the color for the comments area
>      notesCommentsLayouting.setCommentsAreaColor(Color.WHITE);
>      // Set layout options for rendering
>      options.setSlidesLayoutOptions(notesCommentsLayouting);
>      // Converts the first slide of the presentation to a BufferedImage object
>      IImage image = pres.getSlides().get_Item(0).getImage(options, 2f, 2f);
>      // Saves the image in the GIF format
>      image.save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات التصيير. |
| scaleX | float | القيمة التي يُقاس بها هذا Thumbnail على محور x. |
| scaleY | float | القيمة التي يُقاس بها هذا Thumbnail على محور y. |

**الإرجاع:**  
[IImage](../../com.aspose.slides/iimage) - كائنات Bitmap.

### getImage(IRenderingOptions options, Dimension imageSize) {#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public final IImage getImage(IRenderingOptions options, Dimension imageSize)
```

يرجع كائن Thumbnail Image بالحجم المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات التصيير. |
| imageSize | java.awt.Dimension | حجم الصورة التي سيتم إنشاؤها. |

**الإرجاع:**  
[IImage](../../com.aspose.slides/iimage) - كائن Image.

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

يحفظ محتوى الشريحة كملف SVG.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.svg");
>      {
>          // يحفظ الشريحة الأولى كملف SVG
>          pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | الدفق الهدف |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

يحفظ محتوى الشريحة كملف SVG.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file with options.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide1.svg");
>      SVGOptions options = new SVGOptions();
>      options.setVectorizeText(true);
>      // يحفظ الشريحة الأولى كملف SVG
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | الدفق الهدف |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | خيارات إنشاء SVG |

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

يحفظ محتوى الشريحة كملف EMF.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into a metafile.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.emf");
>      {
>          // يحفظ الشريحة الأولى كملف ميتا
>          pres.getSlides().get_Item(0).writeAsEmf(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | الدفق الهدف |

### remove() {#remove--}
```
public final void remove()
```

يزيل الشريحة من العرض التقديمي.

### getLayoutSlide() {#getLayoutSlide--}
```
public final ILayoutSlide getLayoutSlide()
```

يرجع أو يضبط شريحة التخطيط للشريحة الحالية. قراءة/كتابة [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**الإرجاع:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public final void setLayoutSlide(ILayoutSlide value)
```

يرجع أو يضبط شريحة التخطيط للشريحة الحالية. قراءة/كتابة [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |

### reset() {#reset--}
```
public final void reset()
```

يعيد ضبط الموضع والحجم والتنسيق لكل شكل له نموذج على LayoutSlide.

### getNotesSlideManager() {#getNotesSlideManager--}
```
public final INotesSlideManager getNotesSlideManager()
```

يسمح بالوصول إلى شريحة الملاحظات، وإضافتها وإزالتها. للقراءة فقط [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**الإرجاع:**  
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)

### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public final IComment[] getSlideComments(ICommentAuthor author)
```

يرجع كل تعليقات الشريحة التي أضافها مؤلف معين.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | مؤلف التعليقات للبحث عنه أو null لإرجاع كل التعليقات. |

**الإرجاع:**  
com.aspose.slides.IComment[] - مصفوفة من [Comment](../../com.aspose.slides/comment).

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

يجمع القطاعات ذات التنسيق المتطابق في جميع الفقرات بجميع الأشكال المقبولة.