---
title: IPortionCollection
second_title: Aspose.Slides για Android μέσω Αναφοράς API Java
description: Αναπαριστά μια συλλογή τμημάτων.
type: docs
url: /el/com.aspose.slides/iportioncollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPortionCollection extends System.Collections.Generic.IGenericEnumerable<IPortion>
```

Αναπαριστά μια συλλογή τμημάτων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει το στοιχείο στον καθορισμένο δείκτη. |
| [getCount()](#getCount--) | Λαμβάνει τον αριθμό των στοιχείων που περιέχονται πραγματικά στη συλλογή. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Προσθέτει ένα Portion στο τέλος της συλλογής. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Καθορίζει τον δείκτη ενός συγκεκριμένου τμήματος στη συλλογή. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Εισάγει ένα Portion στη συλλογή στον καθορισμένο δείκτη. |
| [clear()](#clear--) | Αφαιρεί όλα τα στοιχεία από τη συλλογή. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | Καθορίζει εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) περιέχει μια συγκεκριμένη τιμή. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από το [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το στοιχείο στον καθορισμένο δείκτη της συλλογής. |
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

Λαμβάνει τον αριθμό των στοιχείων που περιέχονται πραγματικά στη συλλογή. Μόνο για ανάγνωση int.

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

Καθορίζει τον δείκτη ενός συγκεκριμένου τμήματος στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Το τμήμα που πρέπει να εντοπιστεί στη συλλογή. |

**Επιστρέφει:**
int - Ο δείκτης του στοιχείου αν βρεθεί στη συλλογή· διαφορετικά, -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public abstract void insert(int index, IPortion value)
```

Εισάγει ένα Portion στη συλλογή στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικά βασισμένος δείκτης στον οποίο το Portion πρέπει να εισαχθεί. |
| value | [IPortion](../../com.aspose.slides/iportion) | Το Portion προς εισαγωγή. |

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
| item | [IPortion](../../com.aspose.slides/iportion) | Το αντικείμενο που πρέπει να αφαιρεθεί από το [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Επιστρέφει:**
boolean - true εάν το αντικείμενο αφαιρεθεί επιτυχώς από το [IGenericCollection](../../com.aspose.slides/igenericcollection)· διαφορετικά, false. Αυτή η μέθοδος επίσης επιστρέφει false εάν το αντικείμενο δεν βρεθεί στην αρχική [IGenericCollection](../../com.aspose.slides/igenericcollection).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Αφαιρεί το στοιχείο στον καθορισμένο δείκτη της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικά βασισμένος δείκτης του στοιχείου που θα αφαιρεθεί. |