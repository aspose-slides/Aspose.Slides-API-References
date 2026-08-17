---
title: IChartCellCollection
second_title: Aspose.Slides για Αναφορά API Java
description: Αντιπροσωπεύει μια συλλογή κελιών με δεδομένα.
type: docs
url: /el/com.aspose.slides/ichartcellcollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IChartCellCollection extends System.Collections.Generic.IGenericEnumerable<IChartDataCell>
```

Αντιπροσωπεύει μια συλλογή κελιών με δεδομένα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | Επιστρέφει τη διεύθυνση του συνόλου των κελιών στο βιβλίο εργασίας. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | Συνεχεία συμβολοσειράς από όλες τις τιμές συμβολοσειρών κελιών. |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει ένα κελί (IChartDataCell) με βάση το δείκτη. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Προσθέτει νέο κελί στη συλλογή. |
| [add(Object value)](#add-java.lang.Object-) | Δημιουργεί [IChartDataCell](../../com.aspose.slides/ichartdatacell) από την καθορισμένη τιμή και το προσθέτει στη συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί ένα κελί από τη συλλογή με βάση το δείκτη. |
| [getCount()](#getCount--) | Αποκτά τον αριθμό των κελιών στη συλλογή. |
### getCellsAddress() {#getCellsAddress--}
```
public abstract String getCellsAddress()
```

Επιστρέφει τη διεύθυνση του συνόλου των κελιών στο βιβλίο εργασίας.

**Επιστρέφει:**
java.lang.String - Διεύθυνση του συνόλου των κελιών στο βιβλίο εργασίας String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public abstract String getConcatenatedValuesFromCells()
```

Συνεχεία συμβολοσειράς από όλες τις τιμές συμβολοσειρών κελιών.

**Επιστρέφει:**
java.lang.String - Συνεχεια των τιμών των κελιών σε μια συμβολοσειρά String
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int index)
```

Επιστρέφει ένα κελί (IChartDataCell) με βάση το δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης ενός κελιού. |

**Επιστρέφει:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Κελί με δεδομένα.
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract void add(IChartDataCell chartDataCell)
```

Προσθέτει νέο κελί στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Νέο κελί προς προσθήκη. |
### add(Object value) {#add-java.lang.Object-}
```
public abstract void add(Object value)
```

Δημιουργεί [IChartDataCell](../../com.aspose.slides/ichartdatacell) από την καθορισμένη τιμή και το προσθέτει στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.Object | Η τιμή.

--------------------

Αυτή η μέθοδος προσθέτει φύλλο εργασίας με όνομα AUTO_DATA και προσθέτει όλες τις τιμές εκεί. Εάν χρησιμοποιείτε [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) για προσθήκη ή επεξεργασία τιμών Cell, βεβαιωθείτε ότι δεν χρησιμοποιείτε αυτό το φύλλο εργασίας. Ο μέγιστος αριθμός τιμών που προστίθενται με αυτή τη μέθοδο δεν πρέπει να υπερβαίνει το 16711680 |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Αφαιρεί ένα κελί από τη συλλογή με βάση το δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης ενός κελιού προς αφαίρεση. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

Αποκτά τον αριθμό των κελιών στη συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int