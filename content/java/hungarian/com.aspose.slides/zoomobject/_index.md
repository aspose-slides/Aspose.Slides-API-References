---
title: ZoomObject
second_title: Aspose.Slides Java API hivatkozás
description: Egy Zoom objektumot képvisel egy dián.
type: docs
url: /hu/com.aspose.slides/zoomobject/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Minden megvalósított interfész:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public class ZoomObject extends GraphicalObject implements IZoomObject
```

Egy Zoom objektumot képvisel egy dián.
## Módszerek

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
public final int getImageType()
```

Lekéri vagy beállítja a zoom objektum kép típusát. Olvasás/írás [ZoomImageType](../../com.aspose.slides/zoomimagetype). Alapértelmezett érték: Preview

--------------------

> ```
> A következő példa bemutatja a Kép Típusának Preview értékre való módosítását.
>  Ebben az esetben a Zoom objektum aktuális képe a diakép lesz:
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

Megadja, hogy a Zoom objektum a dia előnézetet vagy egy borítóképet használ-e.

**Visszatérési érték:**
int
### setImageType(int value) {#setImageType-int-}
```
public final void setImageType(int value)
```

Lekéri vagy beállítja a zoom objektum kép típusát. Olvasás/írás [ZoomImageType](../../com.aspose.slides/zoomimagetype). Alapértelmezett érték: Preview

--------------------

> ```
> A következő példa bemutatja a Kép Típusának Preview értékre módosítását. 
>  Ebben az esetben a Zoom objektum aktuális képe diaképre változik:
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

Megadja, hogy a Zoom objektum a dia előnézetet vagy egy borítóképet használ-e.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getReturnToParent() {#getReturnToParent--}
```
public final boolean getReturnToParent()
```

Lekéri vagy beállítja a navigációs viselkedést a diavetítésben. Olvasás/írás boolean. Alapértelmezett érték: false

--------------------

> ```
> Példa:
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

A tulajdonság true értéke a szülőre való visszatérést jelöli a diavetítésben.

**Visszatérési érték:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public final void setReturnToParent(boolean value)
```

Lekéri vagy beállítja a navigációs viselkedést a diavetítésben. Olvasás/írás boolean. Alapértelmezett érték: false

--------------------

> ```
> Példa:
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

A tulajdonság true értéke a szülőre való visszatérést jelöli a diavetítésben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getShowBackground() {#getShowBackground--}
```
public final boolean getShowBackground()
```

Lekéri vagy beállítja azt az értéket, amely meghatározza, hogy a Zoom használja-e a cél dia háttérét. Olvasás/írás boolean. Alapértelmezett érték: true

--------------------

> ```
> A példa bemutatja egy Zoom objektum képének háttér eltávolítását:
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
public final void setShowBackground(boolean value)
```

Lekéri vagy beállítja azt az értéket, amely meghatározza, hogy a Zoom használja-e a cél dia háttérét. Olvasás/írás boolean. Alapértelmezett érték: true

--------------------

> ```
> A példa bemutatja egy Zoom objektum képének háttér eltávolítását:
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
public final IPPImage getZoomImage()
```

Lekéri vagy beállítja a zoom objektum képét. Olvasás/írás [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> A példa bemutatja egy Zoom objektum képének megváltoztatását:
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
public final void setZoomImage(IPPImage value)
```

Lekéri vagy beállítja a zoom objektum képét. Olvasás/írás [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> A példa bemutatja egy Zoom objektum képének megváltoztatását:
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
public final float getTransitionDuration()
```

Lekéri vagy beállítja a Zoom és a dia közötti átmenet időtartamát. Olvasás/írás float. Alapértelmezett érték: 1.0f

--------------------

> ```
> A példa bemutatja a Zoom és a dia közötti átmenet időtartamának módosítását:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

Ha nincs megadva (TransitionDur = 0), akkor a cél dia átmenetét és az ahhoz kapcsolódó időzítést használja.

**Visszatérési érték:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public final void setTransitionDuration(float value)
```

Lekéri vagy beállítja a Zoom és a dia közötti átmenet időtartamát. Olvasás/írás float. Alapértelmezett érték: 1.0f

--------------------

> ```
> A példa bemutatja a Zoom és a dia közötti átmenet időtartamának módosítását:
>  
  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

Ha nincs megadva (TransitionDur = 0), akkor a cél dia átmenetét és az ahhoz kapcsolódó időzítést használja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |