---
title: CommentCollection
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Αντιπροσωπεύει μια συλλογή σχολίων ενός συγγραφέα.
type: docs
url: /el/com.aspose.slides/commentcollection/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.ICommentCollection](../../com.aspose.slides/icommentcollection)
```
public final class CommentCollection extends DomObject<CommentAuthor> implements ICommentCollection
```

Αντιπροσωπεύει μια συλλογή σχολίων ενός συγγραφέα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [size()](#size--) | Επιστρέφει τον αριθμό των στοιχείων που περιέχονται πραγματικά στη συλλογή. |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει το στοιχείο στον καθορισμένο δείκτη. |
| [addComment(String text, ISlide slide, PointF position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Προσθέτει νέο σχόλιο στο τέλος μιας συλλογής. |
| [addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Προσθέτει νέο μοντέρνο σχόλιο στο τέλος μιας συλλογής. |
| [insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Εισάγει νέο σχόλιο στη συλλογή στον καθορισμένο δείκτη. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Εισάγει νέο μοντέρνο σχόλιο στη συλλογή στον καθορισμένο δείκτη. |
| [toArray()](#toArray--) | Δημιουργεί και επιστρέφει έναν πίνακα με όλα τα σχόλια. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Δημιουργεί και επιστρέφει έναν πίνακα με όλα τα σχόλια από το καθορισμένο εύρος. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το στοιχείο στον καθορισμένο δείκτη σε μια συλλογή. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Αφαιρεί την πρώτη εμφάνιση του καθορισμένου σχολίου σε μια συλλογή. |
| [clear()](#clear--) | Αφαιρεί όλα τα σχόλια από μια συλλογή. |
| [iterator()](#iterator--) | Επιστρέφει έναν επαναλήπτη που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
| [findCommentByIdx(int idx)](#findCommentByIdx-int-) | Βρίσκει ένα σχόλιο στη συλλογή με βάση το δείκτη. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει όλα τα στοιχεία από τη συλλογή στον καθορισμένο πίνακα. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει μια τιμή που υποδεικνύει αν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει τη ρίζα συγχρονισμού. |
### size() {#size--}
```
public final int size()
```


Επιστρέφει τον αριθμό των στοιχείων που περιέχονται πραγματικά στη συλλογή. Μόνο για ανάγνωση  int .

**Επιστρέφει:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IComment get_Item(int index)
```


Επιστρέφει το στοιχείο στον καθορισμένο δείκτη. Μόνο για ανάγνωση [Comment](../../com.aspose.slides/comment).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, PointF position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public final IComment addComment(String text, ISlide slide, PointF position, Date creationTime)
```


Προσθέτει νέο σχόλιο στο τέλος μιας συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Απλό κείμενο ενός νέου σχολίου. |
| slide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια σε μια παρουσίαση όπου θα προστεθεί ένα νέο σχόλιο. |
| position | android.graphics.PointF | Θέση σε μια διαφάνεια όπου θα προστεθεί ένα νέο σχόλιο. |
| creationTime | java.util.Date | Χρόνος δημιουργίας του σχολίου. |

**Επιστρέφει:**
[IComment](../../com.aspose.slides/icomment) - Προστέθηκε σχόλιο.
### addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public final IModernComment addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```


Προσθέτει νέο μοντέρνο σχόλιο στο τέλος μιας συλλογής.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ICommentAuthor newAuthor = pres.getCommentAuthors().addAuthor("Some Author", "SA");
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new android.graphics.PointF(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Απλό κείμενο ενός νέου μοντέρνου σχολίου. |
| slide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια σε μια παρουσίαση όπου θα προστεθεί ένα νέο μοντέρνο σχόλιο. |
| shape | [IShape](../../com.aspose.slides/ishape) | Σχήμα σε μια διαφάνεια στο οποίο συσχετίζεται ένα νέο μοντέρνο σχόλιο. |
| position | android.graphics.PointF | Θέση σε μια διαφάνεια όπου θα προστεθεί ένα νέο μοντέρνο σχόλιο. |
| creationTime | java.util.Date | Χρόνος δημιουργίας του μοντέρνου σχολίου. |

**Επιστρέφει:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Προστέθηκε μοντέρνο σχόλιο.
### insertComment(int index, String text, ISlide slide, PointF position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public final IComment insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)
```


Εισάγει νέο σχόλιο στη συλλογή στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης του στοιχείου στη συλλογή όπου πρέπει να εισαχθεί το σχόλιο. |
| text | java.lang.String | Απλό κείμενο ενός νέου σχολίου. |
| slide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια σε μια παρουσίαση όπου θα προστεθεί ένα νέο σχόλιο. |
| position | android.graphics.PointF | Θέση σε μια διαφάνεια όπου θα προστεθεί ένα νέο σχόλιο. |
| creationTime | java.util.Date | Χρόνος δημιουργίας του σχολίου. |

**Επιστρέφει:**
[IComment](../../com.aspose.slides/icomment) - Εισαχθέν σχόλιο.
### insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public final IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```


Εισάγει νέο μοντέρνο σχόλιο στη συλλογή στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης του στοιχείου στη συλλογή όπου πρέπει να εισαχθεί το μοντέρνο σχόλιο. |
| text | java.lang.String | Απλό κείμενο ενός νέου μοντέρνου σχολίου. |
| slide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια σε μια παρουσίαση όπου θα προστεθεί ένα νέο μοντέρνο σχόλιο. |
| shape | [IShape](../../com.aspose.slides/ishape) | Σχήμα σε μια διαφάνεια στο οποίο συσχετίζεται ένα νέο μοντέρνο σχόλιο. |
| position | android.graphics.PointF | Θέση σε μια διαφάνεια όπου θα προστεθεί ένα νέο μοντέρνο σχόλιο. |
| creationTime | java.util.Date | Χρόνος δημιουργίας του μοντέρνου σχολίου. |

**Επιστρέφει:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Εισαχθέν μοντέρνο σχόλιο.
### toArray() {#toArray--}
```
public final IComment[] toArray()
```


Δημιουργεί και επιστρέφει έναν πίνακα με όλα τα σχόλια.

**Επιστρέφει:**
com.aspose.slides.IComment[] - Πίνακας των [Comment](../../com.aspose.slides/comment).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IComment[] toArray(int startIndex, int count)
```


Δημιουργεί και επιστρέφει έναν πίνακα με όλα τα σχόλια από το καθορισμένο εύρος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| startIndex | int | Δείκτης του πρώτου σχολίου που θα επιστραφεί. |
| count | int | Αριθμός σχολίων που θα επιστραφούν. |

**Επιστρέφει:**
com.aspose.slides.IComment[] - Πίνακας των [Comment](../../com.aspose.slides/comment).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Αφαιρεί το στοιχείο στον καθορισμένο δείκτη σε μια συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης του στοιχείου που θα αφαιρεθεί. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public final void remove(IComment comment)
```


Αφαιρεί την πρώτη εμφάνιση του καθορισμένου σχολίου σε μια συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | Το σχόλιο που θα αφαιρεθεί από τη συλλογή. |

### clear() {#clear--}
```
public final void clear()
```


Αφαιρεί όλα τα σχόλια από μια συλλογή.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iterator()
```


Επιστρέφει έναν επαναλήπτη που διατρέχει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για να διατρέξει τη συλλογή.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iteratorJava()
```


Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - Ένα java.util.Iterator για ολόκληρη τη συλλογή.
### findCommentByIdx(int idx) {#findCommentByIdx-int-}
```
public final IComment findCommentByIdx(int idx)
```


Βρίσκει ένα σχόλιο στη συλλογή με βάση το δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| idx | int | Μοναδικός δείκτης ενός σχολίου προς εύρεση  int . |

**Επιστρέφει:**
[IComment](../../com.aspose.slides/icomment) - Βρέθηκε το σχόλιο ή null [IComment](../../com.aspose.slides/icomment).
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Αντιγράφει όλα τα στοιχεία από τη συλλογή στον καθορισμένο πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Πίνακας-στόχος. |
| index | int | Αρχικός δείκτης στον πίνακα-στόχο. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Επιστρέφει μια τιμή που υποδεικνύει αν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Μόνο για ανάγνωση  boolean .

**Επιστρέφει:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Επιστρέφει τη ρίζα συγχρονισμού. Μόνο για ανάγνωση  Object .

**Επιστρέφει:**
java.lang.Object