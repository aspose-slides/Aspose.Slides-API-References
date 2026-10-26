---
title: ISlide
second_title: Aspose.Slides لنظام Android عبر مرجع API Java
description: يمثل شريحة في عرض تقديمي.
type: docs
url: /ar/com.aspose.slides/islide/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ISlide extends IBaseSlide, IOverrideThemeable
```

يمثل شريحة في عرض تقديمي.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | يعيد مدير HeaderFooter للشريحة. |
| [getSlideNumber()](#getSlideNumber--) | يعيد رقم الشريحة. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | يعيد رقم الشريحة. |
| [getHidden()](#getHidden--) | يحدد ما إذا كانت الشريحة المحددة مخفية أثناء عرض الشرائح. |
| [setHidden(boolean value)](#setHidden-boolean-) | يحدد ما إذا كانت الشريحة المحددة مخفية أثناء عرض الشرائح. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | يعيد كائن صورة مع مقياس مخصص. |
| [getImage()](#getImage--) | يعيد كائن صورة مصغرة (20% من الحجم الحقيقي). |
| [getImage(Size imageSize)](#getImage-com.aspose.slides.android.Size-) | يعيد كائن صورة بالحجم المحدد. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | يعيد كائن tiff مصغّر مع المعلمات المحددة. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | يعيد كائن Bitmap مصغر. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | يعيد كائن Bitmap مصغر مع مقياس مخصص. |
| [getImage(IRenderingOptions options, Size imageSize)](#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | يعيد كائن Bitmap مصغر بالحجم المحدد. |
| [getLayoutSlide()](#getLayoutSlide--) | يعيد أو يضبط شريحة التخطيط للشريحة الحالية. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | يعيد أو يضبط شريحة التخطيط للشريحة الحالية. |
| [getNotesSlideManager()](#getNotesSlideManager--) | يسمح بالوصول إلى شريحة الملاحظات، وإضافة وإزالتها. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | يعيد جميع تعليقات الشريحة التي أضافها مؤلف معين. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | يحفظ محتوى الشريحة كملف SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | يحفظ محتوى الشريحة كملف SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | يحفظ محتوى الشريحة كملف EMF. |
| [remove()](#remove--) | يزيل الشريحة من العرض التقديمي. |
| [reset()](#reset--) | يعيد تعيين الموقع والحجم والتنسيق لكل شكل يحتوي على نموذج أولي في LayoutSlide. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ISlideHeaderFooterManager getHeaderFooterManager()
```

يعيد مدير HeaderFooter للشريحة. قراءة فقط [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**القيمة المرتجعة:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)
### getSlideNumber() {#getSlideNumber--}
```
public abstract int getSlideNumber()
```

يعيد رقم الشريحة. فهرس الشريحة في مجموعة [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) يساوي دائمًا SlideNumber - 1. قراءة/كتابة int.

**القيمة المرتجعة:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public abstract void setSlideNumber(int value)
```

يعيد رقم الشريحة. فهرس الشريحة في مجموعة [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) يساوي دائمًا SlideNumber - 1. قراءة/كتابة int.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

يحدد ما إذا كانت الشريحة المحددة مخفية أثناء عرض الشرائح. قراءة/كتابة boolean.

**القيمة المرتجعة:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

يحدد ما إذا كانت الشريحة المحددة مخفية أثناء عرض الشرائح. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```

يعيد كائن صورة مع مقياس مخصص.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| scaleX | float | القيمة التي يتم بها تحجيم هذه الصورة المصغرة في اتجاه المحور x. |
| scaleY | float | القيمة التي يتم بها تحجيم هذه الصورة المصغرة في اتجاه المحور y. |

**القيمة المرتجعة:**
[IImage](../../com.aspose.slides/iimage) - Image object android.graphics.Bitmap
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

يعيد كائن صورة مصغرة (20% من الحجم الحقيقي).

**القيمة المرتجعة:**
[IImage](../../com.aspose.slides/iimage) - Image object android.graphics.Bitmap
### getImage(Size imageSize) {#getImage-com.aspose.slides.android.Size-}
```
public abstract IImage getImage(Size imageSize)
```

يعيد كائن صورة بالحجم المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| imageSize | [Size](../../com.aspose.slides.android/size) | حجم الصورة التي سيتم إنشاؤها. |

**القيمة المرتجعة:**
[IImage](../../com.aspose.slides/iimage) - Bitmap object.
### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public abstract IImage getImage(ITiffOptions options)
```

يعيد كائن tiff مصغّر مع المعلمات المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | خيارات Tiff. |

**القيمة المرتجعة:**
[IImage](../../com.aspose.slides/iimage) - Image object.
### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage getImage(IRenderingOptions options)
```

يعيد كائن Bitmap مصغر.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات الرسم. |

**القيمة المرتجعة:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

يعيد كائن Bitmap مصغر مع مقياس مخصص.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات الرسم. |
| scaleX | float | القيمة التي يتم بها تحجيم هذه الصورة المصغرة في اتجاه المحور x. |
| scaleY | float | القيمة التي يتم بها تحجيم هذه الصورة المصغرة في اتجاه المحور y. |

**القيمة المرتجعة:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getImage(IRenderingOptions options, Size imageSize) {#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage getImage(IRenderingOptions options, Size imageSize)
```

يعيد كائن Bitmap مصغر بالحجم المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات الرسم. |
| imageSize | [Size](../../com.aspose.slides.android/size) | حجم الصورة التي سيتم إنشاؤها. |

**القيمة المرتجعة:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getLayoutSlide() {#getLayoutSlide--}
```
public abstract ILayoutSlide getLayoutSlide()
```

يعيد أو يضبط شريحة التخطيط للشريحة الحالية. قراءة/كتابة [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**القيمة المرتجعة:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public abstract void setLayoutSlide(ILayoutSlide value)
```

يعيد أو يضبط شريحة التخطيط للشريحة الحالية. قراءة/كتابة [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |
### getNotesSlideManager() {#getNotesSlideManager--}
```
public abstract INotesSlideManager getNotesSlideManager()
```

يسمح بالوصول إلى شريحة الملاحظات، وإضافة وإزالتها. قراءة فقط [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**القيمة المرتجعة:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public abstract IComment[] getSlideComments(ICommentAuthor author)
```

يعيد جميع تعليقات الشريحة التي أضافها مؤلف معين.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | مؤلف التعليقات للبحث عنه أو null لإرجاع جميع التعليقات. |

**القيمة المرتجعة:**
com.aspose.slides.IComment[] - مصفوفة من [IComment](../../com.aspose.slides/icomment).
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

يحفظ محتوى الشريحة كملف SVG.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | دفق الهدف |
### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

يحفظ محتوى الشريحة كملف SVG.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | دفق الهدف |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | خيارات توليد SVG |
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```

يحفظ محتوى الشريحة كملف EMF.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | دفق الهدف |
### remove() {#remove--}
```
public abstract void remove()
```

يزيل الشريحة من العرض التقديمي.
### reset() {#reset--}
```
public abstract void reset()
```

يعيد تعيين الموقع والحجم والتنسيق لكل شكل يحتوي على نموذج أولي في LayoutSlide.