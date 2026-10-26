---
title: ITrendline
second_title: مرجع API لـ Aspose.Slides للـ Java
description: الفئة تمثل خط الاتجاه لسلسلة المخطط
type: docs
url: /ar/com.aspose.slides/itrendline/
---
**كل الواجهات المنفذة:**
[com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext)
```
public interface ITrendline extends IOverridableText
```

الفئة تمثل خط الاتجاه لسلسلة المخطط
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | تحصل أو تعين اسم خط الاتجاه. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | تحصل أو تعين اسم خط الاتجاه. |
| [getTrendlineType()](#getTrendlineType--) | تحصل أو تعين نوع خط الاتجاه. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | تحصل أو تعين نوع خط الاتجاه. |
| [getFormat()](#getFormat--) | يمثل تنسيق خط الاتجاه. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | يمثل تنسيق خط الاتجاه. |
| [getBackward()](#getBackward--) | يحدد عدد الفئات (أو الوحدات في مخطط التشتت) التي يمتد إليها خط الاتجاه قبل البيانات للسلسلة المتجهة. |
| [setBackward(double value)](#setBackward-double-) | يحدد عدد الفئات (أو الوحدات في مخطط التشتت) التي يمتد إليها خط الاتجاه قبل البيانات للسلسلة المتجهة. |
| [getForward()](#getForward--) | يحدد عدد الفئات (أو الوحدات في مخطط التشتت) التي يمتد إليها خط الاتجاه بعد البيانات للسلسلة المتجهة. |
| [setForward(double value)](#setForward-double-) | يحدد عدد الفئات (أو الوحدات في مخطط التشتت) التي يمتد إليها خط الاتجاه بعد البيانات للسلسلة المتجهة. |
| [getIntercept()](#getIntercept--) | يحدد القيمة التي يعبر عندها خط الاتجاه محور Y. |
| [setIntercept(double value)](#setIntercept-double-) | يحدد القيمة التي يعبر عندها خط الاتجاه محور Y. |
| [getDisplayEquation()](#getDisplayEquation--) | يحدد أن معادلة خط الاتجاه تُعرض على المخطط (في نفس التسمية مثل قيمة Rsquaredvalue). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | يحدد أن معادلة خط الاتجاه تُعرض على المخطط (في نفس التسمية مثل قيمة Rsquaredvalue). |
| [getOrder()](#getOrder--) | يحدد رتبة خط الاتجاه متعدد الحدود. |
| [setOrder(byte value)](#setOrder-byte-) | يحدد رتبة خط الاتجاه متعدد الحدود. |
| [getPeriod()](#getPeriod--) | يحدد فترة خط الاتجاه لخط الاتجاه المتحرك للمتوسط. |
| [setPeriod(byte value)](#setPeriod-byte-) | يحدد فترة خط الاتجاه لخط الاتجاه المتحرك للمتوسط. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | يحدد أن قيمة R-squared لخط الاتجاه تُعرض على المخطط (في نفس التسمية مع المعادلة). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | يحدد أن قيمة R-squared لخط الاتجاه تُعرض على المخطط (في نفس التسمية مع المعادلة). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | يمثل مدخل الأسطورة المتعلق بهذا خط الاتجاه للقراءة فقط [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
### getTrendlineName() {#getTrendlineName--}
```
public abstract String getTrendlineName()
```

تحصل أو تعين اسم خط الاتجاه. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public abstract void setTrendlineName(String value)
```

تحصل أو تعين اسم خط الاتجاه. قراءة/كتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getTrendlineType() {#getTrendlineType--}
```
public abstract int getTrendlineType()
```

تحصل أو تعين نوع خط الاتجاه. قراءة/كتابة [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**الإرجاع:**
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public abstract void setTrendlineType(int value)
```

تحصل أو تعين نوع خط الاتجاه. قراءة/كتابة [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

يمثل تنسيق خط الاتجاه. قراءة/كتابة [IFormat](../../com.aspose.slides/iformat).

**الإرجاع:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

يمثل تنسيق خط الاتجاه. قراءة/كتابة [IFormat](../../com.aspose.slides/iformat).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getBackward() {#getBackward--}
```
public abstract double getBackward()
```

يحدد عدد الفئات (أو الوحدات في مخطط التشتت) التي يمتد إليها خط الاتجاه قبل البيانات للسلسلة المتجهة. في مخططات التشتت وغير التشتت، يجب أن تكون القيمة غير سالبة. قراءة/كتابة double.

**الإرجاع:**
double
### setBackward(double value) {#setBackward-double-}
```
public abstract void setBackward(double value)
```

يحدد عدد الفئات (أو الوحدات في مخطط التشتت) التي يمتد إليها خط الاتجاه قبل البيانات للسلسلة المتجهة. في مخططات التشتت وغير التشتت، يجب أن تكون القيمة غير سالبة. قراءة/كتابة double.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### getForward() {#getForward--}
```
public abstract double getForward()
```

يحدد عدد الفئات (أو الوحدات في مخطط التشتت) التي يمتد إليها خط الاتجاه بعد البيانات للسلسلة المتجهة. في مخططات التشتت وغير التشتت، يجب أن تكون القيمة غير سلبية. قراءة/كتابة double.

**الإرجاع:**
double
### setForward(double value) {#setForward-double-}
```
public abstract void setForward(double value)
```

يحدد عدد الفئات (أو الوحدات في مخطط التشتت) التي يمتد إليها خط الاتجاه بعد البيانات للسلسلة المتجهة. في مخططات التشتت وغير التشتت، يجب أن تكون القيمة غير سلبية. قراءة/كتابة double.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### getIntercept() {#getIntercept--}
```
public abstract double getIntercept()
```

يحدد القيمة التي يعبر عندها خط الاتجاه محور Y. تدعم هذه الخاصية فقط عندما يكون نوع خط الاتجاه exp أو linear أو poly. قراءة/كتابة double.

**الإرجاع:**
double
### setIntercept(double value) {#setIntercept-double-}
```
public abstract void setIntercept(double value)
```

يحدد القيمة التي يعبر عندها خط الاتجاه محور Y. تدعم هذه الخاصية فقط عندما يكون نوع خط الاتجاه exp أو linear أو poly. قراءة/كتابة double.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### getDisplayEquation() {#getDisplayEquation--}
```
public abstract boolean getDisplayEquation()
```

يحدد أن معادلة خط الاتجاه تُعرض على المخطط (في نفس التسمية مثل قيمة Rsquaredvalue). قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public abstract void setDisplayEquation(boolean value)
```

يحدد أن معادلة خط الاتجاه تُعرض على المخطط (في نفس التسمية مثل قيمة Rsquaredvalue). قراءة/كتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getOrder() {#getOrder--}
```
public abstract byte getOrder()
```

يحدد رتبة خط الاتجاه متعدد الحدود. يتم تجاهله لأنواع خطوط الاتجاه الأخرى. يجب أن تكون القيمة بين 2 و 6. قراءة/كتابة byte.

**الإرجاع:**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public abstract void setOrder(byte value)
```

يحدد رتبة خط الاتجاه متعدد الحدود. يتم تجاهله لأنواع خطوط الاتجاه الأخرى. يجب أن تكون القيمة بين 2 و 6. قراءة/كتابة byte.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getPeriod() {#getPeriod--}
```
public abstract byte getPeriod()
```

يحدد فترة خط الاتجاه لخط الاتجاه المتحرك للمتوسط. يتم تجاهله لأنواع خطوط الاتجاه الأخرى. يجب أن تكون القيمة بين 2 و 255. قراءة/كتابة byte.

**الإرجاع:**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public abstract void setPeriod(byte value)
```

يحدد فترة خط الاتجاه لخط الاتجاه المتحرك للمتوسط. يتم تجاهله لأنواع خطوط الاتجاه الأخرى. يجب أن تكون القيمة بين 2 و 255. قراءة/كتابة byte.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public abstract boolean getDisplayRSquaredValue()
```

يحدد أن قيمة R-squared لخط الاتجاه تُعرض على المخطط (في نفس التسمية مع المعادلة). قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public abstract void setDisplayRSquaredValue(boolean value)
```

يحدد أن قيمة R-squared لخط الاتجاه تُعرض على المخطط (في نفس التسمية مع المعادلة). قراءة/كتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

يمثل مدخل الأسطورة المتعلق بهذا خط الاتجاه للقراءة فقط [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**الإرجاع:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)