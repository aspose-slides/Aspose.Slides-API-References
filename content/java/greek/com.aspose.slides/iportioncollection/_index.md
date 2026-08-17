---
title: IPortionCollection
second_title: Aspose.Slides για το Java API Αναφορά
description: Αναπαριστά μια συλλογή από τμήματα.
type: docs
url: /el/com.aspose.slides/iportioncollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPortionCollection extends System.Collections.Generic.IGenericEnumerable<IPortion>
```

Represents a collection of a portions.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [getCount()](#getCount--) | Gets the number of elements actually contained in the collection. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Adds a Portion to the end of collection. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Determines the index of a specific portion in collection. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Inserts a Portion into the collection at the specified index. |
| [clear()](#clear--) | Removes all elements from the collection. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | Determines whether the [IGenericCollection](../../com.aspose.slides/igenericcollection) contains a specific value. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | Removes the first occurrence of a specific object from the [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [removeAt(int index)](#removeAt-int-) | Removes the element at the specified index of the collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPortion get_Item(int index)
```


Λαμβάνει το στοιχείο στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IPortion](../../com.aspose.slides/iportion)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Λαμβάνει τον αριθμό των στοιχείων που περιέχονται στην συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public abstract void add(IPortion value)
```


Προσθέτει ένα Portion στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | Το Portion που θα προστεθεί στο τέλος της συλλογής. |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public abstract int indexOf(IPortion item)
```


Καθορίζει το δείκτη ενός συγκεκριμένου portion στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Το portion που πρέπει να εντοπιστεί στη συλλογή. |

**Επιστρέφει:**
int - Το δείκτη του αντικειμένου αν βρεθεί στη συλλογή· διαφορετικά, -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public abstract void insert(int index, IPortion value)
```


Εισάγει ένα Portion στη συλλογή στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης με μηδενική βάση όπου θα εισαχθεί το Portion. |
| value | [IPortion](../../com.aspose.slides/iportion) | Το Portion που θα εισαχθεί. |

### clear() {#clear--}
```
public abstract void clear()
```


Αφαιρεί όλα τα στοιχεία από τη συλλογή.

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public abstract boolean contains(IPortion item)
```


Καθορίζει εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) περιέχει μια συγκεκριμένη τιμή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Το αντικείμενο που πρέπει να εντοπιστεί στο [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Επιστρέφει:**
boolean - true εάν το αντικείμενο βρεθεί στο [IGenericCollection](../../com.aspose.slides/igenericcollection)· διαφορετικά, false.
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public abstract boolean remove(IPortion item)
```


Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από το [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Το αντικείμενο που θα αφαιρεθεί από το [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Επιστρέφει:**
boolean - true εάν το αντικείμενο αφαιρεθεί επιτυχώς από το [IGenericCollection](../../com.aspose.slides/igenericcollection)· διαφορετικά, false. Αυτή η μέθοδος επιστρέφει επίσης false εάν το αντικείμενο δεν βρεθεί στην αρχική [IGenericCollection](../../com.aspose.slides/igenericcollection).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Αφαιρεί το στοιχείο στον καθορισμένο δείκτη της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης με μηδενική βάση του στοιχείου που θα αφαιρεθεί. |