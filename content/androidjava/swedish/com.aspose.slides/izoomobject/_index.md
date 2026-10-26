---
title: IZoomObject
second_title: Aspose.Slides för Android via Java API-referens
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
| [getImageType()](#getImageType--) | Hämtar eller anger bildtypen för ett zoomobjekt. |
| [setImageType(int value)](#setImageType-int-) | Hämtar eller anger bildtypen för ett zoomobjekt. |
| [getReturnToParent()](#getReturnToParent--) | Hämtar eller anger navigeringsbeteendet i bildspelsläget. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Hämtar eller anger navigeringsbeteendet i bildspelsläget. |
| [getShowBackground()](#getShowBackground--) | Hämtar eller anger värde som specificerar om Zoom ska använda bakgrunden för målbilden. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Hämtar eller anger värde som specificerar om Zoom ska använda bakgrunden för målbilden. |
| [getZoomImage()](#getZoomImage--) | Hämtar eller anger bild för zoomobjekt. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Hämtar eller anger bild för zoomobjekt. |
| [getTransitionDuration()](#getTransitionDuration--) | Hämtar eller anger varaktigheten för övergången mellan Zoom och bild. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Hämtar eller anger varaktigheten för övergången mellan Zoom och bild. |
### getImageType() {#getImageType--}
```
public abstract int getImageType()
```

Hämtar eller anger bildtypen för ett zoomobjekt. Läs/skriv [ZoomImageType](../../com.aspose.slides/zoomimagetype). Standardvärde: Preview

--------------------

> ```
> Detta exempel visar hur man ändrar bildtyp till Preview-värdet. 
>  I detta fall ändras den aktuella bilden för ett Zoom-objekt till bildens bild:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>          zoomFrame.setImageType(ZoomImageType.Preview);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Anger om Zoom-objektet använder bildförhandsgranskning eller en omslagsbild.

**Returnerar:**
int
### setImageType(int value) {#setImageType-int-}
```
public abstract void setImageType(int value)
```

Hämtar eller anger bildtypen för ett zoomobjekt. Läs/skriv [ZoomImageType](../../com.aspose.slides/zoomimagetype). Standardvärde: Preview

--------------------

> ```
> This example demonstrates changing Image Type to Preview value. 
>  In this case the current image of a Zoom object changes to slide image:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>          zoomFrame.setImageType(ZoomImageType.Preview);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Anger om Zoom-objektet använder bildförhandsgranskning eller en omslagsbild.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getReturnToParent() {#getReturnToParent--}
```
public abstract boolean getReturnToParent()
```

Hämtar eller anger navigeringsbeteendet i bildspelsläget. Läs/skriv boolean. Standardvärde: false

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

Sant värde på egenskapen anger återgång till föräldranavigering i bildspelsläget.

**Returnerar:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public abstract void setReturnToParent(boolean value)
```

Hämtar eller anger navigeringsbeteendet i bildspelsläget. Läs/skriv boolean. Standardvärde: false

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

Sant värde på egenskapen anger återgång till föräldranavigering i bildspelsläget.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowBackground() {#getShowBackground--}
```
public abstract boolean getShowBackground()
```

Hämtar eller anger värde som specificerar om Zoom ska använda bakgrunden för målbilden. Läs/skriv boolean. Standardvärde: true

--------------------

> ```
> The example demonstrates removing the background of an image of a Zoom object:
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

Hämtar eller anger värde som specificerar om Zoom ska använda bakgrunden för målbilden. Läs/skriv boolean. Standardvärde: true

--------------------

> ```
> Exemplet visar hur man tar bort bakgrunden på en bild av ett Zoom-objekt:
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getZoomImage() {#getZoomImage--}
```
public abstract IPPImage getZoomImage()
```

Hämtar eller anger bild för zoomobjekt. Läs/skriv [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> Exemplet visar hur man ändrar en bild av ett Zoom-objekt:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          zoomFrame.setImage(image);
>      } finally {
>          if (fos != null) fos.close();
>      }
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

Hämtar eller anger bild för zoomobjekt. Läs/skriv [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> Exemplet visar hur man ändrar en bild av ett Zoom-objekt:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          zoomFrame.setImage(image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getTransitionDuration() {#getTransitionDuration--}
```
public abstract float getTransitionDuration()
```

Hämtar eller anger varaktigheten för övergången mellan Zoom och bild. Läs/skriv float. Standardvärde: 1.0f

--------------------

> ```
> exemplet demonstrerar hur man ändrar varaktigheten för övergången mellan Zoom och bild:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


Om inte angivet (TransitionDur = 0) används målbildens övergång och tidsinställningarna som är associerade med den övergången.

**Returnerar:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public abstract void setTransitionDuration(float value)
```

Hämtar eller anger varaktigheten för övergången mellan Zoom och bild. Läs/skriv float. Standardvärde: 1.0f

--------------------

> ```
> Exemplet demonstrerar hur man ändrar varaktigheten för övergången mellan Zoom och bild:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

Om inte angivet (TransitionDur = 0) används målbildens övergång och tidsinställningarna som är associerade med den övergången.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |