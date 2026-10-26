---
title: ISectionZoomFrame
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: یک شیء Section Zoom را در یک اسلاید نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/isectionzoomframe/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface ISectionZoomFrame extends IZoomObject
```

نمایانگر یک شیء Section Zoom در یک اسلاید.
## متدها

| متد | توضیح |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | شیء بخش را که شیء Section Zoom به آن لینک شده است، دریافت یا تنظیم می‌کند. |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | شیء بخش را که شیء Section Zoom به آن لینک شده است، دریافت یا تنظیم می‌کند. |
### getTargetSection() {#getTargetSection--}
```
public abstract ISection getTargetSection()
```


شیء بخش را که شیء Section Zoom به آن لینک شده است، دریافت یا تنظیم می‌کند. خواندن/نوشتن [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> This example demonstrates changing target section and creates a new image for the section zoom object:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>       sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازگرداندن:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public abstract void setTargetSection(ISection value)
```


شیء بخش را که شیء Section Zoom به آن لینک شده است، دریافت یا تنظیم می‌کند. خواندن/نوشتن [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> این مثال تغییر بخش هدف را نشان می‌دهد و یک تصویر جدید برای شیء Section Zoom ایجاد می‌کند:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>       sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |