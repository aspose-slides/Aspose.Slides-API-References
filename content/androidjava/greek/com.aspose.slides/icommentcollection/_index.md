---
title: ICommentCollection
second_title: Aspose.Slides για Android μέσω Java API
description: Αναπαριστά μια συλλογή σχολίων ενός συγγραφέα.
type: docs
url: /el/com.aspose.slides/icommentcollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ICommentCollection extends IGenericCollection<IComment>
```

Αναπαριστά μια συλλογή σχολίων ενός συγγραφέα.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Παίρνει το στοιχείο στο συγκεκριμένο δείκτη. |
| [addComment(String text, ISlide slide, PointF position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Προσθέτει νέο σχόλιο στο τέλος μιας συλλογής. |
| [addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Προσθέτει νέο μοντέρνο σχόλιο στο τέλος μιας συλλογής. |
| [insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Εισάγει νέο σχόλιο σε μια συλλογή στο συγκεκριμένο δείκτη. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Εισάγει νέο μοντέρνο σχόλιο σε μια συλλογή στο συγκεκριμένο δείκτη. |
| [toArray()](#toArray--) | Δημιουργεί και επιστρέφει έναν πίνακα με όλα τα σχόλια. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Δημιουργεί και επιστρέφει έναν πίνακα με όλα τα σχόλια από το συγκεκριμένο εύρος. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το στοιχείο στο συγκεκριμένο δείκτη σε μια συλλογή. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Αφαιρεί την πρώτη εμφάνιση του συγκεκριμένου σχολίου σε μια συλλογή. |
| [clear()](#clear--) | Αφαιρεί όλα τα σχόλια από μια συλλογή. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IComment get_Item(int index)
```


Παίρνει το στοιχείο στο συγκεκριμένο δείκτη. Μόνο-ανάγνωση [IComment](../../com.aspose.slides/icomment).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, PointF position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public abstract IComment addComment(String text, ISlide slide, PointF position, Date creationTime)
```


Προσθέτει νέο σχόλιο στο τέλος μιας συλλογής.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Απλό κείμενο ενός νέου σχολίου. |
| slide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια σε μια παρουσίαση όπου θα προστεθεί ένα νέο σχόλιο. |
| position | android.graphics.PointF | Θέση σε μια διαφάνεια όπου θα προστεθεί ένα νέο σχόλιο. |
| creationTime | java.util.Date | Ώρα δημιουργίας του σχολίου. |

**Returns:**
[IComment](../../com.aspose.slides/icomment) - Προστέθηκε σχόλιο.
### addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public abstract IModernComment addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Απλό κείμενο ενός νέου μοντέρνου σχολίου. |
| slide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια σε μια παρουσίαση όπου θα προστεθεί ένα νέο μοντέρνο σχόλιο. |
| shape | [IShape](../../com.aspose.slides/ishape) | Σχήμα σε μια διαφάνεια στο οποίο συνδέεται ένα νέο μοντέρνο σχόλιο. |
| position | android.graphics.PointF | Θέση σε μια διαφάνεια όπου θα προστεθεί ένα νέο μοντέρνο σχόλιο. |
| creationTime | java.util.Date | Ώρα δημιουργίας του μοντέρνου σχολίου. |

**Returns:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Προστέθηκε μοντέρνο σχόλιο.
### insertComment(int index, String text, ISlide slide, PointF position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public abstract IComment insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)
```


Εισάγει νέο σχόλιο σε μια συλλογή στο συγκεκριμένο δείκτη.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Δείκτης του στοιχείου σε μια συλλογή όπου θα εισαχθεί το σχόλιο. |
| text | java.lang.String | Απλό κείμενο ενός νέου σχολίου. |
| slide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια σε μια παρουσίαση όπου θα προστεθεί ένα νέο σχόλιο. |
| position | android.graphics.PointF | Θέση σε μια διαφάνεια όπου θα προστεθεί ένα νέο σχόλιο. |
| creationTime | java.util.Date | Ώρα δημιουργίας του σχολίου. |

**Returns:**
[IComment](../../com.aspose.slides/icomment) - Το εισαχθέν σχόλιο.
### insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public abstract IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```


Εισάγει νέο μοντέρνο σχόλιο σε μια συλλογή στο συγκεκριμένο δείκτη.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Δείκτης του στοιχείου σε μια συλλογή όπου θα εισαχθεί το μοντέρνο σχόλιο. |
| text | java.lang.String | Απλό κείμενο ενός νέου μοντέρνου σχολίου. |
| slide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια σε μια παρουσίαση όπου θα προστεθεί ένα νέο μοντέρνο σχόλιο. |
| shape | [IShape](../../com.aspose.slides/ishape) | Σχήμα σε μια διαφάνεια στο οποίο συνδέεται ένα νέο μοντέρνο σχόλιο. |
| position | android.graphics.PointF | Θέση σε μια διαφάνεια όπου θα προστεθεί ένα νέο μοντέρνο σχόλιο. |
| creationTime | java.util.Date | Ώρα δημιουργίας του μοντέρνου σχολίου. |

**Returns:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Το εισαχθέν μοντέρνο σχόλιο.
### toArray() {#toArray--}
```
public abstract IComment[] toArray()
```


Δημιουργεί και επιστρέφει έναν πίνακα με όλα τα σχόλια.

**Returns:**
com.aspose.slides.IComment[] - Πίνακας των [IComment](../../com.aspose.slides/icomment).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IComment[] toArray(int startIndex, int count)
```


Δημιουργεί και επιστρέφει έναν πίνακα με όλα τα σχόλια από το συγκεκριμένο εύρος.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | Δείκτης του πρώτου σχολίου που θα επιστραφεί. |
| count | int | Αριθμός σχολίων που θα επιστραφούν. |

**Returns:**
com.aspose.slides.IComment[] - Πίνακας των [IComment](../../com.aspose.slides/icomment).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Αφαιρεί το στοιχείο στο συγκεκριμένο δείκτη σε μια συλλογή.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης του στοιχείου που θα αφαιρεθεί. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public abstract void remove(IComment comment)
```


Αφαιρεί την πρώτη εμφάνιση του συγκεκριμένου σχολίου σε μια συλλογή.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | Το σχόλιο που θα αφαιρεθεί από μια συλλογή. |

### clear() {#clear--}
```
public abstract void clear()
```


Αφαιρεί όλα τα σχόλια από μια συλλογή.