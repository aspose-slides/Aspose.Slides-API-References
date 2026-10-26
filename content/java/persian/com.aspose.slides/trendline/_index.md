---
title: Trendline
second_title: Aspose.Slides برای Java مرجع API
description: کلاس نمایانگر خط روند سری نمودار
type: docs
url: /fa/com.aspose.slides/trendline/
---
**ارث‌بری:**
java.lang.Object, com.aspose.slides.DomObject

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ITrendline](../../com.aspose.slides/itrendline)
```
public class Trendline extends DomObject<TrendlineCollection> implements ITrendline
```

کلاس نمایانگر خط روند سری نمودار است
## متدها

| متد | توضیح |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | دریافت یا تنظیم نام خط روند. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | دریافت یا تنظیم نام خط روند. |
| [getTrendlineType()](#getTrendlineType--) | دریافت یا تنظیم نوع خط روند. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | دریافت یا تنظیم نوع خط روند. |
| [getFormat()](#getFormat--) | نمایانگر قالب خط روند است. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | نمایانگر قالب خط روند است. |
| [getBackward()](#getBackward--) | تعداد دسته‌ها (یا واحدها در نمودار پراکندگی) که خط روند قبل از داده‌های سری مورد نظر گسترش می‌یابد را مشخص می‌کند. |
| [setBackward(double value)](#setBackward-double-) | تعداد دسته‌ها (یا واحدها در نمودار پراکندگی) که خط روند قبل از داده‌های سری مورد نظر گسترش می‌یابد را مشخص می‌کند. |
| [getForward()](#getForward--) | تعداد دسته‌ها (یا واحدها در نمودار پراکندگی) که خط روند پس از داده‌های سری مورد نظر گسترش می‌یابد را مشخص می‌کند. |
| [setForward(double value)](#setForward-double-) | تعداد دسته‌ها (یا واحدها در نمودار پراکندگی) که خط روند پس از داده‌های سری مورد نظر گسترش می‌یابد را مشخص می‌کند. |
| [getIntercept()](#getIntercept--) | مقداری که خط روند باید محور y را قطع کند را مشخص می‌کند. |
| [setIntercept(double value)](#setIntercept-double-) | مقداری که خط روند باید محور y را قطع کند را مشخص می‌کند. |
| [getDisplayEquation()](#getDisplayEquation--) | مشخص می‌کند که معادله خط روند بر روی نمودار نمایش داده شود (در همان برچسبی که مقدار R² قرار دارد). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | مشخص می‌کند که معادله خط روند بر روی نمودار نمایش داده شود (در همان برچسبی که مقدار R² قرار دارد). |
| [getOrder()](#getOrder--) | مرتبۀ خط روند چندجمله‌ای را مشخص می‌کند. |
| [setOrder(byte value)](#setOrder-byte-) | مرتبۀ خط روند چندجمله‌ای را مشخص می‌کند. |
| [getPeriod()](#getPeriod--) | دوره خط روند برای خط روند میانگین متحرک را مشخص می‌کند. |
| [setPeriod(byte value)](#setPeriod-byte-) | دوره خط روند برای خط روند میانگین متحرک را مشخص می‌کند. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | مشخص می‌کند که مقدار R² خط روند بر روی نمودار نمایش داده شود (در همان برچسبی که معادله قرار دارد). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | مشخص می‌کند که مقدار R² خط روند بر روی نمودار نمایش داده شود (در همان برچسبی که معادله قرار دارد). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | نمایانگر ورودی افسانه مرتبط با این خط روند فقط-خواندنی [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | فریم متن برای بازنویسی را با متن موجود در پارامتر "text" مقداردهی اولیه می‌کند. |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | می‌تواند حاوی متن قالب‌بندی‌شده غنی باشد. |
| [getTextFormat()](#getTextFormat--) | قالب متن را برمی‌گرداند. |
| [getChart()](#getChart--) | نمودار والد را برمی‌گرداند. |
| [getSlide()](#getSlide--) | اسلاید والد یک FillFormat را برمی‌گرداند. |
| [getPresentation()](#getPresentation--) | ارائه والد یک FillFormat را برمی‌گرداند. |

### getTrendlineName() {#getTrendlineName--}
```
public final String getTrendlineName()
```

نام خط روند را دریافت یا تنظیم می‌کند. قابل خواندن و نوشتن String.

**بازگشت:**
java.lang.String

### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public final void setTrendlineName(String value)
```

نام خط روند را دریافت یا تنظیم می‌کند. قابل خواندن و نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getTrendlineType() {#getTrendlineType--}
```
public final int getTrendlineType()
```

دریافت یا تنظیم نوع خط روند. قابل خواندن و نوشتن [TrendlineType](../../com.aspose.slides/trendlinetype).

**بازگشت:**
int

### setTrendlineType(int value) {#setTrendlineType-int-}
```
public final void setTrendlineType(int value)
```

دریافت یا تنظیم نوع خط روند. قابل خواندن و نوشتن [TrendlineType](../../com.aspose.slides/trendlinetype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

نمایانگر قالب خط روند است. قابل خواندن و نوشتن [IFormat](../../com.aspose.slides/iformat).

**بازگشت:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

نمایانگر قالب خط روند است. قابل خواندن و نوشتن [IFormat](../../com.aspose.slides/iformat).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getBackward() {#getBackward--}
```
public final double getBackward()
```

تعداد دسته‌ها (یا واحدها در نمودار پراکندگی) که خط روند قبل از داده‌های سری مورد نظر گسترش می‌یابد را مشخص می‌کند. در نمودارهای پراکندگی و غیرپراکندگی، مقدار می‌تواند هر مقدار غیرمنفی باشد. قابل خواندن و نوشتن double.

**بازگشت:**
double

### setBackward(double value) {#setBackward-double-}
```
public final void setBackward(double value)
```

تعداد دسته‌ها (یا واحدها در نمودار پراکندگی) که خط روند قبل از داده‌های سری مورد نظر گسترش می‌یابد را مشخص می‌کند. در نمودارهای پراکندگی و غیرپراکندگی، مقدار می‌تواند هر مقدار غیرمنفی باشد. قابل خواندن و نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getForward() {#getForward--}
```
public final double getForward()
```

تعداد دسته‌ها (یا واحدها در نمودار پراکندگی) که خط روند پس از داده‌های سری مورد نظر گسترش می‌یابد را مشخص می‌کند. در نمودارهای پراکندگی و غیرپراکندگی، مقدار می‌تواند هر مقدار غیرمنفی باشد. قابل خواندن و نوشتن double.

**بازگشت:**
double

### setForward(double value) {#setForward-double-}
```
public final void setForward(double value)
```

تعداد دسته‌ها (یا واحدها در نمودار پراکندگی) که خط روند پس از داده‌های سری مورد نظر گسترش می‌یابد را مشخص می‌کند. در نمودارهای پراکندگی و غیرپراکندگی، مقدار می‌تواند هر مقدار غیرمنفی باشد. قابل خواندن و نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getIntercept() {#getIntercept--}
```
public final double getIntercept()
```

مقداری که خط روند باید محور y را قطع کند را مشخص می‌کند. این ویژگی تنها زمانی پشتیبانی می‌شود که نوع خط روند exp، linear یا poly باشد. قابل خواندن و نوشتن double.

**بازگشت:**
double

### setIntercept(double value) {#setIntercept-double-}
```
public final void setIntercept(double value)
```

مقداری که خط روند باید محور y را قطع کند را مشخص می‌کند. این ویژگی تنها زمانی پشتیبانی می‌شود که نوع خط روند exp، linear یا poly باشد. قابل خواندن و نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getDisplayEquation() {#getDisplayEquation--}
```
public final boolean getDisplayEquation()
```

مشخص می‌کند که معادله خط روند بر روی نمودار نمایش داده شود (در همان برچسبی که مقدار R² قرار دارد). قابل خواندن و نوشتن boolean.

**بازگشت:**
boolean

### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public final void setDisplayEquation(boolean value)
```

مشخص می‌کند که معادله خط روند بر روی نمودار نمایش داده شود (در همان برچسبی که مقدار R² قرار دارد). قابل خواندن و نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getOrder() {#getOrder--}
```
public final byte getOrder()
```

مرتبۀ خط روند چندجمله‌ای را مشخص می‌کند. برای سایر انواع خط روند نادیده گرفته می‌شود. مقدار باید بین ۲ تا ۶ باشد. قابل خواندن و نوشتن byte.

**بازگشت:**
byte

### setOrder(byte value) {#setOrder-byte-}
```
public final void setOrder(byte value)
```

مرتبۀ خط روند چندجمله‌ای را مشخص می‌کند. برای سایر انواع خط روند نادیده گرفته می‌شود. مقدار باید بین ۲ تا ۶ باشد. قابل خواندن و نوشتن byte.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getPeriod() {#getPeriod--}
```
public final byte getPeriod()
```

دوره خط روند برای خط روند میانگین متحرک را مشخص می‌کند. برای سایر انواع خط روند نادیده گرفته می‌شود. مقدار باید بین ۲ تا ۲۵۵ باشد. قابل خواندن و نوشتن byte.

**بازگشت:**
byte

### setPeriod(byte value) {#setPeriod-byte-}
```
public final void setPeriod(byte value)
```

دوره خط روند برای خط روند میانگین متحرک را مشخص می‌کند. برای سایر انواع خط روند نادیده گرفته می‌شود. مقدار باید بین ۲ تا ۲۵۵ باشد. قابل خواندن و نوشتن byte.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public final boolean getDisplayRSquaredValue()
```

مشخص می‌کند که مقدار R² خط روند بر روی نمودار نمایش داده شود (در همان برچسبی که معادله قرار دارد). قابل خواندن و نوشتن boolean.

**بازگشت:**
boolean

### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public final void setDisplayRSquaredValue(boolean value)
```

مشخص می‌کند که مقدار R² خط روند بر روی نمودار نمایش داده شود (در همان برچسبی که معادله قرار دارد). قابل خواندن و نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

نمایانگر ورودی افسانه مرتبط با این خط روند فقط-خواندنی [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**بازگشت:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

فریم متن برای بازنویسی را با متن موجود در پارامتر "text" مقداردهی اولیه می‌کند. اگر TextFrameForOverriding قبلاً مقداردهی شده باشد، متن آن به سادگی تغییر می‌یابد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متن برای TextFrameForOverriding جدید. |

**بازگشت:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

می‌تواند حاوی متن قالب‌بندی‌شده غنی باشد. اگر این ویژگی null نباشد، این مقدار متن قالب‌بندی‌شده متن خودکار تولید شده برچسب داده را بازنویسی می‌کند. متن خودکار تولید شده برچسب داده به متنی گفته می‌شود که توسط ویژگی‌های ShowSeriesName، ShowValue، ... مدیریت می‌شود و با ویژگی TextFormatManager.TextFormat قالب‌بندی می‌شود. فقط-خواندنی [ITextFrame](../../com.aspose.slides/itextframe).

**بازگشت:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

قالب متن را برمی‌گرداند. فقط-خواندنی [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**بازگشت:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getChart() {#getChart--}
```
public final IChart getChart()
```

نمودار والد را برمی‌گرداند. فقط-خواندنی [IChart](../../com.aspose.slides/ichart).

**بازگشت:**
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

اسلاید والد یک FillFormat را برمی‌گرداند. فقط-خواندنی [BaseSlide](../../com.aspose.slides/baseslide).

**بازگشت:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ارائه والد یک FillFormat را برمی‌گرداند. فقط-خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**بازگشت:**
[IPresentation](../../com.aspose.slides/ipresentation)