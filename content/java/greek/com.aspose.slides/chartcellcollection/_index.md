---
title: ChartCellCollection
second_title: Αναφορά API του Aspose.Slides για Java
description: Αναπαριστά μια συλλογή από κελιά με δεδομένα.
type: docs
url: /el/com.aspose.slides/chartcellcollection/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IChartCellCollection](../../com.aspose.slides/ichartcellcollection), com.aspose.slides.IDOMObject
```
public class ChartCellCollection implements IChartCellCollection, IDOMObject
```

Αναπαριστά μια συλλογή από κελιά με δεδομένα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | Επιστρέφει τη διεύθυνση του συνόλου των κελιών στο βιβλίο εργασίας. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | Συνευρυμένο κείμενο από όλες τις τιμές των κελιών. |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει ένα κελί (IChartDataCell) με βάση τον δείκτη. |
| [add(IChartDataCell cell)](#add-com.aspose.slides.IChartDataCell-) | Προσθέτει νέο κελί στη συλλογή. |
| [add(Object value)](#add-java.lang.Object-) | Δημιουργεί [ChartDataCell](../../com.aspose.slides/chartdatacell) από την καθορισμένη τιμή και το προσθέτει στη συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί ένα κελί από τη συλλογή με βάση τον δείκτη. |
| [getCount()](#getCount--) | Λαμβάνει τον αριθμό των κελιών στη συλλογή. |
| [iterator()](#iterator--) | Επιστρέφει έναν επαναληπτή που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java επαναληπτή για ολόκληρη τη συλλογή. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getCellsAddress() {#getCellsAddress--}
```
public final String getCellsAddress()
```

Επιστρέφει τη διεύθυνση του συνόλου των κελιών στο βιβλίο εργασίας.

**Επιστρέφει:**
java.lang.String

### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public final String getConcatenatedValuesFromCells()
```

Συνευρυμένο κείμενο από όλες τις τιμές των κελιών.

**Επιστρέφει:**
java.lang.String

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataCell get_Item(int index)
```

Επιστρέφει ένα κελί (IChartDataCell) με βάση τον δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης ενός κελιού. |

**Επιστρέφει:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Κελί με δεδομένα.

### add(IChartDataCell cell) {#add-com.aspose.slides.IChartDataCell-}
```
public final void add(IChartDataCell cell)
```

Προσθέτει νέο κελί στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Νέο κελί προς προσθήκη. |

### add(Object value) {#add-java.lang.Object-}
```
public final void add(Object value)
```

Δημιουργεί [ChartDataCell](../../com.aspose.slides/chartdatacell) από την καθορισμένη τιμή και το προσθέτει στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.Object | Η τιμή.

--------------------

Αυτή η μέθοδος προσθέτει φύλλο εργασίας με όνομα AUTO_DATA και προσθέτει όλες τις τιμές εκεί. Εάν χρησιμοποιείτε [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) για να προσθέσετε ή να επεξεργαστείτε τιμές κελιών, βεβαιωθείτε ότι δεν χρησιμοποιείτε αυτό το φύλλο εργασίας. Ο μέγιστος αριθμός τιμών που προστίθενται με αυτή τη μέθοδο δεν πρέπει να υπερβαίνει το 16711680 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Αφαιρεί ένα κελί από τη συλλογή με βάση τον δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης ενός κελιού προς αφαίρεση. |

### getCount() {#getCount--}
```
public final int getCount()
```

Λαμβάνει τον αριθμό των κελιών στη συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iterator()
```

Επιστρέφει έναν επαναληπτή που διατρέχει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για την επανάληψη στη συλλογή.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iteratorJava()
```

Επιστρέφει έναν java επαναληπτή για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - Ένας java.util.Iterator για ολόκληρη τη συλλογή.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο για ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject