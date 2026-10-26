---
title: IRow
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Αναπαριστά μια γραμμή σε έναν πίνακα.
type: docs
url: /el/com.aspose.slides/irow/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IRow extends ICellCollection, IBulkTextFormattable
```

Αναπαριστά μια γραμμή σε έναν πίνακα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getHeight()](#getHeight--) | Επιστρέφει το ύψος μιας γραμμής. |
| [getMinimalHeight()](#getMinimalHeight--) | Επιστρέφει ή ορίζει το ελάχιστο δυνατό ύψος μιας γραμμής. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Επιστρέφει ή ορίζει το ελάχιστο δυνατό ύψος μιας γραμμής. |
| [getRowFormat()](#getRowFormat--) | Επιστρέφει το αντικείμενο RowFormat που περιέχει ιδιότητες μορφοποίησης για αυτή τη γραμμή. |
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


Επιστρέφει το ύψος μιας γραμμής. Ανάγνωση μόνο double.

**Επιστρέφει:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```


Επιστρέφει ή ορίζει το ελάχιστο δυνατό ύψος μιας γραμμής. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public abstract void setMinimalHeight(double value)
```


Επιστρέφει ή ορίζει το ελάχιστο δυνατό ύψος μιας γραμμής. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |
### getRowFormat() {#getRowFormat--}
```
public abstract IRowFormat getRowFormat()
```


Επιστρέφει το αντικείμενο RowFormat που περιέχει ιδιότητες μορφοποίησης για αυτή τη γραμμή. Μόνο ανάγνωση [IRowFormat](../../com.aspose.slides/irowformat).

**Επιστρέφει:**
[IRowFormat](../../com.aspose.slides/irowformat)