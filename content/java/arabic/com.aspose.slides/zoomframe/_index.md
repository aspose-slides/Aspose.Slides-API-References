---
title: ZoomFrame
second_title: مرجع API Aspose.Slides للغة Java
description: يمثل كائن Slide Zoom في شريحة.
type: docs
url: /ar/com.aspose.slides/zoomframe/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IZoomFrame](../../com.aspose.slides/izoomframe)
```
public class ZoomFrame extends ZoomObject implements IZoomFrame
```

يمثل كائن Slide Zoom في شريحة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | يحصل أو يضبط كائن الشريحة الذي يرتبط به كائن Slide Zoom. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | يحصل أو يضبط كائن الشريحة الذي يرتبط به كائن Slide Zoom. |
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

يحصل أو يضبط كائن الشريحة الذي يرتبط به كائن Slide Zoom. قراءة/كتابة [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> المثال التالي يوضح تغيير الشريحة المستهدفة وإنشاء صورة جديدة لكائن Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
```

**الإرجاع:**
[ISlide](../../com.aspose.slides/islide)
### setTargetSlide(ISlide value) {#setTargetSlide-com.aspose.slides.ISlide-}
```
public final void setTargetSlide(ISlide value)
```

يحصل أو يضبط كائن الشريحة الذي يرتبط به كائن Slide Zoom. قراءة/كتابة [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> المثال التالي يوضح تغيير الشريحة المستهدفة وإنشاء صورة جديدة لكائن Slide Zoom:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |