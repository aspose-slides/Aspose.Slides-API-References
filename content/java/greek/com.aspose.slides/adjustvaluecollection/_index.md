---
title: AdjustValueCollection
second_title: Aspose.Slides για την Java API Αναφορά
description: Αναπαριστά μια συλλογή προσαρμογών σχήματος.
type: docs
url: /el/com.aspose.slides/adjustvaluecollection/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
```
public final class AdjustValueCollection extends DomObject<GeometryShape> implements IAdjustValueCollection
```

Αναπαριστά μια συλλογή προσαρμογών σχήματος.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [size()](#size--) | Επιστρέφει έναν αριθμό προσαρμογών. |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει προσαρμογή βάσει δείκτη. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει όλα τα στοιχεία από τη συλλογή στον καθορισμένο πίνακα. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει τη ρίζα συγχρονισμού. |
| [iterator()](#iterator--) | Επιστρέφει έναν απαριθμητή για ολόκληρη τη συλλογή. |
### size() {#size--}
```
public final int size()
```


Επιστρέφει έναν αριθμό προσαρμογών. Read-only int.

**Επιστρέφει:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAdjustValue get_Item(int index)
```


Επιστρέφει προσαρμογή βάσει δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | δείκτης προσαρμογής. |

**Επιστρέφει:**
[IAdjustValue](../../com.aspose.slides/iadjustvalue) - [AdjustValue](../../com.aspose.slides/adjustvalue).
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


Επιστρέφει τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Read-only boolean.

**Επιστρέφει:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Επιστρέφει τη ρίζα συγχρονισμού. Read-only Object.

**Επιστρέφει:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.IEnumerator iterator()
```


Επιστρέφει έναν απαριθμητή για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.IEnumerator