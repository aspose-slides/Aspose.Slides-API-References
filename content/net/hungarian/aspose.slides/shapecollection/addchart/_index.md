---
title: AddChart
second_title: Aspose.Sildes .NET API referencia
description: Új diagramot hoz létre, mintapéldány adatokat és beállításokat inicializál, majd a shape gyűjtemény végére adja hozzá.
type: docs
weight: 100
url: /hu/aspose.slides/shapecollection/addchart/
---
## AddChart(ChartType, float, float, float, float) {#addchart}

Új diagramot hoz létre, mintapéldányokat és beállításokat inicializál, majd a shape gyűjtemény végére adja hozzá.

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | ChartType | A hozzáadandó diagram típusa. |
| x | Single | Az új diagram x-koordinátája pontban. |
| y | Single | Az új diagram y-koordinátája pontban. |
| width | Single | A diagram szélessége pontban. |
| height | Single | A diagram magassága pontban. |

### Visszatérési érték

A frissen létrehozott [`IChart`](../../../aspose.slides.charts/ichart).

### Példák

Az alábbi példa bemutatja, hogyan lehet diagramot létrehozni PowerPoint-prezentációban.

```csharp
[C#]
// Létrehozza a Presentation osztályt, amely egy PPTX fájlt képvisel
using(Presentation pres = new Presentation()) {
  // Eléri az első diát
  ISlide sld = pres.Slides[0];
  // Diagramot ad hozzá alapértelmezett adatokkal
  IChart chart = sld.Shapes.AddChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
  // Beállítja a diagram címét
  chart.ChartTitle.AddTextFrameForOverriding("Sample Title");
  chart.ChartTitle.TextFrameForOverriding.TextFrameFormat.CenterText = NullableBool.True;
  chart.ChartTitle.Height = 20;
  chart.HasTitle = true;
  // Az első sorozatot beállítja értékek megjelenítésére
  chart.ChartData.Series[0].Labels.DefaultDataLabelFormat.ShowValue = true;
  // Beállítja a diagram adatlap indexét
  int defaultWorksheetIndex = 0;
  // Lekéri a diagram adat munkalapját
  IChartDataWorkbook fact = chart.ChartData.ChartDataWorkbook;
  // Törli az alapértelmezett generált sorozatot és kategóriákat
  chart.ChartData.Series.Clear();
  chart.ChartData.Categories.Clear();
  int s = chart.ChartData.Series.Count;
  s = chart.ChartData.Categories.Count;
  // Új sorozatokat ad hozzá
  chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.Type);
  chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.Type);
  // Új kategóriákat ad hozzá
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
  // Az első diagram sorozatot veszi
  IChartSeries series = chart.ChartData.Series[0];
  // Feltölti a sorozat adatait
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 1, 1, 20));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 2, 1, 50));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 3, 1, 30));
  // Beállítja a sorozat kitöltőszínét
  series.Format.Fill.FillType = FillType.Solid;
  series.Format.Fill.SolidFillColor.Color = Color.Red;
  // A második diagram sorozatot veszi
  series = chart.ChartData.Series[1];
  // Feltölti a sorozat adatait
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 1, 2, 30));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 2, 2, 10));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 3, 2, 60));
  // Beállítja a sorozat kitöltőszínét
  series.Format.Fill.FillType = FillType.Solid;
  series.Format.Fill.SolidFillColor.Color = Color.Green;
  // Az első címkét beállítja a kategórianév megjelenítésére
  IDataLabel lbl = series.DataPoints[0].Label;
  lbl.DataLabelFormat.ShowCategoryName = true;
  lbl = series.DataPoints[1].Label;
  lbl.DataLabelFormat.ShowSeriesName = true;
  // A sorozatot beállítja a harmadik címke értékének megjelenítésére
  lbl = series.DataPoints[2].Label;
  lbl.DataLabelFormat.ShowValue = true;
  lbl.DataLabelFormat.ShowSeriesName = true;
  lbl.DataLabelFormat.Separator = "/";
  // Mentse a PPTX fájlt a lemezre
  pres.Save("AsposeChart_out.pptx", SaveFormat.Pptx);
}
```

### Lásd még

* interfész [IChart](../../../aspose.slides.charts/ichart)
* enum [ChartType](../../../aspose.slides.charts/charttype)
* osztály [ShapeCollection](../../shapecollection)
* névtér [Aspose.Slides](../../shapecollection)
* összeállítás [Aspose.Slides](../../../)

---

## AddChart(ChartType, float, float, float, float, bool) {#addchart_1}

Új diagramot hoz létre, mintapéldányokat és beállításokat inicializál, majd a shape gyűjtemény végére adja hozzá.

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height, 
    bool initWithSample)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | ChartType | A hozzáadandó diagram típusa. |
| x | Single | Az új diagram x-koordinátája pontban. |
| y | Single | Az új diagram y-koordinátája pontban. |
| width | Single | A diagram szélessége pontban. |
| height | Single | A diagram magassága pontban. |
| initWithSample | Boolean | True esetén a diagramot mintapéldányokkal és beállításokkal inicializálja; false esetén sorok nélkül és csak minimális beállításokkal hozza létre, ami gyorsabb. |

### Visszatérési érték

A frissen létrehozott [`IChart`](../../../aspose.slides.charts/ichart).

### Lásd még

* interfész [IChart](../../../aspose.slides.charts/ichart)
* enum [ChartType](../../../aspose.slides.charts/charttype)
* osztály [ShapeCollection](../../shapecollection)
* névtér [Aspose.Slides](../../shapecollection)
* összeállítás [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->