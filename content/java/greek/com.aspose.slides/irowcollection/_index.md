---
title: IRowCollection
second_title: Aspose.Slides για Java Αναφορά API
description: Αντιπροσωπεύει τη συλλογή γραμμών πίνακα.
type: docs
url: /el/com.aspose.slides/irowcollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.slides.IGenericCollection
```
public interface IRowCollection extends IGenericCollection<IRow>
```

Αντιπροσωπεύει τη συλλογή γραμμών πίνακα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Παίρνει το στοιχείο στον καθορισμένο δείκτη. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Δημιουργεί ένα αντίγραφο της καθορισμένης γραμμής προτύπου και το τοποθετεί στο κάτω μέρος ενός πίνακα. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Δημιουργεί ένα αντίγραφο της καθορισμένης γραμμής προτύπου και το τοποθετεί στην καθορισμένη θέση σε έναν πίνακα. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Αφαιρεί μια γραμμή στην καθορισμένη θέση από έναν πίνακα. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IRow get_Item(int index)
```


Παίρνει το στοιχείο στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] addClone(IRow templ, boolean withAttachedRows)
```


Δημιουργεί ένα αντίγραφο της καθορισμένης γραμμής προτύπου και το τοποθετεί στο κάτω μέρος ενός πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Γραμμή που χρησιμοποιείται ως πρότυπο. |
| withAttachedRows | boolean | Αληθές για αντιγραφή επίσης όλων των γραμμών που είναι συνδεδεμένες με τη γραμμή προτύπου. |

**Επιστρέφει:**
com.aspose.slides.IRow[] - Προστέθηκαν γραμμές.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```


Δημιουργεί ένα αντίγραφο της καθορισμένης γραμμής προτύπου και το τοποθετεί στην καθορισμένη θέση σε έναν πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης μιας νέας γραμμής. |
| templ | [IRow](../../com.aspose.slides/irow) | Γραμμή που χρησιμοποιείται ως πρότυπο. |
| withAttachedRows | boolean | Αληθές για αντιγραφή επίσης όλων των γραμμών που είναι συνδεδεμένες με τη γραμμή προτύπου. |

**Επιστρέφει:**
com.aspose.slides.IRow[] - Εισαχθείσες γραμμές.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstRowIndex, boolean withAttachedRows)
```


Αφαιρεί μια γραμμή στην καθορισμένη θέση από έναν πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| firstRowIndex | int | Δείκτης μιας γραμμής για διαγραφή. |
| withAttachedRows | boolean | Αληθές για διαγραφή επίσης όλων των συνδεδεμένων γραμμών. |