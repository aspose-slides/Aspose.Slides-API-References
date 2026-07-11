---
title: ChartCategoryCollection
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Αναπαριστά συλλογή του
type: docs
url: /el/com.aspose.slides/chartcategorycollection/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι Υλοποιημένες Διασυνδέσεις:**
[com.aspose.slides.IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
```
public class ChartCategoryCollection extends DomObject<ChartData> implements IChartCategoryCollection
```

Αναπαριστά συλλογή του [ChartCategory](../../com.aspose.slides/chartcategory)
## Μέθοδοι

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει το στοιχείο στη συγκεκριμένη θέση. |
| [getUseCells()](#getUseCells--) | Εάν είναι true, τότε το φύλλο εργασίας χρησιμοποιείται για αποθήκευση κατηγοριών (η περίπτωση αυτή υποστηρίζει κατηγορίες πολλαπλών επιπέδων). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Εάν είναι true, τότε το φύλλο εργασίας χρησιμοποιείται για αποθήκευση κατηγοριών (η περίπτωση αυτή υποστηρίζει κατηγορίες πολλαπλών επιπέδων). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Επιστρέφει τον αριθμό των επιπέδων ομαδοποίησης κατηγοριών που χρησιμοποιούνται. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Εάν η κατηγορία υπάρχει στη συλλογή, την επιστρέφει. |
| [add(Object value)](#add-java.lang.Object-) | Δημιουργεί νέο [ChartCategory](../../com.aspose.slides/chartcategory) από την τιμή και το προσθέτει στη συλλογή. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Αναζητά το καθορισμένο [ChartCategory](../../com.aspose.slides/chartcategory) και επιστρέφει το μηδενικό-βάση δείκτη της πρώτης εμφάνισης μέσα σε ολόκληρη τη Συλλογή. |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Αφαιρεί την καθορισμένη τιμή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το στοιχείο στη δεδομένη θέση. |
| [clear()](#clear--) | Αφαιρεί όλα τα στοιχεία από τη συλλογή. |
| [iterator()](#iterator--) | Επιστρέφει έναν enumerator που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
| [size()](#size--) | Επιστρέφει τον αριθμό των στοιχείων στη συλλογή. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει όλα τα στοιχεία της συλλογής στον καθορισμένο πίνακα. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει μια τιμή που υποδεικνύει αν η πρόσβαση στη List είναι συγχρονισμένη (thread safe). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει ένα αντικείμενο που μπορεί να χρησιμοποιηθεί για συγχρονισμό της πρόσβασης στη συλλογή. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartCategory get_Item(int index)
```

Λαμβάνει το στοιχείο στη συγκεκριμένη θέση.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Το στοιχείο στη συγκεκριμένη θέση.

### getUseCells() {#getUseCells--}
```
public final boolean getUseCells()
```

Εάν είναι true, τότε το φύλλο εργασίας χρησιμοποιείται για αποθήκευση κατηγοριών (η περίπτωση αυτή υποστηρίζει κατηγορίες πολλαπλών επιπέδων). Εάν είναι false, τότε το φύλλο εργασίας ΔΕΝ χρησιμοποιείται για αποθήκευση τιμών (και αυτή η περίπτωση δεν υποστηρίζει κατηγορίες πολλαπλών επιπέδων). Boolean ανάγνωση/εγγραφή.

**Επιστρέφει:**
boolean

### setUseCells(boolean value) {#setUseCells-boolean-}
```
public final void setUseCells(boolean value)
```

Εάν είναι true, τότε το φύλλο εργασίας χρησιμοποιείται για αποθήκευση κατηγοριών (η περίπτωση αυτή υποστηρίζει κατηγορίες πολλαπλών επιπέδων). Εάν είναι false, τότε το φύλλο εργασίας ΔΕΝ χρησιμοποιείται για αποθήκευση τιμών (και αυτή η περίπτωση δεν υποστηρίζει κατηγορίες πολλαπλών επιπέδων). Boolean ανάγνωση/εγγραφή.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public final int getGroupingLevelCount()
```

Επιστρέφει τον αριθμό των επιπέδων ομαδοποίησης κατηγοριών που χρησιμοποιούνται. Είναι μεγαλύτερο από ένα για κατηγορίες πολλαπλών επιπέδων. Ακέραιος μόνο για ανάγνωση.

**Επιστρέφει:**
int

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public final IChartCategory add(IChartDataCell chartDataCell)
```

Εάν η κατηγορία υπάρχει στη συλλογή, την επιστρέφει. Διαφορετικά δημιουργεί νέα κατηγορία γραφήματος από [IChartDataCell](../../com.aspose.slides/ichartdatacell) και την προσθέτει στη συλλογή.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Κύτταρο που χρησιμοποιείται για τη δημιουργία κατηγορίας γραφήματος. |

**Επιστρέφει:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Προστεθείσα ή υπάρχουσα κατηγορία.

### add(Object value) {#add-java.lang.Object-}
```
public final IChartCategory add(Object value)
```

Δημιουργεί νέο [ChartCategory](../../com.aspose.slides/chartcategory) από την τιμή και το προσθέτει στη συλλογή.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | Η τιμή. |

--------------------

Αυτή η μέθοδος προσθέτει φύλλο εργασίας με όνομα AUTO_DATA και προσθέτει όλες τις τιμές εκεί. Εάν χρησιμοποιήσετε [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) για να προσθέσετε ή να επεξεργαστείτε τιμές κελιών, βεβαιωθείτε ότι δεν χρησιμοποιείτε αυτό το φύλλο εργασίας. Ο μέγιστος αριθμός τιμών που προστίθενται με αυτή τη μέθοδο δεν πρέπει να υπερβαίνει το 16711680 |

**Επιστρέφει:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Προστέθηκαν [IChartCategory](../../com.aspose.slides/ichartcategory).

### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public final int indexOf(IChartCategory value)
```

Αναζητά το καθορισμένο [ChartCategory](../../com.aspose.slides/chartcategory) και επιστρέφει το μηδενικό-βάση δείκτη της πρώτης εμφάνισης μέσα σε ολόκληρη τη Συλλογή.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Κατηγορία διαγράμματος. |

**Επιστρέφει:**
int - Το μηδενικό-βάση δείκτη της πρώτης εμφάνισης της τιμής μέσα σε ολόκληρη τη CollectionBase, εάν βρεθεί· διαφορετικά, -1.

### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public final void remove(IChartCategory value)
```

Αφαιρεί την καθορισμένη τιμή.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Η τιμή. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Αφαιρεί το στοιχείο στη δεδομένη θέση.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Δείκτης της κατηγορίας προς αφαίρεση. |

### clear() {#clear--}
```
public final void clear()
```

Αφαιρεί όλα τα στοιχεία από τη συλλογή.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iterator()
```

Επιστρέφει έναν enumerator που διατρέχει τη συλλογή.

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

Επιστρέφει τον αριθμό των στοιχείων στη συλλογή. Ακέραιος μόνο για ανάγνωση.

**Επιστρέφει:**
int

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Αντιγράφει όλα τα στοιχεία της συλλογής στον καθορισμένο πίνακα.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Πίνακας προορισμού. |
| index | int | Αρχικός δείκτης στον πίνακα. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Επιστρέφει μια τιμή που υποδεικνύει αν η πρόσβαση στη List είναι συγχρονισμένη (thread safe). Boolean μόνο για ανάγνωση.

**Επιστρέφει:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Επιστρέφει ένα αντικείμενο που μπορεί να χρησιμοποιηθεί για συγχρονισμό της πρόσβασης στη συλλογή. Αντικείμενο μόνο για ανάγνωση.

Επιστρέφει μια ρίζα συγχρονισμού. Αντικείμενο μόνο για ανάγνωση.

**Επιστρέφει:**
java.lang.Object