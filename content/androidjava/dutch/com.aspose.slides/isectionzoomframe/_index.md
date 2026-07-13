---
title: ISectionZoomFrame
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een Section Zoom-object in een dia voor.
type: docs
url: /nl/com.aspose.slides/isectionzoomframe/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface ISectionZoomFrame extends IZoomObject
```

Stelt een Section Zoom-object in een dia voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | Haalt of stelt het sectie-object in waarmee het Section Zoom-object is gekoppeld. |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | Haalt of stelt het sectie-object in waarmee het Section Zoom-object is gekoppeld. |
### getTargetSection() {#getTargetSection--}
```
public abstract ISection getTargetSection()
```

Haalt of stelt het sectie-object in waarmee het Section Zoom-object is gekoppeld. Lezen/schrijven [ISection](../../com.aspose.slides/isection).

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

**Retour:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public abstract void setTargetSection(ISection value)
```

Haalt of stelt het sectie-object in waarmee het Section Zoom-object is gekoppeld. Lezen/schrijven [ISection](../../com.aspose.slides/isection).

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |