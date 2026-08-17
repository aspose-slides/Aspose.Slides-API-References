---
title: IChartCategory
second_title: Aspose.Slides for Java API Reference
description: Représente les catégories du graphique.
type: docs
url: /fr/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

Représente les catégories du graphique.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getUseCell()](#getUseCell--) | Si true alors la propriété AsCell est effective. |
| [getAsCell()](#getAsCell--) | Retourne ou définit l’objet IChartDataCell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Retourne ou définit l’objet IChartDataCell. |
| [getAsLiteral()](#getAsLiteral--) | Retourne ou définit AsLiteral si UseCell est false. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Retourne ou définit AsLiteral si UseCell est false. |
| [getValue()](#getValue--) | Si UseCell est true alors cette propriété représente la propriété AsCell.Value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Si UseCell est true alors cette propriété représente la propriété AsCell.Value. |
| [getGroupingLevels()](#getGroupingLevels--) | Conteneur géré des valeurs des niveaux de regroupement de la catégorie du graphique. |
| [remove()](#remove--) | Supprime la catégorie du graphique. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```


Si true alors la propriété AsCell est effective. En d’autres termes, la feuille de calcul est utilisée pour stocker la catégorie (ce cas prend en charge une catégorie à plusieurs niveaux). Si false alors la propriété AsLiteral est effective. En d’autres termes, la feuille de calcul n’est PAS utilisée pour stocker la catégorie (et ce cas ne prend pas en charge des catégories à plusieurs niveaux). Booléen en lecture seule.

--------------------

Pour changer la valeur de cette propriété (pour toutes les catégories de la collection) définissez une nouvelle valeur à la propriété [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--).

**Retour :**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```


Retourne ou définit l’objet IChartDataCell. Si la catégorie est à plusieurs niveaux alors l’objet IChartDataCell utilisé est celui du niveau « 0 ». Lecture/écriture [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Retour :**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```


Retourne ou définit l’objet IChartDataCell. Si la catégorie est à plusieurs niveaux alors l’objet IChartDataCell utilisé est celui du niveau « 0 ». Lecture/écriture [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```


Retourne ou définit AsLiteral si UseCell est false. Lecture/écriture Object.

**Retour :**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```


Retourne ou définit AsLiteral si UseCell est false. Lecture/écriture Object.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```


Si UseCell est true alors cette propriété représente la propriété AsCell.Value. Si UseCell est false alors cette propriété représente la propriété AsLiteral. Lecture/écriture Object.

**Retour :**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Si UseCell est true alors cette propriété représente la propriété AsCell.Value. Si UseCell est false alors cette propriété représente la propriété AsLiteral. Lecture/écriture Object.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```


Conteneur géré des valeurs des niveaux de regroupement de la catégorie du graphique. Une catégorie à plusieurs niveaux contient plus d’un niveau de regroupement. L’indexation des niveaux de regroupement commence à zéro. Lecture seule [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Retour :**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```


Supprime la catégorie du graphique.