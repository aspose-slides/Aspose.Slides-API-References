---
title: CommentAuthorCollection
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αναπαριστά μια συλλογή από συγγραφείς σχολίων.
type: docs
url: /el/com.aspose.slides/commentauthorcollection/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
```
public final class CommentAuthorCollection extends DomObject<Presentation> implements ICommentAuthorCollection
```

Αναπαριστά μια συλλογή από συγγραφείς σχολίων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [size()](#size--) | Λαμβάνει τον αριθμό των στοιχείων που περιέχονται στην συλλογή. |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει το στοιχείο στο συγκεκριμένο δείκτη. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Προσθέτει νέο συγγραφέα στο τέλος μιας συλλογής. |
| [toArray()](#toArray--) | Δημιουργεί και επιστρέφει έναν πίνακα με όλους τους συγγραφείς. |
| [findByName(String name)](#findByName-java.lang.String-) | Βρίσκει συγγραφέα σε μια συλλογή με βάση το όνομα. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | Βρίσκει συγγραφέα σε μια συλλογή με βάση το όνομα και τα αρχικά. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί τον συγγραφέα στο καθορισμένο δείκτη της συλλογής. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Αφαιρεί την πρώτη εμφάνιση του καθορισμένου συγγραφέα σε μια συλλογή. |
| [clear()](#clear--) | Αφαιρεί όλους τους συγγραφείς από μια συλλογή. |
| [iterator()](#iterator--) | Επιστρέφει έναν απαριθμητή που διασχίζει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει όλα τα στοιχεία από τη συλλογή στον καθορισμένο πίνακα. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει μια τιμή που υποδεικνύει αν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει μια ρίζα συγχρονισμού. |

### size() {#size--}
```
public final int size()
```

Λαμβάνει τον αριθμό των στοιχείων που περιέχονται στην συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int

### get_Item(int index) {#get-Item-int-}
```
public final ICommentAuthor get_Item(int index)
```

Λαμβάνει το στοιχείο στο συγκεκριμένο δείκτη. Μόνο για ανάγνωση [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)

### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public final ICommentAuthor addAuthor(String name, String initials)
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
public final ICommentAuthor[] toArray()
```

Δημιουργεί και επιστρέφει έναν πίνακα με όλους τους συγγραφείς.

**Επιστρέφει:**
com.aspose.slides.ICommentAuthor[] - Πίνακας του [ICommentAuthor](../../com.aspose.slides/icommentauthor)

### findByName(String name) {#findByName-java.lang.String-}
```
public final ICommentAuthor[] findByName(String name)
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
public final ICommentAuthor[] findByNameAndInitials(String name, String initials)
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
public final void removeAt(int index)
```

Αφαιρεί τον συγγραφέα στο καθορισμένο δείκτη της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης του στοιχείου προς αφαίρεση. |

### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public final void remove(ICommentAuthor author)
```

Αφαιρεί την πρώτη εμφάνιση του καθορισμένου συγγραφέα σε μια συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Ο συγγραφέας προς αφαίρεση από μια συλλογή. |

### clear() {#clear--}
```
public final void clear()
```

Αφαιρεί όλους τους συγγραφείς από μια συλλογή.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iterator()
```

Επιστρέφει έναν απαριθμητή που διασχίζει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για την διαπέραση της συλλογής.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iteratorJava()
```

Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - Ένας java.util.Iterator για ολόκληρη τη συλλογή.

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

Επιστρέφει μια τιμή που υποδεικνύει αν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Επιστρέφει μια ρίζα συγχρονισμού. Μόνο για ανάγνωση Object.

**Επιστρέφει:**
java.lang.Object