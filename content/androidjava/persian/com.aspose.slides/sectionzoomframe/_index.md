---
title: SectionZoomFrame
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: یک شیء Section Zoom را در اسلاید نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/sectionzoomframe/
---
**ارث‌بری:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)  
```
public class SectionZoomFrame extends ZoomObject implements ISectionZoomFrame
```

یک شیء Section Zoom را در اسلاید نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | دریافت یا تنظیم شیء بخش که شیء Section Zoom به آن پیوند می‌دهد. |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | دریافت یا تنظیم شیء بخش که شیء Section Zoom به آن پیوند می‌دهد. |
### getTargetSection() {#getTargetSection--}
```
public final ISection getTargetSection()
```

دریافت یا تنظیم شیء بخش که شیء Section Zoom به آن پیوند می‌دهد. خواندنی/نوشتنی [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> Next example demonstrates changing target section and creates new image for the section zoom object:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>      sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازگشت:**  
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public final void setTargetSection(ISection value)
```

دریافت یا تنظیم شیء بخش که شیء Section Zoom به آن پیوند می‌دهد. خواندنی/نوشتنی [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> Next example demonstrates changing target section and creates new image for the section zoom object:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>      sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |