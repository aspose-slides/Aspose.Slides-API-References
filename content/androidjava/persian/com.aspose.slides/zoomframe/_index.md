---
title: ZoomFrame
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: یک شیء Slide Zoom را در یک اسلاید نمایش می‌دهد.
type: docs
url: /fa/com.aspose.slides/zoomframe/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IZoomFrame](../../com.aspose.slides/izoomframe)
```
public class ZoomFrame extends ZoomObject implements IZoomFrame
```

یک شیء Slide Zoom را در یک اسلاید نمایش می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | شیء اسلایدی را که شیء Slide Zoom به آن پیوند می‌زند دریافت یا تنظیم می‌کند. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | شیء اسلایدی را که شیء Slide Zoom به آن پیوند می‌زند دریافت یا تنظیم می‌کند. |
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

شیء اسلایدی را که شیء Slide Zoom به آن پیوند می‌زند دریافت یا تنظیم می‌کند. قابل خواندن/قابل نوشتن [ISlide](../../com.aspose.slides/islide).

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
public final void setTargetSlide(ISlide value)
```

شیء اسلایدی را که شیء Slide Zoom به آن پیوند می‌زند دریافت یا تنظیم می‌کند. قابل خواندن/قابل نوشتن [ISlide](../../com.aspose.slides/islide).

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