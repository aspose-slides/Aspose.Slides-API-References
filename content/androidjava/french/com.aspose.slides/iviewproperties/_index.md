---
title: IViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Propriétés de vue de la présentation.
type: docs
url: /fr/com.aspose.slides/iviewproperties/
---
```
public interface IViewProperties
```

Propriétés de vue de la présentation.
## Méthodes

| Method | Description |
| --- | --- |
| [getLastView()](#getLastView--) | Spécifie le mode de visualisation qui était utilisé lorsque le document de présentation a été enregistré pour la dernière fois. |
| [setLastView(int value)](#setLastView-int-) | Spécifie le mode de visualisation qui était utilisé lorsque le document de présentation a été enregistré pour la dernière fois. |
| [getShowComments()](#getShowComments--) | Spécifie si les commentaires de la diapositive doivent être affichés. |
| [setShowComments(byte value)](#setShowComments-byte-) | Spécifie si les commentaires de la diapositive doivent être affichés. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Spécifie les propriétés de vue communes associées au mode de visualisation des diapositives. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Spécifie les propriétés de vue communes associées au mode de visualisation des notes. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Représente les propriétés de la vue normale. |
| [getGridSpacing()](#getGridSpacing--) | Renvoie ou définit l'espacement de la grille qui doit être utilisé pour la grille sous-jacente au document de présentation, en points. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Renvoie ou définit l'espacement de la grille qui doit être utilisé pour la grille sous-jacente au document de présentation, en points. |
### getLastView() {#getLastView--}
```
public abstract int getLastView()
```

Spécifie le mode de visualisation qui était utilisé lorsque le document de présentation a été enregistré pour la dernière fois. Lecture/écriture [ViewType](../../com.aspose.slides/viewtype).

**Renvoie :**
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

**Renvoie :**
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

Spécifie les propriétés de vue communes associées au mode de visualisation des diapositives. Lecture seule [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Renvoie :**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public abstract ICommonSlideViewProperties getNotesViewProperties()
```

Spécifie les propriétés de vue communes associées au mode de visualisation des notes. Lecture seule [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Renvoie :**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNormalViewProperties() {#getNormalViewProperties--}
```
public abstract INormalViewProperties getNormalViewProperties()
```

Représente les propriétés de la vue normale. La vue normale comprend trois régions de contenu : la diapositive elle-même, une région de contenu latérale et une région de contenu inférieure. Lecture seule [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Renvoie :**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public abstract float getGridSpacing()
```

Renvoie ou définit l'espacement de la grille qui doit être utilisé pour la grille sous-jacente au document de présentation, en points. Lecture/écriture float.

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

La valeur de l'espacement de la grille doit être un nombre positif. La plage de valeurs typiques va de 1 mm (2.8349607 points) à 2 pouces (144 points).

**Returns:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public abstract void setGridSpacing(float value)


Renvoie ou définit l'espacement de la grille qui doit être utilisé pour la grille sous-jacente au document de présentation, en points. Lecture/écriture float.

--------------------

> Le code d'exemple suivant montre comment modifier l'espacement de la grille dans une présentation PowerPoint.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> 

--------------------

L'espacement de la grille doit être un nombre positif. La plage de valeurs typiques s'étend de 1 mm (2,8349607 points) à 2 pouces (144 points).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |