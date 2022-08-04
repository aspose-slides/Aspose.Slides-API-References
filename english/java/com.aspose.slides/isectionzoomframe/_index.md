---
title: ISectionZoomFrame
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents a Section Zoom object in a slide.
type: docs
weight: 1008
url: /java/com.aspose.slides/isectionzoomframe/
---
**All Implemented Interfaces:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface ISectionZoomFrame extends IZoomObject
```

Represents a Section Zoom object in a slide.
## Methods

| Method | Description |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | Gets or sets the section object that the Section Zoom object is linked to. |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | Gets or sets the section object that the Section Zoom object is linked to. |
### getTargetSection() {#getTargetSection--}
```
public abstract ISection getTargetSection()
```


Gets or sets the section object that the Section Zoom object is linked to. Read/write [ISection](../../com.aspose.slides/isection).

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


Gets or sets the section object that the Section Zoom object is linked to. Read/write [ISection](../../com.aspose.slides/isection).

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

