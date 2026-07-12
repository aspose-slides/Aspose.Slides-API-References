---
title: ISectionZoomFrame
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt ein Section Zoom-Objekt in einer Folie dar.
type: docs
url: /de/com.aspose.slides/isectionzoomframe/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface ISectionZoomFrame extends IZoomObject
```

Stellt ein Section Zoom-Objekt in einer Folie dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | Liest oder setzt das Abschnittsobjekt, mit dem das Section Zoom-Objekt verknüpft ist. |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | Liest oder setzt das Abschnittsobjekt, mit dem das Section Zoom-Objekt verknüpft ist. |
### getTargetSection() {#getTargetSection--}
```
public abstract ISection getTargetSection()
```

Liest oder setzt das Abschnittsobjekt, mit dem das Section Zoom-Objekt verknüpft ist. Lesen/Schreiben [ISection](../../com.aspose.slides/isection).

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


**Rückgabe:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public abstract void setTargetSection(ISection value)
```

Liest oder setzt das Abschnittsobjekt, mit dem das Section Zoom-Objekt verknüpft ist. Lesen/Schreiben [ISection](../../com.aspose.slides/isection).

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


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |