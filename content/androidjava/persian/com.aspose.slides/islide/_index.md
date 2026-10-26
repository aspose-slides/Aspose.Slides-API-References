---
title: ISlide
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر یک اسلاید در یک ارائه است.
type: docs
url: /fa/com.aspose.slides/islide/
---
**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)  
```
public interface ISlide extends IBaseSlide, IOverrideThemeable
```

نمایانگر یک اسلاید در ارائه است.

## متدها

| متد | توضیح |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | مدیر HeaderFooter اسلاید را برمی‌گرداند. |
| [getSlideNumber()](#getSlideNumber--) | شماره‌ای از اسلاید را برمی‌گرداند. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | شماره‌ای از اسلاید را برمی‌گرداند. |
| [getHidden()](#getHidden--) | تعیین می‌کند آیا اسلاید مشخص شده در طول نمایش اسلاید مخفی است یا نه. |
| [setHidden(boolean value)](#setHidden-boolean-) | تعیین می‌کند آیا اسلاید مشخص شده در طول نمایش اسلاید مخفی است یا نه. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | شی تصویر با مقیاس‌گذاری سفارشی را برمی‌گرداند. |
| [getImage()](#getImage--) | شی تصویر کوچک (۲۰٪ اندازه واقعی) را برمی‌گرداند. |
| [getImage(Size imageSize)](#getImage-com.aspose.slides.android.Size-) | شی تصویر با اندازه مشخص را برمی‌گرداند. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | شی بیت‌مپ tiff تصویر کوچک با پارامترهای مشخص را برمی‌گرداند. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | شی بیت‌مپ تصویر کوچک را برمی‌گرداند. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | شی بیت‌مپ تصویر کوچک با مقیاس‌گذاری سفارشی را برمی‌گرداند. |
| [getImage(IRenderingOptions options, Size imageSize)](#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | شی بیت‌مپ تصویر کوچک با اندازه مشخص را برمی‌گرداند. |
| [getLayoutSlide()](#getLayoutSlide--) | اسلاید طرح‌بندی را برای اسلاید جاری برمی‌گرداند یا تنظیم می‌کند. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | اسلاید طرح‌بندی را برای اسلاید جاری برمی‌گرداند یا تنظیم می‌کند. |
| [getNotesSlideManager()](#getNotesSlideManager--) | دسترسی به اسلاید یادداشت‌ها، افزودن و حذف آن را امکان‌پذیر می‌سازد. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | تمام نظرات اسلاید اضافه شده توسط نویسنده خاص را برمی‌گرداند. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | محتوای اسلاید را به‌عنوان فایل SVG ذخیره می‌کند. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | محتوای اسلاید را به‌عنوان فایل SVG ذخیره می‌کند. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | محتوای اسلاید را به‌عنوان فایل EMF ذخیره می‌کند. |
| [remove()](#remove--) | اسلاید را از ارائه حذف می‌کند. |
| [reset()](#reset--) | موقعیت، اندازه و قالب‌بندی هر شکلی که نمونه‌ای روی LayoutSlide دارد را بازنشانی می‌کند. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ISlideHeaderFooterManager getHeaderFooterManager()
```

مدیر HeaderFooter اسلاید را برمی‌گرداند. فقط‌خواندنی [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**بازگشت:**  
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)

### getSlideNumber() {#getSlideNumber--}
```
public abstract int getSlideNumber()
```

شماره‌ای از اسلاید را برمی‌گرداند. ایندکس اسلاید در مجموعه [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) همیشه برابر با SlideNumber - 1 است. قابل خواندن/نوشتن int.

**بازگشت:**  
int

### setSlideNumber(int value) {#setSlideNumber-int-}
```
public abstract void setSlideNumber(int value)
```

شماره‌ای از اسلاید را برمی‌گرداند. ایندکس اسلاید در مجموعه [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) همیشه برابر با SlideNumber - 1 است. قابل خواندن/نوشتن int.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

تعیین می‌کند آیا اسلاید مشخص شده در طول نمایش اسلاید مخفی است یا نه. قابل خواندن/نوشتن boolean.

**بازگشت:**  
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

تعیین می‌کند آیا اسلاید مشخص شده در طول نمایش اسلاید مخفی است یا نه. قابل خواندن/نوشتن boolean.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```

شی تصویر با مقیاس‌گذاری سفارشی را برمی‌گرداند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| scaleX | float | مقداری که برای مقیاس‌گذاری این Thumbnail در جهت محور x استفاده می‌شود. |
| scaleY | float | مقداری که برای مقیاس‌گذاری این Thumbnail در جهت محور y استفاده می‌شود. |

**بازگشت:**  
[IImage](../../com.aspose.slides/iimage) - شی تصویر android.graphics.Bitmap

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

شی تصویر کوچک (۲۰٪ اندازه واقعی) را برمی‌گرداند.

**بازگشت:**  
[IImage](../../com.aspose.slides/iimage) - شی تصویر android.graphics.Bitmap

### getImage(Size imageSize) {#getImage-com.aspose.slides.android.Size-}
```
public abstract IImage getImage(Size imageSize)
```

شی تصویر با اندازه مشخص را برمی‌گرداند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| imageSize | [Size](../../com.aspose.slides.android/size) | اندازه تصویر برای ایجاد. |

**بازگشت:**  
[IImage](../../com.aspose.slides/iimage) - شی Bitmap.

### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public abstract IImage getImage(ITiffOptions options)
```

شی Bitmap تصویر کوچک tiff را با پارامترهای مشخص برمی‌گرداند.

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

شی Bitmap تصویر کوچک را برمی‌گرداند.

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

شی Bitmap تصویر کوچک را با مقیاس‌گذاری سفارشی برمی‌گرداند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های رندرینگ. |
| scaleX | float | مقداری که برای مقیاس‌گذاری این Thumbnail در جهت محور x استفاده می‌شود. |
| scaleY | float | مقداری که برای مقیاس‌گذاری این Thumbnail در جهت محور y استفاده می‌شود. |

**بازگشت:**  
[IImage](../../com.aspose.slides/iimage) - شی Bitmap.

### getImage(IRenderingOptions options, Size imageSize) {#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage getImage(IRenderingOptions options, Size imageSize)
```

شی Bitmap تصویر کوچک را با اندازه مشخص برمی‌گرداند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های رندرینگ. |
| imageSize | [Size](../../com.aspose.slides.android/size) | اندازه تصویر برای ایجاد. |

**بازگشت:**  
[IImage](../../com.aspose.slides/iimage) - شی Bitmap.

### getLayoutSlide() {#getLayoutSlide--}
```
public abstract ILayoutSlide getLayoutSlide()
```

اسلاید طرح‌بندی را برای اسلاید جاری برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**بازگشت:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public abstract void setLayoutSlide(ILayoutSlide value)
```

اسلاید طرح‌بندی را برای اسلاید جاری برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |

### getNotesSlideManager() {#getNotesSlideManager--}
```
public abstract INotesSlideManager getNotesSlideManager()
```

دسترسی به اسلاید یادداشت‌ها را فراهم می‌کند، اضافه و حذف می‌کند. فقط‌خواندنی [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

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
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | نویسنده نظرات برای جستجو یا null برای برگرداندن تمام نظرات. |

**بازگشت:**  
com.aspose.slides.IComment[] - آرایه‌ای از [IComment](../../com.aspose.slides/icomment).

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

محتویات اسلاید را به‌عنوان فایل SVG ذخیره می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان هدف |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

محتویات اسلاید را به‌عنوان فایل SVG ذخیره می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان هدف |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | گزینه‌های تولید SVG |

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```

محتویات اسلاید را به‌عنوان فایل EMF ذخیره می‌کند.

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

موقعیت، اندازه و قالب‌بندی هر شکلی که نمونه‌ای روی LayoutSlide دارد را بازنشانی می‌کند.