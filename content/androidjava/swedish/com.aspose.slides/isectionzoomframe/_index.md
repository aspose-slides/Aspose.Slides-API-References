---
title: ISectionZoomFrame
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar ett Section Zoom-objekt i en bild.
type: docs
url: /sv/com.aspose.slides/isectionzoomframe/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface ISectionZoomFrame extends IZoomObject
```

Representerar ett Section Zoom-objekt i en bild.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | Hämtar eller anger avsnittsobjektet som Section Zoom-objektet är länkat till. |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | Hämtar eller anger avsnittsobjektet som Section Zoom-objektet är länkat till. |
### getTargetSection() {#getTargetSection--}
```
public abstract ISection getTargetSection()
```

Hämtar eller anger avsnittsobjektet som Section Zoom-objektet är länkat till. Läs/skriv [ISection](../../com.aspose.slides/isection).

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

**Returnerar:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public abstract void setTargetSection(ISection value)
```

Hämtar eller anger avsnittsobjektet som Section Zoom-objektet är länkat till. Läs/skriv [ISection](../../com.aspose.slides/isection).

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |