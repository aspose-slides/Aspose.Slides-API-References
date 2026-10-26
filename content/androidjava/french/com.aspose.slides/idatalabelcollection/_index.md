---
title: IDataLabelCollection
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente les étiquettes d'une série.
type: docs
url: /fr/com.aspose.slides/idatalabelcollection/
---
**Toutes les interfaces implémentées :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

Représente les étiquettes d'une série.

## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtient l'étiquette de données pour le point de données avec l'index spécifié. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Renvoie le format par défaut de toutes les étiquettes de données de la collection. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Représente le format des lignes de repère des étiquettes de données. |
| [isVisible()](#isVisible--) | False signifie que l'étiquette de données n'est pas visible par défaut (et que tous les drapeaux Show\*- (ShowValue, …) de la propriété DefaultDataLabelFormat sont faux). |
| [hide()](#hide--) | Masque l'étiquette de données par défaut en réglant tous les drapeaux Show\*- (ShowValue, …) de la propriété DefaultDataLabelFormat sur false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Obtient le nombre d'étiquettes de données visibles dans la collection. |
| [getCount()](#getCount--) | Obtient le nombre total d'étiquettes de données dans la collection. |
| [getParentSeries()](#getParentSeries--) | Renvoie la série de graphique parent. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Renvoie l'indice du DataLabel spécifié dans la collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```


Obtient l'étiquette de données pour le point de données avec l'index spécifié.

--------------------

Une autre façon d'accéder à l'étiquette de données est : - getSeries().getDataPoints().get_Item(i).getLabel() - gérer les propriétés de l'étiquette.

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


Renvoie le format par défaut de toutes les étiquettes de données de la collection. Lecture seule [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Renvoie :**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```


Représente le format des lignes de repère des étiquettes de données. Lecture seule [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False means that data label is not visible by default (and so all Show\*-flags (ShowValue, ...) of the DefaultDataLabelFormat property are false). Read-only  boolean .

--------------------

If data label is visible by default you can make it hidden by default with Hide() method. But if data label is not visible by default (IsVisible is false) you can make data label "visible by default" with setting Show\*-flags (ShowValue, ...) of the DefaultDataLabelFormat property to true state.

**Returns:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Make data label hidden by default by setting all Show*-flags (ShowValue, ...) of the DefaultDataLabelFormat property to false state. IsVisible will be false after this.

--------------------

If data label is not visible by default (IsVisible is false) you can make data label "visible by default" with setting Show*-flags (ShowValue, ...) of the DefaultDataLabelFormat property to true state.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```

Gets the number of visible data labels in the collection. Read-only  int .

**Returns:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```

Gets the number of all data labels in the collection. Read-only  int .

**Returns:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```

Returns parent chart series. Read-only [IChartSeries](../../com.aspose.slides/ichartseries).

**Returns:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)


Renvoie un indice du DataLabel spécifié dans la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel à trouver. |

**Renvoie :**
int - Indice d'un DataLabel ou -1 si le DataLabel ne provient pas de cette collection.