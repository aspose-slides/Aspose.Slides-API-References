---
title: MathMatrix
second_title: Αναφορά API του Aspose.Slides για Java
description: Καθορίζει το αντικείμενο Matrix που αποτελείται από θυγατρικά στοιχεία τοποθετημένα σε μία ή περισσότερες γραμμές και στήλες.
type: docs
url: /el/com.aspose.slides/mathmatrix/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**All Implemented Interfaces:**
[com.aspose.slides.IMathMatrix](../../com.aspose.slides/imathmatrix), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathMatrix extends MathElementBase implements IMathMatrix, IHasControlCharacterProperties
```

Καθορίζει το αντικείμενο Matrix, το οποίο αποτελείται από θυγατρικά στοιχεία οργανωμένα σε μία ή περισσότερες γραμμές και στήλες. Αξίζει να σημειωθεί ότι οι πίνακες δεν έχουν ενσωματωμένους ορίστες. Για να τοποθετήσετε τον πίνακα σε αγκύλες πρέπει να χρησιμοποιήσετε το αντικείμενο delimiter (IMathDelimiter). Μπορούν να χρησιμοποιηθούν null ορίσματα για τη δημιουργία κενών σε πίνακες.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Κατασκευαστές

| Constructor | Description |
| --- | --- |
| [MathMatrix(int rowCount, int columnCount)](#MathMatrix-int-int-) | Αρχικοποιεί ένα νέο αντίγραφο της κλάσης MathMatrix. |
## Μέθοδοι

| Method | Description |
| --- | --- |
| [getRowCount()](#getRowCount--) | Αριθμός γραμμών του πίνακα |
| [getColumnCount()](#getColumnCount--) | Αριθμός στηλών του πίνακα |
| [getHidePlaceholders()](#getHidePlaceholders--) | Απόκρυψη των δεικτών θέση για κενά στοιχεία του πίνακα Προεπιλογή: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Απόκρυψη των δεικτών θέση για κενά στοιχεία του πίνακα Προεπιλογή: false |
| [getBaseJustification()](#getBaseJustification--) | Καθορίζει την κατακόρυφη στοίχιση σε σχέση με το περιβάλλον κείμενο. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Καθορίζει την κατακόρυφη στοίχιση σε σχέση με το περιβάλλον κείμενο. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Ελάχιστο πλάτος στήλης σε twips (1/20 του σημείου) Το διάστημα του κενών (επίσης αναφέρεται ως \\u201cColumn Gap\\u201d ή \\u201cGap Width\\u201d) προστίθεται στο MinColumnWidth για να καθορίσει το σύνολο της απόστασης στηλών του Matrix (απόσταση μεταξύ των ίδιων άκρων διαφορετικών στηλών). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Ελάχιστο πλάτος στήλης σε twips (1/20 του σημείου) Το διάστημα του κενών (επίσης αναφέρεται ως \\u201cColumn Gap\\u201d ή \\u201cGap Width\\u201d) προστίθεται στο MinColumnWidth για να καθορίσει το σύνολο της απόστασης στηλών του Matrix (απόσταση μεταξύ των ίδιων άκρων διαφορετικών στηλών). |
| [getColumnGapRule()](#getColumnGapRule--) | Ο τύπος της οριζόντιας απόστασης μεταξύ των στηλών ενός πίνακα· Οι μονάδες οριζόντιας απόστασης μπορούν να είναι ems ή points (αποθηκευμένες ως twips). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | Ο τύπος της οριζόντιας απόστασης μεταξύ των στηλών ενός πίνακα· Οι μονάδες οριζόντιας απόστασης μπορούν να είναι ems ή points (αποθηκευμένες ως twips). |
| [getColumnGap()](#getColumnGap--) | Η τιμή της οριζόντιας απόστασης μεταξύ των στηλών ενός πίνακα· Εάν το ColumnGapRule είναι ορισμένο σε 3 (\"Exactly\"), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου)· Εάν είναι ορισμένο σε 4 (\"Multiple\"), η μονάδα ερμηνεύεται ως αριθμός 0.5 em βημάτων. |
| [setColumnGap(long value)](#setColumnGap-long-) | Η τιμή της οριζόντιας απόστασης μεταξύ των στηλών ενός πίνακα· Εάν το ColumnGapRule είναι ορισμένο σε 3 (\"Exactly\"), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου)· Εάν είναι ορισμένο σε 4 (\"Multiple\"), η μονάδα ερμηνεύεται ως αριθμός 0.5 em βημάτων. |
| [getRowGapRule()](#getRowGapRule--) | Ο τύπος της κάθετης απόστασης μεταξύ των γραμμών ενός πίνακα· Οι μονάδες κάθετης απόστασης μπορούν να είναι γραμμές ή points (αποθηκευμένες ως twips). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | Ο τύπος της κάθετης απόστασης μεταξύ των γραμμών ενός πίνακα· Οι μονάδες κάθετης απόστασης μπορούν να είναι γραμμές ή points (αποθηκευμένες ως twips). |
| [getRowGap()](#getRowGap--) | Η τιμή της κάθετης απόστασης μεταξύ των γραμμών ενός πίνακα· Εάν το RowGapRule είναι ορισμένο σε 3 (\"Exactly\"), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου)· Εάν είναι ορισμένο σε 4 (\"Multiple\"), η μονάδα ερμηνεύεται ως μισές γραμμές. |
| [setRowGap(long value)](#setRowGap-long-) | Η τιμή της κάθετης απόστασης μεταξύ των γραμμών ενός πίνακα· Εάν το RowGapRule είναι ορισμένο σε 3 (\"Exactly\"), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου)· Εάν είναι ορισμένο σε 4 (\"Multiple\"), η μονάδα ερμηνεύεται ως μισές γραμμές. |
| [get_Item(int row, int column)](#get-Item-int-int-) | Στοιχείο του πίνακα |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Στοιχείο του πίνακα |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Ιδιότητες χαρακτήρα ελέγχου |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Λαμβάνει την οριζόντια στοίχιση της καθορισμένης στήλης |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Ορίζει την οριζόντια στοίχιση της καθορισμένης στήλης |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Ορίζει την οριζόντια στοίχιση των καθορισμένων στηλών |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Εισάγει μια νέα γραμμή πριν από την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα γραμμή είναι null. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Εισάγει μια νέα γραμμή μετά από την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα γραμμή είναι null. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Διαγράφει τη συγκεκριμένη γραμμή |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Εισάγει μια νέα στήλη πριν από την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα στήλη είναι null. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Εισάγει μια νέα στήλη μετά από την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα στήλη είναι null. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Διαγράφει τη συγκεκριμένη στήλη |
| [getChildren()](#getChildren--) | Λαμβάνει τα θυγατρικά στοιχεία |
### MathMatrix(int rowCount, int columnCount) {#MathMatrix-int-int-}
```
public MathMatrix(int rowCount, int columnCount)
```


Αρχικοποιεί ένα νέο αντίγραφο της κλάσης MathMatrix.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
> ```

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| rowCount | int | αριθμός γραμμών |
| columnCount | int | αριθμός στηλών |

### getRowCount() {#getRowCount--}
```
public final int getRowCount()
```


Αριθμός γραμμών του πίνακα

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


Αριθμός στηλών του πίνακα

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


Απόκρυψη των δεικτών θέση για κενά στοιχεία του πίνακα Προεπιλογή: false

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


Απόκρυψη των δεικτών θέση για κενά στοιχεία του πίνακα Προεπιλογή: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```


Καθορίζει την κατακόρυφη στοίχιση σε σχέση με το περιβάλλον κείμενο. Πιθανές τιμές είναι top, bottom, και center. Προεπιλογή: Center

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


Καθορίζει την κατακόρυφη στοίχιση σε σχέση με το περιβάλλον κείμενο. Πιθανές τιμές είναι top, bottom, και center. Προεπιλογή: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMinColumnWidth() {#getMinColumnWidth--}
```
public final long getMinColumnWidth()
```


Ελάχιστο πλάτος στήλης σε twips (1/20 του σημείου) Το διάστημα του κενών (επίσης αναφέρεται ως \\u201cColumn Gap\\u201d ή \\u201cGap Width\\u201d) προστίθεται στο MinColumnWidth για να καθορίσει το σύνολο της απόστασης στηλών του Matrix (απόσταση μεταξύ των ίδιων άκρων διαφορετικών στηλών). Προεπιλογή: 0.

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


Ελάχιστο πλάτος στήλης σε twips (1/20 του σημείου) Το διάστημα του κενών (επίσης αναφέρεται ως \\u201cColumn Gap\\u201d ή \\u201cGap Width\\u201d) προστίθεται στο MinColumnWidth για να καθορίσει το σύνολο της απόστασης στηλών του Matrix (απόσταση μεταξύ των ίδιων άκρων διαφορετικών στηλών). Προεπιλογή: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getColumnGapRule() {#getColumnGapRule--}
```
public final int getColumnGapRule()
```


Ο τύπος της οριζόντιας απόστασης μεταξύ των στηλών ενός πίνακα· Οι μονάδες οριζόντιας απόστασης μπορούν να είναι ems ή points (αποθηκευμένες ως twips). Προεπιλογή: SingleSpacingGap (0)

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


Ο τύπος της οριζόντιας απόστασης μεταξύ των στηλών ενός πίνακα· Οι μονάδες οριζόντιας απόστασης μπορούν να είναι ems ή points (αποθηκευμένες ως twips). Προεπιλογή: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getColumnGap() {#getColumnGap--}
```
public final long getColumnGap()
```


Η τιμή της οριζόντιας απόστασης μεταξύ των στηλών ενός πίνακα· Εάν το ColumnGapRule είναι ορισμένο σε 3 (\"Exactly\"), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου)· Εάν είναι ορισμένο σε 4 (\"Multiple\"), η μονάδα ερμηνεύεται ως αριθμός 0.5 em βημάτων. Σε άλλες περιπτώσεις αγνοείται. Προεπιλογή: 0

--------------------

> ```
> Παράδειγμα:
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


