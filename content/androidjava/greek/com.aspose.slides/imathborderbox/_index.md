---
title: IMathBorderBox
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Σχεδίαζει ένα ορθογώνιο ή κάποιο άλλο περίγραμμα γύρω από το IMathElement.
type: docs
url: /el/com.aspose.slides/imathborderbox/
---
**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBorderBox extends IMathElement
```

Σχεδίαζει ένα ορθογώνιο ή κάποιο άλλο περίγραμμα γύρω από το IMathElement.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBase()](#getBase--) | Βασικό όρισμα |
| [getHideTop()](#getHideTop--) | Απόκρυψη άνω άκρου (προεπιλογή είναι ψευδής) - καθορίζει την κρυφή ή εμφανή κατάσταση του άνω άκρου του πλαισίου περιγράμματος. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Απόκρυψη άνω άκρου (προεπιλογή είναι ψευδής) - καθορίζει την κρυφή ή εμφανή κατάσταση του άνω άκρου του πλαισίου περιγράμματος. |
| [getHideBottom()](#getHideBottom--) | Απόκρυψη κάτω άκρου (προεπιλογή είναι ψευδής) - καθορίζει την κρυφή ή εμφανή κατάσταση του κάτω άκρου του πλαισίου περιγράμματος. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Απόκρυψη κάτω άκρου (προεπιλογή είναι ψευδής) - καθορίζει την κρυφή ή εμφανή κατάσταση του κάτω άκρου του πλαισίου περιγράμματος. |
| [getHideLeft()](#getHideLeft--) | Απόκρυψη αριστερού άκρου (προεπιλογή είναι ψευδής) - καθορίζει την κρυφή ή εμφανή κατάσταση του αριστερού άκρου του πλαισίου περιγράμματος. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Απόκρυψη αριστερού άκρου (προεπιλογή είναι ψευδής) - καθορίζει την κρυφή ή εμφανή κατάσταση του αριστερού άκρου του πλαισίου περιγράμματος. |
| [getHideRight()](#getHideRight--) | Απόκρυψη δεξιού άκρου (προεπιλογή είναι ψευδής) - καθορίζει την κρυφή ή εμφανή κατάσταση του δεξιού άκρου του πλαισίου περιγράμματος. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Απόκρυψη δεξιού άκρου (προεπιλογή είναι ψευδής) - καθορίζει την κρυφή ή εμφανή κατάσταση του δεξιού άκρου του πλαισίου περιγράμματος. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Διακριτή γραμμή Οριζόντια (προεπιλογή είναι ψευδής) - καθορίζει την κρυφή ή εμφανή κατάσταση μιας διακριτής οριζόντιας γραμμής. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Διακριτή γραμμή Οριζόντια (προεπιλογή είναι ψευδής) - καθορίζει την κρυφή ή εμφανή κατάσταση μιας διακριτής οριζόντιας γραμμής. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Διακριτή γραμμή Κατακόρυφα (προεπιλογή είναι ψευδής) - καθορίζει την κρυφή ή εμφανή κατάσταση μιας διακριτής κατακόρυφης γραμμής. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Διακριτή γραμμή Κατακόρυφα (προεπιλογή είναι ψευδής) - καθορίζει την κρυφή ή εμφανή κατάσταση μιας διακριτής κατακόρυφης γραμμής. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Διακριτή γραμμή Κάτω-Αριστερά προς Πάνω-Δεξιά (προεπιλογή είναι ψευδής). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Διακριτή γραμμή Κάτω-Αριστερά προς Πάνω-Δεξιά (προεπιλογή είναι ψευδής). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Διακριτή γραμμή Πάνω-Αριστερά προς Κάτω-Δεξιά (προεπιλογή είναι ψευδής). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Διακριτή γραμμή Πάνω-Αριστερά προς Κάτω-Δεξιά (προεπιλογή είναι ψευδής). |

### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Βασικό όρισμα

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  IMathElement base = borderBox.getBase();
> ```

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public abstract boolean getHideTop()
```


Απόκρυψη άνω άκρου (προεπιλογή είναι ψευδής) - καθορίζει την κρυφή ή εμφανή κατάσταση του άνω άκρου του πλαισίου περιγράμματος.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**Επιστρέφει:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public abstract void setHideTop(boolean value)
```


Απόκρυψη άνω άκρου (προεπιλογή είναι ψευδής) - καθορίζει την κρυφή ή εμφανή κατάσταση του άνω άκρου του πλαισίου περιγράμματος.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public abstract boolean getHideBottom()
```


Απόκρυψη κάτω άκρου (προεπιλογή είναι ψευδής) - καθορίζει την κρυφή ή εμφανή κατάσταση του κάτω άκρου του πλαισίου περιγράμματος.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**Επιστρέφει:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public abstract void setHideBottom(boolean value)
```


