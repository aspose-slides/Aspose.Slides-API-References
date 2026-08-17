---
title: ZoomObject
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente un objet Zoom dans une diapositive.
type: docs
url: /fr/com.aspose.slides/zoomobject/
---
**Héritage:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Toutes les interfaces implémentées:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public class ZoomObject extends GraphicalObject implements IZoomObject
```

Représente un objet Zoom dans une diapositive.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getImageType()](#getImageType--) | Obtient ou définit le type d'image d'un objet Zoom. |
| [setImageType(int value)](#setImageType-int-) | Obtient ou définit le type d'image d'un objet Zoom. |
| [getReturnToParent()](#getReturnToParent--) | Obtient ou définit le comportement de navigation dans le diaporama. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Obtient ou définit le comportement de navigation dans le diaporama. |
| [getShowBackground()](#getShowBackground--) | Obtient ou définit la valeur qui indique si le Zoom utilise l'arrière-plan de la diapositive de destination. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Obtient ou définit la valeur qui indique si le Zoom utilise l'arrière-plan de la diapositive de destination. |
| [getZoomImage()](#getZoomImage--) | Obtient ou définit l'image pour l'objet Zoom. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Obtient ou définit l'image pour l'objet Zoom. |
| [getTransitionDuration()](#getTransitionDuration--) | Obtient ou définit la durée de la transition entre le Zoom et la diapositive. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Obtient ou définit la durée de la transition entre le Zoom et la diapositive. |
### getImageType() {#getImageType--}
```
public final int getImageType()
```

Obtient ou définit le type d'image d'un objet Zoom. Lecture/écriture [ZoomImageType](../../com.aspose.slides/zoomimagetype). Valeur par défaut : Preview

--------------------

> ```
> Le prochain exemple montre comment changer le type d'image à la valeur Preview. 
>  Dans ce cas, l'image actuelle d'un objet Zoom change en image de la diapositive:
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

Indique si l'objet Zoom utilise l'aperçu de la diapositive ou une image de couverture.

**Retourne :**
int
### setImageType(int value) {#setImageType-int-}
```
public final void setImageType(int value)
```

Obtient ou définit le type d'image d'un objet Zoom. Lecture/écriture [ZoomImageType](../../com.aspose.slides/zoomimagetype). Valeur par défaut : Preview

--------------------

> ```
> Le prochain exemple montre comment changer le type d'image à la valeur Preview. 
>  Dans ce cas, l'image actuelle d'un objet Zoom change en image de la diapositive:
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

Indique si l'objet Zoom utilise l'aperçu de la diapositive ou une image de couverture.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getReturnToParent() {#getReturnToParent--}
```
public final boolean getReturnToParent()
```

Obtient ou définit le comportement de navigation dans le diaporama. Lecture/écriture booléen. Valeur par défaut : false

--------------------

> ```
> Exemple:
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

**Retourne :**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public final void setReturnToParent(boolean value)
```

Obtient ou définit le comportement de navigation dans le diaporama. Lecture/écriture booléen. Valeur par défaut : false

--------------------

> ```
> Exemple:
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
public final boolean getShowBackground()
```

Obtient ou définit la valeur qui indique si le Zoom utilise l'arrière-plan de la diapositive de destination. Lecture/écriture booléen. Valeur par défaut : true

--------------------

> ```
> l'exemple montre la suppression de l'arrière-plan d'une image d'un objet Zoom :
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourne :**
boolean
### setShowBackground(boolean value) {#setShowBackground-boolean-}
```
public final void setShowBackground(boolean value)
```

Obtient ou définit la valeur qui indique si le Zoom utilise l'arrière-plan de la diapositive de destination. Lecture/écriture booléen. Valeur par défaut : true

--------------------

> ```
> l'exemple montre la suppression de l'arrière-plan d'une image d'un objet Zoom :
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
public final IPPImage getZoomImage()
```

Obtient ou définit l'image pour l'objet Zoom. Lecture/écriture [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> l'exemple montre comment changer l'image d'un objet Zoom :
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

**Retourne :**
[IPPImage](../../com.aspose.slides/ippimage)
### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public final void setZoomImage(IPPImage value)
```

Obtient ou définit l'image pour l'objet Zoom. Lecture/écriture [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> l'exemple montre comment changer l'image d'un objet Zoom :
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
public final float getTransitionDuration()
```

Obtient ou définit la durée de la transition entre le Zoom et la diapositive. Lecture/écriture float. Valeur par défaut : 1.0f

--------------------

> ```
> l'exemple montre comment changer la durée de la transition entre le Zoom et la diapositive :
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

Si non spécifié (TransitionDur = 0), il utilisera la transition de la diapositive de destination ainsi que les durées associées à cette transition.

**Retourne :**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public final void setTransitionDuration(float value)
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

Si non spécifié (TransitionDur = 0), il utilisera la transition de la diapositive de destination ainsi que les durées associées à cette transition.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |