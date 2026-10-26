---
title: ZoomObject
second_title: Riferimento API Java per Aspose.Slides per Android
description: Rappresenta un oggetto Zoom in una diapositiva.
type: docs
url: /it/com.aspose.slides/zoomobject/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Tutte le interfacce implementate:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public class ZoomObject extends GraphicalObject implements IZoomObject
```

Rappresenta un oggetto Zoom in una diapositiva.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getImageType()](#getImageType--) | Ottiene o imposta il tipo di immagine di un oggetto zoom. |
| [setImageType(int value)](#setImageType-int-) | Ottiene o imposta il tipo di immagine di un oggetto zoom. |
| [getReturnToParent()](#getReturnToParent--) | Ottiene o imposta il comportamento di navigazione nella presentazione. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Ottiene o imposta il comportamento di navigazione nella presentazione. |
| [getShowBackground()](#getShowBackground--) | Ottiene o imposta il valore che specifica se lo Zoom utilizzerà lo sfondo della diapositiva di destinazione. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Ottiene o imposta il valore che specifica se lo Zoom utilizzerà lo sfondo della diapositiva di destinazione. |
| [getZoomImage()](#getZoomImage--) | Ottiene o imposta l’immagine per l’oggetto zoom. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Ottiene o imposta l’immagine per l’oggetto zoom. |
| [getTransitionDuration()](#getTransitionDuration--) | Ottiene o imposta la durata della transizione tra Zoom e diapositiva. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Ottiene o imposta la durata della transizione tra Zoom e diapositiva. |
### getImageType() {#getImageType--}
```
public final int getImageType()
```


Ottiene o imposta il tipo di immagine di un oggetto zoom. Lettura/scrittura [ZoomImageType](../../com.aspose.slides/zoomimagetype). Valore predefinito: Preview

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

Specifica se l’oggetto Zoom utilizza l’anteprima della diapositiva o un’immagine di copertina.

**Restituisce:**
int
### setImageType(int value) {#setImageType-int-}
```
public final void setImageType(int value)
```


Ottiene o imposta il tipo di immagine di un oggetto zoom. Lettura/scrittura [ZoomImageType](../../com.aspose.slides/zoomimagetype). Valore predefinito: Preview

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

Specifica se l’oggetto Zoom utilizza l’anteprima della diapositiva o un’immagine di copertina.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getReturnToParent() {#getReturnToParent--}
```
public final boolean getReturnToParent()
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

Il valore true della proprietà specifica il comportamento di ritorno al genitore nella presentazione.

**Restituisce:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public final void setReturnToParent(boolean value)
```


Ottiene o imposta il comportamento di navigazione nella presentazione. Lettura/scrittura boolean. Valore predefinito: false

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

Il valore true della proprietà specifica il comportamento di ritorno al genitore nella presentazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getShowBackground() {#getShowBackground--}
```
public final boolean getShowBackground()
```


Ottiene o imposta il valore che specifica se lo Zoom utilizzerà lo sfondo della diapositiva di destinazione. Lettura/scrittura boolean. Valore predefinito: true

--------------------

> ```
> l'esempio dimostra la rimozione dello sfondo di un'immagine di un oggetto Zoom:
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
public final void setShowBackground(boolean value)
```


Ottiene o imposta il valore che specifica se lo Zoom utilizzerà lo sfondo della diapositiva di destinazione. Lettura/scrittura boolean. Valore predefinito: true

--------------------

> ```
> l'esempio dimostra la rimozione dello sfondo di un'immagine di un oggetto Zoom:
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
public final IPPImage getZoomImage()
```


Ottiene o imposta l’immagine per l’oggetto zoom. Lettura/scrittura [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> l'esempio dimostra come cambiare l'immagine di un oggetto Zoom:
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

**Restituisce:**
[IPPImage](../../com.aspose.slides/ippimage)
### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public final void setZoomImage(IPPImage value)
```


Ottiene o imposta l’immagine per l’oggetto zoom. Lettura/scrittura [IPPImage](../../com.aspose.slides/ippimage).

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getTransitionDuration() {#getTransitionDuration--}
```
public final float getTransitionDuration()
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

Se non specificato (TransitionDur = 0), verrà utilizzata la transizione della diapositiva di destinazione e i tempi associati a tale transizione.

**Restituisce:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public final void setTransitionDuration(float value)
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

Se non specificato (TransitionDur = 0), verrà utilizzata la transizione della diapositiva di destinazione e i tempi associati a tale transizione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |