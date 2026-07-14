---
title: IZoomFrame
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل كائن Slide Zoom في شريحة.
type: docs
url: /ar/com.aspose.slides/izoomframe/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface IZoomFrame extends IZoomObject
```

يمثل كائن Slide Zoom في شريحة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | يحصل أو يعيّن كائن الشريحة الذي يرتبط به كائن Slide Zoom. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | يحصل أو يعيّن كائن الشريحة الذي يرتبط به كائن Slide Zoom. |
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

يحصل أو يعيّن كائن الشريحة الذي يرتبط به كائن Slide Zoom. قراءة/كتابة [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**القيمة المرجعة:**
[ISlide](../../com.aspose.slides/islide)
### setTargetSlide(ISlide value) {#setTargetSlide-com.aspose.slides.ISlide-}
```
public abstract void setTargetSlide(ISlide value)
```

يحصل أو يعيّن كائن الشريحة الذي يرتبط به كائن Slide Zoom. قراءة/كتابة [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |