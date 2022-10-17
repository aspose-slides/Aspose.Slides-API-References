---
title: SectionZoomFrame
second_title: Aspose.Slides for Java API Reference
description:  Represents a Section Zoom object in a slide.
type: docs
weight: 479
url: /java/com.aspose.slides/sectionzoomframe/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**All Implemented Interfaces:**
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)
```
public class SectionZoomFrame extends ZoomObject implements ISectionZoomFrame
```

Represents a Section Zoom object in a slide.
## Methods

| Method | Description |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | Gets or sets the section object that the Section Zoom object links to. |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | Gets or sets the section object that the Section Zoom object links to. |
### getTargetSection() {#getTargetSection--}
```
public final ISection getTargetSection()
```


Gets or sets the section object that the Section Zoom object links to. Read/write [ISection](../../com.aspose.slides/isection).

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

**Returns:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public final void setTargetSection(ISection value)
```


Gets or sets the section object that the Section Zoom object links to. Read/write [ISection](../../com.aspose.slides/isection).

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |

