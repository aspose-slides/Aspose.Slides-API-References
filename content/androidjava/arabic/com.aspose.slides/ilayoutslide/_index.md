---
title: ILayoutSlide
second_title: Aspose.Slides لنظام Android عبر مرجع Java API
description: يمثل شريحة تخطيط.
type: docs
url: /ar/com.aspose.slides/ilayoutslide/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ILayoutSlide extends IBaseSlide, IOverrideThemeable
```

يمثل شريحة تخطيط.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | يرجع مدير HeaderFooter للشريحة التخطيطية. |
| [getPlaceholderManager()](#getPlaceholderManager--) | يرجع مدير العنصر النائب للشريحة التخطيطية. |
| [getMasterSlide()](#getMasterSlide--) | يرجع أو يعيّن الشريحة الرئيسة لتخطيط. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | يرجع أو يعيّن الشريحة الرئيسة لتخطيط. |
| [getLayoutType()](#getLayoutType--) | يرجع نوع التخطيط لهذه الشريحة التخطيطية. |
| [hasDependingSlides()](#hasDependingSlides--) | يرجع true إذا كان هناك شريحة واحدة على الأقل تعتمد على هذه الشريحة التخطيطية. |
| [getDependingSlides()](#getDependingSlides--) | يرجع مصفوفة تحتوي على جميع الشرائح التي تعتمد على هذه الشريحة التخطيطية. |
| [remove()](#remove--) | يزيل التخطيط من العرض. |
| [getDrawingGuides()](#getDrawingGuides--) | يرجع مجموعة من أدوات الرسم للشريحة التخطيطية. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

يرجع مدير HeaderFooter للشريحة التخطيطية. قراءة فقط [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**الإرجاع:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public abstract ILayoutPlaceholderManager getPlaceholderManager()
```

يرجع مدير العنصر النائب للشريحة التخطيطية. قراءة فقط [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**الإرجاع:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public abstract IMasterSlide getMasterSlide()
```

يرجع أو يعيّن الشريحة الرئيسة لتخطيط. قراءة/كتابة [IMasterSlide](../../com.aspose.slides/imasterslide).

**الإرجاع:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public abstract void setMasterSlide(IMasterSlide value)
```

يرجع أو يعيّن الشريحة الرئيسة لتخطيط. قراءة/كتابة [IMasterSlide](../../com.aspose.slides/imasterslide).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |
### getLayoutType() {#getLayoutType--}
```
public abstract byte getLayoutType()
```

يرجع نوع التخطيط لهذه الشريحة التخطيطية. قراءة فقط [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**الإرجاع:**
byte
### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

يرجع true إذا كان هناك شريحة واحدة على الأقل تعتمد على هذه الشريحة التخطيطية. قراءة فقط boolean.

**الإرجاع:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

يرجع مصفوفة تحتوي على جميع الشرائح التي تعتمد على هذه الشريحة التخطيطية.

**الإرجاع:**
com.aspose.slides.ISlide[] - مصفوفة تحتوي على جميع الشرائح التي تعتمد على هذه الشريحة التخطيطية
### remove() {#remove--}
```
public abstract void remove()
```

يزيل التخطيط من العرض.

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

يرجع مجموعة من أدوات الرسم للشريحة التخطيطية. قراءة فقط [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // إضافة دليل الرسم العمودي الجديد إلى يسار مركز الشريحة
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**الإرجاع:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)