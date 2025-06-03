---
title: Label
second_title: Справка по API Aspose.Slides для .NET
description: Представляет метку данных на уровне точки данных. Применяется для типов серии Treemap и Sunburst. Только для чтения IDataLabelaspose.slides/idatalabel.
type: docs
weight: 20
url: /ru/aspose.slides.charts/ichartdatapointlevel/label/
---

## Свойство IChartDataPointLevel.Label

Представляет метку данных на уровне точки данных. Применяется для типов серии Treemap и Sunburst. Только для чтения [`IDataLabel`](../../idatalabel).

```csharp
public IDataLabel Label { get; }
```

### Примеры

```csharp
using (Presentation pres = new Presentation())

   IChart chart = pres.Slides[0].Shapes.AddChart(ChartType.Sunburst, 50, 50, 500, 400);

    IChartSeries series = chart.ChartData.Series[0];

    IChartDataPointLevel dataPointLevel = series.DataPoints[0].DataPointLevels[1];

    dataPointLevel.Label.DataLabelFormat.ShowCategoryName = false;
    dataPointLevel.Label.DataLabelFormat.ShowValue = true;
    dataPointLevel.Label.DataLabelFormat.ShowSeriesName = true;

    dataPointLevel = series.DataPoints[12].DataPointLevels[1];
    dataPointLevel.Label.TextFormat.PortionFormat.FillFormat.FillType = FillType.Solid;
    dataPointLevel.Label.TextFormat.PortionFormat.FillFormat.SolidFillColor.Color = Color.Red;

```

### Смотрите также

* интерфейс [IDataLabel](../../idatalabel)
* интерфейс [IChartDataPointLevel](../../ichartdatapointlevel)
* пространство имен [Aspose.Slides.Charts](../../ichartdatapointlevel)
* сборка [Aspose.Slides](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для Aspose.Slides.dll -->