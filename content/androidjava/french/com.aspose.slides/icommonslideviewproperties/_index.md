---
title: ICommonSlideViewProperties
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente les propriétés communes de la vue de diapositive.
type: docs
url: /fr/com.aspose.slides/icommonslideviewproperties/
---```
public interface ICommonSlideViewProperties
```

Représente les propriétés communes de la vue de diapositive.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getScale()](#getScale--) | Spécifie le taux de mise à l'échelle de la vue en pourcentages. |
| [setScale(int value)](#setScale-int-) | Spécifie le taux de mise à l'échelle de la vue en pourcentages. |
| [getVariableScale()](#getVariableScale--) | Spécifie que le contenu de la vue doit être automatiquement mis à l'échelle pour s'adapter au mieux à la taille actuelle de la fenêtre. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Spécifie que le contenu de la vue doit être automatiquement mis à l'échelle pour s'adapter au mieux à la taille actuelle de la fenêtre. |
| [getDrawingGuides()](#getDrawingGuides--) | Renvoie la collection des guides de dessin. |
### getScale() {#getScale--}
```
public abstract int getScale()
```


Spécifie le taux de mise à l'échelle de la vue en pourcentages. Lecture/écriture int.

**Renvoie:**  
int
### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```


Spécifie le taux de mise à l'échelle de la vue en pourcentages. Lecture/écriture int.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public abstract boolean getVariableScale()
```


Spécifie que le contenu de la vue doit être automatiquement mis à l'échelle pour s'adapter au mieux à la taille actuelle de la fenêtre. Lecture/écriture boolean.

**Renvoie:**  
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public abstract void setVariableScale(boolean value)
```


Spécifie que le contenu de la vue doit être automatiquement mis à l'échelle pour s'adapter au mieux à la taille actuelle de la fenêtre. Lecture/écriture boolean.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


Renvoie la collection des guides de dessin. Lecture seule [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // Adding the new vertical drawing guide to the right of the slide center
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth() / 2) + 12.5f);
>      // Adding the new horizontal drawing guide below the slide center
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Renvoie:**  
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)