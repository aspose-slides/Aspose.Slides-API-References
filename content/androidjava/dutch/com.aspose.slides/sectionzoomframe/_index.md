---
title: SectionZoomFrame
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een Section Zoom object voor in een dia.
type: docs
url: /nl/com.aspose.slides/sectionzoomframe/
---
**Overerving:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)
```
public class SectionZoomFrame extends ZoomObject implements ISectionZoomFrame
```

Stelt een Section Zoom object voor in een dia.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | Haalt of stelt het sectie-object in waarnaar het Section Zoom object verwijst. |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | Haalt of stelt het sectie-object in waarnaar het Section Zoom object verwijst. |
### getTargetSection() {#getTargetSection--}
```
public final ISection getTargetSection()
```

Haalt of stelt het sectie-object in waarnaar het Section Zoom object verwijst. Lezen/Schrijven [ISection](../../com.aspose.slides/isection).

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

**Retour:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public final void setTargetSection(ISection value)
```

Haalt of stelt het sectie-object in waarnaar het Section Zoom object verwijst. Lezen/Schrijven [ISection](../../com.aspose.slides/isection).

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |