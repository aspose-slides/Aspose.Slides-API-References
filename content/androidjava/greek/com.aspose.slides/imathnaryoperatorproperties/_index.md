---
title: IMathNaryOperatorProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Καθορίζει τις ιδιότητες του IMathNaryOperator
type: docs
url: /el/com.aspose.slides/imathnaryoperatorproperties/
---```
public interface IMathNaryOperatorProperties
```

Καθορίζει τις ιδιότητες του IMathNaryOperator
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getOperator()](#getOperator--) | Χαρακτήρας Nary Operator για παράδειγμα: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Χαρακτήρας Nary Operator για παράδειγμα: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | Η θέση των ορίων (υποσυμβολισμός και ανώτερος εκθέτης) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | Η θέση των ορίων (υποσυμβολισμός και ανώτερος εκθέτης) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Ο χαρακτήρας του τελεστή μεγαλώνει κάθετα για να ταιριάζει με το ύψος του τελεστέου |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Ο χαρακτήρας του τελεστή μεγαλώνει κάθετα για να ταιριάζει με το ύψος του τελεστέου |
| [getHideSubscript()](#getHideSubscript--) | Απόκρυψη Υποσυντελεστή |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | Απόκρυψη Υποσυντελεστή |
| [getHideSuperscript()](#getHideSuperscript--) | Απόκρυψη Ανώτερου Δείκτη |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | Απόκρυψη Ανώτερου Δείκτη |
### getOperator() {#getOperator--}
```
public abstract char getOperator()
```


Χαρακτήρας Nary Operator για παράδειγμα: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
```

**Επιστρέφει:**
char
### setOperator(char value) {#setOperator-char-}
```
public abstract void setOperator(char value)
```


Χαρακτήρας Nary Operator για παράδειγμα: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | char |  |

### getLimitLocation() {#getLimitLocation--}
```
public abstract int getLimitLocation()
```


Η θέση των ορίων (υποσυμβολισμός και ανώτερος εκθέτης)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Επιστρέφει:**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public abstract void setLimitLocation(int value)
```


Η θέση των ορίων (υποσυμβολισμός και ανώτερος εκθέτης)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```


Ο χαρακτήρας του τελεστή μεγαλώνει κάθετα για να ταιριάζει με το ύψος του τελεστέου

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Επιστρέφει:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```


Ο χαρακτήρας του τελεστή μεγαλώνει κάθετα για να ταιριάζει με το ύψος του τελεστέου

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getHideSubscript() {#getHideSubscript--}
```
public abstract boolean getHideSubscript()
```


Απόκρυψη Υποσυντελεστή

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Επιστρέφει:**
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public abstract void setHideSubscript(boolean value)
```


Απόκρυψη Υποσυντελεστή

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getHideSuperscript() {#getHideSuperscript--}
```
public abstract boolean getHideSuperscript()
```


Απόκρυψη Ανώτερου Δείκτη

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Επιστρέφει:**
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public abstract void setHideSuperscript(boolean value)
```


Απόκρυψη Ανώτερου Δείκτη

--------------------

> ```
> Παράδειγμα:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |