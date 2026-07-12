---
title: ZoomFrame
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt ein Slide Zoom-Objekt in einer Folie dar.
type: docs
url: /de/com.aspose.slides/zoomframe/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IZoomFrame](../../com.aspose.slides/izoomframe)
```
public class ZoomFrame extends ZoomObject implements IZoomFrame
```

Stellt ein Slide Zoom-Objekt in einer Folie dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Liest oder setzt das Folienobjekt, das das Slide Zoom-Objekt verlinkt. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Liest oder setzt das Folienobjekt, das das Slide Zoom-Objekt verlinkt. |
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

Liest oder setzt das Folienobjekt, das das Slide Zoom-Objekt verlinkt. Lesen/Schreiben [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**Rückgabe:**
[ISlide](../../com.aspose.slides/islide)
### setTargetSlide(ISlide value) {#setTargetSlide-com.aspose.slides.ISlide-}
```
public final void setTargetSlide(ISlide value)
```

Liest oder setzt das Folienobjekt, das das Slide Zoom-Objekt verlinkt. Lesen/Schreiben [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |