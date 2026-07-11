---
title: ITable
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αντιπροσωπεύει έναν πίνακα σε μια διαφάνεια.
type: docs
url: /el/com.aspose.slides/itable/
---
**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface ITable extends IGraphicalObject, IBulkTextFormattable
```

Αντιπροσωπεύει έναν πίνακα σε μια διαφάνεια.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Επιστρέφει το κελί στους καθορισμένους δείκτες στήλης και σειράς. |
| [getRows()](#getRows--) | Επιστρέφει τη συλλογή των σειρών. |
| [getColumns()](#getColumns--) | Επιστρέφει τη συλλογή των στηλών. |
| [getTableFormat()](#getTableFormat--) | Επιστρέφει το αντικείμενο TableFormat που περιέχει τις ιδιότητες μορφοποίησης για αυτόν τον πίνακα. |
| [getStylePreset()](#getStylePreset--) | Ανακτά ή ορίζει το ενσωματωμένο στυλ πίνακα. |
| [setStylePreset(int value)](#setStylePreset-int-) | Ανακτά ή ορίζει το ενσωματωμένο στυλ πίνακα. |
| [getRightToLeft()](#getRightToLeft--) | Καθορίζει εάν ο πίνακας έχει σειρά ανάγνωσης από δεξιά προς αριστερά. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Καθορίζει εάν ο πίνακας έχει σειρά ανάγνωσης από δεξιά προς αριστερά. |
| [getFirstRow()](#getFirstRow--) | Καθορίζει εάν η πρώτη σειρά του πίνακα πρέπει να αποδοθεί με ειδική μορφοποίηση. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | Καθορίζει εάν η πρώτη σειρά του πίνακα πρέπει να αποδοθεί με ειδική μορφοποίηση. |
| [getFirstCol()](#getFirstCol--) | Καθορίζει εάν η πρώτη στήλη του πίνακα πρέπει να αποδοθεί με ειδική μορφοποίηση. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | Καθορίζει εάν η πρώτη στήλη του πίνακα πρέπει να αποδοθεί με ειδική μορφοποίηση. |
| [getLastRow()](#getLastRow--) | Καθορίζει εάν η τελευταία σειρά του πίνακα πρέπει να αποδοθεί με ειδική μορφοποίηση. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | Καθορίζει εάν η τελευταία σειρά του πίνακα πρέπει να αποδοθεί με ειδική μορφοποίηση. |
| [getLastCol()](#getLastCol--) | Καθορίζει εάν η τελευταία στήλη του πίνακα πρέπει να αποδοθεί με ειδική μορφοποίηση. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | Καθορίζει εάν η τελευταία στήλη του πίνακα πρέπει να αποδοθεί με ειδική μορφοποίηση. |
| [getHorizontalBanding()](#getHorizontalBanding--) | Καθορίζει εάν οι ζυγές σειρές πρέπει να αποδοθούν με διαφορετική μορφοποίηση. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | Καθορίζει εάν οι ζυγές σειρές πρέπει να αποδοθούν με διαφορετική μορφοποίηση. |
| [getVerticalBanding()](#getVerticalBanding--) | Καθορίζει εάν οι ζυγές στήλες πρέπει να αποδοθούν με διαφορετική μορφοποίηση. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | Καθορίζει εάν οι ζυγές στήλες πρέπει να αποδοθούν με διαφορετική μορφοποίηση. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Συγχωνεύει γειτονικά κελιά. |
### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public abstract ICell get_Item(int columnIndex, int rowIndex)
```

Επιστρέφει το κελί στους καθορισμένους δείκτες στήλης και σειράς. Μόνο ανάγνωση [ICell](../../com.aspose.slides/icell).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Επιστροφή:**
[ICell](../../com.aspose.slides/icell)
### getRows() {#getRows--}
```
public abstract IRowCollection getRows()
```

Επιστρέφει τη συλλογή των σειρών. Μόνο ανάγνωση [IRowCollection](../../com.aspose.slides/irowcollection).

**Επιστροφή:**
[IRowCollection](../../com.aspose.slides/irowcollection)
### getColumns() {#getColumns--}
```
public abstract IColumnCollection getColumns()
```

Επιστρέφει τη συλλογή των στηλών. Μόνο ανάγνωση [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Επιστροφή:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)
### getTableFormat() {#getTableFormat--}
```
public abstract ITableFormat getTableFormat()
```

Επιστρέφει το αντικείμενο TableFormat που περιέχει τις ιδιότητες μορφοποίησης για αυτόν τον πίνακα. Μόνο ανάγνωση [ITableFormat](../../com.aspose.slides/itableformat).

**Επιστροφή:**
[ITableFormat](../../com.aspose.slides/itableformat)
### getStylePreset() {#getStylePreset--}
```
public abstract int getStylePreset()
```

Ανακτά ή ορίζει το ενσωματωμένο στυλ πίνακα. Ανάγνωση/εγγραφή [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Επιστροφή:**
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

Καθορίζει εάν ο πίνακας έχει σειρά ανάγνωσης από δεξιά προς αριστερά. Μεταβλητή boolean ανάγνωση-εγγραφή.

**Επιστροφή:**
boolean
### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public abstract void setRightToLeft(boolean value)
```

Καθορίζει εάν ο πίνακας έχει σειρά ανάγνωσης από δεξιά προς αριστερά. Μεταβλητή boolean ανάγνωση-εγγραφή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getFirstRow() {#getFirstRow--}
```
public abstract boolean getFirstRow()
```

Καθορίζει εάν η πρώτη σειρά του πίνακα πρέπει να αποδοθεί με ειδική μορφοποίηση. Μεταβλητή boolean ανάγνωση-εγγραφή.

**Επιστροφή:**
boolean
### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public abstract void setFirstRow(boolean value)
```

Καθορίζει εάν η πρώτη σειρά του πίνακα πρέπει να αποδοθεί με ειδική μορφοποίηση. Μεταβλητή boolean ανάγνωση-εγγραφή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getFirstCol() {#getFirstCol--}
```
public abstract boolean getFirstCol()
```

Καθορίζει εάν η πρώτη στήλη του πίνακα πρέπει να αποδοθεί με ειδική μορφοποίηση. Μεταβλητή boolean ανάγνωση-εγγραφή.

**Επιστροφή:**
boolean
### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public abstract void setFirstCol(boolean value)
```

Καθορίζει εάν η πρώτη στήλη του πίνακα πρέπει να αποδοθεί με ειδική μορφοποίηση. Μεταβλητή boolean ανάγνωση-εγγραφή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getLastRow() {#getLastRow--}
```
public abstract boolean getLastRow()
```

Καθορίζει εάν η τελευταία σειρά του πίνακα πρέπει να αποδοθεί με ειδική μορφοποίηση. Μεταβλητή boolean ανάγνωση-εγγραφή.

**Επιστροφή:**
boolean
### setLastRow(boolean value) {#setLastRow-boolean-}
```
public abstract void setLastRow(boolean value)
```

Καθορίζει εάν η τελευταία σειρά του πίνακα πρέπει να αποδοθεί με ειδική μορφοποίηση. Μεταβλητή boolean ανάγνωση-εγγραφή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getLastCol() {#getLastCol--}
```
public abstract boolean getLastCol()
```

Καθορίζει εάν η τελευταία στήλη του πίνακα πρέπει να αποδοθεί με ειδική μορφοποίηση. Μεταβλητή boolean ανάγνωση-εγγραφή.

**Επιστροφή:**
boolean
### setLastCol(boolean value) {#setLastCol-boolean-}
```
public abstract void setLastCol(boolean value)
```

Καθορίζει εάν η τελευταία στήλη του πίνακα πρέπει να αποδοθεί με ειδική μορφοποίηση. Μεταβλητή boolean ανάγνωση-εγγραφή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getHorizontalBanding() {#getHorizontalBanding--}
```
public abstract boolean getHorizontalBanding()
```

Καθορίζει εάν οι ζυγές σειρές πρέπει να αποδοθούν με διαφορετική μορφοποίηση. Μεταβλητή boolean ανάγνωση-εγγραφή.

**Επιστροφή:**
boolean
### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public abstract void setHorizontalBanding(boolean value)
```

Καθορίζει εάν οι ζυγές σειρές πρέπει να αποδοθούν με διαφορετική μορφοποίηση. Μεταβλητή boolean ανάγνωση-εγγραφή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBanding() {#getVerticalBanding--}
```
public abstract boolean getVerticalBanding()
```

Καθορίζει εάν οι ζυγές στήλες πρέπει να αποδοθούν με διαφορετική μορφοποίηση. Μεταβλητή boolean ανάγνωση-εγγραφή.

**Επιστροφή:**
boolean
### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public abstract void setVerticalBanding(boolean value)
```

Καθορίζει εάν οι ζυγές στήλες πρέπει να αποδοθούν με διαφορετική μορφοποίηση. Μεταβλητή boolean ανάγνωση-εγγραφή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public abstract ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

Συγχωνεύει γειτονικά κελιά.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | Κελί για συγχώνευση. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Κελί για συγχώνευση. |
| allowSplitting | boolean | Αληθές για να επιτρέπεται ο διαχωρισμός κελιών. |

**Επιστροφή:**
[ICell](../../com.aspose.slides/icell) - Συγχωνευμένο κελί.