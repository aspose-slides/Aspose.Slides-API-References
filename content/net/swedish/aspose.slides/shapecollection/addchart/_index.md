---
title: AddChart
second_title: Aspose.Sildes för .NET API-referens
description: Skapar ett nytt diagram, initierar det med exempelseriedata och inställningar och lägger till det i slutet av shape-samlingen.
type: docs
weight: 100
url: /sv/aspose.slides/shapecollection/addchart/
---
## AddChart(ChartType, float, float, float, float) {#addchart}

Skapar ett nytt diagram, initierar det med exempelseriedata och inställningar, och lägger till det i slutet av shape-samlingen.

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | ChartType | Typen av diagram att lägga till. |
| x | Single | x-koordinaten för det nya diagrammet, i punkter. |
| y | Single | y-koordinaten för det nya diagrammet, i punkter. |
| width | Single | Diagrammets bredd, i punkter. |
| height | Single | Diagrammets höjd, i punkter. |

### Return Value

Det nyss skapade [`IChart`](../../../aspose.slides.charts/ichart).

### Examples

Följande exempel visar hur man skapar Chart i PowerPoint Presentation.

```csharp
[C#]
// Skapar en instans av Presentation-klassen som representerar en PPTX-fil
using(Presentation pres = new Presentation()) {
  // Öppnar den första bilden
  ISlide sld = pres.Slides[0];
  // Lägger till ett diagram med dess standarddata
  IChart chart = sld.Shapes.AddChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
  // Ställer in diagramtitel
  chart.ChartTitle.AddTextFrameForOverriding("Sample Title");
  chart.ChartTitle.TextFrameForOverriding.TextFrameFormat.CenterText = NullableBool.True;
  chart.ChartTitle.Height = 20;
  chart.HasTitle = true;
  // Ställer in den första serien att visa värden
  chart.ChartData.Series[0].Labels.DefaultDataLabelFormat.ShowValue = true;
  // Anger indexet för diagrammets kalkylblad
  int defaultWorksheetIndex = 0;
  // Hämtar diagrammets dataarbetsblad
  IChartDataWorkbook fact = chart.ChartData.ChartDataWorkbook;
  // Tar bort de standardgenererade serierna och kategorierna
  chart.ChartData.Series.Clear();
  chart.ChartData.Categories.Clear();
  int s = chart.ChartData.Series.Count;
  s = chart.ChartData.Categories.Count;
  // Lägger till nya serier
  chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.Type);
  chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.Type);
  // Lägger till nya kategorier
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
  // Hämtar den första diagramserien
  IChartSeries series = chart.ChartData.Series[0];
  // Fyller seriedata
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 1, 1, 20));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 2, 1, 50));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 3, 1, 30));
  // Ställer in fyllningsfärgen för serien
  series.Format.Fill.FillType = FillType.Solid;
  series.Format.Fill.SolidFillColor.Color = Color.Red;
  // Hämtar den andra diagramserien
  series = chart.ChartData.Series[1];
  // Fyller seriedata
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 1, 2, 30));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 2, 2, 10));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 3, 2, 60));
  // Ställer in fyllningsfärgen för serien
  series.Format.Fill.FillType = FillType.Solid;
  series.Format.Fill.SolidFillColor.Color = Color.Green;
  // Ställer in den första etiketten att visa kategorinamn
  IDataLabel lbl = series.DataPoints[0].Label;
  lbl.DataLabelFormat.ShowCategoryName = true;
  lbl = series.DataPoints[1].Label;
  lbl.DataLabelFormat.ShowSeriesName = true;
  // Ställer in serien att visa värdet för den tredje etiketten
  lbl = series.DataPoints[2].Label;
  lbl.DataLabelFormat.ShowValue = true;
  lbl.DataLabelFormat.ShowSeriesName = true;
  lbl.DataLabelFormat.Separator = "/";
  // Sparar PPTX-filen till disk
  pres.Save("AsposeChart_out.pptx", SaveFormat.Pptx);
}
```

### See Also

* gränssnitt [IChart](../../../aspose.slides.charts/ichart)
* enum [ChartType](../../../aspose.slides.charts/charttype)
* klass [ShapeCollection](../../shapecollection)
* namnrymd [Aspose.Slides](../../shapecollection)
* assembly [Aspose.Slides](../../../)

---

## AddChart(ChartType, float, float, float, float, bool) {#addchart_1}

Skapar ett nytt diagram, initierar det med exempelseriedata och inställningar, och lägger till det i slutet av shape-samlingen.

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height, 
    bool initWithSample)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | ChartType | Typen av diagram att lägga till. |
| x | Single | x-koordinaten för det nya diagrammet, i punkter. |
| y | Single | y-koordinaten för det nya diagrammet, i punkter. |
| width | Single | Diagrammets bredd, i punkter. |
| height | Single | Diagrammets höjd, i punkter. |
| initWithSample | Boolean | True för att initiera det nya diagrammet med exempelseriedata och inställningar; false för att skapa diagrammet utan serier och med endast minimal konfiguration, vilket gör skapandet snabbare. |

### Return Value

Det nyss skapade [`IChart`](../../../aspose.slides.charts/ichart).

### See Also

* gränssnitt [IChart](../../../aspose.slides.charts/ichart)
* enum [ChartType](../../../aspose.slides.charts/charttype)
* klass [ShapeCollection](../../shapecollection)
* namnrymd [Aspose.Slides](../../shapecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->