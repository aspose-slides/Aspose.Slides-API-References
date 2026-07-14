---
title: IZoomFrame
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایشگر یک شیء Slide Zoom در یک اسلاید.
type: docs
url: /fa/com.aspose.slides/izoomframe/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface IZoomFrame extends IZoomObject
```

نمایشگر یک شیء Slide Zoom در یک اسلاید.
## متدها

| متد | توضیح |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Gets or sets the slide object that the Slide Zoom object links to. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Gets or sets the slide object that the Slide Zoom object links to. |
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```


Gets or sets the slide object that the Slide Zoom object links to. خواندنی/نوشتنی [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**بازگشت:**
[ISlide](../../com.aspose.slides/islide)
### setTargetSlide(ISlide value) {#setTargetSlide-com.aspose.slides.ISlide-}
```
public abstract void setTargetSlide(ISlide value)
```


Gets or sets the slide object that the Slide Zoom object links to. خواندنی/نوشتنی [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |