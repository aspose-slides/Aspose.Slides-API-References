---
title: IZoomObject
second_title: Aspose.Slides för Java API-referens
description: Representerar ett Zoom-objekt i en bild.
type: docs
url: /sv/com.aspose.slides/izoomobject/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IZoomObject extends IGraphicalObject
```

Representerar ett Zoom-objekt i en bild.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getImageType()](#getImageType--) | Hämtar eller anger bildtypen för ett zoom-objekt. |
| [setImageType(int value)](#setImageType-int-) | Hämtar eller anger bildtypen för ett zoom-objekt. |
| [getReturnToParent()](#getReturnToParent--) | Hämtar eller anger navigeringsbeteendet i bildspelet. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Hämtar eller anger navigeringsbeteendet i bildspelet. |
| [getShowBackground()](#getShowBackground--) | Hämtar eller anger värdet som specificerar om Zoom ska använda bakgrunden för destinationsbilden. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Hämtar eller anger värdet som specificerar om Zoom ska använda bakgrunden för destinationsbilden. |
| [getZoomImage()](#getZoomImage--) | Hämtar eller anger bild för zoom-objektet. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Hämtar eller anger bild för zoom-objektet. |
| [getTransitionDuration()](#getTransitionDuration--) | Hämtar eller anger varaktigheten för övergången mellan Zoom och bild. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Hämtar eller anger varaktigheten för övergången mellan Zoom och bild. |
### getImageType() {#getImageType--}
```
public abstract int getImageType()
```

Hämtar eller anger bildtypen för ett zoom-objekt. Läs/skriv [ZoomImageType](../../com.aspose.slides/zoomimagetype). Standardvärde: Preview

--------------------

> ```
> This example demonstrates changing Image Type to Preview value. 
>  In this case the current image of a Zoom object changes to slide image:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>      zoomFrame.setImageType(ZoomImageType.Preview);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Anger om Zoom-objektet använder bildförhandsvisningen eller en omslagsbild.

**Returnerar:**
int
### setImageType(int value) {#setImageType-int-}
```
public abstract void setImageType(int value)
```

Hämtar eller anger bildtypen för ett zoom-objekt. Läs/skriv [ZoomImageType](../../com.aspose.slides/zoomimagetype). Standardvärde: Preview

--------------------

> ```
> This example demonstrates changing Image Type to Preview value. 
>  In this case the current image of a Zoom object changes to slide image:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>      zoomFrame.setImageType(ZoomImageType.Preview);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Anger om Zoom-objektet använder bildförhandsvisningen eller en omslagsbild.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getReturnToParent() {#getReturnToParent--}
```
public abstract boolean getReturnToParent()
```

Hämtar eller anger navigeringsbeteendet i bildspelet. Läs/skriv boolean. Standardvärde: false

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setReturnToParent(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Sant värde av egenskapen anger återgång till föräldernavigeringsbeteendet i bildspelet.

**Returnerar:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public abstract void setReturnToParent(boolean value)
```

Hämtar eller anger navigeringsbeteendet i bildspelet. Läs/skriv boolean. Standardvärde: false

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setReturnToParent(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Sant värde av egenskapen anger återgång till föräldernavigeringsbeteendet i bildspelet.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowBackground() {#getShowBackground--}
```
public abstract boolean getShowBackground()
```

Hämtar eller anger värdet som specificerar om Zoom ska använda bakgrunden för destinationsbilden. Läs/skriv boolean. Standardvärde: true

--------------------

> ```
> Exemplet visar hur bakgrunden tas bort från en bild av ett Zoom-objekt:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returnerar:**
boolean
### setShowBackground(boolean value) {#setShowBackground-boolean-}
```
public abstract void setShowBackground(boolean value)
```

Hämtar eller anger värdet som specificerar om Zoom ska använda bakgrunden för destinationsbilden. Läs/skriv boolean. Standardvärde: true

--------------------

> ```
> Exemplet visar hur bakgrunden tas bort från en bild av ett Zoom-objekt:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZoomImage() {#getZoomImage--}
```
public abstract IPPImage getZoomImage()
```

Hämtar eller anger bild för zoom-objektet. Läs/skriv [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> Exemplet visar hur man ändrar en bild av ett Zoom-objekt:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      zoomFrame.setImage(image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returnerar:**
[IPPImage](../../com.aspose.slides/ippimage)
### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public abstract void setZoomImage(IPPImage value)
```

Hämtar eller anger bild för zoom-objektet. Läs/skriv [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> Exemplet visar hur man ändrar en bild av ett Zoom-objekt:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      zoomFrame.setImage(image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getTransitionDuration() {#getTransitionDuration--}
```
public abstract float getTransitionDuration()
```

Hämtar eller anger varaktigheten för övergången mellan Zoom och bild. Läs/skriv float. Standardvärde: 1.0f

--------------------

> ```
> the example demonstrates changing the duration of the transition between Zoom and slide:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Om inte angivet (TransitionDur = 0) kommer den att använda destinationsbildens övergång och tidpunkterna som är kopplade till den övergången.

**Returnerar:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public abstract void setTransitionDuration(float value)
```

Hämtar eller anger varaktigheten för övergången mellan Zoom och bild. Läs/skriv float. Standardvärde: 1.0f

--------------------

> ```
> the example demonstrates changing the duration of the transition between Zoom and slide:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Om inte angivet (TransitionDur = 0) kommer den att använda destinationsbildens övergång och tidpunkterna som är kopplade till den övergången.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |