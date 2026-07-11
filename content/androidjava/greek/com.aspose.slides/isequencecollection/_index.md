---
title: ISequenceCollection
second_title: Aspose.Slides για Android μέσω Αναφοράς API Java
description: Αναπαριστά τη συλλογή των διαδραστικών ακολουθιών.
type: docs
url: /el/com.aspose.slides/isequencecollection/
---
**Όλες οι υλοποιημένες διεπαφές:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequenceCollection extends System.Collections.Generic.IGenericEnumerable<ISequence>
```

Αντιπροσωπεύει τη συλλογή των διαδραστικών ακολουθιών.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getCount()](#getCount--) | Επιστρέφει τον αριθμό των στοιχείων σε μια συλλογή Μόνο για ανάγνωση int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | Προσθέτει νέα διαδραστική ακολουθία. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | Αφαιρεί την καθορισμένη ακολουθία από μια συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί την ακολουθία στον καθορισμένο δείκτη. |
| [clear()](#clear--) | Αφαιρεί όλες τις ακολουθίες από μια συλλογή. |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει μια ακολουθία στον καθορισμένο δείκτη. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

Επιστρέφει τον αριθμό των στοιχείων σε μια συλλογή Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public abstract ISequence add(IShape shapeTrigger)
```

Προσθέτει νέα διαδραστική ακολουθία.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) | Αντικείμενο σχήματος [IShape](../../com.aspose.slides/ishape) |

**Επιστρέφει:**
[ISequence](../../com.aspose.slides/isequence) - Νέα ακολουθία [ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public abstract void remove(ISequence item)
```

Αφαιρεί την καθορισμένη ακολουθία από μια συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | Ακολουθία προς αφαίρεση. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Αφαιρεί την ακολουθία στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης του στοιχείου στη συλλογή int |
### clear() {#clear--}
```
public abstract void clear()
```

Αφαιρεί όλες τις ακολουθίες από μια συλλογή.
### get_Item(int index) {#get-Item-int-}
```
public abstract ISequence get_Item(int index)
```

Επιστρέφει μια ακολουθία στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης του στοιχείου. |

**Επιστρέφει:**
[ISequence](../../com.aspose.slides/isequence) - Το αντικείμενο [ISequence](../../com.aspose.slides/isequence)