Η τιμή της οριζόντιας απόστασης μεταξύ των στηλών ενός πίνακα· Εάν το ColumnGapRule είναι ορισμένο σε 3 (\"Exactly\"), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου)· Εάν είναι ορισμένο σε 4 (\"Multiple\"), η μονάδα ερμηνεύεται ως αριθμός 0.5 em βημάτων. Σε άλλες περιπτώσεις αγνοείται. Προεπιλογή: 0

--------------------

> ```
> Παράδειγμα:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getRowGapRule() {#getRowGapRule--}
```
public final int getRowGapRule()
```


Ο τύπος της κάθετης απόστασης μεταξύ των γραμμών ενός πίνακα· Οι μονάδες κάθετης απόστασης μπορούν να είναι γραμμές ή points (αποθηκευμένες ως twips). Προεπιλογή: SingleSpacingGap (0)

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


Ο τύπος της κάθετης απόστασης μεταξύ των γραμμών ενός πίνακα· Οι μονάδες κάθετης απόστασης μπορούν να είναι γραμμές ή points (αποθηκευμένες ως twips). Προεπιλογή: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRowGap() {#getRowGap--}
```
public final long getRowGap()
```


Η τιμή της κάθετης απόστασης μεταξύ των γραμμών ενός πίνακα· Εάν το RowGapRule είναι ορισμένο σε 3 (\"Exactly\"), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου)· Εάν είναι ορισμένο σε 4 (\"Multiple\"), η μονάδα ερμηνεύεται ως μισές γραμμές. Προεπιλογή: 0

--------------------

> ```
> Παράδειγμα:
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


Η τιμή της κάθετης απόστασης μεταξύ των γραμμών ενός πίνακα· Εάν το RowGapRule είναι ορισμένο σε 3 (\"Exactly\"), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου)· Εάν είναι ορισμένο σε 4 (\"Multiple\"), η μονάδα ερμηνεύεται ως μισές γραμμές. Προεπιλογή: 0

--------------------

> ```
> Παράδειγμα:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public final IMathElement get_Item(int row, int column)
```


Στοιχείο του πίνακα

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| row | int | Ο δείκτης μηδενικής βάσης της γραμμής για λήψη στοιχείου |
| column | int | Ο δείκτης μηδενικής βάσης της στήλης για λήψη στοιχείου |

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int row, int column, IMathElement value)
```


Στοιχείο του πίνακα

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| row | int | Ο δείκτης μηδενικής βάσης της γραμμής για λήψη στοιχείου |
| column | int | Ο δείκτης μηδενικής βάσης της στήλης για λήψη στοιχείου |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Ιδιότητες χαρακτήρα ελέγχου

**Επιστρέφει:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public final int getColumnAlignment(int columnIndex)
```


Λαμβάνει την οριζόντια στοίχιση της καθορισμένης στήλης

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | Δείκτης μηδενικής βάσης στήλης |

**Επιστρέφει:**
int - Οριζόντια Στοίχιση της καθορισμένης στήλης
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public final void setColumnAlignment(int columnIndex, int val)
```


Ορίζει την οριζόντια στοίχιση της καθορισμένης στήλης

--------------------

> ```
> Παράδειγμα:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | Δείκτης μηδενικής βάσης στήλης |
| val | int | Νέα τιμή της οριζόντιας στοίχισης της καθορισμένης στήλης |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public final void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```


Ορίζει την οριζόντια στοίχιση των καθορισμένων στηλών

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | Δείκτης μηδενικής βάσης της πρώτης στήλης για ορισμό στοίχισης |
| columnsCount | long | Αριθμός στηλών για καθορισμό της στοίχισης |
| val | int | Νέα τιμή της οριζόντιας στοίχισης της καθορισμένης στήλης |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public final void insertRowBefore(int rowIndex)
```


Εισάγει μια νέα γραμμή πριν από την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα γραμμή είναι null.

--------------------

> ```
> Παράδειγμα:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| rowIndex | int | Δείκτης της γραμμής πριν από την οποία θα εισαχθεί μια καινούρια |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public final void insertRowAfter(int rowIndex)
```


Εισάγει μια νέα γραμμή μετά από την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα γραμμή είναι null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| rowIndex | int | Δείκτης της γραμμής μετά από την οποία θα εισαχθεί μια καινούρια |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public final void deleteRow(int rowIndex)
```


Διαγράφει τη συγκεκριμένη γραμμή

--------------------

> ```
> Παράδειγμα:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| rowIndex | int | Ο μηδενικός δείκτης της γραμμής για διαγραφή. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public final void insertColumnBefore(int columnIndex)
```


Εισάγει μια νέα στήλη πριν από την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα στήλη είναι null.

--------------------

> ```
> Παράδειγμα:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | Δείκτης της στήλης πριν από την οποία θα εισαχθεί μια καινούρια |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public final void insertColumnAfter(int columnIndex)
```


Εισάγει μια νέα στήλη μετά από την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα στήλη είναι null.

--------------------

> ```
> Παράδειγμα:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | Δείκτης της στήλης μετά από την οποία θα εισαχθεί μια καινούρια |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public final void deleteColumn(int columnIndex)
```


Διαγράφει τη συγκεκριμένη στήλη

--------------------

> ```
> Παράδειγμα:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```


**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | Ο μηδενικός δείκτης της στήλης για διαγραφή. |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Λαμβάνει τα θυγατρικά στοιχεία

**Επιστρέφει:**
com.aspose.slides.IMathElement[]