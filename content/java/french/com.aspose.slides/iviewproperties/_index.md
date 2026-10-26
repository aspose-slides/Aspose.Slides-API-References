---
title: IViewProperties
second_title: Aspose.Slides for Java API Reference
description: Propriétés de vue de la présentation.
type: docs
url: /fr/com.aspose.slides/iviewproperties/
---```
public interface IViewProperties
```

Propriétés de vue de la présentation.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLastView()](#getLastView--) | Specifies the view mode that was used when the presentation document was last saved. |
| [setLastView(int value)](#setLastView-int-) | Specifies the view mode that was used when the presentation document was last saved. |
| [getShowComments()](#getShowComments--) | Specifies whether the slide comments should be shown. |
| [setShowComments(byte value)](#setShowComments-byte-) | Specifies whether the slide comments should be shown. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Specifies common view properties associated with the slide view mode. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Specifies common view properties associated with the notes view mode. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Represents normal view properties. |
| [getGridSpacing()](#getGridSpacing--) | Returns or sets the grid spacing that should be used for the grid underlying the presentation document, in points. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Returns or sets the grid spacing that should be used for the grid underlying the presentation document, in points. |
### getLastView() {#getLastView--}
```
public abstract int getLastView()
```

Spécifie le mode de visualisation qui était utilisé lorsque le document de présentation a été enregistré pour la dernière fois. Lecture/écriture [ViewType](../../com.aspose.slides/viewtype).

**Retour :**
int
### setLastView(int value) {#setLastView-int-}
```
public abstract void setLastView(int value)
```

Spécifie le mode de visualisation qui était utilisé lorsque le document de présentation a été enregistré pour la dernière fois. Lecture/écriture [ViewType](../../com.aspose.slides/viewtype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public abstract byte getShowComments()
```

Spécifie si les commentaires de la diapositive doivent être affichés. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Retour :**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public abstract void setShowComments(byte value)
```

Spécifie si les commentaires de la diapositive doivent être affichés. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getSlideViewProperties() {#getSlideViewProperties--}
```
public abstract ICommonSlideViewProperties getSlideViewProperties()
```

Spécifie les propriétés de vue communes associées au mode de vue des diapositives. Lecture seule [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Retour :**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public abstract ICommonSlideViewProperties getNotesViewProperties()
```

Spécifie les propriétés de vue communes associées au mode de vue des notes. Lecture seule [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Retour :**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNormalViewProperties() {#getNormalViewProperties--}
```
public abstract INormalViewProperties getNormalViewProperties()
```

Représente les propriétés de la vue normale. La vue normale comprend trois régions de contenu : la diapositive elle-même, une région de contenu latérale et une région de contenu inférieure. Lecture seule [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Retour :**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public abstract float getGridSpacing()
```

Renvoie ou définit l'espacement de la grille qui doit être utilisé pour la grille sous-jacente au document de présentation, en points. Lecture/écriture float.

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

La valeur de l'espacement de la grille doit être un nombre positif. La plage de valeurs typique est de 1 mm (2.8349607 points) à 2 pouces (144 points).

**Retour :**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public abstract void setGridSpacing(float value)
```

Renvoie ou définit l'espacement de la grille qui doit être utilisé pour la grille sous-jacente au document de présentation, en points. Lecture/écriture float.

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

La valeur de l'espacement de la grille doit être un nombre positif. La plage de valeurs typique est de 1 mm (2.8349607 points) à 2 pouces (144 points).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |