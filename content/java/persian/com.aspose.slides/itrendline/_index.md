---
title: ITrendline
second_title: Aspose.Slides برای Java مرجع API
description: کلاسی که خط روند سری نمودار را نشان می‌دهد
type: docs
url: /fa/com.aspose.slides/itrendline/
---
**همه رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext)
```
public interface ITrendline extends IOverridableText
```

کلاس نمایانگر خط روند سری نمودار است
## متدها

| متد | توضیح |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | دریافت یا تنظیم نام خط روند. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | دریافت یا تنظیم نام خط روند. |
| [getTrendlineType()](#getTrendlineType--) | دریافت یا تنظیم نوع خط روند. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | دریافت یا تنظیم نوع خط روند. |
| [getFormat()](#getFormat--) | نمایانگر قالب خط روند. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | نمایانگر قالب خط روند. |
| [getBackward()](#getBackward--) | تعیین تعداد دسته‌ها (یا واحدها در نمودار پراکندگی) که خط روند قبل از داده‌های سری که در حال ترند شدن است، گسترش می‌یابد. |
| [setBackward(double value)](#setBackward-double-) | تعیین تعداد دسته‌ها (یا واحدها در نمودار پراکندگی) که خط روند قبل از داده‌های سری که در حال ترند شدن است، گسترش می‌یابد. |
| [getForward()](#getForward--) | تعیین تعداد دسته‌ها (یا واحدها در نمودار پراکندگی) که خط روند پس از داده‌های سری که در حال ترند شدن است، گسترش می‌یابد. |
| [setForward(double value)](#setForward-double-) | تعیین تعداد دسته‌ها (یا واحدها در نمودار پراکندگی) که خط روند پس از داده‌های سری که در حال ترند شدن است، گسترش می‌یابد. |
| [getIntercept()](#getIntercept--) | تعیین مقداری که خط روند باید محور y را قطع کند. |
| [setIntercept(double value)](#setIntercept-double-) | تعیین مقداری که خط روند باید محور y را قطع کند. |
| [getDisplayEquation()](#getDisplayEquation--) | مشخص می‌کند که معادله خط روند بر روی نمودار نمایش داده شود (در همان برچسبی که Rsquaredvalue دارد). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | مشخص می‌کند که معادله خط روند بر روی نمودار نمایش داده شود (در همان برچسبی که Rsquaredvalue دارد). |
| [getOrder()](#getOrder--) | تعیین ترتیب خط روند چندجمله‌ای. |
| [setOrder(byte value)](#setOrder-byte-) | تعیین ترتیب خط روند چندجمله‌ای. |
| [getPeriod()](#getPeriod--) | تعیین دوره خط روند برای خط روند میانگین متحرک. |
| [setPeriod(byte value)](#setPeriod-byte-) | تعیین دوره خط روند برای خط روند میانگین متحرک. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | مشخص می‌کند که مقدار R-squared خط روند بر روی نمودار نمایش داده شود (در همان برچسبی که معادله دارد). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | مشخص می‌کند که مقدار R-squared خط روند بر روی نمودار نمایش داده شود (در همان برچسبی که معادله دارد). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | نمایانگر ورودی legend مرتبط با این خط روند فقط-خواندنی [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
### getTrendlineName() {#getTrendlineName--}
```
public abstract String getTrendlineName()
```

دریافت یا تنظیم نام خط روند. خواندنی/نوشتنی String.

**بازگشت:**
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public abstract void setTrendlineName(String value)
```

دریافت یا تنظیم نام خط روند. خواندنی/نوشتنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getTrendlineType() {#getTrendlineType--}
```
public abstract int getTrendlineType()
```

دریافت یا تنظیم نوع خط روند. خواندنی/نوشتنی [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**بازگشت:**
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public abstract void setTrendlineType(int value)
```

دریافت یا تنظیم نوع خط روند. خواندنی/نوشتنی [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

نمایانگر قالب خط روند. خواندنی/نوشتنی [IFormat](../../com.aspose.slides/iformat).

**بازگشت:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

نمایانگر قالب خط روند. خواندنی/نوشتنی [IFormat](../../com.aspose.slides/iformat).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getBackward() {#getBackward--}
```
public abstract double getBackward()
```

تعیین تعداد دسته‌ها (یا واحدها در نمودار پراکندگی) که خط روند قبل از داده‌های سری که در حال ترند شدن است، گسترش می‌یابد. در نمودارهای پراکندگی و غیرپراکندگی، مقدار می‌تواند هر مقدار غیر منفی باشد. خواندنی/نوشتنی double.

**بازگشت:**
double
### setBackward(double value) {#setBackward-double-}
```
public abstract void setBackward(double value)
```

تعیین تعداد دسته‌ها (یا واحدها در نمودار پراکندگی) که خط روند قبل از داده‌های سری که در حال ترند شدن است، گسترش می‌یابد. در نمودارهای پراکندگی و غیرپراکندگی، مقدار می‌تواند هر مقدار غیر منفی باشد. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getForward() {#getForward--}
```
public abstract double getForward()
```

تعیین تعداد دسته‌ها (یا واحدها در نمودار پراکندگی) که خط روند پس از داده‌های سری که در حال ترند شدن است، گسترش می‌یابد. در نمودارهای پراکندگی و غیرپراکندگی، مقدار می‌تواند هر مقدار غیر منفی باشد. خواندنی/نوشتنی double.

**بازگشت:**
double
### setForward(double value) {#setForward-double-}
```
public abstract void setForward(double value)
```

تعیین تعداد دسته‌ها (یا واحدها در نمودار پراکندگی) که خط روند پس از داده‌های سری که در حال ترند شدن است، گسترش می‌یابد. در نمودارهای پراکندگی و غیرپراکندگی، مقدار می‌تواند هر مقدار غیر منفی باشد. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getIntercept() {#getIntercept--}
```
public abstract double getIntercept()
```

تعیین مقداری که خط روند باید محور y را قطع کند. این خصوصیت فقط زمانی پشتیبانی می‌شود که نوع خط روند exp، linear یا poly باشد. خواندنی/نوشتنی double.

**بازگشت:**
double
### setIntercept(double value) {#setIntercept-double-}
```
public abstract void setIntercept(double value)
```

تعیین مقداری که خط روند باید محور y را قطع کند. این خصوصیت فقط زمانی پشتیبانی می‌شود که نوع خط روند exp، linear یا poly باشد. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getDisplayEquation() {#getDisplayEquation--}
```
public abstract boolean getDisplayEquation()
```

مشخص می‌کند که معادله خط روند بر روی نمودار نمایش داده شود (در همان برچسبی که Rsquaredvalue دارد). خواندنی/نوشتنی boolean.

**بازگشت:**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public abstract void setDisplayEquation(boolean value)
```

مشخص می‌کند که معادله خط روند بر روی نمودار نمایش داده شود (در همان برچسبی که Rsquaredvalue دارد). خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getOrder() {#getOrder--}
```
public abstract byte getOrder()
```

تعیین ترتیب خط روند چندجمله‌ای. برای سایر انواع خط روند نادیده گرفته می‌شود. مقدار باید بین ۲ تا ۶ باشد. خواندنی/نوشتنی byte.

**بازگشت:**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public abstract void setOrder(byte value)
```

تعیین ترتیب خط روند چندجمله‌ای. برای سایر انواع خط روند نادیده گرفته می‌شود. مقدار باید بین ۲ تا ۶ باشد. خواندنی/نوشتنی byte.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getPeriod() {#getPeriod--}
```
public abstract byte getPeriod()
```

تعیین دوره خط روند برای خط روند میانگین متحرک. برای سایر انواع خط روند نادیده گرفته می‌شود. مقدار باید بین ۲ تا ۲۵۵ باشد. خواندنی/نوشتنی byte.

**بازگشت:**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public abstract void setPeriod(byte value)
```

تعیین دوره خط روند برای خط روند میانگین متحرک. برای سایر انواع خط روند نادیده گرفته می‌شود. مقدار باید بین ۲ تا ۲۵۵ باشد. خواندنی/نوشتنی byte.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public abstract boolean getDisplayRSquaredValue()
```

مشخص می‌کند که مقدار R-squared خط روند بر روی نمودار نمایش داده شود (در همان برچسبی که معادله دارد). خواندنی/نوشتنی boolean.

**بازگشت:**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public abstract void setDisplayRSquaredValue(boolean value)
```

مشخص می‌کند که مقدار R-squared خط روند بر روی نمودار نمایش داده شود (در همان برچسبی که معادله دارد). خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

نمایانگر ورودی legend مرتبط با این خط روند فقط-خواندنی [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**بازگشت:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)