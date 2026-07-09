---
title: IZoomObject
second_title: Référence de l'API Java d'Aspose.Slides pour Android
description: Représente un objet Zoom dans une diapositive.
type: docs
url: /fr/com.aspose.slides/izoomobject/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IZoomObject extends IGraphicalObject
```

Représente un objet Zoom dans une diapositive.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getImageType()](#getImageType--) | Obtient ou définit le type d'image d'un objet Zoom. |
| [setImageType(int value)](#setImageType-int-) | Obtient ou définit le type d'image d'un objet Zoom. |
| [getReturnToParent()](#getReturnToParent--) | Obtient ou définit le comportement de navigation dans le diaporama. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Obtient ou définit le comportement de navigation dans le diaporama. |
| [getShowBackground()](#getShowBackground--) | Obtient ou définit la valeur qui indique si le Zoom utilisera l'arrière-plan de la diapositive de destination. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Obtient ou définit la valeur qui indique si le Zoom utilisera l'arrière-plan de la diapositive de destination. |
| [getZoomImage()](#getZoomImage--) | Obtient ou définit l'image pour l'objet Zoom. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Obtient ou définit l'image pour l'objet Zoom. |
| [getTransitionDuration()](#getTransitionDuration--) | Obtient ou définit la durée de la transition entre le Zoom et la diapositive. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Obtient ou définit la durée de la transition entre le Zoom et la diapositive. |
### getImageType() {#getImageType--}
```
public abstract int getImageType()
```


Obtient ou définit le type d'image d'un objet Zoom. Lecture/écriture [ZoomImageType](../../com.aspose.slides/zoomimagetype). Valeur par défaut : Preview

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
```
public abstract void setImageType(int value)
```


Gets or sets the image type of a zoom object. Read/write [ZoomImageType](../../com.aspose.slides/zoomimagetype). Default value: Preview

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

Specifies whether the Zoom object is using the slide preview or a cover image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getReturnToParent() {#getReturnToParent--}
```
public abstract boolean getReturnToParent()
```

Gets or sets the navigation behavior in slideshow. Read/write boolean. Default value: false

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

True value of the property specifies return to parent navigation behavior in slideshow.

**Returns:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public abstract void setReturnToParent(boolean value)
```

Gets or sets the navigation behavior in slideshow. Read/write boolean. Default value: false

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

True value of the property specifies return to parent navigation behavior in slideshow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowBackground() {#getShowBackground--}
```
public abstract boolean getShowBackground()
```

Gets or sets value that specifies whether the Zoom will use the background of the destination slide. Read/write boolean. Default value: true

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

**Returns:**
boolean
### setShowBackground(boolean value) {#setShowBackground-boolean-}
```
public abstract void setShowBackground(boolean value)
```

Gets or sets value that specifies whether the Zoom will use the background of the destination slide. Read/write boolean. Default value: true

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZoomImage() {#getZoomImage--}
```
public abstract IPPImage getZoomImage()
```

Gets or sets image for zoom object. Read/write [IPPImage](../../com.aspose.slides/ippimage).

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

**Returns:**
[IPPImage](../../com.aspose.slides/ippimage)
### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public abstract void setZoomImage(IPPImage value)
```

Gets or sets image for zoom object. Read/write [IPPImage](../../com.aspose.slides/ippimage).

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getTransitionDuration() {#getTransitionDuration--}
```
public abstract float getTransitionDuration()
```

Gets or sets the duration of the transition between Zoom and slide. Read/write float. Default value: 1.0f

--------------------

> ```
> the example demonstrates changing the duration of the transition between Zoom and slide:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

If not specified (TransitionDur = 0), it will use the destination slide transition and the timings associated with that transition.

**Returns:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public abstract void setTransitionDuration(float value)


Obtient ou définit la durée de la transition entre le Zoom et la diapositive. Lecture/écriture float. Valeur par défaut : 1.0f

--------------------

> ```
> l'exemple montre comment modifier la durée de la transition entre le Zoom et la diapositive :
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

Si non spécifié (TransitionDur = 0), il utilisera la transition de la diapositive de destination et les durées associées à cette transition.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |