---
title: IChartData
second_title: Aspose.Slides for Java API Reference
description: Αναπαριστά δεδομένα που χρησιμοποιούνται για την απεικόνιση ενός διαγράμματος.
type: docs
url: /el/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

Αναπαριστά δεδομένα που χρησιμοποιούνται για την απεικόνιση ενός διαγράμματος.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Λαμβάνει το εργοστάσιο κελιών για τη δημιουργία κελιών που χρησιμοποιούνται για σειρές ή κατηγορίες διαγράμματος. |
| [getSeries()](#getSeries--) | Λαμβάνει τις σειρές. |
| [getSeriesGroups()](#getSeriesGroups--) | Λαμβάνει τις ομάδες σειρών. |
| [getCategories()](#getCategories--) | Λαμβάνει τις κύριες κατηγορίες (ή και τις κύριες και δευτερεύουσες κατηγορίες εάν η ιδιότητα (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) είναι ψευδής). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Εάν είναι ψευδής, τότε η ιδιότητα (\#getSecondaryCategories.getSecondaryCategories) επιστρέφει null και τα δεδομένα στην ιδιότητα (\#getCategories.getCategories) χρησιμοποιούνται τόσο για κύριες όσο και για δευτερεύουσες σειρές. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Εάν είναι ψευδής, τότε η ιδιότητα (\#getSecondaryCategories.getSecondaryCategories) επιστρέφει null και τα δεδομένα στην ιδιότητα (\#getCategories.getCategories) χρησιμοποιούνται τόσο για κύριες όσο και για δευτερεύουσες σειρές. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Λαμβάνει τις δευτερεύουσες κατηγορίες εάν η ιδιότητα (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) είναι αληθής. |
| [readWorkbookStream()](#readWorkbookStream--) | Γράφει το εσωτερικά περιεχόμενο βιβλίο εργασίας Excel σε μια ροή μνήμης. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Αρχικοποιεί το εσωτερικά περιεχόμενο βιβλίο εργασίας Excel με την τιμή που καθορίζεται από τον χρήστη. |
| [setRange(String formula)](#setRange-java.lang.String-) | Ορίζει το εύρος δεδομένων διαγράμματος. |
| [getRange()](#getRange--) | Λαμβάνει το εύρος δεδομένων διαγράμματος. |
| [getDataSourceType()](#getDataSourceType--) | Αντιπροσωπεύει την πηγή δεδομένων του διαγράμματος |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Αντιπροσωπεύει τη διαδρομή εξωτερικού βιβλίου εργασίας εάν η πηγή δεδομένων είναι εξωτερική, διαφορετικά null |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Λαμβάνει τον τύπο του ενσωματωμένου βιβλίου εργασίας. |
| [switchRowColumn()](#switchRowColumn--) | Ανταλλάσσει τα δεδομένα πάνω από τον άξονα. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Ορίζει εξωτερικό βιβλίο εργασίας ως πηγή δεδομένων για το διάγραμμα. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Ορίζει εξωτερικό βιβλίο εργασίας ως πηγή δεδομένων για το διάγραμμα. |
| [refreshData()](#refreshData--) | Ανανεώνει τα δεδομένα του διαγράμματος επαναφορτώνοντάς τα από το βιβλίο εργασίας προέλευσης. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```

Λαμβάνει το εργοστάσιο κελιών για τη δημιουργία κελιών που χρησιμοποιούνται για σειρές ή κατηγορίες διαγράμματος. Μόνο για ανάγνωση [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Επιστρέφει:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```

Λαμβάνει τις σειρές. Μόνο για ανάγνωση [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Επιστρέφει:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```

Λαμβάνει τις ομάδες σειρών. Μόνο για ανάγνωση [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Κάθε ομάδα σειρών περιέχει σειρές με συνδυάσιμους τύπους. Οι ομάδες των συνδυάσιμων τύπων σειρών ορίζονται και περιγράφονται με το enum CombinableSeriesTypesGroup. Επίσης, κάθε ομάδα σειρών περιέχει σειρές που σχεδιάζονται είτε σε πρώτους άξονες είτε σε δευτερεύοντες άξονες (όχι και στις δύο περιπτώσεις στην ίδια ομάδα). Έτσι, η αρχή ομαδοποίησης σειρών είναι η ομαδοποίηση κατά τις παραπάνω ομάδες τύπων και κατά τύπο σχεδίασης κύριου/δευτερεύοντος άξονα. 2) Η ομάδα σειρών περιέχει κάποιες ιδιότητες σειρών που είναι κοινές για κάθε σειρά στην ομάδα («ιδιότητες ομάδας σειρών»). Οι «ιδιότητες ομάδας σειρών» στην κλάση ChartSeriesGroup είναι αναγνώσιμες/εγγράψιμες. Κάθε μία από τις «ιδιότητες ομάδας σειρών» μπορεί να έχει μια προβολή μόνο για ανάγνωση στην κλάση ChartSeries.

**Επιστρέφει:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```

Λαμβάνει τις κύριες κατηγορίες (ή και τις κύριες και δευτερεύουσες κατηγορίες εάν η ιδιότητα (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) είναι ψευδής). Μόνο για ανάγνωση [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Εάν η ιδιότητα (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) είναι ψευδής, τότε η ιδιότητα (\#getSecondaryCategories.getSecondaryCategories) επιστρέφει null και τα δεδομένα σε αυτήν την ιδιότητα (\#getCategories.getCategories) χρησιμοποιούνται τόσο για κύριες όσο και για δευτερεύουσες σειρές. Εάν η ιδιότητα (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) είναι αληθής, τότε τα δεδομένα στην ιδιότητα (\#getSecondaryCategories.getSecondaryCategories) χρησιμοποιούνται για δευτερεύουσες σειρές και τα δεδομένα σε αυτήν την ιδιότητα (\#getCategories.getCategories) χρησιμοποιούνται για κύριες σειρές.

**Επιστρέφει:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

Εάν είναι ψευδής, τότε η ιδιότητα (\#getSecondaryCategories.getSecondaryCategories) επιστρέφει null και τα δεδομένα στην ιδιότητα (\#getCategories.getCategories) χρησιμοποιούνται τόσο για κύριες όσο και για δευτερεύουσες σειρές. Εάν είναι αληθής, τότε τα δεδομένα στην ιδιότητα (\#getSecondaryCategories.getSecondaryCategories) χρησιμοποιούνται για δευτερεύουσες σειρές και τα δεδομένα στην ιδιότητα (\#getCategories.getCategories) χρησιμοποιούνται για κύριες σειρές. Αναγνώσιμη/εγγράψιμη boolean.

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
public abstract void setUseSecondaryCategories(boolean value)
```

Εάν είναι ψευδής, τότε η ιδιότητα (\#getSecondaryCategories.getSecondaryCategories) επιστρέφει null και τα δεδομένα στην ιδιότητα (\#getCategories.getCategories) χρησιμοποιούνται τόσο για κύριες όσο και για δευτερεύουσες σειρές. Εάν είναι αληθής, τότε τα δεδομένα στην ιδιότητα (\#getSecondaryCategories.getSecondaryCategories) χρησιμοποιούνται για δευτερεύουσες σειρές και τα δεδομένα στην ιδιότητα (\#getCategories.getCategories) χρησιμοποιούνται για κύριες σειρές. Αναγνώσιμη/εγγράψιμη boolean.

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public abstract IChartCategoryCollection getSecondaryCategories()
```

Λαμβάνει τις δευτερεύουσες κατηγορίες εάν η ιδιότητα (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) είναι αληθής. Μόνο για ανάγνωση [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Εάν η ιδιότητα (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) είναι ψευδής, τότε αυτή η ιδιότητα (\#getSecondaryCategories.getSecondaryCategories) επιστρέφει null και τα δεδομένα στην ιδιότητα (\#getCategories.getCategories) χρησιμοποιούνται τόσο για κύριες όσο και για δευτερεύουσες σειρές. Εάν η ιδιότητα (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) είναι αληθής, τότε τα δεδομένα σε αυτήν την ιδιότητα (\#getSecondaryCategories.getSecondaryCategories) χρησιμοποιούνται για δευτερεύουσες σειρές και τα δεδομένα στην ιδιότητα (\#getCategories.getCategories) χρησιμοποιούνται για κύριες σειρές.

**Επιστρέφει:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```

Γράφει το εσωτερικά περιεχόμενο βιβλίο εργασίας Excel σε μια ροή μνήμης.

**Επιστρέφει:**
byte[] - Επιστρέφει έναν πίνακα byte που περιέχει ένα αντίγραφο του εσωτερικά περιεχομένου βιβλίου εργασίας Excel.

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```

Αρχικοποιεί το εσωτερικά περιεχόμενο βιβλίο εργασίας Excel με την τιμή που καθορίζεται από τον χρήστη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ms | byte[] | Η ροή που παρέχει ο χρήστης, η οποία περιέχει ολόκληρο το βιβλίο εργασίας Excel. |

### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

Ορίζει το εύρος δεδομένων του διαγράμματος. Οι σειρές και οι κατηγορίες θα ενημερωθούν βάσει του νέου εύρους δεδομένων. Εάν ο αριθμός των σειρών στο εύρος δεδομένων είναι μεγαλύτερος από τον αριθμό των σειρών στα δεδομένα του διαγράμματος, τότε επιπλέον σειρές με τον ίδιο τύπο όπως η τελευταία σειρά στην τρέχουσα συλλογή θα προστεθούν στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| formula | java.lang.String | Ο τύπος εύρους δεδομένων κελιών. Π.χ.: "Sheet1!$A$1:$C$4", "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### getRange() {#getRange--}
```
public abstract String getRange()
```

Λαμβάνει το εύρος δεδομένων του διαγράμματος.

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```

**Επιστρέφει:**
java.lang.String - Τύπος εύρους δεδομένων κελιών. Π.χ.: "Sheet1!$A$1:$C$4"

### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

Αντιπροσωπεύει την πηγή δεδομένων του διαγράμματος

**Επιστρέφει:**
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```

Αντιπροσωπεύει τη διαδρομή εξωτερικού βιβλίου εργασίας εάν η πηγή δεδομένων είναι εξωτερική, διαφορετικά null

**Επιστρέφει:**
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```

Λαμβάνει τον τύπο του ενσωματωμένου βιβλίου εργασίας. Επιστρέφει [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) εάν η DataSourceType (\#getDataSourceType.getDataSourceType) είναι [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Μόνο για ανάγνωση [WorkbookType](../../com.aspose.slides/workbooktype).

**Επιστρέφει:**
int

### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```

Ανταλλάσσει τα δεδομένα πάνω από τον άξονα. Τα δεδομένα που απεικονίζονται στον άξονα X θα μεταφερθούν στον άξονα Y και αντίστροφα.

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```

Ορίζει εξωτερικό βιβλίο εργασίας ως πηγή δεδομένων για το διάγραμμα. Τα δεδομένα του διαγράμματος θα ενημερωθούν από το βιβλίο εργασίας προορισμού.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>     IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>     IChartData chartData = chart.getChartData();
>     ((ChartData)chartData).setExternalWorkbook("../../workbook.xlsx");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| workbookPath | java.lang.String | Διαδρομή προς το βιβλίο εργασίας προορισμού |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

Ορίζει εξωτερικό βιβλίο εργασίας ως πηγή δεδομένων για το διάγραμμα.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>     IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>     IChartData chartData = chart.getChartData();
>     ((ChartData)chartData).setExternalWorkbook("http://path/doesnt/exists", false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| workbookPath | java.lang.String | Διαδρομή προς το βιβλίο εργασίας προορισμού |
| updateChartData | boolean | Εάν η τιμή είναι ψευδής, μόνο η διαδρομή του βιβλίου εργασίας θα ενημερωθεί. Τα δεδομένα του διαγράμματος δεν θα φορτωθούν και δεν θα ενημερωθούν από το βιβλίο εργασίας προορισμού. Μπορεί να χρησιμοποιηθεί όταν το βιβλίο εργασίας προορισμού δεν υπάρχει ή δεν είναι διαθέσιμο. Εάν η τιμή είναι αληθής, τα δεδομένα του διαγράμματος θα ενημερωθούν από το βιβλίο εργασίας προορισμού. |

### refreshData() {#refreshData--}
```
public abstract void refreshData()
```

Ανανεώνει τα δεδομένα του διαγράμματος επαναφορτώνοντάς τα από το βιβλίο εργασίας προέλευσης.

--------------------

> ```
> Presentation presentation = new Presentation("presentationWithChart.pptx");
>  try {
>      IChart chart = (IChart)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      chart.getChartData().refreshData();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```