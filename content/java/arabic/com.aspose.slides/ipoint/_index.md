---
title: IPoint
second_title: Aspose.Slides for Java API Reference
description: يمثل نقطة الرسوم المتحركة.
type: docs
url: /ar/com.aspose.slides/ipoint/
---```
public interface IPoint
```

يمثل نقطة الرسوم المتحركة.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getTime()](#getTime--) | يمثل قيمة الوقت. |
| [setTime(float value)](#setTime-float-) | يمثل قيمة الوقت. |
| [getValue()](#getValue--) | يمثل قيمة النقطة. |
| [setValue(Object value)](#setValue-java.lang.Object-) | يمثل قيمة النقطة. |
| [getFormula()](#getFormula--) | الصيغ داخل القيم، والخصائص from, to, by يمكن أن تتكون من التالي: عوامل حسابية قياسية: '+', '-', '*', '/', '^', '%' (mod) ثوابت: 'pi' 'e' عوامل شرطيّة: 'abs', 'min', 'max', '?' (if) عوامل مقارنة: '==', '>=', '', '!=', '!' عوامل مثلثية: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' اللوغاريتم الطبيعي 'ln()' مراجع الخصائص (الخصائص المدعومة من المضيف) على سبيل المثال: \"\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)\" قراءة/كتابة String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | الصيغ داخل القيم، والخصائص from, to, by يمكن أن تتكون من التالي: عوامل حسابية قياسية: '+', '-', '*', '/', '^', '%' (mod) ثوابت: 'pi' 'e' عوامل شرطيّة: 'abs', 'min', 'max', '?' (if) عوامل مقارنة: '==', '>=', '', '!=', '!' عوامل مثلثية: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' اللوغاريتم الطبيعي 'ln()' مراجع الخصائص (الخصائص المدعومة من المضيف) على سبيل المثال: \"\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)\" قراءة/كتابة String. |
### getTime() {#getTime--}
```
public abstract float getTime()
```

يمثل قيمة الوقت. قراءة/كتابة float.

**الإرجاع:**
float
### setTime(float value) {#setTime-float-}
```
public abstract void setTime(float value)
```

يمثل قيمة الوقت. قراءة/كتابة float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

يمثل قيمة النقطة. فقط: bool, ColorFormat, float, int, string. قراءة/كتابة Object.

**الإرجاع:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

يمثل قيمة النقطة. فقط: bool, ColorFormat, float, int, string. قراءة/كتابة Object.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.Object |  |
### getFormula() {#getFormula--}
```
public abstract String getFormula()
```

الصيغ داخل القيم، والخصائص from, to, by يمكن أن تتكون من التالي: عوامل حسابية قياسية: '+', '-', '*', '/', '^', '%' (mod) ثوابت: 'pi' 'e' عوامل شرطيّة: 'abs', 'min', 'max', '?' (if) عوامل مقارنة: '==', '>=', '', '!=', '!' عوامل مثلثية: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' اللوغاريتم الطبيعي 'ln()' مراجع الخصائص (الخصائص المدعومة من المضيف) على سبيل المثال: \"\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)\" قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```

الصيغ داخل القيم، والخصائص from, to, by يمكن أن تتكون من التالي: عوامل حسابية قياسية: '+', '-', '*', '/', '^', '%' (mod) ثوابت: 'pi' 'e' عوامل شرطيّة: 'abs', 'min', 'max', '?' (if) عوامل مقارنة: '==', '>=', '', '!=', '!' عوامل مثلثية: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' اللوغاريتم الطبيعي 'ln()' مراجع الخصائص (الخصائص المدعومة من المضيف) على سبيل المثال: \"\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)\" قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |