---
title: Slide
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر یک اسلاید در یک ارائه.
type: docs
url: /fa/com.aspose.slides/slide/
---
**وراثت:**  
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**تمام رابط‌های پیاده‌سازی شده:**  
[com.aspose.slides.ISlide](../../com.aspose.slides/islide)  
```
public final class Slide extends BaseSlide implements ISlide
```

نمایشی از یک اسلاید در یک ارائه.

## متدها

| متد | توضیح |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | مدیر HeaderFooter اسلاید را باز می‌گرداند. |
| [getThemeManager()](#getThemeManager--) | مدیر تم حاکم را باز می‌گرداند. |
| [getSlideNumber()](#getSlideNumber--) | شماره اسلاید را باز می‌گرداند. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | شماره اسلاید را باز می‌گرداند. |
| [getHidden()](#getHidden--) | مشخص می‌کند آیا اسلاید مشخص شده در نمایش اسلاید مخفی است یا نه. |
| [setHidden(boolean value)](#setHidden-boolean-) | مشخص می‌کند آیا اسلاید مشخص شده در نمایش اسلاید مخفی است یا نه. |
| [getShowMasterShapes()](#getShowMasterShapes--) | مشخص می‌کند آیا اشکال موجود در اسلاید اصلی بر روی اسلایدها نمایش داده شوند یا نه. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | مشخص می‌کند آیا اشکال موجود در اسلاید اصلی بر روی اسلایدها نمایش داده شوند یا نه. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | شیء Thumbnail Image با مقیاس‌سازی سفارشی را باز می‌گرداند. |
| [getImage()](#getImage--) | شیء Thumbnail Image (۲۰٪ از اندازه واقعی) را باز می‌گرداند. |
| [getImage(Dimension imageSize)](#getImage-java.awt.Dimension-) | شیء Thumbnail Image با اندازه مشخص شده را باز می‌گرداند. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | شیء تصویر تیب‌ف Thumbnail با پارامترهای مشخص شده را باز می‌گرداند. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | شیء Thumbnail Image را باز می‌گرداند. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | شیء Thumbnail Image با مقیاس‌سازی سفارشی را باز می‌گرداند. |
| [getImage(IRenderingOptions options, Dimension imageSize)](#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | شیء Thumbnail Image با اندازه مشخص شده را باز می‌گرداند. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | محتوای اسلاید را به عنوان فایل SVG ذخیره می‌کند. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | محتوای اسلاید را به عنوان فایل SVG ذخیره می‌کند. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | محتوای اسلاید را به عنوان فایل EMF ذخیره می‌کند. |
| [remove()](#remove--) | اسلاید را از ارائه حذف می‌کند. |
| [getLayoutSlide()](#getLayoutSlide--) | طرح اسلاید برای اسلاید جاری را باز می‌گرداند یا تنظیم می‌کند. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | طرح اسلاید برای اسلاید جاری را باز می‌گرداند یا تنظیم می‌کند. |
| [reset()](#reset--) | موقعیت، اندازه و قالب‌بندی هر شکلی که نمونه‌ای در LayoutSlide دارد را بازنشانی می‌کند. |
| [getNotesSlideManager()](#getNotesSlideManager--) | دسترسی به اسلاید یادداشت‌ها را فراهم می‌کند، افزودن و حذف آن. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | تمام نظرات اسلاید اضافه شده توسط نویسنده خاص را باز می‌گرداند. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | دنباله‌های متنی با قالب‌بندی یکسان در تمام پاراگراف‌ها در تمام اشکال قابل قبول را ترکیب می‌کند. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ISlideHeaderFooterManager getHeaderFooterManager()
```

مدیر HeaderFooter اسلاید را باز می‌گرداند. فقط-خواندنی [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**بازگشت:**  
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

مدیر تم حاکم را باز می‌گرداند. فقط-خواندنی [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**بازگشت:**  
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)

### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```

یک شماره اسلاید را باز می‌گرداند. شاخص اسلاید در مجموعه [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) همیشه برابر است با SlideNumber - Presentation.FirstSlideNumber. خواندنی/قابل‌نوشتن int.

**بازگشت:**  
int

### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```

یک شماره اسلاید را باز می‌گرداند. شاخص اسلاید در مجموعه [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) همیشه برابر است با SlideNumber - Presentation.FirstSlideNumber. خواندنی/قابل‌نوشتن int.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

مشخص می‌کند آیا اسلاید مشخص شده در نمایش اسلاید مخفی است یا نه. خواندنی/قابل‌نوشتن boolean.

**بازگشت:**  
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

مشخص می‌کند آیا اسلاید مشخص شده در نمایش اسلاید مخفی است یا نه. خواندنی/قابل‌نوشتن boolean.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

مشخص می‌کند آیا اشکال موجود در اسلاید اصلی بر روی اسلایدها نمایش داده شوند یا نه. خواندنی/قابل‌نوشتن boolean.

**بازگشت:**  
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

مشخص می‌کند آیا اشکال موجود در اسلاید اصلی بر روی اسلایدها نمایش داده شوند یا نه. خواندنی/قابل‌نوشتن boolean.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```

شیء Thumbnail Image با مقیاس‌سازی سفارشی را باز می‌گرداند.

--------------------

> ```
> The following example shows how to generate thumbnails from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("ThumbnailFromSlide.pptx");
>  try {
>      // دسترسی به اولین اسلاید
>      ISlide sld = pres.getSlides().get_Item(0);
>      // ایجاد تصویر با مقیاس کامل
>      IImage bmp = sld.getImage(1f, 1f);
>      // ذخیره تصویر در دیسک با فرمت JPEG
>      bmp.save("Thumbnail_out.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to converting slides to bitmap and saving the images in PNG.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // تبدیل اولین اسلاید در ارائه به یک شیء Bitmap
>      IImage bmp = pres.getSlides().get_Item(0).getImage();
>      // ذخیره تصویر با فرمت PNG
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
>          // ایجاد تصویر با مقیاس کامل
>          IImage bmp = sld.getImage(1f, 1f);
>          // ذخیره تصویر در دیسک با فرمت JPEG
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
>      // تعریف ابعاد
>      int desiredX = 1200;
>      int desiredY = 800;
>      // دریافت مقادیر مقیاس‌دار X و Y
>      float ScaleX = (float)(1.0 / pres.getSlideSize().getSize().getWidth()) * desiredX;
>      float ScaleY = (float)(1.0 / pres.getSlideSize().getSize().getHeight()) * desiredY;
>      for (ISlide sld : pres.getSlides())
>      {
>          // ایجاد تصویر با مقیاس کامل
>          IImage bmp = sld.getImage(ScaleX, ScaleY);
>          // ذخیره تصویر در دیسک با فرمت JPEG
>          bmp.save("Slide.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
> ```


**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| scaleX | float | مقدار برای مقیاس‌گذاری این Thumbnail در جهت محور x. |
| scaleY | float | مقدار برای مقیاس‌گذاری این Thumbnail در جهت محور y. |

**بازگشت:**  
[IImage](../../com.aspose.slides/iimage) - IImage object.

### getImage() {#getImage--}
```
public final IImage getImage()
```

شیء Thumbnail Image (۲۰٪ از اندازه واقعی) را باز می‌گرداند.

**بازگشت:**  
[IImage](../../com.aspose.slides/iimage)

### getImage(Dimension imageSize) {#getImage-java.awt.Dimension-}
```
public final IImage getImage(Dimension imageSize)
```

شیء Thumbnail Image با اندازه مشخص شده را باز می‌گرداند.

--------------------

> ```
> The following example shows how to converting slides to images with custom sizes using C#.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // اولین اسلاید در ارائه را به یک شیء Bitmap با اندازه مشخص تبدیل می‌کند
>      IImage bmp = pres.getSlides().get_Item(0).getImage(new Dimension(1820, 1040));
>      // تصویر را در فرمت JPEG ذخیره می‌کند
>      bmp.save("Slide_0.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| imageSize | java.awt.Dimension | اندازه تصویری که باید ایجاد شود. |

**بازگشت:**  
[IImage](../../com.aspose.slides/iimage) - Image object.

### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public final IImage getImage(ITiffOptions options)
```

شیء تصویر تیب‌ف Thumbnail با پارامترهای مشخص شده را باز می‌گرداند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | گزینه‌های تیب‌ف. |

**بازگشت:**  
[IImage](../../com.aspose.slides/iimage) - Image object.

### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public final IImage getImage(IRenderingOptions options)
```

شیء Thumbnail Image را باز می‌گرداند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های رندرینگ. |

**بازگشت:**  
[IImage](../../com.aspose.slides/iimage) - Image object.

### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

شیء Thumbnail Image با مقیاس‌سازی سفارشی را باز می‌گرداند.

--------------------

> ```
> The following example shows how to converting slides With notes and comments to Images.
>  
>  Presentation pres = new Presentation("PresentationNotesComments.pptx");
>  try {
>      // ایجاد گزینه‌های رندرینگ
>      IRenderingOptions options = new RenderingOptions();
>      // ایجاد گزینه‌های قالب‌بندی یادداشت‌ها و نظرات
>      NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
>      // موقعیت یادداشت‌ها را در صفحه تنظیم می‌کند
>      notesCommentsLayouting.setNotesPosition(NotesPositions.BottomTruncated);
>      // موقعیت نظرات را در صفحه تنظیم می‌کند
>      notesCommentsLayouting.setCommentsPosition(CommentsPositions.Right);
>      // عرض ناحیه خروجی نظرات را تنظیم می‌کند
>      notesCommentsLayouting.setCommentsAreaWidth(500);
>      // رنگ ناحیه نظرات را تنظیم می‌کند
>      notesCommentsLayouting.setCommentsAreaColor(Color.WHITE);
>      // تنظیم گزینه‌های قالب‌بندی برای رندرینگ
>      options.setSlidesLayoutOptions(notesCommentsLayouting);
>      // اولین اسلاید ارائه را به یک شیء BufferedImage تبدیل می‌کند
>      IImage image = pres.getSlides().get_Item(0).getImage(options, 2f, 2f);
>      // تصویر را در قالب GIF ذخیره می‌کند
>      image.save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های رندرینگ. |
| scaleX | float | مقدار برای مقیاس‌گذاری این Thumbnail در جهت محور x. |
| scaleY | float | مقدار برای مقیاس‌گذاری این Thumbnail در جهت محور y. |

**بازگشت:**  
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.

### getImage(IRenderingOptions options, Dimension imageSize) {#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public final IImage getImage(IRenderingOptions options, Dimension imageSize)
```

شیء Thumbnail Image با اندازه مشخص شده را باز می‌گرداند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های رندرینگ. |
| imageSize | java.awt.Dimension | اندازه تصویری که باید ایجاد شود. |

**بازگشت:**  
[IImage](../../com.aspose.slides/iimage) - Image object.

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

محتوای اسلاید را به عنوان فایل SVG ذخیره می‌کند.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.svg");
>      {
>          // اولین اسلاید را به عنوان فایل SVG ذخیره می‌کند
>          pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان هدف |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

محتوای اسلاید را به عنوان فایل SVG ذخیره می‌کند.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file with options.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide1.svg");
>      SVGOptions options = new SVGOptions();
>      options.setVectorizeText(true);
>      // اولین اسلاید را به عنوان فایل SVG ذخیره می‌کند
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان هدف |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | گزینه‌های تولید SVG |

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

محتوای اسلاید را به عنوان فایل EMF ذخیره می‌کند.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into a metafile.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.emf");
>      {
>          // اولین اسلاید را به عنوان متافایل ذخیره می‌کند
>          pres.getSlides().get_Item(0).writeAsEmf(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان هدف |

### remove() {#remove--}
```
public final void remove()
```

اسلاید را از ارائه حذف می‌کند.

### getLayoutSlide() {#getLayoutSlide--}
```
public final ILayoutSlide getLayoutSlide()
```

طرح اسلاید برای اسلاید جاری را باز می‌گرداند یا تنظیم می‌کند. خواندنی/قابل‌نوشتن [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**بازگشت:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public final void setLayoutSlide(ILayoutSlide value)
```

طرح اسلاید برای اسلاید جاری را باز می‌گرداند یا تنظیم می‌کند. خواندنی/قابل‌نوشتن [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |

### reset() {#reset--}
```
public final void reset()
```

موقعیت، اندازه و قالب‌بندی هر شکلی که نمونه‌ای در LayoutSlide دارد را بازنشانی می‌کند.

### getNotesSlideManager() {#getNotesSlideManager--}
```
public final INotesSlideManager getNotesSlideManager()
```

دسترسی به اسلاید یادداشت‌ها را فراهم می‌کند، افزودن و حذف آن. فقط-خواندنی [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**بازگشت:**  
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)

### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public final IComment[] getSlideComments(ICommentAuthor author)
```

تمام نظرات اسلاید اضافه شده توسط نویسنده خاص را باز می‌گرداند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | نویسنده نظرات برای پیدا کردن یا null برای بازگرداندن تمام نظرات. |

**بازگشت:**  
com.aspose.slides.IComment[] - آرایه‌ای از [Comment](../../com.aspose.slides/comment).

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

دنباله‌های متنی با قالب‌بندی یکسان در تمام پاراگراف‌ها در تمام اشکال قابل قبول را ترکیب می‌کند.