---
title: BehaviorCollection
second_title: Αναφορά API Aspose.Slides για Java
description: Αντιπροσωπεύει μια συλλογή από αποτελέσματα συμπεριφοράς.
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

Αντιπροσωπεύει μια συλλογή αποτελεσμάτων συμπεριφοράς.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getCount()](#getCount--) | Επιστρέφει τον αριθμό των συμπεριφορών σε μια συλλογή. |
| [isReadOnly()](#isReadOnly--) | Λαμβάνει μια τιμή που δείχνει αν το [IGenericCollection](../../com.aspose.slides/igenericcollection) είναι μόνο για ανάγνωση. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Προσθέτει νέα συμπεριφορά σε μια συλλογή. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Καθορίζει το δείκτη ενός συγκεκριμένου στοιχείου στη Λίστα. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Εισάγει νέα συμπεριφορά σε μια συλλογή στον καθορισμένο δείκτη. |
| [copyTo(IBehavior[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehavior---int-) | Αντιγράφει τα στοιχεία του [IGenericCollection](../../com.aspose.slides/igenericcollection) σε ένα Array, ξεκινώντας από έναν συγκεκριμένο δείκτη Array. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Αφαιρεί την καθορισμένη συμπεριφορά από μια συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί τη συμπεριφορά από μια συλλογή στον καθορισμένο δείκτη. |
| [clear()](#clear--) | Αφαιρεί όλες τις συμπεριφορές από μια συλλογή. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Καθορίζει αν το [IGenericCollection](../../com.aspose.slides/igenericcollection) περιέχει μια συγκεκριμένη τιμή. |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει μια συμπεριφορά στον καθορισμένο δείκτη. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Ορίζει μια συμπεριφορά στον καθορισμένο δείκτη. |
| [iterator()](#iterator--) | Επιστρέφει έναν επαναλήπτη (enumerator) που διασχίζει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java επαναληπτικό (iterator) για ολόκληρη τη συλλογή. |

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

Λαμβάνει μια τιμή που υποδεικνύει αν το [IGenericCollection](../../com.aspose.slides/igenericcollection) είναι μόνο για ανάγνωση. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean - true αν το [IGenericCollection](../../com.aspose.slides/igenericcollection) είναι μόνο για ανάγνωση· διαφορετικά, false.

### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public final void add(IBehavior item)
```

Προσθέτει νέα συμπεριφορά σε μια συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Συμπεριφορά προς προσθήκη. |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public final int indexOf(IBehavior item)
```

Καθορίζει το δείκτη ενός συγκεκριμένου στοιχείου στη Λίστα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Το αντικείμενο προς εντοπισμό στη Λίστα. |

**Επιστρέφει:**
int - Το δείκτη του στοιχείου εάν βρεθεί στη λίστα· διαφορετικά, -1.

### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public final void insert(int index, IBehavior item)
```

Εισάγει νέα συμπεριφορά σε μια συλλογή στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης όπου πρέπει να εισαχθεί η νέα συμπεριφορά. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Συμπεριφορά προς εισαγωγή. |

### copyTo(IBehavior[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehavior---int-}
```
public final void copyTo(IBehavior[] array, int arrayIndex)
```

Αντιγράφει τα στοιχεία του [IGenericCollection](../../com.aspose.slides/igenericcollection) σε ένα Array, ξεκινώντας από έναν συγκεκριμένο δείκτη Array.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | [IBehavior\[\]](../../com.aspose.slides/ibehavior) | Ο μονοδιάστατος Array που είναι ο προορισμός των στοιχείων που αντιγράφονται από το [IGenericCollection](../../com.aspose.slides/igenericcollection). Ο Array πρέπει να έχει μηδενική αρίθμηση. |
| arrayIndex | int | Ο μηδενικός δείκτης στο array από τον οποίο αρχίζει η αντιγραφή. |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public final boolean remove(IBehavior item)
```

Αφαιρεί την καθορισμένη συμπεριφορά από μια συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Συμπεριφορά προς αφαίρεση. |

**Επιστρέφει:**
boolean

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Αφαιρεί τη συμπεριφορά από μια συλλογή στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης μιας συμπεριφοράς προς αφαίρεση. |

### clear() {#clear--}
```
public final void clear()
```

Αφαιρεί όλες τις συμπεριφορές από μια συλλογή.

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public final boolean contains(IBehavior item)
```

Καθορίζει αν το [IGenericCollection](../../com.aspose.slides/igenericcollection) περιέχει μια συγκεκριμένη τιμή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Το αντικείμενο προς εντοπισμό στο [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Επιστρέφει:**
boolean - true αν το στοιχείο βρέθηκε στο [IGenericCollection](../../com.aspose.slides/igenericcollection)· διαφορετικά, false.

### get_Item(int index) {#get-Item-int-}
```
public final IBehavior get_Item(int index)
```

Επιστρέφει μια συμπεριφορά στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης μιας συμπεριφοράς για επιστροφή. |

**Επιστρέφει:**
[IBehavior](../../com.aspose.slides/ibehavior) - Συμπεριφορά κίνησης.

### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public final void set_Item(int index, IBehavior value)
```

Ορίζει μια συμπεριφορά στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης μιας συμπεριφοράς για επιστροφή. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iterator()
```

Επιστρέφει έναν επαναλήπτη (enumerator) που διασχίζει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για να διασχίσει τη συλλογή.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iteratorJava()
```

Επιστρέφει έναν java επαναληπτικό (iterator) για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - Ένας java.util.Iterator για ολόκληρη τη συλλογή.