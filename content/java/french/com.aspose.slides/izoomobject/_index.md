---
title: IZoomObject
second_title: Référence de l'API Aspose.Slides pour Java
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
> Cet exemple montre comment changer le type d'image en valeur Preview. 
>  Dans ce cas, l'image actuelle d'un objet Zoom passe à l'image de la diapositive:
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

Spécifie si l'objet Zoom utilise l'aperçu de la diapositive ou une image de couverture.

**Renvoie :**
int
### setImageType(int value) {#setImageType-int-}
```
public abstract void setImageType(int value)
```

Obtient ou définit le type d'image d'un objet Zoom. Lecture/écriture [ZoomImageType](../../com.aspose.slides/zoomimagetype). Valeur par défaut : Preview

--------------------

> ```
> Cet exemple montre comment changer le type d'image à la valeur Preview. 
>  Dans ce cas, l'image actuelle d'un objet Zoom passe à l'image de la diapositive :
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

Spécifie si l'objet Zoom utilise l'aperçu de la diapositive ou une image de couverture.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getReturnToParent() {#getReturnToParent--}
```
public abstract boolean getReturnToParent()
```

Obtient ou définit le comportement de navigation dans le diaporama. Lecture/écriture booléen. Valeur par défaut : false

--------------------

> ```
> Exemple :
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

La valeur true de la propriété indique le comportement de navigation de retour au parent dans le diaporama.

**Renvoie :**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public abstract void setReturnToParent(boolean value)
```

Obtient ou définit le comportement de navigation dans le diaporama. Lecture/écriture booléen. Valeur par défaut : false

--------------------

> ```
> Exemple :
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

La valeur true de la propriété indique le comportement de navigation de retour au parent dans le diaporama.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getShowBackground() {#getShowBackground--}
```
public abstract boolean getShowBackground()
```

Obtient ou définit la valeur qui indique si le Zoom utilisera l'arrière-plan de la diapositive de destination. Lecture/écriture booléen. Valeur par défaut : true

--------------------

> ```
> L'exemple montre la suppression de l'arrière-plan d'une image d'un objet Zoom:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Renvoie :**
boolean
### setShowBackground(boolean value) {#setShowBackground-boolean-}
```
public abstract void setShowBackground(boolean value)
```

Obtient ou définit la valeur qui indique si le Zoom utilisera l'arrière-plan de la diapositive de destination. Lecture/écriture booléen. Valeur par défaut : true

--------------------

> ```
> L'exemple montre la suppression de l'arrière-plan d'une image d'un objet Zoom :
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getZoomImage() {#getZoomImage--}
```
public abstract IPPImage getZoomImage()
```

Obtient ou définit l'image pour l'objet Zoom. Lecture/écriture [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> L'exemple montre le changement d'une image d'un objet Zoom :
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

**Renvoie :**
[IPPImage](../../com.aspose.slides/ippimage)
### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public abstract void setZoomImage(IPPImage value)
```

Obtient ou définit l'image pour l'objet Zoom. Lecture/écriture [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> L'exemple montre le changement d'une image d'un objet Zoom :
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


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getTransitionDuration() {#getTransitionDuration--}
```
public abstract float getTransitionDuration()
```

Obtient ou définit la durée de la transition entre le Zoom et la diapositive. Lecture/écriture float. Valeur par défaut : 1.0f

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

Si non spécifié (TransitionDur = 0), il utilisera la transition de la diapositive de destination ainsi que les minuteries associées à cette transition.

**Renvoie :**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public abstract void setTransitionDuration(float value)
```

Obtient ou définit la durée de la transition entre le Zoom et la diapositive. Lecture/écriture float. Valeur par défaut : 1.0f

--------------------

> ```
> l'exemple montre comment changer la durée de la transition entre le Zoom et la diapositive:
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

Si non spécifié (TransitionDur = 0), il utilisera la transition de la diapositive de destination ainsi que les minuteries associées à cette transition.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |