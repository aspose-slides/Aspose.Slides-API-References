---
title: Point
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αντιπροσωπεύει σημείο κινούμενου σχεδίου.
type: docs
url: /el/com.aspose.slides/point/
---
**Κληρονόμηση:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IPoint](../../com.aspose.slides/ipoint)
```
public class Point implements IPoint
```

Αντιπροσωπεύει σημείο κινούμενου σχεδίου.
## Κατασκευαστές

| Constructor | Description |
| --- | --- |
| [Point()](#Point--) | Προεπιλεγμένος κατασκευαστής. |
| [Point(float time, Object value, String formula)](#Point-float-java.lang.Object-java.lang.String-) | Δημιουργεί σημείο κινούμενου σχεδίου με χρόνο, τιμή και τύπο. |
## Μέθοδοι

| Method | Description |
| --- | --- |
| [getTime()](#getTime--) | Αντιπροσωπεύει την τιμή χρόνου. |
| [setTime(float value)](#setTime-float-) | Αντιπροσωπεύει την τιμή χρόνου. |
| [getValue()](#getValue--) | Αντιπροσωπεύει την τιμή του σημείου. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Αντιπροσωπεύει την τιμή του σημείου. |
| [getFormula()](#getFormula--) | Οι τύποι εντός τιμών, χαρακτηριστικών from, to, by μπορούν να αποτελούνται από τα εξής: Standard arithmetic operators: '+', '-', '*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Διαβάσιμο/εγγράψιμο String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Οι τύποι εντός τιμών, χαρακτηριστικών from, to, by μπορούν να αποτελούνται από τα εξής: Standard arithmetic operators: '+', '-', '*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Διαβάσιμο/εγγράψιμο String. |
### Point() {#Point--}
```
public Point()
```

Προεπιλεγμένος κατασκευαστής.

### Point(float time, Object value, String formula) {#Point-float-java.lang.Object-java.lang.String-}
```
public Point(float time, Object value, String formula)
```

Δημιουργεί σημείο κινούμενου σχεδίου με χρόνο, τιμή και τύπο.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| time | float | Τιμή χρόνου. |
| value | java.lang.Object | Τιμή σημείου. |
| formula | java.lang.String | Τύπος. |

### getTime() {#getTime--}
```
public final float getTime()
```

Αντιπροσωπεύει την τιμή χρόνου. Διαβάσιμο/εγγράψιμο float.

**Returns:**
float
### setTime(float value) {#setTime-float-}
```
public final void setTime(float value)
```

Αντιπροσωπεύει την τιμή χρόνου. Διαβάσιμο/εγγράψιμο float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

Αντιπροσωπεύει την τιμή του σημείου. Μόνο: bool, ColorFormat, float, int, string. Διαβάσιμο/εγγράψιμο Object.

**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

Αντιπροσωπεύει την τιμή του σημείου. Μόνο: bool, ColorFormat, float, int, string. Διαβάσιμο/εγγράψιμο Object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```

Οι τύποι εντός τιμών, χαρακτηριστικών from, to, by μπορούν να αποτελούνται από τα εξής: Standard arithmetic operators: '+', '-', '*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Διαβάσιμο/εγγράψιμο String.

**Returns:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```

Οι τύποι εντός τιμών, χαρακτηριστικών from, to, by μπορούν να αποτελούνται από τα εξής: Standard arithmetic operators: '+', '-', '*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) για παράδειγμα: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Διαβάσιμο/εγγράψιμο String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |