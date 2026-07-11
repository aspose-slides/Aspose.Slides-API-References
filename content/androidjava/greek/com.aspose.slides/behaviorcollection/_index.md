---
title: BehaviorCollection
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αναπαριστά μια συλλογή από εφέ συμπεριφοράς.
type: docs
url: /el/com.aspose.slides/behaviorcollection/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
```
public class BehaviorCollection implements IBehaviorCollection
```

Αναπαριστά μια συλλογή από εφέ συμπεριφοράς.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getCount()](#getCount--) | Επιστρέφει τον αριθμό των συμπεριφορών σε μια συλλογή. |
| [isReadOnly()](#isReadOnly--) | Λαμβάνει μια τιμή που υποδεικνύει εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) είναι μόνο για ανάγνωση. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Προσθέτει νέα συμπεριφορά σε μια συλλογή. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Προσδιορίζει το ευρετήριο ενός συγκεκριμένου στοιχείου στη λίστα. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Ενθέτει νέα συμπεριφορά σε μια συλλογή στο καθορισμένο ευρετήριο. |
| [copyTo(IBehavior[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehavior---int-) | Αντιγράφει τα στοιχεία του [IGenericCollection](../../com.aspose.slides/igenericcollection) σε έναν πίνακα, ξεκινώντας από ένα συγκεκριμένο ευρετήριο πίνακα. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Αφαιρεί την καθορισμένη συμπεριφορά από μια συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί τη συμπεριφορά από μια συλλογή στο καθορισμένο ευρετήριο. |
| [clear()](#clear--) | Αφαιρεί όλες τις συμπεριφορές από μια συλλογή. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Προσδιορίζει εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) περιέχει μια συγκεκριμένη τιμή. |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει μια συμπεριφορά στο καθορισμένο ευρετήριο. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Ορίζει μια συμπεριφορά στο καθορισμένο ευρετήριο. |
| [iterator()](#iterator--) | Επιστρέφει έναν απαριθμητή που διασχίζει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
### getCount() {#getCount--}
```
public final int getCount()
```


Επιστρέφει τον αριθμό των συμπεριφορών σε μια συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) είναι μόνο για ανάγνωση. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean - true εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) είναι μόνο για ανάγνωση· αλλιώς, false.
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public final void add(IBehavior item)
```


Προσθέτει νέα συμπεριφορά σε μια συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Η συμπεριφορά προς προσθήκη. |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public final int indexOf(IBehavior item)
```


Προσδιορίζει το ευρετήριο ενός συγκεκριμένου στοιχείου στη λίστα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Το αντικείμενο προς εντοπισμό στη λίστα. |

**Επιστρέφει:**
int - Το ευρετήριο του στοιχείου εάν βρεθεί στη λίστα· αλλιώς, -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public final void insert(int index, IBehavior item)
```


Ενθέτει νέα συμπεριφορά σε μια συλλογή στο καθορισμένο ευρετήριο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ευρετήριο όπου θα ενταχθεί η νέα συμπεριφορά. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Η συμπεριφορά προς ένθεση. |

### copyTo(IBehavior[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehavior---int-}
```
public final void copyTo(IBehavior[] array, int arrayIndex)
```


Αντιγράφει τα στοιχεία του [IGenericCollection](../../com.aspose.slides/igenericcollection) σε έναν πίνακα, ξεκινώντας από ένα συγκεκριμένο ευρετήριο πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | [IBehavior\[\]](../../com.aspose.slides/ibehavior) | Ο μονοδιάστατος πίνακας που είναι ο προορισμός των αντιγραμμένων στοιχείων από το [IGenericCollection](../../com.aspose.slides/igenericcollection). Ο πίνακας πρέπει να είναι με μηδενική βάση δεικτών. |
| arrayIndex | int | Το μηδενικό ευρετήριο στο array στο οποίο αρχίζει η αντιγραφή. |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public final boolean remove(IBehavior item)
```


Αφαιρεί την καθορισμένη συμπεριφορά από μια συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Η συμπεριφορά προς αφαίρεση. |

**Επιστρέφει:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Αφαιρεί τη συμπεριφορά από μια συλλογή στο καθορισμένο ευρετήριο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ευρετήριο μιας συμπεριφοράς προς αφαίρεση. |

### clear() {#clear--}
```
public final void clear()
```


Αφαιρεί όλες τις συμπεριφορές από μια συλλογή.

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public final boolean contains(IBehavior item)
```


Προσδιορίζει εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) περιέχει μια συγκεκριμένη τιμή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Το αντικείμενο προς εντοπισμό στο [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Επιστρέφει:**
boolean - true εάν το στοιχείο βρεθεί στο [IGenericCollection](../../com.aspose.slides/igenericcollection)· αλλιώς, false.
### get_Item(int index) {#get-Item-int-}
```
public final IBehavior get_Item(int index)
```


Επιστρέφει μια συμπεριφορά στο καθορισμένο ευρετήριο.

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ευρετήριο μιας συμπεριφοράς προς επιστροφή. |

**Επιστρέφει:**
[IBehavior](../../com.aspose.slides/ibehavior) - Συμπεριφορά animation.
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public final void set_Item(int index, IBehavior value)
```


Ορίζει μια συμπεριφορά στο καθορισμένο ευρετήριο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ευρετήριο μιας συμπεριφοράς προς επιστροφή. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iterator()
```


Επιστρέφει έναν απαριθμητή που διασχίζει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για την επανάληψη της συλλογής.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iteratorJava()
```


Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - Ένας java.util.Iterator για ολόκληρη τη συλλογή.