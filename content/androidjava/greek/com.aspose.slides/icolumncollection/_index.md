---
title: IColumnCollection
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αντιπροσωπεύει τη συλλογή των στηλών σε έναν πίνακα.
type: docs
url: /el/com.aspose.slides/icolumncollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.slides.IGenericCollection
```
public interface IColumnCollection extends IGenericCollection<IColumn>
```

Αντιπροσωπεύει τη συλλογή των στηλών σε έναν πίνακα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει τη στήλη στο συγκεκριμένο δείκτη. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Δημιουργεί ένα αντίγραφο της καθορισμένης γραμμής προτύπου και το τοποθετεί στο κάτω μέρος ενός πίνακα. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Δημιουργεί ένα αντίγραφο της καθορισμένης στήλης προτύπου και το τοποθετεί στη συγκεκριμένη θέση σε έναν πίνακα. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Αφαιρεί μια στήλη στη συγκεκριμένη θέση από έναν πίνακα. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColumn get_Item(int index)
```

Επιστρέφει τη στήλη στο συγκεκριμένο δείκτη. Μόνο για ανάγνωση [IColumn](../../com.aspose.slides/icolumn).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```

Δημιουργεί ένα αντίγραφο της καθορισμένης γραμμής προτύπου και το τοποθετεί στο κάτω μέρος ενός πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Στήλη που χρησιμοποιείται ως πρότυπο. |
| withAttachedColumns | boolean | Αληθές για αντιγραφή επίσης όλων των στηλών που είναι συνδεδεμένες με τη γραμμή προτύπου. |

**Επιστρέφει:**
com.aspose.slides.IColumn[] - Προστέθηκαν στήλες.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

Δημιουργεί ένα αντίγραφο της καθορισμένης στήλης προτύπου και το τοποθετεί στη συγκεκριμένη θέση σε έναν πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης νέας στήλης. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Στήλη που χρησιμοποιείται ως πρότυπο. |
| withAttachedColumns | boolean | Αληθές για αντιγραφή επίσης όλων των στηλών που είναι συνδεδεμένες με τη στήλη προτύπου. |

**Επιστρέφει:**
com.aspose.slides.IColumn[] - Εισαγόμενες στήλες.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

Αφαιρεί μια στήλη στη συγκεκριμένη θέση από έναν πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| firstColumnIndex | int | Δείκτης της στήλης για διαγραφή. |
| withAttachedRows | boolean | Αληθές για διαγραφή επίσης όλων των συνδεδεμένων στηλών. |