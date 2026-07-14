---
title: LayoutSlide
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل شريحة تخطيطية.
type: docs
url: /ar/com.aspose.slides/layoutslide/
---
**الوراثة:**  
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**جميع الواجهات المُنفذة:**  
[com.aspose.slides.ILayoutSlide](../../com.aspose.slides/ilayoutslide)  
```
public final class LayoutSlide extends BaseSlide implements ILayoutSlide
```

يمثل شريحة تخطيطية.  
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | يعيد مدير HeaderFooter للشريحة التخطيطية. |
| [getPlaceholderManager()](#getPlaceholderManager--) | يعيد مدير العنصر النائب للشريحة التخطيطية. |
| [getMasterSlide()](#getMasterSlide--) | يعيد أو يعيّن الشريحة الرئيسية للتخطيط. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | يعيد أو يعيّن الشريحة الرئيسية للتخطيط. |
| [remove()](#remove--) | يزيل التخطيط من العرض التقديمي. |
| [getThemeManager()](#getThemeManager--) | يعيد مدير السمة المتجاوزة. |
| [getLayoutType()](#getLayoutType--) | يعيد نوع التخطيط لهذه الشريحة التخطيطية. |
| [getDependingSlides()](#getDependingSlides--) | يعيد مصفوفة تحتوي على جميع الشرائح التي تعتمد على هذه الشريحة التخطيطية. |
| [hasDependingSlides()](#hasDependingSlides--) | يعيد true إذا كان هناك شريحة واحدة على الأقل تعتمد على هذه الشريحة التخطيطية. |
| [getShowMasterShapes()](#getShowMasterShapes--) | يحدد ما إذا كان يجب إظهار الأشكال على الشريحة الرئيسية في الشرائح أم لا. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | يحدد ما إذا كان يجب إظهار الأشكال على الشريحة الرئيسية في الشرائح أم لا. |
| [getDrawingGuides()](#getDrawingGuides--) | يعيد مجموعة من أدلة الرسم للشريحة التخطيطية. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

يعيد مدير HeaderFooter للشريحة التخطيطية. قراءة فقط [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**الإرجاع:**  
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)

### getPlaceholderManager() {#getPlaceholderManager--}
```
public final ILayoutPlaceholderManager getPlaceholderManager()
```

يعيد مدير العنصر النائب للشريحة التخطيطية. قراءة فقط [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**الإرجاع:**  
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)

### getMasterSlide() {#getMasterSlide--}
```
public final IMasterSlide getMasterSlide()
```

يعيد أو يعيّن الشريحة الرئيسية للتخطيط. قراءة/كتابة [IMasterSlide](../../com.aspose.slides/imasterslide).

**الإرجاع:**  
[IMasterSlide](../../com.aspose.slides/imasterslide)

### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public final void setMasterSlide(IMasterSlide value)
```

يعيد أو يعيّن الشريحة الرئيسية للتخطيط. قراءة/كتابة [IMasterSlide](../../com.aspose.slides/imasterslide).

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |

### remove() {#remove--}
```
public final void remove()
```

يزيل التخطيط من العرض التقديمي.

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

يعيد مدير السمة المتجاوزة. قراءة فقط [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**الإرجاع:**  
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)

### getLayoutType() {#getLayoutType--}
```
public final byte getLayoutType()
```

يعيد نوع التخطيط لهذه الشريحة التخطيطية. قراءة فقط [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**الإرجاع:**  
byte

### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

يعيد مصفوفة تحتوي على جميع الشرائح التي تعتمد على هذه الشريحة التخطيطية.

**الإرجاع:**  
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)

### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

يعيد true إذا كان هناك شريحة واحدة على الأقل تعتمد على هذه الشريحة التخطيطية. قراءة فقط boolean .

**الإرجاع:**  
boolean

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

يحدد ما إذا كان يجب إظهار الأشكال على الشريحة الرئيسية في الشرائح أم لا. قراءة/كتابة boolean .

**الإرجاع:**  
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

يحدد ما إذا كان يجب إظهار الأشكال على الشريحة الرئيسية في الشرائح أم لا. قراءة/كتابة boolean .

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

يعيد مجموعة من أدلة الرسم للشريحة التخطيطية. قراءة فقط [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
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