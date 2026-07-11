---
title: SequenceCollection
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Αναπαριστά τη συλλογή διαδραστικών ακολουθιών.
type: docs
url: /el/com.aspose.slides/sequencecollection/
---
**Κληρονομία:**
java.lang.Object

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.ISequenceCollection](../../com.aspose.slides/isequencecollection)
```
public class SequenceCollection implements ISequenceCollection
```

Αναπαριστά τη συλλογή διαδραστικών ακολουθιών.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getCount()](#getCount--) | Επιστρέφει τον αριθμό των στοιχείων σε μια συλλογή. Μη-επεξεργάσιμο int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | Προσθέτει νέα διαδραστική ακολουθία. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | Αφαιρεί την καθορισμένη ακολουθία από μια συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί την ακολουθία στον καθορισμένο δείκτη. |
| [clear()](#clear--) | Αφαιρεί όλες τις ακολουθίες από μια συλλογή. |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει μια ακολουθία στον καθορισμένο δείκτη. |
| [iterator()](#iterator--) | Επιστρέφει έναν απαριθμητή που διασχίζει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
### getCount() {#getCount--}
```
public final int getCount()
```


Επιστρέφει τον αριθμό των στοιχείων σε μια συλλογή. Μη-επεξεργάσιμο int.

**Επιστρέφει:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public final ISequence add(IShape shapeTrigger)
```


Προσθέτει νέα διαδραστική ακολουθία. Ανάγνωση/εγγραφή [Sequence](../../com.aspose.slides/sequence).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) |  |

**Επιστρέφει:**
[ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public final void remove(ISequence item)
```


Αφαιρεί την καθορισμένη ακολουθία από μια συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | Ακολουθία προς αφαίρεση. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Αφαιρεί την ακολουθία στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης της ακολουθίας που πρέπει να διαγραφεί. |

### clear() {#clear--}
```
public final void clear()
```


Αφαιρεί όλες τις ακολουθίες από μια συλλογή.

### get_Item(int index) {#get-Item-int-}
```
public final ISequence get_Item(int index)
```


Επιστρέφει μια ακολουθία στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης του στοιχείου. |

**Επιστρέφει:**
[ISequence](../../com.aspose.slides/isequence) - Το [ISequence](../../com.aspose.slides/isequence) αντικείμενο.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iterator()
```


Επιστρέφει έναν απαριθμητή που διασχίζει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - Ένα IGenericEnumerator που μπορεί να χρησιμοποιηθεί για να διασχίσει τη συλλογή.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iteratorJava()
```


Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - Ένα java.util.Iterator για ολόκληρη τη συλλογή.