---
title: ZoomObject
second_title: Aspose.Slides pro Java – referenční příručka API
description: Reprezentuje objekt Zoom na snímku.
type: docs
url: /cs/com.aspose.slides/zoomobject/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public class ZoomObject extends GraphicalObject implements IZoomObject
```

Reprezentuje objekt Zoom na snímku.
## Metody

| Metoda | Popis |
| --- | --- |
| [getImageType()](#getImageType--) | Získá nebo nastaví typ obrázku objektu Zoom. |
| [setImageType(int value)](#setImageType-int-) | Získá nebo nastaví typ obrázku objektu Zoom. |
| [getReturnToParent()](#getReturnToParent--) | Získá nebo nastaví chování navigace v prezentaci. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Získá nebo nastaví chování navigace v prezentaci. |
| [getShowBackground()](#getShowBackground--) | Získá nebo nastaví hodnotu, která určuje, zda Zoom použije pozadí cílového snímku. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Získá nebo nastaví hodnotu, která určuje, zda Zoom použije pozadí cílového snímku. |
| [getZoomImage()](#getZoomImage--) | Získá nebo nastaví obrázek pro objekt Zoom. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Získá nebo nastaví obrázek pro objekt Zoom. |
| [getTransitionDuration()](#getTransitionDuration--) | Získá nebo nastaví dobu trvání přechodu mezi Zoom a snímkem. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Získá nebo nastaví dobu trvání přechodu mezi Zoom a snímkem. |
### getImageType() {#getImageType--}
```
public final int getImageType()
```


Získá nebo nastaví typ obrázku objektu Zoom. Čtení/zápis [ZoomImageType](../../com.aspose.slides/zoomimagetype). Výchozí hodnota: Preview

--------------------

> ```
> Next example demonstrates changing Image Type to Preview value. 
>  In this case current image of a Zoom object changes to slide image:
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

Určuje, zda objekt Zoom používá náhled snímku nebo úvodní obrázek.

**Vrací:**
int
### setImageType(int value) {#setImageType-int-}
```
public final void setImageType(int value)
```


Získá nebo nastaví typ obrázku objektu Zoom. Čtení/zápis [ZoomImageType](../../com.aspose.slides/zoomimagetype). Výchozí hodnota: Preview

--------------------

> ```
> Další příklad ukazuje změnu Image Type na hodnotu Preview. 
>  V tomto případě se aktuální obrázek objektu Zoom změní na obrázek snímku:
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

Určuje, zda objekt Zoom používá náhled snímku nebo úvodní obrázek.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getReturnToParent() {#getReturnToParent--}
```
public final boolean getReturnToParent()
```


Získá nebo nastaví chování navigace v prezentaci. Čtení/zápis boolean. Výchozí hodnota: false

--------------------

> ```
> Příklad:
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

Hodnota true této vlastnosti určuje návrat k nadřazené navigaci v prezentaci.

**Vrací:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public final void setReturnToParent(boolean value)
```


Získá nebo nastaví chování navigace v prezentaci. Čtení/zápis boolean. Výchozí hodnota: false

--------------------

> ```
> Příklad:
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

Hodnota true této vlastnosti určuje návrat k nadřazené navigaci v prezentaci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowBackground() {#getShowBackground--}
```
public final boolean getShowBackground()
```


Získá nebo nastaví hodnotu, která určuje, zda Zoom použije pozadí cílového snímku. Čtení/zápis boolean. Výchozí hodnota: true

--------------------

> ```
> Příklad ukazuje odstranění pozadí obrázku objektu Zoom:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Vrací:**
boolean
### setShowBackground(boolean value) {#setShowBackground-boolean-}
```
public final void setShowBackground(boolean value)
```


Získá nebo nastaví hodnotu, která určuje, zda Zoom použije pozadí cílového snímku. Čtení/zápis boolean. Výchozí hodnota: true

--------------------

> ```
> Příklad ukazuje odstranění pozadí obrázku objektu Zoom:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getZoomImage() {#getZoomImage--}
```
public final IPPImage getZoomImage()
```


Získá nebo nastaví obrázek pro objekt Zoom. Čtení/zápis [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> příklad ukazuje změnu obrázku objektu Zoom:
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

**Vrací:**
[IPPImage](../../com.aspose.slides/ippimage)
### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public final void setZoomImage(IPPImage value)
```


Získá nebo nastaví obrázek pro objekt Zoom. Čtení/zápis [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> příklad ukazuje změnu obrázku objektu Zoom:
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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getTransitionDuration() {#getTransitionDuration--}
```
public final float getTransitionDuration()
```


Získá nebo nastaví dobu trvání přechodu mezi Zoom a snímkem. Čtení/zápis float. Výchozí hodnota: 1.0f

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

Pokud není zadáno (TransitionDur = 0), použije se přechod cílového snímku a časování s ním spojené.

**Vrací:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public final void setTransitionDuration(float value)
```


Získá nebo nastaví dobu trvání přechodu mezi Zoom a snímkem. Čtení/zápis float. Výchozí hodnota: 1.0f

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

Pokud není zadáno (TransitionDur = 0), použije se přechod cílového snímku a časování s ním spojené.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |