---
title: IChartData
second_title: Aspose.Slides for Android via Java API Reference
description: Αναπαριστά τα δεδομένα που χρησιμοποιούνται για τη σχεδίαση ενός διαγράμματος.
type: docs
url: /el/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

Αναπαριστά τα δεδομένα που χρησιμοποιούνται για τη σχεδίαση ενός διαγράμματος.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Λαμβάνει το εργοστάσιο κελιών για τη δημιουργία κελιών που χρησιμοποιούνται για σειρές ή κατηγορίες διαγράμματος. |
| [getSeries()](#getSeries--) | Λαμβάνει τις σειρές. |
| [getSeriesGroups()](#getSeriesGroups--) | Λαμβάνει τις ομάδες σειρών. |
| [getCategories()](#getCategories--) | Λαμβάνει τις κύριες κατηγορίες (ή και τις κύριες και δευτερεύουσες κατηγορίες εάν η ιδιότητα (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) είναι ψευδής). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Αν είναι ψευδής, τότε η ιδιότητα (\#getSecondaryCategories.getSecondaryCategories) επιστρέφει null και τα δεδομένα στην ιδιότητα (\#getCategories.getCategories) χρησιμοποιούνται τόσο για τις κύριες όσο και για τις δευτερεύουσες σειρές. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Αν είναι ψευδής, τότε η ιδιότητα (\#getSecondaryCategories.getSecondaryCategories) επιστρέφει null και τα δεδομένα στην ιδιότητα (\#getCategories.getCategories) χρησιμοποιούνται τόσο για τις κύριες όσο και για τις δευτερεύουσες σειρές. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Λαμβάνει τις δευτερεύουσες κατηγορίες εάν η ιδιότητα (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) είναι αληθής. |
| [readWorkbookStream()](#readWorkbookStream--) | Γράφει το εσωτερικά περιεχόμενο Excel workbook σε μια ροή μνήμης. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Αρχικοποιεί το εσωτερικά περιεχόμενο Excel workbook με τιμή που καθορίζεται από το χρήστη. |
| [setRange(String formula)](#setRange-java.lang.String-) | Ορίζει το εύρος δεδομένων διαγράμματος. |
| [getRange()](#getRange--) | Λαμβάνει το εύρος δεδομένων διαγράμματος. |
| [getDataSourceType()](#getDataSourceType--) | Αναπαριστά την πηγή δεδομένων του διαγράμματος |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Αναπαριστά τη διαδρομή εξωτερικού βιβλίου εργασίας εάν η πηγή δεδομένων είναι εξωτερική, διαφορετικά null |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Λαμβάνει τον τύπο του ενσωματωμένου βιβλίου εργασίας. |
| [switchRowColumn()](#switchRowColumn--) | Ανταλλάσσει τα δεδομένα κατά τον άξονα. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Ορίζει εξωτερικό βιβλίο εργασίας ως πηγή δεδομένων για το διάγραμμα. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Ορίζει εξωτερικό βιβλίο εργασίας ως πηγή δεδομένων για το διάγραμμα. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```

Λαμβάνει το εργοστάσιο κελιών για τη δημιουργία κελιών που χρησιμοποιούνται για σειρές ή κατηγορίες διαγράμματος. Μόνο-ανάγνωση [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Επιστρέφει:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```

Λαμβάνει τις σειρές. Μόνο-ανάγνωση [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Επιστρέφει:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```

Λαμβάνει τις ομάδες σειρών. Μόνο-ανάγνωση [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Κάθε ομάδα σειρών περιλαμβάνει σειρές με συνδυάσιμους τύπους. Οι ομάδες συνδυάσιμων τύπων σειρών ορίζονται και περιγράφονται με το enum CombinableSeriesTypesGroup. Επίσης, κάθε ομάδα σειρών περιλαμβάνει σειρές που σχεδιάζονται είτε στον κύριο άξονα είτε στον δευτερεύοντα άξονα (όχι και οι δύο περιπτώσεις στην ίδια ομάδα). Έτσι, η αρχή ομαδοποίησης σειρών είναι η ομαδοποίηση κατά τις παραπάνω ομάδες τύπων και κατά τον τύπο σχεδίασης κύριου/δευτερεύοντος άξονα. 2) Η ομάδα σειρών περιλαμβάνει κάποιες ιδιότητες σειρών που είναι κοινές για κάθε σειρά στην ομάδα («ιδιότητες ομάδας σειρών»). Οι «ιδιότητες ομάδας σειρών» στην κλάση ChartSeriesGroup είναι ανάγνωση/εγγραφή. Κάθε «ιδιότητα ομάδας σειρών» μπορεί να έχει μια προβολή μόνο-ανάγνωσης στην κλάση ChartSeries.

**Επιστρέφει:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```

Λαμβάνει τις κύριες κατηγορίες (ή και τις κύριες και δευτερεύουσες κατηγορίες εάν η ιδιότητα (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) είναι ψευδής). Μόνο-ανάγνωση [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Αν η ιδιότητα (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) είναι ψευδής, τότε η ιδιότητα (\#getSecondaryCategories.getSecondaryCategories) επιστρέφει null και τα δεδομένα σε αυτήν την ιδιότητα (\#getCategories.getCategories) χρησιμοποιούνται τόσο για τις κύριες όσο και για τις δευτερεύουσες σειρές. Αν η ιδιότητα (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) είναι αληθής, τότε τα δεδομένα στην ιδιότητα (\#getSecondaryCategories.getSecondaryCategories) χρησιμοποιούνται για τις δευτερεύουσες σειρές και τα δεδομένα στην ιδιότητα (\#getCategories.getCategories) χρησιμοποιούνται για τις κύριες σειρές.

**Επιστρέφει:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

Αν είναι ψευδής, η ιδιότητα (\#getSecondaryCategories.getSecondaryCategories) επιστρέφει null και τα δεδομένα στην ιδιότητα (\#getCategories.getCategories) χρησιμοποιούνται τόσο για τις κύριες όσο και για τις δευτερεύουσες σειρές. Αν είναι αληθής, τα δεδομένα στην ιδιότητα (\#getSecondaryCategories.getSecondaryCategories) χρησιμοποιούνται για τις δευτερεύουσες σειρές και τα δεδομένα στην ιδιότητα (\#getCategories.getCategories) χρησιμοποιούνται για τις κύριες σειρές. Ανάγνωση/εγγραφή boolean.

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

Αν είναι ψευδής, η ιδιότητα (\#getSecondaryCategories.getSecondaryCategories) επιστρέφει null και τα δεδομένα στην ιδιότητα (\#getCategories.getCategories) χρησιμοποιούνται τόσο για τις κύριες όσο και για τις δευτερεύουσες σειρές. Αν είναι αληθής, τα δεδομένα στην ιδιότητα (\#getSecondaryCategories.getSecondaryCategories) χρησιμοποιούνται για τις δευτερεύουσες σειρές και τα δεδομένα στην ιδιότητα (\#getCategories.getCategories) χρησιμοποιούνται για τις κύριες σειρές. Ανάγνωση/εγγραφή boolean.

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
| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public abstract IChartCategoryCollection getSecondaryCategories()
```

Λαμβάνει τις δευτερεύουσες κατηγορίες εάν η ιδιότητα (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) είναι αληθής. Μόνο-ανάγνωση [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Αν η ιδιότητα (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) είναι ψευδής, αυτή η ιδιότητα (\#getSecondaryCategories.getSecondaryCategories) επιστρέφει null και τα δεδομένα στην ιδιότητα (\#getCategories.getCategories) χρησιμοποιούνται τόσο για τις κύριες όσο και για τις δευτερεύουσες σειρές. Αν η ιδιότητα (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) είναι αληθής, τα δεδομένα σε αυτήν την ιδιότητα (\#getSecondaryCategories.getSecondaryCategories) χρησιμοποιούνται για τις δευτερεύουσες σειρές και τα δεδομένα στην ιδιότητα (\#getCategories.getCategories) χρησιμοποιούνται για τις κύριες σειρές.

**Επιστρέφει:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```

Γράφει το εσωτερικά περιεχόμενο Excel workbook σε μια ροή μνήμης.

**Επιστρέφει:**
byte[] - Επιστρέφει έναν πίνακα byte που περιέχει αντίγραφο του εσωτερικά περιεχομένου Excel workbook.

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```

Αρχικοποιεί το εσωτερικά περιεχόμενο Excel workbook με τιμή που καθορίζεται από το χρήστη.

**Παράμετροι:**
| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| ms | byte[] | Η ροή που παρέχεται από το χρήστη, περιέχοντας ολόκληρο το Excel workbook. |

### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

Ορίζει το εύρος δεδομένων του διαγράμματος. Οι σειρές και οι κατηγορίες θα ενημερωθούν βάσει του νέου εύρους δεδομένων. Εάν ο αριθμός των σειρών στο εύρος δεδομένων είναι μεγαλύτερος από τον αριθμό των σειρών στα δεδομένα του διαγράμματος, θα προστεθούν επιπλέον σειρές με τον ίδιο τύπο όπως η τελευταία σειρά της τρέχουσας συλλογής, στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| formula | java.lang.String | Ο τύπος του εύρους δεδομένων κελιών. Π.χ: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

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
java.lang.String - Ο τύπος του εύρους δεδομένων κελιών. Π.χ: "Sheet1!$A$1:$C$4"

### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

Αναπαριστά την πηγή δεδομένων του διαγράμματος

**Επιστρέφει:**
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```

Αναπαριστά τη διαδρομή εξωτερικού βιβλίου εργασίας εάν η πηγή δεδομένων είναι εξωτερική, διαφορετικά null

**Επιστρέφει:**
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```

Λαμβάνει τον τύπο του ενσωματωμένου βιβλίου εργασίας. Επιστρέφει [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) εάν ο DataSourceType (\#getDataSourceType.getDataSourceType) είναι [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Μόνο-ανάγνωση [WorkbookType](../../com.aspose.slides/workbooktype).

**Επιστρέφει:**
int

### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```

Ανταλλάσσει τα δεδομένα κατά το άξονα. Τα δεδομένα που εμφανίζονται στον άξονα X θα μετακινηθούν στον άξονα Y και αντίστροφα.

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```

Ορίζει το εξωτερικό βιβλίο εργασίας ως πηγή δεδομένων για το διάγραμμα. Τα δεδομένα του διαγράμματος θα ενημερωθούν από το στοχευόμενο βιβλίο εργασίας.

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
| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| workbookPath | java.lang.String | Διαδρομή προς το στοχευόμενο βιβλίο εργασίας |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

Ορίζει το εξωτερικό βιβλίο εργασίας ως πηγή δεδομένων για το διάγραμμα.

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
| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| workbookPath | java.lang.String | Διαδρομή προς το στοχευόμενο βιβλίο εργασίας |
| updateChartData | boolean | Αν η τιμή είναι ψευδής, μόνο η διαδρομή του βιβλίου εργασίας θα ενημερωθεί. Τα δεδομένα του διαγράμματος δεν θα φορτωθούν και δεν θα ενημερωθούν από το στοχευόμενο βιβλίο εργασίας. Μπορεί να χρησιμοποιηθεί όταν το στοχευόμενο βιβλίο εργασίας δεν υπάρχει ή δεν είναι διαθέσιμο. Αν η τιμή είναι αληθής, τα δεδομένα του διαγράμματος θα ενημερωθούν από το στοχευόμενο βιβλίο εργασίας. |