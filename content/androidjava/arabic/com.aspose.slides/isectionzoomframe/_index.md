---
title: ISectionZoomFrame
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل كائن Section Zoom في شريحة.
type: docs
url: /ar/com.aspose.slides/isectionzoomframe/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface ISectionZoomFrame extends IZoomObject
```

يمثل كائن Section Zoom في شريحة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | يحصل أو يضبط كائن القسم الذي يرتبط به كائن Section Zoom. |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | يحصل أو يضبط كائن القسم الذي يرتبط به كائن Section Zoom. |
### getTargetSection() {#getTargetSection--}
```
public abstract ISection getTargetSection()
```

يحصل أو يضبط كائن القسم الذي يرتبط به كائن Section Zoom. قراءة/كتابة [ISection](../../com.aspose.slides/isection).

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


**الإرجاع:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public abstract void setTargetSection(ISection value)
```

يحصل أو يضبط كائن القسم الذي يرتبط به كائن Section Zoom. قراءة/كتابة [ISection](../../com.aspose.slides/isection).

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

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |