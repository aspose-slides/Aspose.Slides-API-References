---
title: IPoint
second_title: Aspose.Slides for Android via Java API Reference
description: Αναπαριστά σημείο κίνησης.
type: docs
url: /el/com.aspose.slides/ipoint/
---```
public interface IPoint
```

Αναπαριστά σημείο κίνησης.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getTime()](#getTime--) | Αναπαριστά την τιμή του χρόνου. |
| [setTime(float value)](#setTime-float-) | Αναπαριστά την τιμή του χρόνου. |
| [getValue()](#getValue--) | Αναπαριστά την τιμή του σημείου. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Αναπαριστά την τιμή του σημείου. |
| [getFormula()](#getFormula--) | Οι τύποι εντός τιμών, των χαρακτηριστικών from, to, by, μπορούν να αποτελούνται από τα εξής: Standard arithmetic operators: '+', '-', '\*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Ανάγνωση/εγγραφή String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Οι τύποι εντός τιμών, των χαρακτηριστικών from, to, by, μπορούν να αποτελούνται από τα εξής: Standard arithmetic operators: '+', '-', '\*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Ανάγνωση/εγγραφή String. |
### getTime() {#getTime--}
```
public abstract float getTime()
```

Αναπαριστά την τιμή του χρόνου. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setTime(float value) {#setTime-float-}
```
public abstract void setTime(float value)
```

Αναπαριστά την τιμή του χρόνου. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```

Αναπαριστά την τιμή του σημείου. Μόνο: bool, ColorFormat, float, int, string. Ανάγνωση/εγγραφή Object.

**Επιστρέφει:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Αναπαριστά την τιμή του σημείου. Μόνο: bool, ColorFormat, float, int, string. Ανάγνωση/εγγραφή Object.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public abstract String getFormula()
```

Οι τύποι εντός τιμών, των χαρακτηριστικών from, to, by, μπορούν να αποτελούνται από τα εξής: Standard arithmetic operators: '+', '-', '\*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```

Οι τύποι εντός τιμών, των χαρακτηριστικών from, to, by, μπορούν να αποτελούνται από τα εξής: Standard arithmetic operators: '+', '-', '\*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |