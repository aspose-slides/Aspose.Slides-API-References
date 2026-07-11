---
title: ColumnCollection
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αντιπροσωπεύει τη συλλογή στηλών σε έναν πίνακα.
type: docs
url: /el/com.aspose.slides/columncollection/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IColumnCollection](../../com.aspose.slides/icolumncollection)
```
public final class ColumnCollection extends DomObject<RowCollection> implements IColumnCollection
```

Αντιπροσωπεύει τη συλλογή στήλων σε έναν πίνακα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [size()](#size--) | Επιστρέφει τον αριθμό των στηλών σε μια συλλογή. |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει τη στήλη στον καθορισμένο δείκτη. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Δημιουργεί ένα αντίγραφο της καθορισμένης γραμμής προτύπου και το εισάγει στο κάτω μέρος ενός πίνακα. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Δημιουργεί ένα αντίγραφο της καθορισμένης στήλης προτύπου και το εισάγει στην καθορισμένη θέση σε έναν πίνακα. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Αφαιρεί μια στήλη στην καθορισμένη θέση από έναν πίνακα. |
| [iterator()](#iterator--) | Επιστρέφει έναν απαριθμητή που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει όλα τα στοιχεία από τη συλλογή στον καθορισμένο πίνακα. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει μια τιμή που δηλώνει αν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει μια ρίζα συγχρονισμού. |
### size() {#size--}
```
public final int size()
```

Επιστρέφει τον αριθμό των στηλών σε μια συλλογή. Μόνο-ανάγνωση int.

**Επιστρέφει:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IColumn get_Item(int index)
```

Επιστρέφει τη στήλη στον καθορισμένο δείκτη. Μόνο-ανάγνωση [Column](../../com.aspose.slides/column).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```

Δημιουργεί ένα αντίγραφο της καθορισμένης γραμμής προτύπου και το εισάγει στο κάτω μέρος ενός πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Στήλη που χρησιμοποιείται ως πρότυπο. |
| withAttachedColumns | boolean | True για αντιγραφή επίσης όλων των στηλών που συνδέονται με τη γραμμή προτύπου. |

**Επιστρέφει:**
com.aspose.slides.IColumn[] - Στήλες που προστέθηκαν.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

Δημιουργεί ένα αντίγραφο της καθορισμένης στήλης προτύπου και το εισάγει στην καθορισμένη θέση σε έναν πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης της νέας στήλης. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Στήλη που χρησιμοποιείται ως πρότυπο. |
| withAttachedColumns | boolean | True για αντιγραφή επίσης όλων των στηλών που συνδέονται με τη στήλη προτύπου. |

**Επιστρέφει:**
com.aspose.slides.IColumn[] - Στήλες που εισήχθησαν.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

Αφαιρεί μια στήλη στην καθορισμένη θέση από έναν πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| firstColumnIndex | int | Δείκτης της στήλης προς διαγραφή. |
| withAttachedRows | boolean | True για διαγραφή επίσης όλων των συνδεδεμένων στηλών. |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iterator()
```

Επιστρέφει έναν απαριθμητή που διατρέχει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για τη διέλευση της συλλογής.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iteratorJava()
```

Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - Ένας java.util.Iterator για ολόκληρη τη συλλογή.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Αντιγράφει όλα τα στοιχεία από τη συλλογή στον καθορισμένο πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Πίνακας προορισμού. |
| index | int | Αρχικός δείκτης στον πίνακα προορισμού. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Επιστρέφει μια τιμή που δηλώνει αν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Μόνο-ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Επιστρέφει μια ρίζα συγχρονισμού. Μόνο-ανάγνωση Object.

**Επιστρέφει:**
java.lang.Object