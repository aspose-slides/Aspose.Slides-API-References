---
title: LayoutSlide
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل شريحة تخطيطية.
type: docs
url: /ar/com.aspose.slides/layoutslide/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**كل الواجهات المنفذة:**
[com.aspose.slides.ILayoutSlide](../../com.aspose.slides/ilayoutslide)
```
public final class LayoutSlide extends BaseSlide implements ILayoutSlide
```

يمثل شريحة تخطيطية.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | إرجاع مدير HeaderFooter للشريحة التخطيطية. |
| [getPlaceholderManager()](#getPlaceholderManager--) | إرجاع مدير العنصر النائب للشريحة التخطيطية. |
| [getMasterSlide()](#getMasterSlide--) | إرجاع أو تعيين الشريحة الرئيسية للتخطيط. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | إرجاع أو تعيين الشريحة الرئيسية للتخطيط. |
| [remove()](#remove--) | إزالة التخطيط من العرض التقديمي. |
| [getThemeManager()](#getThemeManager--) | إرجاع مدير السمة المتجاوز. |
| [getLayoutType()](#getLayoutType--) | إرجاع نوع التخطيط لهذه الشريحة التخطيطية. |
| [getDependingSlides()](#getDependingSlides--) | إرجاع مصفوفة تحتوي على جميع الشرائح التي تعتمد على هذه الشريحة التخطيطية. |
| [hasDependingSlides()](#hasDependingSlides--) | إرجاع true إذا كان هناك شريحة واحدة على الأقل تعتمد على هذه الشريحة التخطيطية. |
| [getShowMasterShapes()](#getShowMasterShapes--) | تحديد ما إذا كان يجب عرض الأشكال على الشريحة الرئيسية على الشرائح أم لا. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | تحديد ما إذا كان يجب عرض الأشكال على الشريحة الرئيسية على الشرائح أم لا. |
| [getDrawingGuides()](#getDrawingGuides--) | إرجاع مجموعة من أدلة الرسم للشريحة التخطيطية. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```


إرجاع مدير HeaderFooter للشريحة التخطيطية. للقراءة فقط [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**القيمة الراجعة:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public final ILayoutPlaceholderManager getPlaceholderManager()
```


إرجاع مدير العنصر النائب للشريحة التخطيطية. للقراءة فقط [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**القيمة الراجعة:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public final IMasterSlide getMasterSlide()
```


إرجاع أو تعيين الشريحة الرئيسية للتخطيط. قراءة/كتابة [IMasterSlide](../../com.aspose.slides/imasterslide).

**القيمة الراجعة:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public final void setMasterSlide(IMasterSlide value)
```


إرجاع أو تعيين الشريحة الرئيسية للتخطيط. قراءة/كتابة [IMasterSlide](../../com.aspose.slides/imasterslide).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |

### remove() {#remove--}
```
public final void remove()
```


إزالة التخطيط من العرض التقديمي.

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```


إرجاع مدير السمة المتجاوز. للقراءة فقط [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**القيمة الراجعة:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getLayoutType() {#getLayoutType--}
```
public final byte getLayoutType()
```


إرجاع نوع التخطيط لهذه الشريحة التخطيطية. للقراءة فقط [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**القيمة الراجعة:**
byte
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```


إرجاع مصفوفة تحتوي على جميع الشرائح التي تعتمد على هذه الشريحة التخطيطية.

**القيمة الراجعة:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```


إرجاع true إذا كان هناك شريحة واحدة على الأقل تعتمد على هذه الشريحة التخطيطية. للقراءة فقط  boolean .

**القيمة الراجعة:**
boolean
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


تحديد ما إذا كان يجب عرض الأشكال على الشريحة الرئيسية على الشرائح أم لا. قراءة/كتابة  boolean .

**القيمة الراجعة:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


تحديد ما إذا كان يجب عرض الأشكال على الشريحة الرئيسية على الشرائح أم لا. قراءة/كتابة  boolean .

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```


إرجاع مجموعة من أدلة الرسم للشريحة التخطيطية. للقراءة فقط [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

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


**القيمة الراجعة:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)