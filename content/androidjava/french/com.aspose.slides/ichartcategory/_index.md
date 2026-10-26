---
title: IChartCategory
second_title: Aspose.Slides for Android via Java API Reference
description: Represents chart categories.
type: docs
url: /fr/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

Représente les catégories de graphique.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getUseCell()](#getUseCell--) | Si vrai, la propriété AsCell est effective. |
| [getAsCell()](#getAsCell--) | Renvoie ou définit l’objet IChartDataCell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Renvoie ou définit l’objet IChartDataCell. |
| [getAsLiteral()](#getAsLiteral--) | Renvoie ou définit AsLiteral si UseCell est faux. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Renvoie ou définit AsLiteral si UseCell est faux. |
| [getValue()](#getValue--) | Si UseCell est vrai, cette propriété représente la propriété AsCell.Value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Si UseCell est vrai, cette propriété représente la propriété AsCell.Value. |
| [getGroupingLevels()](#getGroupingLevels--) | Conteneur géré des valeurs des niveaux de regroupement de catégorie de graphique. |
| [remove()](#remove--) | Supprime la catégorie du graphique. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```


Si vrai, la propriété AsCell est effective. En d’autres termes, la feuille de calcul est utilisée pour stocker la catégorie (ce cas prend en charge une catégorie à plusieurs niveaux). Si faux, la propriété AsLiteral est effective. En d’autres termes, la feuille de calcul n’est PAS utilisée pour stocker la catégorie (et ce cas ne prend pas en charge les catégories à plusieurs niveaux). Booléen en lecture seule.

--------------------

Pour modifier la valeur de cette propriété (pour toutes les catégories de la collection), définissez la nouvelle valeur dans la propriété [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--).

**Renvoie:**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```


Renvoie ou définit l’objet IChartDataCell. Si la catégorie est à plusieurs niveaux, alors l’objet IChartDataCell utilisé est celui du niveau « 0 ». Lecture/écriture [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Renvoie:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```


Renvoie ou définit l’objet IChartDataCell. Si la catégorie est à plusieurs niveaux, alors l’objet IChartDataCell utilisé est celui du niveau « 0 ». Lecture/écriture [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```


Renvoie ou définit AsLiteral si UseCell est faux. Lecture/écriture Object.

**Renvoie:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```


Renvoie ou définit AsLiteral si UseCell est faux. Lecture/écriture Object.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```


Si UseCell est vrai, cette propriété représente la propriété AsCell.Value. Si UseCell est faux, cette propriété représente la propriété AsLiteral. Lecture/écriture Object.

**Renvoie:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Si UseCell est vrai, cette propriété représente la propriété AsCell.Value. Si UseCell est faux, cette propriété représente la propriété AsLiteral. Lecture/écriture Object.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```


Conteneur géré des valeurs des niveaux de regroupement de catégorie de graphique. Une catégorie à plusieurs niveaux contient plus d’un niveau de regroupement. L’indexation des niveaux de regroupement commence à zéro. En lecture seule [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Renvoie:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```


Supprime la catégorie du graphique.