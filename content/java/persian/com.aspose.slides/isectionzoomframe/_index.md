---
title: ISectionZoomFrame
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایندهٔ یک شی Section Zoom در یک اسلاید است.
type: docs
url: /fa/com.aspose.slides/isectionzoomframe/
---
**تمام اینترفیس‌های پیاده‌سازی شده:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface ISectionZoomFrame extends IZoomObject
```

نمایندهٔ یک شی Section Zoom در یک اسلاید است.
## متدها

| متد | توضیح |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | دریافت یا تنظیم شی بخش که شی Section Zoom به آن پیوند داده شده است. |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | دریافت یا تنظیم شی بخش که شی Section Zoom به آن پیوند داده شده است. |
### getTargetSection() {#getTargetSection--}
```
public abstract ISection getTargetSection()
```


دریافت یا تنظیم شی بخش که شی Section Zoom به آن مرتبط است. خواندن/نوشتن [ISection](../../com.aspose.slides/isection).

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


**باز می‌گرداند:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public abstract void setTargetSection(ISection value)
```


دریافت یا تنظیم شی بخش که شی Section Zoom به آن مرتبط است. خواندن/نوشتن [ISection](../../com.aspose.slides/isection).

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


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |