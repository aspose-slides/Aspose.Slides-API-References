---
title: RowCollection
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Αναπαριστά τη συλλογή γραμμών πίνακα.
type: docs
url: /el/com.aspose.slides/rowcollection/
---
**Κληρονόμηση:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IRowCollection](../../com.aspose.slides/irowcollection)
```
public final class RowCollection extends DomObject<Table> implements IRowCollection
```

Αναπαριστά τη συλλογή γραμμών πίνακα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [size()](#size--) | Επιστρέφει τον αριθμό των γραμμών που περιέχονται στην συλλογή. |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει τη γραμμή στον καθορισμένο δείκτη. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Δημιουργεί αντίγραφο της καθορισμένης γραμμής προτύπου και την εισάγει στο κάτω μέρος ενός πίνακα. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Δημιουργεί αντίγραφο της καθορισμένης γραμμής προτύπου και την εισάγει στη συγκεκριμένη θέση σε έναν πίνακα. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Αφαιρεί μια γραμμή στη συγκεκριμένη θέση από έναν πίνακα. |
| [iterator()](#iterator--) | Επιστρέφει έναν enumerator που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει όλα τα στοιχεία της συλλογής στον καθορισμένο πίνακα. |
| [isSynchronized()](#isSynchronized--) | Επιστέφει τιμή που υποδεικνύει αν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει τη ρίζα συγχρονισμού. |
### size() {#size--}
```
public final int size()
```


Επιστρέφει τον αριθμό των γραμμών που περιέχονται στην συλλογή. Μόνο-ανάγνωση int.

**Επιστρέφει:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IRow get_Item(int index)
```


Επιστρέφει τη γραμμή στον καθορισμένο δείκτη. Μόνο-ανάγνωση [Row](../../com.aspose.slides/row).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public final IRow[] addClone(IRow templ, boolean withAttachedRows)
```


Δημιουργεί αντίγραφο της καθορισμένης γραμμής προτύπου και την εισάγει στο κάτω μέρος ενός πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Γραμμή που χρησιμοποιείται ως πρότυπο. |
| withAttachedRows | boolean | Αληθές για αντιγραφή επίσης όλων των γραμμών που είναι συνδεδεμένες με τη γραμμή προτύπου. |

**Επιστρέφει:**
com.aspose.slides.IRow[] - Προστέθηκαν γραμμές.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public final IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```


Δημιουργεί αντίγραφο της καθορισμένης γραμμής προτύπου και την εισάγει στη συγκεκριμένη θέση σε έναν πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης νέας γραμμής. |
| templ | [IRow](../../com.aspose.slides/irow) | Γραμμή που χρησιμοποιείται ως πρότυπο. |
| withAttachedRows | boolean | Αληθές για αντιγραφή επίσης όλων των γραμμών που είναι συνδεδεμένες με τη γραμμή προτύπου. |

**Επιστρέφει:**
com.aspose.slides.IRow[] - Εισαχθείσες γραμμές.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstRowIndex, boolean withAttachedRows)
```


Αφαιρεί μια γραμμή στη συγκεκριμένη θέση από έναν πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| firstRowIndex | int | Δείκτης της γραμμής που θα διαγραφεί. |
| withAttachedRows | boolean | Αληθές για διαγραφή επίσης όλων των συνδεδεμένων γραμμών. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iterator()
```


Επιστρέφει έναν enumerator που διατρέχει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για διαπέραση της συλλογής.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iteratorJava()
```


Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - Ένα java.util.Iterator για ολόκληρη τη συλλογή.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Αντιγράφει όλα τα στοιχεία της συλλογής στον καθορισμένο πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Πίνακας-στόχος. |
| index | int | Αρχικός δείκτης στον πίνακα-στόχο. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Επιστέφει τιμή που υποδεικνύει αν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Μόνο-ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Επιστρέφει τη ρίζα συγχρονισμού. Μόνο-ανάγνωση Object.

**Επιστρέφει:**
java.lang.Object