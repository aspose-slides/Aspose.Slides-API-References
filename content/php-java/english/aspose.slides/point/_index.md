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

 **Returns:**
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

 **Returns:**
Point


---


### getFormula {#getFormula}

| Name | Description |
| --- | --- |
| getFormula () | Formulas within values, from, to, by attributes can be made up of these: Standard arithmetic operators: &#39+&#39, &#39-&#39, &#39*&#39, &#39/&#39, &#39^&#39, &#39%&#39 (mod) Constants: &#39pi&#39 &#39e&#39 Conditional operators: &#39abs&#39, &#39min&#39, &#39max&#39, &#39&#63&#39 (if) Comparison operators: &#39==&#39, &#39&gt;=&#39, &#39&#39, &#39&#33&#61&#39, &#39&#33&#39 Trigonometric operators: &#39sin()&#39, &#39cos()&#39, &#39tan()&#39, &#39asin()&#39, &#39acos()&#39, &#39atan()&#39 Natural logarithm &#39ln()&#39 Property references (host supported properties) for example: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)" Read/write String. |

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
| setFormula (String) | Formulas within values, from, to, by attributes can be made up of these: Standard arithmetic operators: &#39+&#39, &#39-&#39, &#39*&#39, &#39/&#39, &#39^&#39, &#39%&#39 (mod) Constants: &#39pi&#39 &#39e&#39 Conditional operators: &#39abs&#39, &#39min&#39, &#39max&#39, &#39&#63&#39 (if) Comparison operators: &#39==&#39, &#39&gt;=&#39, &#39&#39, &#39&#33&#61&#39, &#39&#33&#39 Trigonometric operators: &#39sin()&#39, &#39cos()&#39, &#39tan()&#39, &#39asin()&#39, &#39acos()&#39, &#39atan()&#39 Natural logarithm &#39ln()&#39 Property references (host supported properties) for example: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)" Read/write String. |

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


