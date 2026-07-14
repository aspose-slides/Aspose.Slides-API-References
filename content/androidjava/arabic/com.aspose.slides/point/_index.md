---
title: Point
second_title: Aspose.Slides لأندرويد عبر مرجع واجهة برمجة التطبيقات Java
description: تمثيل نقطة الرسوم المتحركة.
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

تمثيل نقطة الرسوم المتحركة.
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [Point()](#Point--) | المُنشئ الافتراضي. |
| [Point(float time, Object value, String formula)](#Point-float-java.lang.Object-java.lang.String-) | إنشاء نقطة رسوم متحركة مع الوقت والقيمة والصيغة. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getTime()](#getTime--) | يمثل قيمة الوقت. |
| [setTime(float value)](#setTime-float-) | يمثل قيمة الوقت. |
| [getValue()](#getValue--) | يمثل قيمة النقطة. |
| [setValue(Object value)](#setValue-java.lang.Object-) | يمثل قيمة النقطة. |
| [getFormula()](#getFormula--) | يمكن تكوين الصيغ داخل القيم، والسمات from و to و by من خلال ما يلي: عوامل حسابية قياسية: '+', '-', '*', '/', '^', '%' (mod) ثوابت: 'pi' 'e' عوامل شرطية: 'abs', 'min', 'max', '?' (if) عوامل مقارنة: '==', '>=', '', '!=', '!' عوامل مثلثية: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' اللوغاريتم الطبيعي 'ln()' مراجع خصائص (الخصائص المدعومة من المضيف) على سبيل المثال: "\#ppt\_x+(cos(-2*pi*(1-$))*-\#ppt\_x-sin(-2*pi*(1-$))*(1-\#ppt\_y))*(1-$)" قراءة/كتابة String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | يمكن تكوين الصيغ داخل القيم، والسمات from و to و by من خلال ما يلي: عوامل حسابية قياسية: '+', '-', '*', '/', '^', '%' (mod) ثوابت: 'pi' 'e' عوامل شرطية: 'abs', 'min', 'max', '?' (if) عوامل مقارنة: '==', '>=', '', '!=', '!' عوامل مثلثية: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' اللوغاريتم الطبيعي 'ln()' مراجع خصائص (الخصائص المدعومة من المضيف) على سبيل المثال: "\#ppt\_x+(cos(-2*pi*(1-$))*-\#ppt\_x-sin(-2*pi*(1-$))*(1-\#ppt\_y))*(1-$)" قراءة/كتابة String.

### Point() {#Point--}
```
public Point()
```


المُنشئ الافتراضي.

### Point(float time, Object value, String formula) {#Point-float-java.lang.Object-java.lang.String-}
```
public Point(float time, Object value, String formula)
```


إنشاء نقطة رسوم متحركة مع الوقت والقيمة والصيغة.

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

**القيمة المرجعة:**
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


يمثل قيمة النقطة. القيم المسموح بها فقط: bool, ColorFormat, float, int, string. قراءة/كتابة Object.

**القيمة المرجعة:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


يمثل قيمة النقطة. القيم المسموح بها فقط: bool, ColorFormat, float, int, string. قراءة/كتابة Object.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```


يمكن تكوين الصيغ داخل القيم، والسمات from و to و by من خلال ما يلي: عوامل حسابية قياسية: '+', '-', '*', '/', '^', '%' (mod) ثوابت: 'pi' 'e' عوامل شرطية: 'abs', 'min', 'max', '?' (if) عوامل مقارنة: '==', '>=', '', '!=', '!' عوامل مثلثية: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' اللوغاريتم الطبيعي 'ln()' مراجع خصائص (الخصائص المدعومة من المضيف) على سبيل المثال: "\#ppt\_x+(cos(-2*pi*(1-$))*-\#ppt\_x-sin(-2*pi*(1-$))*(1-\#ppt\_y))*(1-$)" قراءة/كتابة String.

**القيمة المرجعة:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```


يمكن تكوين الصيغ داخل القيم، والسمات from و to و by من خلال ما يلي: عوامل حسابية قياسية: '+', '-', '*', '/', '^', '%' (mod) ثوابت: 'pi' 'e' عوامل شرطية: 'abs', 'min', 'max', '?' (if) عوامل مقارنة: '==', '>=', '', '!=', '!' عوامل مثلثية: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' اللوغاريتم الطبيعي 'ln()' مراجع خصائص (الخصائص المدعومة من المضيف) على سبيل المثال: "\#ppt\_x+(cos(-2*pi*(1-$))*-\#ppt\_x-sin(-2*pi*(1-$))*(1-\#ppt\_y))*(1-$)" قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |