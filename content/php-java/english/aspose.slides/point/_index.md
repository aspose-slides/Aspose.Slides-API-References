---
title: Point
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/point/
---

## Point class

 Represent animation point.
 
### Point {#Point}

| Name | Description |
| --- | --- |
| Point() | Default function. |

 **Result:**
Point


---


### Point {#Point}

| Name | Description |
| --- | --- |
| Point(float, Object, String) | Create animation point with time, value and formula. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| time | float | Time value. |
| value | Object | Point value. |
| formula | String | Formula. |

 **Result:**
Point


---


### getFormula {#getFormula}

| Name | Description |
| --- | --- |
| getFormula () | Formulas within values, from, to, by attributes can be made up of these: Standard arithmetic operators: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod) Constants: ‘pi’ ‘e’ Conditional operators: ‘abs’, ‘min’, ‘max’, ‘?’ (if) Comparison operators: '==', '&gt;=', '', '!=', '!' Trigonometric operators: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’ Natural logarithm ‘ln()’ Property references (host supported properties) for example: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)" Read/write String. |

 **Returns:**
String


---


### getTime {#getTime}

| Name | Description |
| --- | --- |
| getTime () | Represents time value. Read/write float. |

 **Returns:**
float


---


### getValue {#getValue}

| Name | Description |
| --- | --- |
| getValue () | Represents point value. Only: bool, ColorFormat, float, int, string. Read/write Object. |

 **Returns:**
Object


---


### setFormula {#setFormula}

| Name | Description |
| --- | --- |
| setFormula (String) | Formulas within values, from, to, by attributes can be made up of these: Standard arithmetic operators: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod) Constants: ‘pi’ ‘e’ Conditional operators: ‘abs’, ‘min’, ‘max’, ‘?’ (if) Comparison operators: '==', '&gt;=', '', '!=', '!' Trigonometric operators: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’ Natural logarithm ‘ln()’ Property references (host supported properties) for example: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)" Read/write String. |

 **Returns:**
void


---


### setTime {#setTime}

| Name | Description |
| --- | --- |
| setTime (float) | Represents time value. Read/write float. |

 **Returns:**
void


---


### setValue {#setValue}

| Name | Description |
| --- | --- |
| setValue (Object) | Represents point value. Only: bool, ColorFormat, float, int, string. Read/write Object. |

 **Returns:**
void


---


