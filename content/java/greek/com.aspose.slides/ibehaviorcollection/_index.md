---
title: IBehaviorCollection
second_title: Aspose.Slides για την Αναφορά API της Java
description: Αντιπροσωπεύει τη συλλογή των εφέ συμπεριφοράς.
type: docs
url: /el/com.aspose.slides/ibehaviorcollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IBehaviorCollection extends System.Collections.Generic.IGenericEnumerable<IBehavior>
```

Αντιπροσωπεύει τη συλλογή των επιδράσεων συμπεριφοράς.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει μια συμπεριφορά στον καθορισμένο δείκτη. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Επιστρέφει μια συμπεριφορά στον καθορισμένο δείκτη. |
| [getCount()](#getCount--) | Επιστρέφει τον αριθμό των συμπεριφορών σε μια συλλογή. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Προσθέτει νέα συμπεριφορά σε μια συλλογή. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Καθορίζει τον δείκτη ενός συγκεκριμένου αντικειμένου στη List. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Εισάγει νέα συμπεριφορά σε μια συλλογή στον καθορισμένο δείκτη. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Αφαιρεί την καθορισμένη συμπεριφορά από μια συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί τη συμπεριφορά από μια συλλογή στον καθορισμένο δείκτη. |
| [clear()](#clear--) | Αφαιρεί όλες τις συμπεριφορές από μια συλλογή. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Καθορίζει εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) περιέχει μια συγκεκριμένη τιμή. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IBehavior get_Item(int index)
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
public abstract void set_Item(int index, IBehavior value)
```

Επιστρέφει μια συμπεριφορά στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης μιας συμπεριφοράς για επιστροφή. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### getCount() {#getCount--}
```
public abstract int getCount()
```

Επιστρέφει τον αριθμό των συμπεριφορών σε μια συλλογή. Μόνο ανάγνωση int.

**Επιστρέφει:**
int

### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public abstract void add(IBehavior item)
```

Προσθέτει νέα συμπεριφορά σε μια συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Συμπεριφορά για προσθήκη. |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public abstract int indexOf(IBehavior item)
```

Καθορίζει τον δείκτη ενός συγκεκριμένου αντικειμένου στη List.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Το αντικείμενο προς εντοπισμό στη List. |

**Επιστρέφει:**
int - Ο δείκτης του αντικειμένου εάν βρεθεί στη λίστα· διαφορετικά, -1.

### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public abstract void insert(int index, IBehavior item)
```

Εισάγει νέα συμπεριφορά σε μια συλλογή στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης όπου η νέα συμπεριφορά πρέπει να εισαχθεί. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Συμπεριφορά για εισαγωγή. |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public abstract boolean remove(IBehavior item)
```

Αφαιρεί την καθορισμένη συμπεριφορά από μια συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Συμπεριφορά για αφαίρεση. |

**Επιστρέφει:**
boolean - true εάν η συμπεριφορά αφαιρεθεί επιτυχώς.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Αφαιρεί τη συμπεριφορά από μια συλλογή στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης μιας συμπεριφοράς για αφαίρεση. |

### clear() {#clear--}
```
public abstract void clear()
```

Αφαιρεί όλες τις συμπεριφορές από μια συλλογή.

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public abstract boolean contains(IBehavior item)
```

Καθορίζει εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) περιέχει μια συγκεκριμένη τιμή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Το αντικείμενο προς εντοπισμό στο [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Επιστρέφει:**
boolean - true εάν το αντικείμενο βρεθεί στο [IGenericCollection](../../com.aspose.slides/igenericcollection)· διαφορετικά, false.