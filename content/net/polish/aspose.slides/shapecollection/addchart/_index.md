---
title: AddChart
second_title: Aspose.Sildes dla .NET – odniesienie API
description: Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami oraz dodaje go na koniec kolekcji kształtów.
type: docs
weight: 100
url: /pl/aspose.slides/shapecollection/addchart/
---
## AddChart(ChartType, float, float, float, float) {#addchart}

Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami oraz dodaje go na koniec kolekcji kształtów.

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| type | ChartType | Typ wykresu do dodania. |
| x | Single | Współrzędna x nowego wykresu, w punktach. |
| y | Single | Współrzędna y nowego wykresu, w punktach. |
| width | Single | Szerokość wykresu, w punktach. |
| height | Single | Wysokość wykresu, w punktach. |

### Wartość zwracana

Nowo utworzony [`IChart`](../../../aspose.slides.charts/ichart).

### Przykłady

Poniższy przykład pokazuje, jak utworzyć wykres w prezentacji PowerPoint.

```csharp
[C#]
// Tworzy instancję klasy Presentation, która reprezentuje plik PPTX
using(Presentation pres = new Presentation()) {
  // Uzyskuje dostęp do pierwszego slajdu
  ISlide sld = pres.Slides[0];
  // Dodaje wykres z domyślnymi danymi
  IChart chart = sld.Shapes.AddChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
  // Ustawia tytuł wykresu
  chart.ChartTitle.AddTextFrameForOverriding("Sample Title");
  chart.ChartTitle.TextFrameForOverriding.TextFrameFormat.CenterText = NullableBool.True;
  chart.ChartTitle.Height = 20;
  chart.HasTitle = true;
  // Ustawia pierwszą serię, aby wyświetlała wartości
  chart.ChartData.Series[0].Labels.DefaultDataLabelFormat.ShowValue = true;
  // Ustawia indeks arkusza danych wykresu
  int defaultWorksheetIndex = 0;
  // Pobiera arkusz danych wykresu
  IChartDataWorkbook fact = chart.ChartData.ChartDataWorkbook;
  // Usuwa domyślnie wygenerowane serie i kategorie
  chart.ChartData.Series.Clear();
  chart.ChartData.Categories.Clear();
  int s = chart.ChartData.Series.Count;
  s = chart.ChartData.Categories.Count;
  // Dodaje nowe serie
  chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.Type);
  chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.Type);
  // Dodaje nowe kategorie
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
  // Pobiera pierwszą serię wykresu
  IChartSeries series = chart.ChartData.Series[0];
  // Wypełnia dane serii
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 1, 1, 20));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 2, 1, 50));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 3, 1, 30));
  // Ustawia kolor wypełnienia dla serii
  series.Format.Fill.FillType = FillType.Solid;
  series.Format.Fill.SolidFillColor.Color = Color.Red;
  // Pobiera drugą serię wykresu
  series = chart.ChartData.Series[1];
  // Wypełnia dane serii
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 1, 2, 30));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 2, 2, 10));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 3, 2, 60));
  // Ustawia kolor wypełnienia dla serii
  series.Format.Fill.FillType = FillType.Solid;
  series.Format.Fill.SolidFillColor.Color = Color.Green;
  // Ustawia pierwszą etykietę, aby wyświetlała nazwę kategorii
  IDataLabel lbl = series.DataPoints[0].Label;
  lbl.DataLabelFormat.ShowCategoryName = true;
  lbl = series.DataPoints[1].Label;
  lbl.DataLabelFormat.ShowSeriesName = true;
  // Ustawia serię, aby wyświetlała wartość dla trzeciej etykiety
  lbl = series.DataPoints[2].Label;
  lbl.DataLabelFormat.ShowValue = true;
  lbl.DataLabelFormat.ShowSeriesName = true;
  lbl.DataLabelFormat.Separator = "/";
  // Zapisuje plik PPTX na dysku
  pres.Save("AsposeChart_out.pptx", SaveFormat.Pptx);
}
```

### Zobacz także

* interfejs [IChart](../../../aspose.slides.charts/ichart)
* wyliczenie [ChartType](../../../aspose.slides.charts/charttype)
* klasa [ShapeCollection](../../shapecollection)
* przestrzeń nazw [Aspose.Slides](../../shapecollection)
* biblioteka [Aspose.Slides](../../../)

---

## AddChart(ChartType, float, float, float, float, bool) {#addchart_1}

Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami oraz dodaje go na koniec kolekcji kształtów.

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height, 
    bool initWithSample)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| type | ChartType | Typ wykresu do dodania. |
| x | Single | Współrzędna x nowego wykresu, w punktach. |
| y | Single | Współrzędna y nowego wykresu, w punktach. |
| width | Single | Szerokość wykresu, w punktach. |
| height | Single | Wysokość wykresu, w punktach. |
| initWithSample | Boolean | Prawda, aby zainicjalizować nowy wykres przykładowymi danymi serii i ustawieniami; fałsz, aby utworzyć wykres bez serii i tylko z minimalnymi ustawieniami, co przyspiesza tworzenie. |

### Wartość zwracana

Nowo utworzony [`IChart`](../../../aspose.slides.charts/ichart).

### Zobacz także

* interfejs [IChart](../../../aspose.slides.charts/ichart)
* wyliczenie [ChartType](../../../aspose.slides.charts/charttype)
* klasa [ShapeCollection](../../shapecollection)
* przestrzeń nazw [Aspose.Slides](../../shapecollection)
* biblioteka [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->