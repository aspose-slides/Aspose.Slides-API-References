---
title: CommonSlideViewProperties
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente les propriétés communes de la vue de diapositive.
type: docs
url: /fr/com.aspose.slides/commonslideviewproperties/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
```
public class CommonSlideViewProperties implements ICommonSlideViewProperties
```

Représente les propriétés courantes de la vue de diapositive.

--------------------

> ```
> The following example shows how to set the zoom value for slide of PowerPoint Presentation.
>  
>  // Instancier un objet Presentation qui représente un fichier de présentation
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Définition des propriétés de vue de la présentation
>      pres.getViewProperties().getSlideViewProperties().setScale(100); // Valeur du zoom en pourcentage pour la vue diapositive
>      pres.getViewProperties().getNotesViewProperties().setScale(100); // Valeur du zoom en pourcentage pour la vue des notes
>      pres.save("Zoom_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Méthodes

| Méthode | Description |
| --- | --- |
| [getScale()](#getScale--) | Spécifie le ratio de mise à l'échelle de la vue en pourcentage. |
| [setScale(int value)](#setScale-int-) | Spécifie le ratio de mise à l'échelle de la vue en pourcentage. |
| [getVariableScale()](#getVariableScale--) | Spécifie que le contenu de la vue doit s'adapter automatiquement pour s'ajuster au mieux à la taille actuelle de la fenêtre. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Spécifie que le contenu de la vue doit s'adapter automatiquement pour s'ajuster au mieux à la taille actuelle de la fenêtre. |
| [getDrawingGuides()](#getDrawingGuides--) | Renvoie la collection des guides de dessin. |
### getScale() {#getScale--}
```
public final int getScale()
```

Spécifie le ratio de mise à l'échelle de la vue en pourcentage. Lecture/écriture int.

**Renvoie :**
int
### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```

Spécifie le ratio de mise à l'échelle de la vue en pourcentage. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public final boolean getVariableScale()
```

Spécifie que le contenu de la vue doit s'adapter automatiquement pour s'ajuster au mieux à la taille actuelle de la fenêtre. Lecture/écriture boolean.

**Renvoie :**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public final void setVariableScale(boolean value)
```

Spécifie que le contenu de la vue doit s'adapter automatiquement pour s'ajuster au mieux à la taille actuelle de la fenêtre. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Renvoie la collection des guides de dessin. Lecture seule [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // Ajout du nouveau guide de dessin vertical à droite du centre de la diapositive
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth()) / 2 + 12.5f);
>      // Ajout du nouveau guide de dessin horizontal sous le centre de la diapositive
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Renvoie :**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)