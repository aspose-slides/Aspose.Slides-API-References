---
title: IDataLabelCollection
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente les libellés d'une série.
type: docs
url: /fr/com.aspose.slides/idatalabelcollection/
---
**Toutes les interfaces implémentées :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

Représente les libellés d'une série.

## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtient le libellé de données du point de données avec l'index spécifié. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Renvoie le format par défaut de tous les libellés de données de la collection. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Représente le format des lignes de repère des libellés de données. |
| [isVisible()](#isVisible--) | False indique que le libellé de données n'est pas visible par défaut (et donc tous les indicateurs Show\*-flags (ShowValue, ...) de la propriété DefaultDataLabelFormat sont false). |
| [hide()](#hide--) | Masquez le libellé de données par défaut en définissant tous les indicateurs Show\*-flags (ShowValue, ...) de la propriété DefaultDataLabelFormat à l'état false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Obtient le nombre de libellés de données visibles dans la collection. |
| [getCount()](#getCount--) | Obtient le nombre de tous les libellés de données de la collection. |
| [getParentSeries()](#getParentSeries--) | Renvoie la série de diagramme parent. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Renvoie l'index du DataLabel spécifié dans la collection. |
| [getDefaultLabelShapeType()](#getDefaultLabelShapeType--) | Obtient ou définit le type de forme par défaut pour les libellés de données. |
| [setDefaultLabelShapeType(int value)](#setDefaultLabelShapeType-int-) | Obtient ou définit le type de forme par défaut pour les libellés de données. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```

Obtient le libellé de données du point de données avec l'index spécifié.

--------------------

Une autre façon d'accéder au libellé de données est : - getSeries().getDataPoints().get\_Item(i).getLabel() - gérer les propriétés du libellé.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Renvoie :**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```

Renvoie le format par défaut de tous les libellés de données de la collection. Lecture seule [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Renvoie :**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```

Représente le format des lignes de repère des libellés de données. Lecture seule [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IChart chart = (IChart) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      IDataLabelCollection labels = series.get_Item(0).getLabels();
>      labels.getLeaderLinesFormat().getLine().getFillFormat().setFillType(FillType.Solid);
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(new java.awt.Color(255, 0, 0, 255));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Renvoie :**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False indique que le libellé de données n'est pas visible par défaut (et donc tous les indicateurs Show\*-flags (ShowValue, ...) de la propriété DefaultDataLabelFormat sont false). Lecture seule  boolean .

--------------------

Si le libellé de données est visible par défaut, vous pouvez le masquer par défaut avec la méthode Hide(). Mais si le libellé de données n'est pas visible par défaut (IsVisible est false), vous pouvez rendre le libellé de données « visible par défaut » en réglant les indicateurs Show\*-flags (ShowValue, ...) de la propriété DefaultDataLabelFormat sur l'état true.

**Renvoie :**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Masquez le libellé de données par défaut en définissant tous les indicateurs Show\*-flags (ShowValue, ...) de la propriété DefaultDataLabelFormat à l'état false. IsVisible sera false après cela.

--------------------

Si le libellé de données n'est pas visible par défaut (IsVisible est false), vous pouvez rendre le libellé de données « visible par défaut » en réglant les indicateurs Show\*-flags (ShowValue, ...) de la propriété DefaultDataLabelFormat sur l'état true.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```

Obtient le nombre de libellés de données visibles dans la collection. Lecture seule  int .

**Renvoie :**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```

Obtient le nombre de tous les libellés de données de la collection. Lecture seule  int .

**Renvoie :**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```

Renvoie la série de diagramme parent. Lecture seule [IChartSeries](../../com.aspose.slides/ichartseries).

**Renvoie :**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```

Renvoie l'index du DataLabel spécifié dans la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel à trouver. |

**Renvoie :**
int - Index d'un DataLabel ou -1 si le DataLabel ne provient pas de cette collection.
### getDefaultLabelShapeType() {#getDefaultLabelShapeType--}
```
public abstract int getDefaultLabelShapeType()
```

Obtient ou définit le type de forme par défaut pour les libellés de données. Renvoie [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) si aucune forme n'est définie.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Définit le type de forme de tous les libellés de données de la première série sur Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

La définition de cette propriété définit également la propriété IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) pour tous les libellés de données de la collection à la même valeur.

**Renvoie :**
int
### setDefaultLabelShapeType(int value) {#setDefaultLabelShapeType-int-}
```
public abstract void setDefaultLabelShapeType(int value)
```

Obtient ou définit le type de forme par défaut pour les libellés de données. Renvoie [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) si aucune forme n'est définie.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Définit le type de forme de tous les libellés de données de la première série sur Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

La définition de cette propriété définit également la propriété IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) pour tous les libellés de données de la collection à la même valeur.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |