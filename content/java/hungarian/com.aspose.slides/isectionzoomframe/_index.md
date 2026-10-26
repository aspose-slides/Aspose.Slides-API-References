---
title: ISectionZoomFrame
second_title: Aspose.Slides Java API hivatkozás
description: Egy szakasz zoom objektumot képvisel egy dián.
type: docs
url: /hu/com.aspose.slides/isectionzoomframe/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface ISectionZoomFrame extends IZoomObject
```

Egy szakasz zoom objektumot képviseli egy dián.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | Lekéri vagy beállítja azt a szakaszobjektumot, amelyhez a Section Zoom objektum kapcsolódik. |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | Lekéri vagy beállítja azt a szakaszobjektumot, amelyhez a Section Zoom objektum kapcsolódik. |
### getTargetSection() {#getTargetSection--}
```
public abstract ISection getTargetSection()
```

Lekéri vagy beállítja azt a szakaszobjektumot, amelyhez a Section Zoom objektum kapcsolódik. Olvasás/írás [ISection](../../com.aspose.slides/isection).

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

Lekéri vagy beállítja azt a szakaszobjektumot, amelyhez a Section Zoom objektum kapcsolódik. Olvasás/írás [ISection](../../com.aspose.slides/isection).

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
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |