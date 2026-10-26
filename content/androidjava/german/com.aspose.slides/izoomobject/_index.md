---
title: IZoomObject
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt ein Zoom-Objekt in einer Folie dar.
type: docs
url: /de/com.aspose.slides/izoomobject/
---
**All Implemented Interfaces:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IZoomObject extends IGraphicalObject
```

Stellt ein Zoom-Objekt in einer Folie dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getImageType()](#getImageType--) | Ruft den Bildtyp eines Zoom-Objekts ab oder legt ihn fest. |
| [setImageType(int value)](#setImageType-int-) | Ruft den Bildtyp eines Zoom-Objekts ab oder legt ihn fest. |
| [getReturnToParent()](#getReturnToParent--) | Ruft das Navigationsverhalten in der Vorführung ab oder legt es fest. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Ruft das Navigationsverhalten in der Vorführung ab oder legt es fest. |
| [getShowBackground()](#getShowBackground--) | Ruft den Wert ab oder legt ihn fest, der angibt, ob das Zoom-Objekt den Hintergrund der Ziel-Folien verwendet. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Ruft den Wert ab oder legt ihn fest, der angibt, ob das Zoom-Objekt den Hintergrund der Ziel-Folien verwendet. |
| [getZoomImage()](#getZoomImage--) | Ruft das Bild für das Zoom-Objekt ab oder legt es fest. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Ruft das Bild für das Zoom-Objekt ab oder legt es fest. |
| [getTransitionDuration()](#getTransitionDuration--) | Ruft die Dauer des Übergangs zwischen Zoom und Folie ab oder legt sie fest. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Ruft die Dauer des Übergangs zwischen Zoom und Folie ab oder legt sie fest. |
### getImageType() {#getImageType--}
```
public abstract int getImageType()
```


Ruft den Bildtyp eines Zoom-Objekts ab oder legt ihn fest. Lesen/Schreiben [ZoomImageType](../../com.aspose.slides/zoomimagetype). Standardwert: Preview

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

Gibt an, ob das Zoom-Objekt die Folien-Vorschau oder ein Deckblatt-Bild verwendet.

**Rückgabewert:**
int
### setImageType(int value) {#setImageType-int-}
```
public abstract void setImageType(int value)
```


Ruft den Bildtyp eines Zoom-Objekts ab oder legt ihn fest. Lesen/Schreiben [ZoomImageType](../../com.aspose.slides/zoomimagetype). Standardwert: Preview

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

Gibt an, ob das Zoom-Objekt die Folien-Vorschau oder ein Deckblatt-Bild verwendet.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getReturnToParent() {#getReturnToParent--}
```
public abstract boolean getReturnToParent()
```


Ruft das Navigationsverhalten in der Vorführung ab oder legt es fest. Lesen/Schreiben boolean. Standardwert: false

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

Der Wert true der Eigenschaft gibt das Rückkehr-zu-Eltern-Navigationsverhalten in der Vorführung an.

**Rückgabewert:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public abstract void setReturnToParent(boolean value)
```


Ruft das Navigationsverhalten in der Vorführung ab oder legt es fest. Lesen/Schreiben boolean. Standardwert: false

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

Der Wert true der Eigenschaft gibt das Rückkehr-zu-Eltern-Navigationsverhalten in der Vorführung an.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowBackground() {#getShowBackground--}
```
public abstract boolean getShowBackground()
```


Ruft den Wert ab oder legt ihn fest, der angibt, ob das Zoom-Objekt den Hintergrund der Ziel-Folien verwendet. Lesen/Schreiben boolean. Standardwert: true

--------------------

> ```
> Das Beispiel demonstriert das Entfernen des Hintergrunds eines Bildes eines Zoom-Objekts:
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


Ruft den Wert ab oder legt ihn fest, der angibt, ob das Zoom-Objekt den Hintergrund der Ziel-Folien verwendet. Lesen/Schreiben boolean. Standardwert: true

--------------------

> ```
> Das Beispiel demonstriert das Entfernen des Hintergrunds eines Bildes eines Zoom-Objekts:
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


Ruft das Bild für das Zoom-Objekt ab oder legt es fest. Lesen/Schreiben [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> The example demonstrates changing an image of a Zoom object:
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


**Rückgabewert:**
[IPPImage](../../com.aspose.slides/ippimage)
### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public abstract void setZoomImage(IPPImage value)
```


Ruft das Bild für das Zoom-Objekt ab oder legt es fest. Lesen/Schreiben [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> Das Beispiel demonstriert das Ändern eines Bildes eines Zoom-Objekts:
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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getTransitionDuration() {#getTransitionDuration--}
```
public abstract float getTransitionDuration()
```


Ruft die Dauer des Übergangs zwischen Zoom und Folie ab oder legt sie fest. Lesen/Schreiben float. Standardwert: 1.0f

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

Wenn nicht angegeben (TransitionDur = 0), wird die Übergangs-Animation der Ziel-Folien und die damit verbundenen Zeitangaben verwendet.

**Rückgabewert:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public abstract void setTransitionDuration(float value)
```


Ruft die Dauer des Übergangs zwischen Zoom und Folie ab oder legt sie fest. Lesen/Schreiben float. Standardwert: 1.0f

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

Wenn nicht angegeben (TransitionDur = 0), wird die Übergangs-Animation der Ziel-Folien und die damit verbundenen Zeitangaben verwendet.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |