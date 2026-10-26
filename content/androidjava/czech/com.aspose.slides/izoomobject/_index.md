---
title: IZoomObject
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje objekt Zoom na snímku.
type: docs
url: /cs/com.aspose.slides/izoomobject/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IZoomObject extends IGraphicalObject
```

Represents a Zoom object in a slide.
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

Získá nebo nastaví typ obrázku objektu Zoom. Čtení/zápis [ZoomImageType](../../com.aspose.slides/zoomimagetype). Výchozí hodnota: Preview

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

Určuje, zda objekt Zoom používá náhled snímku nebo obrázek obalu.

**Vrací:**
int
### setImageType(int value) {#setImageType-int-}
```
public abstract void setImageType(int value)
```

Získá nebo nastaví typ obrázku objektu Zoom. Čtení/zápis [ZoomImageType](../../com.aspose.slides/zoomimagetype). Výchozí hodnota: Preview

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

Určuje, zda objekt Zoom používá náhled snímku nebo obrázek obalu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getReturnToParent() {#getReturnToParent--}
```
public abstract boolean getReturnToParent()
```

Získá nebo nastaví chování navigace v prezentaci. Čtení/zápis boolean. Výchozí hodnota: false

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

Hodnota true této vlastnosti určuje návrat k rodičovskému chování navigace v prezentaci.

**Vrací:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public abstract void setReturnToParent(boolean value)
```

Získá nebo nastaví chování navigace v prezentaci. Čtení/zápis boolean. Výchozí hodnota: false

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

Hodnota true této vlastnosti určuje návrat k rodičovskému chování navigace v prezentaci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getShowBackground() {#getShowBackground--}
```
public abstract boolean getShowBackground()
```

Získá nebo nastaví hodnotu, která určuje, zda Zoom použije pozadí cílového snímku. Čtení/zápis boolean. Výchozí hodnota: true

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

**Vrací:**
boolean
### setShowBackground(boolean value) {#setShowBackground-boolean-}
```
public abstract void setShowBackground(boolean value)
```

Získá nebo nastaví hodnotu, která určuje, zda Zoom použije pozadí cílového snímku. Čtení/zápis boolean. Výchozí hodnota: true

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


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getZoomImage() {#getZoomImage--}
```
public abstract IPPImage getZoomImage()
```

Získá nebo nastaví obrázek pro objekt Zoom. Čtení/zápis [IPPImage](../../com.aspose.slides/ippimage).

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

**Vrací:**
[IPPImage](../../com.aspose.slides/ippimage)
### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public abstract void setZoomImage(IPPImage value)
```

Získá nebo nastaví obrázek pro objekt Zoom. Čtení/zápis [IPPImage](../../com.aspose.slides/ippimage).

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


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getTransitionDuration() {#getTransitionDuration--}
```
public abstract float getTransitionDuration()
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

Pokud není specifikováno (TransitionDur = 0), použije se přechod cílového snímku a časování s ním spojené.

**Vrací:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public abstract void setTransitionDuration(float value)
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

Pokud není specifikováno (TransitionDur = 0), použije se přechod cílového snímku a časování s ním spojené.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |