---
title: SectionZoomFrame
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar ett Section Zoom-objekt i en bild.
type: docs
url: /sv/com.aspose.slides/sectionzoomframe/
---
**Arv:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**Alla implementerade gränssnitt:**
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)
```
public class SectionZoomFrame extends ZoomObject implements ISectionZoomFrame
```

Representerar ett Section Zoom-objekt i en bild.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | Hämtar eller anger section-objektet som Section Zoom-objektet länkar till. |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | Hämtar eller anger section-objektet som Section Zoom-objektet länkar till. |
### getTargetSection() {#getTargetSection--}
```
public final ISection getTargetSection()
```


Hämtar eller anger section-objektet som Section Zoom-objektet länkar till. Läs/skriv [ISection](../../com.aspose.slides/isection).

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

**Returnerar:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public final void setTargetSection(ISection value)
```


Hämtar eller anger section-objektet som Section Zoom-objektet länkar till. Läs/skriv [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> Nästa exempel demonstrerar ändring av målsektionen och skapar en ny bild för section zoom-objektet:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>      sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |