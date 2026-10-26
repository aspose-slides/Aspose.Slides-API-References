---
title: ITrendline
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: الفئة تمثل خط الاتجاه لسلسلة المخطط
type: docs
url: /ar/com.aspose.slides/itrendline/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext)
```
public interface ITrendline extends IOverridableText
```

الفئة تمثل خط الاتجاه لسلسلة المخطط
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | يحصل على اسم خط الاتجاه أو يضعه. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | يحصل على اسم خط الاتجاه أو يضعه. |
| [getTrendlineType()](#getTrendlineType--) | يحصل على نوع خط الاتجاه أو يضعه. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | يحصل على نوع خط الاتجاه أو يضعه. |
| [getFormat()](#getFormat--) | يمثل تنسيق خط الاتجاه. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | يمثل تنسيق خط الاتجاه. |
| [getBackward()](#getBackward--) | يحدد عدد الفئات (أو الوحدات في مخطط التبعثر) التي يمتد إليها خط الاتجاه قبل البيانات الخاصة بالسلسلة التي يتم تتبعها. |
| [setBackward(double value)](#setBackward-double-) | يحدد عدد الفئات (أو الوحدات في مخطط التبعثر) التي يمتد إليها خط الاتجاه قبل البيانات الخاصة بالسلسلة التي يتم تتبعها. |
| [getForward()](#getForward--) | يحدد عدد الفئات (أو الوحدات في مخطط التبعثر) التي يمتد إليها خط الاتجاه بعد البيانات الخاصة بالسلسلة التي يتم تتبعها. |
| [setForward(double value)](#setForward-double-) | يحدد عدد الفئات (أو الوحدات في مخطط التبعثر) التي يمتد إليها خط الاتجاه بعد البيانات الخاصة بالسلسلة التي يتم تتبعها. |
| [getIntercept()](#getIntercept--) | يحدد القيمة التي يتقاطع عندها خط الاتجاه مع المحور ص. |
| [setIntercept(double value)](#setIntercept-double-) | يحدد القيمة التي يتقاطع عندها خط الاتجاه مع المحور ص. |
| [getDisplayEquation()](#getDisplayEquation--) | يحدد أن معادلة خط الاتجاه تُعرض على المخطط (في نفس التسمية مثل قيمة Rsquaredvalue). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | يحدد أن معادلة خط الاتجاه تُعرض على المخطط (في نفس التسمية مثل قيمة Rsquaredvalue). |
| [getOrder()](#getOrder--) | يحدد ترتيب خط الاتجاه المتعدد الحدود. |
| [setOrder(byte value)](#setOrder-byte-) | يحدد ترتيب خط الاتجاه المتعدد الحدود. |
| [getPeriod()](#getPeriod--) | يحدد الفترة لخط الاتجاه لخط المتوسط المتحرك. |
| [setPeriod(byte value)](#setPeriod-byte-) | يحدد الفترة لخط الاتجاه لخط المتوسط المتحرك. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | يحدد أن قيمة R المربعة لخط الاتجاه تُعرض على المخطط (في نفس التسمية مثل المعادلة). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | يحدد أن قيمة R المربعة لخط الاتجاه تُعرض على المخطط (في نفس التسمية مثل المعادلة). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | يمثل إدخال وسيلة الإيضاح المتعلق بهذا خط الاتجاه للقراءة فقط [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
### getTrendlineName() {#getTrendlineName--}
```
public abstract String getTrendlineName()
```

يحصل على اسم خط الاتجاه أو يضعه. قابل للقراءة/الكتابة String.

**الإرجاع:**
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public abstract void setTrendlineName(String value)
```

يحصل على اسم خط الاتجاه أو يضعه. قابل للقراءة/الكتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getTrendlineType() {#getTrendlineType--}
```
public abstract int getTrendlineType()
```

يحصل على نوع خط الاتجاه أو يضعه. قابل للقراءة/الكتابة [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**الإرجاع:**
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public abstract void setTrendlineType(int value)
```

يحصل على نوع خط الاتجاه أو يضعه. قابل للقراءة/الكتابة [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

يمثل تنسيق خط الاتجاه. قابل للقراءة/الكتابة [IFormat](../../com.aspose.slides/iformat).

**الإرجاع:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

يمثل تنسيق خط الاتجاه. قابل للقراءة/الكتابة [IFormat](../../com.aspose.slides/iformat).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getBackward() {#getBackward--}
```
public abstract double getBackward()
```

يحدد عدد الفئات (أو الوحدات في مخطط التبعثر) التي يمتد إليها خط الاتجاه قبل البيانات الخاصة بالسلسلة التي يتم تتبعها. في المخططات التبعثريّة وغير التبعثريّة، يجب أن تكون القيمة غير سلبية. قابل للقراءة/الكتابة double.

**الإرجاع:**
double
### setBackward(double value) {#setBackward-double-}
```
public abstract void setBackward(double value)
```

يحدد عدد الفئات (أو الوحدات في مخطط التبعثر) التي يمتد إليها خط الاتجاه قبل البيانات الخاصة بالسلسلة التي يتم تتبعها. في المخططات التبعثريّة وغير التبعثريّة، يجب أن تكون القيمة غير سلبية. قابل للقراءة/الكتابة double.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### getForward() {#getForward--}
```
public abstract double getForward()
```

يحدد عدد الفئات (أو الوحدات في مخطط التبعثر) التي يمتد إليها خط الاتجاه بعد البيانات الخاصة بالسلسلة التي يتم تتبعها. في المخططات التبعثريّة وغير التبعثريّة، يجب أن تكون القيمة غير سلبية. قابل للقراءة/الكتابة double.

**الإرجاع:**
double
### setForward(double value) {#setForward-double-}
```
public abstract void setForward(double value)
```

يحدد عدد الفئات (أو الوحدات في مخطط التبعثر) التي يمتد إليها خط الاتجاه بعد البيانات الخاصة بالسلسلة التي يتم تتبعها. في المخططات التبعثريّة غير التبعثريّة، يجب أن تكون القيمة غير سلبية. قابل للقراءة/الكتابة double.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### getIntercept() {#getIntercept--}
```
public abstract double getIntercept()
```

يحدد القيمة التي يتقاطع عندها خط الاتجاه مع المحور ص. يجب أن يكون هذا الخصائص مدعومة فقط عندما يكون نوع خط الاتجاه إما exp أو linear أو poly. قابل للقراءة/الكتابة double.

**الإرجاع:**
double
### setIntercept(double value) {#setIntercept-double-}
```
public abstract void setIntercept(double value)
```

يحدد القيمة التي يتقاطع عندها خط الاتجاه مع المحور ص. يجب أن يكون هذا الخصائص مدعومة فقط عندما يكون نوع خط الاتجاه إما exp أو linear أو poly. قابل للقراءة/الكتابة double.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### getDisplayEquation() {#getDisplayEquation--}
```
public abstract boolean getDisplayEquation()
```

يحدد أن معادلة خط الاتجاه تُعرض على المخطط (في نفس التسمية مثل قيمة Rsquaredvalue). قابل للقراءة/الكتابة boolean.

**الإرجاع:**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public abstract void setDisplayEquation(boolean value)
```

يحدد أن معادلة خط الاتجاه تُعرض على المخطط (في نفس التسمية مثل قيمة Rsquaredvalue). قابل للقراءة/الكتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getOrder() {#getOrder--}
```
public abstract byte getOrder()
```

يحدد ترتيب خط الاتجاه المتعدد الحدود. يتم تجاهله للأنواع الأخرى من خطوط الاتجاه. يجب أن تكون القيمة بين 2 و 6. قابل للقراءة/الكتابة byte.

**الإرجاع:**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public abstract void setOrder(byte value)
```

يحدد ترتيب خط الاتجاه المتعدد الحدود. يتم تجاهله للأنواع الأخرى من خطوط الاتجاه. يجب أن تكون القيمة بين 2 و 6. قابل للقراءة/الكتابة byte.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getPeriod() {#getPeriod--}
```
public abstract byte getPeriod()
```

يحدد الفترة لخط الاتجاه لخط المتوسط المتحرك. يتم تجاهله للأنواع الأخرى من خطوط الاتجاه. يجب أن تكون القيمة بين 2 و 255. قابل للقراءة/الكتابة byte.

**الإرجاع:**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public abstract void setPeriod(byte value)
```

يحدد الفترة لخط الاتجاه لخط المتوسط المتحرك. يتم تجاهله للأنواع الأخرى من خطوط الاتجاه. يجب أن تكون القيمة بين 2 و 255. قابل للقراءة/الكتابة byte.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public abstract boolean getDisplayRSquaredValue()
```

يحدد أن قيمة R المربعة لخط الاتجاه تُعرض على المخطط (في نفس التسمية مثل المعادلة). قابل للقراءة/الكتابة boolean.

**الإرجاع:**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public abstract void setDisplayRSquaredValue(boolean value)
```

يحدد أن قيمة R المربعة لخط الاتجاه تُعرض على المخطط (في نفس التسمية مثل المعادلة). قابل للقراءة/الكتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

يمثل إدخال وسيلة الإيضاح المتعلق بهذا خط الاتجاه للقراءة فقط [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**الإرجاع:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)