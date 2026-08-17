---
title: ICommentAuthorCollection
second_title: Αναφορά API Aspose.Slides για Java
description: Αναπαριστά μια συλλογή από συγγραφείς σχολίων.
type: docs
url: /el/com.aspose.slides/icommentauthorcollection/
---
**Όλες οι υλοποιημένες διεπαφές:**
com.aspose.slides.IGenericCollection
```
public interface ICommentAuthorCollection extends IGenericCollection<ICommentAuthor>
```

Αναπαριστά μια συλλογή από συγγραφείς σχολίων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει το στοιχείο στη συγκεκριμένη θέση. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Προσθέτει νέο συγγραφέα στο τέλος μιας συλλογής. |
| [toArray()](#toArray--) | Δημιουργεί και επιστρέφει έναν πίνακα με όλους τους συγγραφείς. |
| [findByName(String name)](#findByName-java.lang.String-) | Βρίσκει συγγραφέα σε μια συλλογή κατά όνομα. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | Βρίσκει συγγραφέα σε μια συλλογή κατά όνομα και αρχικά. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το συγγραφέα στη συγκεκριμένη θέση της συλλογής. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Αφαιρεί την πρώτη εμφάνιση του συγκεκριμένου συγγραφέα σε μια συλλογή. |
| [clear()](#clear--) | Αφαιρεί όλους τους συγγραφείς από μια συλλογή. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICommentAuthor get_Item(int index)
```


Λαμβάνει το στοιχείο στη συγκεκριμένη θέση. Μόνο για ανάγνωση [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor addAuthor(String name, String initials)
```


Προσθέτει νέο συγγραφέα στο τέλος μιας συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Το όνομα ενός νέου συγγραφέα. |
| initials | java.lang.String | Τα αρχικά ενός νέου συγγραφέα. |

**Επιστρέφει:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - Νέο αντικείμενο [ICommentAuthor](../../com.aspose.slides/icommentauthor).
### toArray() {#toArray--}
```
public abstract ICommentAuthor[] toArray()
```


Δημιουργεί και επιστρέφει έναν πίνακα με όλους τους συγγραφείς.

**Επιστρέφει:**
com.aspose.slides.ICommentAuthor[] - Πίνακας του [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public abstract ICommentAuthor[] findByName(String name)
```


Βρίσκει συγγραφέα σε μια συλλογή κατά όνομα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Το όνομα ενός συγγραφέα προς εύρεση. |

**Επιστρέφει:**
com.aspose.slides.ICommentAuthor[] - Συγγραφέας ή null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor[] findByNameAndInitials(String name, String initials)
```


Βρίσκει συγγραφέα σε μια συλλογή κατά όνομα και αρχικά.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Το όνομα ενός συγγραφέα προς εύρεση. |
| initials | java.lang.String | Τα αρχικά ενός συγγραφέα προς εύρεση. |

**Επιστρέφει:**
com.aspose.slides.ICommentAuthor[] - Συγγραφέας ή null.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Αφαιρεί το συγγραφέα στη συγκεκριμένη θέση της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | |
| index | int | Ο δείκτης μηδενικής βάσης του στοιχείου που θα αφαιρεθεί. |
### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public abstract void remove(ICommentAuthor author)
```


Αφαιρεί την πρώτη εμφάνιση του συγκεκριμένου συγγραφέα σε μια συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Ο συγγραφέας που θα αφαιρεθεί από τη συλλογή. |
### clear() {#clear--}
```
public abstract void clear()
```


Αφαιρεί όλους τους συγγραφείς από μια συλλογή.