---
title: CommentCollection
second_title: Αναφορά API του Aspose.Slides για Java
description: Αναπαριστά μια συλλογή σχολίων ενός συγγραφέα.
type: docs
url: /el/com.aspose.slides/commentcollection/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι Υλοποιημένες Διασυνδέσεις:**
[com.aspose.slides.ICommentCollection](../../com.aspose.slides/icommentcollection)
```
public final class CommentCollection extends DomObject<CommentAuthor> implements ICommentCollection
```

Αντιπροσωπεύει μια συλλογή σχολίων ενός συγγραφέα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [size()](#size--) | Αποκτά τον αριθμό των στοιχείων που πραγματικά περιέχονται στη συλλογή. |
| [get_Item(int index)](#get-Item-int-) | Αποκτά το στοιχείο στο συγκεκριμένο δείκτη. |
| [addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Προσθέτει νέο σχόλιο στο τέλος μιας συλλογής. |
| [addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Προσθέτει νέο σύγχρονο σχόλιο στο τέλος μιας συλλογής. |
| [insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Εισάγει νέο σχόλιο σε μια συλλογή στον καθορισμένο δείκτη. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Εισάγει νέο σύγχρονο σχόλιο σε μια συλλογή στον καθορισμένο δείκτη. |
| [toArray()](#toArray--) | Δημιουργεί και επιστρέφει έναν πίνακα με όλα τα σχόλια. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Δημιουργεί και επιστρέφει έναν πίνακα με όλα τα σχόλια από το καθορισμένο εύρος. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το στοιχείο στον καθορισμένο δείκτη σε μια συλλογή. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Αφαιρεί την πρώτη εμφάνιση του καθορισμένου σχολίου σε μια συλλογή. |
| [clear()](#clear--) | Αφαιρεί όλα τα σχόλια από μια συλλογή. |
| [iterator()](#iterator--) | Επιστρέφει έναν απαριθμητή που επαναλαμβάνει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
| [findCommentByIdx(int idx)](#findCommentByIdx-int-) | Βρίσκει ένα σχόλιο στη συλλογή με βάση το δείκτη. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει όλα τα στοιχεία από τη συλλογή στον καθορισμένο πίνακα. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει μια τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει μία ρίζα συγχρονισμού. |

### size() {#size--}
```
public final int size()
```

Αποκτά τον αριθμό των στοιχείων που πραγματικά περιέχονται στη συλλογή. Μόνο για ανάγνωση  int .

**Επιστρέφει:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IComment get_Item(int index)
```

Αποκτά το στοιχείο στο καθορισμένο δείκτη. Μόνο για ανάγνωση [Comment](../../com.aspose.slides/comment).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IComment](../../com.aspose.slides/icomment)

### addComment(String text, ISlide slide, Point2D.Float position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IComment addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)
```

Προσθέτει νέο σχόλιο στο τέλος μιας συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Απλό κείμενο ενός νέου σχολίου. |
| slide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια σε μια παρουσίαση όπου θα προστεθεί ένα νέο σχόλιο. |
| position | java.awt.geom.Point2D.Float | Θέση σε μια διαφάνεια όπου θα προστεθεί ένα νέο σχόλιο. |
| creationTime | java.util.Date | Χρόνος δημιουργίας του σχολίου. |

**Επιστρέφει:**
[IComment](../../com.aspose.slides/icomment) - Προστέθηκε το σχόλιο.

### addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IModernComment addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

Προσθέτει νέο σύγχρονο σχόλιο στο τέλος μιας συλλογής.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ICommentAuthor newAuthor = pres.getCommentAuthors().addAuthor("Some Author", "SA");
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new Point2D.Float(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Απλό κείμενο ενός νέου σύγχρονου σχολίου. |
| slide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια σε μια παρουσίαση όπου θα προστεθεί ένα νέο σύγχρονο σχόλιο. |
| shape | [IShape](../../com.aspose.slides/ishape) | Σχήμα σε μια διαφάνεια στο οποίο συσχετίζεται το νέο σύγχρονο σχόλιο. |
| position | java.awt.geom.Point2D.Float | Θέση σε μια διαφάνεια όπου θα προστεθεί ένα νέο σύγχρονο σχόλιο. |
| creationTime | java.util.Date | Χρόνος δημιουργίας του σύγχρονου σχολίου. |

**Επιστρέφει:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Προστέθηκε το σύγχρονο σχόλιο.

### insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IComment insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)
```

Εισάγει νέο σχολείο σε μια συλλογή στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης του στοιχείου σε μια συλλογή όπου θα πρέπει να εισαχθεί το σχόλιο. |
| text | java.lang.String | Απλό κείμενο ενός νέου σχολίου. |
| slide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια σε μια παρουσίαση όπου θα προστεθεί ένα νέο σχόλιο. |
| position | java.awt.geom.Point2D.Float | Θέση σε μια διαφάνεια όπου θα προστεθεί ένα νέο σχόλιο. |
| creationTime | java.util.Date | Χρόνος δημιουργίας του σχολίου. |

**Επιστρέφει:**
[IComment](../../com.aspose.slides/icomment) - Εισαχθεί το σχόλιο.

### insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

Εισάγει νέο σύγχρονο σχόλιο σε μια συλλογή στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης του στοιχείου σε μια συλλογή όπου θα πρέπει να εισαχθεί το σύγχρονο σχόλιο. |
| text | java.lang.String | Απλό κείμενο ενός νέου σύγχρονου σχολίου. |
| slide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια σε μια παρουσίαση όπου θα προστεθεί ένα νέο σύγχρονο σχόλιο. |
| shape | [IShape](../../com.aspose.slides/ishape) | Σχήμα σε μια διαφάνεια στο οποίο συσχετίζεται το νέο σύγχρονο σχόλιο. |
| position | java.awt.geom.Point2D.Float | Θέση σε μια διαφάνεια όπου θα προστεθεί ένα νέο σύγχρονο σχόλιο. |
| creationTime | java.util.Date | Χρόνος δημιουργίας του σύγχρονου σχολίου. |

**Επιστρέφει:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Εισαχθεί το σύγχρονο σχόλιο.

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
| count | int | Αριθμός σχολίων προς επιστροφή. |

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
| index | int | Ο μηδενικός δείκτης του στοιχείου που θα αφαιρεθεί. |

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

Επιστρέφει έναν απαριθμητή που επαναλαμβάνει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για επανάληψη της συλλογής.

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
| idx | int | Μοναδικός δείκτης ενός σχολίου για εύρεση  int . |

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
| array | com.aspose.ms.System.Array | Πίνακας προορισμού. |
| index | int | Αρχικός δείκτης στον πίνακα προορισμού. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Επιστρέφει μια τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Μόνο για ανάγνωση  boolean .

**Επιστρέφει:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Επιστρέφει μια ρίζα συγχρονισμού. Μόνο για ανάγνωση  Object .

**Επιστρέφει:**
java.lang.Object