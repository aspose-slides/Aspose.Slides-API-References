---
title: IZoomObject
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta un oggetto Zoom in una diapositiva.
type: docs
url: /it/com.aspose.slides/izoomobject/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IZoomObject extends IGraphicalObject
```

Rappresenta un oggetto Zoom in una diapositiva.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getImageType()](#getImageType--) | Ottiene o imposta il tipo di immagine di un oggetto Zoom. |
| [setImageType(int value)](#setImageType-int-) | Ottiene o imposta il tipo di immagine di un oggetto Zoom. |
| [getReturnToParent()](#getReturnToParent--) | Ottiene o imposta il comportamento di navigazione nella presentazione. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Ottiene o imposta il comportamento di navigazione nella presentazione. |
| [getShowBackground()](#getShowBackground--) | Ottiene o imposta il valore che specifica se lo Zoom utilizzerà lo sfondo della diapositiva di destinazione. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Ottiene o imposta il valore che specifica se lo Zoom utilizzerà lo sfondo della diapositiva di destinazione. |
| [getZoomImage()](#getZoomImage--) | Ottiene o imposta l'immagine per l'oggetto Zoom. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Ottiene o imposta l'immagine per l'oggetto Zoom. |
| [getTransitionDuration()](#getTransitionDuration--) | Ottiene o imposta la durata della transizione tra Zoom e diapositiva. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Ottiene o imposta la durata della transizione tra Zoom e diapositiva. |
### getImageType() {#getImageType--}
```
public abstract int getImageType()
```

Ottiene o imposta il tipo di immagine di un oggetto Zoom. Lettura/scrittura [ZoomImageType](../../com.aspose.slides/zoomimagetype). Valore predefinito: Preview

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

Specifica se l'oggetto Zoom utilizza l'anteprima della diapositiva o un'immagine di copertina.

**Restituisce:**
int
### setImageType(int value) {#setImageType-int-}
```
public abstract void setImageType(int value)
```

Ottiene o imposta il tipo di immagine di un oggetto Zoom. Lettura/scrittura [ZoomImageType](../../com.aspose.slides/zoomimagetype). Valore predefinito: Preview

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

Specifica se l'oggetto Zoom utilizza l'anteprima della diapositiva o un'immagine di copertina.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getReturnToParent() {#getReturnToParent--}
```
public abstract boolean getReturnToParent()
```

Ottiene o imposta il comportamento di navigazione nella presentazione. Lettura/scrittura boolean. Valore predefinito: false

--------------------

> ```
> Esempio:
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

Il valore true della proprietà specifica il comportamento di navigazione ritorno al genitore nella presentazione.

**Restituisce:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public abstract void setReturnToParent(boolean value)
```

Ottiene o imposta il comportamento di navigazione nella presentazione. Lettura/scrittura boolean. Valore predefinito: false

--------------------

> ```
> Esempio:
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

Il valore true della proprietà specifica il comportamento di navigazione ritorno al genitore nella presentazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getShowBackground() {#getShowBackground--}
```
public abstract boolean getShowBackground()
```

Ottiene o imposta il valore che specifica se lo Zoom utilizzerà lo sfondo della diapositiva di destinazione. Lettura/scrittura boolean. Valore predefinito: true

--------------------

> ```
> L'esempio dimostra la rimozione dello sfondo di un'immagine di un oggetto Zoom:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Restituisce:**
boolean
### setShowBackground(boolean value) {#setShowBackground-boolean-}
```
public abstract void setShowBackground(boolean value)
```

Ottiene o imposta il valore che specifica se lo Zoom utilizzerà lo sfondo della diapositiva di destinazione. Lettura/scrittura boolean. Valore predefinito: true

--------------------

> ```
> L'esempio dimostra la rimozione dello sfondo di un'immagine di un oggetto Zoom:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getZoomImage() {#getZoomImage--}
```
public abstract IPPImage getZoomImage()
```

Ottiene o imposta l'immagine per l'oggetto Zoom. Lettura/scrittura [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> L'esempio dimostra la modifica di un'immagine di un oggetto Zoom:
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


**Restituisce:**
[IPPImage](../../com.aspose.slides/ippimage)
### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public abstract void setZoomImage(IPPImage value)
```

Ottiene o imposta l'immagine per l'oggetto Zoom. Lettura/scrittura [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> L'esempio dimostra la modifica di un'immagine di un oggetto Zoom:
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


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getTransitionDuration() {#getTransitionDuration--}
```
public abstract float getTransitionDuration()
```

Ottiene o imposta la durata della transizione tra Zoom e diapositiva. Lettura/scrittura float. Valore predefinito: 1.0f

--------------------

> ```
> l'esempio dimostra la modifica della durata della transizione tra Zoom e diapositiva:
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

Se non specificato (TransitionDur = 0), verrà utilizzata la transizione della diapositiva di destinazione e i tempi associati a quella transizione.

**Restituisce:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public abstract void setTransitionDuration(float value)
```

Ottiene o imposta la durata della transizione tra Zoom e diapositiva. Lettura/scrittura float. Valore predefinito: 1.0f

--------------------

> ```
> l'esempio dimostra la modifica della durata della transizione tra Zoom e diapositiva:
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

Se non specificato (TransitionDur = 0), verrà utilizzata la transizione della diapositiva di destinazione e i tempi associati a quella transizione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |