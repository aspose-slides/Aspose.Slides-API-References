---
title: SeriesGroups
second_title: Aspose.Sildes для .NET API Справочник
description: Получает группы серий. Только для чтения IChartSeriesGroupCollectionaspose.slides.charts/ichartseriesgroupcollection.
type: docs
weight: 70
url: /ru/aspose.slides.charts/ichartdata/seriesgroups/
---

## IChartData.SeriesGroups свойство

Получает группы серий. Только для чтения [`IChartSeriesGroupCollection`](../../ichartseriesgroupcollection).

```csharp
public IChartSeriesGroupCollection SeriesGroups { get; }
```

### Замечания

1) Каждая группа серий содержит серии с комбинируемыми типами. Группы комбинируемых типов серий определяются и описываются с помощью перечисления CombinableSeriesTypesGroup. Также каждая группа серий содержит серии, которые строятся либо на основных осях, либо на вторичных осях (не в обоих случаях в одной группе). Таким образом, принцип группировки серий заключается в группировке по упомянутым выше типам групп и по основному/вторичному типу построения. 2) Группа серий содержит некоторые свойства серий, которые общие для каждой серии в группе ("свойства группы серий"). "Свойства группы серий" в классе ChartSeriesGroup являются читаемыми и записываемыми. Каждое из "свойств группы серий" может иметь только для чтения проекцию в классе ChartSeries.

### См. также

* интерфейс [IChartSeriesGroupCollection](../../ichartseriesgroupcollection)
* интерфейс [IChartData](../../ichartdata)
* пространство имен [Aspose.Slides.Charts](../../ichartdata)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->