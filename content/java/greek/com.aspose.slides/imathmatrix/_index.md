---
title: IMathMatrix
second_title: Αναφορά API του Aspose.Slides για Java
description: Καθορίζει το αντικείμενο Matrix που αποτελείται από στοιχεία-παιδιά τοποθετημένα σε μία ή περισσότερες σειρές και στήλες.
type: docs
url: /el/com.aspose.slides/imathmatrix/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathMatrix extends IMathElement
```

Καθορίζει το αντικείμενο Matrix, το οποίο αποτελείται από στοιχεία-παιδιά ταυτοποιημένα σε μία ή περισσότερες σειρές και στήλες. Είναι σημαντικό να σημειωθεί ότι τα πλέγματα δεν έχουν ενσωματωμένους οριοθετητές. Για να τοποθετήσετε το πλέγμα σε αγκύλες, πρέπει να χρησιμοποιήσετε το αντικείμενο οριοθέτη (IMathDelimiter). Μπορούν να χρησιμοποιηθούν null ορίσματα για τη δημιουργία κενών στα πλέγματα.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int row, int column)](#get-Item-int-int-) | Στοιχεία του πλέγματος |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Στοιχεία του πλέγματος |
| [getRowCount()](#getRowCount--) | Αριθμός σειρών στο πλέγμα |
| [getColumnCount()](#getColumnCount--) | Αριθμός στηλών στο πλέγμα |
| [getHidePlaceholders()](#getHidePlaceholders--) | Απόκρυψη των placeholders για κενά στοιχεία του πλέγματος Προεπιλογή: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Απόκρυψη των placeholders για κενά στοιχεία του πλέγματος Προεπιλογή: false |
| [getBaseJustification()](#getBaseJustification--) | Καθορίζει την κατακόρυφη στοίχιση σε σχέση με το περιβάλλον κείμενο. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Καθορίζει την κατακόρυφη στοίχιση σε σχέση με το περιβάλλον κείμενο. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Ελάχιστο πλάτος στήλης σε twips (1/20 του σημείου). Το διάστημα του κενού (επίσης αναφερόμενο ως \u201cColumn Gap\u201d ή \u201cGap Width\u201d) προστίθεται στο MinColumnWidth για τον καθορισμό του συνολικού διαστήματος στηλών του Matrix (απόσταση μεταξύ των ίδιων άκρων διαφορετικών στηλών). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Ελάχιστο πλάτος στήλης σε twips (1/20 του σημείου). Το διάστημα του κενού (επίσης αναφερόμενο ως \u201cColumn Gap\u201d ή \u201cGap Width\u201d) προστίθεται στο MinColumnWidth για τον καθορισμό του συνολικού διαστήματος στηλών του Matrix (απόσταση μεταξύ των ίδιων άκρων διαφορετικών στηλών). |
| [getColumnGapRule()](#getColumnGapRule--) | Ο τύπος του οριζόντιου διαστήματος μεταξύ των στηλών ενός πλέγματος· οι μονάδες οριζόντιου διαστήματος μπορεί να είναι ems ή points (αποθηκευμένα ως twips). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | Ο τύπος του οριζόντιου διαστήματος μεταξύ των στηλών ενός πλέγματος· οι μονάδες οριζόντιου διαστήματος μπορεί να είναι ems ή points (αποθηκευμένα ως twips). |
| [getColumnGap()](#getColumnGap--) | Η τιμή του οριζόντιου διαστήματος μεταξύ των στηλών ενός πλέγματος· εάν το ColumnGapRule είναι ορισμένο σε 3 («Exactly»), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου). Εάν το ColumnGapRule είναι ορισμένο σε 4 («Multiple»), η μονάδα ερμηνεύεται ως αριθμός αυξήσεων κατά 0,5 em. |
| [setColumnGap(long value)](#setColumnGap-long-) | Η τιμή του οριζόντιου διαστήματος μεταξύ των στηλών ενός πλέγματος· εάν το ColumnGapRule είναι ορισμένο σε 3 («Exactly»), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου). Εάν το ColumnGapRule είναι ορισμένο σε 4 («Multiple»), η μονάδα ερμηνεύεται ως αριθμός αυξήσεων κατά 0,5 em. |
| [getRowGapRule()](#getRowGapRule--) | Ο τύπος του κατακόρυφου διαστήματος μεταξύ των σειρών ενός πλέγματος· οι μονάδες κατακόρυφου διαστήματος μπορεί να είναι lines ή points (αποθηκευμένα ως twips). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | Ο τύπος του κατακόρυφου διαστήματος μεταξύ των σειρών ενός πλέγματος· οι μονάδες κατακόρυφου διαστήματος μπορεί να είναι lines ή points (αποθηκευμένα ως twips). |
| [getRowGap()](#getRowGap--) | Η τιμή του κατακόρυφου διαστήματος μεταξύ των σειρών ενός πλέγματος· εάν το RowGapRule είναι ορισμένο σε 3 («Exactly»), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου). Εάν το RowGapRule είναι ορισμένο σε 4 («Multiple»), η μονάδα ερμηνεύεται ως μισές γραμμές. |
| [setRowGap(long value)](#setRowGap-long-) | Η τιμή του κατακόρυφου διαστήματος μεταξύ των σειρών ενός πλέγματος· εάν το RowGapRule είναι ορισμένο σε 3 («Exactly»), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου). Εάν το RowGapRule είναι ορισμένο σε 4 («Multiple»), η μονάδα ερμηνεύεται ως μισές γραμμές. |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Λήψη της οριζόντιας στοίχισης της καθορισμένης στήλης |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Ορισμός της οριζόντιας στοίχισης της καθορισμένης στήλης |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Ορισμός της οριζόντιας στοίχισης των καθορισμένων στηλών |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Εισαγωγή νέας σειράς πριν από την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα σειρά είναι null. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Εισαγωγή νέας σειράς μετά την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα σειρά είναι null. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Διαγραφή της καθορισμένης σειράς |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Εισαγωγή νέας στήλης πριν από την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα στήλη είναι null. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Εισαγωγή νέας στήλης μετά την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα στήλη είναι null. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Διαγραφή της καθορισμένης στήλης |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public abstract IMathElement get_Item(int row, int column)
```

Στοιχεία του πλέγματος

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
| row | int | Ο δείκτης μηδενικής βάσης της σειράς για λήψη του αντικειμένου |
| column | int | Ο δείκτης μηδενικής βάσης της στήλης για λήψη του αντικειμένου |

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public abstract void set_Item(int row, int column, IMathElement value)
```

Στοιχεία του πλέγματος

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
| row | int | Ο δείκτης μηδενικής βάσης της σειράς για λήψη του αντικειμένου |
| column | int | Ο δείκτης μηδενικής βάσης της στήλης για λήψη του αντικειμένου |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getRowCount() {#getRowCount--}
```
public abstract int getRowCount()
```

Αριθμός σειρών στο πλέγμα

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
public abstract int getColumnCount()
```

Αριθμός στηλών στο πλέγμα

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
public abstract boolean getHidePlaceholders()
```

Απόκρυψη των placeholders για κενά στοιχεία του πλέγματος Προεπιλογή: false

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
public abstract void setHidePlaceholders(boolean value)
```

Απόκρυψη των placeholders για κενά στοιχεία του πλέγματος Προεπιλογή: false

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
public abstract int getBaseJustification()
```

Καθορίζει την κατακόρυφη στοίχιση σε σχέση με το περιβάλλον κείμενο. Πιθανές τιμές είναι top, bottom και center. Προεπιλογή: Center

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
public abstract void setBaseJustification(int value)
```

Καθορίζει την κατακόρυφη στοίχιση σε σχέση με το περιβάλλον κείμενο. Πιθανές τιμές είναι top, bottom και center. Προεπιλογή: Center

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
public abstract long getMinColumnWidth()
```

Ελάχιστο πλάτος στήλης σε twips (1/20 του σημείου). Το διάστημα του κενού (επίσης αναφερόμενο ως \u201cColumn Gap\u201d ή \u201cGap Width\u201d) προστίθεται στο MinColumnWidth για τον καθορισμό του συνολικού διαστήματος στηλών του Matrix (απόσταση μεταξύ των ίδιων άκρων διαφορετικών στηλών). Προεπιλογή: 0.

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
public abstract void setMinColumnWidth(long value)
```

Ελάχιστο πλάτος στήλης σε twips (1/20 του σημείου). Το διάστημα του κενού (επίσης αναφερόμενο ως \u201cColumn Gap\u201d ή \u201cGap Width\u201d) προστίθεται στο MinColumnWidth για τον καθορισμό του συνολικού διαστήματος στηλών του Matrix (απόσταση μεταξύ των ίδιων άκρων διαφορετικών στηλών). Προεπιλογή: 0.

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
public abstract int getColumnGapRule()
```

Ο τύπος του οριζόντιου διαστήματος μεταξύ των στηλών ενός πλέγματος· οι μονάδες οριζόντιου διαστήματος μπορεί να είναι ems ή points (αποθηκευμένα ως twips). Προεπιλογή: SingleSpacingGap (0)

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
public abstract void setColumnGapRule(int value)
```

Ο τύπος του οριζόντιου διαστήματος μεταξύ των στηλών ενός πλέγματος· οι μονάδες οριζόντιου διαστήματος μπορεί να είναι ems ή points (αποθηκευμένα ως twips). Προεπιλογή: SingleSpacingGap (0)

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
public abstract long getColumnGap()
```

Η τιμή του οριζόντιου διαστήματος μεταξύ των στηλών ενός πλέγματος· εάν το ColumnGapRule είναι ορισμένο σε 3 («Exactly»), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου). Εάν το ColumnGapRule είναι ορισμένο σε 4 («Multiple»), η μονάδα ερμηνεύεται ως αριθμός αυξήσεων κατά 0,5 em. Σε άλλες περιπτώσεις αγνοείται. Προεπιλογή: 0

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
public abstract void setColumnGap(long value)
```

Η τιμή του οριζόντιου διαστήματος μεταξύ των στηλών ενός πλέγματος· εάν το ColumnGapRule είναι ορισμένο σε 3 («Exactly»), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου). Εάν το ColumnGapRule είναι ορισμένο σε 4 («Multiple»), η μονάδα ερμηνεύεται ως αριθμός αυξήσεων κατά 0,5 em. Σε άλλες περιπτώσεις αγνοείται. Προεπιλογή: 0

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
public abstract int getRowGapRule()
```

Ο τύπος του κατακόρυφου διαστήματος μεταξύ των σειρών ενός πλέγματος· οι μονάδες κατακόρυφου διαστήματος μπορεί να είναι lines ή points (αποθηκευμένα ως twips). Προεπιλογή: SingleSpacingGap (0)

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
public abstract void setRowGapRule(int value)
```

Ο τύπος του κατακόρυφου διαστήματος μεταξύ των σειρών ενός πλέγματος· οι μονάδες κατακόρυφου διαστήματος μπορεί να είναι lines ή points (αποθηκευμένα ως twips). Προεπιλογή: SingleSpacingGap (0)

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
public abstract long getRowGap()
```

Η τιμή του κατακόρυφου διαστήματος μεταξύ των σειρών ενός πλέγματος· εάν το RowGapRule είναι ορισμένο σε 3 («Exactly»), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου). Εάν το RowGapRule είναι ορισμένο σε 4 («Multiple»), η μονάδα ερμηνεύεται ως μισές γραμμές. Προεπιλογή: 0

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
public abstract void setRowGap(long value)
```

Η τιμή του κατακόρυφου διαστήματος μεταξύ των σειρών ενός πλέγματος· εάν το RowGapRule είναι ορισμένο σε 3 («Exactly»), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου). Εάν το RowGapRule είναι ορισμένο σε 4 («Multiple»), η μονάδα ερμηνεύεται ως μισές γραμμές. Προεπιλογή: 0

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

### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public abstract int getColumnAlignment(int columnIndex)
```

Λήψη της οριζόντιας στοίχισης της καθορισμένης στήλης

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
public abstract void setColumnAlignment(int columnIndex, int val)
```

Ορισμός της οριζόντιας στοίχισης της καθορισμένης στήλης

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
public abstract void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

Ορισμός της οριζόντιας στοίχισης των καθορισμένων στηλών

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
| columnIndex | int | Δείκτης μηδενικής βάσης της πρώτης στήλης για ρύθμιση στοίχισης |
| columnsCount | long | Αριθμός στηλών για τις οποίες θα οριστεί η στοίχηση |
| val | int | Νέα τιμή της οριζόντιας στοίχισης της καθορισμένης στήλης |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public abstract void insertRowBefore(int rowIndex)
```

Εισαγωγή νέας σειράς πριν από την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα σειρά είναι null.

--------------------

> ```
> Παράδειγμα:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rowIndex | int | Δείκτης της σειράς πριν από την οποία θα εισαχθεί μια νέα |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public abstract void insertRowAfter(int rowIndex)
```

Εισαγωγή νέας σειράς μετά την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα σειρά είναι null.

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
| rowIndex | int | Δείκτης της σειράς μετά την οποία θα εισαχθεί μια νέα |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public abstract void deleteRow(int rowIndex)
```

Διαγραφή της καθορισμένης σειράς

--------------------

> ```
> Παράδειγμα:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rowIndex | int | Ο δείκτης μηδενικής βάσης της σειράς για διαγραφή. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public abstract void insertColumnBefore(int columnIndex)
```

Εισαγωγή νέας στήλης πριν από την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα στήλη είναι null.

--------------------

> ```
> Παράδειγμα:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| columnIndex | int | Δείκτης της στήλης πριν από την οποία θα εισαχθεί μια νέα |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public abstract void insertColumnAfter(int columnIndex)
```

Εισαγωγή νέας στήλης μετά την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα στήλη είναι null.

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
| columnIndex | int | Δείκτης της στήλης μετά την οποία θα εισαχθεί μια νέα |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public abstract void deleteColumn(int columnIndex)
```

Διαγραφή της καθορισμένης στήλης

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
| columnIndex | int | Δείκτης μηδενικής βάσης της στήλης για διαγραφή. |