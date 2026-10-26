---
title: SpreadsheetOptions
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αντιπροσωπεύει επιλογές που μπορούν να χρησιμοποιηθούν για τον καθορισμό πρόσθετης συμπεριφοράς των υπολογιστικών φύλλων.
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

Αντιπροσωπεύει επιλογές που μπορούν να χρησιμοποιηθούν για τον καθορισμό πρόσθετης συμπεριφοράς των υπολογιστικών φύλλων.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [SpreadsheetOptions()](#SpreadsheetOptions--) | Δημιουργεί μια νέα παρουσία της κλάσης [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Λαμβάνει ή ορίζει τις προτιμώμενες πληροφορίες πολιτισμού για τον υπολογισμό ορισμένων συναρτήσεων που προορίζονται για χρήση με γλώσσες που χρησιμοποιούν το σύνολο χαρακτήρων διπλού byte (DBCS). |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Λαμβάνει ή ορίζει τις προτιμώμενες πληροφορίες πολιτισμού για τον υπολογισμό ορισμένων συναρτήσεων που προορίζονται για χρήση με γλώσσες που χρησιμοποιούν το σύνολο χαρακτήρων διπλού byte (DBCS). |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | Εάν η πηγή δεδομένων για το γράφημα είναι ένα εξωτερικό βιβλίο εργασίας και δεν είναι διαθέσιμο, θα ανακτηθεί από την κρυφή μνήμη του γραφήματος. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | Εάν η πηγή δεδομένων για το γράφημα είναι ένα εξωτερικό βιβλίο εργασίας και δεν είναι διαθέσιμο, θα ανακτηθεί από την κρυφή μνήμη του γραφήματος. |
### SpreadsheetOptions() {#SpreadsheetOptions--}
```
public SpreadsheetOptions()
```

Δημιουργεί μια νέα παρουσία της κλάσης [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions).

### getPreferredCulture() {#getPreferredCulture--}
```
public final Locale getPreferredCulture()
```

Λαμβάνει ή ορίζει τις προτιμώμενες πληροφορίες πολιτισμού για τον υπολογισμό ορισμένων συναρτήσεων που προορίζονται για χρήση με γλώσσες που χρησιμοποιούν το σύνολο χαρακτήρων διπλού byte (DBCS).

**Επιστρέφει:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public final void setPreferredCulture(Locale value)
```

Λαμβάνει ή ορίζει τις προτιμώμενες πληροφορίες πολιτισμού για τον υπολογισμό ορισμένων συναρτήσεων που προορίζονται για χρήση με γλώσσες που χρησιμοποιούν το σύνολο χαρακτήρων διπλού byte (DBCS).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public final boolean getRecoverWorkbookFromChartCache()
```

Εάν η πηγή δεδομένων για το γράφημα είναι ένα εξωτερικό βιβλίο εργασίας και δεν είναι διαθέσιμο, θα ανακτηθεί από την κρυφή μνήμη του γραφήματος.

**Επιστρέφει:**
boolean
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

Εάν η πηγή δεδομένων για το γράφημα είναι ένα εξωτερικό βιβλίο εργασίας και δεν είναι διαθέσιμο, θα ανακτηθεί από την κρυφή μνήμη του γραφήματος.

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