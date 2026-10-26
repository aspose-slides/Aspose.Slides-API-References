---
title: ZoomObject
second_title: Aspose.Slides für Java API-Referenz
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
| [getImageType()](#getImageType--) | Ermittelt oder legt den Bildtyp eines Zoom-Objekts fest. |
| [setImageType(int value)](#setImageType-int-) | Ermittelt oder legt den Bildtyp eines Zoom-Objekts fest. |
| [getReturnToParent()](#getReturnToParent--) | Ermittelt oder legt das Navigationsverhalten in der Diashow fest. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Ermittelt oder legt das Navigationsverhalten in der Diashow fest. |
| [getShowBackground()](#getShowBackground--) | Ermittelt oder legt den Wert fest, der angibt, ob das Zoom den Hintergrund der Zielfolie verwendet. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Ermittelt oder legt den Wert fest, der angibt, ob das Zoom den Hintergrund der Zielfolie verwendet. |
| [getZoomImage()](#getZoomImage--) | Ermittelt oder legt das Bild für das Zoom-Objekt fest. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Ermittelt oder legt das Bild für das Zoom-Objekt fest. |
| [getTransitionDuration()](#getTransitionDuration--) | Ermittelt oder legt die Dauer der Übergangsanimation zwischen Zoom und Folie fest. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Ermittelt oder legt die Dauer der Übergangsanimation zwischen Zoom und Folie fest. |
### getImageType() {#getImageType--}
```
public final int getImageType()
```

Ermittelt oder legt den Bildtyp eines Zoom-Objekts fest. Lese-/Schreibzugriff [ZoomImageType](../../com.aspose.slides/zoomimagetype). Standardwert: Preview

--------------------

> ```
> Das nächste Beispiel zeigt das Ändern des Bildtyps auf den Wert Preview. 
>  In diesem Fall wird das aktuelle Bild eines Zoom-Objekts in das Folienbild geändert:
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

Gibt an, ob das Zoom-Objekt die Folienvorschau oder ein Titelbild verwendet.

**Rückgabewert:**
int
### setImageType(int value) {#setImageType-int-}
```
public final void setImageType(int value)
```

Ermittelt oder legt den Bildtyp eines Zoom-Objekts fest. Lese-/Schreibzugriff [ZoomImageType](../../com.aspose.slides/zoomimagetype). Standardwert: Preview

--------------------

> ```
> Das nächste Beispiel zeigt das Ändern des Bildtyps auf den Wert Preview. 
>  In diesem Fall wird das aktuelle Bild eines Zoom-Objekts in das Folienbild geändert:
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

Gibt an, ob das Zoom-Objekt die Folienvorschau oder ein Titelbild verwendet.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getReturnToParent() {#getReturnToParent--}
```
public final boolean getReturnToParent()
```

Ermittelt oder legt das Navigationsverhalten in der Diashow fest. Lese-/Schreibzugriff boolean. Standardwert: false

--------------------

> ```
> Beispiel:
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

Der wahre Wert der Eigenschaft gibt das Rückkehr-zu-Eltern-Navigationsverhalten in der Diashow an.

**Rückgabewert:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public final void setReturnToParent(boolean value)
```

Ermittelt oder legt das Navigationsverhalten in der Diashow fest. Lese-/Schreibzugriff boolean. Standardwert: false

--------------------

> ```
> Beispiel:
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

Der wahre Wert der Eigenschaft gibt das Rückkehr-zu-Eltern-Navigationsverhalten in der Diashow an.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getShowBackground() {#getShowBackground--}
```
public final boolean getShowBackground()
```

Ermittelt oder legt den Wert fest, der angibt, ob das Zoom den Hintergrund der Zielfolie verwendet. Lese-/Schreibzugriff boolean. Standardwert: true

--------------------

> ```
> Das Beispiel zeigt das Entfernen des Hintergrunds eines Bildes eines Zoom-Objekts:
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

Ermittelt oder legt den Wert fest, der angibt, ob das Zoom den Hintergrund der Zielfolie verwendet. Lese-/Schreibzugriff boolean. Standardwert: true

--------------------

> ```
> Das Beispiel zeigt das Entfernen des Hintergrunds eines Bildes eines Zoom-Objekts:
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

Ermittelt oder legt das Bild für das Zoom-Objekt fest. Lese-/Schreibzugriff [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> Das Beispiel zeigt das Ändern eines Bildes eines Zoom-Objekts:
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
public final void setZoomImage(IPPImage value)
```

Ermittelt oder legt das Bild für das Zoom-Objekt fest. Lese-/Schreibzugriff [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> Das Beispiel zeigt das Ändern eines Bildes eines Zoom-Objekts:
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
public final float getTransitionDuration()
```

Ermittelt oder legt die Dauer des Übergangs zwischen Zoom und Folie fest. Lese-/Schreibzugriff float. Standardwert: 1.0f

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

Wenn nicht angegeben (TransitionDur = 0), wird die Übergangsanimation der Zielfolie und die mit diesem Übergang verbundenen Zeiten verwendet.

**Rückgabewert:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public final void setTransitionDuration(float value)
```

Ermittelt oder legt die Dauer des Übergangs zwischen Zoom und Folie fest. Lese-/Schreibzugriff float. Standardwert: 1.0f

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

Wenn nicht angegeben (TransitionDur = 0), wird die Übergangsanimation der Zielfolie und die mit diesem Übergang verbundenen Zeiten verwendet.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |