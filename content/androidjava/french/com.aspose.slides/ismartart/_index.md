---
title: ISmartArt
second_title: Aspose.Slides pour Android via la référence d'API Java
description: Représente un diagramme SmartArt.
type: docs
url: /fr/com.aspose.slides/ismartart/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISmartArt extends IGraphicalObject
```

Représente un diagramme SmartArt.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | Renvoie les collections de tous les nœuds de l'objet SmartArt. |
| [getNodes()](#getNodes--) | Renvoie les collections des nœuds racines de l'objet SmartArt. |
| [getLayout()](#getLayout--) | Renvoie ou définit la mise en page de l'objet SmartArt. |
| [setLayout(int value)](#setLayout-int-) | Renvoie ou définit la mise en page de l'objet SmartArt. |
| [getQuickStyle()](#getQuickStyle--) | Renvoie ou définit le style rapide de l'objet SmartArt. |
| [setQuickStyle(int value)](#setQuickStyle-int-) | Renvoie ou définit le style rapide de l'objet SmartArt. |
| [getColorStyle()](#getColorStyle--) | Renvoie ou définit le style de couleur de l'objet SmartArt. |
| [setColorStyle(int value)](#setColorStyle-int-) | Renvoie ou définit le style de couleur de l'objet SmartArt. |
| [isReversed()](#isReversed--) | Renvoie ou définit l'état du diagramme SmartArt concernant le sens de lecture de gauche à droite (LTR) ou de droite à gauche (RTL), si le diagramme prend en charge l'inversion. |
| [setReversed(boolean value)](#setReversed-boolean-) | Renvoie ou définit l'état du diagramme SmartArt concernant le sens de lecture de gauche à droite (LTR) ou de droite à gauche (RTL), si le diagramme prend en charge l'inversion. |
### getAllNodes() {#getAllNodes--}
```
public abstract ISmartArtNodeCollection getAllNodes()
```

Renvoie les collections de tous les nœuds de l'objet SmartArt. Lecture seule [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Retour :**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getNodes() {#getNodes--}
```
public abstract ISmartArtNodeCollection getNodes()
```

Renvoie les collections des nœuds racines de l'objet SmartArt. Lecture seule [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Retour :**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```

Renvoie ou définit la mise en page de l'objet SmartArt. Lecture/écriture [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Retour :**
int
### setLayout(int value) {#setLayout-int-}
```
public abstract void setLayout(int value)
```

Renvoie ou définit la mise en page de l'objet SmartArt. Lecture/écriture [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getQuickStyle() {#getQuickStyle--}
```
public abstract int getQuickStyle()
```

Renvoie ou définit le style rapide de l'objet SmartArt. Lecture/écriture [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Retour :**
int
### setQuickStyle(int value) {#setQuickStyle-int-}
```
public abstract void setQuickStyle(int value)
```

Renvoie ou définit le style rapide de l'objet SmartArt. Lecture/écriture [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getColorStyle() {#getColorStyle--}
```
public abstract int getColorStyle()
```

Renvoie ou définit le style de couleur de l'objet SmartArt. Lecture/écriture [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Retour :**
int
### setColorStyle(int value) {#setColorStyle-int-}
```
public abstract void setColorStyle(int value)
```

Renvoie ou définit le style de couleur de l'objet SmartArt. Lecture/écriture [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### isReversed() {#isReversed--}
```
public abstract boolean isReversed()
```

Renvoie ou définit l'état du diagramme SmartArt concernant le sens de lecture de gauche à droite (LTR) ou de droite à gauche (RTL), si le diagramme prend en charge l'inversion. Lecture/écriture boolean.

**Retour :**
boolean
### setReversed(boolean value) {#setReversed-boolean-}
```
public abstract void setReversed(boolean value)
```

Renvoie ou définit l'état du diagramme SmartArt concernant le sens de lecture de gauche à droite (LTR) ou de droite à gauche (RTL), si le diagramme prend en charge l'inversion. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |