---
title: DataLabelCollection
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente les libellés d’une série.
type: docs
url: /fr/com.aspose.slides/datalabelcollection/
---
**Héritage:**
java.lang.Object, com.aspose.slides.DomObject

**Toutes les interfaces implémentées:**
[com.aspose.slides.IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
```
public class DataLabelCollection extends DomObject<ChartSeries> implements IDataLabelCollection
```

Représente les libellés de série.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getChart()](#getChart--) | Renvoie le graphique parent. |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur java pour l'ensemble de la collection. |
| [isVisible()](#isVisible--) | False signifie que le libellé de données n’est pas visible par défaut (et donc que tous les indicateurs Show*-flags (ShowValue, ...) de la propriété DefaultDataLabelFormat sont false). |
| [hide()](#hide--) | Masquez le libellé de données par défaut en définissant tous les indicateurs Show*-flags (ShowValue, ...) de la propriété DefaultDataLabelFormat à l’état false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Obtient le nombre de libellés de données visibles dans la collection. |
| [getCount()](#getCount--) | Obtient le nombre de tous les libellés de données dans la collection. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Obtient le format de libellé de données par défaut. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Représente le format des lignes directrices des libellés de données. |
| [getParentSeries()](#getParentSeries--) | Obtient la série parent. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Renvoie l’index du DataLabel spécifié dans la collection. |
| [get_Item(int index)](#get-Item-int-) | Obtient le libellé de données pour le point de données avec l’index spécifié. |
| [getSlide()](#getSlide--) | Renvoie la diapositive parent d’un FillFormat. |
| [getPresentation()](#getPresentation--) | Renvoie la présentation parent d’un FillFormat. |
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
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```


Renvoie un itérateur java pour l'ensemble de la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - An java.util.Iterator for the entire collection.
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


False signifie que le libellé de données n’est pas visible par défaut (et donc que tous les indicateurs Show*-flags (ShowValue, ...) de la propriété DefaultDataLabelFormat sont false). Lecture seule booléen.

--------------------

Si le libellé de données est visible par défaut, vous pouvez le rendre masqué par défaut avec la méthode Hide(). Mais si le libellé de données n’est pas visible par défaut (IsVisible est false), vous pouvez rendre le libellé "visible par défaut" en définissant les indicateurs Show*-flags (ShowValue, ...) de la propriété DefaultDataLabelFormat à l’état true.

**Renvoie :**
boolean
### hide() {#hide--}
```
public final void hide()
```


Masquez le libellé de données par défaut en définissant tous les indicateurs Show*-flags (ShowValue, ...) de la propriété DefaultDataLabelFormat à l’état false. IsVisible sera false après cela.

--------------------

Si le libellé de données n’est pas visible par défaut (IsVisible est false), vous pouvez rendre le libellé "visible par défaut" en définissant les indicateurs Show*-flags (ShowValue, ...) de la propriété DefaultDataLabelFormat à l’état true.
### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```


Obtient le nombre de libellés de données visibles dans la collection. int en lecture seule.

**Renvoie :**
int
### getCount() {#getCount--}
```
public final int getCount()
```


Obtient le nombre de tous les libellés de données dans la collection. int en lecture seule.

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


Représente le format des lignes directrices des libellés de données. Lecture seule [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getParentSeries() {#getParentSeries--}
```
public final IChartSeries getParentSeries()
```

Gets the parent series. Read-only [IChartSeries](../../com.aspose.slides/ichartseries).

**Returns:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```


Returns an index of the specified DataLabel in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel to find. |

**Returns:**
int - Index of a DataLabel or -1 if DataLabel not from this collection.
### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```


Gets the data label for the data point with the specified index.

--------------------

Alternate way to access data label is: - series.getDataPoints().get_Item(i).getLabel() - manage label properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Returns the parent slide of a FillFormat. Read-only [BaseSlide](../../com.aspose.slides/baseslide).

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()


Renvoie la présentation parent d’un FillFormat. Lecture seule [IPresentation](../../com.aspose.slides/ipresentation).

**Renvoie :**
[IPresentation](../../com.aspose.slides/ipresentation)