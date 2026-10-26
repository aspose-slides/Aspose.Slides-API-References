---
title: CellFormat
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Représente le format d'une cellule de tableau.
type: docs
url: /fr/com.aspose.slides/cellformat/
---
**Héritage:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Toutes les interfaces implémentées:**  
[com.aspose.slides.ICellFormat](../../com.aspose.slides/icellformat)  
```
public final class CellFormat extends PVIObject implements ICellFormat
```

Représente le format d'une cellule de tableau.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillFormat()](#getFillFormat--) | Renvoie un objet de propriétés de remplissage de cellule. |
| [getBorderLeft()](#getBorderLeft--) | Renvoie un objet de propriétés de ligne de bordure gauche. |
| [getBorderTop()](#getBorderTop--) | Renvoie un objet de propriétés de ligne de bordure supérieure. |
| [getBorderRight()](#getBorderRight--) | Renvoie un objet de propriétés de ligne de bordure droite. |
| [getBorderBottom()](#getBorderBottom--) | Renvoie un objet de propriétés de ligne de bordure inférieure. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Renvoie un objet de propriétés de ligne diagonale de haut-gauche à bas-droite. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Renvoie un objet de propriétés de ligne diagonale de bas-gauche à haut-droite. |
| [getEffective()](#getEffective--) | Obtient les propriétés de formatage effectives d'une cellule de tableau avec héritage et styles de tableau appliqués. |
| [getTransparency()](#getTransparency--) | Obtient ou définit la transparence de la couleur de remplissage. |
| [setTransparency(float value)](#setTransparency-float-) | Obtient ou définit la transparence de la couleur de remplissage. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Lecture seule long.

**Renvoie :**  
long

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Renvoie un objet de propriétés de remplissage de cellule. Lecture seule [IFillFormat](../../com.aspose.slides/ifillformat).

**Renvoie :**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getBorderLeft() {#getBorderLeft--}
```
public final ILineFormat getBorderLeft()
```

Renvoie un objet de propriétés de ligne de bordure gauche. Lecture seule [ILineFormat](../../com.aspose.slides/ilineformat).

**Renvoie :**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderTop() {#getBorderTop--}
```
public final ILineFormat getBorderTop()
```

Renvoie un objet de propriétés de ligne de bordure supérieure. Lecture seule [ILineFormat](../../com.aspose.slides/ilineformat).

**Renvoie :**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderRight() {#getBorderRight--}
```
public final ILineFormat getBorderRight()
```

Renvoie un objet de propriétés de ligne de bordure droite. Lecture seule [ILineFormat](../../com.aspose.slides/ilineformat).

**Renvoie :**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderBottom() {#getBorderBottom--}
```
public final ILineFormat getBorderBottom()
```

Renvoie un objet de propriétés de ligne de bordure inférieure. Lecture seule [ILineFormat](../../com.aspose.slides/ilineformat).

**Renvoie :**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public final ILineFormat getBorderDiagonalDown()
```

Renvoie un objet de propriétés de ligne diagonale de haut-gauche à bas-droite. Lecture seule [ILineFormat](../../com.aspose.slides/ilineformat).

**Renvoie :**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public final ILineFormat getBorderDiagonalUp()
```

Renvoie un objet de propriétés de ligne diagonale de bas-gauche à haut-droite. Lecture seule [ILineFormat](../../com.aspose.slides/ilineformat).

**Renvoie :**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getEffective() {#getEffective--}
```
public final ICellFormatEffectiveData getEffective()
```

Obtient les propriétés de formatage effectives d'une cellule de tableau avec héritage et styles de tableau appliqués.

--------------------

> ```
> This example demonstrates getting effective fill format for different table logic parts.
>  Please note that cell formatting always has higher priority than row formatting, row - higher than column, column - higher that whole table.
>  So finally CellFormatEffectiveData properties always used to draw the table. The following code is just an example of API.
>  
>  Presentation pres = new Presentation(@"MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (ITable) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).RowFormat.GetEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - A [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```

Obtient ou définit la transparence de la couleur de remplissage. Lecture/écriture float .

**Renvoie:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
Gets or sets the transparency of the fill color. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |