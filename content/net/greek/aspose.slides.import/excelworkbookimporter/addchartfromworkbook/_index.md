---
title: AddChartFromWorkbook
second_title: Aspose.Sildes για .NET API Αναφορά
description: Ανακτά ένα διάγραμμα από το καθορισμένο βιβλίο εργασίας Excel και το προσθέτει στο τέλος της δοθείσας συλλογής σχημάτων στις καθορισμένες συντεταγμένες.
type: docs
weight: 10
url: /el/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## AddChartFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, int, bool) {#addchartfromworkbook}

Ανακτά ένα διάγραμμα από το καθορισμένο βιβλίο εργασίας Excel και το προσθέτει στο τέλος της δοθείσας συλλογής σχημάτων στις καθορισμένες συντεταγμένες.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, int chartIndex, bool embedAllWorkbook)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapes | IShapeCollection | Η συλλογή σχημάτων στην οποία θα προστεθεί το διάγραμμα. |
| x | Single | Η συντεταγμένη X για τη θέση του διαγράμματος. |
| y | Single | Η συντεταγμένη Y για τη θέση του διαγράμματος. |
| workbook | IExcelDataWorkbook | Το βιβλίο εργασίας Excel. |
| worksheetName | String | Το όνομα του φύλλου εργασίας που περιέχει το διάγραμμα. |
| chartIndex | Int32 | Ο μηδενικός δείκτης του σχήματος διαγράμματος που θα εισαχθεί. Αυτός ο δείκτης μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο [`GetChartsFromWorksheet`](../../../aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet). |
| embedAllWorkbook | Boolean | Εάν `true`, ολόκληρο το βιβλίο εργασίας θα ενσωματωθεί στο διάγραμμα· εάν `false`, θα ενσωματωθούν μόνο τα δεδομένα του διαγράμματος. |

### Τιμή επιστροφής

Το διάγραμμα που προστέθηκε στη συλλογή σχημάτων.

### Εξαιρέσεις

| Εξαίρεση | Συνθήκη |
| --- | --- |
| ArgumentException | Εκτοξεύεται όταν οποιαδήποτε απαιτούμενη παράμετρος είναι null, κενή, ή όταν δεν είναι δυνατή η εύρεση του διαγράμματος στο βιβλίο εργασίας. |

### Παραδείγματα

Παράδειγμα:

```csharp
[C#]
IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.Slides[0].Shapes, 10, 10, wb, worksheetName, chartName, false);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Δείτε επίσης

* διεπαφή [IChart](../../../aspose.slides.charts/ichart)
* διεπαφή [IShapeCollection](../../../aspose.slides/ishapecollection)
* διεπαφή [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* κλάση [ExcelWorkbookImporter](../../excelworkbookimporter)
* χώρος ονομάτων [Aspose.Slides.Import](../../excelworkbookimporter)
* συναρμολόγηση [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, string, bool) {#addchartfromworkbook_1}

Ανακτά ένα διάγραμμα από το καθορισμένο βιβλίο εργασίας Excel και το προσθέτει στο τέλος της δοθείσας συλλογής σχημάτων στις καθορισμένες συντεταγμένες.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, string chartName, bool embedAllWorkbook)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapes | IShapeCollection | Η συλλογή σχημάτων στην οποία θα προστεθεί το διάγραμμα. |
| x | Single | Η συντεταγμένη X για τη θέση του διαγράμματος. |
| y | Single | Η συντεταγμένη Y για τη θέση του διαγράμματος. |
| workbook | IExcelDataWorkbook | Το βιβλίο εργασίας Excel. |
| worksheetName | String | Το όνομα του φύλλου εργασίας που περιέχει το διάγραμμα. |
| chartName | String | Το όνομα του διαγράμματος που θα προστεθεί. |
| embedAllWorkbook | Boolean | Εάν `true`, ολόκληρο το βιβλίο εργασίας θα ενσωματωθεί στο διάγραμμα· εάν `false`, θα ενσωματωθούν μόνο τα δεδομένα του διαγράμματος. |

### Τιμή επιστροφής

Το διάγραμμα που προστέθηκε στη συλλογή σχημάτων.

### Εξαιρέσεις

| Εξαίρεση | Συνθήκη |
| --- | --- |
| ArgumentException | Εκτοξεύεται όταν οποιαδήποτε απαιτούμενη παράμετρος είναι null, κενή, ή όταν δεν είναι δυνατή η εύρεση του διαγράμματος στο βιβλίο εργασίας. |

### Παραδείγματα

Παράδειγμα:

```csharp
[C#]
IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    string worksheetName = "worksheet name";
    var worksheetCharts = wb.GetChartsFromWorksheet(worksheetName);
    foreach (var chart in worksheetCharts)
    {
        ISlide slide = pres.Slides.AddEmptySlide(pres.LayoutSlides[0]);
        ExcelWorkbookImporter.AddChartFromWorkbook(slide.Shapes, 10, 10, wb, worksheetName, chart.Key, false);
    }
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Δείτε επίσης

* διεπαφή [IChart](../../../aspose.slides.charts/ichart)
* διεπαφή [IShapeCollection](../../../aspose.slides/ishapecollection)
* διεπαφή [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* κλάση [ExcelWorkbookImporter](../../excelworkbookimporter)
* χώρος ονομάτων [Aspose.Slides.Import](../../excelworkbookimporter)
* συναρμολόγηση [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, Stream, string, string, bool) {#addchartfromworkbook_2}

Ανακτά ένα διάγραμμα από το καθορισμένο βιβλίο εργασίας Excel και το προσθέτει στο τέλος της δοθείσας συλλογής σχημάτων στις καθορισμένες συντεταγμένες.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    Stream workbookStream, string worksheetName, string chartName, bool embedAllWorkbook)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapes | IShapeCollection | Η συλλογή σχημάτων στην οποία θα προστεθεί το διάγραμμα. |
| x | Single | Η συντεταγμένη X για τη θέση του διαγράμματος. |
| y | Single | Η συντεταγμένη Y για τη θέση του διαγράμματος. |
| workbookStream | Stream | Μία ροή που περιέχει τα δεδομένα του βιβλίου εργασίας. |
| worksheetName | String | Το όνομα του φύλλου εργασίας που περιέχει το διάγραμμα. |
| chartName | String | Το όνομα του διαγράμματος που θα προστεθεί. |
| embedAllWorkbook | Boolean | Εάν `true`, ολόκληρο το βιβλίο εργασίας θα ενσωματωθεί στο διάγραμμα· εάν `false`, θα ενσωματωθούν μόνο τα δεδομένα του διαγράμματος. |

### Τιμή επιστροφής

Το διάγραμμα που προστέθηκε στη συλλογή σχημάτων.

### Εξαιρέσεις

| Εξαίρεση | Συνθήκη |
| --- | --- |
| ArgumentException | Εκτοξεύεται όταν οποιαδήποτε απαιτούμενη παράμετρος είναι null, κενή, ή όταν δεν είναι δυνατή η εύρεση του διαγράμματος στο βιβλίο εργασίας. |
| InvalidOperationException | Εκτοξεύεται όταν τα εισερχόμενα δεδομένα βρίσκονται σε μη υποστηριζόμενη μορφή. |

### Παραδείγματα

Παράδειγμα:

```csharp
[C#]
using (var fStream = new FileStream(workbookPath, FileMode.Open, FileAccess.Read))
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.LayoutSlides[0].Shapes, 10, 10, fStream, worksheetName, chartName, true);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Δείτε επίσης

* διεπαφή [IChart](../../../aspose.slides.charts/ichart)
* διεπαφή [IShapeCollection](../../../aspose.slides/ishapecollection)
* κλάση [ExcelWorkbookImporter](../../excelworkbookimporter)
* χώρος ονομάτων [Aspose.Slides.Import](../../excelworkbookimporter)
* συναρμολόγηση [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, string, string, string, bool) {#addchartfromworkbook_3}

Ανακτά ένα διάγραμμα από το καθορισμένο βιβλίο εργασίας Excel και το προσθέτει στο τέλος της δοθείσας συλλογής σχημάτων στις καθορισμένες συντεταγμένες.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    string workbookPath, string worksheetName, string chartName, bool embedWorkbook)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapes | IShapeCollection | Η συλλογή σχημάτων στην οποία θα προστεθεί το διάγραμμα. |
| x | Single | Η συντεταγμένη X για τη θέση του διαγράμματος. |
| y | Single | Η συντεταγμένη Y για τη θέση του διαγράμματος. |
| workbookPath | String | Η διαδρομή αρχείου προς το βιβλίο εργασίας που περιέχει το διάγραμμα. |
| worksheetName | String | Το όνομα του φύλλου εργασίας που περιέχει το διάγραμμα. |
| chartName | String | Το όνομα του διαγράμματος που θα προστεθεί. |
| embedWorkbook | Boolean | Εάν `true`, το βιβλίο εργασίας θα ενσωματωθεί στο διάγραμμα· εάν `false`, το διάγραμμα θα συνδεθεί με το εξωτερικό βιβλίο εργασίας. |

### Τιμή επιστροφής

Το διάγραμμα που προστέθηκε στη συλλογή σχημάτων.

### Εξαιρέσεις

| Εξαίρεση | Συνθήκη |
| --- | --- |
| ArgumentException | Εκτοξεύεται όταν οποιαδήποτε απαιτούμενη παράμετρος είναι null, κενή, ή όταν δεν είναι δυνατή η εύρεση του διαγράμματος στο βιβλίο εργασίας. |
| IOException | Εκτοξεύεται όταν προκύψει σφάλμα I/O κατά την πρόσβαση στο αρχείο. |
| InvalidOperationException | Εκτοξεύεται όταν τα εισερχόμενα δεδομένα βρίσκονται σε μη υποστηριζόμενη μορφή. |

### Παραδείγματα

Παράδειγμα:

```csharp
[C#]
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbookPath, worksheetName, chartName, false);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Δείτε επίσης

* διεπαφή [IChart](../../../aspose.slides.charts/ichart)
* διεπαφή [IShapeCollection](../../../aspose.slides/ishapecollection)
* κλάση [ExcelWorkbookImporter](../../excelworkbookimporter)
* χώρος ονομάτων [Aspose.Slides.Import](../../excelworkbookimporter)
* συναρμολόγηση [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->