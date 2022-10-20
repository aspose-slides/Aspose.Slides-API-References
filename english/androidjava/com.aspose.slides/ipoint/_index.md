---
title: IPoint
second_title: Aspose.Slides for Android via Java API Reference
description: Represent animation point.
type: docs
weight: 967
url: /androidjava/com.aspose.slides/ipoint/
---```
public interface IPoint
```

Represent animation point.
## Methods

| Method | Description |
| --- | --- |
| [getTime()](#getTime--) | Represents time value. |
| [setTime(float value)](#setTime-float-) | Represents time value. |
| [getValue()](#getValue--) | Represents point value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Represents point value. |
| [getFormula()](#getFormula--) | Formulas within values, from, to, by attributes can be made up of these: Standard arithmetic operators: '+', '-', '\*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' |
| [setFormula(String value)](#setFormula-java.lang.String-) | Formulas within values, from, to, by attributes can be made up of these: Standard arithmetic operators: '+', '-', '\*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' |
### getTime() {#getTime--}
```
public abstract float getTime()
```


Represents time value. Read/write float.

**Returns:**
float
### setTime(float value) {#setTime-float-}
```
public abstract void setTime(float value)
```


Represents time value. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```


Represents point value. Only: bool, ColorFormat, float, int, string. Read/write Object.

**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Represents point value. Only: bool, ColorFormat, float, int, string. Read/write Object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public abstract String getFormula()
```


Formulas within values, from, to, by attributes can be made up of these: Standard arithmetic operators: '+', '-', '\*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Read/write String.

**Returns:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```


Formulas within values, from, to, by attributes can be made up of these: Standard arithmetic operators: '+', '-', '\*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

