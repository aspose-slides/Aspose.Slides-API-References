---
title: ISlide
second_title: مرجع API Aspose.Slides برای Java
description: یک اسلاید را در یک ارائه نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/islide/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ISlide extends IBaseSlide, IOverrideThemeable
```

یک اسلاید در یک ارائه را نمایندگی می‌کند.
## متدها

| متد | توضیح |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | مدیر HeaderFooter اسلاید را برمی‌گرداند. |
| [getSlideNumber()](#getSlideNumber--) | شماره اسلاید را برمی‌گرداند. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | شماره اسلاید را برمی‌گرداند. |
| [getHidden()](#getHidden--) | تعیین می‌کند که آیا اسلاید مشخص شده در نمایش اسلایدها مخفی است یا نه. |
| [setHidden(boolean value)](#setHidden-boolean-) | تعیین می‌کند که آیا اسلاید مشخص شده در نمایش اسلایدها مخفی است یا نه. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | شی تصویر با مقیاس سفارشی را برمی‌گرداند. |
| [getImage()](#getImage--) | شی تصویر Thumbnail (۲۰٪ از اندازه واقعی) را برمی‌گرداند. |
| [getImage(Dimension imageSize)](#getImage-java.awt.Dimension-) | شی تصویر با اندازه مشخص شده را برمی‌گرداند. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | شی bitmap تِیف Thumbnail با پارامترهای مشخص را برمی‌گرداند. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | شی Bitmap Thumbnail را برمی‌گرداند. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | شی Bitmap Thumbnail با مقیاس سفارشی را برمی‌گرداند. |
| [getImage(IRenderingOptions options, Dimension imageSize)](#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | شی Bitmap Thumbnail با اندازه مشخص را برمی‌گرداند. |
| [getLayoutSlide()](#getLayoutSlide--) | اسلاید layout را برای اسلاید جاری برمی‌گرداند یا تنظیم می‌کند. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | اسلاید layout را برای اسلاید جاری برمی‌گرداند یا تنظیم می‌کند. |
| [getNotesSlideManager()](#getNotesSlideManager--) | دسترسی به اسلاید یادداشت‌ها را فراهم می‌کند، اضافه و حذف می‌کند. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | تمام نظرات اسلاید اضافه شده توسط نویسنده خاص را برمی‌گرداند. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | محتوای اسلاید را به عنوان فایل SVG ذخیره می‌کند. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | محتوای اسلاید را به عنوان فایل SVG ذخیره می‌کند. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | محتوای اسلاید را به عنوان فایل EMF ذخیره می‌کند. |
| [remove()](#remove--) | اسلاید را از ارائه حذف می‌کند. |
| [reset()](#reset--) | موقعیت، اندازه و قالب‌بندی هر شکلی که پروتوتایپ بر LayoutSlide دارد را بازنشانی می‌کند. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ISlideHeaderFooterManager getHeaderFooterManager()
```

مدیر HeaderFooter اسلاید را برمی‌گرداند. فقط-خواندنی [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**بازگشت:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)
### getSlideNumber() {#getSlideNumber--}
```
public abstract int getSlideNumber()
```

شماره اسلاید را برمی‌گرداند. شاخص اسلاید در مجموعه [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) همیشه برابر با SlideNumber - 1 است. خواندنی/قابل نوشتن int.

**بازگشت:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public abstract void setSlideNumber(int value)
```

شماره اسلاید را برمی‌گرداند. شاخص اسلاید در مجموعه [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) همیشه برابر با SlideNumber - 1 است. خواندنی/قابل نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

تعیین می‌کند که آیا اسلاید مشخص شده در نمایش اسلایدها مخفی است یا نه. خواندنی/قابل نوشتن boolean.

**بازگشت:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

تعیین می‌کند که آیا اسلاید مشخص شده در نمایش اسلایدها مخفی است یا نه. خواندنی/قابل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```

شی تصویر با مقیاس سفارشی را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| scaleX | float | مقداری که برای مقیاس این Thumbnail در جهت محور x استفاده می‌شود. |
| scaleY | float | مقداری که برای مقیاس این Thumbnail در جهت محور y استفاده می‌شود. |

**بازگشت:**
[IImage](../../com.aspose.slides/iimage) - شی Image java.awt.image.BufferedImage
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

شی تصویر Thumbnail (۲۰٪ از اندازه واقعی) را برمی‌گرداند.

**بازگشت:**
[IImage](../../com.aspose.slides/iimage) - شی Image java.awt.image.BufferedImage
### getImage(Dimension imageSize) {#getImage-java.awt.Dimension-}
```
public abstract IImage getImage(Dimension imageSize)
```

شی تصویر با اندازه مشخص شده را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| imageSize | java.awt.Dimension | اندازه تصویر برای ایجاد. |

**بازگشت:**
[IImage](../../com.aspose.slides/iimage) - شی Bitmap.
### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public abstract IImage getImage(ITiffOptions options)
```

شی bitmap تِیف Thumbnail با پارامترهای مشخص را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | گزینه‌های Tiff. |

**بازگشت:**
[IImage](../../com.aspose.slides/iimage) - شی Image.
### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage getImage(IRenderingOptions options)
```

شی Bitmap Thumbnail را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های رندرینگ. |

**بازگشت:**
[IImage](../../com.aspose.slides/iimage) - شی Bitmap.
### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

شی Bitmap Thumbnail با مقیاس سفارشی را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های رندرینگ. |
| scaleX | float | مقداری که برای مقیاس این Thumbnail در جهت محور x استفاده می‌شود. |
| scaleY | float | مقداری که برای مقیاس این Thumbnail در جهت محور y استفاده می‌شود. |

**بازگشت:**
[IImage](../../com.aspose.slides/iimage) - شی Bitmap.
### getImage(IRenderingOptions options, Dimension imageSize) {#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage getImage(IRenderingOptions options, Dimension imageSize)
```

شی Bitmap Thumbnail با اندازه مشخص را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های رندرینگ. |
| imageSize | java.awt.Dimension | اندازه تصویر برای ایجاد. |

**بازگشت:**
[IImage](../../com.aspose.slides/iimage) - شی Bitmap.
### getLayoutSlide() {#getLayoutSlide--}
```
public abstract ILayoutSlide getLayoutSlide()
```

اسلاید layout را برای اسلاید جاری برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**بازگشت:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public abstract void setLayoutSlide(ILayoutSlide value)
```

اسلاید layout را برای اسلاید جاری برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |
### getNotesSlideManager() {#getNotesSlideManager--}
```
public abstract INotesSlideManager getNotesSlideManager()
```

دسترسی به اسلاید یادداشت‌ها را فراهم می‌کند، اضافه و حذف می‌کند. فقط-خواندنی [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**بازگشت:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public abstract IComment[] getSlideComments(ICommentAuthor author)
```

تمام نظرات اسلاید اضافه شده توسط نویسنده خاص را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | نویسنده نظرات برای جستجو یا null برای برگرداندن همه نظرات. |

**بازگشت:**
com.aspose.slides.IComment[] - آرایه‌ای از [IComment](../../com.aspose.slides/icomment).
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

محتوای اسلاید را به عنوان فایل SVG ذخیره می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان هدف |
### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

محتوای اسلاید را به عنوان فایل SVG ذخیره می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان هدف |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | گزینه‌های تولید SVG |
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```

محتوای اسلاید را به عنوان فایل EMF ذخیره می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان هدف |
### remove() {#remove--}
```
public abstract void remove()
```

اسلاید را از ارائه حذف می‌کند.
### reset() {#reset--}
```
public abstract void reset()
```

موقعیت، اندازه و قالب‌بندی هر شکلی که پروتوتایپ بر LayoutSlide دارد را بازنشانی می‌کند.