---
title: ChartSeriesCollection
second_title: Aspose.Slides για την Αναφορά API της Java
description: Αναπαριστά συλλογή του
type: docs
url: /el/com.aspose.slides/chartseriescollection/
---
**Κληρονομία:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
```
public class ChartSeriesCollection extends DomObject<ChartData> implements IChartSeriesCollection
```

Αναπαριστά συλλογή του [ChartSeries](../../com.aspose.slides/chartseries)
## Μέθοδοι

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει το στοιχείο στο καθορισμένο δείκτη. |
| [size()](#size--) | Επιστρέφει αριθμό αντικειμένων στη συλλογή. |
| [add(int type)](#add-int-) | Δημιουργεί νέα σειρά γραφήματος και την προσθέτει στη συλλογή. |
| [insert(int index, int type)](#insert-int-int-) | Δημιουργεί νέα σειρά γραφήματος και την εισάγει στη συλλογή. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | Δημιουργεί νέα σειρά γραφήματος από [ChartDataCell](../../com.aspose.slides/chartdatacell) και την προσθέτει στη συλλογή. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | Δημιουργεί νέα σειρά γραφήματος από [ChartCellCollection](../../com.aspose.slides/chartcellcollection) και την προσθέτει στη συλλογή. |
| [add(String name, int type)](#add-java.lang.String-int-) | Δημιουργεί νέα σειρά γραφήματος από την τιμή και την προσθέτει στη συλλογή. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | Αναζητά το καθορισμένο [ChartSeries](../../com.aspose.slides/chartseries) και επιστρέφει τον μηδενικό δείκτη της πρώτης εμφάνισης σε ολόκληρη τη Συλλογή |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | Αφαιρεί την καθορισμένη τιμή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί έναν έλεγχο ActiveX αποθηκευμένο στη συγκεκριμένη θέση από τη συλλογή. |
| [clear()](#clear--) | Αφαιρεί όλους τους ελέγχους από τη συλλογή. |
| [iterator()](#iterator--) | Επιστρέφει έναν απαριθμητή που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει ολόκληρη τη συλλογή στον καθορισμένο πίνακα. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει μια τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει μια ρίζα συγχρονισμού. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

Λαμβάνει το στοιχείο στο καθορισμένο δείκτη.

**Παράμετροι:**
| Παραμετρος | Τυπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Το στοιχείο στο καθορισμένο δείκτη.
### size() {#size--}
```
public final int size()
```

Επιστρέφει αριθμό αντικειμένων στη συλλογή. int μόνο για ανάγνωση.

**Επιστρέφει:**
int
### add(int type) {#add-int-}
```
public final IChartSeries add(int type)
```

Δημιουργεί νέα σειρά γραφήματος και την προσθέτει στη συλλογή.

**Παράμετροι:**
| Παραμετρος | Τυπος | Περιγραφή |
| --- | --- | --- |
| type | int | Τύπος σειράς |

**Επιστρέφει:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Νέα σειρά γραφήματος.
### insert(int index, int type) {#insert-int-int-}
```
public final IChartSeries insert(int index, int type)
```

Δημιουργεί νέα σειρά γραφήματος και την εισάγει στη συλλογή.

**Παράμετροι:**
| Παραμετρος | Τυπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |
| type | int |  |

**Επιστρέφει:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public final IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

Δημιουργεί νέα σειρά γραφήματος από [ChartDataCell](../../com.aspose.slides/chartdatacell) και την προσθέτει στη συλλογή.

**Παράμετροι:**
| Παραμετρος | Τυπος | Περιγραφή |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Κελί που περιέχει το όνομα σειράς. |
| type | int | Τύπος που ορίζει τον τύπο της σειράς |

--------------------

Εάν η σειρά γραφήματος δημιουργηθεί από το ίδιο κελί που υπάρχει ήδη στη συλλογή, τότε η μέθοδος δεν προσθέτει τίποτα και επιστρέφει το δείκτη της. |

**Επιστρέφει:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Προστέθηκε σειρά γραφήματος ή σειρά που ήδη βρίσκεται στη συλλογή.
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public final IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

Δημιουργεί νέα σειρά γραφήματος από [ChartCellCollection](../../com.aspose.slides/chartcellcollection) και την προσθέτει στη συλλογή.

**Παράμετροι:**
| Παραμετρος | Τυπος | Περιγραφή |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | Κελιά που περιέχουν το όνομα σειράς. |
| type | int | Τύπος που ορίζει τον τύπο της σειράς |

--------------------

Εάν η σειρά γραφήματος δημιουργηθεί από το ίδιο κελί που υπάρχει ήδη στη συλλογή, τότε η μέθοδος δεν προσθέτει τίποτα και επιστρέφει το δείκτη της. |

**Επιστρέφει:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Προστέθηκε σειρά γραφήματος ή σειρά που ήδη βρίσκεται στη συλλογή.
### add(String name, int type) {#add-java.lang.String-int-}
```
public final IChartSeries add(String name, int type)
```

Δημιουργεί νέα σειρά γραφήματος από την τιμή και την προσθέτει στη συλλογή.

**Παράμετροι:**
| Παραμετρος | Τυπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα σειράς. |
| type | int | Τύπος που ορίζει τον τύπο της σειράς |

**Επιστρέφει:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Προστέθηκε σειρά γραφήματος.
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public final int indexOf(IChartSeries value)
```

Αναζητά το καθορισμένο [ChartSeries](../../com.aspose.slides/chartseries) και επιστρέφει τον μηδενικό δείκτη της πρώτης εμφάνισης σε ολόκληρη τη Συλλογή

**Παράμετροι:**
| Παραμετρος | Τυπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Τιμή σειράς γραφήματος. |

**Επιστρέφει:**
int - Ο μηδενικός δείκτης της πρώτης εμφάνισης της τιμής σε ολόκληρο το CollectionBase, αν βρεθεί· διαφορετικά, -1.
### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public final void remove(IChartSeries value)
```

Αφαιρεί την καθορισμένη τιμή.

**Παράμετροι:**
| Παραμετρος | Τυπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Η τιμή. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Αφαιρεί έναν έλεγχο ActiveX αποθηκευμένο στη συγκεκριμένη θέση από τη συλλογή.

**Παράμετροι:**
| Παραμετρος | Τυπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης ελέγχου προς αφαίρεση. |
### clear() {#clear--}
```
public final void clear()
```

Αφαιρεί όλους τους ελέγχους από τη συλλογή.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iterator()
```

Επιστρέφει έναν απαριθμητή που διατρέχει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για την επανάληψη στη συλλογή.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iteratorJava()
```

Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - Ένα java.util.Iterator για ολόκληρη τη συλλογή.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Αντιγράφει ολόκληρη τη συλλογή στον καθορισμένο πίνακα.

**Παράμετροι:**
| Παραμετρος | Τυπος | Περιγραφή |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Πίνακας προορισμού |
| index | int | Δείκτης στον πίνακα προορισμού. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Επιστρέφει μια τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Boolean μόνο για ανάγνωση.

**Επιστρέφει:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Επιστρέφει μια ρίζα συγχρονισμού. Αντικείμενο μόνο για ανάγνωση.

**Επιστρέφει:**
java.lang.Object