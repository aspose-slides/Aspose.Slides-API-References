---
title: ISmartArt
second_title: Référence de l'API Aspose.Slides pour Java
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
| [getAllNodes()](#getAllNodes--) | Retourne les collections de tous les nœuds dans l'objet SmartArt. |
| [getNodes()](#getNodes--) | Retourne les collections de nœuds racine dans l'objet SmartArt. |
| [getLayout()](#getLayout--) | Retourne ou définit la disposition de l'objet SmartArt. |
| [setLayout(int value)](#setLayout-int-) | Retourne ou définit la disposition de l'objet SmartArt. |
| [getQuickStyle()](#getQuickStyle--) | Retourne ou définit le style rapide de l'objet SmartArt. |
| [setQuickStyle(int value)](#setQuickStyle-int-) | Retourne ou définit le style rapide de l'objet SmartArt. |
| [getColorStyle()](#getColorStyle--) | Retourne ou définit le style de couleur de l'objet SmartArt. |
| [setColorStyle(int value)](#setColorStyle-int-) | Retourne ou définit le style de couleur de l'objet SmartArt. |
| [isReversed()](#isReversed--) | Retourne ou définit l'état du diagramme SmartArt par rapport à (de gauche à droite) LTR ou (de droite à gauche) RTL, si le diagramme prend en charge l'inversion. |
| [setReversed(boolean value)](#setReversed-boolean-) | Retourne ou définit l'état du diagramme SmartArt par rapport à (de gauche à droite) LTR ou (de droite à gauche) RTL, si le diagramme prend en charge l'inversion. |

### getAllNodes() {#getAllNodes--}
```
public abstract ISmartArtNodeCollection getAllNodes()
```

Retourne les collections de tous les nœuds dans l'objet SmartArt. Lecture seule [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Retourne :**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)

### getNodes() {#getNodes--}
```
public abstract ISmartArtNodeCollection getNodes()
```

Retourne les collections de nœuds racine dans l'objet SmartArt. Lecture seule [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Retourne :**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)

### getLayout() {#getLayout--}
```
public abstract int getLayout()
```

Retourne ou définit la disposition de l'objet SmartArt. Lecture/écriture [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Retourne :**
int

### setLayout(int value) {#setLayout-int-}
```
public abstract void setLayout(int value)
```

Retourne ou définit la disposition de l'objet SmartArt. Lecture/écriture [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getQuickStyle() {#getQuickStyle--}
```
public abstract int getQuickStyle()
```

Retourne ou définit le style rapide de l'objet SmartArt. Lecture/écriture [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Retourne :**
int

### setQuickStyle(int value) {#setQuickStyle-int-}
```
public abstract void setQuickStyle(int value)
```

Retourne ou définit le style rapide de l'objet SmartArt. Lecture/écriture [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getColorStyle() {#getColorStyle--}
```
public abstract int getColorStyle()
```

Retourne ou définit le style de couleur de l'objet SmartArt. Lecture/écriture [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Retourne :**
int

### setColorStyle(int value) {#setColorStyle-int-}
```
public abstract void setColorStyle(int value)
```

Retourne ou définit le style de couleur de l'objet SmartArt. Lecture/écriture [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### isReversed() {#isReversed--}
```
public abstract boolean isReversed()
```

Retourne ou définit l'état du diagramme SmartArt par rapport à (de gauche à droite) LTR ou (de droite à gauche) RTL, si le diagramme prend en charge l'inversion. Lecture/écriture booléen.

**Retourne :**
boolean

### setReversed(boolean value) {#setReversed-boolean-}
```
public abstract void setReversed(boolean value)
```

Retourne ou définit l'état du diagramme SmartArt par rapport à (de gauche à droite) LTR ou (de droite à gauche) RTL, si le diagramme prend en charge l'inversion. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |