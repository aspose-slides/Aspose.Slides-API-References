---
title: EffectStyleCollection
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Αντιπροσωπεύει μια συλλογή στυλ εφέ.
type: docs
url: /el/com.aspose.slides/effectstylecollection/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IEffectStyleCollection](../../com.aspose.slides/ieffectstylecollection)
```
public final class EffectStyleCollection extends DomObject<FormatScheme> implements IEffectStyleCollection
```

Αντιπροσωπεύει μια συλλογή στυλ εφέ.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει ένα στοιχείο στη συγκεκριμένη θέση. |
| [iterator()](#iterator--) | Επιστρέφει έναν αριθμητή που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
| [size()](#size--) | Επιστρέφει έναν αριθμό στοιχείων στη συλλογή. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει όλα τα στοιχεία από τη συλλογή στον καθορισμένο πίνακα. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει μια τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει μια ρίζα συγχρονισμού. |
### get_Item(int index) {#get-Item-int-}
```
public final IEffectStyle get_Item(int index)
```


Επιστρέφει ένα στοιχείο στη συγκεκριμένη θέση. Μόνο για ανάγνωση [EffectStyle](../../com.aspose.slides/effectstyle).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Θέση του στοιχείου. |

**Τιμή Επιστροφής:**
[IEffectStyle](../../com.aspose.slides/ieffectstyle) - Στοιχείο στη συγκεκριμένη θέση.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectStyle> iterator()
```


Επιστρέφει έναν αριθμητή που διατρέχει τη συλλογή.

**Τιμή Επιστροφής:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectStyle> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για τη διαμετάδοση της συλλογής.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectStyle> iteratorJava()
```


Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Τιμή Επιστροφής:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectStyle> - Ένας java.util.Iterator για ολόκληρη τη συλλογή.
### size() {#size--}
```
public final int size()
```


Επιστρέφει έναν αριθμό στοιχείων στη συλλογή. Μόνο για ανάγνωση int, Μόνο για ανάγνωση int.

**Τιμή Επιστροφής:**
int
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


Επιστρέφει μια τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Μόνο για ανάγνωση boolean.

**Τιμή Επιστροφής:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Επιστρέφει μια ρίζα συγχρονισμού. Μόνο για ανάγνωση Object.

**Τιμή Επιστροφής:**
java.lang.Object