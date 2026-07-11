---
title: ICommentAuthorCollection
second_title: Αναφορά API Java για Aspose.Slides για Android
description: Αντιπροσωπεύει μια συλλογή από συγγραφείς σχολίων.
type: docs
url: /el/com.aspose.slides/icommentauthorcollection/
---
**Όλες οι υλοποιημένες διεπαφές:**
com.aspose.slides.IGenericCollection
```
public interface ICommentAuthorCollection extends IGenericCollection<ICommentAuthor>
```

Αντιπροσωπεύει μια συλλογή από συγγραφείς σχολίων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει το στοιχείο στο καθορισμένο δείκτη. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Προσθέτει νέο συγγραφέα στο τέλος μιας συλλογής. |
| [toArray()](#toArray--) | Δημιουργεί και επιστρέφει έναν πίνακα με όλους τους συγγραφείς. |
| [findByName(String name)](#findByName-java.lang.String-) | Βρίσκει συγγραφέα σε μια συλλογή με βάση το όνομα. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | Βρίσκει συγγραφέα σε μια συλλογή με βάση το όνομα και τα αρχικά. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί τον συγγραφέα στη συγκεκριμένη θέση της συλλογής. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Αφαιρεί την πρώτη εμφάνιση του συγκεκριμένου συγγραφέα σε μια συλλογή. |
| [clear()](#clear--) | Αφαιρεί όλους τους συγγραφείς από μια συλλογή. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICommentAuthor get_Item(int index)
```

Λαμβάνει το στοιχείο στο καθορισμένο δείκτη. Μόνο για ανάγνωση [ICommentAuthor](../../com.aspose.slides/icommentauthor).

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
| name | java.lang.String | Όνομα νέου συγγραφέα. |
| initials | java.lang.String | Αρχικά νέου συγγραφέα. |

**Επιστρέφει:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - Νέο [ICommentAuthor](../../com.aspose.slides/icommentauthor) αντικείμενο.
### toArray() {#toArray--}
```
public abstract ICommentAuthor[] toArray()
```

Δημιουργεί και επιστρέφει έναν πίνακα με όλους τους συγγραφείς.

**Επιστρέφει:**
com.aspose.slides.ICommentAuthor[] - Πίνακας των [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public abstract ICommentAuthor[] findByName(String name)
```

Βρίσκει συγγραφέα σε μια συλλογή με βάση το όνομα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα συγγραφέα προς εύρεση. |

**Επιστρέφει:**
com.aspose.slides.ICommentAuthor[] - Συγγραφέας ή null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor[] findByNameAndInitials(String name, String initials)
```

Βρίσκει συγγραφέα σε μια συλλογή με βάση το όνομα και τα αρχικά.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα συγγραφέα προς εύρεση. |
| initials | java.lang.String | Αρχικά συγγραφέα προς εύρεση. |

**Επιστρέφει:**
com.aspose.slides.ICommentAuthor[] - Συγγραφέας ή null.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Αφαιρεί τον συγγραφέα στη συγκεκριμένη θέση της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης του στοιχείου προς αφαίρεση. |

### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public abstract void remove(ICommentAuthor author)
```

Αφαιρεί την πρώτη εμφάνιση του συγκεκριμένου συγγραφέα σε μια συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Ο συγγραφέας που θα αφαιρεθεί από τη συλλογή. |

### clear() {#clear--}
```
public abstract void clear()
```

Αφαιρεί όλους τους συγγραφείς από μια συλλογή.