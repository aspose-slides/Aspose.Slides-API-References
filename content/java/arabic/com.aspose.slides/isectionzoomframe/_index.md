---
title: ISectionZoomFrame
second_title: Aspose.Slides لمرجع API جافا
description: يمثل كائن Section Zoom في شريحة.
type: docs
url: /ar/com.aspose.slides/isectionzoomframe/
---
**All Implemented Interfaces:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface ISectionZoomFrame extends IZoomObject
```

يمثل كائن Section Zoom في شريحة.
## Methods

| Method | Description |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | يحصل أو يعيّن كائن القسم الذي يرتبط به كائن Section Zoom. |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | يحصل أو يعيّن كائن القسم الذي يرتبط به كائن Section Zoom. |
### getTargetSection() {#getTargetSection--}
```
public abstract ISection getTargetSection()
```


يحصل أو يعيّن كائن القسم الذي يرتبط به كائن Section Zoom. قراءة/كتابة [ISection](../../com.aspose.slides/isection).

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

**Returns:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public abstract void setTargetSection(ISection value)
```


يحصل أو يعيّن كائن القسم الذي يرتبط به كائن Section Zoom. قراءة/كتابة [ISection](../../com.aspose.slides/isection).

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |