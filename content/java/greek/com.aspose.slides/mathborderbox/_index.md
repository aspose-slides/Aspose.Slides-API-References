---
title: MathBorderBox
second_title: Aspose.Slides για Java API Αναφορά
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

Σχεδιάζει ένα ορθογώνιο ή κάποιον άλλο περίγραμμα γύρω από το IMathElement.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MathBorderBox(IMathElement element)](#MathBorderBox-com.aspose.slides.IMathElement-) | Δημιουργεί στοιχείο MathBorderBox με ορθογώνιο περίγραμμα |
| [MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Δημιουργεί στοιχείο MathBorderBox |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBase()](#getBase--) | Βασικό επιχείρημα |
| [getHideTop()](#getHideTop--) | Απόκρυψη Άνω Ακμής (προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση της άνω ακμής του πλαισίου περιγράμματος. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Απόκρυψη Άνω Ακμής (προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση της άνω ακμής του πλαισίου περιγράμματος. |
| [getHideBottom()](#getHideBottom--) | Απόκρυψη Κάτω Ακμής (προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση της κάτω ακμής του πλαισίου περιγράμματος. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Απόκρυψη Κάτω Ακμής (προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση της κάτω ακμής του πλαισίου περιγράμματος. |
| [getHideLeft()](#getHideLeft--) | Απόκρυψη Αριστερής Ακμής (προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση της αριστερής ακμής του πλαισίου περιγράμματος. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Απόκρυψη Αριστερής Ακμής (προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση της αριστερής ακμής του πλαισίου περιγράμματος. |
| [getHideRight()](#getHideRight--) | Απόκρυψη Δεξιάς Ακμής (προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση της δεξιάς ακμής του πλαισίου περιγράμματος. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Απόκρυψη Δεξιάς Ακμής (προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση της δεξιάς ακμής του πλαισίου περιγράμματος. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Γραμμή διαγράμμισης οριζόντια (προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση μιας οριζόντιας γραμμής διαγράμμισης. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Γραμμή διαγράμμισης οριζόντια (προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση μιας οριζόντιας γραμμής διαγράμμισης. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Γραμμή διαγράμμισης κάθετη (προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση μιας κάθετης γραμμής διαγράμμισης. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Γραμμή διαγράμμισης κάθετη (προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση μιας κάθετης γραμμής διαγράμμισης. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Διαγράμμιση Κάτω-Αριστερά προς Πάνω-Δεξιά (προεπιλογή είναι false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Διαγράμμιση Κάτω-Αριστερά προς Πάνω-Δεξιά (προεπιλογή είναι false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Διαγράμμιση Πάνω-Αριστερά προς Κάτω-Δεξιά (προεπιλογή είναι false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Διαγράμμιση Πάνω-Αριστερά προς Κάτω-Δεξιά (προεπιλογή είναι false). |
| [getChildren()](#getChildren--) | Λήψη παιδικών στοιχείων |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Ιδιότητες Χαρακτήρων Ελέγχου |
### MathBorderBox(IMathElement element) {#MathBorderBox-com.aspose.slides.IMathElement-}
```
public MathBorderBox(IMathElement element)
```

Δημιουργεί στοιχείο MathBorderBox με ορθογώνιο περίγραμμα

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

Δημιουργεί στοιχείο MathBorderBox

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
| hideTop | boolean | Απόκρυψη Άνω Ακμής |
| hideBottom | boolean | Απόκρυψη Κάτω Ακμής |
| hideLeft | boolean | Απόκρυψη Αριστερής Ακμής |
| hideRight | boolean | Απόκρυψη Δεξιάς Ακμής |
| strikethroughHorizontal | boolean | Διαγράμμιση Οριζόντια |
| strikethroughVertical | boolean | Διαγράμμιση Κάθετη |
| strikethroughBottomLeftToTopRight | boolean | Διαγράμμιση Κάτω-Αριστερά προς Πάνω-Δεξιά |
| strikethroughTopLeftToBottomRight | boolean | Διαγράμμιση Πάνω-Αριστερά προς Κάτω-Δεξιά |

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

Απόκρυψη Άνω Ακμής (προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση της άνω ακμής του πλαισίου περιγράμματος.

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

Απόκρυψη Άνω Ακμής (προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση της άνω ακμής του πλαισίου περιγράμματος.

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

Απόκρυψη Κάτω Ακμής (προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση της κάτω ακμής του πλαισίου περιγράμματος.

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

Απόκρυψη Κάτω Ακμής (προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση της κάτω ακμής του πλαισίου περιγράμματος.

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

Απόκρυψη Αριστερής Ακμής (προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση της αριστερής ακμής του πλαισίου περιγράμματος.

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

Απόκρυψη Αριστερής Ακμής (προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση της αριστερής ακμής του πλαισίου περιγράμματος.

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

Απόκρυψη Δεξιάς Ακμής (προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση της δεξιάς ακμής του πλαισίου περιγράμματος.

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

Απόκρυψη Δεξιάς Ακμής (προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση της δεξιάς ακμής του πλαισίου περιγράμματος.

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

Γραμμή διαγράμμισης οριζόντια (προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση μιας οριζόντιας γραμμής διαγράμμισης.

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

Γραμμή διαγράμμισης οριζόντια (προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση μιας οριζόντιας γραμμής διαγράμμισης.

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

Γραμμή διαγράμμισης κάθετη (προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση μιας κάθετης γραμμής διαγράμμισης.

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

Γραμμή διαγράμμισης κάθετη (προεπιλογή είναι false) - καθορίζει την κρυφή ή εμφανή κατάσταση μιας κάθετης γραμμής διαγράμμισης.

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

Διαγράμμιση Κάτω-Αριστερά προς Πάνω-Δεξιά (προεπιλογή είναι false). Καθορίζει την κρυφή ή εμφανή κατάσταση μιας διαγώνιας γραμμής διαγράμμισης από την κάτω αριστερή γωνία προς την πάνω δεξιά γωνία του πλαισίου περιγράμματος.

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

Διαγράμμιση Κάτω-Αριστερά προς Πάνω-Δεξιά (προεπιλογή είναι false). Καθορίζει την κρυφή ή εμφανή κατάσταση μιας διαγώνιας γραμμής διαγράμμισης από την κάτω αριστερή γωνία προς την πάνω δεξιά γωνία του πλαισίου περιγράμματος.

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

Διαγράμμιση Πάνω-Αριστερά προς Κάτω-Δεξιά (προεπιλογή είναι false). Καθορίζει την κρυφή ή εμφανή κατάσταση μιας διαγώνιας γραμμής διαγράμμισης από την πάνω αριστερή γωνία προς την κάτω δεξιά γωνία του πλαισίου περιγράμματος.

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

Διαγράμμιση Πάνω-Αριστερά προς Κάτω-Δεξιά (προεπιλογή είναι false). Καθορίζει την κρυφή ή εμφανή κατάσταση μιας διαγώνιας γραμμής διαγράμμισης από την πάνω αριστερή γωνία προς την κάτω δεξιά γωνία του πλαισίου περιγράμματος.

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

Λήψη παιδικών στοιχείων

**Επιστρέφει:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Ιδιότητες Χαρακτήρων Ελέγχου

**Επιστρέφει:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps