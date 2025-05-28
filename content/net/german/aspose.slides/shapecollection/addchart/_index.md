---
title: AddChart
second_title: Aspose.Slides für .NET API-Referenz
description: Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten und Einstellungen und fügt es am Ende der Sammlung hinzu.
type: docs
weight: 100
url: /de/aspose.slides/shapecollection/addchart/
---

## AddChart(ChartType, float, float, float, float) {#addchart}

Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten und Einstellungen und fügt es am Ende der Sammlung hinzu.

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | ChartType | Diagrammtyp. |
| x | Single | X-Koordinate eines neuen Diagramms. |
| y | Single | Y-Koordinate eines neuen Diagramms. |
| width | Single | Breite des Diagramms. |
| height | Single | Höhe des Diagramms. |

### Rückgabewert

Erstelltes Diagramm.

### Beispiele

Das folgende Beispiel zeigt, wie man ein Diagramm in einer PowerPoint-Präsentation erstellt.

```csharp
[C#]
// Instanziiert die Presentation-Klasse, die eine PPTX-Datei darstellt
using(Presentation pres = new Presentation()) {
  // Greift auf die erste Folie zu
  ISlide sld = pres.Slides[0];
  // Fügt ein Diagramm mit den Standarddaten hinzu
  IChart chart = sld.Shapes.AddChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
  // Setzt den Diagrammtitel
  chart.ChartTitle.AddTextFrameForOverriding("Beispieltitel");
  chart.ChartTitle.TextFrameForOverriding.TextFrameFormat.CenterText = NullableBool.True;
  chart.ChartTitle.Height = 20;
  chart.HasTitle = true;
  // Setzt die erste Reihe so, dass Werte angezeigt werden
  chart.ChartData.Series[0].Labels.DefaultDataLabelFormat.ShowValue = true;
  // Setzt den Index für das Diagrammdatenblatt
  int defaultWorksheetIndex = 0;
  // Erhält das Diagrammdatenarbeitsblatt
  IChartDataWorkbook fact = chart.ChartData.ChartDataWorkbook;
  // Löscht die standardmäßig erstellen Serien und Kategorien
  chart.ChartData.Series.Clear();
  chart.ChartData.Categories.Clear();
  int s = chart.ChartData.Series.Count;
  s = chart.ChartData.Categories.Count;
  // Fügt neue Serien hinzu
  chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 0, 1, "Reihe 1"), chart.Type);
  chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 0, 2, "Reihe 2"), chart.Type);
  // Fügt neue Kategorien hinzu
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 1, 0, "Kategorie 1"));
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 2, 0, "Kategorie 2"));
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 3, 0, "Kategorie 3"));
  // Nimmt die erste Diagrammreihe
  IChartSeries series = chart.ChartData.Series[0];
  // Füllt die Reihendaten
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 1, 1, 20));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 2, 1, 50));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 3, 1, 30));
  // Setzt die Füllfarbe für die Reihe
  series.Format.Fill.FillType = FillType.Solid;
  series.Format.Fill.SolidFillColor.Color = Color.Red;
  // Nimmt die zweite Diagrammreihe
  series = chart.ChartData.Series[1];
  // Füllt die Reihendaten
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 1, 2, 30));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 2, 2, 10));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 3, 2, 60));
  // Setzt die Füllfarbe für die Reihe
  series.Format.Fill.FillType = FillType.Solid;
  series.Format.Fill.SolidFillColor.Color = Color.Green;
  // Setzt das erste Label so, dass der Kategoriename angezeigt wird
  IDataLabel lbl = series.DataPoints[0].Label;
  lbl.DataLabelFormat.ShowCategoryName = true;
  lbl = series.DataPoints[1].Label;
  lbl.DataLabelFormat.ShowSeriesName = true;
  // Setzt die Reihe so, dass der Wert für das dritte Label angezeigt wird
  lbl = series.DataPoints[2].Label;
  lbl.DataLabelFormat.ShowValue = true;
  lbl.DataLabelFormat.ShowSeriesName = true;
  lbl.DataLabelFormat.Separator = "/";
  // Speichert die PPTX-Datei auf der Festplatte
  pres.Save("AsposeChart_out.pptx", SaveFormat.Pptx);
}
```

### Siehe auch

* Schnittstelle [IChart](../../../aspose.slides.charts/ichart)
* Aufzählung [ChartType](../../../aspose.slides.charts/charttype)
* Klasse [ShapeCollection](../../shapecollection)
* Namespace [Aspose.Slides](../../shapecollection)
* Assembly [Aspose.Slides](../../../)

---

## AddChart(ChartType, float, float, float, float, bool) {#addchart_1}

Erstellt ein neues Diagramm und fügt es am Ende der Sammlung hinzu.

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height, 
    bool initWithSample)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | ChartType | Diagrammtyp. |
| x | Single | X-Koordinate eines neuen Diagramms. |
| y | Single | Y-Koordinate eines neuen Diagramms. |
| width | Single | Breite des Diagramms. |
| height | Single | Höhe des Diagramms. |
| initWithSample | Boolean | Wenn true, wird das neue Diagramm mit Beispieldaten und Einstellungen initialisiert. Wenn false, hat das neue Diagramm keine Serien und minimale Einstellungen. In diesem Fall wird die Diagrammerstellung schneller sein. |

### Rückgabewert

Erstelltes Diagramm.

### Siehe auch

* Schnittstelle [IChart](../../../aspose.slides.charts/ichart)
* Aufzählung [ChartType](../../../aspose.slides.charts/charttype)
* Klasse [ShapeCollection](../../shapecollection)
* Namespace [Aspose.Slides](../../shapecollection)
* Assembly [Aspose.Slides](../../../)