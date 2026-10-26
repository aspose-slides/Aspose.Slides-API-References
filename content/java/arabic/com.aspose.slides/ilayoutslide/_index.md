---
title: ILayoutSlide
second_title: مرجع API لـ Aspose.Slides للـ Java
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

| Method | Description |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | يرجع مدير HeaderFooter لشريحة التخطيط. |
| [getPlaceholderManager()](#getPlaceholderManager--) | يرجع مدير العناصر النائبة لشريحة التخطيط. |
| [getMasterSlide()](#getMasterSlide--) | يرجع أو يحدد الشريحة الرئيسة للتخطيط. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | يرجع أو يحدد الشريحة الرئيسة للتخطيط. |
| [getLayoutType()](#getLayoutType--) | يرجع نوع التخطيط لهذه الشريحة. |
| [hasDependingSlides()](#hasDependingSlides--) | يرجع true إذا كان هناك شريحة واحدة على الأقل تعتمد على هذه الشريحة. |
| [getDependingSlides()](#getDependingSlides--) | يرجع مصفوفة بجميع الشرائح التي تعتمد على هذه الشريحة. |
| [remove()](#remove--) | يزيل التخطيط من العرض التقديمي. |
| [getDrawingGuides()](#getDrawingGuides--) | يرجع مجموعة من أدلة الرسم لشريحة التخطيط. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

يرجع مدير HeaderFooter لشريحة التخطيط. قراءة فقط [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**الإرجاع:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public abstract ILayoutPlaceholderManager getPlaceholderManager()
```

يرجع مدير العناصر النائبة لشريحة التخطيط. قراءة فقط [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**الإرجاع:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public abstract IMasterSlide getMasterSlide()
```

يرجع أو يحدد الشريحة الرئيسة للتخطيط. قراءة/كتابة [IMasterSlide](../../com.aspose.slides/imasterslide).

**الإرجاع:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public abstract void setMasterSlide(IMasterSlide value)
```

يرجع أو يحدد الشريحة الرئيسة للتخطيط. قراءة/كتابة [IMasterSlide](../../com.aspose.slides/imasterslide).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |
### getLayoutType() {#getLayoutType--}
```
public abstract byte getLayoutType()
```

يرجع نوع التخطيط لهذه الشريحة. قراءة فقط [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**الإرجاع:**
byte
### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

يرجع true إذا كان هناك شريحة واحدة على الأقل تعتمد على هذه الشريحة. قراءة فقط boolean.

**الإرجاع:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

يرجع مصفوفة بجميع الشرائح التي تعتمد على هذه الشريحة.

**الإرجاع:**
com.aspose.slides.ISlide[] - مصفوفة بجميع الشرائح التي تعتمد على هذه الشريحة
### remove() {#remove--}
```
public abstract void remove()
```

يزيل التخطيط من العرض التقديمي.

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

يرجع مجموعة من أدلة الرسم لشريحة التخطيط. قراءة فقط [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // إضافة دليل الرسم العمودي الجديد إلى يسار مركز الشريحة
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**الإرجاع:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)