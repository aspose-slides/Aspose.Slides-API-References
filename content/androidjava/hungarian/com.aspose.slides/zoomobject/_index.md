---
title: ZoomObject
second_title: Aspose.Slides Androidra a Java API hivatkozás alapján
description: Egy Zoom objektumot képvisel egy dián.
type: docs
url: /hu/com.aspose.slides/zoomobject/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**All Implemented Interfaces:**  
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)  
```
public class ZoomObject extends GraphicalObject implements IZoomObject
```

Egy Zoom objektumot képvisel egy dián.

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getImageType()](#getImageType--) | Lekéri vagy beállítja egy zoom objektum kép típusát. |
| [setImageType(int value)](#setImageType-int-) | Lekéri vagy beállítja egy zoom objektum kép típusát. |
| [getReturnToParent()](#getReturnToParent--) | Lekéri vagy beállítja a navigációs viselkedést a diavetítésben. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Lekéri vagy beállítja a navigációs viselkedést a diavetítésben. |
| [getShowBackground()](#getShowBackground--) | Lekéri vagy beállítja azt az értéket, amely meghatározza, hogy a Zoom használja-e a cél dia háttérét. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Lekéri vagy beállítja azt az értéket, amely meghatározza, hogy a Zoom használja-e a cél dia háttérét. |
| [getZoomImage()](#getZoomImage--) | Lekéri vagy beállítja a zoom objektum képét. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Lekéri vagy beállítja a zoom objektum képét. |
| [getTransitionDuration()](#getTransitionDuration--) | Lekéri vagy beállítja a Zoom és a dia közötti áttűnés időtartamát. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Lekéri vagy beállítja a Zoom és a dia közötti áttűnés időtartamát. |

### getImageType() {#getImageType--}
```
public final int getImageType()
```

Lekéri vagy beállítja egy zoom objektum kép típusát. Olvasás/írás [ZoomImageType](../../com.aspose.slides/zoomimagetype). Alapértelmezett érték: Preview

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

Megadja, hogy a Zoom objektum a dia előnézetet vagy egy borító képet használja-e.

**Visszatérési érték:**  
int

### setImageType(int value) {#setImageType-int-}
```
public final void setImageType(int value)
```

Lekéri vagy beállítja egy zoom objektum kép típusát. Olvasás/írás [ZoomImageType](../../com.aspose.slides/zoomimagetype). Alapértelmezett érték: Preview

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

Megadja, hogy a Zoom objektum a dia előnézetet vagy egy borító képet használja-e.

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

A tulajdonság igaz értéke a szülőhöz való visszatérés navigációs viselkedését határozza meg a diavetítésben.

**Visszatérési érték:**  
boolean

### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public final void setReturnToParent(boolean value)
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

A tulajdonság igaz értéke a szülőhöz való visszatérés navigációs viselkedését határozza meg a diavetítésben.

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
> the example demonstrates removing the background of an image of a Zoom object:
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
> the example demonstrates removing the background of an image of a Zoom object:
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
public final void setZoomImage(IPPImage value)
```

Lekéri vagy beállítja a zoom objektum képét. Olvasás/írás [IPPImage](../../com.aspose.slides/ippimage).

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getTransitionDuration() {#getTransitionDuration--}
```
public final float getTransitionDuration()
```

Lekéri vagy beállítja a Zoom és a dia közötti áttűnés időtartamát. Olvasás/írás float. Alapértelmezett érték: 1.0f

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

If not specified (TransitionDur = 0), it will use the destination slide transition and the timings associated with that transition.

**Visszatérési érték:**  
float

### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public final void setTransitionDuration(float value)
```

Lekéri vagy beállítja a Zoom és a dia közötti áttűnés időtartamát. Olvasás/írás float. Alapértelmezett érték: 1.0f

--------------------

> ```
> a példa bemutatja a Zoom és a dia közötti áttűnés időtartamának módosítását:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

If not specified (TransitionDur = 0), it will use the destination slide transition and the timings associated with that transition.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |