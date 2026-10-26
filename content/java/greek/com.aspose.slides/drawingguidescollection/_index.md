---
title: DrawingGuidesCollection
second_title: Aspose.Slides για Java – Αναφορά API
description: Αντιπροσωπεύει μια συλλογή των ρυθμιζόμενων οδηγών σχεδίασης.
type: docs
url: /el/com.aspose.slides/drawingguidescollection/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)
```
public final class DrawingGuidesCollection implements IDrawingGuidesCollection
```

Αντιπροσωπεύει μια συλλογή των ρυθμιζόμενων οδηγών σχεδίασης.
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει τον οδηγό σχεδίασης με βάση το ευρετήριο. |
| [add(byte orientation, float position)](#add-byte-float-) | Προσθέτει τον οδηγό σχεδίασης στο τέλος της συλλογής. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί τον οδηγό σχεδίασης στο συγκεκριμένο ευρετήριο. |
| [clear()](#clear--) | Αφαιρεί όλα τα στοιχεία από τη συλλογή. |
| [iterator()](#iterator--) | Επιστρέφει έναν enumerator που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
| [getCount()](#getCount--) | Επιστρέφει τον αριθμό των στοιχείων στη συλλογή. |
| [copyTo(IDrawingGuide[] array, int index)](#copyTo-com.aspose.slides.IDrawingGuide---int-) | Αντιγράφει όλα τα στοιχεία από τη συλλογή στον καθορισμένο πίνακα. |
### get_Item(int index) {#get-Item-int-}
```
public final IDrawingGuide get_Item(int index)
```

Επιστρέφει τον οδηγό σχεδίασης με βάση το ευρετήριο. Μόνο για ανάγνωση [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Τιμή επιστροφής:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public final IDrawingGuide add(byte orientation, float position)
```

Προσθέτει τον οδηγό σχεδίασης στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| orientation | byte | Προσανατολισμός του οδηγού σχεδίασης. |
| position | float | Θέση του οδηγού σχεδίασης σε μονάδες σημείων. |

**Τιμή επιστροφής:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Αφαιρεί τον οδηγό σχεδίασης στο συγκεκριμένο ευρετήριο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ευρετήριο του οδηγού σχεδίασης που πρέπει να διαγραφεί. |

### clear() {#clear--}
```
public final void clear()
```

Αφαιρεί όλα τα στοιχεία από τη συλλογή.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iterator()
```

Επιστρέφει έναν enumerator που διατρέχει τη συλλογή.

**Τιμή επιστροφής:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για την επανάληψη στη συλλογή.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iteratorJava()
```

Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Τιμή επιστροφής:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - Ένας java.util.Iterator για ολόκληρη τη συλλογή.
### getCount() {#getCount--}
```
public final int getCount()
```

Επιστρέφει τον αριθμό των στοιχείων στη συλλογή. Μόνο για ανάγνωση int.

**Τιμή επιστροφής:**
int
### copyTo(IDrawingGuide[] array, int index) {#copyTo-com.aspose.slides.IDrawingGuide---int-}
```
public final void copyTo(IDrawingGuide[] array, int index)
```

Αντιγράφει όλα τα στοιχεία από τη συλλογή στον καθορισμένο πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | [IDrawingGuide\[\]](../../com.aspose.slides/idrawingguide) | Πίνακας προορισμού. |
| index | int | Αρχικό ευρετήριο στον πίνακα προορισμού. |