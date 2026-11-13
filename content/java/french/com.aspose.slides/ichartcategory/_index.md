---
title: IChartCategory
second_title: Aspose.Slides for Java API Reference
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
| [getUseCell()](#getUseCell--) | Si true alors la propriété AsCell est effective. |
| [getAsCell()](#getAsCell--) | Renvoie ou définit l'objet IChartDataCell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Renvoie ou définit l'objet IChartDataCell. |
| [getAsLiteral()](#getAsLiteral--) | Renvoie ou définit AsLiteral si UseCell est false. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Renvoie ou définit AsLiteral si UseCell est false. |
| [getValue()](#getValue--) | Si UseCell est true alors cette propriété représente la propriété AsCell.Value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Si UseCell est true alors cette propriété représente la propriété AsCell.Value. |
| [getCachedValue()](#getCachedValue--) | Obtient la valeur mise en cache d'une catégorie de graphique. |
| [getGroupingLevels()](#getGroupingLevels--) | Conteneur géré des valeurs des niveaux de regroupement des catégories de graphique. |
| [remove()](#remove--) | Supprime la catégorie du graphique. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```

Si true alors la propriété AsCell est effective. Autrement dit, la worksheet est utilisée pour stocker la catégorie (ce cas prend en charge une catégorie à plusieurs niveaux). Si false alors la propriété AsLiteral est effective. Autrement dit, la worksheet N'EST PAS utilisée pour stocker la catégorie (et ce cas ne prend pas en charge des catégories à plusieurs niveaux). Booléen lecture seule.

--------------------

Pour modifier la valeur de cette propriété (pour toutes les catégories de la collection) définissez la nouvelle valeur sur la propriété [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--).

**Renvoie:**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```

Renvoie ou définit l'objet IChartDataCell. Si la catégorie est à plusieurs niveaux, alors l'objet IChartDataCell utilisé pour le niveau "0". Lecture/écriture [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Renvoie:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```

Renvoie ou définit l'objet IChartDataCell. Si la catégorie est à plusieurs niveaux, alors l'objet IChartDataCell utilisé pour le niveau "0". Lecture/écriture [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```

Renvoie ou définit AsLiteral si UseCell est false. Lecture/écriture Object.

**Renvoie:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```

Renvoie ou définit AsLiteral si UseCell est false. Lecture/écriture Object.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

Si UseCell est true alors cette propriété représente la propriété AsCell.Value. Si UseCell est false alors cette propriété représente la propriété AsLiteral. Lecture/écriture Object.

**Renvoie:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Si UseCell est true alors cette propriété représente la propriété AsCell.Value. Si UseCell est false alors cette propriété représente la propriété AsLiteral. Lecture/écriture Object.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |
### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
```

Obtient la valeur mise en cache d'une catégorie de graphique. Lecture seule [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
> 
>      // Imprime toutes les valeurs en cache des catégories de graphique.
>      for (IChartCategory category : chart.getChartData().getCategories())
>          System.out.println(category.getCachedValue().toString());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Renvoie:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```

Conteneur géré des valeurs des niveaux de regroupement des catégories de graphique. Une catégorie à plusieurs niveaux contient plus d'un niveau de regroupement. L'indexation des niveaux de regroupement commence à zéro. Lecture seule [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Renvoie:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```

Supprime la catégorie du graphique.