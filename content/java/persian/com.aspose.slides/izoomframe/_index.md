---
title: IZoomFrame
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر یک شیء Slide Zoom در یک اسلاید است.
type: docs
url: /fa/com.aspose.slides/izoomframe/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface IZoomFrame extends IZoomObject
```

نشان‌دهندهٔ یک شیء Slide Zoom در یک اسلاید است.
## متدها

| متد | توضیح |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | شیء اسلایدی که شیء Slide Zoom به آن لینک می‌دهد را دریافت یا تنظیم می‌کند. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | شیء اسلایدی که شیء Slide Zoom به آن لینک می‌دهد را دریافت یا تنظیم می‌کند. |
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

شیء اسلایدی که شیء Slide Zoom به آن لینک می‌دهد را دریافت یا تنظیم می‌کند. خواندنی/نوشتنی [ISlide](../../com.aspose.slides/islide).

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

شیء اسلایدی که شیء Slide Zoom به آن لینک می‌دهد را دریافت یا تنظیم می‌کند. خواندنی/نوشتنی [ISlide](../../com.aspose.slides/islide).

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