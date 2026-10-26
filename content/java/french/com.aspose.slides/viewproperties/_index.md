---
title: ViewProperties
second_title: Référence de l'API Aspose.Slides pour Java
description: Propriétés de vue à l'échelle de la présentation.
type: docs
url: /fr/com.aspose.slides/viewproperties/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IViewProperties](../../com.aspose.slides/iviewproperties), com.aspose.slides.IDOMObject
```
public class ViewProperties implements IViewProperties, IDOMObject
```

Propriétés de vue à l’échelle de la présentation.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLastView()](#getLastView--) | Spécifie le mode d’affichage qui a été utilisé lors de la dernière sauvegarde du document de présentation. |
| [setLastView(int value)](#setLastView-int-) | Spécifie le mode d’affichage qui a été utilisé lors de la dernière sauvegarde du document de présentation. |
| [getShowComments()](#getShowComments--) | Indique si les commentaires de la diapositive doivent être affichés. |
| [setShowComments(byte value)](#setShowComments-byte-) | Indique si les commentaires de la diapositive doivent être affichés. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Représente les propriétés de vue normale. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Spécifie les propriétés de vue communes associées au mode de vue diapositive. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Spécifie les propriétés de vue communes associées au mode de vue notes. |
| [getGridSpacing()](#getGridSpacing--) | Renvoie ou définit l’espacement de la grille qui doit être utilisé pour la grille sous-jacente au document de présentation, en points. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Renvoie ou définit l’espacement de la grille qui doit être utilisé pour la grille sous-jacente au document de présentation, en points. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getLastView() {#getLastView--}
```
public final int getLastView()
```

Spécifie le mode d’affichage qui a été utilisé lors de la dernière sauvegarde du document de présentation. Lecture/écriture [ViewType](../../com.aspose.slides/viewtype).

**Renvoie :**
int
### setLastView(int value) {#setLastView-int-}
```
public final void setLastView(int value)
```

Spécifie le mode d’affichage qui a été utilisé lors de la dernière sauvegarde du document de présentation. Lecture/écriture [ViewType](../../com.aspose.slides/viewtype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final byte getShowComments()
```

Indique si les commentaires de la diapositive doivent être affichés. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Renvoie :**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public final void setShowComments(byte value)
```

Indique si les commentaires de la diapositive doivent être affichés. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getNormalViewProperties() {#getNormalViewProperties--}
```
public final INormalViewProperties getNormalViewProperties()
```

Représente les propriétés de vue normale. La vue normale comprend trois zones de contenu : la diapositive elle-même, une zone de contenu latérale et une zone de contenu inférieure. Lecture seule [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Renvoie :**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getSlideViewProperties() {#getSlideViewProperties--}
```
public final ICommonSlideViewProperties getSlideViewProperties()
```

Spécifie les propriétés de vue communes associées au mode de vue diapositive. Lecture seule [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Renvoie :**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public final ICommonSlideViewProperties getNotesViewProperties()
```

Spécifie les propriétés de vue communes associées au mode de vue notes. Lecture seule [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Renvoie :**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public final float getGridSpacing()
```

Renvoie ou définit l’espacement de la grille qui doit être utilisé pour la grille sous-jacente au document de présentation, en points. Lecture/écriture float.

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

La valeur d’espacement de la grille doit être un nombre positif. La plage de valeurs typique va de 1 mm (2,8349607 points) à 2 pouces (144 points).

**Renvoie :**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public final void setGridSpacing(float value)
```

Renvoie ou définit l’espacement de la grille qui doit être utilisé pour la grille sous-jacente au document de présentation, en points. Lecture/écriture float.

--------------------

> ```
> Le code d'exemple suivant montre comment modifier l'espacement de la grille dans une présentation PowerPoint.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

La valeur d’espacement de la grille doit être un nombre positif. La plage de valeurs typique va de 1 mm (2,8349607 points) à 2 pouces (144 points).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Renvoie l’objet Parent_Immediate. Lecture seule IDOMObject.

**Renvoie :**
com.aspose.slides.IDOMObject