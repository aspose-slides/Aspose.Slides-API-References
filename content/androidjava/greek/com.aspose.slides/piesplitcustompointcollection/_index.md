---
title: PieSplitCustomPointCollection
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Αντιπροσωπεύει μια συλλογή σημείων για το σημείο διαχωρισμού σε διάγραμμα bar-of-pie ή pie-of-pie με προσαρμοσμένο διαχωρισμό.
type: docs
url: /el/com.aspose.slides/piesplitcustompointcollection/
---
**Κληρονόμηση:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
```
public class PieSplitCustomPointCollection implements IPieSplitCustomPointCollection
```

Αναπαριστά μια συλλογή σημείων για το σημείο διαχωρισμού σε διάγραμμα bar-of-pie ή pie-of-pie με προσαρμοσμένο διαχωρισμό.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει το σημείο δεδομένων του γραφήματος για τον καθορισμένο δείκτη. |
| [add(int dataPointIndex)](#add-int-) | Προσθέτει σημείο δεδομένων με το δείκτη του στη συλλογή σημείων της γονικής σειράς. |
| [addItem(IChartDataPoint dataPoint)](#addItem-com.aspose.slides.IChartDataPoint-) | Προσθέτει σημείο δεδομένων στη συλλογή. |
| [removeItem(IChartDataPoint dataPoint)](#removeItem-com.aspose.slides.IChartDataPoint-) | Αφαιρεί στοιχείο από τη συλλογή. |
| [remove(int dataPointIndex)](#remove-int-) | Αφαιρεί στοιχείο από τη συλλογή με το δείκτη του στη συλλογή σημείων της γονικής σειράς. |
| [clear()](#clear--) | Αφαιρεί όλα τα στοιχεία από το [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [containsItem(IChartDataPoint item)](#containsItem-com.aspose.slides.IChartDataPoint-) | Καθορίζει εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) περιέχει μια συγκεκριμένη τιμή. |
| [copyToTArray(IChartDataPoint[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IChartDataPoint---int-) | Αντιγράφει τα στοιχεία του [IGenericCollection](../../com.aspose.slides/igenericcollection) σε έναν Πίνακα, ξεκινώντας από έναν συγκεκριμένο δείκτη Πίνακα. |
| [size()](#size--) | Επιστρέφει ή ορίζει τον αριθμό των σημείων δεδομένων του γραφήματος. |
| [isReadOnly()](#isReadOnly--) | Λαμβάνει μια τιμή που υποδεικνύει εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) είναι μόνο για ανάγνωση. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει μια τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει τη ρίζα συγχρονισμού. |
| [iterator()](#iterator--) | Επιστρέφει έναν απαριθμητή που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

Επιστρέφει το σημείο δεδομένων του γραφήματος για τον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης. |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Σημείο δεδομένων γραφήματος.

### add(int dataPointIndex) {#add-int-}
```
public final void add(int dataPointIndex)
```

Προσθέτει σημείο δεδομένων με το δείκτη του στη συλλογή σημείων της γονικής σειράς.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dataPointIndex | int | Δείκτης σημείου δεδομένων στη συλλογή σημείων της γονικής σειράς. |

### addItem(IChartDataPoint dataPoint) {#addItem-com.aspose.slides.IChartDataPoint-}
```
public void addItem(IChartDataPoint dataPoint)
```

Προσθέτει σημείο δεδομένων στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Το σημείο δεδομένων να προστεθεί. |

### removeItem(IChartDataPoint dataPoint) {#removeItem-com.aspose.slides.IChartDataPoint-}
```
public boolean removeItem(IChartDataPoint dataPoint)
```

Αφαιρεί στοιχείο από τη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Το σημείο δεδομένων να αφαιρεθεί. |

**Επιστρέφει:**
boolean - true αν το στοιχείο αφαιρεθεί επιτυχώς· διαφορετικά, false. Η μέθοδος αυτή επίσης επιστρέφει false εάν το στοιχείο δεν βρέθηκε στη System.Collections.Generic.List\{T\}.

### remove(int dataPointIndex) {#remove-int-}
```
public final void remove(int dataPointIndex)
```

Αφαιρεί στοιχείο από τη συλλογή με το δείκτη του στη συλλογή σημείων της γονικής σειράς.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dataPointIndex | int | Δείκτης σημείου δεδομένων στη συλλογή σημείων της γονικής σειράς. |

### clear() {#clear--}
```
public final void clear()
```

Αφαιρεί όλα τα στοιχεία από το [IGenericCollection](../../com.aspose.slides/igenericcollection).

### containsItem(IChartDataPoint item) {#containsItem-com.aspose.slides.IChartDataPoint-}
```
public boolean containsItem(IChartDataPoint item)
```

Καθορίζει εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) περιέχει μια συγκεκριμένη τιμή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Το αντικείμενο για εντοπισμό στο [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Επιστρέφει:**
boolean - true αν το στοιχείο βρεθεί στο [IGenericCollection](../../com.aspose.slides/igenericcollection)· διαφορετικά, false.

### copyToTArray(IChartDataPoint[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IChartDataPoint---int-}
```
public void copyToTArray(IChartDataPoint[] array, int arrayIndex)
```

Αντιγράφει τα στοιχεία του [IGenericCollection](../../com.aspose.slides/igenericcollection) σε έναν Πίνακα, ξεκινώντας από έναν συγκεκριμένο δείκτη Πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | [IChartDataPoint\[\]](../../com.aspose.slides/ichartdatapoint) | Ο μονοδιάστατος Πίνακας που είναι ο προορισμός των στοιχείων που αντιγράφονται από το [IGenericCollection](../../com.aspose.slides/igenericcollection). Ο Πίνακας πρέπει να έχει μηδενική βάση δεικτών. |
| arrayIndex | int | Ο δείκτης μηδενικής βάσης στον Πίνακα από όπου αρχίζει η αντιγραφή. |

### size() {#size--}
```
public final int size()
```

Επιστρέφει ή ορίζει τον αριθμό των σημείων δεδομένων του γραφήματος. Μόνο ανάγνωση int.

**Επιστρέφει:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Λαμβάνει μια τιμή που υποδεικνύει εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) είναι μόνο για ανάγνωση. Μόνο ανάγνωση boolean.

**Επιστρέφει:**
boolean - true αν το [IGenericCollection](../../com.aspose.slides/igenericcollection) είναι μόνο για ανάγνωση· διαφορετικά, false.

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Επιστρέφει μια τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Μόνο ανάγνωση boolean.

**Επιστρέφει:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Επιστρέφει τη ρίζα συγχρονισμού. Μόνο ανάγνωση Object.

**Επιστρέφει:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

Επιστρέφει έναν απαριθμητή που διατρέχει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για την επανάληψη της συλλογής.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Ένας java.util.Iterator για ολόκληρη τη συλλογή.