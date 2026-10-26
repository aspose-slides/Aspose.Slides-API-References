---
title: ExtraColorSchemeCollection
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Αντιπροσωπεί μια συλλογή πρόσθετων χρωματικών σχημάτων.
type: docs
url: /el/com.aspose.slides/extracolorschemecollection/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection), com.aspose.slides.IDOMObject
```
public class ExtraColorSchemeCollection implements IExtraColorSchemeCollection, IDOMObject
```

Αναπαριστά μια συλλογή πρόσθετων χρωματικών σχημάτων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [size()](#size--) | Επιστρέφει τον αριθμό των στοιχείων στη συλλογή. |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει ένα χρωματικό σχήμα με βάση το δείκτη. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iterator()](#iterator--) | Επιστρέφει έναν ενομετρητή που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει όλα τα στοιχεία της συλλογής στον καθορισμένο πίνακα. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει μια τιμή που υποδεικνύει αν η πρόσβαση στο ArrayList είναι συγχρονισμένη (thread safe). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει ένα αντικείμενο που μπορεί να χρησιμοποιηθεί για τον συγχρονισμό της πρόσβασης στη συλλογή. |
### size() {#size--}
```
public final int size()
```

Επιστρέφει τον αριθμό των στοιχείων στη συλλογή. Μόνο ανάγνωση int.

**Επιστρέφει:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IExtraColorScheme get_Item(int index)
```

Επιστρέφει ένα χρωματικό σχήμα με βάση το δείκτη. Μόνο ανάγνωση [ExtraColorScheme](../../com.aspose.slides/extracolorscheme).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IExtraColorScheme](../../com.aspose.slides/iextracolorscheme)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Επιστρέφει το αντικείμενο Parent\_Immediate. Μόνο ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iterator()
```

Επιστρέφει έναν ενομετρητή που διατρέχει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - Ένα IGenericEnumerator που μπορεί να χρησιμοποιηθεί για την διαπέραση της συλλογής.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iteratorJava()
```

Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - Ένας java.util.Iterator για ολόκληρη τη συλλογή.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Αντιγράφει όλα τα στοιχεία της συλλογής στον καθορισμένο πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Στόχος πίνακας. |
| index | int | Αρχικός δείκτης στον πίνακα. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Επιστρέφει μια τιμή που υποδεικνύει αν η πρόσβαση στο ArrayList είναι συγχρονισμένη (thread safe). Μόνο ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Επιστρέφει ένα αντικείμενο που μπορεί να χρησιμοποιηθεί για τον συγχρονισμό της πρόσβασης στη συλλογή. Μόνο ανάγνωση Object.

Επιστρέφει μια ρίζα συγχρονισμού. Μόνο ανάγνωση Object.

**Επιστρέφει:**
java.lang.Object