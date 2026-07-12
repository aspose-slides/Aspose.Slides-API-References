---
title: IZoomObject
second_title: Aspose.Slides Androidhoz Java API hivatkozással
description: Egy diában lévő Zoom objektumot képvisel.
type: docs
url: /hu/com.aspose.slides/izoomobject/
---
**Minden implementált interfész:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IZoomObject extends IGraphicalObject
```

A Zoom objektum egy dián.

## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getImageType()](#getImageType--) | Megkapja vagy beállítja a Zoom objektum kép típusát. |
| [setImageType(int value)](#setImageType-int-) | Megkapja vagy beállítja a Zoom objektum kép típusát. |
| [getReturnToParent()](#getReturnToParent--) | Megkapja vagy beállítja a navigációs viselkedést a diavetítésben. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Megkapja vagy beállítja a navigációs viselkedést a diavetítésben. |
| [getShowBackground()](#getShowBackground--) | Megkapja vagy beállítja azt az értéket, amely meghatározza, hogy a Zoom a cél dia háttérét használja-e. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Megkapja vagy beállítja azt az értéket, amely meghatározza, hogy a Zoom a cél dia háttérét használja-e. |
| [getZoomImage()](#getZoomImage--) | Megkapja vagy beállítja a Zoom objektum képét. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Megkapja vagy beállítja a Zoom objektum képét. |
| [getTransitionDuration()](#getTransitionDuration--) | Megkapja vagy beállítja a Zoom és a dia közötti átmenet időtartamát. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Megkapja vagy beállítja a Zoom és a dia közötti átmenet időtartamát. |

### getImageType() {#getImageType--}
```
public abstract int getImageType()
```

Megkapja vagy beállítja a Zoom objektum kép típusát. Olvasás/írás [ZoomImageType](../../com.aspose.slides/zoomimagetype). Alapértelmezett érték: Preview

--------------------

> ```
> Ez a példa bemutatja az Image Type előnézet értékre történő módosítását. 
>  Ebben az esetben a Zoom objektum aktuális képe a dia képére változik:
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

Megadja, hogy a Zoom objektum a dia előnézetét vagy egy borítóképét használja-e.

**Visszatérési érték:**
int

### setImageType(int value) {#setImageType-int-}
```
public abstract void setImageType(int value)
```

Megkapja vagy beállítja a Zoom objektum kép típusát. Olvasás/írás [ZoomImageType](../../com.aspose.slides/zoomimagetype). Alapértelmezett érték: Preview

--------------------

> ```
> Ez a példa bemutatja az Image Type előnézet értékre történő módosítását. 
>  Ebben az esetben a Zoom objektum aktuális képe a dia képére változik:
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

Megadja, hogy a Zoom objektum a dia előnézetét vagy egy borítóképét használja-e.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getReturnToParent() {#getReturnToParent--}
```
public abstract boolean getReturnToParent()
```

Megkapja vagy beállítja a navigációs viselkedést a diavetítésben. Olvasás/írás boolean. Alapértelmezett érték: false

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

Az igaz érték azt jelzi, hogy a visszatérés a szülőhöz navigációs viselkedése a diavetítésben.

**Visszatérési érték:**
boolean

### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public abstract void setReturnToParent(boolean value)
```

Megkapja vagy beállítja a navigációs viselkedést a diavetítésben. Olvasás/írás boolean. Alapértelmezett érték: false

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

Az igaz érték azt jelzi, hogy a visszatérés a szülőhöz navigációs viselkedése a diavetítésben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowBackground() {#getShowBackground--}
```
public abstract boolean getShowBackground()
```

Megkapja vagy beállítja azt az értéket, amely meghatározza, hogy a Zoom a cél dia háttérét használja-e. Olvasás/írás boolean. Alapértelmezett érték: true

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
public abstract void setShowBackground(boolean value)
```

Megkapja vagy beállítja azt az értéket, amely meghatározza, hogy a Zoom a cél dia háttérét használja-e. Olvasás/írás boolean. Alapértelmezett érték: true

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
public abstract IPPImage getZoomImage()
```

Megkapja vagy beállítja a Zoom objektum képét. Olvasás/írás [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> A példa bemutatja egy Zoom objektum képének módosítását:
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

**Visszatérési érték:**
[IPPImage](../../com.aspose.slides/ippimage)

### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public abstract void setZoomImage(IPPImage value)
```

Megkapja vagy beállítja a Zoom objektum képét. Olvasás/írás [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> A példa bemutatja egy Zoom objektum képének módosítását:
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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getTransitionDuration() {#getTransitionDuration--}
```
public abstract float getTransitionDuration()
```

Megkapja vagy beállítja a Zoom és a dia közötti átmenet időtartamát. Olvasás/írás float. Alapértelmezett érték: 1.0f

--------------------

> ```
> a példa bemutatja a Zoom és a dia közötti átmenet időtartamának módosítását:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

Ha nincs megadva (TransitionDur = 0), akkor a cél dia átmenetét és az ahhoz kapcsolódó időzítéseket használja.

**Visszatérési érték:**
float

### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public abstract void setTransitionDuration(float value)
```

Megkapja vagy beállítja a Zoom és a dia közötti átmenet időtartamát. Olvasás/írás float. Alapértelmezett érték: 1.0f

--------------------

> ```
> a példa bemutatja a Zoom és a dia közötti átmenet időtartamának módosítását:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

Ha nincs megadva (TransitionDur = 0), akkor a cél dia átmenetét és az ahhoz kapcsolódó időzítéseket használja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |