---
title: ExcelWorkbookImporter
second_title: Aspose.Slides για Android μέσω Αναφοράς API Java
description: Παρέχει λειτουργικότητα για την εισαγωγή περιεχομένου από βιβλίο εργασίας Excel σε μια παρουσίαση.
type: docs
url: /el/com.aspose.slides/excelworkbookimporter/
---
**Κληρονομικότητα:**
java.lang.Object
```
public class ExcelWorkbookImporter
```

Παρέχει λειτουργικότητα για την εισαγωγή περιεχομένου από βιβλίο εργασίας Excel σε μια παρουσίαση.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-) | Ανακτά ένα διάγραμμα από το καθορισμένο βιβλίο εργασίας Excel και το προσθέτει στο τέλος της δεδομένης συλλογής σχημάτων στις καθορισμένες συντεταγμένες. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-) | Ανακτά ένα διάγραμμα από το καθορισμένο βιβλίο εργασίας Excel και το προσθέτει στο τέλος της δεδομένης συλλογής σχημάτων στις καθορισμένες συντεταγμένες. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-) | Ανακτά ένα διάγραμμα από το καθορισμένο βιβλίο εργασίας Excel και το προσθέτει στο τέλος της δεδομένης συλλογής σχημάτων στις καθορισμένες συντεταγμένες. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-) | Ανακτά ένα διάγραμμα από το καθορισμένο βιβλίο εργασίας Excel και το προσθέτει στο τέλος της δεδομένης συλλογής σχημάτων στις καθορισμένες συντεταγμένες. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-) | Ανακτά έναν πίνακα από το καθορισμένο βιβλίο εργασίας Excel και τον προσθέτει στο τέλος της δεδομένης συλλογής σχημάτων στις καθορισμένες συντεταγμένες. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-) | Ανακτά έναν πίνακα από το καθορισμένο αρχείο βιβλίου εργασίας Excel και τον προσθέτει στο τέλος της δεδομένης συλλογής σχημάτων στις καθορισμένες συντεταγμένες. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-) | Ανακτά έναν πίνακα από το καθορισμένο αρχείο βιβλίου εργασίας Excel και τον προσθέτει στο τέλος της δεδομένης συλλογής σχημάτων στις καθορισμένες συντεταγμένες. |
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)
```


Ανακτά ένα διάγραμμα από το καθορισμένο βιβλίο εργασίας Excel και το προσθέτει στο τέλος της δεδομένης συλλογής σχημάτων στις καθορισμένες συντεταγμένες.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addChartFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, wb, worksheetName, chartName, false);
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Η συλλογή σχημάτων στην οποία θα προστεθεί το διάγραμμα. |
| x | float | Η συντεταγμένη X για την τοποθέτηση του διαγράμματος. |
| y | float | Η συντεταγμένη Y για την τοποθέτηση του διαγράμματος. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Το βιβλίο εργασίας Excel. |
| worksheetName | java.lang.String | Το όνομα του φύλλου εργασίας που περιέχει το διάγραμμα. |
| chartIndex | int | Ο δείκτης μηδενικής βάσης του σχήματος διαγράμματος προς εισαγωγή. Αυτός ο δείκτης μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο [IExcelDataWorkbook.getChartsFromWorksheet(String)](../../com.aspose.slides/iexceldataworkbook\#getChartsFromWorksheet-String-). |
| embedAllWorkbook | boolean | Αν είναι true, ολόκληρο το βιβλίο εργασίας θα ενσωματωθεί στο διάγραμμα· αν είναι false, μόνο τα δεδομένα του διαγράμματος θα ενσωματωθούν. |

**Επιστρέφει:**
[IChart](../../com.aspose.slides/ichart) - Το διάγραμμα που προστέθηκε στη συλλογή σχημάτων.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)
```


Ανακτά ένα διάγραμμα από το καθορισμένο βιβλίο εργασίας Excel και το προσθέτει στο τέλος της δεδομένης συλλογής σχημάτων στις καθορισμένες συντεταγμένες.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  Presentation pres = new Presentation();
>  try {
>      String worksheetName = "worksheet name";
>      Dictionary.Enumerator<Integer, String> worksheetCharts = wb.getChartsFromWorksheet(worksheetName).iterator();
>      while (worksheetCharts.hasNext())
>      {
>          KeyValuePair<Integer, String> chart = worksheetCharts.next();
>          ISlide slide = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>          ExcelWorkbookImporter.addChartFromWorkbook(slide.getShapes(), 10, 10, wb, worksheetName, chart.getKey(), false);
>      }
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Η συλλογή σχημάτων στην οποία θα προστεθεί το διάγραμμα. |
| x | float | Η συντεταγμένη X για την τοποθέτηση του διαγράμματος. |
| y | float | Η συντεταγμένη Y για την τοποθέτηση του διαγράμματος. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Το βιβλίο εργασίας Excel. |
| worksheetName | java.lang.String | Το όνομα του φύλλου εργασίας που περιέχει το διάγραμμα. |
| chartName | java.lang.String | Το όνομα του διαγράμματος που θα προστεθεί. |
| embedAllWorkbook | boolean | Αν είναι true, ολόκληρο το βιβλίο εργασίας θα ενσωματωθεί στο διάγραμμα· αν είναι false, μόνο τα δεδομένα του διαγράμματος θα ενσωματωθούν. |

**Επιστρέφει:**
[IChart](../../com.aspose.slides/ichart) - Το διάγραμμα που προστέθηκε στη συλλογή σχημάτων.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)
```


Ανακτά ένα διάγραμμα από το καθορισμένο βιβλίο εργασίας Excel και το προσθέτει στο τέλος της δεδομένης συλλογής σχημάτων στις καθορισμένες συντεταγμένες.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fStream = new FileInputStream(workbookPath);
>      ExcelWorkbookImporter.addChartFromWorkbook(pres.getLayoutSlides().get_Item(0).getShapes(), 10, 10, fStream, worksheetName, chartName, true);
>      fStream.close();
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Η συλλογή σχημάτων στην οποία θα προστεθεί το διάγραμμα. |
| x | float | Η συντεταγμένη X για την τοποθέτηση του διαγράμματος. |
| y | float | Η συντεταγμένη Y για την τοποθέτηση του διαγράμματος. |
| workbookStream | java.io.InputStream | Μια ροή που περιέχει τα δεδομένα του βιβλίου εργασίας. |
| worksheetName | java.lang.String | Το όνομα του φύλλου εργασίας που περιέχει το διάγραμμα. |
| chartName | java.lang.String | Το όνομα του διαγράμματος που θα προστεθεί. |
| embedAllWorkbook | boolean | Αν είναι true, ολόκληρο το βιβλίο εργασίας θα ενσωματωθεί στο διάγραμμα· αν είναι false, μόνο τα δεδομένα του διαγράμματος θα ενσωματωθούν. |

**Επιστρέφει:**
[IChart](../../com.aspose.slides/ichart) - Το διάγραμμα που προστέθηκε στη συλλογή σχημάτων.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)
```


Ανακτά ένα διάγραμμα από το καθορισμένο βιβλίο εργασίας Excel και το προσθέτει στο τέλος της δεδομένης συλλογής σχημάτων στις καθορισμένες συντεταγμένες.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addChartFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, workbookPath, worksheetName, chartName, false);
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Η συλλογή σχημάτων στην οποία θα προστεθεί το διάγραμμα. |
| x | float | Η συντεταγμένη X για την τοποθέτηση του διαγράμματος. |
| y | float | Η συντεταγμένη Y για την τοποθέτηση του διαγράμματος. |
| workbookPath | java.lang.String | Η διαδρομή του αρχείου στο βιβλίο εργασίας που περιέχει το διάγραμμα. |
| worksheetName | java.lang.String | Το όνομα του φύλλου εργασίας που περιέχει το διάγραμμα. |
| chartName | java.lang.String | Το όνομα του διαγράμματος που θα προστεθεί. |
| embedWorkbook | boolean | Αν είναι true, το βιβλίο εργασίας θα ενσωματωθεί στο διάγραμμα· αν είναι false, το διάγραμμα θα συνδεθεί με το εξωτερικό βιβλίο εργασίας. |

**Επιστρέφει:**
[IChart](../../com.aspose.slides/ichart) - Το διάγραμμα που προστέθηκε στη συλλογή σχημάτων.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)
```


Ανακτά έναν πίνακα από το καθορισμένο βιβλίο εργασίας Excel και τον προσθέτει στο τέλος της δεδομένης συλλογής σχημάτων στις καθορισμένες συντεταγμένες.

--------------------

> ```
> IExcelDataWorkbook workbook = new ExcelDataWorkbook(testFile);
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addTableFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, workbook, worksheetName, "A1:D10");
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Η συλλογή σχημάτων στην οποία θα προστεθεί ο πίνακας. |
| x | float | Η συντεταγμένη X για την τοποθέτηση του πίνακα. |
| y | float | Η συντεταγμένη Y για την τοποθέτηση του πίνακα. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Το βιβλίο εργασίας Excel. |
| worksheetName | java.lang.String | Το όνομα του φύλλου εργασίας που περιέχει τον πίνακα. |
| cellRange | java.lang.String | Το εύρος κελιών που ορίζει τον πίνακα (για παράδειγμα, "A1:D10"). |

**Επιστρέφει:**
[ITable](../../com.aspose.slides/itable) - Ο πίνακας που προστέθηκε στη συλλογή σχημάτων.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)
```


Ανακτά έναν πίνακα από το καθορισμένο αρχείο βιβλίου εργασίας Excel και τον προσθέτει στο τέλος της δεδομένης συλλογής σχημάτων στις καθορισμένες συντεταγμένες.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addTableFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, workbookPath, worksheetName, "A1:D10");
>      pres.save("result.pptx", SaveFormat.Pptx);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Η συλλογή σχημάτων στην οποία θα προστεθεί ο πίνακας. |
| x | float | Η συντεταγμένη X για την τοποθέτηση του πίνακα. |
| y | float | Η συντεταγμένη Y για την τοποθέτηση του πίνακα. |
| workbookPath | java.lang.String | Η διαδρομή του αρχείου βιβλίου εργασίας Excel. |
| worksheetName | java.lang.String | Το όνομα του φύλλου εργασίας που περιέχει τον πίνακα. |
| cellRange | java.lang.String | Το εύρος κελιών που ορίζει τον πίνακα (για παράδειγμα, "A1:D10"). |

**Επιστρέφει:**
[ITable](../../com.aspose.slides/itable) - Ο πίνακας που προστέθηκε στη συλλογή σχημάτων.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)
```


Ανακτά έναν πίνακα από το καθορισμένο αρχείο βιβλίου εργασίας Excel και τον προσθέτει στο τέλος της δεδομένης συλλογής σχημάτων στις καθορισμένες συντεταγμένες.

--------------------

> ```
> FileInputStream fStream = new FileInputStream(workbookPath);
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addTableFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, fStream, worksheetName, "A1:D10");
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Η συλλογή σχημάτων στην οποία θα προστεθεί ο πίνακας. |
| x | float | Η συντεταγμένη X για την τοποθέτηση του πίνακα. |
| y | float | Η συντεταγμένη Y για την τοποθέτηση του πίνακα. |
| workbookStream | java.io.InputStream | Μια ροή που περιέχει τα δεδομένα του βιβλίου εργασίας. |
| worksheetName | java.lang.String | Το όνομα του φύλλου εργασίας που περιέχει τον πίνακα. |
| cellRange | java.lang.String | Το εύρος κελιών που ορίζει τον πίνακα (για παράδειγμα, "A1:D10"). |

**Επιστρέφει:**
[ITable](../../com.aspose.slides/itable) - Ο πίνακας που προστέθηκε στη συλλογή σχημάτων.