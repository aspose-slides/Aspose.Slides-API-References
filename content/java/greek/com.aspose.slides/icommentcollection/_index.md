---
title: ICommentCollection
second_title: Αναφορά API Aspose.Slides για Java
description: Αντιπροσωπεύει μια συλλογή σχολίων ενός συγγραφέα.
type: docs
url: /el/com.aspose.slides/icommentcollection/
---
**Όλες οι Υλοποιημένες Διασυνδέσεις:**
com.aspose.slides.IGenericCollection
```
public interface ICommentCollection extends IGenericCollection<IComment>
```

Αντιπροσωπεύει μια συλλογή σχολίων ενός συγγραφέα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει το στοιχείο στον καθορισμένο δείκτη. |
| [addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Προσθέτει νέο σχόλιο στο τέλος μιας συλλογής. |
| [addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Προσθέτει νέο σύγχρονο σχόλιο στο τέλος μιας συλλογής. |
| [insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Εισάγει νέο σχόλιο σε μια συλλογή στον καθορισμένο δείκτη. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Εισάγει νέο σύγχρονο σχόλιο σε μια συλλογή στον καθορισμένο δείκτη. |
| [toArray()](#toArray--) | Δημιουργεί και επιστρέφει έναν πίνακα με όλα τα σχόλια. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Δημιουργεί και επιστρέφει έναν πίνακα με όλα τα σχόλια από το καθορισμένο εύρος. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το στοιχείο στον καθορισμένο δείκτη σε μια συλλογή. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Αφαιρεί την πρώτη εμφάνιση του καθορισμένου σχολίου σε μια συλλογή. |
| [clear()](#clear--) | Αφαιρεί όλα τα σχόλια από μια συλλογή. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IComment get_Item(int index)
```


Λαμβάνει το στοιχείο στον καθορισμένο δείκτη. Μόνο για ανάγνωση [IComment](../../com.aspose.slides/icomment).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, Point2D.Float position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IComment addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)
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
[IComment](../../com.aspose.slides/icomment) - Πρόσθετο σχόλιο.
### addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IModernComment addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
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
| shape | [IShape](../../com.aspose.slides/ishape) | Σχήμα σε μια διαφάνεια στο οποίο σχετίζεται το νέο σύγχρονο σχόλιο. |
| position | java.awt.geom.Point2D.Float | Θέση σε μια διαφάνεια όπου θα προστεθεί ένα νέο σύγχρονο σχόλιο. |
| creationTime | java.util.Date | Χρόνος δημιουργίας του σύγχρονου σχολίου. |

**Επιστρέφει:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Πρόσθετο σύγχρονο σχόλιο.
### insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IComment insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)
```


Εισάγει νέο σχόλιο σε μια συλλογή στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης του στοιχείου στη συλλογή όπου θα εισαχθεί το σχόλιο. |
| text | java.lang.String | Απλό κείμενο ενός νέου σχολίου. |
| slide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια σε μια παρουσίαση όπου θα προστεθεί ένα νέο σχόλιο. |
| position | java.awt.geom.Point2D.Float | Θέση σε μια διαφάνεια όπου θα προστεθεί ένα νέο σχόλιο. |
| creationTime | java.util.Date | Χρόνος δημιουργίας του σχολίου. |

**Επιστρέφει:**
[IComment](../../com.aspose.slides/icomment) - Εισαχθέν σχόλιο.
### insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```


Εισάγει νέο σύγχρονο σχόλιο σε μια συλλογή στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης του στοιχείου στη συλλογή όπου θα εισαχθεί το σύγχρονο σχόλιο. |
| text | java.lang.String | Απλό κείμενο ενός νέου σύγχρονου σχολίου. |
| slide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια σε μια παρουσίαση όπου θα προστεθεί ένα νέο σύγχρονο σχόλιο. |
| shape | [IShape](../../com.aspose.slides/ishape) | Σχήμα σε μια διαφάνεια στο οποίο σχετίζεται το νέο σύγχρονο σχόλιο. |
| position | java.awt.geom.Point2D.Float | Θέση σε μια διαφάνεια όπου θα προστεθεί ένα νέο σύγχρονο σχόλιο. |
| creationTime | java.util.Date | Χρόνος δημιουργίας του σύγχρονου σχολίου. |

**Επιστρέφει:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Εισαχθέν σύγχρονο σχόλιο.
### toArray() {#toArray--}
```
public abstract IComment[] toArray()
```


Δημιουργεί και επιστρέφει έναν πίνακα με όλα τα σχόλια.

**Επιστρέφει:**
com.aspose.slides.IComment[] - Πίνακας των [IComment](../../com.aspose.slides/icomment).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IComment[] toArray(int startIndex, int count)
```


Δημιουργεί και επιστρέφει έναν πίνακα με όλα τα σχόλια από το καθορισμένο εύρος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| startIndex | int | Δείκτης του πρώτου σχολίου προς επιστροφή. |
| count | int | Αριθμός σχολίων προς επιστροφή. |

**Επιστρέφει:**
com.aspose.slides.IComment[] - Πίνακας των [IComment](../../com.aspose.slides/icomment).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Αφαιρεί το στοιχείο στον καθορισμένο δείκτη σε μια συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης του στοιχείου προς αφαίρεση. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public abstract void remove(IComment comment)
```


Αφαιρεί την πρώτη εμφάνιση του καθορισμένου σχολίου σε μια συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | Το σχόλιο προς αφαίρεση από τη συλλογή. |

### clear() {#clear--}
```
public abstract void clear()
```


Αφαιρεί όλα τα σχόλια από μια συλλογή.