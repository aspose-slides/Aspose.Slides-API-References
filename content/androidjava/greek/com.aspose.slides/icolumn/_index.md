---
title: IColumn
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αντιπροσωπεύει μια στήλη σε έναν πίνακα.
type: docs
url: /el/com.aspose.slides/icolumn/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IColumn extends ICellCollection, IBulkTextFormattable
```

Αντιπροσωπεύει μια στήλη σε έναν πίνακα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getWidth()](#getWidth--) | Επιστρέφει ή ορίζει το πλάτος μιας στήλης. |
| [setWidth(double value)](#setWidth-double-) | Επιστρέφει ή ορίζει το πλάτος μιας στήλης. |
| [getColumnFormat()](#getColumnFormat--) | Επιστρέφει το αντικείμενο ColumnFormat που περιέχει τις ιδιότητες μορφοποίησης για αυτή τη στήλη. |

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Επιστρέφει ή ορίζει το πλάτος μιας στήλης. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

Επιστρέφει ή ορίζει το πλάτος μιας στήλης. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getColumnFormat() {#getColumnFormat--}
```
public abstract IColumnFormat getColumnFormat()
```

Επιστρέφει το αντικείμενο ColumnFormat που περιέχει τις ιδιότητες μορφοποίησης για αυτή τη στήλη. Μόνο για ανάγνωση [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Επιστρέφει:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)