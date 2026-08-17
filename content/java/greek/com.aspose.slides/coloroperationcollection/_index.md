---
title: ColorOperationCollection
second_title: Αναφορά API του Aspose.Slides για Java
description: Αναπαριστά μια συλλογή από λειτουργίες μετασχηματισμού χρώματος.
type: docs
url: /el/com.aspose.slides/coloroperationcollection/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διασυνδέσεις:**
[com.aspose.slides.IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
```
public final class ColorOperationCollection implements IColorOperationCollection
```

Αναπαριστά μια συλλογή από λειτουργίες μετασχηματισμού χρώματος.
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [size()](#size--) | Επιστρέφει τον αριθμό των λειτουργιών σε μια συλλογή. |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει ή ορίζει τη λειτουργία στο καθορισμένο δείκτη. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Επιστρέφει ή ορίζει τη λειτουργία στο καθορισμένο δείκτη. |
| [add(int operation, float parameter)](#add-int-float-) | Προσθέτει μια νέα λειτουργία στο τέλος της συλλογής. |
| [add(int operation)](#add-int-) | Προσθέτει μια νέα λειτουργία στο τέλος της συλλογής. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Εισάγει τη νέα λειτουργία σε μια συλλογή. |
| [insert(int position, int operation)](#insert-int-int-) | Εισάγει τη νέα λειτουργία σε μια συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί τη λειτουργία χρώματος από μια συλλογή. |
| [clear()](#clear--) | Αφαιρεί όλες τις λειτουργίες χρώματος. |
| [iterator()](#iterator--) | Επιστρέφει έναν επαναληπτικό που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει όλα τα στοιχεία από τη συλλογή στο καθορισμένο πίνακα. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει έναν ριζικό σημείο συγχρονισμού. |
| [deepClone()](#deepClone--) | Δημιουργεί ένα αντίγραφο μιας συλλογής ColorOperationCollection. |
| [cloneT()](#cloneT--) | Κλωνοποιεί το τρέχον αντικείμενο |
### size() {#size--}
```
public final int size()
```


Επιστρέφει τον αριθμό των λειτουργιών σε μια συλλογή. Μόνο-ανάγνωση int.

**Επιστρέφει:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IColorOperation get_Item(int index)
```


Επιστρέφει ή ορίζει τη λειτουργία στο καθορισμένο δείκτη. Ανάγνωση/εγγραφή [ColorOperation](../../com.aspose.slides/coloroperation).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IColorOperation](../../com.aspose.slides/icoloroperation)
### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public final void set_Item(int index, IColorOperation value)
```


Επιστρέφει ή ορίζει τη λειτουργία στο καθορισμένο δείκτη. Ανάγνωση/εγγραφή [ColorOperation](../../com.aspose.slides/coloroperation).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public final IColorOperation add(int operation, float parameter)
```


Προσθέτει μια νέα λειτουργία στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| operation | int | Τύπος λειτουργίας. |
| parameter | float | Παράμετρος λειτουργίας. |

**Επιστρέφει:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Προστιθέμενη λειτουργία.
### add(int operation) {#add-int-}
```
public final IColorOperation add(int operation)
```


Προσθέτει μια νέα λειτουργία στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| operation | int | Τύπος λειτουργίας. |

**Επιστρέφει:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Προστιθέμενη λειτουργία.
### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public final IColorOperation insert(int position, int operation, float parameter)
```


Εισάγει τη νέα λειτουργία σε μια συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | int | Ο δείκτης στον οποίο θα εισαχθεί η λειτουργία. |
| operation | int | Τύπος λειτουργίας. |
| parameter | float | Παράμετρος λειτουργίας. |

**Επιστρέφει:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Εισαχθείσα λειτουργία.
### insert(int position, int operation) {#insert-int-int-}
```
public final IColorOperation insert(int position, int operation)
```


Εισάγει τη νέα λειτουργία σε μια συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | int | Ο δείκτης στον οποίο θα εισαχθεί η λειτουργία. |
| operation | int | Τύπος λειτουργίας. |

**Επιστρέφει:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Εισαχθείσα λειτουργία.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Αφαιρεί τη λειτουργία χρώματος από μια συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης λειτουργίας χρώματος για αφαίρεση. |

### clear() {#clear--}
```
public final void clear()
```


Αφαιρεί όλες τις λειτουργίες χρώματος.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iterator()
```


Επιστρέφει έναν επαναληπτικό που διατρέχει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για διαπέραση της συλλογής.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iteratorJava()
```


Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - Ένας java.util.Iterator για ολόκληρη τη συλλογή.
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


Επιστρέφει τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Μόνο-ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Επιστρέφει έναν ριζικό σημείο συγχρονισμού. Μόνο-ανάγνωση Object.

**Επιστρέφει:**
java.lang.Object
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Δημιουργεί ένα αντίγραφο μιας συλλογής ColorOperationCollection.

**Επιστρέφει:**
java.lang.Object - Νέα [ColorOperationCollection](../../com.aspose.slides/coloroperationcollection) συλλογή.
### cloneT() {#cloneT--}
```
public final IColorOperationCollection cloneT()
```


Κλωνοποιεί το τρέχον αντικείμενο

**Επιστρέφει:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection) - Κλώνος