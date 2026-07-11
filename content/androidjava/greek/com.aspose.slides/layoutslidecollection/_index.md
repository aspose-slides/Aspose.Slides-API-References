---
title: LayoutSlideCollection
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αντιπροσωπεύει μια βασική κλάση για τη συλλογή διαφανειών διάταξης.
type: docs
url: /el/com.aspose.slides/layoutslidecollection/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection), com.aspose.slides.IDOMObject
```
public class LayoutSlideCollection implements ILayoutSlideCollection, IDOMObject
```

Αντιπροσωπεύει μία βασική κλάση για τη συλλογή διαφανειών διάταξης.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [size()](#size--) | Επιστρέφει τον αριθμό των διαφανειών διάταξης σε μια συλλογή. |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει τη διαφάνεια διάταξης με βάση το δείκτη. |
| [getByType(byte type)](#getByType-byte-) | Επιστρέφει την πρώτη διαφάνεια διάταξης του συγκεκριμένου τύπου. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Αφαιρεί μια διάταξη από τη συλλογή. |
| [removeUnused()](#removeUnused--) | Αφαιρεί αχρησιμοποίητες διαφάνειες διάταξης (διαφάνειες διάταξης των οποίων η ιδιότητα HasDependingSlides είναι ψευδής). |
| [iterator()](#iterator--) | Επιστρέφει έναν απαριθμητή που διασχίζει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει όλα τα στοιχεία από τη συλλογή στον καθορισμένο πίνακα. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει μια τιμή που υποδεικνύει αν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει τη ρίζα συγχρονισμού. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```


Επιστρέφει τον αριθμό των διαφανειών διάταξης σε μια συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ILayoutSlide get_Item(int index)
```


Επιστρέφει τη διαφάνεια διάταξης με βάση το δείκτη. Μόνο για ανάγνωση [LayoutSlide](../../com.aspose.slides/layoutslide).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public final ILayoutSlide getByType(byte type)
```


Επιστρέφει την πρώτη διαφάνεια διάταξης του συγκεκριμένου τύπου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | byte | Ένας τύπος διαφάνειας διάταξης για εύρεση. |

**Επιστρέφει:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [LayoutSlide](../../com.aspose.slides/layoutslide) με τον καθορισμένο τύπο ή null εάν δεν βρέθηκαν διαφάνειες.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public final void remove(ILayoutSlide value)
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
public final void removeUnused()
```


Αφαιρεί αχρησιμοποίητες διαφάνειες διάταξης (διαφάνειες διάταξης των οποίων η ιδιότητα HasDependingSlides είναι ψευδής).

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iterator()
```


Επιστρέφει έναν απαριθμητή που διασχίζει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για την επανάληψη στη συλλογή.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iteratorJava()
```


Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - Ένας java.util.Iterator για ολόκληρη τη συλλογή.
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


Επιστρέφει τη ρίζα συγχρονισμού. Μόνο για ανάγνωση Object.

**Επιστρέφει:**
java.lang.Object
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο για ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject