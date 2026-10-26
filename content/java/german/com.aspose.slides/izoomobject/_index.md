---
title: IZoomObject
second_title: Aspose.Slides für die Java-API-Referenz
description: Stellt ein Zoom-Objekt in einer Folie dar.
type: docs
url: /de/com.aspose.slides/izoomobject/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IZoomObject extends IGraphicalObject
```

Stellt ein Zoom-Objekt in einer Folie dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getImageType()](#getImageType--) | Liest oder setzt den Bildtyp eines Zoom-Objekts. |
| [setImageType(int value)](#setImageType-int-) | Liest oder setzt den Bildtyp eines Zoom-Objekts. |
| [getReturnToParent()](#getReturnToParent--) | Liest oder setzt das Navigationsverhalten in der Diashow. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Liest oder setzt das Navigationsverhalten in der Diashow. |
| [getShowBackground()](#getShowBackground--) | Liest oder setzt den Wert, der angibt, ob das Zoom den Hintergrund der Zielfolie verwendet. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Liest oder setzt den Wert, der angibt, ob das Zoom den Hintergrund der Zielfolie verwendet. |
| [getZoomImage()](#getZoomImage--) | Liest oder setzt das Bild für das Zoom-Objekt. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Liest oder setzt das Bild für das Zoom-Objekt. |
| [getTransitionDuration()](#getTransitionDuration--) | Liest oder setzt die Dauer des Übergangs zwischen Zoom und Folie. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Liest oder setzt die Dauer des Übergangs zwischen Zoom und Folie. |
### getImageType() {#getImageType--}
```
public abstract int getImageType()
```


Liest oder setzt den Bildtyp eines Zoom-Objekts. Lesen/Schreiben [ZoomImageType](../../com.aspose.slides/zoomimagetype). Standardwert: Preview

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

Gibt an, ob das Zoom-Objekt die Folienvorschau oder ein Deckblattbild verwendet.

**Rückgabewert:**
int
### setImageType(int value) {#setImageType-int-}
```
public abstract void setImageType(int value)
```


Liest oder setzt den Bildtyp eines Zoom-Objekts. Lesen/Schreiben [ZoomImageType](../../com.aspose.slides/zoomimagetype). Standardwert: Preview

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

Gibt an, ob das Zoom-Objekt die Folienvorschau oder ein Deckblattbild verwendet.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getReturnToParent() {#getReturnToParent--}
```
public abstract boolean getReturnToParent()
```


Liest oder setzt das Navigationsverhalten in der Diashow. Lesen/Schreiben boolesch. Standardwert: false

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

Ein wahrer Wert der Eigenschaft gibt das Rückkehr-zum-Eltern-Navigationsverhalten in der Diashow an.

**Rückgabewert:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public abstract void setReturnToParent(boolean value)
```


Liest oder setzt das Navigationsverhalten in der Diashow. Lesen/Schreiben boolesch. Standardwert: false

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

Ein wahrer Wert der Eigenschaft gibt das Rückkehr-zum-Eltern-Navigationsverhalten in der Diashow an.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowBackground() {#getShowBackground--}
```
public abstract boolean getShowBackground()
```


Liest oder setzt den Wert, der angibt, ob das Zoom den Hintergrund der Zielfolie verwendet. Lesen/Schreiben boolesch. Standardwert: true

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


**Rückgabewert:**
boolean
### setShowBackground(boolean value) {#setShowBackground-boolean-}
```
public abstract void setShowBackground(boolean value)
```


Liest oder setzt den Wert, der angibt, ob das Zoom den Hintergrund der Zielfolie verwendet. Lesen/Schreiben boolesch. Standardwert: true

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getZoomImage() {#getZoomImage--}
```
public abstract IPPImage getZoomImage()
```


Liest oder setzt das Bild für das Zoom-Objekt. Lesen/Schreiben [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> Das Beispiel demonstriert das Ändern eines Bildes eines Zoom-Objekts:
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


**Rückgabewert:**
[IPPImage](../../com.aspose.slides/ippimage)
### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public abstract void setZoomImage(IPPImage value)
```


Liest oder setzt das Bild für das Zoom-Objekt. Lesen/Schreiben [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> Das Beispiel demonstriert das Ändern eines Bildes eines Zoom-Objekts:
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


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getTransitionDuration() {#getTransitionDuration--}
```
public abstract float getTransitionDuration()
```


Liest oder setzt die Dauer des Übergangs zwischen Zoom und Folie. Lesen/Schreiben float. Standardwert: 1.0f

--------------------

> ```
> Das Beispiel demonstriert das Ändern der Dauer des Übergangs zwischen Zoom und Folie:
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

Wenn nicht angegeben (TransitionDur = 0), wird die Übergangsanimation der Zielfolie und die damit verbundenen Zeitangaben verwendet.

**Rückgabewert:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public abstract void setTransitionDuration(float value)
```


Liest oder setzt die Dauer des Übergangs zwischen Zoom und Folie. Lesen/Schreiben float. Standardwert: 1.0f

--------------------

> ```
> Das Beispiel demonstriert das Ändern der Dauer des Übergangs zwischen Zoom und Folie:
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

Wenn nicht angegeben (TransitionDur = 0), wird die Übergangsanimation der Zielfolie und die damit verbundenen Zeitangaben verwendet.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |