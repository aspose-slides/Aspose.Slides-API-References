---
title: AddChart
second_title: Aspose.Sildes pro .NET API Reference
description: Vytvoří nový graf, inicializuje jej ukázkovými daty řady a nastaveními a přidá jej na konec kolekce tvarů.
type: docs
weight: 100
url: /cs/aspose.slides/shapecollection/addchart/
---
## AddChart(ChartType, float, float, float, float) {#addchart}

Vytvoří nový graf, inicializuje jej ukázkovými daty řady a nastaveními a přidá jej na konec kolekce tvarů.

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height)
```

| Parameter | Type | Description |
| --- | --- | --- |
| type | ChartType | Typ grafu, který se má přidat. |
| x | Single | Souřadnice x nového grafu v bodech. |
| y | Single | Souřadnice y nového grafu v bodech. |
| width | Single | Šířka grafu v bodech. |
| height | Single | Výška grafu v bodech. |

### Návratová hodnota

Nově vytvořený [`IChart`](../../../aspose.slides.charts/ichart).

### Příklady

Následující příklad ukazuje, jak vytvořit graf v prezentaci PowerPoint.

```csharp
[C#]
// Vytvoří instanci třídy Presentation, která představuje soubor PPTX
using(Presentation pres = new Presentation()) {
  // Přistupuje k první snímku
  ISlide sld = pres.Slides[0];
  // Přidá graf s výchozími daty
  IChart chart = sld.Shapes.AddChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
  // Nastaví nadpis grafu
  chart.ChartTitle.AddTextFrameForOverriding("Sample Title");
  chart.ChartTitle.TextFrameForOverriding.TextFrameFormat.CenterText = NullableBool.True;
  chart.ChartTitle.Height = 20;
  chart.HasTitle = true;
  // Nastaví první sérii, aby zobrazovala hodnoty
  chart.ChartData.Series[0].Labels.DefaultDataLabelFormat.ShowValue = true;
  // Nastaví index listu s daty grafu
  int defaultWorksheetIndex = 0;
  // Získá list s daty grafu
  IChartDataWorkbook fact = chart.ChartData.ChartDataWorkbook;
  // Odstraní výchozí vygenerované řady a kategorie
  chart.ChartData.Series.Clear();
  chart.ChartData.Categories.Clear();
  int s = chart.ChartData.Series.Count;
  s = chart.ChartData.Categories.Count;
  // Přidá nové řady
  chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.Type);
  chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.Type);
  // Přidá nové kategorie
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
  // Získá první sérii grafu
  IChartSeries series = chart.ChartData.Series[0];
  // Naplní data řady
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 1, 1, 20));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 2, 1, 50));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 3, 1, 30));
  // Nastaví barvu výplně řady
  series.Format.Fill.FillType = FillType.Solid;
  series.Format.Fill.SolidFillColor.Color = Color.Red;
  // Získá druhou sérii grafu
  series = chart.ChartData.Series[1];
  // Naplní data řady
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 1, 2, 30));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 2, 2, 10));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 3, 2, 60));
  // Nastaví barvu výplně řady
  series.Format.Fill.FillType = FillType.Solid;
  series.Format.Fill.SolidFillColor.Color = Color.Green;
  // Nastaví první popisek tak, aby zobrazoval název kategorie
  IDataLabel lbl = series.DataPoints[0].Label;
  lbl.DataLabelFormat.ShowCategoryName = true;
  lbl = series.DataPoints[1].Label;
  lbl.DataLabelFormat.ShowSeriesName = true;
  // Nastaví řadu, aby zobrazovala hodnotu pro třetí popisek
  lbl = series.DataPoints[2].Label;
  lbl.DataLabelFormat.ShowValue = true;
  lbl.DataLabelFormat.ShowSeriesName = true;
  lbl.DataLabelFormat.Separator = "/";
  // Uloží soubor PPTX na disk
  pres.Save("AsposeChart_out.pptx", SaveFormat.Pptx);
}
```

### Viz také

* rozhraní [IChart](../../../aspose.slides.charts/ichart)
* výčet [ChartType](../../../aspose.slides.charts/charttype)
* třída [ShapeCollection](../../shapecollection)
* jmenný prostor [Aspose.Slides](../../shapecollection)
* sestavení [Aspose.Slides](../../../)

---

## AddChart(ChartType, float, float, float, float, bool) {#addchart_1}

Vytvoří nový graf, inicializuje jej ukázkovými daty řady a nastaveními a přidá jej na konec kolekce tvarů.

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height, 
    bool initWithSample)
```

| Parameter | Type | Description |
| --- | --- | --- |
| type | ChartType | Typ grafu, který se má přidat. |
| x | Single | Souřadnice x nového grafu v bodech. |
| y | Single | Souřadnice y nového grafu v bodech. |
| width | Single | Šířka grafu v bodech. |
| height | Single | Výška grafu v bodech. |
| initWithSample | Boolean | true pro inicializaci nového grafu ukázkovými daty řady a nastaveními; false pro vytvoření grafu bez řad a pouze s minimálními nastaveními, což urychluje vytvoření. |

### Návratová hodnota

Nově vytvořený [`IChart`](../../../aspose.slides.charts/ichart).

### Viz také

* rozhraní [IChart](../../../aspose.slides.charts/ichart)
* výčet [ChartType](../../../aspose.slides.charts/charttype)
* třída [ShapeCollection](../../shapecollection)
* jmenný prostor [Aspose.Slides](../../shapecollection)
* sestavení [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->