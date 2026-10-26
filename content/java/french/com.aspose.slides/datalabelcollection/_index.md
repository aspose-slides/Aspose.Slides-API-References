---
title: DataLabelCollection
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente des libellés de séries.
type: docs
url: /fr/com.aspose.slides/datalabelcollection/
---
**Héritage :**
java.lang.Object, com.aspose.slides.DomObject

**Toutes les interfaces implémentées :**
[com.aspose.slides.IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
```
public class DataLabelCollection extends DomObject<ChartSeries> implements IDataLabelCollection
```

Représente des libellés de séries.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getChart()](#getChart--) | Renvoie le graphique parent. |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur java pour l'ensemble de la collection. |
| [isVisible()](#isVisible--) | False signifie que le libellé de données n'est pas visible par défaut (et donc tous les indicateurs Show*-flags (ShowValue, ...) de la propriété DefaultDataLabelFormat sont false). |
| [hide()](#hide--) | Masquez le libellé de données par défaut en définissant tous les indicateurs Show*-flags (ShowValue, ...) de la propriété DefaultDataLabelFormat à l'état false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Obtient le nombre de libellés de données visibles dans la collection. |
| [getCount()](#getCount--) | Obtient le nombre total de libellés de données dans la collection. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Obtient le format de libellé de données par défaut. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Représente le format des lignes de leader des libellés de données. |
| [getParentSeries()](#getParentSeries--) | Obtient la série parent. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Renvoie l'index du DataLabel spécifié dans la collection. |
| [get_Item(int index)](#get-Item-int-) | Obtient le libellé de données pour le point de données avec l'index spécifié. |
| [getSlide()](#getSlide--) | Renvoie la diapositive parent d'un FillFormat. |
| [getPresentation()](#getPresentation--) | Renvoie la présentation parent d'un FillFormat. |
### getChart() {#getChart--}
```
public final IChart getChart()
```

Renvoie le graphique parent. Lecture seule [IChart](../../com.aspose.slides/ichart).

**Renvoie :**
[IChart](../../com.aspose.slides/ichart)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```

Renvoie un énumérateur qui parcourt la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - Un IGenericEnumerator qui peut être utilisé pour parcourir la collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```

Renvoie un itérateur java pour l'ensemble de la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - Un java.util.Iterator pour l'ensemble de la collection.
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False signifie que le libellé de données n'est pas visible par défaut (et donc tous les indicateurs Show*-flags (ShowValue, ...) de la propriété DefaultDataLabelFormat sont false). Lecture seule boolean.

--------------------

Si le libellé de données est visible par défaut, vous pouvez le masquer par défaut avec la méthode Hide(). Mais si le libellé de données n'est pas visible par défaut (IsVisible est false), vous pouvez rendre le libellé de données « visible par défaut » en définissant les indicateurs Show*-flags (ShowValue, ...) de la propriété DefaultDataLabelFormat à l'état true.

**Renvoie :**
boolean
### hide() {#hide--}
```
public final void hide()
```

Masquez le libellé de données par défaut en définissant tous les indicateurs Show*-flags (ShowValue, ...) de la propriété DefaultDataLabelFormat à l'état false. IsVisible sera false après cela.

--------------------

Si le libellé de données n'est pas visible par défaut (IsVisible est false), vous pouvez rendre le libellé de données « visible par défaut » en définissant les indicateurs Show*-flags (ShowValue, ...) de la propriété DefaultDataLabelFormat à l'état true.
### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```

Obtient le nombre de libellés de données visibles dans la collection. Lecture seule int.

**Renvoie :**
int
### getCount() {#getCount--}
```
public final int getCount()
```

Obtient le nombre total de libellés de données dans la collection. Lecture seule int.

**Renvoie :**
int
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```

Obtient le format de libellé de données par défaut. Lecture seule [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Renvoie :**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
```

Représente le format des lignes de leader des libellés de données. Lecture seule [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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
### getParentSeries() {#getParentSeries--}
```
public final IChartSeries getParentSeries()
```

Obtient la série parent. Lecture seule [IChartSeries](../../com.aspose.slides/ichartseries).

**Renvoie :**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```

Renvoie l'index du DataLabel spécifié dans la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel à trouver. |

**Renvoie :**
int - Index d'un DataLabel ou -1 si le DataLabel ne provient pas de cette collection.
### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```

Obtient le libellé de données pour le point de données avec l'index spécifié.

--------------------

Une autre façon d'accéder au libellé de données est : - series.getDataPoints().get_Item(i).getLabel() - gérer les propriétés du libellé.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Renvoie :**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Renvoie la diapositive parent d'un FillFormat. Lecture seule [BaseSlide](../../com.aspose.slides/baseslide).

**Renvoie :**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Renvoie la présentation parent d'un FillFormat. Lecture seule [IPresentation](../../com.aspose.slides/ipresentation).

**Renvoie :**
[IPresentation](../../com.aspose.slides/ipresentation)