---
title: IRow
second_title: Aspose.Slides για Java Αναφορά API
description: Αντιπροσωπεύει μια σειρά σε έναν πίνακα.
type: docs
url: /el/com.aspose.slides/irow/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IRow extends ICellCollection, IBulkTextFormattable
```

Αντιπροσωπεύει μια σειρά σε έναν πίνακα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getHeight()](#getHeight--) | Επιστρέφει το ύψος μιας σειράς. |
| [getMinimalHeight()](#getMinimalHeight--) | Επιστρέφει ή ορίζει το ελάχιστο δυνατό ύψος μιας σειράς. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Επιστρέφει ή ορίζει το ελάχιστο δυνατό ύψος μιας σειράς. |
| [getRowFormat()](#getRowFormat--) | Επιστρέφει το αντικείμενο RowFormat που περιέχει τις ιδιότητες μορφοποίησης για αυτή τη σειρά. |
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```

Επιστρέφει το ύψος μιας σειράς. Μόνο-ανάγνωση double.

**Επιστρέφει:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```

Επιστρέφει ή ορίζει το ελάχιστο δυνατό ύψος μιας σειράς. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public abstract void setMinimalHeight(double value)
```

Επιστρέφει ή ορίζει το ελάχιστο δυνατό ύψος μιας σειράς. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |
### getRowFormat() {#getRowFormat--}
```
public abstract IRowFormat getRowFormat()
```

Επιστρέφει το αντικείμενο RowFormat που περιέχει τις ιδιότητες μορφοποίησης για αυτή τη σειρά. Μόνο-ανάγνωση [IRowFormat](../../com.aspose.slides/irowformat).

**Επιστρέφει:**
[IRowFormat](../../com.aspose.slides/irowformat)