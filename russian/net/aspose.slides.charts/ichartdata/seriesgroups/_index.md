---
title: SeriesGroups
second_title: Справочник по API Aspose.Slides для .NET
description: Получает группы серий. Только для чтенияIChartSeriesGroupCollectionaspose.slides.charts/ichartseriesgroupcollection .
type: docs
weight: 70
url: /ru/net/aspose.slides.charts/ichartdata/seriesgroups/
---
## IChartData.SeriesGroups property

Получает группы серий. Только для чтения[`IChartSeriesGroupCollection`](../../ichartseriesgroupcollection) .

```csharp
public IChartSeriesGroupCollection SeriesGroups { get; }
```

### Примечания

1) Каждая группа серий содержит серии с комбинируемыми типами. Группы комбинируемых типов серий определены и описаны с помощью CombinableSeriesTypesGroup enum. Кроме того, каждая группа серий содержит серии, которые нанесены на график независимо от того, по основным осям или по второстепенным осям (не оба случая в одной группе). Итак, принцип группирования серий представляет собой группировку по группам типов, указанным выше , и по первичному/дополнительному типу построения. 2) Группа серий содержит некоторые свойства серий, которые являются общими для каждой серии в группе ("свойства группы серий"). "Свойства группы серий" " в классе ChartSeriesGroup доступен для чтения/записи. Каждое из "свойств группы серий" может иметь доступную только для чтения проекцию в классе ChartSeries.

### Смотрите также

* interface [IChartSeriesGroupCollection](../../ichartseriesgroupcollection)
* interface [IChartData](../../ichartdata)
* пространство имен [Aspose.Slides.Charts](../../ichartdata)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
