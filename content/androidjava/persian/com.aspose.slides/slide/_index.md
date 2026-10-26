---
title: Slide
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: یک اسلاید در یک ارائه را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/slide/
---
**ارث‌بری:**  
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**همه اینترفیس‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.ISlide](../../com.aspose.slides/islide)  
```
public final class Slide extends BaseSlide implements ISlide
```

یک اسلاید در یک ارائه را نشان می‌دهد.

## متدها

| متد | توضیح |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | مدیر HeaderFooter اسلاید را برمی‌گرداند. |
| [getThemeManager()](#getThemeManager--) | مدیر تم برتری را برمی‌گرداند. |
| [getSlideNumber()](#getSlideNumber--) | شماره اسلاید را برمی‌گرداند. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | شماره اسلاید را برمی‌گرداند. |
| [getHidden()](#getHidden--) | تعیین می‌کند که آیا اسلاید مشخص شده در نمایش اسلاید مخفی است. |
| [setHidden(boolean value)](#setHidden-boolean-) | تعیین می‌کند که آیا اسلاید مشخص شده در نمایش اسلاید مخفی است. |
| [getShowMasterShapes()](#getShowMasterShapes--) | مشخص می‌کند آیا اشکال روی اسلاید اصلی باید روی اسلایدها نمایش داده شوند یا خیر. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | مشخص می‌کند آیا اشکال روی اسلاید اصلی باید روی اسلایدها نمایش داده شوند یا خیر. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | یک شیء تصویر بندانگشتی با مقیاس‌گذاری سفارشی را برمی‌گرداند. |
| [getImage()](#getImage--) | یک شیء تصویر بندانگشتی (20٪ از اندازه واقعی) را برمی‌گرداند. |
| [getImage(Size imageSize)](#getImage-com.aspose.slides.android.Size-) | یک شیء تصویر بندانگشتی با اندازه مشخص را برمی‌گرداند. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | یک شیء تصویر TIFF بندانگشتی با پارامترهای مشخص را برمی‌گرداند. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | یک شیء تصویر بندانگشتی را برمی‌گرداند. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | یک شیء تصویر بندانگشتی با مقیاس‌گذاری سفارشی را برمی‌گرداند. |
| [getImage(IRenderingOptions options, Size imageSize)](#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | یک شیء تصویر بندانگشتی با اندازه مشخص را برمی‌گرداند. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | محتوای اسلاید را به‌عنوان فایل SVG ذخیره می‌کند. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | محتوای اسلاید را به‌عنوان فایل SVG ذخیره می‌کند. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | محتوای اسلاید را به‌عنوان فایل EMF ذخیره می‌کند. |
| [remove()](#remove--) | اسلاید را از ارائه حذف می‌کند. |
| [getLayoutSlide()](#getLayoutSlide--) | طرح اسلاید برای اسلید فعلی را برمی‌گرداند یا تنظیم می‌کند. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | طرح اسلاید برای اسلید فعلی را برمی‌گرداند یا تنظیم می‌کند. |
| [reset()](#reset--) | موقعیت، اندازه و قالب‌بندی هر شکلی که یک نمونه در LayoutSlide دارد را بازنشانی می‌کند. |
| [getNotesSlideManager()](#getNotesSlideManager--) | اجازۀ دسترسی به اسلاید یادداشت‌ها، اضافه و حذف آن را می‌دهد. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | تمام نظرات اسلاید اضافه‌شده توسط نویسنده خاص را برمی‌گرداند. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | بخش‌های متنی با قالب‌بندی یکسان را در تمام پاراگراف‌ها در تمام اشکال قابل قبول ترکیب می‌کند. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ISlideHeaderFooterManager getHeaderFooterManager()
```

مدیر HeaderFooter اسلاید را برمی‌گرداند. فقط-خواندنی [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**بازگشت:**  
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

مدیر تم برتری را برمی‌گرداند. فقط-خواندنی [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**بازگشت:**  
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)

### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```

شماره اسلاید را برمی‌گرداند. شاخص اسلاید در مجموعه [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) همیشه برابر است با SlideNumber - Presentation.FirstSlideNumber. قابل خواندن/نوشتن int.

**بازگشت:**  
int

### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```

شماره اسلاید را تنظیم می‌کند. شاخص اسلاید در مجموعه [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) همیشه برابر است با SlideNumber - Presentation.FirstSlideNumber. قابل خواندن/نوشتن int.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

تعیین می‌کند که آیا اسلاید مشخص شده در نمایش اسلاید مخفی است. قابل خواندن/نوشتن boolean.

**بازگشت:**  
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

تعیین می‌کند که آیا اسلاید مشخص شده در نمایش اسلاید مخفی است. قابل خواندن/نوشتن boolean.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

مشخص می‌کند آیا اشکال روی اسلاید اصلی باید روی اسلایدها نمایش داده شوند یا خیر. قابل خواندن/نوشتن boolean.

**بازگشت:**  
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

مشخص می‌کند آیا اشکال روی اسلاید اصلی باید روی اسلایدها نمایش داده شوند یا خیر. قابل خواندن/نوشتن boolean.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```

یک شیء تصویر بندانگشتی با مقیاس‌گذاری سفارشی را برمی‌گرداند.

--------------------

> ```
> The following example shows how to generate thumbnails from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("ThumbnailFromSlide.pptx");
>  try {
>      // دسترسی به اسلاید اول
>      ISlide sld = pres.getSlides().get_Item(0);
>      // ایجاد یک تصویر با مقیاس کامل
>      IImage bmp = sld.getImage(1f, 1f);
>      // ذخیره تصویر بر روی دیسک با فرمت JPEG
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
>          // ایجاد یک تصویر با مقیاس کامل
>          IImage bmp = sld.getImage(1f, 1f);
>          // ذخیره تصویر بر روی دیسک با فرمت JPEG
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
>          // ایجاد یک تصویر با مقیاس کامل
>          IImage bmp = sld.getImage(ScaleX, ScaleY);
>          // ذخیره تصویر بر روی دیسک با فرمت JPEG
>          bmp.save("Slide.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
> ```


**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| scaleX | float | مقدار مقیاس این بندانگشتی در راستای محور x. |
| scaleY | float | مقدار مقیاس این بندانگشتی در راستای محور y. |

**بازگشت:**  
[IImage](../../com.aspose.slides/iimage) - IImage object.

### getImage() {#getImage--}
```
public final IImage getImage()
```

یک شیء تصویر بندانگشتی (20٪ از اندازه واقعی) را برمی‌گرداند.

**بازگشت:**  
[IImage](../../com.aspose.slides/iimage)

### getImage(Size imageSize) {#getImage-com.aspose.slides.android.Size-}
```
public final IImage getImage(Size imageSize)
```

یک شیء تصویر بندانگشتی با اندازه مشخص را برمی‌گرداند.

--------------------

> ```
> The following example shows how to converting slides to images with custom sizes using C#.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // اسلاید اول در ارائه را به یک Bitmap با اندازه مشخص تبدیل می‌کند
>      IImage bmp = pres.getSlides().get_Item(0).getImage(new com.aspose.slides.android.Size(1820, 1040));
>      // تصویر را با فرمت JPEG ذخیره می‌کند
>      bmp.save("Slide_0.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
> ```


**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| imageSize | [Size](../../com.aspose.slides.android/size) | اندازه تصویر برای ایجاد. |

**بازگشت:**  
[IImage](../../com.aspose.slides/iimage) - Image object.

### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public final IImage getImage(ITiffOptions options)
```

یک شیء تصویر TIFF بندانگشتی با پارامترهای مشخص را برمی‌گرداند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | گزینه‌های Tiff. |

**بازگشت:**  
[IImage](../../com.aspose.slides/iimage) - Image object.

### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public final IImage getImage(IRenderingOptions options)
```

یک شیء تصویر بندانگشتی را برمی‌گرداند.

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

یک شیء تصویر بندانگشتی با مقیاس‌گذاری سفارشی را برمی‌گرداند.

--------------------

> ```
> The following example shows how to converting slides With notes and comments to Images.
>  
>  Presentation pres = new Presentation("PresentationNotesComments.pptx");
>  try {
>      // ایجاد گزینه‌های رندرینگ
>      IRenderingOptions options = new RenderingOptions();
>      // ایجاد گزینه‌های چینش یادداشت‌ها و نظرات
>      NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
>      // موقعیت یادداشت‌ها را در صفحه تنظیم می‌کند
>      notesCommentsLayouting.setNotesPosition(NotesPositions.BottomTruncated);
>      // موقعیت نظرات را در صفحه تنظیم می‌کند
>      notesCommentsLayouting.setCommentsPosition(CommentsPositions.Right);
>      // عرض ناحیه خروجی نظرات را تنظیم می‌کند
>      notesCommentsLayouting.setCommentsAreaWidth(500);
>      // رنگ ناحیه نظرات را تنظیم می‌کند
>      notesCommentsLayouting.setCommentsAreaColor(Color.WHITE);
>      // تنظیم گزینه‌های چینش برای رندرینگ
>      options.setSlidesLayoutOptions(notesCommentsLayouting);
>      // اسلاید اول ارائه را به یک شیء android.graphics.Bitmap تبدیل می‌کند
>      IImage image = pres.getSlides().get_Item(0).getImage(options, 2f, 2f);
>      // تصویر را در فرمت GIF ذخیره می‌کند
>      image.save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های رندرینگ. |
| scaleX | float | مقدار مقیاس این بندانگشتی در راستای محور x. |
| scaleY | float | مقدار مقیاس این بندانگشتی در راستای محور y. |

**بازگشت:**  
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.

### getImage(IRenderingOptions options, Size imageSize) {#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public final IImage getImage(IRenderingOptions options, Size imageSize)
```

یک شیء تصویر بندانگشتی با اندازه مشخص را برمی‌گرداند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های رندرینگ. |
| imageSize | [Size](../../com.aspose.slides.android/size) | اندازه تصویر برای ایجاد. |

**بازگشت:**  
[IImage](../../com.aspose.slides/iimage) - Image object.

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

محتوای اسلاید را به‌عنوان فایل SVG ذخیره می‌کند.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.svg");
>      {
>          // ذخیره اسلاید اول به عنوان فایل SVG
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

محتوای اسلاید را به‌عنوان فایل SVG ذخیره می‌کند.

--------------------

> ```
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide1.svg");
>      SVGOptions options = new SVGOptions();
>      options.setVectorizeText(true);
>      // اسلاید اول را به عنوان فایل SVG ذخیره می‌کند
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

محتوای اسلاید را به‌عنوان فایل EMF ذخیره می‌کند.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into a metafile.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.emf");
>      {
>          // اسلاید اول را به عنوان یک متافایل ذخیره می‌کند
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

طرح اسلاید برای اسلاید فعلی را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**بازگشت:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public final void setLayoutSlide(ILayoutSlide value)
```

طرح اسلاید برای اسلاید فعلی را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |

### reset() {#reset--}
```
public final void reset()
```

موقعیت، اندازه و قالب‌بندی هر شکلی که یک نمونه در LayoutSlide دارد را بازنشانی می‌کند.

### getNotesSlideManager() {#getNotesSlideManager--}
```
public final INotesSlideManager getNotesSlideManager()
```

اجازۀ دسترسی به اسلاید یادداشت‌ها، اضافه و حذف آن را می‌دهد. فقط-خواندنی [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**بازگشت:**  
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)

### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public final IComment[] getSlideComments(ICommentAuthor author)
```

تمام نظرات اسلاید اضافه‌شده توسط نویسنده خاص را برمی‌گرداند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | نویسنده نظرات برای جستجو یا null برای برگرداندن همه نظرات. |

**بازگشت:**  
com.aspose.slides.IComment[] - Array of [Comment](../../com.aspose.slides/comment).

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

بخش‌های متنی با قالب‌بندی یکسان را در تمام پاراگراف‌ها در تمام اشکال قابل قبول ترکیب می‌کند.