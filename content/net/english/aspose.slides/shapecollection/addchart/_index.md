---
title: AddChart
second_title: Aspose.Sildes for .NET API Reference
description: Creates a new Chart initialize it with sample series data and settings and adds it to the end of the collection.
type: docs
weight: 100
url: /aspose.slides/shapecollection/addchart/
---
## AddChart(ChartType, float, float, float, float) {#addchart}

Creates a new Chart, initialize it with sample series data and settings and adds it to the end of the collection.

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height)
```

| Parameter | Type | Description |
| --- | --- | --- |
| type | ChartType | Type of chart. |
| x | Single | X coordinate of a new chart. |
| y | Single | Y coordinate of a new chart. |
| width | Single | Chart's width. |
| height | Single | Chart's height. |

### Return Value

Created chart.

### Examples

The following example shows how to create Chart in PowerPoint Presentation.

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

### See Also

* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [ChartType](../../../aspose.slides.charts/charttype)
* class [ShapeCollection](../../shapecollection)
* namespace [Aspose.Slides](../../shapecollection)
* assembly [Aspose.Slides](../../../)

---

## AddChart(ChartType, float, float, float, float, bool) {#addchart_1}

Creates a new Chart and adds it to the end of the collection.

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height, 
    bool initWithSample)
```

| Parameter | Type | Description |
| --- | --- | --- |
| type | ChartType | Type of chart. |
| x | Single | X coordinate of a new chart. |
| y | Single | Y coordinate of a new chart. |
| width | Single | Chart's width. |
| height | Single | Chart's height. |
| initWithSample | Boolean | If true then new chart will be initialized with sample series data and settings. If false then new chart will have no series and minimum settings. In this case chart creation will be more fast. |

### Return Value

Created chart.

### See Also

* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [ChartType](../../../aspose.slides.charts/charttype)
* class [ShapeCollection](../../shapecollection)
* namespace [Aspose.Slides](../../shapecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
