---
title: ChartCategory
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente les catégories de graphique.
type: docs
url: /fr/com.aspose.slides/chartcategory/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IChartCategory](../../com.aspose.slides/ichartcategory), com.aspose.slides.IDOMObject
```
public class ChartCategory implements IChartCategory, IDOMObject
```

Représente les catégories de graphique.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getUseCell()](#getUseCell--) | Si true alors la propriété AsCell est effective. |
| [getAsCell()](#getAsCell--) | Retourne ou définit l'objet IChartDataCell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Retourne ou définit l'objet IChartDataCell. |
| [getAsLiteral()](#getAsLiteral--) | Retourne ou définit l'objet AsLiteral. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Retourne ou définit l'objet AsLiteral. |
| [getValue()](#getValue--) | Si UseCell est true alors cette propriété représente la propriété AsCell.Value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Si UseCell est true alors cette propriété représente la propriété AsCell.Value. |
| [getGroupingLevels()](#getGroupingLevels--) | Conteneur géré des valeurs des niveaux de regroupement des catégories de graphique. |
| [remove()](#remove--) | Supprime la catégorie du graphique. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```

Si true alors la propriété AsCell est effective. En d’autres termes, la feuille de calcul est utilisée pour stocker la catégorie (ce cas prend en charge une catégorie à plusieurs niveaux). Si false alors la propriété AsLiteral est effective. En d’autres termes, la feuille de calcul N’EST PAS utilisée pour stocker la catégorie (et ce cas ne prend pas en charge les catégories à plusieurs niveaux). Booléen en lecture seule.

--------------------

Pour modifier la valeur de cette propriété (pour toutes les catégories de la collection) définissez la nouvelle valeur sur la propriété ChartCategoryCollection.UseCells.

**Renvoie :**
boolean
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

Retourne ou définit l'objet IChartDataCell. Si la catégorie est à plusieurs niveaux, l’objet IChartDataCell utilisé correspond au niveau « 0 ». Lecture/écriture [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Renvoie :**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

Retourne ou définit l'objet IChartDataCell. Si la catégorie est à plusieurs niveaux, l’objet IChartDataCell utilisé correspond au niveau « 0 ». Lecture/écriture [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```

Retourne ou définit l'objet AsLiteral. Lecture/écriture Object.

**Renvoie :**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public final void setAsLiteral(Object value)
```

Retourne ou définit l'objet AsLiteral. Lecture/écriture Object.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

Si UseCell est true alors cette propriété représente la propriété AsCell.Value. Si UseCell est false alors cette propriété représente la propriété AsLiteral. Lecture/écriture Object.

**Renvoie :**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

Si UseCell est true alors cette propriété représente la propriété AsCell.Value. Si UseCell est false alors cette propriété représente la propriété AsLiteral. Lecture/écriture Object.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public final IChartCategoryLevelsManager getGroupingLevels()
```

Conteneur géré des valeurs des niveaux de regroupement des catégories de graphique. Une catégorie à plusieurs niveaux contient plus d’un niveau de regroupement. L’indexation des niveaux de regroupement commence à zéro. Lecture seule [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Renvoie :**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public final void remove()
```

Supprime la catégorie du graphique.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retourne l’objet Parent_Immediate. Lecture seule IDOMObject.

**Renvoie :**
com.aspose.slides.IDOMObject