---
title: SeriesGroups
second_title: Aspose.Slides pour la référence API .NET
description: Obtient les groupes de séries. Collection IChartSeriesGroupCollection aspose.slides.charts/ichartseriesgroupcollection en lecture seule.
type: docs
weight: 70
url: /fr/aspose.slides.charts/ichartdata/seriesgroups/
---

## Propriété IChartData.SeriesGroups

Obtient les groupes de séries. Collection [`IChartSeriesGroupCollection`](../../ichartseriesgroupcollection) en lecture seule.

```csharp
public IChartSeriesGroupCollection SeriesGroups { get; }
```

### Remarques

1) Chaque groupe de séries contient des séries avec des types combinables. Les groupes de types de séries combinables sont définis et décrits avec l'énumération CombinableSeriesTypesGroup. De plus, chaque groupe de séries contient des séries tracées soit sur des axes primaires, soit sur des axes secondaires (pas les deux cas dans un même groupe). Ainsi, le principe de regroupement des séries est un regroupement par les types énoncés ci-dessus et par le type de traçage primaire/secondaire. 2) Un groupe de séries contient certaines propriétés des séries qui sont communes à chaque série dans le groupe ("propriétés du groupe de séries"). Les "propriétés du groupe de séries" dans la classe ChartSeriesGroup sont en lecture/écriture. Chacune des "propriétés du groupe de séries" peut avoir une projection en lecture seule dans la classe ChartSeries.

### Voir Aussi

* interface [IChartSeriesGroupCollection](../../ichartseriesgroupcollection)
* interface [IChartData](../../ichartdata)
* namespace [Aspose.Slides.Charts](../../ichartdata)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: généré par xmldocmd pour Aspose.Slides.dll -->