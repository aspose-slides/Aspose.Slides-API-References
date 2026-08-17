---
title: ChartCategoryCollection
second_title: Αναφορά API Aspose.Slides για Java
description: Αναπαριστά τη συλλογή του
type: docs
url: /el/com.aspose.slides/chartcategorycollection/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
```
public class ChartCategoryCollection extends DomObject<ChartData> implements IChartCategoryCollection
```

Αναπαριστά τη συλλογή του [ChartCategory](../../com.aspose.slides/chartcategory)
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει το στοιχείο στον καθορισμένο δείκτη. |
| [getUseCells()](#getUseCells--) | Εάν είναι true, το φύλλο εργασίας χρησιμοποιείται για αποθήκευση κατηγοριών (αυτή η περίπτωση υποστηρίζει κατηγορίες πολλαπλών επιπέδων). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Εάν είναι true, το φύλλο εργασίας χρησιμοποιείται για αποθήκευση κατηγοριών (αυτή η περίπτωση υποστηρίζει κατηγορίες πολλαπλών επιπέδων). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Επιστρέφει τον αριθμό των επιπέδων ομαδοποίησης κατηγοριών που χρησιμοποιούνται. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Εάν η κατηγορία υπάρχει στη συλλογή, την επιστρέφει. |
| [add(Object value)](#add-java.lang.Object-) | Δημιουργεί νέο [ChartCategory](../../com.aspose.slides/chartcategory) από την τιμή και το προσθέτει στη συλλογή. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Αναζητεί το καθορισμένο [ChartCategory](../../com.aspose.slides/chartcategory) και επιστρέφει τον δείκτη μηδενικής βάσης της πρώτης εμφάνισης εντός ολόκληρης της Συλλογής. |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Αφαιρεί την καθορισμένη τιμή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το στοιχείο στον δοθέντα δείκτη. |
| [clear()](#clear--) | Αφαιρεί όλα τα στοιχεία από τη συλλογή. |
| [iterator()](#iterator--) | Επιστρέφει έναν απαριθμητή που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
| [size()](#size--) | Επιστρέφει έναν αριθμό στοιχείων στη συλλογή. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει όλα τα στοιχεία της συλλογής στον καθορισμένο πίνακα. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει μια τιμή που υποδεικνύει εάν η πρόσβαση στη List είναι συγχρονισμένη (thread safe). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει ένα αντικείμενο που μπορεί να χρησιμοποιηθεί για το συγχρονισμό της πρόσβασης στη συλλογή. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartCategory get_Item(int index)
```

Λαμβάνει το στοιχείο στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Το στοιχείο στον καθορισμένο δείκτη.

### getUseCells() {#getUseCells--}
```
public final boolean getUseCells()
```

Εάν είναι true, το φύλλο εργασίας χρησιμοποιείται για αποθήκευση κατηγοριών (αυτή η περίπτωση υποστηρίζει κατηγορίες πολλαπλών επιπέδων). Εάν είναι false, το φύλλο εργασίας ΔΕΝ χρησιμοποιείται για αποθήκευση τιμών (και αυτή η περίπτωση δεν υποστηρίζει κατηγορίες πολλαπλών επιπέδων). Boolean ανάγνωσης/εγγραφής.

**Επιστρέφει:**
boolean

### setUseCells(boolean value) {#setUseCells-boolean-}
```
public final void setUseCells(boolean value)
```

Εάν είναι true, το φύλλο εργασίας χρησιμοποιείται για αποθήκευση κατηγοριών (αυτή η περίπτωση υποστηρίζει κατηγορίες πολλαπλών επιπέδων). Εάν είναι false, το φύλλο εργασίας ΔΕΝ χρησιμοποιείται για αποθήκευση τιμών (και αυτή η περίπτωση δεν υποστηρίζει κατηγορίες πολλαπλών επιπέδων). Boolean ανάγνωσης/εγγραφής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public final int getGroupingLevelCount()
```

Επιστρέφει τον αριθμό των επιπέδων ομαδοποίησης κατηγοριών που χρησιμοποιούνται. Είναι περισσότερο του ενός για κατηγορίες πολλαπλών επιπέδων. int μόνο για ανάγνωση.

**Επιστρέφει:**
int

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public final IChartCategory add(IChartDataCell chartDataCell)
```

Εάν η κατηγορία υπάρχει στη συλλογή, την επιστρέφει. Διαφορετικά δημιουργεί νέα κατηγορία γραφήματος από [IChartDataCell](../../com.aspose.slides/ichartdatacell) και την προσθέτει στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Κελί που χρησιμοποιείται για τη δημιουργία κατηγορίας γραφήματος. |

**Επιστρέφει:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Προστέθηκε ή υπάρχουσα κατηγορία.

### add(Object value) {#add-java.lang.Object-}
```
public final IChartCategory add(Object value)
```

Δημιουργεί νέο [ChartCategory](../../com.aspose.slides/chartcategory) από την τιμή και το προσθέτει στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.Object | Η τιμή.

--------------------

Αυτή η μέθοδος προσθέτει φύλλο εργασίας με όνομα AUTO_DATA και προσθέτει όλες τις τιμές εκεί. Εάν χρησιμοποιείτε [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) για προσθήκη ή επεξεργασία τιμών κελιών, βεβαιωθείτε ότι δεν χρησιμοποιείτε αυτό το φύλλο εργασίας. Ο μέγιστος αριθμός τιμών που προστίθενται με αυτή τη μέθοδο δεν πρέπει να υπερβαίνει το 16711680 |

**Επιστρέφει:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Προστέθηκε [IChartCategory](../../com.aspose.slides/ichartcategory).

### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public final int indexOf(IChartCategory value)
```

Αναζητεί το καθορισμένο [ChartCategory](../../com.aspose.slides/chartcategory) και επιστρέφει τον δείκτη μηδενικής βάσης της πρώτης εμφάνισης εντός ολόκληρης της Συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Κατηγορία γραφήματος. |

**Επιστρέφει:**
int - Ο δείκτης μηδενικής βάσης της πρώτης εμφάνισης του value εντός ολόκληρης της CollectionBase, εάν βρεθεί· διαφορετικά, -1.

### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public final void remove(IChartCategory value)
```

Αφαιρεί την καθορισμένη τιμή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Η τιμή. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Αφαιρεί το στοιχείο στον δοθέντα δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης κατηγορίας προς αφαίρεση. |

### clear() {#clear--}
```
public final void clear()
```

Αφαιρεί όλα τα στοιχεία από τη συλλογή.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iterator()
```

Επιστρέφει έναν απαριθμητή που διατρέχει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για τη διαπέραση της συλλογής.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iteratorJava()
```

Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - Ένας java.util.Iterator για ολόκληρη τη συλλογή.

### size() {#size--}
```
public final int size()
```

Επιστρέφει έναν αριθμό στοιχείων στη συλλογή. int μόνο για ανάγνωση.

**Επιστρέφει:**
int

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Αντιγράφει όλα τα στοιχεία της συλλογής στον καθορισμένο πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Πίνακας-στόχος. |
| index | int | Αρχικός δείκτης στον πίνακα. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Επιστρέφει μια τιμή που υποδεικνύει εάν η πρόσβαση στη List είναι συγχρονισμένη (thread safe). Boolean μόνο για ανάγνωση.

**Επιστρέφει:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Επιστρέφει ένα αντικείμενο που μπορεί να χρησιμοποιηθεί για το συγχρονισμό της πρόσβασης στη συλλογή. Object μόνο για ανάγνωση.

Επιστρέφει μια ρίζα συγχρονισμού. Object μόνο για ανάγνωση.

**Επιστρέφει:**
java.lang.Object