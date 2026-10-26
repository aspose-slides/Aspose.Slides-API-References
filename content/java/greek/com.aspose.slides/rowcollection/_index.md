---
title: RowCollection
second_title: Αναφορά API Aspose.Slides για Java
description: Αναπαριστά τη συλλογή σειρών πίνακα.
type: docs
url: /el/com.aspose.slides/rowcollection/
---
**Κληρονόμηση:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι Υλοποιημένες Διασυνδέσεις:**
[com.aspose.slides.IRowCollection](../../com.aspose.slides/irowcollection)
```
public final class RowCollection extends DomObject<Table> implements IRowCollection
```

Αναπαριστά τη συλλογή σειρών πίνακα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [size()](#size--) | Αποκτά τον αριθμό των σειρών που περιέχονται πραγματικά στη συλλογή. |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει τη σειρά στο καθορισμένο δείκτη. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Δημιουργεί ένα αντίγραφο της συγκεκριμένης σειράς προτύπου και το εισάγει στο κάτω μέρος ενός πίνακα. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Δημιουργεί ένα αντίγραφο της συγκεκριμένης σειράς προτύπου και το εισάγει στη συγκεκριμένη θέση σε έναν πίνακα. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Αφαιρεί μια σειρά στη συγκεκριμένη θέση από έναν πίνακα. |
| [iterator()](#iterator--) | Επιστρέφει έναν επαναλήπτη που διασχίζει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java επαναλήπτη για ολόκληρη τη συλλογή. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει όλα τα στοιχεία από τη συλλογή στον καθορισμένο πίνακα. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει μια τιμή που υποδεικνύει αν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει τη ρίζα συγχρονισμού. |
### size() {#size--}
```
public final int size()
```


Αποκτά τον αριθμό των σειρών που περιέχονται πραγματικά στη συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IRow get_Item(int index)
```


Επιστρέφει τη σειρά στο καθορισμένο δείκτη. Μόνο για ανάγνωση [Row](../../com.aspose.slides/row).

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


Δημιουργεί ένα αντίγραφο της συγκεκριμένης σειράς προτύπου και το εισάγει στο κάτω μέρος ενός πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Σειρά που χρησιμοποιείται ως πρότυπο. |
| withAttachedRows | boolean | True για αντιγραφή επίσης όλων των σειρών που είναι συνημμένες στη σειρά προτύπου. |

**Επιστρέφει:**
com.aspose.slides.IRow[] - Προστιθέμενες σειρές.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public final IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```


Δημιουργεί ένα αντίγραφο της συγκεκριμένης σειράς προτύπου και το εισάγει στη συγκεκριμένη θέση σε έναν πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης μιας νέας σειράς. |
| templ | [IRow](../../com.aspose.slides/irow) | Σειρά που χρησιμοποιείται ως πρότυπο. |
| withAttachedRows | boolean | True για αντιγραφή επίσης όλων των σειρών που είναι συνημμένες στη σειρά προτύπου. |

**Επιστρέφει:**
com.aspose.slides.IRow[] - Εισαχθείσες σειρές.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstRowIndex, boolean withAttachedRows)
```


Αφαιρεί μια σειρά στη συγκεκριμένη θέση από έναν πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| firstRowIndex | int | Δείκτης μιας σειράς προς διαγραφή. |
| withAttachedRows | boolean | True για διαγραφή επίσης όλων των συνημμένων σειρών. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iterator()
```


Επιστρέφει έναν επαναλήπτη που διασχίζει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για να διασχίζει τη συλλογή.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iteratorJava()
```


Επιστρέφει έναν java επαναλήπτη για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - Ένας java.util.Iterator για ολόκληρη τη συλλογή.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Αντιγράφει όλα τα στοιχεία από τη συλλογή στον καθορισμένο πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Στοχευόμενος πίνακας. |
| index | int | Αρχικός δείκτης στον στοχευόμενο πίνακα. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Επιστρέφει μια τιμή που υποδεικνύει αν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Επιστρέφει τη ρίζα συγχρονισμού. Μόνο για ανάγνωση Object.

**Επιστρέφει:**
java.lang.Object