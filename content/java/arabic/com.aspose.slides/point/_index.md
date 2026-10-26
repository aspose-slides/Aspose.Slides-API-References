---
title: Point
second_title: Aspose.Slides للـ Java مرجع واجهة برمجة التطبيقات
description: يمثل نقطة الرسوم المتحركة.
type: docs
url: /ar/com.aspose.slides/point/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IPoint](../../com.aspose.slides/ipoint)
```
public class Point implements IPoint
```

يمثل نقطة الرسوم المتحركة.
## البنّاءات

| المنشئ | الوصف |
| --- | --- |
| [Point()](#Point--) | Default constructor. |
| [Point(float time, Object value, String formula)](#Point-float-java.lang.Object-java.lang.String-) | Create animation point with time, value and formula. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getTime()](#getTime--) | Represents time value. |
| [setTime(float value)](#setTime-float-) | Represents time value. |
| [getValue()](#getValue--) | Represents point value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Represents point value. |
| [getFormula()](#getFormula--) | Formulas within values, from, to, by attributes can be made up of these: Standard arithmetic operators: '+', '-', '*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Read/write String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Formulas within values, from, to, by attributes can be made up of these: Standard arithmetic operators: '+', '-', '*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Read/write String. |
### Point() {#Point--}
```
public Point()
```


المنشئ الافتراضي.

### Point(float time, Object value, String formula) {#Point-float-java.lang.Object-java.lang.String-}
```
public Point(float time, Object value, String formula)
```


إنشاء نقطة الرسوم المتحركة مع الوقت، القيمة والصيغة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| time | float | قيمة الوقت. |
| value | java.lang.Object | قيمة النقطة. |
| formula | java.lang.String | الصيغة. |

### getTime() {#getTime--}
```
public final float getTime()
```


يمثل قيمة الوقت. قراءة/كتابة float.

**الإرجاع:**
float
### setTime(float value) {#setTime-float-}
```
public final void setTime(float value)
```


يمثل قيمة الوقت. قراءة/كتابة float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


يمثل قيمة النقطة. فقط: bool, ColorFormat, float, int, string. قراءة/كتابة Object.

**الإرجاع:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


يمثل قيمة النقطة. فقط: bool, ColorFormat, float, int, string. قراءة/كتابة Object.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```


Formulas within values, from, to, by attributes can be made up of these: Standard arithmetic operators: '+', '-', '*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Read/write String.

**الإرجاع:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```


Formulas within values, from, to, by attributes can be made up of these: Standard arithmetic operators: '+', '-', '*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Read/write String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |