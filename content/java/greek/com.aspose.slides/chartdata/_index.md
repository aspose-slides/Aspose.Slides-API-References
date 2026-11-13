---
title: ChartData
second_title: Αναφορά API του Aspose.Slides για Java
description: Αντιπροσωπεύει τα δεδομένα που χρησιμοποιούνται για τη σχεδίαση ενός διαγράμματος.
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

Αντιπροσωπεύει τα δεδομένα που χρησιμοποιούνται για τη σχεδίαση ενός διαγράμματος.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Λαμβάνει το εργοστάσιο κελιών για τη δημιουργία κελιών που χρησιμοποιούνται για σειρές ή κατηγορίες διαγράμματος. |
| [getSeries()](#getSeries--) | Λαμβάνει τις σειρές. |
| [getSeriesGroups()](#getSeriesGroups--) | Λαμβάνει τις ομάδες σειρών. |
| [getCategories()](#getCategories--) | Λαμβάνει τις κύριες κατηγορίες (ή τόσο τις κύριες όσο και τις δευτερεύουσες κατηγορίες εάν η ιδιότητα #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) είναι ψευδής). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Αν είναι ψευδής, τότε η ιδιότητα #getSecondaryCategories.getSecondaryCategories επιστρέφει null και τα δεδομένα στην ιδιότητα #getCategories.getCategories χρησιμοποιούνται τόσο για κύριες όσο και για δευτερεύουσες σειρές. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Αν είναι ψευδής, τότε η ιδιότητα #getSecondaryCategories.getSecondaryCategories επιστρέφει null και τα δεδομένα στην ιδιότητα #getCategories.getCategories χρησιμοποιούνται τόσο για κύριες όσο και για δευτερεύουσες σειρές. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Λαμβάνει τις δευτερεύουσες κατηγορίες εάν η ιδιότητα #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) είναι αληθής. |
| [readWorkbookStream()](#readWorkbookStream--) | Γράφει το εσωτερικά περιεχόμενο φύλλο εργασίας Excel σε μια ροή μνήμης. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Αρχικοποιεί το εσωτερικά περιεχόμενο φύλλο εργασίας Excel με τιμή που καθορίζεται από τον χρήστη. |
| [getDataSourceType()](#getDataSourceType--) | Αντιπροσωπεύει τη διαδρομή εξωτερικού βιβλίου εργασίας εάν η πηγή δεδομένων είναι εξωτερική, αλλιώς null. |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Αντιπροσωπεύει την πηγή δεδομένων του διαγράμματος. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Λαμβάνει τον τύπο του ενσωματωμένου βιβλίου εργασίας. |
| [getRange()](#getRange--) | Λαμβάνει την περιοχή δεδομένων του διαγράμματος. |
| [setRange(String formula)](#setRange-java.lang.String-) | Ορίζει την περιοχή δεδομένων του διαγράμματος. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Ορίζει το εξωτερικό βιβλίο εργασίας ως πηγή δεδομένων για το διάγραμμα. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Ορίζει το εξωτερικό βιβλίο εργασίας ως πηγή δεδομένων για το διάγραμμα. |
| [refreshData()](#refreshData--) | Ανανεώνει τα δεδομένα του διαγράμματος επαναφορτώνοντάς τα από το βιβλίο εργασίας προέλευσης. |
| [switchRowColumn()](#switchRowColumn--) | Ανταλλάσσει τα δεδομένα κατά τον άξονα. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

Λαμβάνει το εργοστάσιο κελιών για τη δημιουργία κελιών που χρησιμοποιούνται για σειρές ή κατηγορίες διαγράμματος. Μόνο-ανάγνωση [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Επιστρέφει:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

Λαμβάνει τις σειρές. Μόνο-ανάγνωση [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Επιστρέφει:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

Λαμβάνει τις ομάδες σειρών. Μόνο-ανάγνωση [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

Κάθε ομάδα σειρών περιέχει σειρές με συνδυάσιμους τύπους. Οι ομάδες συνδυάσιμων τύπων σειρών ορίζονται και περιγράφονται με το enum CombinableSeriesTypesGroup. Επίσης, κάθε ομάδα σειρών περιέχει σειρές που σχεδιάζονται είτε στον κύριο άξονα είτε στον δευτερεύοντα άξονα (όχι και στις δύο περιπτώσεις μέσα στην ίδια ομάδα). Έτσι, η αρχή ομαδοποίησης των σειρών είναι η ομαδοποίηση κατά τύπους ομάδων όπως αναφέρθηκαν παραπάνω και κατά τύπο σχεδίασης κύριος/δευτερεύων.

**Επιστρέφει:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

Λαμβάνει τις κύριες κατηγορίες (ή τόσο τις κύριες όσο και τις δευτερεύουσες κατηγορίες εάν η ιδιότητα #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) είναι ψευδής). Μόνο-ανάγνωση [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Αν η ιδιότητα #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) είναι ψευδής, τότε η ιδιότητα #getSecondaryCategories.getSecondaryCategories επιστρέφει null και τα δεδομένα στην ιδιότητα #getCategories.getCategories χρησιμοποιούνται τόσο για κύριες όσο και για δευτερεύουσες σειρές. Εάν η ιδιότητα είναι αληθής, τότε τα δεδομένα στην ιδιότητα #getSecondaryCategories.getSecondaryCategories χρησιμοποιούνται για δευτερεύουσες σειρές και τα δεδομένα στην ιδιότητα #getCategories.getCategories χρησιμοποιούνται για κύριες σειρές.

**Επιστρέφει:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

Αν είναι ψευδής, τότε η ιδιότητα #getSecondaryCategories.getSecondaryCategories επιστρέφει null και τα δεδομένα στην ιδιότητα #getCategories.getCategories χρησιμοποιούνται τόσο για κύριες όσο και για δευτερεύουσες σειρές. Αν είναι αληθής, τότε τα δεδομένα στην ιδιότητα #getSecondaryCategories.getSecondaryCategories χρησιμοποιούνται για δευτερεύουσες σειρές και τα δεδομένα στην ιδιότητα #getCategories.getCategories χρησιμοποιούνται για κύριες σειρές. Ανάγνωση/Εγγραφή boolean.

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

Αν είναι ψευδής, τότε η ιδιότητα #getSecondaryCategories.getSecondaryCategories επιστρέφει null και τα δεδομένα στην ιδιότητα #getCategories.getCategories χρησιμοποιούνται τόσο για κύριες όσο και για δευτερεύουσες σειρές. Αν είναι αληθής, τότε τα δεδομένα στην ιδιότητα #getSecondaryCategories.getSecondaryCategories χρησιμοποιούνται για δευτερεύουσες σειρές και τα δεδομένα στην ιδιότητα #getCategories.getCategories χρησιμοποιούνται για κύριες σειρές. Ανάγνωση/Εγγραφή boolean.

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
public final IChartCategoryCollection getSecondaryCategories()
```

Λαμβάνει τις δευτερεύουσες κατηγορίες εάν η ιδιότητα #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) είναι αληθής. Μόνο-ανάγνωση [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Αν η ιδιότητα #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) είναι ψευδής, τότε αυτή η ιδιότητα #getSecondaryCategories.getSecondaryCategories επιστρέφει null και τα δεδομένα στην ιδιότητα #getCategories.getCategories χρησιμοποιούνται τόσο για κύριες όσο και για δευτερεύουσες σειρές. Εάν η ιδιότητα είναι αληθής, τότε τα δεδομένα στην ιδιότητα #getSecondaryCategories.getSecondaryCategories χρησιμοποιούνται για δευτερεύουσες σειρές και τα δεδομένα στην ιδιότητα #getCategories.getCategories χρησιμοποιούνται για κύριες σειρές.

**Επιστρέφει:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

Γράφει το εσωτερικά περιεχόμενο φύλλο εργασίας Excel σε μια ροή μνήμης.

**Επιστρέφει:**
byte[] - Επιστρέφει ένα στιγμιότυπο πίνακα byte που περιέχει αντίγραφο του εσωτερικά περιεχομένου φύλλου εργασίας Excel.

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

Αρχικοποιεί το εσωτερικά περιεχόμενο φύλλο εργασίας Excel με τιμή που καθορίζεται από τον χρήστη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ms | byte[] | Η ροή που παρέχεται από τον χρήστη και περιλαμβάνει ολόκληρο το φύλλο εργασίας Excel. |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

Αντιπροσωπεύει τη διαδρομή εξωτερικού βιβλίου εργασίας εάν η πηγή δεδομένων είναι εξωτερική, αλλιώς null.

**Επιστρέφει:**
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public final String getExternalWorkbookPath()
```

Αντιπροσωπεύει την πηγή δεδομένων του διαγράμματος.

**Επιστρέφει:**
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```

Λαμβάνει τον τύπο του ενσωματωμένου βιβλίου εργασίας. Επιστρέφει [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) εάν το DataSourceType (#getDataSourceType.getDataSourceType) είναι [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Μόνο-ανάγνωση [WorkbookType](../../com.aspose.slides/workbooktype).

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
java.lang.String - Τύπος περιοχής δεδομένων κελιών. Π.χ: "Sheet1!$A$1:$C$4"

### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

Ορίζει την περιοχή δεδομένων του διαγράμματος. Οι σειρές και οι κατηγορίες θα ενημερωθούν βάσει της νέας περιοχής δεδομένων. Εάν ο αριθμός των σειρών στην περιοχή δεδομένων είναι μεγαλύτερος από τον αριθμό σειρών στα δεδομένα του διαγράμματος, τότε επιπλέον σειρές με τον ίδιο τύπο με την τελευταία σειρά στην τρέχουσα συλλογή θα προσαρτηθούν στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| formula | java.lang.String | Ο τύπος περιοχής δεδομένων κελιών. Π.χ: "Sheet1!$A$1:$C$4", "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
```

Ορίζει το εξωτερικό βιβλίο εργασίας ως πηγή δεδομένων για το διάγραμμα. Τα δεδομένα του διαγράμματος θα ενημερωθούν από το σχετικό βιβλίο εργασίας.

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
| workbookPath | java.lang.String | Διαδρομή προς το βιβλίο εργασίας προορισμού |

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
| workbookPath | java.lang.String | Διαδρομή προς το βιβλίο εργασίας προορισμού |
| updateChartData | boolean | Εάν η τιμή είναι ψευδής, θα ενημερωθεί μόνο η διαδρομή του βιβλίου εργασίας. Τα δεδομένα του διαγράμματος δεν θα φορτωθούν και δεν θα ενημερωθούν από το βιβλίο εργασίας προορισμού. Μπορεί να χρησιμοποιηθεί όταν το βιβλίο εργασίας προορισμού δεν υπάρχει ή δεν είναι διαθέσιμο. Εάν η τιμή είναι αληθής, τα δεδομένα του διαγράμματος θα ενημερωθούν από το βιβλίο εργασίας προορισμού. |

### refreshData() {#refreshData--}
```
public final void refreshData()
```

Ανανεώνει τα δεδομένα του διαγράμματος επαναφορτώνοντάς τα από το βιβλίο εργασίας προέλευσης.

--------------------

> ```
> Presentation presentation = new Presentation("presentationWithChart.pptx");
>  try {
>      IChart chart = (IChart)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      chart.getChartData().refreshData();
>  } finally {
>      presentation.dispose();
>  }
> ```

### switchRowColumn() {#switchRowColumn--}
```
public final void switchRowColumn()
```

Ανταλλάσσει τα δεδομένα κατά τον άξονα. Τα δεδομένα που απεικονίζονται στον άξονα X θα μετακινηθούν στον άξονα Y και αντίστροφα.