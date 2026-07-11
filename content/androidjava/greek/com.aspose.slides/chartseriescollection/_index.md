---
title: ChartSeriesCollection
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αντιπροσωπεύει τη συλλογή των
type: docs
url: /el/com.aspose.slides/chartseriescollection/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
```
public class ChartSeriesCollection extends DomObject<ChartData> implements IChartSeriesCollection
```

Αντιπροσωπεύει τη συλλογή των [ChartSeries](../../com.aspose.slides/chartseries)

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Αποκτά το στοιχείο στον καθορισμένο δείκτη. |
| [size()](#size--) | Επιστρέφει τον αριθμό των αντικειμένων στη συλλογή. |
| [add(int type)](#add-int-) | Δημιουργεί νέα σειρά γραφήματος και την προσθέτει στη συλλογή. |
| [insert(int index, int type)](#insert-int-int-) | Δημιουργεί νέα σειρά γραφήματος και την εισάγει στη συλλογή. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | Δημιουργεί νέα σειρά γραφήματος από [ChartDataCell](../../com.aspose.slides/chartdatacell) και την προσθέτει στη συλλογή. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | Δημιουργεί νέα σειρά γραφήματος από [ChartCellCollection](../../com.aspose.slides/chartcellcollection) και την προσθέτει στη συλλογή. |
| [add(String name, int type)](#add-java.lang.String-int-) | Δημιουργεί νέα σειρά γραφήματος από την τιμή και την προσθέτει στη συλλογή. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | Αναζητά το καθορισμένο [ChartSeries](../../com.aspose.slides/chartseries) και επιστρέφει τον μηδενικό ευρετήριος της πρώτης εμφάνισης εντός ολόκληρης της Συλλογής. |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | Αφαιρεί την καθορισμένη τιμή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί ένα στοιχείο ελέγχου ActiveX αποθηκευμένο στη συγκεκριμένη θέση από τη συλλογή. |
| [clear()](#clear--) | Αφαιρεί όλα τα στοιχεία ελέγχου από τη συλλογή. |
| [iterator()](#iterator--) | Επιστρέφει έναν απαριθμητή που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για την ολόκληρη συλλογή. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει την ολόκληρη συλλογή στον καθορισμένο πίνακα. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει μια τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (ασφαλής-νήματα). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει τη ρίζα συγχρονισμού. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

Αποκτά το στοιχείο στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Το στοιχείο στον καθορισμένο δείκτη.

### size() {#size--}
```
public final int size()
```

Επιστρέφει τον αριθμό των αντικειμένων στη συλλογή. int μόνο για ανάγνωση.

**Επιστρέφει:**
int

### add(int type) {#add-int-}
```
public final IChartSeries add(int type)
```

Δημιουργεί νέα σειρά γραφήματος και την προσθέτει στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
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
| Παράμετρος | Τύπος | Περιγραφή |
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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Κυψέλη που περιέχει το όνομα σειράς. |
| type | int | Τύπος που θέτει τον τύπο της σειράς |

--------------------

Εάν η σειρά γραφήματος που δημιουργήθηκε από το ίδιο κελί υπάρχει ήδη στη συλλογή, η μέθοδος δεν προσθέτει τίποτα και επιστρέφει το ευρετήριό της. |

**Επιστρέφει:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Προστιθέμενη σειρά γραφήματος ή σειρά που ήδη υπάρχει στη συλλογή.

### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public final IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

Δημιουργεί νέα σειρά γραφήματος από [ChartCellCollection](../../com.aspose.slides/chartcellcollection) και την προσθέτει στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | Κυψέλες που περιέχουν το όνομα σειράς. |
| type | int | Τύπος που θέτει τον τύπο της σειράς |

--------------------

Εάν η σειρά γραφήματος που δημιουργήθηκε από το ίδιο κελί υπάρχει ήδη στη συλλογή, η μέθοδος δεν προσθέτει τίποτα και επιστρέφει το ευρετήριό της. |

**Επιστρέφει:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Προστιθέμενη σειρά γραφήματος ή σειρά που ήδη υπάρχει στη συλλογή.

### add(String name, int type) {#add-java.lang.String-int-}
```
public final IChartSeries add(String name, int type)
```

Δημιουργεί νέα σειρά γραφήματος από τιμή και την προσθέτει στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα σειράς. |
| type | int | Τύπος που θέτει τον τύπο της σειράς |

**Επιστρέφει:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Προστιθέμενη σειρά γραφήματος.

### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public final int indexOf(IChartSeries value)
```

Αναζητά το καθορισμένο [ChartSeries](../../com.aspose.slides/chartseries) και επιστρέφει τον μηδενικό ευρετήριος της πρώτης εμφάνισης εντός ολόκληρης της Συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Τιμή σειράς γραφήματος. |

**Επιστρέφει:**
int - Ο μηδενικός ευρετήριος της πρώτης εμφάνισης της τιμής εντός ολόκληρης της CollectionBase, εάν βρεθεί· διαφορετικά, -1.

### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public final void remove(IChartSeries value)
```

Αφαιρέι τη καθορισμένη τιμή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Η τιμή. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Αφαιρεί ένα στοιχείο ελέγχου ActiveX αποθηκευμένο στην καθορισμένη θέση από τη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ευρετήριο του ελέγχου που θα αφαιρεθεί. |

### clear() {#clear--}
```
public final void clear()
```

Αφαιρεί όλα τα στοιχεία ελέγχου από τη συλλογή.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iterator()
```

Επιστρέφει έναν απαριθμητή που διατρέχει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - Ένα IGenericEnumerator που μπορεί να χρησιμοποιηθεί για την επανάληψη στη συλλογή.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iteratorJava()
```

Επιστρέφει έναν java iterator για την ολόκληρη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - Ένα java.util.Iterator για την ολόκληρη συλλογή.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Αντιγράφει την ολόκληρη συλλογή στον καθορισμένο πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Πίνακας προορισμού |
| index | int | Ευρετήριο στον πίνακα προορισμού. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Επιστρέφει μια τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (ασφαλής-νήματα). boolean μόνο για ανάγνωση.

**Επιστρέφει:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Επιστρέφει τη ρίζα συγχρονισμού. Object μόνο για ανάγνωση.

**Επιστρέφει:**
java.lang.Object