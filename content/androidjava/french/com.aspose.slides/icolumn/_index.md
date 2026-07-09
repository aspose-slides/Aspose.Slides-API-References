---
title: IColumn
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente une colonne dans un tableau.
type: docs
url: /fr/com.aspose.slides/icolumn/
---
**Toutes les interfaces implémentées:**  
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)  
```
public interface IColumn extends ICellCollection, IBulkTextFormattable
```

Représente une colonne dans un tableau.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getWidth()](#getWidth--) | Retourne ou définit la largeur d'une colonne. |
| [setWidth(double value)](#setWidth-double-) | Retourne ou définit la largeur d'une colonne. |
| [getColumnFormat()](#getColumnFormat--) | Retourne l'objet ColumnFormat qui contient les propriétés de mise en forme pour cette colonne. |

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Retourne ou définit la largeur d'une colonne. Lecture/écriture double.

**Retourne :**  
double

### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

Retourne ou définit la largeur d'une colonne. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getColumnFormat() {#getColumnFormat--}
```
public abstract IColumnFormat getColumnFormat()
```

Retourne l'objet ColumnFormat qui contient les propriétés de mise en forme pour cette colonne. Lecture seule [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Retourne :**  
[IColumnFormat](../../com.aspose.slides/icolumnformat)