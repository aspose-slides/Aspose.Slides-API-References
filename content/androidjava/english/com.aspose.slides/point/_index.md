---
title: Point
second_title: Aspose.Slides for Android via Java API Reference
description: Represent animation point.
type: docs
url: /com.aspose.slides/point/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IPoint](../../com.aspose.slides/ipoint)
```
public class Point implements IPoint
```

Represent animation point.
## Constructors

| Constructor | Description |
| --- | --- |
| [Point()](#Point--) | Default constructor. |
| [Point(float time, Object value, String formula)](#Point-float-java.lang.Object-java.lang.String-) | Create animation point with time, value and formula. |
## Methods

| Method | Description |
| --- | --- |
| [getTime()](#getTime--) | Represents time value. |
| [setTime(float value)](#setTime-float-) | Represents time value. |
| [getValue()](#getValue--) | Represents point value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Represents point value. |
| [getFormula()](#getFormula--) | Formulas within values, from, to, by attributes can be made up of these: Standard arithmetic operators: \\u2018+\\u2019, \\u2018-\\u2018, \\u2018\*\\u2019, \\u2018/\\u2019, \\u2018^\\u2019, \\u2018%\\u2019 (mod) Constants: \\u2018pi\\u2019 \\u2018e\\u2019 Conditional operators: \\u2018abs\\u2019, \\u2018min\\u2019, \\u2018max\\u2019, \\u2018?\\u2019 |
| [setFormula(String value)](#setFormula-java.lang.String-) | Formulas within values, from, to, by attributes can be made up of these: Standard arithmetic operators: \\u2018+\\u2019, \\u2018-\\u2018, \\u2018\*\\u2019, \\u2018/\\u2019, \\u2018^\\u2019, \\u2018%\\u2019 (mod) Constants: \\u2018pi\\u2019 \\u2018e\\u2019 Conditional operators: \\u2018abs\\u2019, \\u2018min\\u2019, \\u2018max\\u2019, \\u2018?\\u2019 |
### Point() {#Point--}
```
public Point()
```


Default constructor.

### Point(float time, Object value, String formula) {#Point-float-java.lang.Object-java.lang.String-}
```
public Point(float time, Object value, String formula)
```


Create animation point with time, value and formula.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| time | float | Time value. |
| value | java.lang.Object | Point value. |
| formula | java.lang.String | Formula. |

### getTime() {#getTime--}
```
public final float getTime()
```


Represents time value. Read/write float.

**Returns:**
float
### setTime(float value) {#setTime-float-}
```
public final void setTime(float value)
```


Represents time value. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


Represents point value. Only: bool, ColorFormat, float, int, string. Read/write Object.

**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Represents point value. Only: bool, ColorFormat, float, int, string. Read/write Object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```


Formulas within values, from, to, by attributes can be made up of these: Standard arithmetic operators: \\u2018+\\u2019, \\u2018-\\u2018, \\u2018\*\\u2019, \\u2018/\\u2019, \\u2018^\\u2019, \\u2018%\\u2019 (mod) Constants: \\u2018pi\\u2019 \\u2018e\\u2019 Conditional operators: \\u2018abs\\u2019, \\u2018min\\u2019, \\u2018max\\u2019, \\u2018?\\u2019 (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: \\u2018sin()\\u2019, \\u2018cos()\\u2019, \\u2018tan()\\u2019, \\u2018asin()\\u2019, \\u2018acos()\\u2019, \\u2018atan()\\u2019 Natural logarithm \\u2018ln()\\u2019 Property references (host supported properties) for example: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Read/write String.

**Returns:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```


Formulas within values, from, to, by attributes can be made up of these: Standard arithmetic operators: \\u2018+\\u2019, \\u2018-\\u2018, \\u2018\*\\u2019, \\u2018/\\u2019, \\u2018^\\u2019, \\u2018%\\u2019 (mod) Constants: \\u2018pi\\u2019 \\u2018e\\u2019 Conditional operators: \\u2018abs\\u2019, \\u2018min\\u2019, \\u2018max\\u2019, \\u2018?\\u2019 (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: \\u2018sin()\\u2019, \\u2018cos()\\u2019, \\u2018tan()\\u2019, \\u2018asin()\\u2019, \\u2018acos()\\u2019, \\u2018atan()\\u2019 Natural logarithm \\u2018ln()\\u2019 Property references (host supported properties) for example: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

