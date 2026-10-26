---
title: ILayoutSlideCollection
second_title: Αναφορά API του Aspose.Slides για Java
description: Αντιπροσωπεύει μια βασική κλάση για τη συλλογή των διαφανειών διάταξης.
type: docs
url: /el/com.aspose.slides/ilayoutslidecollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ILayoutSlideCollection extends IGenericCollection<ILayoutSlide>
```

Αντιπροσωπεύει μια βασική κλάση για τη συλλογή των διαφανειών διάταξης.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει τη διαφάνεια διάταξης με βάση το δείκτη. |
| [getByType(byte type)](#getByType-byte-) | Επιστρέφει την πρώτη διαφάνεια διάταξης του συγκεκριμένου τύπου. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Αφαιρεί μια διάταξη από τη συλλογή. |
| [removeUnused()](#removeUnused--) | Αφαιρεί αχρησιμοποίητες διαφάνειες διάταξης (διαφάνειες διάταξης των οποίων το HasDependingSlides είναι ψευδές). |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILayoutSlide get_Item(int index)
```

Επιστρέφει τη διαφάνεια διάταξης με βάση το δείκτη. Μόνο για ανάγνωση [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public abstract ILayoutSlide getByType(byte type)
```

Επιστρέφει την πρώτη διαφάνεια διάταξης του συγκεκριμένου τύπου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | byte | Ένα τύπο διαφάνειας διάταξης προς εύρεση. |

**Επιστρέφει:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [ILayoutSlide](../../com.aspose.slides/ilayoutslide) με τον συγκεκριμένο τύπο ή null εάν δεν βρέθηκαν διαφάνειες.

### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public abstract void remove(ILayoutSlide value)
```

Αφαιρεί μια διάταξη από τη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Η διαφάνεια διάταξης προς αφαίρεση από τη συλλογή.

--------------------

1) Για να αποφύγετε την εξαίρεση PptxEditException, ελέγξτε πρώτα την ιδιότητα HasDependingSlides της διάταξης. 2) Μπορείτε επίσης να χρησιμοποιήσετε τη μέθοδο [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) για να απλοποιήσετε τον κώδικα. |

### removeUnused() {#removeUnused--}
```
public abstract void removeUnused()
```

Αφαιρεί αχρησιμοποίητες διαφάνειες διάταξης (διαφάνειες διάταξης των οποίων το HasDependingSlides είναι ψευδές).