---
title: ILayoutSlideCollection
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αναπαριστά μια βασική κλάση για τη συλλογή διαφανειών διάταξης.
type: docs
url: /el/com.aspose.slides/ilayoutslidecollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.slides.IGenericCollection
```
public interface ILayoutSlideCollection extends IGenericCollection<ILayoutSlide>
```

Αναπαριστά μια βασική κλάση για τη συλλογή διαφανειών διάταξης.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει τη διαφάνεια διάταξης με το δείκτη. |
| [getByType(byte type)](#getByType-byte-) | Επιστρέφει την πρώτη διαφάνεια διάταξης του συγκεκριμένου τύπου. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Αφαιρεί μια διάταξη από τη συλλογή. |
| [removeUnused()](#removeUnused--) | Αφαιρεί αχρησιμοποίητες διαφάνειες διάταξης (διαφάνειες διάταξης των οποίων η ιδιότητα HasDependingSlides είναι ψευδής). |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILayoutSlide get_Item(int index)
```


Επιστρέφει τη διαφάνεια διάταξης με το δείκτη. Μόνο για ανάγνωση [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

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
| type | byte | Ένας τύπος διαφάνειας διάταξης προς εύρεση. |

**Επιστρέφει:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [ILayoutSlide](../../com.aspose.slides/ilayoutslide) με τον καθορισμένο τύπο ή null αν δεν βρεθούν διαφάνειες.

### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public abstract void remove(ILayoutSlide value)
```


Αφαιρεί μια διάταξη από τη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Η διαφάνεια διάταξης που θα αφαιρεθεί από τη συλλογή.

--------------------

1) Για να αποφύγετε την εξαίρεση PptxEditException, ελέγξτε την ιδιότητα HasDependingSlides της διάταξης πριν. 2) Μπορείτε επίσης να χρησιμοποιήσετε τη μέθοδο [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) για να απλοποιήσετε τον κώδικα. |
### removeUnused() {#removeUnused--}
```
public abstract void removeUnused()
```


Αφαιρεί αχρησιμοποίητες διαφάνειες διάταξης (διαφάνειες διάταξης των οποίων η ιδιότητα HasDependingSlides είναι ψευδής).