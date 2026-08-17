---
title: IColumn
second_title: Référence API Aspose.Slides pour Java
description: Représente une colonne dans un tableau.
type: docs
url: /fr/com.aspose.slides/icolumn/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IColumn extends ICellCollection, IBulkTextFormattable
```

Représente une colonne dans un tableau.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getWidth()](#getWidth--) | Renvoie ou définit la largeur d’une colonne. |
| [setWidth(double value)](#setWidth-double-) | Renvoie ou définit la largeur d’une colonne. |
| [getColumnFormat()](#getColumnFormat--) | Renvoie l’objet ColumnFormat qui contient les propriétés de formatage pour cette colonne. |
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Renvoie ou définit la largeur d’une colonne. Lecture/écriture double.

**Renvoie :**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

Renvoie ou définit la largeur d’une colonne. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getColumnFormat() {#getColumnFormat--}
```
public abstract IColumnFormat getColumnFormat()
```

Renvoie l’objet ColumnFormat qui contient les propriétés de formatage pour cette colonne. Lecture seule [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Renvoie :**
[IColumnFormat](../../com.aspose.slides/icolumnformat)