---
title: ITable
second_title: Aspose.Slides για Java API Αναφορά
description: Αντιπροσωπεύει έναν πίνακα σε μια διαφάνεια.
type: docs
url: /el/com.aspose.slides/itable/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface ITable extends IGraphicalObject, IBulkTextFormattable
```

Αντιπροσωπεύει έναν πίνακα σε μια διαφάνεια.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Επιστρέφει το κελί στα συγκεκριμένα δείκτες στήλης και γραμμής. |
| [getRows()](#getRows--) | Επιστρέφει τη συλλογή των γραμμών. |
| [getColumns()](#getColumns--) | Επιστρέφει τη συλλογή των στηλών. |
| [getTableFormat()](#getTableFormat--) | Επιστρέφει το αντικείμενο TableFormat που περιέχει τις ιδιότητες μορφοποίησης για αυτόν τον πίνακα. |
| [getStylePreset()](#getStylePreset--) | Ανακτά ή ορίζει το ενσωματωμένο στυλ πίνακα. |
| [setStylePreset(int value)](#setStylePreset-int-) | Ανακτά ή ορίζει το ενσωματωμένο στυλ πίνακα. |
| [getRightToLeft()](#getRightToLeft--) | Καθορίζει αν ο πίνακας έχει σειρά ανάγνωσης από δεξιά προς αριστερά. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Καθορίζει αν ο πίνακας έχει σειρά ανάγνωσης από δεξιά προς αριστερά. |
| [getFirstRow()](#getFirstRow--) | Καθορίζει αν η πρώτη γραμμή ενός πίνακα πρέπει να σχεδιαστεί με ειδική μορφοποίηση. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | Καθορίζει αν η πρώτη γραμμή ενός πίνακα πρέπει να σχεδιαστεί με ειδική μορφοποίηση. |
| [getFirstCol()](#getFirstCol--) | Καθορίζει αν η πρώτη στήλη ενός πίνακα πρέπει να σχεδιαστεί με ειδική μορφοποίηση. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | Καθορίζει αν η πρώτη στήλη ενός πίνακα πρέπει να σχεδιαστεί με ειδική μορφοποίηση. |
| [getLastRow()](#getLastRow--) | Καθορίζει αν η τελευταία γραμμή ενός πίνακα πρέπει να σχεδιαστεί με ειδική μορφοποίηση. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | Καθορίζει αν η τελευταία γραμμή ενός πίνακα πρέπει να σχεδιαστεί με ειδική μορφοποίηση. |
| [getLastCol()](#getLastCol--) | Καθορίζει αν η τελευταία στήλη ενός πίνακα πρέπει να σχεδιαστεί με ειδική μορφοποίηση. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | Καθορίζει αν η τελευταία στήλη ενός πίνακα πρέπει να σχεδιαστεί με ειδική μορφοποίηση. |
| [getHorizontalBanding()](#getHorizontalBanding--) | Καθορίζει αν οι ζυγές γραμμές πρέπει να σχεδιαστούν με διαφορετική μορφοποίηση. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | Καθορίζει αν οι ζυγές γραμμές πρέπει να σχεδιαστούν με διαφορετική μορφοποίηση. |
| [getVerticalBanding()](#getVerticalBanding--) | Καθορίζει αν οι ζυγές στήλες πρέπει να σχεδιαστούν με διαφορετική μορφοποίηση. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | Καθορίζει αν οι ζυγές στήλες πρέπει να σχεδιαστούν με διαφορετική μορφοποίηση. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Συγχωνεύει γειτονικά κελιά. |
### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public abstract ICell get_Item(int columnIndex, int rowIndex)
```

Επιστρέφει το κελί στα συγκεκριμένα δείκτες στήλης και γραμμής. Μόνο για ανάγνωση [ICell](../../com.aspose.slides/icell).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Επιστρέφει:**
[ICell](../../com.aspose.slides/icell)
### getRows() {#getRows--}
```
public abstract IRowCollection getRows()
```

Επιστρέφει τη συλλογή των γραμμών. Μόνο για ανάγνωση [IRowCollection](../../com.aspose.slides/irowcollection).

**Επιστρέφει:**
[IRowCollection](../../com.aspose.slides/irowcollection)
### getColumns() {#getColumns--}
```
public abstract IColumnCollection getColumns()
```

Επιστρέφει τη συλλογή των στηλών. Μόνο για ανάγνωση [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Επιστρέφει:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)
### getTableFormat() {#getTableFormat--}
```
public abstract ITableFormat getTableFormat()
```

Επιστρέφει το αντικείμενο TableFormat που περιέχει τις ιδιότητες μορφοποίησης για αυτόν τον πίνακα. Μόνο για ανάγνωση [ITableFormat](../../com.aspose.slides/itableformat).

**Επιστρέφει:**
[ITableFormat](../../com.aspose.slides/itableformat)
### getStylePreset() {#getStylePreset--}
```
public abstract int getStylePreset()
```

Ανακτά ή ορίζει το ενσωματωμένο στυλ πίνακα. Ανάγνωση/εγγραφή [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Επιστρέφει:**
int
### setStylePreset(int value) {#setStylePreset-int-}
```
public abstract void setStylePreset(int value)
```

Ανακτά ή ορίζει το ενσωματωμένο στυλ πίνακα. Ανάγνωση/εγγραφή [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

Καθορίζει αν ο πίνακας έχει σειρά ανάγνωσης από δεξιά προς αριστερά. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public abstract void setRightToLeft(boolean value)
```

Καθορίζει αν ο πίνακας έχει σειρά ανάγνωσης από δεξιά προς αριστερά. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public abstract boolean getFirstRow()
```

Καθορίζει αν η πρώτη γραμμή ενός πίνακα πρέπει να σχεδιαστεί με ειδική μορφοποίηση. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public abstract void setFirstRow(boolean value)
```

Καθορίζει αν η πρώτη γραμμή ενός πίνακα πρέπει να σχεδιαστεί με ειδική μορφοποίηση. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public abstract boolean getFirstCol()
```

Καθορίζει αν η πρώτη στήλη ενός πίνακα πρέπει να σχεδιαστεί με ειδική μορφοποίηση. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public abstract void setFirstCol(boolean value)
```

Καθορίζει αν η πρώτη στήλη ενός πίνακα πρέπει να σχεδιαστεί με ειδική μορφοποίηση. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public abstract boolean getLastRow()
```

Καθορίζει αν η τελευταία γραμμή ενός πίνακα πρέπει να σχεδιαστεί με ειδική μορφοποίηση. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setLastRow(boolean value) {#setLastRow-boolean-}
```
public abstract void setLastRow(boolean value)
```

Καθορίζει αν η τελευταία γραμμή ενός πίνακα πρέπει να σχεδιαστεί με ειδική μορφοποίηση. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public abstract boolean getLastCol()
```

Καθορίζει αν η τελευταία στήλη ενός πίνακα πρέπει να σχεδιαστεί με ειδική μορφοποίηση. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setLastCol(boolean value) {#setLastCol-boolean-}
```
public abstract void setLastCol(boolean value)
```

Καθορίζει αν η τελευταία στήλη ενός πίνακα πρέπει να σχεδιαστεί με ειδική μορφοποίηση. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public abstract boolean getHorizontalBanding()
```

Καθορίζει αν οι ζυγές γραμμές πρέπει να σχεδιαστούν με διαφορετική μορφοποίηση. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public abstract void setHorizontalBanding(boolean value)
```

Καθορίζει αν οι ζυγές γραμμές πρέπει να σχεδιαστούν με διαφορετική μορφοποίηση. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public abstract boolean getVerticalBanding()
```

Καθορίζει αν οι ζυγές στήλες πρέπει να σχεδιαστούν με διαφορετική μορφοποίηση. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public abstract void setVerticalBanding(boolean value)
```

Καθορίζει αν οι ζυγές στήλες πρέπει να σχεδιαστούν με διαφορετική μορφοποίηση. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public abstract ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

Συγχωνεύει γειτονικά κελιά.

**Παράμετρα:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | Κελί για συγχώνευση. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Κελί για συγχώνευση. |
| allowSplitting | boolean | True για να επιτρέπεται ο διαχωρισμός των κελιών. |

**Επιστρέφει:**
[ICell](../../com.aspose.slides/icell) - Συγχωνευμένο κελί.