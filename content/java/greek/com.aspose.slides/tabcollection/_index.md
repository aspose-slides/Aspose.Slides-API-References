---
title: TabCollection
second_title: Aspose.Slides για την Αναφορά API της Java
description: Αναπαριστά μια συλλογή από καρτέλες.
type: docs
url: /el/com.aspose.slides/tabcollection/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ITabCollection](../../com.aspose.slides/itabcollection), com.aspose.slides.IDOMObject
```
public final class TabCollection implements ITabCollection, IDOMObject
```

Αναπαριστά μια συλλογή από καρτέλες.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [size()](#size--) | Ανακτά τον αριθμό των στοιχείων που περιέχονται στην πραγματική συλλογή. |
| [get_Item(int index)](#get-Item-int-) | Ανακτά το στοιχείο στον καθορισμένο δείκτη. |
| [add(double position, int align)](#add-double-int-) | Προσθέτει μια Καρτέλα στη συλλογή. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Προσθέτει μια Καρτέλα στη συλλογή. |
| [clear()](#clear--) | Αφαιρεί όλα τα στοιχεία από τη συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρέι το στοιχείο στον καθορισμένο δείκτη της συλλογής. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει αν δύο αντικείμενα TabsEx είναι ίσα. |
| [iterator()](#iterator--) | Επιστρέφει έναν απαριθμητή που διασχίζει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει όλα τα στοιχεία από τη συλλογή στον καθορισμένο πίνακα. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει τιμή που υποδεικνύει αν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει τη ρίζα συγχρονισμού. |
### size() {#size--}
```
public final int size()
```


Ανακτά τον αριθμό των στοιχείων που περιέχονται στην πραγματική συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ITab get_Item(int index)
```


Ανακτά το στοιχείο στον καθορισμένο δείκτη. Μόνο για ανάγνωση [Tab](../../com.aspose.slides/tab).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public final ITab add(double position, int align)
```


Προσθέτει μια Καρτέλα στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | double |  |
| align | int |  |

**Επιστρέφει:**
[ITab](../../com.aspose.slides/itab) - Προστέθηκε η καρτέλα.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public final int add(ITab value)
```


Προσθέτει μια Καρτέλα στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | Το αντικείμενο Tab που θα προστεθεί στο τέλος της συλλογής. |

**Επιστρέφει:**
int - Ο δείκτης στον οποίο προστέθηκε η καρτέλα.
### clear() {#clear--}
```
public final void clear()
```


Αφαιρεί όλα τα στοιχεία από τη συλλογή.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Αφαιρεί το στοιχείο στον καθορισμένο δείκτη της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης του στοιχείου προς αφαίρεση. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο για ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Καθορίζει αν δύο αντικείμενα TabsEx είναι ίσα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το TabsEx για σύγκριση με το τρέχον TabsEx. |

**Επιστρέφει:**
boolean - **true** εάν το συγκεκριμένο TabsEx είναι ίσο με το τρέχον TabsEx· διαφορετικά, **false**.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iterator()
```


Επιστρέφει έναν απαριθμητή που διασχίζει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για την επανάληψη στη συλλογή.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iteratorJava()
```


Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - Ένας java.util.Iterator για ολόκληρη τη συλλογή.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Αντιγράφει όλα τα στοιχεία από τη συλλογή στον καθορισμένο πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Ο πίνακας προορισμού. |
| index | int | Αρχικός δείκτης στον πίνακα προορισμού. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Επιστρέφει τιμή που υποδεικνύει αν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Επιστρέφει τη ρίζα συγχρονισμού. Μόνο για ανάγνωση Object.

**Επιστρέφει:**
java.lang.Object