---
title: IMathNaryOperatorProperties
second_title: Aspose.Slides για Java Αναφορά API
description: Καθορίζει τις ιδιότητες του IMathNaryOperator
type: docs
url: /el/com.aspose.slides/imathnaryoperatorproperties/
---```
public interface IMathNaryOperatorProperties
```

Καθορίζει τις ιδιότητες του IMathNaryOperator
## Methods

| Method | Description |
| --- | --- |
| [getOperator()](#getOperator--) | Χαρακτήρας Nary Operator Για παράδειγμα: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Χαρακτήρας Nary Operator Για παράδειγμα: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | Η θέση των ορίων (υποσέλιδο και υπερσέλιδο) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | Η θέση των ορίων (υποσέλιδο και υπερσέλιδο) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Ο Χαρακτήρας του Τελεστή μεγαλώνει κατακόρυφα ώστε να ταιριάζει με το ύψος του τελεσίου |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Ο Χαρακτήρας του Τελεστή μεγαλώνει κατακόρυφα ώστε να ταιριάζει με το ύψος του τελεσίου |
| [getHideSubscript()](#getHideSubscript--) | Απόκρυψη Υποσέλιδο |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | Απόκρυψη Υποσέλιδο |
| [getHideSuperscript()](#getHideSuperscript--) | Απόκρυψη Υπερσέλιδο |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | Απόκρυψη Υπερσέλιδο |
### getOperator() {#getOperator--}
```
public abstract char getOperator()
```


Χαρακτήρας Nary Operator Για παράδειγμα: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Returns:**
char
### setOperator(char value) {#setOperator-char-}
```
public abstract void setOperator(char value)
```


Χαρακτήρας Nary Operator Για παράδειγμα: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

### getLimitLocation() {#getLimitLocation--}
```
public abstract int getLimitLocation()
```


Η θέση των ορίων (υποσέλιδο και υπερσέλιδο)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Returns:**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public abstract void setLimitLocation(int value)
```


Η θέση των ορίων (υποσέλιδο και υπερσέλιδο)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```


Ο Χαρακτήρας του Τελεστή μεγαλώνει κατακόρυφα ώστε να ταιριάζει με το ύψος του τελεσίου

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Returns:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```


Ο Χαρακτήρας του Τελεστή μεγαλώνει κατακόρυφα ώστε να ταιριάζει με το ύψος του τελεσίου

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideSubscript() {#getHideSubscript--}
```
public abstract boolean getHideSubscript()
```


Απόκρυψη Υποσέλιδο

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```


**Returns:**
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public abstract void setHideSubscript(boolean value)
```


Απόκρυψη Υποσέλιδο

--------------------

> ```
> Παράδειγμα:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideSuperscript() {#getHideSuperscript--}
```
public abstract boolean getHideSuperscript()
```


Απόκρυψη Υπερσέλιδο

--------------------

> ```
> Παράδειγμα:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```


**Returns:**
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public abstract void setHideSuperscript(boolean value)
```


Απόκρυψη Υπερσέλιδο

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |