---
title: IMathMatrix
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Καθορίζει το αντικείμενο Matrix που αποτελείται από στοιχεία-παιδιά τα οποία τοποθετούνται σε μία ή περισσότερες γραμμές και στήλες.
type: docs
url: /el/com.aspose.slides/imathmatrix/
---
**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathMatrix extends IMathElement
```

Καθορίζει το αντικείμενο Matrix, το οποίο αποτελείται από στοιχεία-παιδιά τοποθετημένα σε μία ή περισσότερες γραμμές και στήλες. Είναι σημαντικό να σημειωθεί ότι οι πίνακες δεν έχουν ενσωματωμένους οριοθέτες. Για να τοποθετήσετε τον πίνακα σε αγκύλες πρέπει να χρησιμοποιήσετε το αντικείμενο οριοθέτη (IMathDelimiter). Μπορούν να χρησιμοποιηθούν παράμετροι null για να δημιουργηθούν κενά στους πίνακες.

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
| [get_Item(int row, int column)](#get-Item-int-int-) | Στοιχεία του πίνακα |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Στοιχεία του πίνακα |
| [getRowCount()](#getRowCount--) | Αριθμός γραμμών στον πίνακα |
| [getColumnCount()](#getColumnCount--) | Αριθμός στηλών στον πίνακα |
| [getHidePlaceholders()](#getHidePlaceholders--) | Απόκρυψη των κρατημάτων θέσης για κενά στοιχεία του πίνακα Προεπιλογή: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Απόκρυψη των κρατημάτων θέσης για κενά στοιχεία του πίνακα Προεπιλογή: false |
| [getBaseJustification()](#getBaseJustification--) | Καθορίζει τη κάθετη στοίχιση σε σχέση με το περιβάλλον κείμενο. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Καθορίζει τη κάθετη στοίχιση σε σχέση με το περιβάλλον κείμενο. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Ελάχιστο πλάτος στήλης σε twips (1/20 του σημείου). Το διάστημα του κενού (επίσης αναφέρεται ως “Column Gap” ή “Gap Width”) προστίθεται στο MinColumnWidth για να καθορίσει το συνολικό διάστημα στηλών του πίνακα (απόσταση μεταξύ των ίδιων άκρων διαφορετικών στηλών). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Ελάχιστο πλάτος στήλης σε twips (1/20 του σημείου). Το διάστημα του κενού (επίσης αναφέρεται ως “Column Gap” ή “Gap Width”) προστίθεται στο MinColumnWidth για να καθορίσει το συνολικό διάστημα στηλών του πίνακα (απόσταση μεταξύ των ίδιων άκρων διαφορετικών στηλών). |
| [getColumnGapRule()](#getColumnGapRule--) | Ο τύπος του οριζόντιου διαστήματος μεταξύ στηλών ενός πίνακα· Οι μονάδες οριζόντιου διαστήματος μπορούν να είναι ems ή points (αποθηκεύονται ως twips). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | Ο τύπος του οριζόντιου διαστήματος μεταξύ στηλών ενός πίνακα· Οι μονάδες οριζόντιου διαστήματος μπορούν να είναι ems ή points (αποθηκεύονται ως twips). |
| [getColumnGap()](#getColumnGap--) | Η τιμή του οριζόντιου διαστήματος μεταξύ στηλών ενός πίνακα· Εάν το ColumnGapRule οριστεί σε 3 (“Exactly”), τότε η μονάδα ερμηνεύεται ως twips (1/20 του σημείου). Εάν το ColumnGapRule οριστεί σε 4 (“Multiple”), τότε η μονάδα ερμηνεύεται ως αριθμός 0,5 em βημάτων. |
| [setColumnGap(long value)](#setColumnGap-long-) | Η τιμή του οριζόντιου διαστήματος μεταξύ στηλών ενός πίνακα· Εάν το ColumnGapRule οριστεί σε 3 (“Exactly”), τότε η μονάδα ερμηνεύεται ως twips (1/20 του σημείου). Εάν το ColumnGapRule οριστεί σε 4 (“Multiple”), τότε η μονάδα ερμηνεύεται ως αριθμός 0,5 em βημάτων. |
| [getRowGapRule()](#getRowGapRule--) | Ο τύπος του κάθετου διαστήματος μεταξύ γραμμών ενός πίνακα· Οι μονάδες κάθετου διαστήματος μπορούν να είναι lines ή points (αποθηκεύονται ως twips). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | Ο τύπος του κάθετου διαστήματος μεταξύ γραμμών ενός πίνακα· Οι μονάδες κάθετου διαστήματος μπορούν να είναι lines ή points (αποθηκεύονται ως twips). |
| [getRowGap()](#getRowGap--) | Η τιμή του κάθετου διαστήματος μεταξύ γραμμών ενός πίνακα· Εάν το RowGapRule οριστεί σε 3 (“Exactly”), τότε η μονάδα ερμηνεύεται ως twips (1/20 του σημείου). Εάν το RowGapRule οριστεί σε 4 (“Multiple”), τότε η μονάδα ερμηνεύεται ως ημικαλές. |
| [setRowGap(long value)](#setRowGap-long-) | Η τιμή του κάθετου διαστήματος μεταξύ γραμμών ενός πίνακα· Εάν το RowGapRule οριστεί σε 3 (“Exactly”), τότε η μονάδα ερμηνεύεται ως twips (1/20 του σημείου). Εάν το RowGapRule οριστεί σε 4 (“Multiple”), τότε η μονάδα ερμηνεύεται ως ημικαλές. |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Λήψη της οριζόντιας στοίχισης της καθορισμένης στήλης |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Ορισμός της οριζόντιας στοίχισης της καθορισμένης στήλης |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Ορισμός της οριζόντιας στοίχισης των καθορισμένων στηλών |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Εισαγωγή νέας γραμμής πριν από τη καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα γραμμή είναι null. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Εισαγωγή νέας γραμμής μετά από τη καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα γραμμή είναι null. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Διαγράφει τη καθορισμένη γραμμή |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Εισαγωγή νέας στήλης πριν από τη καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα στήλη είναι null. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Εισαγωγή νέας στήλης μετά από τη καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα στήλη είναι null. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Διαγράφει τη καθορισμένη στήλη |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public abstract IMathElement get_Item(int row, int column)
```


Στοιχεία του πίνακα

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
| row | int | Ο δείκτης μηδενικής βάσης της γραμμής για την λήψη του στοιχείου |
| column | int | Ο δείκτης μηδενικής βάσης της στήλης για την λήψη του στοιχείου |

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public abstract void set_Item(int row, int column, IMathElement value)
```


Στοιχεία του πίνακα

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
| row | int | Ο δείκτης μηδενικής βάσης της γραμμής για την λήψη του στοιχείου |
| column | int | Ο δείκτης μηδενικής βάσης της στήλης για την λήψη του στοιχείου |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getRowCount() {#getRowCount--}
```
public abstract int getRowCount()
```

Αριθμός γραμμών στον πίνακα

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

Αριθμός στηλών στον πίνακα

--------------------

> ```
> Παράδειγμα:
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

Απόκρυψη των κρατημάτων θέσης για κενά στοιχεία του πίνακα Προεπιλογή: false

--------------------

> ```
> Παράδειγμα:
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

Απόκρυψη των κρατημάτων θέσης για κενά στοιχεία του πίνακα Προεπιλογή: false

--------------------

> ```
> Παράδειγμα:
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

Καθορίζει τη κάθετη στοίχιση σε σχέση με το περιβάλλον κείμενο. Οι δυνατές τιμές είναι top, bottom και center. Προεπιλογή: Center

--------------------

> ```
> Παράδειγμα:
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

Καθορίζει τη κάθετη στοίχιση σε σχέση με το περιβάλλον κείμενο. Οι δυνατές τιμές είναι top, bottom και center. Προεπιλογή: Center

--------------------

> ```
> Παράδειγμα:
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

Ελάχιστο πλάτος στήλης σε twips (1/20 του σημείου). Το διάστημα του κενού (επίσης αναφέρεται ως “Column Gap” ή “Gap Width”) προστίθεται στο MinColumnWidth για να καθορίσει το συνολικό διάστημα στηλών του πίνακα (απόσταση μεταξύ των ίδιων άκρων διαφορετικών στηλών). Προεπιλογή: 0.

--------------------

> ```
> Παράδειγμα:
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

Ελάχιστο πλάτος στήλης σε twips (1/20 του σημείου). Το διάστημα του κενού (επίσης αναφέρεται ως “Column Gap” ή “Gap Width”) προστίθεται στο MinColumnWidth για να καθορίσει το συνολικό διάστημα στηλών του πίνακα (απόσταση μεταξύ των ίδιων άκρων διαφορετικών στηλών). Προεπιλογή: 0.

--------------------

> ```
> Παράδειγμα:
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

Ο τύπος του οριζόντιου διαστήματος μεταξύ στηλών ενός πίνακα· Οι μονάδες οριζόντιου διαστήματος μπορούν να είναι ems ή points (αποθηκεύονται ως twips). Προεπιλογή: SingleSpacingGap (0)

--------------------

> ```
> Παράδειγμα:
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

Ο τύπος του οριζόντιου διαστήματος μεταξύ στηλών ενός πίνακα· Οι μονάδες οριζόντιου διαστήματος μπορούν να είναι ems ή points (αποθηκεύονται ως twips). Προεπιλογή: SingleSpacingGap (0)

--------------------

> ```
> Παράδειγμα:
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

Η τιμή του οριζόντιου διαστήματος μεταξύ στηλών ενός πίνακα· Εάν το ColumnGapRule οριστεί σε 3 (“Exactly”), τότε η μονάδα ερμηνεύεται ως twips (1/20 του σημείου). Εάν το ColumnGapRule οριστεί σε 4 (“Multiple”), τότε η μονάδα ερμηνεύεται ως αριθμός 0,5 em βημάτων. Σε άλλες περιπτώσεις αγνοείται. Προεπιλογή: 0

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
public abstract void setColumnGap(long value)
```

Η τιμή του οριζόντιου διαστήματος μεταξύ στηλών ενός πίνακα· Εάν το ColumnGapRule οριστεί σε 3 (“Exactly”), τότε η μονάδα ερμηνεύεται ως twips (1/20 του σημείου). Εάν το ColumnGapRule οριστεί σε 4 (“Multiple”), τότε η μονάδα ερμηνεύεται ως αριθμός 0,5 em βημάτων. Σε άλλες περιπτώσεις αγνοείται. Προεπιλογή: 0

--------------------

> ```
> Παράδειγμα:
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

Ο τύπος του κάθετου διαστήματος μεταξύ γραμμών ενός πίνακα· Οι μονάδες κάθετου διαστήματος μπορούν να είναι lines ή points (αποθηκεύονται ως twips). Προεπιλογή: SingleSpacingGap (0)

--------------------

> ```
> Παράδειγμα:
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

Ο τύπος του κάθετου διαστήματος μεταξύ γραμμών ενός πίνακα· Οι μονάδες κάθετου διαστήματος μπορούν να είναι lines ή points (αποθηκεύονται ως twips). Προεπιλογή: SingleSpacingGap (0)

--------------------

> ```
> Παράδειγμα:
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

Η τιμή του κάθετου διαστήματος μεταξύ γραμμών ενός πίνακα· Εάν το RowGapRule οριστεί σε 3 (“Exactly”), τότε η μονάδα ερμηνεύεται ως twips (1/20 του σημείου). Εάν το RowGapRule οριστεί σε 4 (“Multiple”), τότε η μονάδα ερμηνεύεται ως ημικαλές. Προεπιλογή: 0

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
public abstract void setRowGap(long value)
```

Η τιμή του κάθετου διαστήματος μεταξύ γραμμών ενός πίνακα· Εάν το RowGapRule οριστεί σε 3 (“Exactly”), τότε η μονάδα ερμηνεύεται ως twips (1/20 του σημείου). Εάν το RowGapRule οριστεί σε 4 (“Multiple”), τότε η μονάδα ερμηνεύεται ως ημικαλές. Προεπιλογή: 0

--------------------

> ```
> Παράδειγμα:
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
> Παράδειγμα:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| columnIndex | int | Δείκτης στήλης μηδενικής βάσης |

**Επιστρέφει:**
int - Οριζόντια Στοίχιση καθορισμένης στήλης
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public abstract void setColumnAlignment(int columnIndex, int val)
```

Ορισμός της οριζόντιας στοίχισης της καθορισμένης στήλης

--------------------

> ```
> Παράδειγμα:
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
> Παράδειγμα:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| columnIndex | int | Δείκτης της πρώτης στήλης για την οποία ορίζεται στοίχιση |
| columnsCount | long | Ο αριθμός των στηλών για τις οποίες ορίζεται η στοίχιση |
| val | int | Νέα τιμή της οριζόντιας στοίχισης της καθορισμένης στήλης |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public abstract void insertRowBefore(int rowIndex)
```

Εισαγωγή νέας γραμμής πριν από τη καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα γραμμή είναι null.

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
| rowIndex | int | Δείκτης της γραμμής πριν από την οποία θα προστεθεί νέα γραμμή |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public abstract void insertRowAfter(int rowIndex)
```

Εισαγωγή νέας γραμμής μετά από τη καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα γραμμή είναι null.

--------------------

> ```
> Παράδειγμα:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rowIndex | int | Δείκτης της γραμμής μετά τη οποία θα προστεθεί νέα γραμμή |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public abstract void deleteRow(int rowIndex)
```

Διαγράφει τη καθορισμένη γραμμή

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
| rowIndex | int | Ο δείκτης μηδενικής βάσης της γραμμής που θα διαγραφεί. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public abstract void insertColumnBefore(int columnIndex)
```

Εισαγωγή νέας στήλης πριν από τη καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα στήλη είναι null.

--------------------

> ```
> Παράδειγμα:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| columnIndex | int | Δείκτης της στήλης πριν από την οποία θα προστεθεί νέα στήλη |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public abstract void insertColumnAfter(int columnIndex)
```

Εισαγωγή νέας στήλης μετά από τη καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα στήλη είναι null.

--------------------

> ```
> Παράδειγμα:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```


**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| columnIndex | int | Δείκτης της στήλης μετά τη οποία θα προστεθεί νέα στήλη |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public abstract void deleteColumn(int columnIndex)
```

Διαγράφει τη καθορισμένη στήλη

--------------------

> ```
> Παράδειγμα:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| columnIndex | int | Ο δείκτης μηδενικής βάσης της στήλης που θα διαγραφεί. |