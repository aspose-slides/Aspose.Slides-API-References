---
title: ChartData
second_title: Aspose.Slides για την Αναφορά API Java
description: Αναπαριστά τα δεδομένα που χρησιμοποιούνται για τη δημιουργία γραφήματος.
type: docs
url: /el/com.aspose.slides/chartdata/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IChartData](../../com.aspose.slides/ichartdata)
```
public class ChartData extends DomObject<Chart> implements IChartData
```

Αναπαριστά δεδομένα που χρησιμοποιούνται για τη σχεδίαση ενός γραφήματος.
## Μέθοδοι

| Method | Description |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Αποκτά το εργοστάσιο κελιών για τη δημιουργία κελιών που χρησιμοποιούνται για σειρές ή κατηγορίες γραφήματος. |
| [getSeries()](#getSeries--) | Αποκτά τις σειρές. |
| [getSeriesGroups()](#getSeriesGroups--) | Αποκτά τις ομάδες σειρών. |
| [getCategories()](#getCategories--) | Αποκτά τις πρωτεύουσες κατηγορίες (ή και τις δύο, πρωτεύουσες και δευτερεύουσες, εάν η ιδιότητα \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) είναι ψευδής). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Εάν είναι ψευδές, τότε η ιδιότητα \#getSecondaryCategories.getSecondaryCategories επιστρέφει null και τα δεδομένα στην ιδιότητα \#getCategories.getCategories χρησιμοποιούνται και για τις πρωτεύουσες και για τις δευτερεύουσες σειρές. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Εάν είναι ψευδές, τότε η ιδιότητα \#getSecondaryCategories.getSecondaryCategories επιστρέφει null και τα δεδομένα στην ιδιότητα \#getCategories.getCategories χρησιμοποιούνται και για τις πρωτεύουσες και για τις δευτερεύουσες σειρές. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Αποκτά τις δευτερεύουσες κατηγορίες εάν η ιδιότητα \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) είναι αληθής. |
| [readWorkbookStream()](#readWorkbookStream--) | Γράφει το εσωτερικά περιέχομενο βιβλίο εργασίας Excel σε ροή μνήμης. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Αρχικοποιεί το εσωτερικά περιέχομενο βιβλίο εργασίας Excel με τιμή που καθορίζεται από τον χρήστη. |
| [getDataSourceType()](#getDataSourceType--) | Αναπαριστά τη διαδρομή εξωτερικού βιβλίου εργασίας εάν η πηγή δεδομένων είναι εξωτερική, διαφορετικά null |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Αναπαριστά την πηγή δεδομένων του γραφήματος |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Αποκτά τον τύπο του ενσωματωμένου βιβλίου εργασίας. |
| [getRange()](#getRange--) | Αποκτά το εύρος δεδομένων του γραφήματος. |
| [setRange(String formula)](#setRange-java.lang.String-) | Ορίζει το εύρος δεδομένων του γραφήματος. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Ορίζει εξωτερικό βιβλίο εργασίας ως πηγή δεδομένων για το γράφημα. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Ορίζει εξωτερικό βιβλίο εργασίας ως πηγή δεδομένων για το γράφημα. |
| [switchRowColumn()](#switchRowColumn--) | Αλλάζει την διάταξη των δεδομένων κατά τον άξονα. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

Αποκτά το εργοστάσιο κελιών για τη δημιουργία κελιών που χρησιμοποιούνται για σειρές ή κατηγορίες γραφήματος. Μόνο για ανάγνωση [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Επιστρέφει:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

Αποκτά τις σειρές. Μόνο για ανάγνωση [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Επιστρέφει:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

Αποκτά τις ομάδες σειρών. Μόνο για ανάγνωση [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Κάθε ομάδα σειρών περιέχει σειρές με συνδυάσιμους τύπους. Οι ομάδες συνδυάσιμων τύπων σειρών ορίζονται και περιγράφονται με την enum CombinableSeriesTypesGroup. Επίσης κάθε ομάδα σειρών περιέχει σειρές που σχεδιάζονται είτε στον πρωτεύοντα άξονα είτε στον δευτερεύοντα άξονα (όχι και στις δύο περιπτώσεις στην ίδια ομάδα). Έτσι, η αρχή ομαδοποίησης σειρών είναι μια ομαδοποίηση κατά τις παραπάνω ομάδες τύπων και κατά τον τύπο σχεδίασης πρωτεύοντος/δευτερεύοντος.

**Επιστρέφει:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

Αποκτά τις πρωτεύουσες κατηγορίες (ή και τις δύο, πρωτεύουσες και δευτερεύουσες, εάν η ιδιότητα \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) είναι ψευδής). Μόνο για ανάγνωση [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Αν η ιδιότητα \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) είναι ψευδής, τότε η ιδιότητα (\#getSecondaryCategories.getSecondaryCategories) επιστρέφει null και τα δεδομένα στην ιδιότητα \#getCategories.getCategories χρησιμοποιούνται και για τις πρωτεύουσες και για τις δευτερεύουσες σειρές. Αν η ιδιότητα είναι αληθής, τότε τα δεδομένα στην ιδιότητα (\#getSecondaryCategories.getSecondaryCategories) χρησιμοποιούνται για τις δευτερεύουσες σειρές και τα δεδομένα στην ιδιότητα \#getCategories.getCategories χρησιμοποιούνται για τις πρωτεύουσες σειρές.

**Επιστρέφει:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

Αν είναι ψευδής, τότε η ιδιότητα \#getSecondaryCategories.getSecondaryCategories επιστρέφει null και τα δεδομένα στην ιδιότητα \#getCategories.getCategories χρησιμοποιούνται και για τις πρωτεύουσες και για τις δευτερεύουσες σειρές. Αν είναι αληθής, τότε τα δεδομένα στην ιδιότητα \#getSecondaryCategories.getSecondaryCategories χρησιμοποιούνται για τις δευτερεύουσες σειρές και τα δεδομένα στην ιδιότητα \#getCategories.getCategories χρησιμοποιούνται για τις πρωτεύουσες σειρές. Αναγνώγηση/εγγραφή boolean.

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

**Επιστρέφει:**
boolean

### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public final void setUseSecondaryCategories(boolean value)
```

Αν είναι ψευδής, τότε η ιδιότητα \#getSecondaryCategories.getSecondaryCategories επιστρέφει null και τα δεδομένα στην ιδιότητα \#getCategories.getCategories χρησιμοποιούνται και για τις πρωτεύουσες και για τις δευτερεύουσες σειρές. Αν είναι αληθής, τότε τα δεδομένα στην ιδιότητα \#getSecondaryCategories.getSecondaryCategories χρησιμοποιούνται για τις δευτερεύουσες σειρές και τα δεδομένα στην ιδιότητα \#getCategories.getCategories χρησιμοποιούνται για τις πρωτεύουσες σειρές. Αναγνώγηση/εγγραφή boolean.

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

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public final IChartCategoryCollection getSecondaryCategories()
```

Αποκτά τις δευτερεύουσες κατηγορίες εάν η ιδιότητα \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) είναι αληθής. Μόνο για ανάγνωση [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Αν η ιδιότητα \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) είναι ψευδής, τότε αυτή η ιδιότητα (\#getSecondaryCategories.getSecondaryCategories) επιστρέφει null και τα δεδομένα στην ιδιότητα \#getCategories.getCategories χρησιμοποιούνται και για τις πρωτεύουσες και για τις δευτερεύουσες σειρές. Αν η ιδιότητα είναι αληθής, τότε τα δεδομένα στην ιδιότητα \#getSecondaryCategories.getSecondaryCategories χρησιμοποιούνται για τις δευτερεύουσες σειρές και τα δεδομένα στην ιδιότητα \#getCategories.getCategories χρησιμοποιούνται για τις πρωτεύουσες σειρές.

**Επιστρέφει:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

Γράφει το εσωτερικά περιέχομενο βιβλίο εργασίας Excel σε ροή μνήμης.

**Επιστρέφει:**
byte[] - Επιστρέφει ένα στιγμιότυπο πίνακα byte που περιέχει αντίγραφο του εσωτερικά περιεχόμενου βιβλίου εργασίας Excel.

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

Αρχικοποιεί το εσωτερικά περιέχομενο βιβλίο εργασίας Excel με τιμή που καθορίζεται από τον χρήστη.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| ms | byte[] | Η ροή που παρέχεται από το χρήστη και περιέχει ολόκληρο το βιβλίο εργασίας Excel. |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

Αναπαριστά τη διαδρομή εξωτερικού βιβλίου εργασίας εάν η πηγή δεδομένων είναι εξωτερική, διαφορετικά null

**Επιστρέφει:**
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public final String getExternalWorkbookPath()
```

Αναπαριστά την πηγή δεδομένων του γραφήματος

**Επιστρέφει:**
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```

Αποκτά τον τύπο του ενσωματωμένου βιβλίου εργασίας. Επιστρέφει [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) εάν DataSourceType (\#getDataSourceType.getDataSourceType) είναι [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Μόνο για ανάγνωση [WorkbookType](../../com.aspose.slides/workbooktype).

**Επιστρέφει:**
int

### getRange() {#getRange--}
```
public final String getRange()
```

Αποκτά το εύρος δεδομένων του γραφήματος.

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
java.lang.String - Τύπος φόρμουλας εύρους δεδομένων κελιών. Π.χ.: "Sheet1!$A$1:$C$4"

### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

Ορίζει το εύρος δεδομένων του γραφήματος. Οι σειρές και οι κατηγορίες θα ενημερωθούν βάσει του νέου εύρους δεδομένων. Εάν ο αριθμός των σειρών στο εύρος δεδομένων είναι μεγαλύτερος από τον αριθμό σειρών στο γράφημα, θα προστεθούν επιπλέον σειρές με τον ίδιο τύπο ως η τελευταία σειρά στην τρέχουσα συλλογή, στο τέλος της συλλογής.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| formula | java.lang.String | Η φόρμουλα εύρους δεδομένων κελιών. Π.χ.: "Sheet1!$A$1:$C$4", "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
```

Ορίζει εξωτερικό βιβλίο εργασίας ως πηγή δεδομένων για το γράφημα. Τα δεδομένα του γραφήματος θα ενημερωθούν από το επιλεγμένο βιβλίο εργασίας.

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
| Parameter | Type | Description |
| --- | --- | --- |
| workbookPath | java.lang.String | Διαδρομή προς το επιλεγμένο βιβλίο εργασίας |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public final void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

Ορίζει εξωτερικό βιβλίο εργασίας ως πηγή δεδομένων για το γράφημα.

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
| Parameter | Type | Description |
| --- | --- | --- |
| workbookPath | java.lang.String | Διαδρομή προς το επιλεγμένο βιβλίο εργασίας |
| updateChartData | boolean | Εάν η τιμή είναι ψευδής, θα ενημερωθεί μόνο η διαδρομή του βιβλίου εργασίας. Τα δεδομένα του γραφήματος δεν θα φορτωθούν και δεν θα ενημερωθούν από το επιλεγμένο βιβλίο εργασίας. Μπορεί να χρησιμοποιηθεί όταν το βιβλίο εργασίας δεν υπάρχει ή δεν είναι διαθέσιμο. Εάν η τιμή είναι αληθής, τα δεδομένα του γραφήματος θα ενημερωθούν από το επιλεγμένο βιβλίο εργασίας. |

### switchRowColumn() {#switchRowColumn--}
```
public final void switchRowColumn()
```

Αλλάζει την διάταξη των δεδομένων κατά τον άξονα. Τα δεδομένα που εμφανίζονται στον άξονα X θα μετακινηθούν στον άξονα Y και αντίστροφα.