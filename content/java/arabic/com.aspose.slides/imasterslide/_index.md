---
title: IMasterSlide
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل شريحة رئيسية في عرض تقديمي.
type: docs
url: /ar/com.aspose.slides/imasterslide/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterSlide extends IBaseSlide, IMasterThemeable
```

يمثل شريحة رئيسية في عرض تقديمي.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | يرجع مدير HeaderFooter للشريحة الرئيسية. |
| [getTitleStyle()](#getTitleStyle--) | يرجع نمط نص العنوان. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | ينشئ شريحة رئيسية جديدة بناءً على الحالية، ويطبق سمة خارجية عليها ثم يطبق الشريحة الرئيسية التي تم إنشاؤها على جميع الشرائح التابعة. |
| [getBodyStyle()](#getBodyStyle--) | يرجع نمط نص الجسم. |
| [getOtherStyle()](#getOtherStyle--) | يرجع نمط نص آخر. |
| [getLayoutSlides()](#getLayoutSlides--) | يرجع مجموعة الشرائح التخطيطية الفرعية لهذه الشريحة الرئيسية. |
| [getPreserve()](#getPreserve--) | يحدد ما إذا كان يتم حذف الشريحة الرئيسية المقابلة عندما يتم حذف جميع الشرائح التي تلي تلك الشريحة الرئيسية. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | يحدد ما إذا كان يتم حذف الشريحة الرئيسية المقابلة عندما يتم حذف جميع الشرائح التي تلي تلك الشريحة الرئيسية. |
| [hasDependingSlides()](#hasDependingSlides--) | يرجع true إذا كان هناك شريحة واحدة على الأقل تعتمد على هذه الشريحة الرئيسية. |
| [getDependingSlides()](#getDependingSlides--) | يرجع مصفوفة تحتوي على جميع الشرائح التي تعتمد على هذه الشريحة الرئيسية. |
| [getDrawingGuides()](#getDrawingGuides--) | يرجع مجموعة من أدوات الرسم لهذه الشريحة الرئيسية. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

يرجع مدير HeaderFooter للشريحة الرئيسية. للقراءة فقط [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**الإرجاع:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### getTitleStyle() {#getTitleStyle--}
```
public abstract ITextStyle getTitleStyle()
```

يرجع نمط نص العنوان. للقراءة فقط [ITextStyle](../../com.aspose.slides/itextstyle).

**الإرجاع:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public abstract IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

ينشئ شريحة رئيسية جديدة بناءً على الحالية، ويطبق سمة خارجية عليها ثم يطبق الشريحة الرئيسية التي تم إنشاؤها على جميع الشرائح التابعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fname | java.lang.String | مسار ملف السمة الخارجي (.thmx). |

**الإرجاع:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - New themed MasterSlide.
### getBodyStyle() {#getBodyStyle--}
```
public abstract ITextStyle getBodyStyle()
```

يرجع نمط نص الجسم. للقراءة فقط [ITextStyle](../../com.aspose.slides/itextstyle).

**الإرجاع:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public abstract ITextStyle getOtherStyle()
```

يرجع نمط نص آخر. للقراءة فقط [ITextStyle](../../com.aspose.slides/itextstyle).

**الإرجاع:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IMasterLayoutSlideCollection getLayoutSlides()
```

يرجع مجموعة الشرائح التخطيطية الفرعية لهذه الشريحة الرئيسية. للقراءة فقط [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

يمكنك الوصول إلى API البديلة لإضافة/إدراج/إزالة/استنساخ الشرائح التخطيطية باستخدام الخاصية ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**الإرجاع:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public abstract boolean getPreserve()
```

يحدد ما إذا كان يتم حذف الشريحة الرئيسية المقابلة عندما يتم حذف جميع الشرائح التي تلي تلك الشريحة الرئيسية. ملاحظة: Aspose.Slides لن يزيل أي شريحة رئيسية غير مستخدمة بنفسه، لإزالة الشرائح الرئيسية غير المستخدمة فعليًا استدعِ [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) قابل للقراءة والكتابة boolean.

**الإرجاع:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public abstract void setPreserve(boolean value)
```

يحدد ما إذا كان يتم حذف الشريحة الرئيسية المقابلة عندما يتم حذف جميع الشرائح التي تلي تلك الشريحة الرئيسية. ملاحظة: Aspose.Slides لن يزيل أي شريحة رئيسية غير مستخدمة بنفسه، لإزالة الشرائح الرئيسية غير المستخدمة فعليًا استدعِ [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) قابل للقراءة والكتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

يرجع true إذا كان هناك شريحة واحدة على الأقل تعتمد على هذه الشريحة الرئيسية. للقراءة فقط boolean.

**الإرجاع:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

يرجع مصفوفة تحتوي على جميع الشرائح التي تعتمد على هذه الشريحة الرئيسية.

**الإرجاع:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide), which depend on this master slide
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

يرجع مجموعة من أدوات الرسم للشريحة الرئيسية. للقراءة فقط [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
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