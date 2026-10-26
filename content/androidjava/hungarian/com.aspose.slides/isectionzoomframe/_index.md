---
title: ISectionZoomFrame
second_title: Aspose.Slides Android számára Java API hivatkozás
description: Egy dián egy Section Zoom objektumot ábrázol.
type: docs
url: /hu/com.aspose.slides/isectionzoomframe/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface ISectionZoomFrame extends IZoomObject
```

Egy dián egy Section Zoom objektumot ábrázol.
## Módszerek

| Method | Description |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | Gets or sets the section object that the Section Zoom object is linked to. |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | Gets or sets the section object that the Section Zoom object is linked to. |
### getTargetSection() {#getTargetSection--}
```
public abstract ISection getTargetSection()
```

Gets or sets the section object that the Section Zoom object is linked to. Olvasás/írás [ISection](../../com.aspose.slides/isection).

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

**Visszatérési érték:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public abstract void setTargetSection(ISection value)
```

Gets or sets the section object that the Section Zoom object is linked to. Olvasás/írás [ISection](../../com.aspose.slides/isection).

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

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |