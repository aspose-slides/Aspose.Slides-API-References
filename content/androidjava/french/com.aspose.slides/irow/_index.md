---
title: IRow
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente une ligne dans un tableau.
type: docs
url: /fr/com.aspose.slides/irow/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IRow extends ICellCollection, IBulkTextFormattable
```

Représente une ligne dans un tableau.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getHeight()](#getHeight--) | Renvoie la hauteur d'une ligne. |
| [getMinimalHeight()](#getMinimalHeight--) | Renvoie ou définit la hauteur minimale possible d'une ligne. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Renvoie ou définit la hauteur minimale possible d'une ligne. |
| [getRowFormat()](#getRowFormat--) | Renvoie l'objet RowFormat qui contient les propriétés de formatage pour cette ligne. |
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```

Renvoie la hauteur d'une ligne. Lecture seule double.

**Renvoie :**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```

Renvoie ou définit la hauteur minimale possible d'une ligne. Lecture/écriture double.

**Renvoie :**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public abstract void setMinimalHeight(double value)
```

Renvoie ou définit la hauteur minimale possible d'une ligne. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getRowFormat() {#getRowFormat--}
```
public abstract IRowFormat getRowFormat()
```

Renvoie l'objet RowFormat qui contient les propriétés de formatage pour cette ligne. Lecture seule [IRowFormat](../../com.aspose.slides/irowformat).

**Renvoie :**
[IRowFormat](../../com.aspose.slides/irowformat)