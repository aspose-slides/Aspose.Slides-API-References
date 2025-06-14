---
title: IChartSeriesGroupCollection
second_title: Aspose.Sildes for .NET API Reference
description: Représente la collection de groupes de séries combinables.
type: docs
weight: 1880
url: /fr/aspose.slides.charts/ichartseriesgroupcollection/
---

## Interface IChartSeriesGroupCollection

Représente la collection de groupes de séries combinables.

```csharp
public interface IChartSeriesGroupCollection : IGenericCollection<IChartSeriesGroup>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Item](../../aspose.slides.charts/ichartseriesgroupcollection/item) { get; } | Obtient le groupe de séries par séries. (2 indexeurs) |

### Remarques

1) Chaque groupe de séries contient des séries avec des types combinables. Les groupes de types de séries combinables sont définis et décrits avec l'énumération CombinableSeriesTypesGroup. De plus, chaque groupe de séries contient des séries qui sont tracées soit sur des axes primaires, soit sur des axes secondaires (pas les deux cas dans un même groupe). Ainsi, le principe de regroupement des séries est un regroupement par les types de groupes mentionnés ci-dessus et par le type de tracé primaire/secondaire. 2) Un groupe de séries contient certaines propriétés de séries qui sont communes à chaque série dans le groupe ("propriétés du groupe de séries"). Les "propriétés du groupe de séries" dans la classe ChartSeriesGroup sont en lecture/écriture. Chacune des "propriétés du groupe de séries" peut avoir une projection en lecture seule dans la classe ChartSeries.

### Voir Aussi

* interface [IGenericCollection&lt;T&gt;](../../aspose.slides/igenericcollection-1)
* interface [IChartSeriesGroup](../ichartseriesgroup)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->