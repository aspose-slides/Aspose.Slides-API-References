---
title: Trendline
second_title: Aspose.Slides لأندرويد عبر مرجع API جافا
description: الفئة تمثل خط الاتجاه لسلسلة المخطط
type: docs
url: /ar/com.aspose.slides/trendline/
---
**الوراثة:**
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المُنفذة:**
[com.aspose.slides.ITrendline](../../com.aspose.slides/itrendline)
```
public class Trendline extends DomObject<TrendlineCollection> implements ITrendline
```

الفئة تمثل خط الاتجاه لسلسلة المخطط
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | يحصل أو يضع اسم خط الاتجاه. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | يحصل أو يضع اسم خط الاتجاه. |
| [getTrendlineType()](#getTrendlineType--) | يحصل أو يضع نوع خط الاتجاه. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | يحصل أو يضع نوع خط الاتجاه. |
| [getFormat()](#getFormat--) | يمثل تنسيق خط الاتجاه. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | يمثل تنسيق خط الاتجاه. |
| [getBackward()](#getBackward--) | يحدد عدد الفئات (أو الوحدات في مخطط التبعثر) التي يمتد إليها خط الاتجاه قبل البيانات للسلسلة التي يتم تتبعها. |
| [setBackward(double value)](#setBackward-double-) | يحدد عدد الفئات (أو الوحدات في مخطط التبعثر) التي يمتد إليها خط الاتجاه قبل البيانات للسلسلة التي يتم تتبعها. |
| [getForward()](#getForward--) | يحدد عدد الفئات (أو الوحدات في مخطط التبعثر) التي يمتد إليها خط الاتجاه بعد البيانات للسلسلة التي يتم تتبعها. |
| [setForward(double value)](#setForward-double-) | يحدد عدد الفئات (أو الوحدات في مخطط التبعثر) التي يمتد إليها خط الاتجاه بعد البيانات للسلسلة التي يتم تتبعها. |
| [getIntercept()](#getIntercept--) | يحدد القيمة التي يعبر فيها خط الاتجاه محور y. |
| [setIntercept(double value)](#setIntercept-double-) | يحدد القيمة التي يعبر فيها خط الاتجاه محور y. |
| [getDisplayEquation()](#getDisplayEquation--) | يحدد أن معادلة خط الاتجاه تُعرض على المخطط (في نفس التسمية كما Rsquaredvalue). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | يحدد أن معادلة خط الاتجاه تُعرض على المخطط (في نفس التسمية كما Rsquaredvalue). |
| [getOrder()](#getOrder--) | يحدد رتبة خط الاتجاه المتعدد الحدود. |
| [setOrder(byte value)](#setOrder-byte-) | يحدد رتبة خط الاتجاه المتعدد الحدود. |
| [getPeriod()](#getPeriod--) | يحدد فترة خط الاتجاه لخط المتوسط المتحرك. |
| [setPeriod(byte value)](#setPeriod-byte-) | يحدد فترة خط الاتجاه لخط المتوسط المتحرك. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | يحدد أن قيمة R-squared لخط الاتجاه تُعرض على المخطط (في نفس التسمية كما المعادلة). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | يحدد أن قيمة R-squared لخط الاتجاه تُعرض على المخطط (في نفس التسمية كما المعادلة). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | يمثل إدخال الأسطورة المتعلق بهذا خط الاتجاه قراءة فقط [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | تهيئة TextFrameForOverriding بالنص في المعامل "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | يمكن أن يحتوي على نص غني منسق. |
| [getTextFormat()](#getTextFormat--) | يرجع تنسيق النص. |
| [getChart()](#getChart--) | يرجع المخطط الأب. |
| [getSlide()](#getSlide--) | يرجع الشريحة الأب لـ FillFormat. |
| [getPresentation()](#getPresentation--) | يرجع العرض الأب لـ FillFormat. |

### getTrendlineName() {#getTrendlineName--}
```
public final String getTrendlineName()
```

يحصل أو يضع اسم خط الاتجاه. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public final void setTrendlineName(String value)
```

يحصل أو يضع اسم خط الاتجاه. قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getTrendlineType() {#getTrendlineType--}
```
public final int getTrendlineType()
```

يحصل أو يضع نوع خط الاتجاه. قراءة/كتابة [TrendlineType](../../com.aspose.slides/trendlinetype).

**الإرجاع:**
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public final void setTrendlineType(int value)
```

يحصل أو يضع نوع خط الاتجاه. قراءة/كتابة [TrendlineType](../../com.aspose.slides/trendlinetype).

**المعلمات:**
| المعامل | النوع | الوصف |
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
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getBackward() {#getBackward--}
```
public final double getBackward()
```

يحدد عدد الفئات (أو الوحدات في مخطط التبعثر) التي يمتد إليها خط الاتجاه قبل البيانات للسلسلة التي يتم تتبعها. قراءة/كتابة double.

**الإرجاع:**
double
### setBackward(double value) {#setBackward-double-}
```
public final void setBackward(double value)
```

يحدد عدد الفئات (أو الوحدات في مخطط التبعثر) التي يمتد إليها خط الاتجاه قبل البيانات للسلسلة التي يتم تتبعها. قراءة/كتابة double.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getForward() {#getForward--}
```
public final double getForward()
```

يحدد عدد الفئات (أو الوحدات في مخطط التبعثر) التي يمتد إليها خط الاتجاه بعد البيانات للسلسلة التي يتم تتبعها. قراءة/كتابة double.

**الإرجاع:**
double
### setForward(double value) {#setForward-double-}
```
public final void setForward(double value)
```

يحدد عدد الفئات (أو الوحدات في مخطط التبعثر) التي يمتد إليها خط الاتجاه بعد البيانات للسلسلة التي يتم تتبعها. قراءة/كتابة double.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getIntercept() {#getIntercept--}
```
public final double getIntercept()
```

يحدد القيمة التي يعبر فيها خط الاتجاه محور y. هذه الخاصية مدعومة فقط عندما يكون نوع خط الاتجاه exp أو linear أو poly. قراءة/كتابة double.

**الإرجاع:**
double
### setIntercept(double value) {#setIntercept-double-}
```
public final void setIntercept(double value)
```

يحدد القيمة التي يعبر فيها خط الاتجاه محور y. هذه الخاصية مدعومة فقط عندما يكون نوع خط الاتجاه exp أو linear أو poly. قراءة/كتابة double.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getDisplayEquation() {#getDisplayEquation--}
```
public final boolean getDisplayEquation()
```

يحدد أن معادلة خط الاتجاه تُعرض على المخطط (في نفس التسمية كما Rsquaredvalue). قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public final void setDisplayEquation(boolean value)
```

يحدد أن معادلة خط الاتجاه تُعرض على المخطط (في نفس التسمية كما Rsquaredvalue). قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getOrder() {#getOrder--}
```
public final byte getOrder()
```

يحدد رتبة خط الاتجاه المتعدد الحدود. يتم تجاهلها للأنواع الأخرى من خطوط الاتجاه. يجب أن تكون القيمة بين 2 و 6. قراءة/كتابة byte.

**الإرجاع:**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public final void setOrder(byte value)
```

يحدد رتبة خط الاتجاه المتعدد الحدود. يتم تجاهلها للأنواع الأخرى من خطوط الاتجاه. يجب أن تكون القيمة بين 2 و 6. قراءة/كتابة byte.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getPeriod() {#getPeriod--}
```
public final byte getPeriod()
```

يحدد فترة خط الاتجاه لخط المتوسط المتحرك. يتم تجاهلها للأنواع الأخرى من خطوط الاتجاه. يجب أن تكون القيمة بين 2 و 255. قراءة/كتابة byte.

**الإرجاع:**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public final void setPeriod(byte value)
```

يحدد فترة خط الاتجاه لخط المتوسط المتحرك. يتم تجاهلها للأنواع الأخرى من خطوط الاتجاه. يجب أن تكون القيمة بين 2 و 255. قراءة/كتابة byte.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public final boolean getDisplayRSquaredValue()
```

يحدد أن قيمة R-squared لخط الاتجاه تُعرض على المخطط (في نفس التسمية كما المعادلة). قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public final void setDisplayRSquaredValue(boolean value)
```

يحدد أن قيمة R-squared لخط الاتجاه تُعرض على المخطط (في نفس التسمية كما المعادلة). قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

يمثل إدخال الأسطورة المتعلق بهذا خط الاتجاه قراءة فقط [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**الإرجاع:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

تهيئة TextFrameForOverriding بالنص في المعامل "text". إذا كان TextFrameForOverriding مُهيأً مسبقًا فسيتم فقط تغيير نصه.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | نص لإطار TextFrameForOverriding الجديد. |

**الإرجاع:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

يمكن أن يحتوي على نص غني منسق. إذا كانت هذه الخاصية غير فارغة فستستبدل هذه القيمة النص المُولَّد تلقائيًا لتسمية البيانات. النص المُولَّد تلقائيًا لتسمية البيانات يعني النص الذي تُديره الخصائص ShowSeriesName و ShowValue … ويتم تنسيقه بواسطة خاصية TextFormatManager.TextFormat. قراءة فقط [ITextFrame](../../com.aspose.slides/itextframe).

**الإرجاع:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

يرجع تنسيق النص. قراءة فقط [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**الإرجاع:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```

يرجع المخطط الأب. قراءة فقط [IChart](../../com.aspose.slides/ichart).

**الإرجاع:**
[IChart](../../com.aspose.slides/ichart)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

يرجع الشريحة الأب لـ FillFormat. قراءة فقط [BaseSlide](../../com.aspose.slides/baseslide).

**الإرجاع:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

يرجع العرض الأب لـ FillFormat. قراءة فقط [IPresentation](../../com.aspose.slides/ipresentation).

**الإرجاع:**
[IPresentation](../../com.aspose.slides/ipresentation)