---
title: SectionZoomFrame
second_title: مرجع API Aspose.Slides للغة Java
description: يمثل كائن Section Zoom في شريحة.
type: docs
url: /ar/com.aspose.slides/sectionzoomframe/
---
**الوراثة:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**جميع الواجهات المُطبَّقة:**  
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)  
```
public class SectionZoomFrame extends ZoomObject implements ISectionZoomFrame
```

يمثّل كائن Section Zoom في شريحة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | يحصل أو يعيّن كائن القسم الذي يربط به كائن Section Zoom. |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | يحصل أو يعيّن كائن القسم الذي يربط به كائن Section Zoom. |
### getTargetSection() {#getTargetSection--}
```
public final ISection getTargetSection()
```

يحصل أو يعيّن كائن القسم الذي يربط به كائن Section Zoom. قراءة/كتابة [ISection](../../com.aspose.slides/isection).

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


**الإرجاع:**  
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public final void setTargetSection(ISection value)
```

يحصل أو يعيّن كائن القسم الذي يربط به كائن Section Zoom. قراءة/كتابة [ISection](../../com.aspose.slides/isection).

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


**المعلمات:**  
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |