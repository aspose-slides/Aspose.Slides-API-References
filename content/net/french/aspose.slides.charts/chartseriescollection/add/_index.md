---
title: Add
second_title: Référence de l'API Aspose.Slides pour .NET
description: Crée une nouvelle série de graphiques et lajoute à la collection.
type: docs
weight: 50
url: /fr/aspose.slides.charts/chartseriescollection/add/
---
## Add(ChartType) {#add}

Crée une nouvelle série de graphiques et l'ajoute à la collection.

```csharp
public IChartSeries Add(ChartType type)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| type | ChartType | Type de série |

### Return_Value

Nouvelle série de cartes.

### Voir également

* interface [IChartSeries](../../ichartseries)
* enum [ChartType](../../charttype)
* class [ChartSeriesCollection](../../chartseriescollection)
* espace de noms [Aspose.Slides.Charts](../../chartseriescollection)
* Assemblée [Aspose.Slides](../../../)

---

## Add(IChartDataCell, ChartType) {#add_2}

Crée une nouvelle série de graphiques à partir de[`ChartDataCell`](../../chartdatacell) et l'ajoute à la collection.

```csharp
public IChartSeries Add(IChartDataCell cellWithSeriesName, ChartType type)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| cellWithSeriesName | IChartDataCell | Cellule contenant le nom de la série. |
| type | ChartType | Tapez le type de série |

### Return_Value

Ajout d'une série de graphiques ou d'une série qui est déjà dans la collection.

### Remarques

Si la série de graphiques se situe déjà dans la même cellule de la collection , la méthode n'ajoute rien et renvoie son index.

### Voir également

* interface [IChartSeries](../../ichartseries)
* interface [IChartDataCell](../../ichartdatacell)
* enum [ChartType](../../charttype)
* class [ChartSeriesCollection](../../chartseriescollection)
* espace de noms [Aspose.Slides.Charts](../../chartseriescollection)
* Assemblée [Aspose.Slides](../../../)

---

## Add(IChartCellCollection, ChartType) {#add_1}

Crée une nouvelle série de graphiques à partir de[`ChartCellCollection`](../../chartcellcollection) et l'ajoute à la collection.

```csharp
public IChartSeries Add(IChartCellCollection cellsWithSeriesName, ChartType type)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| cellsWithSeriesName | IChartCellCollection | Cellules contenant le nom de la série. |
| type | ChartType | Tapez le type de série |

### Return_Value

Ajout d'une série de graphiques ou d'une série qui est déjà dans la collection.

### Remarques

Si la série de graphiques se situe déjà dans la même cellule de la collection , la méthode n'ajoute rien et renvoie son index.

### Voir également

* interface [IChartSeries](../../ichartseries)
* interface [IChartCellCollection](../../ichartcellcollection)
* enum [ChartType](../../charttype)
* class [ChartSeriesCollection](../../chartseriescollection)
* espace de noms [Aspose.Slides.Charts](../../chartseriescollection)
* Assemblée [Aspose.Slides](../../../)

---

## Add(string, ChartType) {#add_3}

Crée une nouvelle série de graphiques à partir de la valeur et l'ajoute à la collection.

```csharp
public IChartSeries Add(string name, ChartType type)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| name | String | Nom de la série. |
| type | ChartType | Tapez le type de série |

### Return_Value

Série de graphiques ajoutée.

### Voir également

* interface [IChartSeries](../../ichartseries)
* enum [ChartType](../../charttype)
* class [ChartSeriesCollection](../../chartseriescollection)
* espace de noms [Aspose.Slides.Charts](../../chartseriescollection)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
