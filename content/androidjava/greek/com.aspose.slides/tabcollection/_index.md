---
title: TabCollection
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αναπαριστά μια συλλογή καρτελών.
type: docs
url: /el/com.aspose.slides/tabcollection/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.ITabCollection](../../com.aspose.slides/itabcollection), com.aspose.slides.IDOMObject
```
public final class TabCollection implements ITabCollection, IDOMObject
```

Αντιπροσωπεύει μια συλλογή καρτελών.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [size()](#size--) | Επιστρέφει τον αριθμό των στοιχείων που περιέχονται πραγματικά στη συλλογή. |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει το στοιχείο στον καθορισμένο δείκτη. |
| [add(double position, int align)](#add-double-int-) | Προσθέτει μια Καρτέλα στη συλλογή. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Προσθέτει μια Καρτέλα στη συλλογή. |
| [clear()](#clear--) | Αφαιρεί όλα τα στοιχεία από τη συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το στοιχείο στον καθορισμένο δείκτη της συλλογής. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει αν δύο παρουσίες του TabsEx είναι ίσες. |
| [iterator()](#iterator--) | Επιστρέφει έναν επαναλήπτη που διασχίζει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει όλα τα στοιχεία από τη συλλογή στον καθορισμένο πίνακα. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει μια τιμή που υποδεικνύει αν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει μια ρίζα συγχρονισμού. |
### size() {#size--}
```
public final int size()
```

Επιστρέφει τον αριθμό των στοιχείων που περιέχονται πραγματικά στη συλλογή. Μόνο για ανάγνωση int.

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ITab get_Item(int index)
```

Επιστρέφει το στοιχείο στον καθορισμένο δείκτη. Μόνο για ανάγνωση [Tab](../../com.aspose.slides/tab).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public final ITab add(double position, int align)
```

Προσθέτει μια Καρτέλα στη συλλογή.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | double |  |
| align | int |  |

**Returns:**
[ITab](../../com.aspose.slides/itab) - Προστιθέμενη καρτέλα.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public final int add(ITab value)
```

Προσθέτει μια Καρτέλα στη συλλογή.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | Το αντικείμενο Tab που προστίθεται στο τέλος της συλλογής. |

**Returns:**
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης του στοιχείου που θα αφαιρεθεί. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο για ανάγνωση IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Καθορίζει αν δύο παρουσίες του TabsEx είναι ίσες.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Το TabsEx προς σύγκριση με το τρέχον TabsEx. |

**Returns:**
boolean - **true** εάν το καθορισμένο TabsEx είναι ίσο με το τρέχον TabsEx· διαφορετικά, **false**.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iterator()
```

Επιστρέφει έναν επαναλήπτη που διασχίζει τη συλλογή.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για την επανάληψη στη συλλογή.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iteratorJava()
```

Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - Ένας java.util.Iterator για ολόκληρη τη συλλογή.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Αντιγράφει όλα τα στοιχεία από τη συλλογή στον καθορισμένο πίνακα.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Πίνακας-στόχος. |
| index | int | Αρχικός δείκτης στον πίνακα-στόχο. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Επιστρέφει μια τιμή που υποδεικνύει αν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Μόνο για ανάγνωση boolean.

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Επιστρέφει μια ρίζα συγχρονισμού. Μόνο για ανάγνωση Object.

**Returns:**
java.lang.Object