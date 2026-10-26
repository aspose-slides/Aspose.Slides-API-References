---
title: Column
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente une colonne dans un tableau.
type: docs
url: /fr/com.aspose.slides/column/
---
**Héritage:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**Toutes les interfaces implémentées:**
[com.aspose.slides.IColumn](../../com.aspose.slides/icolumn)
```
public final class Column extends CellCollection implements IColumn
```

Représente une colonne dans un tableau.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getWidth()](#getWidth--) | Renvoie ou définit la largeur d'une colonne. |
| [setWidth(double value)](#setWidth-double-) | Renvoie ou définit la largeur d'une colonne. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Définit les propriétés de format de portion définies pour toutes les portions des cellules de colonne. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Définit les propriétés de format de paragraphe définies pour tous les paragraphes des cellules de colonne. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Définit les propriétés de format de cadre de texte définies pour tous les cadres de texte des cellules de colonne. |
| [getColumnFormat()](#getColumnFormat--) | Renvoie l'objet ColumnFormat qui contient les propriétés de formatage pour cette colonne. |
### getWidth() {#getWidth--}
```
public final double getWidth()
```


Renvoie ou définit la largeur d'une colonne. Lecture/écriture double.

**Renvoie :**
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Renvoie ou définit la largeur d'une colonne. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```


Définit les propriétés de format de portion définies pour toutes les portions des cellules de colonne.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | IPortionFormat object with necessary properties set. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```


Définit les propriétés de format de paragraphe définies pour tous les paragraphes des cellules de colonne.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | IParagraphFormat object with necessary properties set. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```


Définit les propriétés de format de cadre de texte définies pour tous les cadres de texte des cellules de colonne.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | ITextFrameFormat object with necessary properties set. |

### getColumnFormat() {#getColumnFormat--}
```
public final IColumnFormat getColumnFormat()
```


Renvoie l'objet ColumnFormat qui contient les propriétés de formatage pour cette colonne. Lecture seule [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Renvoie :**
[IColumnFormat](../../com.aspose.slides/icolumnformat)