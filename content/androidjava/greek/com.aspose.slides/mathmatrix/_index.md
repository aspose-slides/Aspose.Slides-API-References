---
title: MathMatrix
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Καθορίζει το αντικείμενο Matrix, αποτελούμενο από στοιχεία παιδιών διατεταγμένα σε μία ή περισσότερες γραμμές και στήλες.
type: docs
url: /el/com.aspose.slides/mathmatrix/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMathMatrix](../../com.aspose.slides/imathmatrix), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathMatrix extends MathElementBase implements IMathMatrix, IHasControlCharacterProperties
```

Καθορίζει το αντικείμενο Matrix, που αποτελείται από στοιχεία-παιδιά διατεταγμένα σε μία ή περισσότερες γραμμές και στήλες. Είναι σημαντικό να σημειωθεί ότι οι μήτρες δεν έχουν ενσωματωμένους οριοθέτες. Για να τοποθετήσετε τη μήτρα στις αγκύλες, πρέπει να χρησιμοποιήσετε το αντικείμενο οριοθέτη (IMathDelimiter). Μπορούν να χρησιμοποιηθούν null ορίσματα για τη δημιουργία κενών στη μήτρα.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MathMatrix(int rowCount, int columnCount)](#MathMatrix-int-int-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης MathMatrix. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getRowCount()](#getRowCount--) | Αριθμός γραμμών στη μήτρα |
| [getColumnCount()](#getColumnCount--) | Αριθμός στηλών στη μήτρα |
| [getHidePlaceholders()](#getHidePlaceholders--) | Απόκρυψη των εικονικών χαρακτήρων για κενά στοιχεία της μήτρας Προεπιλογή: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Απόκρυψη των εικονικών χαρακτήρων για κενά στοιχεία της μήτρας Προεπιλογή: false |
| [getBaseJustification()](#getBaseJustification--) | Καθορίζει την κατακόρυφη στοίχιση σε σχέση με το περιβάλλον κείμενο. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Καθορίζει την κατακόρυφη στοίχιση σε σχέση με το περιβάλλον κείμενο. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Ελάχιστο πλάτος στήλης σε twips (1/20 του σημείου). Το διάστημα κενού (επίσης αναφέρεται ως “Column Gap” ή “Gap Width”) προστίθεται στο MinColumnWidth για τον καθορισμό του συνολικού Matrix Column Spacing (απόσταση μεταξύ των ίδιας άκτης διαφορετικών στηλών). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Ελάχιστο πλάτος στήλης σε twips (1/20 του σημείου). Το διάστημα κενού (επίσης αναφέρεται ως “Column Gap” ή “Gap Width”) προστίθεται στο MinColumnWidth για τον καθορισμό του συνολικού Matrix Column Spacing (απόσταση μεταξύ των ίδιας άκτης διαφορετικών στηλών). |
| [getColumnGapRule()](#getColumnGapRule--) | Ο τύπος του οριζόντιου διαστήματος μεταξύ στηλών μιας μήτρας· Οι μονάδες οριζόντιου διαστήματος μπορούν να είναι ems ή points (αποθηκευμένα ως twips). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | Ο τύπος του οριζόντιου διαστήματος μεταξύ στηλών μιας μήτρας· Οι μονάδες οριζόντιου διαστήματος μπορούν να είναι ems ή points (αποθηκευμένα ως twips). |
| [getColumnGap()](#getColumnGap--) | Η τιμή του οριζόντιου διαστήματος μεταξύ στηλών μιας μήτρας· Αν το ColumnGapRule είναι 3 (“Exactly”), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου). Αν το ColumnGapRule είναι 4 (“Multiple”), η μονάδα ερμηνεύεται ως αριθμός 0.5 em βήμαι. |
| [setColumnGap(long value)](#setColumnGap-long-) | Η τιμή του οριζόντιου διαστήματος μεταξύ στηλών μιας μήτρας· Αν το ColumnGapRule είναι 3 (“Exactly”), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου). Αν το ColumnGapRule είναι 4 (“Multiple”), η μονάδα ερμηνεύεται ως αριθμός 0.5 em βήμαι. |
| [getRowGapRule()](#getRowGapRule--) | Ο τύπος του κατακόρυφου διαστήματος μεταξύ γραμμών μιας μήτρας· Οι μονάδες κατακόρυφου διαστήματος μπορούν να είναι lines ή points (αποθηκευμένα ως twips). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | Ο τύπος του κατακόρυφου διαστήματος μεταξύ γραμμών μιας μήτρας· Οι μονάδες κατακόρυφου διαστήματος μπορούν να είναι lines ή points (αποθηκευμένα ως twips). |
| [getRowGap()](#getRowGap--) | Η τιμή του κατακόρυφου διαστήματος μεταξύ γραμμών μιας μήτρας· Αν το RowGapRule είναι 3 (“Exactly”), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου). Αν το RowGapRule είναι 4 (“Multiple”), η μονάδα ερμηνεύεται ως μισές γραμμές. |
| [setRowGap(long value)](#setRowGap-long-) | Η τιμή του κατακόρυφου διαστήματος μεταξύ γραμμών μιας μήτρας· Αν το RowGapRule είναι 3 (“Exactly”), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου). Αν το RowGapRule είναι 4 (“Multiple”), η μονάδα ερμηνεύεται ως μισές γραμμές. |
| [get_Item(int row, int column)](#get-Item-int-int-) | Στοιχείο της μήτρας |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Στοιχείο της μήτρας |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Ιδιότητες Χαρακτήρων Ελέγχου |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Λάβετε την οριζόντια στοίχιση της καθορισμένης στήλης |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Ορίστε την οριζόντια στοίχιση της καθορισμένης στήλης |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Ορίστε την οριζόντια στοίχιση των καθορισμένων στηλών |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Εισαγωγή νέας γραμμής πριν από την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα γραμμή είναι null. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Εισαγωγή νέας γραμμής μετά από την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα γραμμή είναι null. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Διαγράφει την καθορισμένη γραμμή |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Εισαγωγή νέας στήλης πριν από την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα στήλη είναι null. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Εισαγωγή νέας στήλης μετά από την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα στήλη είναι null. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Διαγράφει την καθορισμένη στήλη |
| [getChildren()](#getChildren--) | Λάβετε τα στοιχεία παιδιών |
### MathMatrix(int rowCount, int columnCount) {#MathMatrix-int-int-}
```
public MathMatrix(int rowCount, int columnCount)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης MathMatrix.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rowCount | int | αριθμός γραμμών |
| columnCount | int | αριθμός στηλών |

### getRowCount() {#getRowCount--}
```
public final int getRowCount()
```


Αριθμός γραμμών στη μήτρα

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int rowCount = matrix.getRowCount();
> ```

**Επιστρέφει:**
int
### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```


Αριθμός στηλών στη μήτρα

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int columnCount = matrix.getColumnCount();
> ```

**Επιστρέφει:**
int
### getHidePlaceholders() {#getHidePlaceholders--}
```
public final boolean getHidePlaceholders()
```


Απόκρυψη των εικονικών χαρακτήρων για κενά στοιχεία της μήτρας Προεπιλογή: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Επιστρέφει:**
boolean
### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public final void setHidePlaceholders(boolean value)
```


Απόκρυψη των εικονικών χαρακτήρων για κενά στοιχεία της μήτρας Προεπιλογή: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```


Καθορίζει την κατακόρυφη στοίχιση σε σχέση με το περιβάλλον κείμενο. Πιθανές τιμές είναι top, bottom, and center. Προεπιλογή: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Επιστρέφει:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```


Καθορίζει την κατακόρυφη στοίχιση σε σχέση με το περιβάλλον κείμενο. Πιθανές τιμές είναι top, bottom, and center. Προεπιλογή: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getMinColumnWidth() {#getMinColumnWidth--}
```
public final long getMinColumnWidth()
```


Ελάχιστο πλάτος στήλης σε twips (1/20 του σημείου). Το διάστημα κενού (επίσης αναφέρεται ως “Column Gap” ή “Gap Width”) προστίθεται στο MinColumnWidth για τον καθορισμό του συνολικού Matrix Column Spacing (απόσταση μεταξύ των ίδιας άκτης διαφορετικών στηλών). Προεπιλογή: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Επιστρέφει:**
long
### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public final void setMinColumnWidth(long value)
```


Ελάχιστο πλάτος στήλης σε twips (1/20 του σημείου). Το διάστημα κενού (επίσης αναφέρεται ως “Column Gap” ή “Gap Width”) προστίθεται στο MinColumnWidth για τον καθορισμό του συνολικού Matrix Column Spacing (απόσταση μεταξύ των ίδιας άκτης διαφορετικών στηλών). Προεπιλογή: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | long |  |

### getColumnGapRule() {#getColumnGapRule--}
```
public final int getColumnGapRule()
```


Ο τύπος του οριζόντιου διαστήματος μεταξύ στηλών μιας μήτρας· Οι μονάδες οριζόντιου διαστήματος μπορούν να είναι ems ή points (αποθηκευμένα ως twips). Προεπιλογή: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Επιστρέφει:**
int
### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public final void setColumnGapRule(int value)
```


Ο τύπος του οριζόντιου διαστήματος μεταξύ στηλών μιας μήτρας· Οι μονάδες οριζόντιου διαστήματος μπορούν να είναι ems ή points (αποθηκευμένα ως twips). Προεπιλογή: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getColumnGap() {#getColumnGap--}
```
public final long getColumnGap()
```


Η τιμή του οριζόντιου διαστήματος μεταξύ στηλών μιας μήτρας· Αν το ColumnGapRule είναι 3 (“Exactly”), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου). Αν το ColumnGapRule είναι 4 (“Multiple”), η μονάδα ερμηνεύεται ως αριθμός 0.5 em βήμαι. Σε άλλες περιπτώσεις παραβλέπεται. Προεπιλογή: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Επιστρέφει:**
long
### setColumnGap(long value) {#setColumnGap-long-}
```
public final void setColumnGap(long value)
```


Η τιμή του οριζόντιου διαστήματος μεταξύ στηλών μιας μήτρας· Αν το ColumnGapRule είναι 3 (“Exactly”), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου). Αν το ColumnGapRule είναι 4 (“Multiple”), η μονάδα ερμηνεύεται ως αριθμός 0.5 em βήμαι. Σε άλλες περιπτώσεις παραβλέπεται. Προεπιλογή: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | long |  |

### getRowGapRule() {#getRowGapRule--}
```
public final int getRowGapRule()
```


Ο τύπος του κατακόρυφου διαστήματος μεταξύ γραμμών μιας μήτρας· Οι μονάδες κατακόρυφου διαστήματος μπορούν να είναι lines ή points (αποθηκευμένα ως twips). Προεπιλογή: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Επιστρέφει:**
int
### setRowGapRule(int value) {#setRowGapRule-int-}
```
public final void setRowGapRule(int value)
```


Ο τύπος του κατακόρυφου διαστήματος μεταξύ γραμμών μιας μήτρας· Οι μονάδες κατακόρυφου διαστήματος μπορούν να είναι lines ή points (αποθηκευμένα ως twips). Προεπιλογή: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getRowGap() {#getRowGap--}
```
public final long getRowGap()
```


Η τιμή του κατακόρυφου διαστήματος μεταξύ γραμμών μιας μήτρας· Αν το RowGapRule είναι 3 (“Exactly”), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου). Αν το RowGapRule είναι 4 (“Multiple”), η μονάδα ερμηνεύεται ως μισές γραμμές. Προεπιλογή: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Επιστρέφει:**
long
### setRowGap(long value) {#setRowGap-long-}
```
public final void setRowGap(long value)
```


Η τιμή του κατακόρυφου διαστήματος μεταξύ γραμμών μιας μήτρας· Αν το RowGapRule είναι 3 (“Exactly”), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου). Αν το RowGapRule είναι 4 (“Multiple”), η μονάδα ερμηνεύεται ως μισές γραμμές. Προεπιλογή: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | long |  |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public final IMathElement get_Item(int row, int column)
```


Στοιχείο της μήτρας

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| row | int | Ο μηδενικός δείκτης της γραμμής για λήψη στοιχείου |
| column | int | Ο μηδενικός δείκτης της στήλης για λήψη στοιχείου |

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int row, int column, IMathElement value)
```


Στοιχείο της μήτρας

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| row | int | Ο μηδενικός δείκτης της γραμμής για λήψη στοιχείου |
| column | int | Ο μηδενικός δείκτης της στήλης για λήψη στοιχείου |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Ιδιότητες Χαρακτήρων Ελέγχου

**Επιστρέφει:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public final int getColumnAlignment(int columnIndex)
```


Λάβετε την οριζόντια στοίχιση της καθορισμένης στήλης

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| columnIndex | int | Δείκτης στήλης μηδενικής βάσης |

**Επιστρέφει:**
int - Horizontal Alignment of specified column
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public final void setColumnAlignment(int columnIndex, int val)
```


Ορίστε την οριζόντια στοίχιση της καθορισμένης στήλης

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| columnIndex | int | Δείκτης στήλης μηδενικής βάσης |
| val | int | Νέα τιμή της οριζόντιας στοίχισης της καθορισμένης στήλης |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public final void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```


Ορίστε την οριζόντια στοίχιση των καθορισμένων στηλών

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| columnIndex | int | Μηδενικός δείκτης της πρώτης στήλης για ορισμό στοίχισης |
| columnsCount | long | Ο αριθμός των στηλών για τον καθορισμό της στοίχισης |
| val | int | Νέα τιμή της οριζόντιας στοίχισης της καθορισμένης στήλης |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public final void insertRowBefore(int rowIndex)
```


Εισαγωγή νέας γραμμής πριν από την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα γραμμή είναι null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rowIndex | int | Δείκτης της γραμμής πριν από την οποία θα εισαχθεί καινούρια |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public final void insertRowAfter(int rowIndex)
```


Εισαγωγή νέας γραμμής μετά από την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα γραμμή είναι null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rowIndex | int | Δείκτης της γραμμής μετά από την οποία θα εισαχθεί καινούρια |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public final void deleteRow(int rowIndex)
```


Διαγράφει την καθορισμένη γραμμή

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rowIndex | int | Ο μηδενικός δείκτης της γραμμής για διαγραφή. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public final void insertColumnBefore(int columnIndex)
```


Εισαγωγή νέας στήλης πριν από την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα στήλη είναι null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| columnIndex | int | Δείκτης της στήλης πριν από την οποία θα εισαχθεί καινούρια |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public final void insertColumnAfter(int columnIndex)
```


Εισαγωγή νέας στήλης μετά από την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα στήλη είναι null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| columnIndex | int | Δείκτης της στήλης μετά από την οποία θα εισαχθεί καινούρια |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public final void deleteColumn(int columnIndex)
```


Διαγράφει την καθορισμένη στήλη

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| columnIndex | int | Ο μηδενικός δείκτης της στήλης για διαγραφή. |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Λάβετε τα στοιχεία παιδιών

**Επιστρέφει:**
com.aspose.slides.IMathElement[]