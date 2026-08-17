---
title: PieSplitCustomPointCollection
second_title: Aspose.Slides για Java – Αναφορά API
description: Αναπαριστά μια συλλογή σημείων για το σημείο διαχωρισμού σε γράφημα μπάρας-πίτας ή πίτας-πίτας με προσαρμοσμένο διαχωρισμό.
type: docs
url: /el/com.aspose.slides/piesplitcustompointcollection/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
```
public class PieSplitCustomPointCollection implements IPieSplitCustomPointCollection
```

Αναπαριστά μια συλλογή σημείων για το σημείο διαχωρισμού σε γράφημα μπάρας-πίτας ή πίτας-πίτας με προσαρμοσμένο διαχωρισμό.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει το σημείο δεδομένων διαγράμματος για τον καθορισμένο δείκτη. |
| [add(int dataPointIndex)](#add-int-) | Προσθέτει σημείο δεδομένων με βάση τον δείκτη του στη συλλογή σημείων της γονικής σειράς. |
| [addItem(IChartDataPoint dataPoint)](#addItem-com.aspose.slides.IChartDataPoint-) | Προσθέτει σημείο δεδομένων στη συλλογή. |
| [removeItem(IChartDataPoint dataPoint)](#removeItem-com.aspose.slides.IChartDataPoint-) | Αφαιρεί στοιχείο από τη συλλογή. |
| [remove(int dataPointIndex)](#remove-int-) | Αφαιρεί στοιχείο από τη συλλογή με βάση τον δείκτη του στη συλλογή σημείων της γονικής σειράς. |
| [clear()](#clear--) | Αφαιρεί όλα τα στοιχεία από το [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [containsItem(IChartDataPoint item)](#containsItem-com.aspose.slides.IChartDataPoint-) | Καθορίζει αν το [IGenericCollection](../../com.aspose.slides/igenericcollection) περιέχει μια συγκεκριμένη τιμή. |
| [copyToTArray(IChartDataPoint[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IChartDataPoint---int-) | Αντιγράφει τα στοιχεία του [IGenericCollection](../../com.aspose.slides/igenericcollection) σε έναν Πίνακα, ξεκινώντας από έναν συγκεκριμένο δείκτη Πίνακα. |
| [size()](#size--) | Επιστρέφει ή ορίζει τον αριθμό των σημείων δεδομένων διαγράμματος. |
| [isReadOnly()](#isReadOnly--) | Λαμβάνει μια τιμή που υποδεικνύει αν το [IGenericCollection](../../com.aspose.slides/igenericcollection) είναι μόνο ανάγνωση. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει μια τιμή που υποδεικνύει αν η πρόσβαση στη συλλογή είναι συγχρονισμένη (ασφαλής-νήματος). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει μια ρίζα συγχρονισμού. |
| [iterator()](#iterator--) | Επιστρέφει έναν enumerator που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

Επιστρέφει το σημείο δεδομένων διαγράμματος για τον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης. |

**Επιστροφή:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Σημείο δεδομένων διαγράμματος.
### add(int dataPointIndex) {#add-int-}
```
public final void add(int dataPointIndex)
```

Προσθέτει σημείο δεδομένων με βάση τον δείκτη του στη συλλογή σημείων της γονικής σειράς.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dataPointIndex | int | Δείκτης του σημείου δεδομένων στη συλλογή σημείων της γονικής σειράς. |
### addItem(IChartDataPoint dataPoint) {#addItem-com.aspose.slides.IChartDataPoint-}
```
public void addItem(IChartDataPoint dataPoint)
```

Προσθέτει σημείο δεδομένων στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Σημείο δεδομένων προς προσθήκη. |
### removeItem(IChartDataPoint dataPoint) {#removeItem-com.aspose.slides.IChartDataPoint-}
```
public boolean removeItem(IChartDataPoint dataPoint)
```

Αφαιρεί στοιχείο από τη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Σημείο δεδομένων για αφαίρεση. |

**Επιστροφή:**
boolean - true εάν το στοιχείο αφαιρέθηκε επιτυχώς· διαφορετικά, false. Αυτή η μέθοδος επίσης επιστρέφει false εάν το στοιχείο δεν βρέθηκε στη System.Collections.Generic.List\{T\}.
### remove(int dataPointIndex) {#remove-int-}
```
public final void remove(int dataPointIndex)
```

Αφαιρεί στοιχείο από τη συλλογή με βάση τον δείκτη του στη συλλογή σημείων της γονικής σειράς.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dataPointIndex | int | Δείκτης του σημείου δεδομένων στη συλλογή σημείων της γονικής σειράς. |
### clear() {#clear--}
```
public final void clear()
```

Αφαιρεί όλα τα στοιχεία από το [IGenericCollection](../../com.aspose.slides/igenericcollection).
### containsItem(IChartDataPoint item) {#containsItem-com.aspose.slides.IChartDataPoint-}
```
public boolean containsItem(IChartDataPoint item)
```

Καθορίζει αν το [IGenericCollection](../../com.aspose.slides/igenericcollection) περιέχει μια συγκεκριμένη τιμή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Το αντικείμενο προς εντόπιση στο [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Επιστροφή:**
boolean - true εάν το στοιχείο βρεθεί στο [IGenericCollection](../../com.aspose.slides/igenericcollection)· διαφορετικά, false.
### copyToTArray(IChartDataPoint[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IChartDataPoint---int-}
```
public void copyToTArray(IChartDataPoint[] array, int arrayIndex)
```

Αντιγράφει τα στοιχεία του [IGenericCollection](../../com.aspose.slides/igenericcollection) σε έναν Πίνακα, ξεκινώντας από έναν συγκεκριμένο δείκτη Πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | [IChartDataPoint\[\]](../../com.aspose.slides/ichartdatapoint) | Ο μονοδιάστατος Πίνακας που είναι ο προορισμός των αντιγραμμένων στοιχείων από το [IGenericCollection](../../com.aspose.slides/igenericcollection). Ο Πίνακας πρέπει να έχει δεικτοδότηση από το μηδέν. |
| arrayIndex | int | Ο μηδενικός δείκτης στον πίνακα από όπου ξεκινά η αντιγραφή. |
### size() {#size--}
```
public final int size()
```

Επιστρέφει ή ορίζει τον αριθμό των σημείων δεδομένων διαγράμματος. Μόνο ανάγνωση int.

**Επιστροφή:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Λαμβάνει μια τιμή που υποδεικνύει αν το [IGenericCollection](../../com.aspose.slides/igenericcollection) είναι μόνο ανάγνωση. Μόνο ανάγνωση boolean.

**Επιστροφή:**
boolean - true εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) είναι μόνο ανάγνωση· διαφορετικά, false.
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Επιστρέφει μια τιμή που υποδεικνύει αν η πρόσβαση στη συλλογή είναι συγχρονισμένη (ασφαλής-νήματος). Μόνο ανάγνωση boolean.

**Επιστροφή:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Επιστρέφει μια ρίζα συγχρονισμού. Μόνο ανάγνωση Object.

**Επιστροφή:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

Επιστρέφει έναν enumerator που διατρέχει τη συλλογή.

**Επιστροφή:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστροφή:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - An java.util.Iterator for the entire collection.