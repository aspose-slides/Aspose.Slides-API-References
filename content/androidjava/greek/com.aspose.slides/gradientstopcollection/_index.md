---
title: GradientStopCollection
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αναπαριστά μια συλλογή από σημεία διαβάθμισης.
type: docs
url: /el/com.aspose.slides/gradientstopcollection/
---
**Κληρονομικότητα:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Όλες οι Υλοποιημένες Διεπαφές:**  
[com.aspose.slides.IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)
```
public final class GradientStopCollection extends PVIObject implements IGradientStopCollection
```

Αναπαριστά μια συλλογή από σημεία διαβάθμισης.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [size()](#size--) | Επιστρέφει τον αριθμό των σημείων διαβάθμισης σε μια συλλογή. |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει το σημείο διαβάθμισης με βάση το δείκτη. |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | Δημιουργεί το νέο σημείο διαβάθμισης και το προσθέτει στο τέλος της συλλογής. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Δημιουργεί το νέο σημείο διαβάθμισης και το προσθέτει στο τέλος της συλλογής. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Δημιουργεί το νέο σημείο διαβάθμισης και το προσθέτει στο τέλος της συλλογής. |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | Δημιουργεί το νέο σημείο διαβάθμισης και το εισάγει στη συλλογή στη συγκεκριμένη θέση. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Δημιουργεί το νέο σημείο διαβάθμισης και το εισάγει στη συλλογή στη συγκεκριμένη θέση. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Δημιουργεί το νέο σημείο διαβάθμισης και το εισάγει στη συλλογή στη συγκεκριμένη θέση. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί ένα σημείο διαβάθμισης στη συγκεκριμένη θέση. |
| [clear()](#clear--) | Αφαιρεί όλα τα σημεία διαβάθμισης από μια συλλογή. |
| [iterator()](#iterator--) | Επιστρέφει έναν ατζέντη που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει όλα τα στοιχεία από τη συλλογή στον καθορισμένο πίνακα. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει μια τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει τη ρίζα συγχρονισμού. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Έκδοση. Μόνο για ανάγνωση long.

**Επιστρέφει:**  
long
### size() {#size--}
```
public final int size()
```


Επιστρέφει τον αριθμό των σημείων διαβάθμισης σε μια συλλογή. Μόνο για ανάγνωση int .

**Επιστρέφει:**  
int
### get_Item(int index) {#get-Item-int-}
```
public final IGradientStop get_Item(int index)
```


Επιστρέφει το σημείο διαβάθμισης με βάση το δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**  
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public final IGradientStop add(float position, Integer color)
```


Δημιουργεί το νέο σημείο διαβάθμισης και το προσθέτει στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | float | Θέση του νέου σημείου διαβάθμισης. |
| color | java.lang.Integer | Χρώμα του νέου σημείου διαβάθμισης. |

**Επιστρέφει:**  
[IGradientStop](../../com.aspose.slides/igradientstop) - Δείκτης του νέου σημείου διαβάθμισης στη συλλογή.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public final IGradientStop addPresetColor(float position, int presetColor)
```


Δημιουργεί το νέο σημείο διαβάθμισης και το προσθέτει στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | float | Θέση του νέου σημείου διαβάθμισης. |
| presetColor | int | Χρώμα του νέου σημείου διαβάθμισης. |

**Επιστρέφει:**  
[IGradientStop](../../com.aspose.slides/igradientstop) - Δείκτης του νέου σημείου διαβάθμισης στη συλλογή.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public final IGradientStop addSchemeColor(float position, int schemeColor)
```


Δημιουργεί το νέο σημείο διαβάθμισης και το προσθέτει στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | float | Θέση του νέου σημείου διαβάθμισης. |
| schemeColor | int | Χρώμα του νέου σημείου διαβάθμισης. |

**Επιστρέφει:**  
[IGradientStop](../../com.aspose.slides/igradientstop) - Δείκτης του νέου σημείου διαβάθμισης στη συλλογή.
### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public final void insert(int index, float position, Integer color)
```


Δημιουργεί το νέο σημείο διαβάθμισης και το εισάγει στη συλλογή στη συγκεκριμένη θέση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης στη συλλογή όπου θα εισαχθεί το νέο σημείο διαβάθμισης. |
| position | float | Θέση του νέου σημείου διαβάθμισης. |
| color | java.lang.Integer | Χρώμα του νέου σημείου διαβάθμισης. |
### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public final void insertPresetColor(int index, float position, int presetColor)
```


Δημιουργεί το νέο σημείο διαβάθμισης και το εισάγει στη συλλογή στη συγκεκριμένη θέση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης στη συλλογή όπου θα εισαχθεί το νέο σημείο διαβάθμισης. |
| position | float | Θέση του νέου σημείου διαβάθμισης. |
| presetColor | int | Χρώμα του νέου σημείου διαβάθμισης. |
### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public final void insertSchemeColor(int index, float position, int schemeColor)
```


Δημιουργεί το νέο σημείο διαβάθμισης και το εισάγει στη συλλογή στη συγκεκριμένη θέση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης στη συλλογή όπου θα εισαχθεί το νέο σημείο διαβάθμισης. |
| position | float | Θέση του νέου σημείου διαβάθμισης. |
| schemeColor | int | Χρώμα του νέου σημείου διαβάθμισης. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Αφαιρεί ένα σημείο διαβάθμισης στη συγκεκριμένη θέση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης ενός σημείου διαβάθμισης που πρέπει να διαγραφεί. |
### clear() {#clear--}
```
public final void clear()
```


Αφαιρεί όλα τα σημεία διαβάθμισης από μια συλλογή.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iterator()
```


Επιστρέφει έναν ατζέντη που διατρέχει τη συλλογή.

**Επιστρέφει:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για την επανάληψη στη συλλογή.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iteratorJava()
```


Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - Ένα java.util.Iterator για ολόκληρη τη συλλογή.
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


Επιστρέφει μια τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Μόνο για ανάγνωση boolean .

**Επιστρέφει:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Επιστρέφει τη ρίζα συγχρονισμού. Μόνο για ανάγνωση Object.

**Επιστρέφει:**  
java.lang.Object