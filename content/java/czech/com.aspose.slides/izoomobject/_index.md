---
title: IZoomObject
second_title: Reference API Aspose.Slides pro Java
description: Představuje objekt Zoom na snímku.
type: docs
url: /cs/com.aspose.slides/izoomobject/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IZoomObject extends IGraphicalObject
```

Představuje objekt Zoom na snímku.
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
public abstract int getImageType()
```


Získá nebo nastaví typ obrázku objektu Zoom. Čtení/Zápis [ZoomImageType](../../com.aspose.slides/zoomimagetype). Výchozí hodnota: Preview

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

Určuje, zda objekt Zoom používá náhled snímku nebo obrázek obalu.

**Vrací:**
int
### setImageType(int value) {#setImageType-int-}
```
public abstract void setImageType(int value)
```


Získá nebo nastaví typ obrázku objektu Zoom. Čtení/Zápis [ZoomImageType](../../com.aspose.slides/zoomimagetype). Výchozí hodnota: Preview

--------------------

> ```
> Tento příklad ukazuje změnu typu obrázku na hodnotu Preview. 
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

Určuje, zda objekt Zoom používá náhled snímku nebo obrázek obalu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getReturnToParent() {#getReturnToParent--}
```
public abstract boolean getReturnToParent()
```


Získá nebo nastaví chování navigace v prezentaci. Čtení/Zápis boolean. Výchozí hodnota: false

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

Hodnota true vlastnosti určuje návrat k nadřazenému navigačnímu chování v prezentaci.

**Vrací:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public abstract void setReturnToParent(boolean value)
```


Získá nebo nastaví chování navigace v prezentaci. Čtení/Zápis boolean. Výchozí hodnota: false

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

Hodnota true vlastnosti určuje návrat k nadřazenému navigačnímu chování v prezentaci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowBackground() {#getShowBackground--}
```
public abstract boolean getShowBackground()
```


Získá nebo nastaví hodnotu, která určuje, zda Zoom použije pozadí cílového snímku. Čtení/Zápis boolean. Výchozí hodnota: true

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
public abstract void setShowBackground(boolean value)
```


Získá nebo nastaví hodnotu, která určuje, zda Zoom použije pozadí cílového snímku. Čtení/Zápis boolean. Výchozí hodnota: true

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
public abstract IPPImage getZoomImage()
```


Získá nebo nastaví obrázek pro objekt Zoom. Čtení/Zápis [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> Příklad ukazuje změnu obrázku objektu Zoom:
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
public abstract void setZoomImage(IPPImage value)
```


Získá nebo nastaví obrázek pro objekt Zoom. Čtení/Zápis [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> Příklad ukazuje změnu obrázku objektu Zoom:
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
public abstract float getTransitionDuration()
```


Získá nebo nastaví dobu trvání přechodu mezi Zoom a snímkem. Čtení/Zápis float. Výchozí hodnota: 1.0f

--------------------

> ```
> Příklad ukazuje změnu trvání přechodu mezi Zoom a snímkem:
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

Pokud není specifikováno (TransitionDur = 0), použije se přechod cílového snímku a časování s ním spojené.

**Vrací:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public abstract void setTransitionDuration(float value)
```


Získá nebo nastaví dobu trvání přechodu mezi Zoom a snímkem. Čtení/Zápis float. Výchozí hodnota: 1.0f

--------------------

> ```
> Příklad ukazuje změnu trvání přechodu mezi Zoom a snímkem:
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

Pokud není specifikováno (TransitionDur = 0), použije se přechod cílového snímku a časování s ním spojené.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |