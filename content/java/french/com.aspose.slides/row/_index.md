---
title: Row
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente une ligne dans un tableau.
type: docs
url: /fr/com.aspose.slides/row/
---
**Héritage:**  
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**Toutes les interfaces implémentées:**  
[com.aspose.slides.IRow](../../com.aspose.slides/irow)  
```
public final class Row extends CellCollection implements IRow
```

Représente une ligne dans un tableau.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getHeight()](#getHeight--) | Renvoie la hauteur d'une ligne. |
| [getMinimalHeight()](#getMinimalHeight--) | Renvoie ou définit la hauteur minimale possible d'une ligne. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Renvoie ou définit la hauteur minimale possible d'une ligne. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Définit les propriétés de format de portion spécifiées pour toutes les portions des cellules de la ligne. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Définit les propriétés de format de paragraphe spécifiées pour tous les paragraphes des cellules de la ligne. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Définit les propriétés de format de cadre de texte spécifiées pour tous les cadres de texte des cellules de la ligne. |
| [getRowFormat()](#getRowFormat--) | Renvoie l'objet RowFormat qui contient les propriétés de mise en forme pour cette ligne. |
### getHeight() {#getHeight--}
```
public final double getHeight()
```

Renvoie la hauteur d'une ligne. Lecture seule double.

**Retour:**  
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

Renvoie ou définit la hauteur minimale possible d'une ligne. Lecture/écriture double.

**Retour:**  
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public final void setMinimalHeight(double value)
```

Renvoie ou définit la hauteur minimale possible d'une ligne. Lecture/écriture double.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |
### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Définit les propriétés de format de portion spécifiées pour toutes les portions des cellules de la ligne.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | IPortionFormat object avec les propriétés nécessaires définies. |
### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Définit les propriétés de format de paragraphe spécifiées pour tous les paragraphes des cellules de la ligne.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | IParagraphFormat object avec les propriétés nécessaires définies. |
### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFrameFormat(ITextFrameFormat source)
```

Définit les propriétés de format de cadre de texte spécifiées pour tous les cadres de texte des cellules de la ligne.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | ITextFrameFormat object avec les propriétés nécessaires définies. |
### getRowFormat() {#getRowFormat--}
```
public final IRowFormat getRowFormat()
```

Renvoie l'objet RowFormat qui contient les propriétés de mise en forme pour cette ligne. Lecture seule [IRowFormat](../../com.aspose.slides/irowformat).

**Retour:**  
[IRowFormat](../../com.aspose.slides/irowformat)