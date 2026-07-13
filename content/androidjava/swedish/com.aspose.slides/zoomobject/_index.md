---
title: ZoomObject
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar ett Zoom-objekt i en bild.
type: docs
url: /sv/com.aspose.slides/zoomobject/
---
**Arv:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public class ZoomObject extends GraphicalObject implements IZoomObject
```

Representerar ett Zoom-objekt i en bild.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getImageType()](#getImageType--) | Hämtar eller anger bildtypen för ett zoom-objekt. |
| [setImageType(int value)](#setImageType-int-) | Hämtar eller anger bildtypen för ett zoom-objekt. |
| [getReturnToParent()](#getReturnToParent--) | Hämtar eller anger navigeringsbeteendet i bildspelet. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Hämtar eller anger navigeringsbeteendet i bildspelet. |
| [getShowBackground()](#getShowBackground--) | Hämtar eller anger värdet som specificerar om Zoom ska använda bakgrunden på målbilden. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Hämtar eller anger värdet som specificerar om Zoom ska använda bakgrunden på målbilden. |
| [getZoomImage()](#getZoomImage--) | Hämtar eller anger bild för zoom-objekt. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Hämtar eller anger bild för zoom-objekt. |
| [getTransitionDuration()](#getTransitionDuration--) | Hämtar eller anger varaktigheten för övergången mellan Zoom och bild. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Hämtar eller anger varaktigheten för övergången mellan Zoom och bild. |
### getImageType() {#getImageType--}
```
public final int getImageType()
```


Hämtar eller anger bildtypen för ett zoom-objekt. Läs/skriv [ZoomImageType](../../com.aspose.slides/zoomimagetype). Standardvärde: Preview

--------------------

> ```
> Next example demonstrates changing Image Type to Preview value. 
>  In this case current image of a Zoom object changes to slide image:
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

Anger om Zoom-objektet använder bildförhandsgranskning eller en omslagbild.

**Returnerar:**
int
### setImageType(int value) {#setImageType-int-}
```
public final void setImageType(int value)
```


Hämtar eller anger bildtypen för ett zoom-objekt. Läs/skriv [ZoomImageType](../../com.aspose.slides/zoomimagetype). Standardvärde: Preview

--------------------

> ```
> Next example demonstrates changing Image Type to Preview value. 
>  In this case current image of a Zoom object changes to slide image:
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

Anger om Zoom-objektet använder bildförhandsgranskning eller en omslagbild.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getReturnToParent() {#getReturnToParent--}
```
public final boolean getReturnToParent()
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

Sant värde på egenskapen anger återgång till föräldranavigering i bildspelet.

**Returnerar:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public final void setReturnToParent(boolean value)
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

Sant värde på egenskapen anger återgång till föräldranavigering i bildspelet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowBackground() {#getShowBackground--}
```
public final boolean getShowBackground()
```


Hämtar eller anger värdet som specificerar om Zoom ska använda bakgrunden på målbilden. Läs/skriv boolean. Standardvärde: true

--------------------

> ```
> exemplet demonstrerar hur bakgrunden tas bort från en bild av ett Zoom-objekt:
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
public final void setShowBackground(boolean value)
```


Hämtar eller anger värdet som specificerar om Zoom ska använda bakgrunden på målbilden. Läs/skriv boolean. Standardvärde: true

--------------------

> ```
> exemplet demonstrerar hur bakgrunden tas bort från en bild av ett Zoom-objekt:
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
public final IPPImage getZoomImage()
```


Hämtar eller anger bild för zoom-objekt. Läs/skriv [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> the example demonstrates changing an image of a Zoom object:
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
public final void setZoomImage(IPPImage value)
```


Hämtar eller anger bild för zoom-objekt. Läs/skriv [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> exemplet demonstrerar hur man ändrar en bild av ett Zoom-objekt:
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
public final float getTransitionDuration()
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


--------------------

Om inte specificerat (TransitionDur = 0) kommer den att använda övergången för målbilden och tidsinställningarna som är kopplade till den övergången.

**Returnerar:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public final void setTransitionDuration(float value)
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

--------------------

Om inte specificerat (TransitionDur = 0) kommer den att använda övergången för målbilden och tidsinställningarna som är kopplade till den övergången.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |