---
title: PortionCollection
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Αντιπροσωπεύει μια συλλογή από τμήματα.
type: docs
url: /el/com.aspose.slides/portioncollection/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IPortionCollection](../../com.aspose.slides/iportioncollection)
```
public final class PortionCollection extends DomObject<Paragraph> implements IPortionCollection
```

Αντιπροσωπεύει μια συλλογή από τμήματα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getCount()](#getCount--) | Λαμβάνει τον αριθμό των στοιχείων που περιέχονται πραγματικά στη συλλογή. |
| [isReadOnly()](#isReadOnly--) | Λαμβάνει μια τιμή που υποδεικνύει εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) είναι μόνο για ανάγνωση. |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει το στοιχείο στο καθορισμένο ευρετήριο. |
| [set_Item(int index, IPortion value)](#set-Item-int-com.aspose.slides.IPortion-) | Λαμβάνει το στοιχείο στο καθορισμένο ευρετήριο. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Προσθέτει ένα Portion στο τέλος της συλλογής. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Καθορίζει το ευρετήριο ενός συγκεκριμένου αντικειμένου στη λίστα. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Εισάγει ένα Portion στη συλλογή στο καθορισμένο ευρετήριο. |
| [clear()](#clear--) | Αφαιρεί όλα τα στοιχεία από τη συλλογή. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | Καθορίζει εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) περιέχει μια συγκεκριμένη τιμή. |
| [copyTo(IPortion[] array, int arrayIndex)](#copyTo-com.aspose.slides.IPortion---int-) | Αντιγράφει τα στοιχεία του [IGenericCollection](../../com.aspose.slides/igenericcollection) σε ένα Array, ξεκινώντας από ένα συγκεκριμένο ευρετήριο Array. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | Αφαιρέι την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από το [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το στοιχείο στο καθορισμένο ευρετήριο της συλλογής. |
| [iterator()](#iterator--) | Επιστρέφει έναν enumerator που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
### getCount() {#getCount--}
```
public final int getCount()
```


Λαμβάνει τον αριθμό των στοιχείων που περιέχονται πραγματικά στη συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) είναι μόνο για ανάγνωση. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean - true εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) είναι μόνο για ανάγνωση· διαφορετικά, false.
### get_Item(int index) {#get-Item-int-}
```
public final IPortion get_Item(int index)
```


Λαμβάνει το στοιχείο στο καθορισμένο ευρετήριο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IPortion](../../com.aspose.slides/iportion)
### set_Item(int index, IPortion value) {#set-Item-int-com.aspose.slides.IPortion-}
```
public final void set_Item(int index, IPortion value)
```


Λαμβάνει το στοιχείο στο καθορισμένο ευρετήριο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |
| value | [IPortion](../../com.aspose.slides/iportion) |  |

### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public final void add(IPortion value)
```


Προσθέτει ένα Portion στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | Το Portion που θα προστεθεί στο τέλος της συλλογής. |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public final int indexOf(IPortion item)
```


Καθορίζει το ευρετήριο ενός συγκεκριμένου αντικειμένου στη λίστα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Το αντικείμενο προς εντοπισμό στη λίστα. |

**Επιστρέφει:**
int - Το ευρετήριο του αντικειμένου εάν βρεθεί στη λίστα· διαφορετικά, -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public final void insert(int index, IPortion value)
```


Εισάγει ένα Portion στη συλλογή στο καθορισμένο ευρετήριο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός-βάση ευρετήριο στο οποίο πρέπει να εισαχθεί το Portion. |
| value | [IPortion](../../com.aspose.slides/iportion) | Το Portion προς εισαγωγή. |

### clear() {#clear--}
```
public final void clear()
```


Αφαιρεί όλα τα στοιχεία από τη συλλογή.

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public final boolean contains(IPortion item)
```


Καθορίζει εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) περιέχει μια συγκεκριμένη τιμή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Το αντικείμενο προς εντοπισμό στο [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Επιστρέφει:**
boolean - true εάν το αντικείμενο βρεθεί στο [IGenericCollection](../../com.aspose.slides/igenericcollection)· διαφορετικά, false.
### copyTo(IPortion[] array, int arrayIndex) {#copyTo-com.aspose.slides.IPortion---int-}
```
public final void copyTo(IPortion[] array, int arrayIndex)
```


Αντιγράφει τα στοιχεία του [IGenericCollection](../../com.aspose.slides/igenericcollection) σε ένα Array, ξεκινώντας από ένα συγκεκριμένο ευρετήριο Array.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | [IPortion\[\]](../../com.aspose.slides/iportion) | Ο μοδιάστατος Array που είναι προορισμός των στοιχείων που αντιγράφηκαν από το [IGenericCollection](../../com.aspose.slides/igenericcollection). Ο Array πρέπει να έχει μηδενική βάση ευρετηρίου. |
| arrayIndex | int | Ο μηδενικός-βάση ευρετήριο στο array από όπου ξεκινά η αντιγραφή. |

### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public final boolean remove(IPortion item)
```


Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από το [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Το αντικείμενο προς αφαίρεση από το [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Επιστρέφει:**
boolean - true εάν το αντικείμενο αφαιρεθεί επιτυχώς από το [IGenericCollection](../../com.aspose.slides/igenericcollection)· διαφορετικά, false. Αυτή η μέθοδος επίσης επιστρέφει false εάν το αντικείμενο δεν βρεθεί στο αρχικό [IGenericCollection](../../com.aspose.slides/igenericcollection).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Αφαιρεί το στοιχείο στο καθορισμένο ευρετήριο της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός-βάση ευρετήριο του στοιχείου που θα αφαιρεθεί. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iterator()
```


Επιστρέφει έναν enumerator που διατρέχει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - Ένα IGenericEnumerator που μπορεί να χρησιμοποιηθεί για την επανάληψη στη συλλογή.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iteratorJava()
```


Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - An java.util.Iterator for the entire collection.