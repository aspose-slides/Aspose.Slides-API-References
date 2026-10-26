---
title: Trendline
second_title: مرجع API لـ Aspose.Slides للغة Java
description: الفئة تمثل خط الاتجاه لسلسلة المخطط
type: docs
url: /ar/com.aspose.slides/trendline/
---
**الوراثة:**  
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المنفذة:**  
[com.aspose.slides.ITrendline](../../com.aspose.slides/itrendline)  
```
public class Trendline extends DomObject<TrendlineCollection> implements ITrendline
```

الصف يُمثّل خط الاتجاه لسلسلة المخطط  
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | يحصل أو يعيّن اسم خط الاتجاه. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | يحصل أو يعيّن اسم خط الاتجاه. |
| [getTrendlineType()](#getTrendlineType--) | يحصل أو يعيّن نوع خط الاتجاه. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | يحصل أو يعيّن نوع خط الاتجاه. |
| [getFormat()](#getFormat--) | يمثل تنسيق خط الاتجاه. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | يمثل تنسيق خط الاتجاه. |
| [getBackward()](#getBackward--) | يحدّد عدد الفئات (أو الوحدات في مخطط مبعثر) التي يمتد إليها خط الاتجاه قبل البيانات الخاصة بالسلسلة المتتبعة. |
| [setBackward(double value)](#setBackward-double-) | يحدّد عدد الفئات (أو الوحدات في مخطط مبعثر) التي يمتد إليها خط الاتجاه قبل البيانات الخاصة بالسلسلة المتتبعة. |
| [getForward()](#getForward--) | يحدّد عدد الفئات (أو الوحدات في مخطط مبعثر) التي يمتد إليها خط الاتجاه بعد البيانات الخاصة بالسلسلة المتتبعة. |
| [setForward(double value)](#setForward-double-) | يحدّد عدد الفئات (أو الوحدات في مخطط مبعثر) التي يمتد إليها خط الاتجاه بعد البيانات الخاصة بالسلسلة المتتبعة. |
| [getIntercept()](#getIntercept--) | يحدّد القيمة حيث يقطع خط الاتجاه محور y. |
| [setIntercept(double value)](#setIntercept-double-) | يحدّد القيمة حيث يقطع خط الاتجاه محور y. |
| [getDisplayEquation()](#getDisplayEquation--) | يحدّد أن معادلة خط الاتجاه تُعرض على المخطط (في نفس الملصق مع Rsquaredvalue). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | يحدّد أن معادلة خط الاتجاه تُعرض على المخطط (في نفس الملصق مع Rsquaredvalue). |
| [getOrder()](#getOrder--) | يحدّد رتبة خط الاتجاه المتعدد الحدود. |
| [setOrder(byte value)](#setOrder-byte-) | يحدّد رتبة خط الاتجاه المتعدد الحدود. |
| [getPeriod()](#getPeriod--) | يحدّد فترة خط الاتجاه لخط متوسط متحرك. |
| [setPeriod(byte value)](#setPeriod-byte-) | يحدّد فترة خط الاتجاه لخط متوسط متحرك. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | يحدّد أن قيمة R-squared لخط الاتجاه تُعرض على المخطط (في نفس الملصق مع المعادلة). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | يحدّد أن قيمة R-squared لخط الاتجاه تُعرض على المخطط (في نفس الملصق مع المعادة). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | يمثل إدخال وسيلة الإيضاح المرتبط بهذا خط الاتجاه قراءة فقط [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | تهيئة TextFrameForOverriding بالنص في المعامل "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | يمكن أن يحتوي على نص منسق غني. |
| [getTextFormat()](#getTextFormat--) | يُعيد تنسيق النص. |
| [getChart()](#getChart--) | يُعيد المخطط الأب. |
| [getSlide()](#getSlide--) | يُعيد الشريحة الأب لـ FillFormat. |
| [getPresentation()](#getPresentation--) | يُعيد العرض الأب لـ FillFormat. |
### getTrendlineName() {#getTrendlineName--}
```
public final String getTrendlineName()
```

يحصل أو يعيّن اسم خط الاتجاه. قراءة/كتابة String.

**الإرجاع:**  
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public final void setTrendlineName(String value)
```

يحصل أو يعيّن اسم خط الاتجاه. قراءة/كتابة String.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getTrendlineType() {#getTrendlineType--}
```
public final int getTrendlineType()
```

يحصل أو يعيّن نوع خط الاتجاه. قراءة/كتابة [TrendlineType](../../com.aspose.slides/trendlinetype).

**الإرجاع:**  
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public final void setTrendlineType(int value)
```

يحصل أو يعيّن نوع خط الاتجاه. قراءة/كتابة [TrendlineType](../../com.aspose.slides/trendlinetype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

يمثل تنسيق خط الاتجاه. قراءة/كتابة [IFormat](../../com.aspose.slides/iformat).

**الإرجاع:**  
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

يمثل تنسيق خط الاتجاه. قراءة/كتابة [IFormat](../../com.aspose.slides/iformat).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getBackward() {#getBackward--}
```
public final double getBackward()
```

يحدد عدد الفئات (أو الوحدات في مخطط مبعثر) التي يمتد إليها خط الاتجاه قبل البيانات الخاصة بالسلسلة المتتبعة. في المخططات المبعثرة وغير المبعثرة، يجب أن تكون القيمة غير سالبة. قراءة/كتابة double.

**الإرجاع:**  
double
### setBackward(double value) {#setBackward-double-}
```
public final void setBackward(double value)
```

يحدد عدد الفئات (أو الوحدات في مخطط مبعثر) التي يمتد إليها خط الاتجاه قبل البيانات الخاصة بالسلسلة المتتبعة. في المخططات المبعثرة وغير المبعثرة، يجب أن تكون القيمة غير سالبة. قراءة/كتابة double.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### getForward() {#getForward--}
```
public final double getForward()
```

يحدد عدد الفئات (أو الوحدات في مخطط مبعثر) التي يمتد إليها خط الاتجاه بعد البيانات الخاصة بالسلسلة المتتبعة. في المخططات المبعثرة وغير المبعثرة، يجب أن تكون القيمة غير سالبة. قراءة/كتابة double.

**الإرجاع:**  
double
### setForward(double value) {#setForward-double-}
```
public final void setForward(double value)
```

يحدد عدد الفئات (أو الوحدات في مخطط مبعثر) التي يمتد إليها خط الاتجاه بعد البيانات الخاصة بالسلسلة المتتبعة. في المخططات المبعثرة وغير المبعثرة، يجب أن تكون القيمة غير سالبة. قراءة/كتابة double.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### getIntercept() {#getIntercept--}
```
public final double getIntercept()
```

يحدد القيمة التي يقطع فيها خط الاتجاه محور y. تدعم هذه الخاصية فقط عندما يكون نوع خط الاتجاه exp أو linear أو poly. قراءة/كتابة double.

**الإرجاع:**  
double
### setIntercept(double value) {#setIntercept-double-}
```
public final void setIntercept(double value)
```

يحدد القيمة التي يقطع فيها خط الاتجاه محور y. تدعم هذه الخاصية فقط عندما يكون نوع خط الاتجاه exp أو linear أو poly. قراءة/كتابة double.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### getDisplayEquation() {#getDisplayEquation--}
```
public final boolean getDisplayEquation()
```

يحدد أن معادلة خط الاتجاه تُعرض على المخطط (في نفس الملصق مع Rsquaredvalue). قراءة/كتابة boolean.

**الإرجاع:**  
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public final void setDisplayEquation(boolean value)
```

يحدد أن معادلة خط الاتجاه تُعرض على المخطط (في نفس الملصق مع Rsquaredvalue). قراءة/كتابة boolean.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getOrder() {#getOrder--}
```
public final byte getOrder()
```

يحدد رتبة خط الاتجاه المتعدد الحدود. يتم تجاهلها لأنواع الخطوط الأخرى. يجب أن تكون القيمة بين 2 و 6. قراءة/كتابة byte.

**الإرجاع:**  
byte
### setOrder(byte value) {#setOrder-byte-}
```
public final void setOrder(byte value)
```

يحدد رتبة خط الاتجاه المتعدد الحدود. يتم تجاهلها لأنواع الخطوط الأخرى. يجب أن تكون القيمة بين 2 و 6. قراءة/كتابة byte.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getPeriod() {#getPeriod--}
```
public final byte getPeriod()
```

يحدد فترة خط الاتجاه لخط متوسط متحرك. يتم تجاهلها للمتغيرات الأخرى. يجب أن تكون القيمة بين 2 و 255. قراءة/كتابة byte.

**الإرجاع:**  
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public final void setPeriod(byte value)
```

يحدد فترة خط الاتجاه لخط متوسط متحرك. يتم تجاهلها للمتغيرات الأخرى. يجب أن تكون القيمة بين 2 و 255. قراءة/كتابة byte.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public final boolean getDisplayRSquaredValue()
```

يحدد أن قيمة R-squared لخط الاتجاه تُعرض على المخطط (في نفس الملصق مع المعادلة). قراءة/كتابة boolean.

**الإرجاع:**  
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public final void setDisplayRSquaredValue(boolean value)
```

يحدد أن قيمة R-squared لخط الاتجاه تُعرض على المخطط (في نفس الملصق مع المعادلة). قراءة/كتابة boolean.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

يمثل إدخال وسيلة الإيضاح المرتبط بهذا خط الاتجاه قراءة فقط [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**الإرجاع:**  
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

تهيئة TextFrameForOverriding بالنص في المعامل "text". إذا كان TextFrameForOverriding مُهيأً مسبقاً فسيتم ببساطة تغيير نصه.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | نص لإطار TextFrameForOverriding الجديد. |

**الإرجاع:**  
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

يمكن أن يحتوي على نص منسق غني. إذا كانت هذه الخاصية غير فارغة فسيحل هذا النص المنسق محل النص المُولد تلقائياً لتسمية البيانات. النص المُولد تلقائياً لتسمية البيانات يعني النص المُدار عبر الخصائص ShowSeriesName، ShowValue، ... ومُنسق باستخدام خاصية TextFormatManager.TextFormat. قراءة فقط [ITextFrame](../../com.aspose.slides/itextframe).

**الإرجاع:**  
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

يعيد تنسيق النص. قراءة فقط [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**الإرجاع:**  
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```

يعيد المخطط الأب. قراءة فقط [IChart](../../com.aspose.slides/ichart).

**الإرجاع:**  
[IChart](../../com.aspose.slides/ichart)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

يعيد الشريحة الأب لـ FillFormat. قراءة فقط [BaseSlide](../../com.aspose.slides/baseslide).

**الإرجاع:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

يعيد العرض الأب لـ FillFormat. قراءة فقط [IPresentation](../../com.aspose.slides/ipresentation).

**الإرجاع:**  
[IPresentation](../../com.aspose.slides/ipresentation)