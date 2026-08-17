---
title: Point
second_title: Aspose.Slides for Java Αναφορά API
description: Αναπαριστά σημείο κίνησης.
type: docs
url: /el/com.aspose.slides/point/
---
**Κληρονόμηση:**
java.lang.Object

**Όλες οι Υλοποιημένες Διασυνδέσεις:**
[com.aspose.slides.IPoint](../../com.aspose.slides/ipoint)
```
public class Point implements IPoint
```

Αναπαριστά το σημείο κίνησης.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Point()](#Point--) | Προεπιλεγμένος κατασκευαστής. |
| [Point(float time, Object value, String formula)](#Point-float-java.lang.Object-java.lang.String-) | Δημιουργεί σημείο κίνησης με χρόνο, τιμή και τύπο. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getTime()](#getTime--) | Αναπαριστά την τιμή χρόνου. |
| [setTime(float value)](#setTime-float-) | Αναπαριστά την τιμή χρόνου. |
| [getValue()](#getValue--) | Αναπαριστά την τιμή του σημείου. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Αναπαριστά την τιμή του σημείου. |
| [getFormula()](#getFormula--) | Οι τύποι εντός τιμών, των ιδιοτήτων from, to, by μπορούν να αποτελούνται από τα ακόλουθα: Standard arithmetic operators: '+', '-', '*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "#ppt\_x+(cos(-2*pi*(1-$))*-#ppt\_x-sin(-2*pi*(1-$))*(1-#ppt\_y))*(1-$)" Αναγνώσιμο/εγγράψιμο String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Οι τύποι εντός τιμών, των ιδιοτήτων from, to, by μπορούν να αποτελούνται από τα ακόλουθα: Standard arithmetic operators: '+', '-', '*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "#ppt\_x+(cos(-2*pi*(1-$))*-#ppt\_x-sin(-2*pi*(1-$))*(1-#ppt\_y))*(1-$)" Αναγνώσιμο/εγγράψιμο String. |
### Point() {#Point--}
```
public Point()
```

Προεπιλεγμένος κατασκευαστής.

### Point(float time, Object value, String formula) {#Point-float-java.lang.Object-java.lang.String-}
```
public Point(float time, Object value, String formula)
```

Δημιουργεί σημείο κίνησης με χρόνο, τιμή και τύπο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| time | float | Τιμή χρόνου. |
| value | java.lang.Object | Τιμή σημείου. |
| formula | java.lang.String | Τύπος. |

### getTime() {#getTime--}
```
public final float getTime()
```

Αναπαριστά την τιμή χρόνου. Αναγνώσιμο/εγγράψιμο float.

**Επιστρέφει:**
float
### setTime(float value) {#setTime-float-}
```
public final void setTime(float value)
```

Αναπαριστά την τιμή χρόνου. Αναγνώσιμο/εγγράψιμο float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

Αναπαριστά την τιμή του σημείου. Μόνο: bool, ColorFormat, float, int, string. Αναγνώσιμο/εγγράψιμο Object.

**Επιστρέφει:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

Αναπαριστά την τιμή του σημείου. Μόνο: bool, ColorFormat, float, int, string. Αναγνώσιμο/εγγράψιμο Object.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```

Οι τύποι εντός τιμών, των ιδιοτήτων from, to, by μπορούν να αποτελούνται από τα ακόλουθα: Standard arithmetic operators: '+', '-', '*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "#ppt\_x+(cos(-2*pi*(1-$))*-#ppt\_x-sin(-2*pi*(1-$))*(1-#ppt\_y))*(1-$)" Αναγνώσιμο/εγγράψιμο String.

**Επιστρέφει:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```

Οι τύποι εντός τιμών, των ιδιοτήτων from, to, by μπορούν να αποτελούνται από τα ακόλουθα: Standard arithmetic operators: '+', '-', '*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) για παράδειγμα: "#ppt\_x+(cos(-2*pi*(1-$))*-#ppt\_x-sin(-2*pi*(1-$))*(1-#ppt\_y))*(1-$)" Αναγνώσιμο/εγγράψιμο String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |