---
title: ViewProperties
second_title: Référence de l'API Java via Android d'Aspose.Slides
description: Propriétés de la vue à l’échelle de la présentation.
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

Propriétés de la vue à l’échelle de la présentation.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLastView()](#getLastView--) | Spécifie le mode de vue qui a été utilisé lorsque le document de présentation a été enregistré pour la dernière fois. |
| [setLastView(int value)](#setLastView-int-) | Spécifie le mode de vue qui a été utilisé lorsque le document de présentation a été enregistré pour la dernière fois. |
| [getShowComments()](#getShowComments--) | Indique si les commentaires de la diapositive doivent être affichés. |
| [setShowComments(byte value)](#setShowComments-byte-) | Indique si les commentaires de la diapositive doivent être affichés. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Représente les propriétés de la vue normale. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Spécifie les propriétés de vue communes associées au mode de vue diapositive. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Spécifie les propriétés de vue communes associées au mode de vue notes. |
| [getGridSpacing()](#getGridSpacing--) | Retourne ou définit l’espacement de la grille qui doit être utilisé pour la grille sous-jacente du document de présentation, en points. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Retourne ou définit l’espacement de la grille qui doit être utilisé pour la grille sous-jacente du document de présentation, en points. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getLastView() {#getLastView--}
```
public final int getLastView()
```

Spécifie le mode de vue qui a été utilisé lorsque le document de présentation a été enregistré pour la dernière fois. Lecture/écriture [ViewType](../../com.aspose.slides/viewtype).

**Retour :**
int
### setLastView(int value) {#setLastView-int-}
```
public final void setLastView(int value)
```

Spécifie le mode de vue qui a été utilisé lorsque le document de présentation a été enregistré pour la dernière fois. Lecture/écriture [ViewType](../../com.aspose.slides/viewtype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getShowComments() {#getShowComments--}
```
public final byte getShowComments()
```

Indique si les commentaires de la diapositive doivent être affichés. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Retour :**
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

Représente les propriétés de la vue normale. La vue normale comprend trois zones de contenu : la diapositive elle-même, une zone de contenu latérale et une zone de contenu inférieure. Lecture seule [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Retour :**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getSlideViewProperties() {#getSlideViewProperties--}
```
public final ICommonSlideViewProperties getSlideViewProperties()
```

Spécifie les propriétés de vue communes associées au mode de vue diapositive. Lecture seule [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Retour :**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public final ICommonSlideViewProperties getNotesViewProperties()
```

Spécifie les propriétés de vue communes associées au mode de vue notes. Lecture seule [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Retour :**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public final float getGridSpacing()
```

Retourne ou définit l’espacement de la grille qui doit être utilisé pour la grille sous-jacente du document de présentation, en points. Lecture/écriture float.

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

The grid spacing value must be a positive number . The typical value range is from 1 mm (2.8349607 points) to 2 inches (144 points).

**Returns:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public final void setGridSpacing(float value)
```


Returns or sets the grid spacing that should be used for the grid underlying the presentation document, in points. Read/write float.

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

The grid spacing value must be a positive number . The typical value range is from 1 mm (2.8349607 points) to 2 inches (144 points).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()


Retourne l’objet Parent_Immediate. Lecture seule IDOMObject.

**Retour :**
com.aspose.slides.IDOMObject
