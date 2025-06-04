---
title: AddChart
second_title: Aspose.Sildes для справочника API .NET
description: Создает новый график, инициализирует его с помощью образцов данных и настроек и добавляет в конец коллекции.
type: docs
weight: 100
url: /ru/aspose.slides/shapecollection/addchart/
---

## AddChart(ChartType, float, float, float, float) {#addchart}

Создает новый график, инициализирует его с помощью образцов данных и настроек и добавляет в конец коллекции.

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | ChartType | Тип графика. |
| x | Single | Координата X нового графика. |
| y | Single | Координата Y нового графика. |
| width | Single | Ширина графика. |
| height | Single | Высота графика. |

### Возвращаемое значение

Созданный график.

### Примеры

Следующий пример показывает, как создать график в презентации PowerPoint.

```csharp
[C#]
// Instantiates the Presentation class that represents a PPTX file
using(Presentation pres = new Presentation()) {
  // Accesses the first slide
  ISlide sld = pres.Slides[0];
  // Adds a chart with its default data
  IChart chart = sld.Shapes.AddChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
  // Sets the chart title
  chart.ChartTitle.AddTextFrameForOverriding("Sample Title");
  chart.ChartTitle.TextFrameForOverriding.TextFrameFormat.CenterText = NullableBool.True;
  chart.ChartTitle.Height = 20;
  chart.HasTitle = true;
  // Sets the first series to show values
  chart.ChartData.Series[0].Labels.DefaultDataLabelFormat.ShowValue = true;
  // Sets the index for the chart data sheet
  int defaultWorksheetIndex = 0;
  // Gets the chart data worksheet
  IChartDataWorkbook fact = chart.ChartData.ChartDataWorkbook;
  // Deletes the default generated series and categories
  chart.ChartData.Series.Clear();
  chart.ChartData.Categories.Clear();
  int s = chart.ChartData.Series.Count;
  s = chart.ChartData.Categories.Count;
  // Adds new series
  chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.Type);
  chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.Type);
  // Adds new categories
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
  // Takes the first chart series
  IChartSeries series = chart.ChartData.Series[0];
  // Populates series data
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 1, 1, 20));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 2, 1, 50));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 3, 1, 30));
  // Sets the fill color for the series
  series.Format.Fill.FillType = FillType.Solid;
  series.Format.Fill.SolidFillColor.Color = Color.Red;
  // Takes the second chart series
  series = chart.ChartData.Series[1];
  // Populates series data
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 1, 2, 30));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 2, 2, 10));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 3, 2, 60));
  // Sets the fill color for series
  series.Format.Fill.FillType = FillType.Solid;
  series.Format.Fill.SolidFillColor.Color = Color.Green;
  // Sets the first label to show Category name
  IDataLabel lbl = series.DataPoints[0].Label;
  lbl.DataLabelFormat.ShowCategoryName = true;
  lbl = series.DataPoints[1].Label;
  lbl.DataLabelFormat.ShowSeriesName = true;
  // Sets the series to show the value for the third label
  lbl = series.DataPoints[2].Label;
  lbl.DataLabelFormat.ShowValue = true;
  lbl.DataLabelFormat.ShowSeriesName = true;
  lbl.DataLabelFormat.Separator = "/";
  // Saves the PPTX file to disk
  pres.Save("AsposeChart_out.pptx", SaveFormat.Pptx);
}
```

### См. также

* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [ChartType](../../../aspose.slides.charts/charttype)
* class [ShapeCollection](../../shapecollection)
* namespace [Aspose.Slides](../../shapecollection)
* assembly [Aspose.Slides](../../../)

---

## AddChart(ChartType, float, float, float, float, bool) {#addchart_1}

Создает новый график и добавляет его в конец коллекции.

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height, 
    bool initWithSample)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | ChartType | Тип графика. |
| x | Single | Координата X нового графика. |
| y | Single | Координата Y нового графика. |
| width | Single | Ширина графика. |
| height | Single | Высота графика. |
| initWithSample | Boolean | Если true, то новый график будет инициализирован с помощью образцов данных и настроек. Если false, то новый график не будет иметь серий и минимальных настроек. В этом случае создание графика будет быстрее. |

### Возвращаемое значение

Созданный график.

### См. также

* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [ChartType](../../../aspose.slides.charts/charttype)
* class [ShapeCollection](../../shapecollection)
* namespace [Aspose.Slides](../../shapecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->