Απόκρυψη κάτω άκρου (προεπιλογή είναι ψευδής) - καθορίζει την κρυφή ή εμφανή κατάσταση του κάτω άκρου του πλαισίου περιγράμματος.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public abstract boolean getHideLeft()
```


Απόκρυψη αριστερού άκρου (προεπιλογή είναι ψευδής) - καθορίζει την κρυφή ή εμφανή κατάσταση του αριστερού άκρου του πλαισίου περιγράμματος.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**Επιστρέφει:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public abstract void setHideLeft(boolean value)
```


Απόκρυψη αριστερού άκρου (προεπιλογή είναι ψευδής) - καθορίζει την κρυφή ή εμφανή κατάσταση του αριστερού άκρου του πλαισίου περιγράμματος.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public abstract boolean getHideRight()
```


Απόκρυψη δεξιού άκρου (προεπιλογή είναι ψευδής) - καθορίζει την κρυφή ή εμφανή κατάσταση του δεξιού άκρου του πλαισίου περιγράμματος.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**Επιστρέφει:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public abstract void setHideRight(boolean value)
```


Απόκρυψη δεξιού άκρου (προεπιλογή είναι ψευδής) - καθορίζει την κρυφή ή εμφανή κατάσταση του δεξιού άκρου του πλαισίου περιγράμματος.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public abstract boolean getStrikethroughHorizontal()
```


Διακριτή γραμμή Οριζόντια (προεπιλογή είναι ψευδής) - καθορίζει την κρυφή ή εμφανή κατάσταση μιας διακριτής οριζόντιας γραμμής.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Επιστρέφει:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public abstract void setStrikethroughHorizontal(boolean value)
```


Διακριτή γραμμή Οριζόντια (προεπιλογή είναι ψευδής) - καθορίζει την κρυφή ή εμφανή κατάσταση μιας διακριτής οριζόντιας γραμμής.

--------------------

> ```
public abstract void setStrikethroughHorizontal(boolean value)
```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public abstract boolean getStrikethroughVertical()
```


Διακριτή γραμμή Κατακόρυφα (προεπιλογή είναι ψευδής) - καθορίζει την κρυφή ή εμφανή κατάσταση μιας διακριτής κατακόρυφης γραμμής.

--------------------

> ```
public abstract boolean getStrikethroughVertical()
```

**Επιστρέφει:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public abstract void setStrikethroughVertical(boolean value)
```


Διακριτή γραμμή Κατακόρυφα (προεπιλογή είναι ψευδής) - καθορίζει την κρυφή ή εμφανή κατάσταση μιας διακριτής κατακόρυφης γραμμής.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public abstract boolean getStrikethroughBottomLeftToTopRight()
```


Διακριτή γραμμή Κάτω-Αριστερά προς Πάνω-Δεξιά (προεπιλογή είναι ψευδής). Καθορίζει την κρυφή ή εμφανή κατάσταση μιας διακριτής διαγώνιας γραμμής από την κάτω-αριστερή γωνία προς την πάνω-δεξιά γωνία του πλαισίου περιγράμματος.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Επιστρέφει:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public abstract void setStrikethroughBottomLeftToTopRight(boolean value)
```


Διακριτή γραμμή Κάτω-Αριστερά προς Πάνω-Δεξιά (προεπιλογή είναι ψευδής). Καθορίζει την κρυφή ή εμφανή κατάσταση μιας διακριτής διαγώνιας γραμμής από την κάτω-αριστερή γωνία προς την πάνω-δεξιά γωνία του πλαισίου περιγράμματος.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public abstract boolean getStrikethroughTopLeftToBottomRight()
```


Διακριτή γραμμή Πάνω-Αριστερά προς Κάτω-Δεξιά (προεπιλογή είναι ψευδής). Καθορίζει την κρυφή ή εμφανή κατάσταση μιας διακριτής διαγώνιας γραμμής από την πάνω-αριστερή γωνία προς την κάτω-δεξιά γωνία του πλαισίου περιγράμματος.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Επιστρέφει:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public abstract void setStrikethroughTopLeftToBottomRight(boolean value)
```


Διακριτή γραμμή Πάνω-Αριστερά προς Κάτω-Δεξιά (προεπιλογή είναι ψευδής). Καθορίζει την κρυφή ή εμφανή κατάσταση μιας διακριτής διαγώνιας γραμμής από την πάνω-αριστερή γωνία προς την κάτω-δεξιά γωνία του πλαισίου περιγράμματος.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |