---
title: ControlCollection
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Μια συλλογή ελεγκτών ActiveX.
type: docs
url: /el/com.aspose.slides/controlcollection/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IControlCollection](../../com.aspose.slides/icontrolcollection), com.aspose.slides.IDOMObject
```
public class ControlCollection implements IControlCollection, IDOMObject
```

Μια συλλογή ελεγκτών ActiveX.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [size()](#size--) | Επιστρέφει έναν αριθμό αντικειμένων στη συλλογή. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Δημιουργεί και προσθέτει ένα νέο έλεγχο στη συλλογή. |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Αφαιρεί έναν έλεγχο ActiveX από τη συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί έναν έλεγχο ActiveX που βρίσκεται στη συγκεκριμένη θέση από τη συλλογή. |
| [clear()](#clear--) | Αφαιρεί όλους τους ελέγχους από τη συλλογή. |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει έναν έλεγχο στη συγκεκριμένη θέση. |
| [iterator()](#iterator--) | Επιστρέφει έναν αριθμητή που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει ολόκληρη τη συλλογή στον καθορισμένο πίνακα. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει μια τιμή που υποδεικνύει αν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει ένα στοιχείο ρίζας συγχρονισμού. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### size() {#size--}
```
public final int size()
```

Επιστρέφει έναν αριθμό αντικειμένων στη συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int

### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public final IControl addControl(int controlType, float x, float y, float width, float height)
```

Δημιουργεί και προσθέτει ένα νέο έλεγχο στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| controlType | int | Τύπος ελέγχου προς προσθήκη. |
| x | float | Η συντεταγμένη X για την αριστερή πλευρά του πλαισίου του σχήματος. |
| y | float | Η συντεταγμένη Y για την επάνω πλευρά του πλαισίου του σχήματος. |
| width | float | Το πλάτος του πλαισίου του σχήματος. |
| height | float | Το ύψος του πλαισίου του σχήματος. |

**Επιστρέφει:**
[IControl](../../com.aspose.slides/icontrol) - Δημιουργημένος έλεγχος.

### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public final void remove(IControl item)
```

Αφαιρεί έναν έλεγχο ActiveX από τη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | Ένας έλεγχος προς αφαίρεση. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Αφαιρεί έναν έλεγχο ActiveX που βρίσκεται στη συγκεκριμένη θέση από τη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης του ελέγχου προς αφαίρεση. |

### clear() {#clear--}
```
public final void clear()
```

Αφαιρεί όλους τους ελέγχους από τη συλλογή.

### get_Item(int index) {#get-Item-int-}
```
public final IControl get_Item(int index)
```

Επιστρέφει έναν έλεγχο στη συγκεκριμένη θέση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης ελέγχου. |

**Επιστρέφει:**
[IControl](../../com.aspose.slides/icontrol)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iterator()
```

Επιστρέφει έναν αριθμητή που διατρέχει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για την επανάληψη στη συλλογή.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iteratorJava()
```

Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - Ένας java.util.Iterator για ολόκληρη τη συλλογή.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Αντιγράφει ολόκληρη τη συλλογή στον καθορισμένο πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Πίνακας προορισμού |
| index | int | Δείκτης στον πίνακα προορισμού. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Επιστρέφει μια τιμή που υποδεικνύει αν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Επιστρέφει ένα στοιχείο ρίζας συγχρονισμού. Μόνο για ανάγνωση Object.

**Επιστρέφει:**
java.lang.Object

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο για ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject