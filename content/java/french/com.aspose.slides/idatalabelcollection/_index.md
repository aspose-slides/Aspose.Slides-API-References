---
title: IDataLabelCollection
second_title: Référence API Aspose.Slides pour Java
description: Représente les libellés d'une série.
type: docs
url: /fr/com.aspose.slides/idatalabelcollection/
---
**Toutes les interfaces implémentées :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

Représente les libellés d’une série.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Récupère le libellé de données pour le point de données avec l'index spécifié. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Renvoie le format par défaut de tous les libellés de données dans la collection. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Représente le format des lignes de repère des libellés de données. |
| [isVisible()](#isVisible--) | False signifie que le libellé de données n'est pas visible par défaut (et donc tous les drapeaux Show*- (ShowValue, ...) de la propriété DefaultDataLabelFormat sont à false). |
| [hide()](#hide--) | Masque le libellé de données par défaut en définissant tous les drapeaux Show*- (ShowValue, ...) de la propriété DefaultDataLabelFormat à l'état false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Récupère le nombre de libellés de données visibles dans la collection. |
| [getCount()](#getCount--) | Récupère le nombre total de libellés de données dans la collection. |
| [getParentSeries()](#getParentSeries--) | Renvoie la série de diagramme parente. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Renvoie l'index du DataLabel spécifié dans la collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```

Récupère le libellé de données pour le point de données avec l'index spécifié.

--------------------

Une autre façon d'accéder au libellé de données est : - getSeries().getDataPoints().get_Item(i).getLabel() - gérer les propriétés du libellé.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Retour :**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```

Renvoie le format par défaut de tous les libellés de données dans la collection. Lecture seule [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Retour :**
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


**Retour :**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False signifie que le libellé de données n'est pas visible par défaut (et donc tous les drapeaux Show*- (ShowValue, ...) de la propriété DefaultDataLabelFormat sont à false). Lecture seule booléen.

--------------------

Si le libellé de données est visible par défaut, vous pouvez le masquer par défaut avec la méthode Hide(). Mais si le libellé de données n'est pas visible par défaut (IsVisible est false), vous pouvez le rendre « visible par défaut » en définissant les drapeaux Show*- (ShowValue, ...) de la propriété DefaultDataLabelFormat à l'état true.

**Retour :**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Masque le libellé de données par défaut en définissant tous les drapeaux Show*- (ShowValue, ...) de la propriété DefaultDataLabelFormat à l'état false. IsVisible sera false après cela.

--------------------

Si le libellé de données n'est pas visible par défaut (IsVisible est false), vous pouvez le rendre « visible par défaut » en définissant les drapeaux Show*- (ShowValue, ...) de la propriété DefaultDataLabelFormat à l'état true.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```

Récupère le nombre de libellés de données visibles dans la collection. Lecture seule int.

**Retour :**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```

Récupère le nombre total de libellés de données dans la collection. Lecture seule int.

**Retour :**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```

Renvoie la série de diagramme parente. Lecture seule [IChartSeries](../../com.aspose.slides/ichartseries).

**Retour :**
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

**Retour :**
int - Index d'un DataLabel ou -1 si le DataLabel ne provient pas de cette collection.