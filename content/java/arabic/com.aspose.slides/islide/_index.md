---
title: ISlide
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل شريحة في عرض تقديمي.
type: docs
url: /ar/com.aspose.slides/islide/
---
**جميع الواجهات المُطبقة:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ISlide extends IBaseSlide, IOverrideThemeable
```

يمثل شريحة في عرض تقديمي.
## الطرق

| Method | Description |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | إرجاع مدير HeaderFooter للشريحة. |
| [getSlideNumber()](#getSlideNumber--) | إرجاع رقم الشريحة. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | إرجاع رقم الشريحة. |
| [getHidden()](#getHidden--) | تحديد ما إذا كانت الشريحة المحددة مخفية أثناء عرض الشرائح. |
| [setHidden(boolean value)](#setHidden-boolean-) | تحديد ما إذا كانت الشريحة المحددة مخفية أثناء عرض الشرائح. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | إرجاع كائن صورة مع قياس مخصص. |
| [getImage()](#getImage--) | إرجاع كائن صورة مُصغَّرة (20% من الحجم الحقيقي). |
| [getImage(Dimension imageSize)](#getImage-java.awt.Dimension-) | إرجاع كائن صورة بالحجم المحدد. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | إرجاع كائن بتخطيط tiff مصغّر مع معلمات محددة. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | إرجاع كائن بتخطيط مصغّر. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | إرجاع كائن بتخطيط مصغّر مع قياس مخصص. |
| [getImage(IRenderingOptions options, Dimension imageSize)](#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | إرجاع كائن بتخطيط مصغّر بالحجم المحدد. |
| [getLayoutSlide()](#getLayoutSlide--) | إرجاع أو تعيين شريحة التخطيط للشريحة الحالية. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | إرجاع أو تعيين شريحة التخطيط للشريحة الحالية. |
| [getNotesSlideManager()](#getNotesSlideManager--) | السماح بالوصول إلى شريحة الملاحظات، وإضافتها وإزالتها. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | إرجاع جميع تعليقات الشريحة المضافة بواسطة مؤلف محدد. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | حفظ محتوى الشريحة كملف SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | حفظ محتوى الشريحة كملف SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | حفظ محتوى الشريحة كملف EMF. |
| [remove()](#remove--) | إزالة الشريحة من العرض التقديمي. |
| [reset()](#reset--) | إعادة تعيين الموقع والحجم والتنسيق لكل شكل لديه نموذج على LayoutSlide. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ISlideHeaderFooterManager getHeaderFooterManager()
```

إرجاع مدير HeaderFooter للشريحة. للقراءة فقط [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**الإرجاع:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)

### getSlideNumber() {#getSlideNumber--}
```
public abstract int getSlideNumber()
```

إرجاع رقم الشريحة. مؤشر الشريحة في مجموعة [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) يكون دائمًا مساويًا لـ SlideNumber - 1. قراءة/كتابة int.

**الإرجاع:**
int

### setSlideNumber(int value) {#setSlideNumber-int-}
```
public abstract void setSlideNumber(int value)
```

إرجاع رقم الشريحة. مؤشر الشريحة في مجموعة [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) يكون دائمًا مساويًا لـ SlideNumber - 1. قراءة/كتابة int.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

تحديد ما إذا كانت الشريحة المحددة مخفية أثناء عرض الشرائح. قراءة/كتابة boolean.

**الإرجاع:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

تحديد ما إذا كانت الشريحة المحددة مخفية أثناء عرض الشرائح. قراءة/كتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```

إرجاع كائن صورة مع قياس مخصص.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| scaleX | float | القيمة التي يتم منها تحجيم هذا المصغّر في اتجاه المحور x. |
| scaleY | float | القيمة التي يتم منها تحجيم هذا المصغّر في اتجاه المحور y. |

**الإرجاع:**
[IImage](../../com.aspose.slides/iimage) - Image object java.awt.image.BufferedImage

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

إرجاع كائن صورة مصغّرة (20% من الحجم الحقيقي).

**الإرجاع:**
[IImage](../../com.aspose.slides/iimage) - Image object java.awt.image.BufferedImage

### getImage(Dimension imageSize) {#getImage-java.awt.Dimension-}
```
public abstract IImage getImage(Dimension imageSize)
```

إرجاع كائن صورة بالحجم المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| imageSize | java.awt.Dimension | حجم الصورة التي سيتم إنشاؤها. |

**الإرجاع:**
[IImage](../../com.aspose.slides/iimage) - Bitmap object.

### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public abstract IImage getImage(ITiffOptions options)
```

إرجاع كائن بتخطيط tiff مصغّر مع معلمات محددة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | خيارات Tiff. |

**الإرجاع:**
[IImage](../../com.aspose.slides/iimage) - Image object.

### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage getImage(IRenderingOptions options)
```

إرجاع كائن بتخطيط مصغّر.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات العرض. |

**الإرجاع:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.

### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

إرجاع كائن بتخطيط مصغّر مع قياس مخصص.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات العرض. |
| scaleX | float | القيمة التي يتم منها تحجيم هذا المصغّر في اتجاه المحور x. |
| scaleY | float | القيمة التي يتم منها تحجيم هذا المصغّر في اتجاه المحور y. |

**الإرجاع:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.

### getImage(IRenderingOptions options, Dimension imageSize) {#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage getImage(IRenderingOptions options, Dimension imageSize)
```

إرجاع كائن بتخطيط مصغّر بالحجم المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات العرض. |
| imageSize | java.awt.Dimension | حجم الصورة التي سيتم إنشاؤها. |

**الإرجاع:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.

### getLayoutSlide() {#getLayoutSlide--}
```
public abstract ILayoutSlide getLayoutSlide()
```

إرجاع أو تعيين شريحة التخطيط للشريحة الحالية. قراءة/كتابة [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**الإرجاع:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public abstract void setLayoutSlide(ILayoutSlide value)
```

إرجاع أو تعيين شريحة التخطيط للشريحة الحالية. قراءة/كتابة [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |

### getNotesSlideManager() {#getNotesSlideManager--}
```
public abstract INotesSlideManager getNotesSlideManager()
```

السماح بالوصول إلى شريحة الملاحظات، وإضافتها وإزالتها. للقراءة فقط [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**الإرجاع:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)

### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public abstract IComment[] getSlideComments(ICommentAuthor author)
```

إرجاع جميع تعليقات الشريحة المضافة بواسطة مؤلف معين.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | مؤلف التعليقات للبحث عنها أو null لإرجاع جميع التعليقات. |

**الإرجاع:**
com.aspose.slides.IComment[] - Array of [IComment](../../com.aspose.slides/icomment).

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

حفظ محتوى الشريحة كملف SVG.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | دفق الهدف |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

حفظ محتوى الشريحة كملف SVG.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | دفق الهدف |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | خيارات توليد SVG |

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```

حفظ محتوى الشريحة كملف EMF.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | دفق الهدف |

### remove() {#remove--}
```
public abstract void remove()
```

إزالة الشريحة من العرض التقديمي.

### reset() {#reset--}
```
public abstract void reset()
```

إعادة تعيين الموقع والحجم والتنسيق لكل شكل لديه نموذج على LayoutSlide.