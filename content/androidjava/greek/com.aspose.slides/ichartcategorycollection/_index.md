---
title: IChartCategoryCollection
second_title: Aspose.Slides για Android μέσω Αναφοράς API Java
description: Αντιπροσωπεύει τη συλλογή των
type: docs
url: /el/com.aspose.slides/ichartcategorycollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.slides.IGenericCollection
```
public interface IChartCategoryCollection extends IGenericCollection<IChartCategory>
```

Αντιπροσωπεύει τη συλλογή των [IChartCategory](../../com.aspose.slides/ichartcategory)
## Μέθοδοι

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει το στοιχείο στον καθορισμένο δείκτη. |
| [getUseCells()](#getUseCells--) | Εάν είναι true, τότε το φύλλο εργασίας χρησιμοποιείται για αποθήκευση κατηγοριών (αυτή η περίπτωση υποστηρίζει πολυεπίπεδες κατηγορίες). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Εάν είναι true, τότε το φύλλο εργασίας χρησιμοποιείται για αποθήκευση κατηγοριών (αυτή η περίπτωση υποστηρίζει πολυεπίπεδες κατηγορίες). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Επιστρέφει τον αριθμό των επιπέδων ομαδοποίησης κατηγοριών που χρησιμοποιούνται. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Εάν η κατηγορία υπάρχει στη συλλογή, την επιστρέφει. |
| [add(Object value)](#add-java.lang.Object-) | Δημιουργεί νέο [IChartCategory](../../com.aspose.slides/ichartcategory) από την τιμή και το προσθέτει στη συλλογή. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Αναζητά το καθορισμένο [IChartCategory](../../com.aspose.slides/ichartcategory) και επιστρέφει το μηδενικό-βασισμένο ευρετήριο της πρώτης εμφάνισης εντός της πλήρους Συλλογής |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Αφαιρεί την καθορισμένη τιμή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το στοιχείο στον δεδομένο δείκτη. |
| [clear()](#clear--) | Αφαιρεί όλα τα στοιχεία από τη συλλογή. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartCategory get_Item(int index)
```

Λαμβάνει το στοιχείο στον καθορισμένο δείκτη.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Το στοιχείο στον καθορισμένο δείκτη.
### getUseCells() {#getUseCells--}
```
public abstract boolean getUseCells()
```

Εάν είναι true, τότε το φύλλο εργασίας χρησιμοποιείται για αποθήκευση κατηγοριών (αυτή η περίπτωση υποστηρίζει πολυεπίπεδες κατηγορίες). Εάν είναι false, τότε το φύλλο εργασίας ΔΕΝ χρησιμοποιείται για αποθήκευση τιμών (και αυτή η περίπτωση δεν υποστηρίζει πολυεπίπεδες κατηγορίες). Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setUseCells(boolean value) {#setUseCells-boolean-}
```
public abstract void setUseCells(boolean value)
```

Εάν είναι true, τότε το φύλλο εργασίας χρησιμοποιείται για αποθήκευση κατηγοριών (αυτή η περίπτωση υποστηρίζει πολυεπίπεδες κατηγορίες). Εάν είναι false, τότε το φύλλο εργασίας ΔΕΝ χρησιμοποιείται για αποθήκευση τιμών (και αυτή η περίπτωση δεν υποστηρίζει πολυεπίπεδες κατηγορίες). Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public abstract int getGroupingLevelCount()
```

Επιστρέφει τον αριθμό των επιπέδων ομαδοποίησης κατηγοριών που χρησιμοποιούνται. Είναι περισσότερο από ένα για πολυεπίπεδες κατηγορίες. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract IChartCategory add(IChartDataCell chartDataCell)
```

Εάν η κατηγορία υπάρχει στη συλλογή, την επιστρέφει. Διαφορετικά δημιουργεί νέα κατηγορία διαγράμματος από [IChartDataCell](../../com.aspose.slides/ichartdatacell) και την προσθέτει στη συλλογή.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Κελί που χρησιμοποιείται για τη δημιουργία κατηγορίας διαγράμματος. |

**Επιστρέφει:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Προστέθηκε ή υπάρχουσα κατηγορία.
### add(Object value) {#add-java.lang.Object-}
```
public abstract IChartCategory add(Object value)
```

Δημιουργεί νέο [IChartCategory](../../com.aspose.slides/ichartcategory) από την τιμή και το προσθέτει στη συλλογή.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | Η τιμή.

--------------------

Αυτή η μέθοδος προσθέτει φύλλο εργασίας με όνομα AUTO_DATA και προσθέτει όλες τις τιμές εκεί. Εάν χρησιμοποιείτε [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) για να προσθέσετε ή να επεξεργαστείτε τιμές κελιών, βεβαιωθείτε ότι δεν χρησιμοποιείτε αυτό το φύλλο εργασίας. Ο μέγιστος αριθμός τιμών που προστίθενται με αυτή τη μέθοδο δεν πρέπει να υπερβαίνει το 16711680 |

**Επιστρέφει:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Προστέθηκε [IChartCategory](../../com.aspose.slides/ichartcategory).
### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public abstract int indexOf(IChartCategory value)
```

Αναζητά το καθορισμένο [IChartCategory](../../com.aspose.slides/ichartcategory) και επιστρέφει το μηδενικό-βασισμένο ευρετήριο της πρώτης εμφάνισης εντός ολόκληρης της Συλλογής

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Κατηγορία διαγράμματος. |

**Επιστρέφει:**
int - Το μηδενικό-βασισμένο ευρετήριο της πρώτης εμφάνισης της τιμής εντός ολόκληρης της CollectionBase, εάν βρεθεί· διαφορετικά, -1.
### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public abstract void remove(IChartCategory value)
```

Αφαιρεί την καθορισμένη τιμή.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Η τιμή. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Αφαιρεί το στοιχείο στον δεδομένο δείκτη.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Δείκτης μιας κατηγορίας προς διαγραφή. |
### clear() {#clear--}
```
public abstract void clear()
```

Αφαιρεί όλα τα στοιχεία από τη συλλογή.