---
title: ICellFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Représente le format d'une cellule de tableau.
type: docs
url: /fr/com.aspose.slides/icellformat/
---```
public interface ICellFormat
```

Représente le format d'une cellule de tableau.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Renvoie un objet de propriétés de remplissage de cellule. |
| [getBorderLeft()](#getBorderLeft--) | Renvoie un objet de propriétés de ligne de bordure gauche. |
| [getBorderTop()](#getBorderTop--) | Renvoie un objet de propriétés de ligne de bordure supérieure. |
| [getBorderRight()](#getBorderRight--) | Renvoie un objet de propriétés de ligne de bordure droite. |
| [getBorderBottom()](#getBorderBottom--) | Renvoie un objet de propriétés de ligne de bordure inférieure. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Renvoie un objet de propriétés de ligne diagonale de haut-gauche à bas-droit. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Renvoie un objet de propriétés de ligne diagonale de bas-gauche à haut-droit. |
| [getTransparency()](#getTransparency--) | Obtient ou définit la transparence de la couleur de remplissage. |
| [setTransparency(float value)](#setTransparency-float-) | Obtient ou définit la transparence de la couleur de remplissage. |
| [getEffective()](#getEffective--) | Obtient les propriétés de formatage effectives d'une cellule de tableau avec héritage et styles de tableau appliqués. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Renvoie un objet de propriétés de remplissage de cellule. Lecture seule [IFillFormat](../../com.aspose.slides/ifillformat).

**Renvoie :**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public abstract ILineFormat getBorderLeft()
```

Renvoie un objet de propriétés de ligne de bordure gauche. Lecture seule [ILineFormat](../../com.aspose.slides/ilineformat).

**Renvoie :**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public abstract ILineFormat getBorderTop()
```

Renvoie un objet de propriétés de ligne de bordure supérieure. Lecture seule [ILineFormat](../../com.aspose.slides/ilineformat).

**Renvoie :**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public abstract ILineFormat getBorderRight()
```

Renvoie un objet de propriétés de ligne de bordure droite. Lecture seule [ILineFormat](../../com.aspose.slides/ilineformat).

**Renvoie :**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public abstract ILineFormat getBorderBottom()
```

Renvoie un objet de propriétés de ligne de bordure inférieure. Lecture seule [ILineFormat](../../com.aspose.slides/ilineformat).

**Renvoie :**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public abstract ILineFormat getBorderDiagonalDown()
```

Renvoie un objet de propriétés de ligne diagonale de haut-gauche à bas-droit. Lecture seule [ILineFormat](../../com.aspose.slides/ilineformat).

**Renvoie :**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public abstract ILineFormat getBorderDiagonalUp()
```

Renvoie un objet de propriétés de ligne diagonale de bas-gauche à haut-droit. Lecture seule [ILineFormat](../../com.aspose.slides/ilineformat).

**Renvoie :**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```

Obtient ou définit la transparence de la couleur de remplissage. Lecture/écriture  float .

**Renvoie :**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```

Obtient ou définit la transparence de la couleur de remplissage. Lecture/écriture  float .

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ICellFormatEffectiveData getEffective()
```

Obtient les propriétés de formatage effectives d'une cellule de tableau avec héritage et styles de tableau appliqués.

**Renvoie :**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - Un [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).