---
title: AddChart
second_title: Aspose.Sildes για .NET API Αναφορά
description: Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεων και το προσθέτει στο τέλος της συλλογής σχήματος.
type: docs
weight: 100
url: /el/aspose.slides/shapecollection/addchart/
---
## AddChart(ChartType, float, float, float, float) {#addchart}

Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεων, και το προσθέτει στο τέλος της συλλογής σχήματος.

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | ChartType | Ο τύπος του γραφήματος που θα προστεθεί. |
| x | Single | Η συντεταγμένη x του νέου γραφήματος, σε σημεία. |
| y | Single | Η συντεταγμένη y του νέου γραφήματος, σε σημεία. |
| width | Single | Το πλάτος του γραφήματος, σε σημεία. |
| height | Single | Το ύψος του γραφήματος, σε σημεία. |

### Τιμή επιστροφής

Το νεοδημιουργημένο [`IChart`](../../../aspose.slides.charts/ichart).

### Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς να δημιουργήσετε ένα Chart σε παρουσίαση PowerPoint.

```csharp
[C#]
// Δημιουργεί ένα αντικείμενο της κλάσης Presentation που αντιπροσωπεύει ένα αρχείο PPTX
using(Presentation pres = new Presentation()) {
  // Προσπελαύνει την πρώτη διαφάνεια
  ISlide sld = pres.Slides[0];
  // Προσθέτει ένα γράφημα με τα προεπιλεγμένα δεδομένα του
  IChart chart = sld.Shapes.AddChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
  // Ορίζει τον τίτλο του γραφήματος
  chart.ChartTitle.AddTextFrameForOverriding("Sample Title");
  chart.ChartTitle.TextFrameForOverriding.TextFrameFormat.CenterText = NullableBool.True;
  chart.ChartTitle.Height = 20;
  chart.HasTitle = true;
  // Ορίζει τη πρώτη σειρά να εμφανίζει τιμές
  chart.ChartData.Series[0].Labels.DefaultDataLabelFormat.ShowValue = true;
  // Ορίζει το δείκτη για το φύλλο δεδομένων του γραφήματος
  int defaultWorksheetIndex = 0;
  // Αποκτά το φύλλο εργασίας δεδομένων του γραφήματος
  IChartDataWorkbook fact = chart.ChartData.ChartDataWorkbook;
  // Διαγράφει τις προεπιλεγμένες παραγόμενες σειρές και κατηγορίες
  chart.ChartData.Series.Clear();
  chart.ChartData.Categories.Clear();
  int s = chart.ChartData.Series.Count;
  s = chart.ChartData.Categories.Count;
  // Προσθέτει νέες σειρές
  chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.Type);
  chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.Type);
  // Προσθέτει νέες κατηγορίες
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
  // Παίρνει την πρώτη σειρά γραφήματος
  IChartSeries series = chart.ChartData.Series[0];
  // Συμπληρώνει τα δεδομένα της σειράς
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 1, 1, 20));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 2, 1, 50));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 3, 1, 30));
  // Ορίζει το χρώμα γεμίσματος για τη σειρά
  series.Format.Fill.FillType = FillType.Solid;
  series.Format.Fill.SolidFillColor.Color = Color.Red;
  // Παίρνει τη δεύτερη σειρά γραφήματος
  series = chart.ChartData.Series[1];
  // Συμπληρώνει τα δεδομένα της σειράς
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 1, 2, 30));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 2, 2, 10));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 3, 2, 60));
  // Ορίζει το χρώμα γεμίσματος για τη σειρά
  series.Format.Fill.FillType = FillType.Solid;
  series.Format.Fill.SolidFillColor.Color = Color.Green;
  // Ορίζει την πρώτη ετικέτα να εμφανίζει το όνομα Κατηγορίας
  IDataLabel lbl = series.DataPoints[0].Label;
  lbl.DataLabelFormat.ShowCategoryName = true;
  lbl = series.DataPoints[1].Label;
  lbl.DataLabelFormat.ShowSeriesName = true;
  // Ορίζει τη σειρά να εμφανίζει την τιμή για την τρίτη ετικέτα
  lbl = series.DataPoints[2].Label;
  lbl.DataLabelFormat.ShowValue = true;
  lbl.DataLabelFormat.ShowSeriesName = true;
  lbl.DataLabelFormat.Separator = "/";
  // Αποθηκεύει το αρχείο PPTX στο δίσκο
  pres.Save("AsposeChart_out.pptx", SaveFormat.Pptx);
}
```

### Δείτε επίσης

* Διεπαφή [IChart](../../../aspose.slides.charts/ichart)
* Απαρίθμηση [ChartType](../../../aspose.slides.charts/charttype)
* Κλάση [ShapeCollection](../../shapecollection)
* Χώρος ονομάτων [Aspose.Slides](../../shapecollection)
* Συναρμολόγηση [Aspose.Slides](../../../)

---

## AddChart(ChartType, float, float, float, float, bool) {#addchart_1}

Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεων, και το προσθέτει στο τέλος της συλλογής σ_shape_.

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height, 
    bool initWithSample)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | ChartType | Ο τύπος του γραφήματος που θα προστεθεί. |
| x | Single | Η συντεταγμένη x του νέου γραφήματος, σε σημεία. |
| y | Single | Η συντεταγμένη y του νέου γραφήματος, σε σημεία. |
| width | Single | Το πλάτος του γραφήματος, σε σημεία. |
| height | Single | Το ύψος του γραφήματος, σε σημεία. |
| initWithSample | Boolean | Αληθές για την αρχικοποίηση του νέου γραφήματος με δείγμα δεδομένων σειράς και ρυθμίσεων· ψευδές για τη δημιουργία του γραφήματος χωρίς σειρά και μόνο ελάχιστες ρυθμίσεις, κάτι που επιταχύνει τη δημιουργία. |

### Τιμή επιστροφής

Το νεοδημιουργημένο [`IChart`](../../../aspose.slides.charts/ichart).

### Δείτε επίσης

* Διεπαφή [IChart](../../../aspose.slides.charts/ichart)
* Απαρίθμηση [ChartType](../../../aspose.slides.charts/charttype)
* Κλάση [ShapeCollection](../../shapecollection)
* Χώρος ονομάτων [Aspose.Slides](../../shapecollection)
* Συναρμολόγηση [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->