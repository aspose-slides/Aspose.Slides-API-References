---
title: GradientStopCollectionEffectiveData
second_title: Aspose.Slides για Android μέσω Αναφοράς API Java
description: Αντιπροσωπεύει μια συλλογή αντικειμένων GradientStopData.
type: docs
url: /el/com.aspose.slides/gradientstopcollectioneffectivedata/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διασυνδέσεις:**
com.aspose.slides.IEffectiveData, [com.aspose.slides.IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)
```
public class GradientStopCollectionEffectiveData implements IEffectiveData, IGradientStopCollectionEffectiveData
```

Αντιπροσωπεύει μια συλλογή αντικειμένων GradientStopData.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [size()](#size--) | Επιστρέφει τον αριθμό των σημείων διαβάθμισης σε μια συλλογή. |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει το σημείο διαβάθμισης με βάση το ευρετήριο. |
| [iterator()](#iterator--) | Επιστρέφει έναν enumerator που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει όλα τα στοιχεία από τη συλλογή στον καθορισμένο πίνακα. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει μια τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει μια ρίζα συγχρονισμού. |
### size() {#size--}
```
public final int size()
```

Επιστρέφει τον αριθμό των σημείων διαβάθμισης σε μια συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IGradientStopEffectiveData get_Item(int index)
```

Επιστρέφει το σημείο διαβάθμισης με βάση το ευρετήριο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IGradientStopEffectiveData](../../com.aspose.slides/igradientstopeffectivedata)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStopEffectiveData> iterator()
```

Επιστρέφει έναν enumerator που διατρέχει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStopEffectiveData> - Ένα IGenericEnumerator που μπορεί να χρησιμοποιηθεί για να διατρέξει τη συλλογή.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStopEffectiveData> iteratorJava()
```

Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStopEffectiveData> - Ένας java.util.Iterator για ολόκληρη τη συλλογή.
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

**Επιστρέφει:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Επιστρέφει μια ρίζα συγχρονισμού. Μόνο για ανάγνωση Object.

**Επιστρέφει:**
java.lang.Object