---
title: AddChart
second_title: Riferimento API Aspose.Sildes per .NET
description: Crea un nuovo chart, lo inizializza con dati di serie di esempio e impostazioni e lo aggiunge alla fine della shape collection.
type: docs
weight: 100
url: /it/aspose.slides/shapecollection/addchart/
---
## AddChart(ChartType, float, float, float, float) {#addchart}

Crea un nuovo chart, lo inizializza con dati di serie di esempio e impostazioni, e lo aggiunge alla fine della shape collection.

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | ChartType | Il tipo di chart da aggiungere. |
| x | Single | La coordinata x del nuovo chart, in punti. |
| y | Single | La coordinata y del nuovo chart, in punti. |
| width | Single | La larghezza del chart, in punti. |
| height | Single | L'altezza del chart, in punti. |

### Valore di ritorno

Il [`IChart`](../../../aspose.slides.charts/ichart) appena creato.

### Esempi

Il seguente esempio mostra come creare Chart in una presentazione PowerPoint.

```csharp
[C#]
// Istanzia la classe Presentation che rappresenta un file PPTX
using(Presentation pres = new Presentation()) {
  // Accede alla prima slide
  ISlide sld = pres.Slides[0];
  // Aggiunge un chart con i dati predefiniti
  IChart chart = sld.Shapes.AddChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
  // Imposta il titolo del chart
  chart.ChartTitle.AddTextFrameForOverriding("Sample Title");
  chart.ChartTitle.TextFrameForOverriding.TextFrameFormat.CenterText = NullableBool.True;
  chart.ChartTitle.Height = 20;
  chart.HasTitle = true;
  // Imposta la prima serie per mostrare i valori
  chart.ChartData.Series[0].Labels.DefaultDataLabelFormat.ShowValue = true;
  // Imposta l'indice per il foglio dati del chart
  int defaultWorksheetIndex = 0;
  // Ottiene il foglio di lavoro dei dati del chart
  IChartDataWorkbook fact = chart.ChartData.ChartDataWorkbook;
  // Elimina le serie e le categorie generate di default
  chart.ChartData.Series.Clear();
  chart.ChartData.Categories.Clear();
  int s = chart.ChartData.Series.Count;
  s = chart.ChartData.Categories.Count;
  // Aggiunge nuove serie
  chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.Type);
  chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.Type);
  // Aggiunge nuove categorie
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
  // Prende la prima serie del chart
  IChartSeries series = chart.ChartData.Series[0];
  // Popola i dati della serie
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 1, 1, 20));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 2, 1, 50));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 3, 1, 30));
  // Imposta il colore di riempimento per la serie
  series.Format.Fill.FillType = FillType.Solid;
  series.Format.Fill.SolidFillColor.Color = Color.Red;
  // Prende la seconda serie del chart
  series = chart.ChartData.Series[1];
  // Popola i dati della serie
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 1, 2, 30));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 2, 2, 10));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 3, 2, 60));
  // Imposta il colore di riempimento per la serie
  series.Format.Fill.FillType = FillType.Solid;
  series.Format.Fill.SolidFillColor.Color = Color.Green;
  // Imposta la prima etichetta per mostrare il nome della Categoria
  IDataLabel lbl = series.DataPoints[0].Label;
  lbl.DataLabelFormat.ShowCategoryName = true;
  lbl = series.DataPoints[1].Label;
  lbl.DataLabelFormat.ShowSeriesName = true;
  // Imposta la serie per mostrare il valore per la terza etichetta
  lbl = series.DataPoints[2].Label;
  lbl.DataLabelFormat.ShowValue = true;
  lbl.DataLabelFormat.ShowSeriesName = true;
  lbl.DataLabelFormat.Separator = "/";
  // Salva il file PPTX su disco
  pres.Save("AsposeChart_out.pptx", SaveFormat.Pptx);
}
```

### Vedi anche

* interfaccia [IChart](../../../aspose.slides.charts/ichart)
* enum [ChartType](../../../aspose.slides.charts/charttype)
* classe [ShapeCollection](../../shapecollection)
* spazio dei nomi [Aspose.Slides](../../shapecollection)
* assembly [Aspose.Slides](../../../)

---

## AddChart(ChartType, float, float, float, float, bool) {#addchart_1}

Crea un nuovo chart, lo inizializza con dati di serie di esempio e impostazioni, e lo aggiunge alla fine della shape collection.

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height, 
    bool initWithSample)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | ChartType | Il tipo di chart da aggiungere. |
| x | Single | La coordinata x del nuovo chart, in punti. |
| y | Single | La coordinata y del nuovo chart, in punti. |
| width | Single | La larghezza del chart, in punti. |
| height | Single | L'altezza del chart, in punti. |
| initWithSample | Boolean | True per inizializzare il nuovo chart con dati di serie di esempio e impostazioni; false per creare il chart senza serie e solo con impostazioni minime, rendendo la creazione più veloce. |

### Valore di ritorno

Il [`IChart`](../../../aspose.slides.charts/ichart) appena creato.

### Vedi anche

* interfaccia [IChart](../../../aspose.slides.charts/ichart)
* enum [ChartType](../../../aspose.slides.charts/charttype)
* classe [ShapeCollection](../../shapecollection)
* spazio dei nomi [Aspose.Slides](../../shapecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->