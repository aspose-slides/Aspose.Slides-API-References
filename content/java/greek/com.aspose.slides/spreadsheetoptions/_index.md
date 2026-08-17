---
title: SpreadsheetOptions
second_title: Αναφορά API του Aspose.Slides για Java
description: Αντιπροσωπεύει επιλογές που μπορούν να χρησιμοποιηθούν για να καθορίσουν πρόσθετη συμπεριφορά των λογιστικών φύλλων.
type: docs
url: /el/com.aspose.slides/spreadsheetoptions/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
```
public class SpreadsheetOptions implements ISpreadsheetOptions
```

Αντιπροσωπεύει επιλογές που μπορούν να χρησιμοποιηθούν για να καθορίσουν πρόσθετη συμπεριφορά των λογιστικών φύλλων.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [SpreadsheetOptions()](#SpreadsheetOptions--) | Δημιουργεί ένα νέο στιγμιότυπο της κλάσης [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Ανακτά ή ορίζει τις προτιμώμενες ρυθμίσεις πολιτισμού για τον υπολογισμό ορισμένων συναρτήσεων που προορίζονται για γλώσσες που χρησιμοποιούν σύνολο διπλού-byte χαρακτήρων (DBCS). |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Ανακτά ή ορίζει τις προτιμώμενες ρυθμίσεις πολιτισμού για τον υπολογισμό ορισμένων συναρτήσεων που προορίζονται για γλώσσες που χρησιμοποιούν σύνολο διπλού-byte χαρακτήρων (DBCS). |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | Εάν η πηγή δεδομένων για το διάγραμμα είναι εξωτερικό βιβλίο εργασίας και δεν είναι διαθέσιμη, θα ανακτηθεί από την κρυφή μνήμη του διαγράμματος. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | Εάν η πηγή δεδομένων για το διάγραμμα είναι εξωτερικό βιβλίο εργασίας και δεν είναι διαθέσιμη, θα ανακτηθεί από την κρυφή μνήμη του διαγράμματος. |
### SpreadsheetOptions() {#SpreadsheetOptions--}
```
public SpreadsheetOptions()
```

Δημιουργεί ένα νέο στιγμιότυπο της κλάσης [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions).

### getPreferredCulture() {#getPreferredCulture--}
```
public final Locale getPreferredCulture()
```

Ανακτά ή ορίζει τις προτιμώμενες ρυθμίσεις πολιτισμού για τον υπολογισμό ορισμένων συναρτήσεων που προορίζονται για γλώσσες που χρησιμοποιούν σύνολο διπλού-byte χαρακτήρων (DBCS).

**Επιστρέφει:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public final void setPreferredCulture(Locale value)
```

Ανακτά ή ορίζει τις προτιμώμενες ρυθμίσεις πολιτισμού για τον υπολογισμό ορισμένων συναρτήσεων που προορίζονται για γλώσσες που χρησιμοποιούν σύνολο διπλού-byte χαρακτήρων (DBCS).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public final boolean getRecoverWorkbookFromChartCache()
```

Εάν η πηγή δεδομένων για το διάγραμμα είναι εξωτερικό βιβλίο εργασίας και δεν είναι διαθέσιμη, θα ανακτηθεί από την κρυφή μνήμη του διαγράμματος.

--------------------

> ```
> Example:
>   
>   SpreadsheetOptions spreadOptions = new SpreadsheetOptions();
>   spreadOptions.setRecoverWorkbookFromChartCache(true);
> 
>   LoadOptions loadOptions = new LoadOptions();
>   loadOptions.setSpreadsheetOptions(spreadOptions);
> 
>   Presentation pres = new Presentation("Presentation.pptx", loadOptions);
>   try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartDataWorkbook recoveredWorkbook = chart.getChartData().getChartDataWorkbook();
>   } finally {
>      if (pres != null) pres.dispose();
>   }
> ```


**Επιστρέφει:**
boolean
### setRecoverWorkbookFromChartCache(boolean value) {#setRecoverWorkbookFromChartCache-boolean-}
```
public final void setRecoverWorkbookFromChartCache(boolean value)
```

Εάν η πηγή δεδομένων για το διάγραμμα είναι εξωτερικό βιβλίο εργασίας και δεν είναι διαθέσιμη, θα ανακτηθεί από την κρυφή μνήμη του διαγράμματος.

--------------------

> ```
> Example:
>   
>   SpreadsheetOptions spreadOptions = new SpreadsheetOptions();
>   spreadOptions.setRecoverWorkbookFromChartCache(true);
> 
>   LoadOptions loadOptions = new LoadOptions();
>   loadOptions.setSpreadsheetOptions(spreadOptions);
> 
>   Presentation pres = new Presentation("Presentation.pptx", loadOptions);
>   try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartDataWorkbook recoveredWorkbook = chart.getChartData().getChartDataWorkbook();
>   } finally {
>      if (pres != null) pres.dispose();
>   }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |