---
title: ZoomObject
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt ein Zoom-Objekt in einer Folie dar.
type: docs
url: /de/com.aspose.slides/zoomobject/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public class ZoomObject extends GraphicalObject implements IZoomObject
```

Stellt ein Zoom-Objekt in einer Folie dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getImageType()](#getImageType--) | Liest oder setzt den Bildtyp eines Zoom-Objekts. |
| [setImageType(int value)](#setImageType-int-) | Liest oder setzt den Bildtyp eines Zoom-Objekts. |
| [getReturnToParent()](#getReturnToParent--) | Liest oder setzt das Navigationsverhalten in der Diashow. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Liest oder setzt das Navigationsverhalten in der Diashow. |
| [getShowBackground()](#getShowBackground--) | Liest oder setzt den Wert, der angibt, ob das Zoom-Objekt den Hintergrund der Zielfolie verwendet. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Liest oder setzt den Wert, der angibt, ob das Zoom-Objekt den Hintergrund der Zielfolie verwendet. |
| [getZoomImage()](#getZoomImage--) | Liest oder setzt das Bild für das Zoom-Objekt. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Liest oder setzt das Bild für das Zoom-Objekt. |
| [getTransitionDuration()](#getTransitionDuration--) | Liest oder setzt die Dauer des Übergangs zwischen Zoom und Folie. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Liest oder setzt die Dauer des Übergangs zwischen Zoom und Folie. |
### getImageType() {#getImageType--}
```
public final int getImageType()
```

Liest oder setzt den Bildtyp eines Zoom-Objekts. Lesen/Schreiben [ZoomImageType](../../com.aspose.slides/zoomimagetype). Standardwert: Preview

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

Gibt an, ob das Zoom-Objekt die Folienvorschau oder ein Titelbild verwendet.

**Rückgabewert:**
int
### setImageType(int value) {#setImageType-int-}
```
public final void setImageType(int value)
```

Liest oder setzt den Bildtyp eines Zoom-Objekts. Lesen/Schreiben [ZoomImageType](../../com.aspose.slides/zoomimagetype). Standardwert: Preview

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

Gibt an, ob das Zoom-Objekt die Folienvorschau oder ein Titelbild verwendet.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getReturnToParent() {#getReturnToParent--}
```
public final boolean getReturnToParent()
```

Liest oder setzt das Navigationsverhalten in der Diashow. Lesen/Schreiben boolean. Standardwert: false

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

Der True-Wert der Eigenschaft gibt das Rückkehr-zum-Eltern-Navigationsverhalten in der Diashow an.

**Rückgabewert:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public final void setReturnToParent(boolean value)
```

Liest oder setzt das Navigationsverhalten in der Diashow. Lesen/Schreiben boolean. Standardwert: false

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

Der True-Wert der Eigenschaft gibt das Rückkehr-zum-Eltern-Navigationsverhalten in der Diashow an.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getShowBackground() {#getShowBackground--}
```
public final boolean getShowBackground()
```

Liest oder setzt den Wert, der angibt, ob das Zoom-Objekt den Hintergrund der Zielfolie verwendet. Lesen/Schreiben boolean. Standardwert: true

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
public final void setShowBackground(boolean value)
```

Liest oder setzt den Wert, der angibt, ob das Zoom-Objekt den Hintergrund der Zielfolie verwendet. Lesen/Schreiben boolean. Standardwert: true

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
public final IPPImage getZoomImage()
```

Liest oder setzt das Bild für das Zoom-Objekt. Lesen/Schreiben [IPPImage](../../com.aspose.slides/ippimage).

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

**Rückgabewert:**
[IPPImage](../../com.aspose.slides/ippimage)
### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public final void setZoomImage(IPPImage value)
```

Liest oder setzt das Bild für das Zoom-Objekt. Lesen/Schreiben [IPPImage](../../com.aspose.slides/ippimage).

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
public final float getTransitionDuration()
```

Liest oder setzt die Dauer des Übergangs zwischen Zoom und Folie. Lesen/Schreiben float. Standardwert: 1.0f

--------------------

> ```
> das Beispiel demonstriert das Ändern der Dauer des Übergangs zwischen Zoom und Folie:
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

Wenn nicht angegeben (TransitionDur = 0), wird die Folienübergang der Zielfolie und die damit verbundenen Zeitangaben verwendet.

**Rückgabewert:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public final void setTransitionDuration(float value)
```

Liest oder setzt die Dauer des Übergangs zwischen Zoom und Folie. Lesen/Schreiben float. Standardwert: 1.0f

--------------------

> ```
> das Beispiel demonstriert das Ändern der Dauer des Übergangs zwischen Zoom und Folie:
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

Wenn nicht angegeben (TransitionDur = 0), wird die Folienübergang der Zielfolie und die damit verbundenen Zeitangaben verwendet.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |