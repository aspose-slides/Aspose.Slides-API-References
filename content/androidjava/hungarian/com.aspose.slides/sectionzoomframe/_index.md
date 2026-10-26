---
title: SectionZoomFrame
second_title: Aspose.Slides Android számára Java API referencia
description: Egy dián lévő Section Zoom objektumot képvisel.
type: docs
url: /hu/com.aspose.slides/sectionzoomframe/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**Az összes megvalósított interfész:**
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)
```
public class SectionZoomFrame extends ZoomObject implements ISectionZoomFrame
```

Egy Section Zoom objektumot képvisel egy dián.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | A Section Zoom objektumhoz kapcsolódó szakasz objektumot lekéri vagy beállítja. |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | A Section Zoom objektumhoz kapcsolódó szakasz objektumot lekéri vagy beállítja. |
### getTargetSection() {#getTargetSection--}
```
public final ISection getTargetSection()
```

A Section Zoom objektumhoz kapcsolódó szakasz objektumot lekéri vagy beállítja. Olvasás/írás [ISection](../../com.aspose.slides/isection).

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


**Visszatérési érték:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public final void setTargetSection(ISection value)
```

A Section Zoom objektumhoz kapcsolódó szakasz objektumot lekéri vagy beállítja. Olvasás/írás [ISection](../../com.aspose.slides/isection).

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |