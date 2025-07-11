---
title: IChartSeriesGroupCollection
second_title: Aspose.Slides für .NET API Referenz
description: Stellt die Sammlung von Gruppen kombinierbarer Serien dar.
type: docs
weight: 1880
url: /de/aspose.slides.charts/ichartseriesgroupcollection/
---

## IChartSeriesGroupCollection-Schnittstelle

Stellt die Sammlung von Gruppen kombinierbarer Serien dar.

```csharp
public interface IChartSeriesGroupCollection : IGenericCollection<IChartSeriesGroup>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Item](../../aspose.slides.charts/ichartseriesgroupcollection/item) { get; } | Ruft die Seriengruppe nach Serien ab. (2 Indizes) |

### Anmerkungen

1) Jede Gruppe von Serien enthält Serien mit kombinierbaren Typen. Gruppen von kombinierbaren Serientypen sind durch das CombinableSeriesTypesGroup-Enum definiert und beschrieben. Außerdem enthält jede Gruppe von Serien Serien, die entweder auf primären Achsen oder auf sekundären Achsen (nicht beide Fälle in einer Gruppe) geplottet sind. Das Prinzip der Seriengruppierung basiert auf der Gruppierung nach den oben genannten Typgruppen und dem primären/semanaren Plottyp. 2) Die Gruppe von Serien enthält einige Eigenschaften von Serien, die für jede Serie in der Gruppe gemeinsam sind ("Eigenschaften der Seriengruppe"). "Eigenschaften der Seriengruppe" in der ChartSeriesGroup-Klasse ist schreibbar. Jede der "Eigenschaften der Seriengruppe" kann eine schreibgeschützte Projektion in der ChartSeries-Klasse haben.

### Siehe auch

* Schnittstelle [IGenericCollection&lt;T&gt;](../../aspose.slides/igenericcollection-1)
* Schnittstelle [IChartSeriesGroup](../ichartseriesgroup)
* Namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->