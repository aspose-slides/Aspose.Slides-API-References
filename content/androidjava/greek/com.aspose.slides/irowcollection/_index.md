---
title: IRowCollection
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αναπαριστά τη συλλογή γραμμών πίνακα.
type: docs
url: /el/com.aspose.slides/irowcollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.slides.IGenericCollection
```
public interface IRowCollection extends IGenericCollection<IRow>
```

Αναπαριστά τη συλλογή γραμμών πίνακα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Αποκτά το στοιχείο στη συγκεκριμένη θέση. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Δημιουργεί ένα αντίγραφο της συγκεκριμένης γραμμής προτύπου και το τοποθετεί στο τέλος ενός πίνακα. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Δημιουργεί ένα αντίγραφο της συγκεκριμένης γραμμής προτύπου και το εισάγει στη συγκεκριμένη θέση σε έναν πίνακα. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Αφαιρεί μια γραμμή στη συγκεκριμένη θέση από έναν πίνακα. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IRow get_Item(int index)
```


Αποκτά το στοιχείο στη συγκεκριμένη θέση.

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


Δημιουργεί ένα αντίγραφο της συγκεκριμένης γραμμής προτύπου και το τοποθετεί στο τέλος ενός πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Γραμμή που χρησιμοποιείται ως πρότυπο. |
| withAttachedRows | boolean | True για να αντιγραφούν επίσης όλες οι γραμμές συνδεδεμένες με τη γραμμή προτύπου. |

**Επιστρέφει:**
com.aspose.slides.IRow[] - Added rows.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```


Δημιουργεί ένα αντίγραφο της συγκεκριμένης γραμμής προτύπου και το εισάγει στη συγκεκριμένη θέση σε έναν πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης μιας νέας γραμμής. |
| templ | [IRow](../../com.aspose.slides/irow) | Γραμμή που χρησιμοποιείται ως πρότυπο. |
| withAttachedRows | boolean | True για να αντιγραφούν επίσης όλες οι γραμμές συνδεδεμένες με τη γραμμή προτύπου. |

**Επιστρέφει:**
com.aspose.slides.IRow[] - Inserted rows.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstRowIndex, boolean withAttachedRows)
```


Αφαιρεί μια γραμμή στη συγκεκριμένη θέση από έναν πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| firstRowIndex | int | Δείκτης μιας γραμμής προς διαγραφή. |
| withAttachedRows | boolean | True για να διαγραφούν επίσης όλες οι συνδεδεμένες γραμμές. |