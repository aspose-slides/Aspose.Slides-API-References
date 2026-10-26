---
title: IMasterSlide
second_title: Aspose.Slides للأندرويد عبر مرجع API جافا
description: يمثل شريحة رئيسية في عرض تقديمي.
type: docs
url: /ar/com.aspose.slides/imasterslide/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterSlide extends IBaseSlide, IMasterThemeable
```

يمثل شريحة رئيسية في عرض تقديمي.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | يرد مدير HeaderFooter الخاص بالشريحة الرئيسية. |
| [getTitleStyle()](#getTitleStyle--) | يرد نمط نص العنوان. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | ينشئ شريحة رئيسية جديدة استنادًا إلى الحالية، ويطبق موضوعًا خارجيًا عليها ثم يطبق الشريحة الرئيسية المنشأة على جميع الشرائح التابعة. |
| [getBodyStyle()](#getBodyStyle--) | يرد نمط نص الجسم. |
| [getOtherStyle()](#getOtherStyle--) | يرد نمط نص آخر. |
| [getLayoutSlides()](#getLayoutSlides--) | يرد مجموعة الشرائح التخطيطية الفرعية لهذه الشريحة الرئيسية. |
| [getPreserve()](#getPreserve--) | يحدد ما إذا كان سيتم حذف الشريحة الرئيسية المقابلة عندما يتم حذف جميع الشرائح التي تتبع تلك الشريحة الرئيسية. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | يحدد ما إذا كان سيتم حذف الشريحة الرئيسية المقابلة عندما يتم حذف جميع الشرائح التي تتبع تلك الشريحة الرئيسية. |
| [hasDependingSlides()](#hasDependingSlides--) | يرد true إذا كان هناك شريحة واحدة على الأقل تعتمد على هذه الشريحة الرئيسية. |
| [getDependingSlides()](#getDependingSlides--) | يرد مصفوفة تحتوي على جميع الشرائح التي تعتمد على هذه الشريحة الرئيسية. |
| [getDrawingGuides()](#getDrawingGuides--) | يرد مجموعة من أدلة الرسم للشريحة الرئيسية. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

يرجع مدير HeaderFooter الخاص بالشريحة الرئيسية. قراءة فقط [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**الإرجاع:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### getTitleStyle() {#getTitleStyle--}
```
public abstract ITextStyle getTitleStyle()
```

يرجع نمط نص العنوان. قراءة فقط [ITextStyle](../../com.aspose.slides/itextstyle).

**الإرجاع:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public abstract IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

ينشئ شريحة رئيسية جديدة استنادًا إلى الحالية، ويطبق موضوعًا خارجيًا عليها ثم يطبق الشريحة الرئيسية المنشأة على جميع الشرائح التابعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fname | java.lang.String | المسار إلى ملف الموضوع الخارجي (.thmx). |

**الإرجاع:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - MasterSlide بموضوع جديد.
### getBodyStyle() {#getBodyStyle--}
```
public abstract ITextStyle getBodyStyle()
```

يرجع نمط نص الجسم. قراءة فقط [ITextStyle](../../com.aspose.slides/itextstyle).

**الإرجاع:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public abstract ITextStyle getOtherStyle()
```

يرجع نمط نص آخر. قراءة فقط [ITextStyle](../../com.aspose.slides/itextstyle).

**الإرجاع:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IMasterLayoutSlideCollection getLayoutSlides()
```

يرجع مجموعة الشرائح التخطيطية الفرعية لهذه الشريحة الرئيسية. قراءة فقط [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

يمكنك الوصول إلى واجهة برمجة تطبيقات بديلة لإضافة/إدراج/إزالة/استنساخ شرائح التخطيط باستخدام الخاصية ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**الإرجاع:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public abstract boolean getPreserve()
```

يحدد ما إذا كان سيتم حذف الشريحة الرئيسية المقابلة عندما يتم حذف جميع الشرائح التي تتبع تلك الشريحة الرئيسية. ملاحظة: Aspose.Slides لن يقوم أبداً بإزالة أي شريحة رئيسية غير مستخدمة بنفسه؛ لإزالة الشرائح الرئيسية غير المستخدمة فعليًا استدعِ [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public abstract void setPreserve(boolean value)
```

يحدد ما إذا كان سيتم حذف الشريحة الرئيسية المقابلة عندما يتم حذف جميع الشرائح التي تتبع تلك الشريحة الرئيسية. ملاحظة: Aspose.Slides لن يقوم أبداً بإزالة أي شريحة رئيسية غير مستخدمة بنفسه؛ لإزالة الشرائح الرئيسية غير المستخدمة فعليًا استدعِ [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

يرجع true إذا كان هناك شريحة واحدة على الأقل تعتمد على هذه الشريحة الرئيسية. قراءة فقط boolean.

**الإرجاع:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

يرجع مصفوفة تحتوي على جميع الشرائح التي تعتمد على هذه الشريحة الرئيسية.

**الإرجاع:**
com.aspose.slides.ISlide[] - مصفوفة من [ISlide](../../com.aspose.slides/islide)، التي تعتمد على هذه الشريحة الرئيسية
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

يرجع مجموعة من أدلة الرسم للشريحة الرئيسية. قراءة فقط [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // إضافة دليل الرسم العمودي الجديد إلى يمين مركز الشريحة
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**الإرجاع:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)