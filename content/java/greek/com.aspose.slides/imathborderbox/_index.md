---
title: IMathBorderBox
second_title: Aspose.Slides για Java API Αναφορά
description: Σχεδιάζει ένα ορθογώνιο ή κάποιο άλλο περίγραμμα γύρω από το IMathElement.
type: docs
url: /el/com.aspose.slides/imathborderbox/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBorderBox extends IMathElement
```

Σχεδιάζει ένα ορθογώνιο ή κάποιον άλλο τύπο περιγράμματος γύρω από το IMathElement.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBase()](#getBase--) | Βασική παράμετρος |
| [getHideTop()](#getHideTop--) | Απόκρυψη Άνω Άκρης (default is false) - καθορίζει την κρυφή ή εμφανή κατάσταση της άνω άκρης του κουτιού περιγράμματος. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Απόκρυψη Άνω Άκρης (default is false) - καθορίζει την κρυφή ή εμφανή κατάσταση της άνω άκρης του κουτιού περιγράμματος. |
| [getHideBottom()](#getHideBottom--) | Απόκρυψη Κάτω Άκρης (default is false) - καθορίζει την κρυφή ή εμφανή κατάσταση της κάτω άκρης του κουτιού περιγράμματος. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Απόκρυψη Κάτω Άκρης (default is false) - καθορίζει την κρυφή ή εμφανή κατάσταση της κάτω άκρης του κουτιού περιγράμματος. |
| [getHideLeft()](#getHideLeft--) | Απόκρυψη Αριστερής Άκρης (default is false) - καθορίζει την κρυφή ή εμφανή κατάσταση της αριστερής άκρης του κουτιού περιγράμματος. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Απόκρυψη Αριστερής Άκρης (default is false) - καθορίζει την κρυφή ή εμφανή κατάσταση της αριστερής άκρης του κουτιού περιγράμματος. |
| [getHideRight()](#getHideRight--) | Απόκρυψη Δεξιάς Άκρης (default is false) - καθορίζει την κρυφή ή εμφανή κατάσταση της δεξιάς άκρης του κουτιού περιγράμματος. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Απόκρυψη Δεξιάς Άκρης (default is false) - καθορίζει την κρυφή ή εμφανή κατάσταση της δεξιάς άκρης του κουτιού περιγράμματος. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Διαγράμμιση Οριζόντια (default is false) - καθορίζει την κρυφή ή εμφανή κατάσταση μιας οριζόντιας γραμμής διαγράμμισης. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Διαγράμμιση Οριζόντια (default is false) - καθορίζει την κρυφή ή εμφανή κατάσταση μιας οριζόντιας γραμμής διαγράμμισης. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Διαγράμμιση Κατακόρυφα (default is false) - καθορίζει την κρυφή ή εμφανή κατάσταση μιας κατακόρυφης γραμμής διαγράμμισης. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Διαγράμμιση Κατακόρυφα (default is false) - καθορίζει την κρυφή ή εμφανή κατάσταση μιας κατακόρυφης γραμμής διαγράμμισης. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Διαγράμμιση Κάτω-Αριστερά προς Πάνω-Δεξιά (default is false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Διαγράμμιση Κάτω-Αριστερά προς Πάνω-Δεξιά (default is false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Διαγράμμιση Πάνω-Αριστερά προς Κάτω-Δεξιά (default is false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Διαγράμμιση Πάνω-Αριστερά προς Κάτω-Δεξιά (default is false). |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Βασική παράμετρος

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


Απόκρυψη Άνω Άκρης (default is false) - καθορίζει την κρυφή ή εμφανή κατάσταση της άνω άκρης του κουτιού περιγράμματος.

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


Απόκρυψη Άνω Άκρης (default is false) - καθορίζει την κρυφή ή εμφανή κατάσταση της άνω άκρης του κουτιού περιγράμματος.

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


Απόκρυψη Κάτω Άκρης (default is false) - καθορίζει την κρυφή ή εμφανή κατάσταση της κάτω άκρης του κουτιού περιγράμματος.

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


Απόκρυψη Κάτω Άκρης (default is false) - καθορίζει την κρυφή ή εμφανή κατάσταση της κάτω άκρης του κουτιού περιγράμματος.

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


Απόκρυψη Αριστερής Άκρης (default is false) - καθορίζει την κρυφή ή εμφανή κατάσταση της αριστερής άκρης του κουτιού περιγράμματος.

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


Απόκρυψη Αριστερής Άκρης (default is false) - καθορίζει την κρυφή ή εμφανή κατάσταση της αριστερής άκρης του κουτιού περιγράμματος.

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


Απόκρυψη Δεξιάς Άκρης (default is false) - καθορίζει την κρυφή ή εμφανή κατάσταση της δεξιάς άκρης του κουτιού περιγράμματος.

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


Απόκρυψη Δεξιάς Άκρης (default is false) - καθορίζει την κρυφή ή εμφανή κατάσταση της δεξιάς άκρης του κουτιού περιγράμματος.

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


Διαγράμμιση Οριζόντια (default is false) - καθορίζει την κρυφή ή εμφανή κατάσταση μιας οριζόντιας γραμμής διαγράμμισης.

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


Διαγράμμιση Οριζόντια (default is false) - καθορίζει την κρυφή ή εμφανή κατάσταση μιας οριζόντιας γραμμής διαγράμμισης.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public abstract boolean getStrikethroughVertical()
```


Διαγράμμιση Κατακόρυφα (default is false) - καθορίζει την κρυφή ή εμφανή κατάσταση μιας κατακόρυφης γραμμής διαγράμμισης.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**Επιστρέφει:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public abstract void setStrikethroughVertical(boolean value)
```


Διαγράμμιση Κατακόρυφα (default is false) - καθορίζει την κρυφή ή εμφανή κατάσταση μιας κατακόρυφης γραμμής διαγράμμισης.

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


Διαγράμμιση Κάτω-Αριστερά προς Πάνω-Δεξιά (default is false). Καθορίζει την κρυφή ή εμφανή κατάσταση μιας διαγώνιας γραμμής διαγράμμισης από την κάτω αριστερή γωνία προς την πάνω δεξιά γωνία του κουτιού περιγράμματος.

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


Διαγράμμιση Κάτω-Αριστερά προς Πάνω-Δεξιά (default is false). Καθορίζει την κρυφή ή εμφανή κατάσταση μιας διαγώνιας γραμμής διαγράμμισης από την κάτω αριστερή γωνία προς την πάνω δεξιά γωνία του κουτιού περιγράμματος.

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


Διαγράμμιση Πάνω-Αριστερά προς Κάτω-Δεξιά (default is false). Καθορίζει την κρυφή ή εμφανή κατάσταση μιας διαγώνιας γραμμής διαγράμμισης από την πάνω αριστερή γωνία προς την κάτω δεξιά γωνία του κουτιού περιγράμματος.

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


Διαγράμμιση Πάνω-Αριστερά προς Κάτω-Δεξιά (default is false). Καθορίζει την κρυφή ή εμφανή κατάσταση μιας διαγώνιας γραμμής διαγράμμισης από την πάνω αριστερή γωνία προς την κάτω δεξιά γωνία του κουτιού περιγράμματος.

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