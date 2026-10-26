---
title: ChartData
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Αντιπροσωπεύει δεδομένα που χρησιμοποιούνται για τη σχεδίαση διαγράμματος.
type: docs
url: /el/com.aspose.slides/chartdata/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IChartData](../../com.aspose.slides/ichartdata)
```
public class ChartData extends DomObject<Chart> implements IChartData
```

Αντιπροσωπεύει δεδομένα που χρησιμοποιούνται για τη σχεδίαση διαγράμματος.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Λαμβάνει το εργοστάσιο κελιών για τη δημιουργία κελιών που χρησιμοποιούνται για σειρές ή κατηγορίες διαγράμματος. |
| [getSeries()](#getSeries--) | Λαμβάνει τις σειρές. |
| [getSeriesGroups()](#getSeriesGroups--) | Λαμβάνει τις ομάδες σειρών. |
| [getCategories()](#getCategories--) | Λαμβάνει τις κύριες κατηγορίες (ή και τις κύριες και δευτερεύουσες κατηγορίες εάν η ιδιότητα \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) είναι ψευδής). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Εάν είναι ψευδής, τότε η ιδιότητα \#getSecondaryCategories.getSecondaryCategories επιστρέφει null και τα δεδομένα στην ιδιότητα \#getCategories.getCategories χρησιμοποιούνται τόσο για τις κύριες όσο και για τις δευτερεύουσες σειρές. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Εάν είναι ψευδής, τότε η ιδιότητα \#getSecondaryCategories.getSecondaryCategories επιστρέφει null και τα δεδομένα στην ιδιότητα \#getCategories.getCategories χρησιμοποιούνται τόσο για τις κύριες όσο και για τις δευτερεύουσες σειρές. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Λαμβάνει τις δευτερεύουσες κατηγορίες εάν η ιδιότητα \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) είναι αληθής. |
| [readWorkbookStream()](#readWorkbookStream--) | Γράφει το εσωτερικά περιέμενο βιβλίο εργασίας Excel σε μια ροή μνήμης. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Αρχικοποιεί το εσωτερικά περιέμενο βιβλίο εργασίας Excel με τιμή καθορισμένη από το χρήστη. |
| [getDataSourceType()](#getDataSourceType--) | Αντιπροσωπεύει τη διαδρομή εξωτερικού βιβλίου εργασίας εάν η πηγή δεδομένων είναι εξωτερική, διαφορετικά null |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Αντιπροσωπεύει την πηγή δεδομένων του διαγράμματος |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Λαμβάνει τον τύπο του ενσωματωμένου βιβλίου εργασίας. |
| [getRange()](#getRange--) | Λαμβάνει την περιοχή δεδομένων του διαγράμματος. |
| [setRange(String formula)](#setRange-java.lang.String-) | Ορίζει την περιοχή δεδομένων του διαγράμματος. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Ορίζει το εξωτερικό βιβλίο εργασίας ως πηγή δεδομένων για το διάγραμμα. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Ορίζει το εξωτερικό βιβλίο εργασίας ως πηγή δεδομένων για το διάγραμμα. |
| [switchRowColumn()](#switchRowColumn--) | Ανταλλάσσει τα δεδομένα κατά τον άξονα. |
### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

Λαμβάνει το εργοστάσιο κελιών για τη δημιουργία κελιών που χρησιμοποιούνται για σειρές ή κατηγορίες διαγράμματος. Μόνο για ανάγνωση [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Επιστρέφει:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

Λαμβάνει τις σειρές. Μόνο για ανάγνωση [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Επιστρέφει:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

Λαμβάνει τις ομάδες σειρών. Μόνο για ανάγνωση [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Κάθε ομάδα σειρών περιέχει σειρές με συνδυάσιμους τύπους. Οι ομάδες συνδυάσιμων τύπων σειρών καθορίζονται και περιγράφονται με το enum CombinableSeriesTypesGroup. Επίσης, κάθε ομάδα σειρών περιέχει σειρές που σχεδιάζονται είτε στον κύριο άξονα είτε στον δευτερεύοντα άξονα (όχι και στις δύο περιπτώσεις στην ίδια ομάδα). Έτσι, η αρχή ομαδοποίησης των σειρών είναι η ομαδοποίηση κατά τύπο ομάδων όπως αναφέρεται παραπάνω και κατά τύπο σχεδιασμού κύριου/δευτερεύοντος άξονα. 2) Η ομάδα σειρών περιέχει ορισμένες ιδιότητες σειρών κοινές για κάθε σειρά στην ομάδα ("ιδιότητες ομάδας σειρών"). Οι "ιδιότητες ομάδας σειρών" στην κλάση ChartSeriesGroup είναι ανάγνωση/εγγραφή. Κάθε "ιδιότητα ομάδας σειρών" μπορεί να έχει μια μόνο για ανάγνωση προβολή στην κλάση ChartSeries.

**Επιστρέφει:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

Λαμβάνει τις κύριες κατηγορίες (ή και τις κύριες και δευτερεύουσες κατηγορίες εάν η ιδιότητα \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) είναι ψευδής). Μόνο για ανάγνωση [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // οι σχετικές κατηγορίες είναι series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // οι σχετικές κατηγορίες είναι series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

Εάν η ιδιότητα \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) είναι ψευδής, τότε η ιδιότητα (\#getSecondaryCategories.getSecondaryCategories) επιστρέφει null και τα δεδομένα στην ιδιότητα \#getCategories.getCategories χρησιμοποιούνται τόσο για τις κύριες όσο και για τις δευτερεύουσες σειρές. Εάν η ιδιότητα είναι αληθής, τότε τα δεδομένα στην ιδιότητα (\#getSecondaryCategories.getSecondaryCategories) χρησιμοποιούνται για τις δευτερεύουσες σειρές και τα δεδομένα στην ιδιότητα \#getCategories.getCategories χρησιμοποιούνται για τις κύριες σειρές.

**Επιστρέφει:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

Εάν είναι ψευδής, τότε η ιδιότητα \#getSecondaryCategories.getSecondaryCategories επιστρέφει null και τα δεδομένα στην ιδιότητα \#getCategories.getCategories χρησιμοποιούνται τόσο για τις κύριες όσο και για τις δευτερεύουσες σειρές. Εάν είναι αληθής, τότε τα δεδομένα στην ιδιότητα \#getSecondaryCategories.getSecondaryCategories χρησιμοποιούνται για τις δευτερεύουσες σειρές και τα δεδομένα στην ιδιότητα \#getCategories.getCategories χρησιμοποιούνται για τις κύριες σειρές. Ανάγνωση/εγγραφή boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // οι σχετικές κατηγορίες είναι series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // οι σχετικές κατηγορίες είναι series.getChart().getChartData().getCategories()
>  }
> ```

**Επιστρέφει:**
boolean
### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public final void setUseSecondaryCategories(boolean value)
```

Εάν είναι ψευδής, τότε η ιδιότητα \#getSecondaryCategories.getSecondaryCategories επιστρέφει null και τα δεδομένα στην ιδιότητα \#getCategories.getCategories χρησιμοποιούνται τόσο για τις κύριες όσο και για τις δευτερεύουσες σειρές. Εάν είναι αληθής, τότε τα δεδομένα στην ιδιότητα \#getSecondaryCategories.getSecondaryCategories χρησιμοποιούνται για τις δευτερεύουσες σειρές και τα δεδομένα στην ιδιότητα \#getCategories.getCategories χρησιμοποιούνται για τις κύριες σειρές. Ανάγνωση/εγγραφή boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // οι σχετικές κατηγορίες είναι series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // οι σχετικές κατηγορίες είναι series.getChart().getChartData().getCategories()
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public final IChartCategoryCollection getSecondaryCategories()
```

Λαμβάνει τις δευτερεύουσες κατηγορίες εάν η ιδιότητα \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) είναι αληθής. Μόνο για ανάγνωση [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // σχετικές κατηγορίες είναι series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // σχετικές κατηγορίες είναι series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

Εάν η ιδιότητα \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) είναι ψευδής, τότε αυτή η ιδιότητα (\#getSecondaryCategories.getSecondaryCategories) επιστρέφει null και τα δεδομένα στην ιδιότητα \#getCategories.getCategories χρησιμοποιούνται τόσο για τις κύριες όσο και για τις δευτερεύουσες σειρές. Εάν η ιδιότητα είναι αληθής, τότε τα δεδομένα σε αυτήν την ιδιότητα \#getSecondaryCategories.getSecondaryCategories χρησιμοποιούνται για τις δευτερεύουσες σειρές και τα δεδομένα στην ιδιότητα \#getCategories.getCategories χρησιμοποιούνται για τις κύριες σειρές.

**Επιστρέφει:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

Γράφει το εσωτερικά περιέμενο βιβλίο εργασίας Excel σε μια ροή μνήμης.

**Επιστρέφει:**
byte[] - Returns an instance of byte array containing a copy of the internally contained Excel workbook.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

Αρχικοποιεί το εσωτερικά περιέμενο βιβλίο εργασίας Excel με τιμή καθορισμένη από το χρήστη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ms | byte[] | The user-supplied stream containing the entire Excel workbook. |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

Αντιπροσωπεύει τη διαδρομή εξωτερικού βιβλίου εργασίας εάν η πηγή δεδομένων είναι εξωτερική, διαφορετικά null

**Επιστρέφει:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public final String getExternalWorkbookPath()
```

Αντιπροσωπεύει την πηγή δεδομένων του διαγράμματος

**Επιστρέφει:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```

Λαμβάνει τον τύπο του ενσωματωμένου βιβλίου εργασίας. Returns [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) if  DataSourceType (\#getDataSourceType.getDataSourceType) is [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Μόνο για ανάγνωση [WorkbookType](../../com.aspose.slides/workbooktype).

**Επιστρέφει:**
int
### getRange() {#getRange--}
```
public final String getRange()
```

Λαμβάνει την περιοχή δεδομένων του διαγράμματος.

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 0, 0, 100, 100);
>       String result = ((ChartData)chart.getChartData()).getRange();
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Επιστρέφει:**
java.lang.String - Cells data range formula. E.g: "Sheet1!$A$1:$C$4"
### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

Ορίζει την περιοχή δεδομένων του διαγράμματος. Οι σειρές και οι κατηγορίες θα ενημερωθούν βάσει της νέας περιοχής δεδομένων. Εάν ο αριθμός των σειρών στην περιοχή δεδομένων είναι μεγαλύτερος από τον αριθμό σειρών στο διάγραμμα, θα προστεθούν επιπλέον σειρές με τον ίδιο τύπο ως η τελευταία σειρά στην τρέχουσα συλλογή, στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| formula | java.lang.String | The cells data range formula. E.g: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
```

Ορίζει το εξωτερικό βιβλίο εργασίας ως πηγή δεδομένων για το διάγραμμα. Τα δεδομένα του διαγράμματος θα ενημερωθούν από το βιβλίο εργασίας προορισμού.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>     IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>     IChartData chartData = chart.getChartData();
>     ((ChartData)chartData).setExternalWorkbook("../../workbook.xlsx");
>  } finally {
>     if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| workbookPath | java.lang.String | Path to the target workbook |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public final void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

Ορίζει το εξωτερικό βιβλίο εργασίας ως πηγή δεδομένων για το διάγραμμα.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>      IChartData chartData = chart.getChartData();
>      ((ChartData).setExternalWorkbook("http://path/doesnt/exists", false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| workbookPath | java.lang.String | Path to the target workbook |
| updateChartData | boolean | If value is false only workbook path will be updated. Chart data won't be loaded and updated from the target workbook. Can be used when target workbook doesn't exist or it's not available. If value is true chart data will be updated from the target workbook. |

### switchRowColumn() {#switchRowColumn--}
```
public final void switchRowColumn()
```

Ανταλλάσσει τα δεδομένα κατά τον άξονα. Τα δεδομένα που απεικονίζονται στον άξονα X θα μετακινηθούν στον άξονα Y και αντίστροφα.