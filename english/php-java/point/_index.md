---
title: Point
type: docs
weight: 0
url: /php-java/point/
---

# Point class

 Represent animation point.
 

## Constructors

| name | description |
| --- | --- |
| [Point](/php-java/point/point/)() | Default constructor. |
| [Point](/php-java/point/point/)(float, Object, String) | Create animation point with time, value and formula. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getFormula](/php-java/point/getformula/)() | String | Formulas within values, from, to, by attributes can be made up of these: Standard arithmetic operators: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod) Constants: ‘pi’ ‘e’ Conditional operators: ‘abs’, ‘min’, ‘max’, ‘?’ (if) Comparison operators: '==', '&gt;=', '', '!=', '!' Trigonometric operators: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’ Natural logarithm ‘ln()’ Property references (host supported properties) for example: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)" Read/write String. |
| [getTime](/php-java/point/gettime/)() | float | Represents time value. Read/write float. |
| [getValue](/php-java/point/getvalue/)() | Object | Represents point value. Only: bool, ColorFormat, float, int, string. Read/write Object. |
| [setFormula](/php-java/point/setformula/)(String) | void | Formulas within values, from, to, by attributes can be made up of these: Standard arithmetic operators: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod) Constants: ‘pi’ ‘e’ Conditional operators: ‘abs’, ‘min’, ‘max’, ‘?’ (if) Comparison operators: '==', '&gt;=', '', '!=', '!' Trigonometric operators: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’ Natural logarithm ‘ln()’ Property references (host supported properties) for example: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)" Read/write String. |
| [setTime](/php-java/point/settime/)(float) | void | Represents time value. Read/write float. |
| [setValue](/php-java/point/setvalue/)(Object) | void | Represents point value. Only: bool, ColorFormat, float, int, string. Read/write Object. |
