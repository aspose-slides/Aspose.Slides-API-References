---
title: Table
second_title: Aspose.Slides για την Αναφορά API της Java
description: Αντιπροσωπεύει έναν πίνακα σε μια διαφάνεια.
type: docs
url: /el/com.aspose.slides/table/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.ITable](../../com.aspose.slides/itable)
```
public final class Table extends GraphicalObject implements ITable
```

Αντιπροσωπεύει έναν πίνακα σε μια διαφάνεια.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Επιστρέφει το κελί στις καθορισμένες ευρετήρια στήλης και γραμμής. |
| [getRows()](#getRows--) | Επιστρέφει τη συλλογή των γραμμών. |
| [getColumns()](#getColumns--) | Επιστρέφει τη συλλογή των στήλων. |
| [getTableFormat()](#getTableFormat--) | Επιστρέφει το αντικείμενο TableFormat που περιέχει τις ιδιότητες μορφοποίησης για αυτόν τον πίνακα. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Συγχωνεύει γειτονικά κελιά. |
| [getStylePreset()](#getStylePreset--) | Αποκτά ή ορίζει ενσωματωμένο στυλ πίνακα. |
| [setStylePreset(int value)](#setStylePreset-int-) | Αποκτά ή ορίζει ενσωματωμένο στυλ πίνακα. |
| [getRightToLeft()](#getRightToLeft--) | Καθορίζει αν ο πίνακας έχει φορά ανάγνωσης από δεξιά προς τα αριστερά. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Καθορίζει αν ο πίνακας έχει φορά ανάγνωσης από δεξιά προς τα αριστερά. |
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
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Ορίζει τις καθορισμένες ιδιότητες μορφοποίησης τμημάτων σε όλα τα τμήματα των κελιών του πίνακα. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Ορίζει τις καθορισμένες ιδιότητες μορφοποίησης παραγράφων σε όλα τα παραγράφοι των κελιών του πίνακα. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Ορίζει τις καθορισμένες ιδιότητες μορφοποίησης πλαισίων κειμένου σε όλα τα πλαίσια κειμένου των κελιών του πίνακα. |
| [getFillFormat()](#getFillFormat--) | Επιστρέφει ένα αντικείμενο TableFormat.FillFormat που περιέχει τη μορφοποίηση γεμίσματος για τον Πίνακα. |
### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public final ICell get_Item(int columnIndex, int rowIndex)
```

Επιστρέφει το κελί στις καθορισμένες ευρετήρια στήλης και γραμμής. Μόνο ανάγνωση [Cell](../../com.aspose.slides/cell).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Τιμή επιστροφής:**
[ICell](../../com.aspose.slides/icell)
### getRows() {#getRows--}
```
public final IRowCollection getRows()
```

Επιστρέφει τη συλλογή των γραμμών. Μόνο ανάγνωση [IRowCollection](../../com.aspose.slides/irowcollection).

**Τιμή επιστροφής:**
[IRowCollection](../../com.aspose.slides/irowcollection)
### getColumns() {#getColumns--}
```
public final IColumnCollection getColumns()
```

Επιστρέφει τη συλλογή των στήλων. Μόνο ανάγνωση [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Τιμή επιστροφής:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)
### getTableFormat() {#getTableFormat--}
```
public final ITableFormat getTableFormat()
```

Επιστρέφει το αντικείμενο TableFormat που περιέχει τις ιδιότητες μορφοποίησης για αυτόν τον πίνακα. Μόνο ανάγνωση [ITableFormat](../../com.aspose.slides/itableformat).

**Τιμή επιστροφής:**
[ITableFormat](../../com.aspose.slides/itableformat)
### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public final ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

Συγχωνεύει γειτονικά κελιά.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | Κελίδιο προς συγχώνευση. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Κελίδιο προς συγχώνευση. |
| allowSplitting | boolean | True για να επιτρέπεται ο διαχωρισμός των κελιών. |

**Τιμή επιστροφής:**
[ICell](../../com.aspose.slides/icell) - Συγχωνευμένο κελί.
### getStylePreset() {#getStylePreset--}
```
public final int getStylePreset()
```

Αποκτά ή ορίζει ενσωματωμένο στυλ πίνακα. Ανάγνωση/Εγγραφή [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Τιμή επιστροφής:**
int
### setStylePreset(int value) {#setStylePreset-int-}
```
public final void setStylePreset(int value)
```

Αποκτά ή ορίζει ενσωματωμένο στυλ πίνακα. Ανάγνωση/Εγγραφή [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getRightToLeft() {#getRightToLeft--}
```
public final boolean getRightToLeft()
```

Καθορίζει αν ο πίνακας έχει φορά ανάγνωσης από δεξιά προς τα αριστερά. Ανάγνωση/Εγγραφή  boolean .

**Τιμή επιστροφής:**
boolean
### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public final void setRightToLeft(boolean value)
```

Καθορίζει αν ο πίνακας έχει φορά ανάγνωσης από δεξιά προς τα αριστερά. Ανάγνωση/Εγγραφή  boolean .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getFirstRow() {#getFirstRow--}
```
public final boolean getFirstRow()
```

Καθορίζει αν η πρώτη γραμμή ενός πίνακα πρέπει να σχεδιαστεί με ειδική μορφοποίηση. Ανάγνωση/Εγγραφή  boolean .

**Τιμή επιστροφής:**
boolean
### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public final void setFirstRow(boolean value)
```

Καθορίζει αν η πρώτη γραμμή ενός πίνακα πρέπει να σχεδιαστεί με ειδική μορφοποίηση. Ανάγνωση/Εγγραφή  boolean .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getFirstCol() {#getFirstCol--}
```
public final boolean getFirstCol()
```

Καθορίζει αν η πρώτη στήλη ενός πίνακα πρέπει να σχεδιαστεί με ειδική μορφοποίηση. Ανάγνωση/Εγγραφή  boolean .

**Τιμή επιστροφής:**
boolean
### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public final void setFirstCol(boolean value)
```

Καθορίζει αν η πρώτη στήλη ενός πίνακα πρέπει να σχεδιαστεί με ειδική μορφοποίηση. Ανάγνωση/Εγγραφή  boolean .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getLastRow() {#getLastRow--}
```
public final boolean getLastRow()
```

Καθορίζει αν η τελευταία γραμμή ενός πίνακα πρέπει να σχεδιαστεί με ειδική μορφοποίηση. Ανάγνωση/Εγγραφή  boolean .

**Τιμή επιστροφής:**
boolean
### setLastRow(boolean value) {#setLastRow-boolean-}
```
public final void setLastRow(boolean value)
```

Καθορίζει αν η τελευταία γραμμή ενός πίνακα πρέπει να σχεδιαστεί με ειδική μορφοποίηση. Ανάγνωση/Εγγραφή  boolean .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getLastCol() {#getLastCol--}
```
public final boolean getLastCol()
```

Καθορίζει αν η τελευταία στήλη ενός πίνακα πρέπει να σχεδιαστεί με ειδική μορφοποίηση. Ανάγνωση/Εγγραφή  boolean .

**Τιμή επιστροφής:**
boolean
### setLastCol(boolean value) {#setLastCol-boolean-}
```
public final void setLastCol(boolean value)
```

Καθορίζει αν η τελευταία στήλη ενός πίνακα πρέπει να σχεδιαστεί με ειδική μορφοποίηση. Ανάγνωση/Εγγραφή  boolean .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getHorizontalBanding() {#getHorizontalBanding--}
```
public final boolean getHorizontalBanding()
```

Καθορίζει αν οι ζυγές γραμμές πρέπει να σχεδιαστούν με διαφορετική μορφοποίηση. Ανάγνωση/Εγγραφή  boolean .

**Τιμή επιστροφής:**
boolean
### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public final void setHorizontalBanding(boolean value)
```

Καθορίζει αν οι ζυγές γραμμές πρέπει να σχεδιαστούν με διαφορετική μορφοποίηση. Ανάγνωση/Εγγραφή  boolean .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBanding() {#getVerticalBanding--}
```
public final boolean getVerticalBanding()
```

Καθορίζει αν οι ζυγές στήλες πρέπει να σχεδιαστούν με διαφορετική μορφοποίηση. Ανάγνωση/Εγγραφή  boolean .

**Τιμή επιστροφής:**
boolean
### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public final void setVerticalBanding(boolean value)
```

Καθορίζει αν οι ζυγές στήλες πρέπει να σχεδιαστούν με διαφορετική μορφοποίηση. Ανάγνωση/Εγγραφή  boolean .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Ορίζει τις καθορισμένες ιδιότητες μορφοποίησης τμημάτων σε όλα τα τμήματα των κελιών του πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | Αντικείμενο IPortionFormat με τις απαιτούμενες ιδιότητες ορισμένες. |
### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Ορίζει τις καθορισμένες ιδιότητες μορφοποίησης παραγράφων σε όλα τα παραγράφοι των κελιών του πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | Αντικείμενο IParagraphFormat με τις απαιτούμενες ιδιότητες ορισμένες. |
### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

Ορίζει τις καθορισμένες ιδιότητες μορφοποίησης πλαισίων κειμένου σε όλα τα πλαίσια κειμένου των κελιών του πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | Αντικείμενο ITextFrameFormat με τις απαιτούμενες ιδιότητες ορισμένες. |
### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

Επιστρέφει ένα αντικείμενο TableFormat.FillFormat που περιέχει τη μορφοποίηση γεμίσματος για τον Πίνακα. Μόνο ανάγνωση [IFillFormat](../../com.aspose.slides/ifillformat).

**Τιμή επιστροφής:**
[IFillFormat](../../com.aspose.slides/ifillformat)