---
title: IZoomObject
second_title: Aspose.Slides Java API hivatkozás
description: Egy Zoom objektumot képvisel egy diában.
type: docs
url: /hu/com.aspose.slides/izoomobject/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IZoomObject extends IGraphicalObject
```

Egy Zoom objektumot képvisel egy diában.
## Metódusok

| Módszer | Leírás |
| --- | --- |
| [getImageType()](#getImageType--) | Lekéri vagy beállítja a zoom objektum kép típusát. |
| [setImageType(int value)](#setImageType-int-) | Lekéri vagy beállítja a zoom objektum kép típusát. |
| [getReturnToParent()](#getReturnToParent--) | Lekéri vagy beállítja a navigációs viselkedést a diavetítésben. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Lekéri vagy beállítja a navigációs viselkedést a diavetítésben. |
| [getShowBackground()](#getShowBackground--) | Lekéri vagy beállítja azt az értéket, amely meghatározza, hogy a Zoom használja-e a cél dia háttérét. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Lekéri vagy beállítja azt az értéket, amely meghatározza, hogy a Zoom használja-e a cél dia háttérét. |
| [getZoomImage()](#getZoomImage--) | Lekéri vagy beállítja a zoom objektum képét. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Lekéri vagy beállítja a zoom objektum képét. |
| [getTransitionDuration()](#getTransitionDuration--) | Lekéri vagy beállítja a Zoom és a dia közötti átmenet időtartamát. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Lekéri vagy beállítja a Zoom és a dia közötti átmenet időtartamát. |
### getImageType() {#getImageType--}
```
public abstract int getImageType()
```

Lekéri vagy beállítja a zoom objektum kép típusát. Olvasás/írás [ZoomImageType](../../com.aspose.slides/zoomimagetype). Alapértelmezett érték: Preview

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

Megadja, hogy a Zoom objektum a dia előnézetét vagy egy borítóképét használja-e.

**Visszatérési érték:**
int
### setImageType(int value) {#setImageType-int-}
```
public abstract void setImageType(int value)
```

Lekéri vagy beállítja a zoom objektum kép típusát. Olvasás/írás [ZoomImageType](../../com.aspose.slides/zoomimagetype). Alapértelmezett érték: Preview

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

Megadja, hogy a Zoom objektum a dia előnézetét vagy egy borítóképét használja-e.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getReturnToParent() {#getReturnToParent--}
```
public abstract boolean getReturnToParent()
```

Lekéri vagy beállítja a navigációs viselkedést a diavetítésben. Olvasás/írás boolean. Alapértelmezett érték: false

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

Az igaz érték azt jelzi, hogy a tulajdonság visszatérési viselkedést a szülőhöz határoz meg a diavetítésben.

**Visszatérési érték:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public abstract void setReturnToParent(boolean value)
```

Lekéri vagy beállítja a navigációs viselkedést a diavetítésben. Olvasás/írás boolean. Alapértelmezett érték: false

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

Az igaz érték azt jelzi, hogy a tulajdonság visszatérési viselkedést a szülőhöz határoz meg a diavetítésben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowBackground() {#getShowBackground--}
```
public abstract boolean getShowBackground()
```

Lekéri vagy beállítja azt az értéket, amely meghatározza, hogy a Zoom használja-e a cél dia háttérét. Olvasás/írás boolean. Alapértelmezett érték: true

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


**Visszatérési érték:**
boolean
### setShowBackground(boolean value) {#setShowBackground-boolean-}
```
public abstract void setShowBackground(boolean value)
```

Lekéri vagy beállítja azt az értéket, amely meghatározza, hogy a Zoom használja-e a cél dia háttérét. Olvasás/írás boolean. Alapértelmezett érték: true

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getZoomImage() {#getZoomImage--}
```
public abstract IPPImage getZoomImage()
```

Lekéri vagy beállítja a zoom objektum képét. Olvasás/írás [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> The example demonstrates changing an image of a Zoom object:
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


**Visszatérési érték:**
[IPPImage](../../com.aspose.slides/ippimage)
### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public abstract void setZoomImage(IPPImage value)
```

Lekéri vagy beállítja a zoom objektum képét. Olvasás/írás [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> The example demonstrates changing an image of a Zoom object:
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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getTransitionDuration() {#getTransitionDuration--}
```
public abstract float getTransitionDuration()
```

Lekéri vagy beállítja a Zoom és a dia közötti átmenet időtartamát. Olvasás/írás float. Alapértelmezett érték: 1.0f

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

Ha nincs megadva (TransitionDur = 0), akkor a cél dia átmenetét és a hozzá tartozó időzítéseket fogja használni.

**Visszatérési érték:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public abstract void setTransitionDuration(float value)
```

Lekéri vagy beállítja a Zoom és a dia közötti átmenet időtartamát. Olvasás/írás float. Alapértelmezett érték: 1.0f

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

Ha nincs megadva (TransitionDur = 0), akkor a cél dia átmenetét és a hozzá tartozó időzítéseket fogja használni.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |