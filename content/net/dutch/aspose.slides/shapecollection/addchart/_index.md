---
title: AddChart
second_title: Aspose.Sildes voor .NET API-referentie
description: Maakt een nieuw diagram, initialiseert het met voorbeeldreeksgegevens en instellingen, en voegt het toe aan het einde van de shape collection.
type: docs
weight: 100
url: /nl/aspose.slides/shapecollection/addchart/
---
## AddChart(ChartType, float, float, float, float) {#addchart}

Maakt een nieuw Chart, initialiseert het met voorbeeldreeksgegevens en instellingen, en voegt het toe aan het einde van de shape collection.

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | ChartType | Het type diagram dat moet worden toegevoegd. |
| x | Single | De x-coördinaat van het nieuwe diagram, in points. |
| y | Single | De y-coördinaat van het nieuwe diagram, in points. |
| width | Single | De breedte van het diagram, in points. |
| height | Single | De hoogte van het diagram, in points. |

### Retourwaarde

The newly created [`IChart`](../../../aspose.slides.charts/ichart).

### Voorbeelden

The following example shows how to create Chart in PowerPoint Presentation.

```csharp
[C#]
// Instantieert de Presentation-klasse die een PPTX-bestand vertegenwoordigt
using(Presentation pres = new Presentation()) {
  // Verkrijgt de eerste dia
  ISlide sld = pres.Slides[0];
  // Voegt een diagram toe met de standaardgegevens
  IChart chart = sld.Shapes.AddChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
  // Stelt de diagramtitel in
  chart.ChartTitle.AddTextFrameForOverriding("Sample Title");
  chart.ChartTitle.TextFrameForOverriding.TextFrameFormat.CenterText = NullableBool.True;
  chart.ChartTitle.Height = 20;
  chart.HasTitle = true;
  // Stelt de eerste reeks in om waarden weer te geven
  chart.ChartData.Series[0].Labels.DefaultDataLabelFormat.ShowValue = true;
  // Stelt de index in voor het diagramgegevensblad
  int defaultWorksheetIndex = 0;
  // Haalt het werkblad met diagramgegevens op
  IChartDataWorkbook fact = chart.ChartData.ChartDataWorkbook;
  // Verwijdert de standaardgegenereerde reeksen en categorieën
  chart.ChartData.Series.Clear();
  chart.ChartData.Categories.Clear();
  int s = chart.ChartData.Series.Count;
  s = chart.ChartData.Categories.Count;
  // Voegt nieuwe reeksen toe
  chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.Type);
  chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.Type);
  // Voegt nieuwe categorieën toe
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
  // Haalt de eerste diagramreeks op
  IChartSeries series = chart.ChartData.Series[0];
  // Vult de reeksen met gegevens
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 1, 1, 20));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 2, 1, 50));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 3, 1, 30));
  // Stelt de opvulkleur in voor de reeks
  series.Format.Fill.FillType = FillType.Solid;
  series.Format.Fill.SolidFillColor.Color = Color.Red;
  // Haalt de tweede diagramreeks op
  series = chart.ChartData.Series[1];
  // Vult de reeksen met gegevens
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 1, 2, 30));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 2, 2, 10));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 3, 2, 60));
  // Stelt de opvulkleur in voor de reeks
  series.Format.Fill.FillType = FillType.Solid;
  series.Format.Fill.SolidFillColor.Color = Color.Green;
  // Stelt het eerste label in om de categorienaam weer te geven
  IDataLabel lbl = series.DataPoints[0].Label;
  lbl.DataLabelFormat.ShowCategoryName = true;
  lbl = series.DataPoints[1].Label;
  lbl.DataLabelFormat.ShowSeriesName = true;
  // Stelt de reeks in om de waarde voor het derde label weer te geven
  lbl = series.DataPoints[2].Label;
  lbl.DataLabelFormat.ShowValue = true;
  lbl.DataLabelFormat.ShowSeriesName = true;
  lbl.DataLabelFormat.Separator = "/";
  // Slaat het PPTX-bestand op schijf
  pres.Save("AsposeChart_out.pptx", SaveFormat.Pptx);
}
```

### Zie ook

* interface [IChart](../../../aspose.slides.charts/ichart)
* enumeratie [ChartType](../../../aspose.slides.charts/charttype)
* klasse [ShapeCollection](../../shapecollection)
* naamruimte [Aspose.Slides](../../shapecollection)
* assemblage [Aspose.Slides](../../../)

---

## AddChart(ChartType, float, float, float, float, bool) {#addchart_1}

Maakt een nieuw Chart, initialiseert het met voorbeeldreeksgegevens en instellingen, en voegt het toe aan het einde van de shape collection.

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height, 
    bool initWithSample)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | ChartType | Het type diagram dat moet worden toegevoegd. |
| x | Single | De x-coördinaat van het nieuwe diagram, in points. |
| y | Single | De y-coördinaat van het nieuwe diagram, in points. |
| width | Single | De breedte van het diagram, in points. |
| height | Single | De hoogte van het diagram, in points. |
| initWithSample | Boolean | True om de nieuwe Chart te initialiseren met voorbeeldreeksgegevens en -instellingen; false om de Chart te maken zonder reeksen en alleen minimale instellingen, waardoor de creatie sneller gaat. |

### Retourwaarde

The newly created [`IChart`](../../../aspose.slides.charts/ichart).

### Zie ook

* interface [IChart](../../../aspose.slides.charts/ichart)
* enumeratie [ChartType](../../../aspose.slides.charts/charttype)
* klasse [ShapeCollection](../../shapecollection)
* naamruimte [Aspose.Slides](../../shapecollection)
* assemblage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->