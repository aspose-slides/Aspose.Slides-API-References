---
title: ISpreadsheetOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Represents options which can be used to specify additional spreadsheets behavior.
type: docs
url: /el/com.aspose.slides/ispreadsheetoptions/
---```
public interface ISpreadsheetOptions
```

Αντιπροσωπεύει επιλογές που μπορούν να χρησιμοποιηθούν για να καθορίσουν πρόσθετη συμπεριφορά των λογιστικών φύλλων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Λαμβάνει ή ορίζει τις προτιμώμενες πληροφορίες πολιτισμού για τον υπολογισμό ορισμένων συναρτήσεων που προορίζονται για χρήση με γλώσσες που χρησιμοποιούν σύνολο διπλών byte (DBCS). |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Λαμβάνει ή ορίζει τις προτιμώμενες πληροφορίες πολιτισμού για τον υπολογισμό ορισμένων συναρτήσεων που προορίζονται για χρήση με γλώσσες που χρησιμοποιούν σύνολο διπλών byte (DBCS). |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | Εάν η πηγή δεδομένων για το γράφημα είναι ένα εξωτερικό βιβλίο εργασίας και δεν είναι διαθέσιμη, θα ανακτηθεί από την κρυφή μνήμη του γραφήματος. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | Εάν η πηγή δεδομένων για το γράφημα είναι ένα εξωτερικό βιβλίο εργασίας και δεν είναι διαθέσιμη, θα ανακτηθεί από την κρυφή μνήμη του γραφήματος. |
### getPreferredCulture() {#getPreferredCulture--}
```
public abstract Locale getPreferredCulture()
```


Λαμβάνει ή ορίζει τις προτιμώμενες πληροφορίες πολιτισμού για τον υπολογισμό ορισμένων συναρτήσεων που προορίζονται για χρήση με γλώσσες που χρησιμοποιούν σύνολο διπλών byte (DBCS).

**Επιστρέφει:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public abstract void setPreferredCulture(Locale value)
```


Λαμβάνει ή ορίζει τις προτιμώμενες πληροφορίες πολιτισμού για τον υπολογισμό ορισμένων συναρτήσεων που προορίζονται για χρήση με γλώσσες που χρησιμοποιούν σύνολο διπλών byte (DBCS).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public abstract boolean getRecoverWorkbookFromChartCache()
```


Εάν η πηγή δεδομένων για το γράφημα είναι ένα εξωτερικό βιβλίο εργασίας και δεν είναι διαθέσιμη, θα ανακτηθεί από την κρυφή μνήμη του γραφήματος.

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
public abstract void setRecoverWorkbookFromChartCache(boolean value)
```


Εάν η πηγή δεδομένων για το γράφημα είναι ένα εξωτερικό βιβλίο εργασίας και δεν είναι διαθέσιμη, θα ανακτηθεί από την κρυφή μνήμη του γραφήματος.

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