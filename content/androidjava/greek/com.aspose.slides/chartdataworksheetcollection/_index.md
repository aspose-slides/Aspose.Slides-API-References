---
title: ChartDataWorksheetCollection
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αναπαριστά τη συλλογή των φύλλων εργασίας του βιβλίου δεδομένων διαγράμματος.
type: docs
url: /el/com.aspose.slides/chartdataworksheetcollection/
---
**Κληρονομικότητα:**  
java.lang.Object

**Όλες οι Υλοποιημένες Διασυνδέσεις:**  
[com.aspose.slides.IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection), com.aspose.slides.IDOMObject  
```
public final class ChartDataWorksheetCollection implements IChartDataWorksheetCollection, IDOMObject
```

Αναπαριστά τη συλλογή των φύλλων εργασίας του βιβλίου δεδομένων διαγράμματος.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 500);
>      IChartDataWorkbook workbook =  chart.getChartData().getChartDataWorkbook();
>      for (IChartDataWorksheet worksheet : workbook.getWorksheets())
>      {
>          String worksheetName = worksheet.getName();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει το φύλλο εργασίας κατά δείκτη. |
| [size()](#size--) | Επιστρέφει τον αριθμό. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
| [iterator()](#iterator--) | Επιστρέφει έναν enumerator που διατρέχει τη συλλογή. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει στο καθορισμένο πίνακα. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει τη ρίζα συγχρονισμού. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataWorksheet get_Item(int index)
```

Επιστρέφει το φύλλο εργασίας κατά δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης του φύλλου εργασίας στη συλλογή. |

**Τιμή επιστροφής:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - Παράδειγμα του IChartDataWorksheet.
### size() {#size--}
```
public final int size()
```

Επιστρέφει τον αριθμό. Μόνο για ανάγνωση int.

**Τιμή επιστροφής:**
int
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο για ανάγνωση IDOMObject.

**Τιμή επιστροφής:**
com.aspose.slides.IDOMObject
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataWorksheet> iteratorJava()
```

Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Τιμή επιστροφής:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataWorksheet> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για τη διαδρομή στη συλλογή.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataWorksheet> iterator()
```

Επιστρέφει έναν enumerator που διατρέχει τη συλλογή.

**Τιμή επιστροφής:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataWorksheet> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για τη διαδρομή στη συλλογή.
### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```

Αντιγράφει στο καθορισμένο πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Πίνακας στον οποίο θα γίνει η αντιγραφή. |
| arrayIndex | int | Δείκτης από τον οποίο αρχίζει η αντιγραφή. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Επιστρέφει τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Μόνο για ανάγνωση boolean.

**Τιμή επιστροφής:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Επιστρέφει τη ρίζα συγχρονισμού. Μόνο για ανάγνωση Object.

**Τιμή επιστροφής:**
java.lang.Object