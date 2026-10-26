---
title: MathBorderBox
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Σχεδιάζει ένα ορθογώνιο ή κάποιο άλλο περίγραμμα γύρω από το IMathElement.
type: docs
url: /el/com.aspose.slides/mathborderbox/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMathBorderBox](../../com.aspose.slides/imathborderbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBorderBox extends MathElementBase implements IMathBorderBox, IHasControlCharacterProperties
```

Σχεδιάζει ένα ορθογώνιο ή κάποιο άλλο περίγραμμα γύρω από το IMathElement.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MathBorderBox(IMathElement element)](#MathBorderBox-com.aspose.slides.IMathElement-) | Δημιουργεί το στοιχείο MathBorderBox με ορθογώνιο περίγραμμα |
| [MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Δημιουργεί το στοιχείο MathBorderBox |
## Μεθόδους

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBase()](#getBase--) | Βασικό επιχείρημα |
| [getHideTop()](#getHideTop--) | Απόκρυψη Άνω Άκρου (η προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση του άνω άκρου του πλαισίου περιγράμματος. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Απόκρυψη Άνω Άκρου (η προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση του άνω άκρου του πλαισίου περιγράμματος. |
| [getHideBottom()](#getHideBottom--) | Απόκρυψη Κάτω Άκρου (η προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση του κάτω άκρου του πλαισίου περιγράμματος. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Απόκρυψη Κάτω Άκρου (η προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση του κάτω άκρου του πλαισίου περιγράμματος. |
| [getHideLeft()](#getHideLeft--) | Απόκρυψη Αριστερού Άκρου (η προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση του αριστερού άκρου του πλαισίου περιγράμματος. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Απόκρυψη Αριστερού Άκρου (η προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση του αριστερού άκρου του πλαισίου περιγράμματος. |
| [getHideRight()](#getHideRight--) | Απόκρυψη Δεξιού Άκρου (η προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση του δεξιού άκρου του πλαισίου περιγράμματος. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Απόκρυψη Δεξιού Άκρου (η προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση του δεξιού άκρου του πλαισίου περιγράμματος. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Διαγράμμιση Οριζόντια (η προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση μιας οριζόντιας γραμμής διαγράμμισης. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Διαγράμμιση Οριζόντια (η προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση μιας οριζόντιας γραμμής διαγράμμισης. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Διαγράμμιση Κατακόρυφα (η προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση μιας κατακόρυφης γραμμής διαγράμμισης. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Διαγράμμιση Κατακόρυφα (η προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση μιας κατακόρυφης γραμμής διαγράμμισης. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Διαγράμμιση από Κάτω-Αριστερά προς Πάνω-Δεξιά (η προεπιλογή είναι false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Διαγράμμιση από Κάτω-Αριστερά προς Πάνω-Δεξιά (η προεπιλογή είναι false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Διαγράμμιση από Πάνω-Αριστερά προς Κάτω-Δεξιά (η προεπιλογή είναι false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Διαγράμμιση από Πάνω-Αριστερά προς Κάτω-Δεξιά (η προεπιλογή είναι false). |
| [getChildren()](#getChildren--) | Λαμβάνει τα στοιχεία των παιδιών |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Ιδιότητες Χαρακτήρων Ελέγχου |
### MathBorderBox(IMathElement element) {#MathBorderBox-com.aspose.slides.IMathElement-}
```
public MathBorderBox(IMathElement element)
```


Δημιουργεί το στοιχείο MathBorderBox με ορθογώνιο περίγραμμα

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Το βασικό στοιχείο στο οποίο εφαρμόζεται το πλαίσιο περιγράμματος. Μπορεί να είναι null. |

### MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


Δημιουργεί το στοιχείο MathBorderBox

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"), true, true, true, false, true, true, true, true)
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Το βασικό στοιχείο στο οποίο εφαρμόζεται το πλαίσιο περιγράμματος |
| hideTop | boolean | Απόκρυψη Άνω Άκρου |
| hideBottom | boolean | Απόκρυψη Κάτω Άκρου |
| hideLeft | boolean | Απόκρυψη Αριστερού Άκρου |
| hideRight | boolean | Απόκρυψη Δεξιού Άκρου |
| strikethroughHorizontal | boolean | Διαγράμμιση Οριζόντια |
| strikethroughVertical | boolean | Διαγράμμιση Κατακόρυφα |
| strikethroughBottomLeftToTopRight | boolean | Διαγράμμιση από Κάτω-Αριστερά προς Πάνω-Δεξιά |
| strikethroughTopLeftToBottomRight | boolean | Διαγράμμιση από Πάνω-Αριστερά προς Κάτω-Δεξιά |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Βασικό επιχείρημα

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  IMathElement base = borderBox.getBase();
> ```

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public final boolean getHideTop()
```


Απόκρυψη Άνω Άκρου (η προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση του άνω άκρου του πλαισίου περιγράμματος.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**Επιστρέφει:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public final void setHideTop(boolean value)
```


Απόκρυψη Άνω Άκρου (η προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση του άνω άκρου του πλαισίου περιγράμματος.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public final boolean getHideBottom()
```


Απόκρυψη Κάτω Άκρου (η προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση του κάτω άκρου του πλαισίου περιγράμματος.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**Επιστρέφει:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public final void setHideBottom(boolean value)
```


Απόκρυψη Κάτω Άκρου (η προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση του κάτω άκρου του πλαισίου περιγράμματος.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public final boolean getHideLeft()
```


Απόκρυψη Αριστερού Άκρου (η προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση του αριστερού άκρου του πλαισίου περιγράμματος.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**Επιστρέφει:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public final void setHideLeft(boolean value)
```


Απόκρυψη Αριστερού Άκρου (η προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση του αριστερού άκρου του πλαισίου περιγράμματος.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public final boolean getHideRight()
```


Απόκρυψη Δεξιού Άκρου (η προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση του δεξιού άκρου του πλαισίου περιγράμματος.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**Επιστρέφει:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public final void setHideRight(boolean value)
```


Απόκρυψη Δεξιού Άκρου (η προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση του δεξιού άκρου του πλαισίου περιγράμματος.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public final boolean getStrikethroughHorizontal()
```


Διαγράμμιση Οριζόντια (η προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση μιας οριζόντιας γραμμής διαγράμμισης.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Επιστρέφει:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public final void setStrikethroughHorizontal(boolean value)
```


Διαγράμμιση Οριζόντια (η προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση μιας οριζόντιας γραμμής διαγράμμισης.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public final boolean getStrikethroughVertical()
```


Διαγράμμιση Κατακόρυφα (η προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση μιας κατακόρυφης γραμμής διαγράμμισης.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**Επιστρέφει:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public final void setStrikethroughVertical(boolean value)
```


Διαγράμμιση Κατακόρυφα (η προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση μιας κατακόρυφης γραμμής διαγράμμισης.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public final boolean getStrikethroughBottomLeftToTopRight()
```


Διαγράμμιση από Κάτω-Αριστερά προς Πάνω-Δεξιά (η προεπιλογή είναι false). Καθορίζει την κρυφή ή εμφανή κατάσταση μιας διαγώνιας γραμμής διαγράμμισης από την κάτω αριστερή γωνία προς την πάνω δεξιά γωνία του πλαισίου περιγράμματος.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Επιστρέφει:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public final void setStrikethroughBottomLeftToTopRight(boolean value)
```


Διαγράμμιση από Κάτω-Αριστερά προς Πάνω-Δεξιά (η προεπιλογή είναι false). Καθορίζει την κρυφή ή εμφανή κατάσταση μιας διαγώνιας γραμμής διαγράμμισης από την κάτω αριστερή γωνία προς την πάνω δεξιά γωνία του πλαισίου περιγράμματος.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public final boolean getStrikethroughTopLeftToBottomRight()
```


Διαγράμμιση από Πάνω-Αριστερά προς Κάτω-Δεξιά (η προεπιλογή είναι false). Καθορίζει την κρυφή ή εμφανή κατάσταση μιας διαγώνιας γραμμής διαγράμμισης από την πάνω αριστερή γωνία προς την κάτω δεξιά γωνία του πλαισίου περιγράμματος.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Επιστρέφει:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public final void setStrikethroughTopLeftToBottomRight(boolean value)
```


Διαγράμμιση από Πάνω-Αριστερά προς Κάτω-Δεξιά (η προεπιλογή είναι false). Καθορίζει την κρυφή ή εμφανή κατάσταση μιας διαγώνιας γραμμής διαγράμμισης από την πάνω αριστερή γωνία προς την κάτω δεξιά γωνία του πλαισίου περιγράμματος.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Λαμβάνει τα στοιχεία των παιδιών

**Επιστρέφει:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Ιδιότητες Χαρακτήρων Ελέγχου

**Επιστρέφει:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps