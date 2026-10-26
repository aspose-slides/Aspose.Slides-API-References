---
title: Trendline
second_title: Aspose.Slides برای Android از طریق مرجع API Java
description: کلاس نمایانگر خط روند سری نمودار
type: docs
url: /fa/com.aspose.slides/trendline/
---
**ارث‌بری:**
java.lang.Object, com.aspose.slides.DomObject

**تمام واسط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ITrendline](../../com.aspose.slides/itrendline)
```
public class Trendline extends DomObject<TrendlineCollection> implements ITrendline
```

کلاس نمایانگر خط روند سری نمودار است
## متدها

| متد | توضیح |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | نام خط‌ روند را دریافت یا تنظیم می‌کند. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | نام خط‌ روند را دریافت یا تنظیم می‌کند. |
| [getTrendlineType()](#getTrendlineType--) | نوع خط‌ روند را دریافت یا تنظیم می‌کند. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | نوع خط‌ روند را دریافت یا تنظیم می‌کند. |
| [getFormat()](#getFormat--) | فرمت خط‌ روند را نشان می‌دهد. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | فرمت خط‌ روند را نشان می‌دهد. |
| [getBackward()](#getBackward--) | تعداد دسته‌ها (یا واحدها در نمودار پراکنده) که خط‌ روند قبل از داده‌های سری مورد روند گسترش می‌یابد را مشخص می‌کند. |
| [setBackward(double value)](#setBackward-double-) | تعداد دسته‌ها (یا واحدها در نمودار پراکنده) که خط‌ روند قبل از داده‌های سری مورد روند گسترش می‌یابد را مشخص می‌کند. |
| [getForward()](#getForward--) | تعداد دسته‌ها (یا واحدها در نمودار پراکنده) که خط‌ روند پس از داده‌های سری مورد روند گسترش می‌یابد را مشخص می‌کند. |
| [setForward(double value)](#setForward-double-) | تعداد دسته‌ها (یا واحدها در نمودار پراکنده) که خط‌ روند پس از داده‌های سری مورد روند گسترش می‌یابد را مشخص می‌کند. |
| [getIntercept()](#getIntercept--) | مقداری که خط‌ روند محور y را قطع می‌کند را مشخص می‌کند. |
| [setIntercept(double value)](#setIntercept-double-) | مقداری که خط‌ روند محور y را قطع می‌کند را مشخص می‌کند. |
| [getDisplayEquation()](#getDisplayEquation--) | مشخص می‌کند که معادله خط‌ روند بر روی نمودار نمایش داده شود (در همان برچسب که مقدار Rsquaredvalue قرار دارد). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | مشخص می‌کند که معادله خط‌ روند بر روی نمودار نمایش داده شود (در همان برچسب که مقدار Rsquaredvalue قرار دارد). |
| [getOrder()](#getOrder--) | مرتبه‌ی خط‌ روند چندجمله‌ای را مشخص می‌کند. |
| [setOrder(byte value)](#setOrder-byte-) | مرتبه‌ی خط‌ روند چندجمله‌ای را مشخص می‌کند. |
| [getPeriod()](#getPeriod--) | دوره‌ی خط‌ روند برای خط‌ روند متوسط حرکتی را مشخص می‌کند. |
| [setPeriod(byte value)](#setPeriod-byte-) | دوره‌ی خط‌ روند برای خط‌ روند متوسط حرکتی را مشخص می‌کند. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | مشخص می‌کند که مقدار R-squared خط‌ روند بر روی نمودار نمایش داده شود (در همان برچسب که معادله قرار دارد). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | مشخص می‌کند که مقدار R-squared خط‌ روند بر روی نمودار نمایش داده شود (در همان برچسب که معادله قرار دارد). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | ورودی افسانه مربوط به این خط‌ روند را نمایش می‌دهد (فقط‌خواندنی) [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | TextFrameForOverriding را با متنی که در پارامتر "text" قرار دارد مقداردهی اولیه می‌کند. |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | می‌تواند متنی با قالب‌بندی پیشرفته داشته باشد. |
| [getTextFormat()](#getTextFormat--) | قالب متن را برمی‌گرداند. |
| [getChart()](#getChart--) | نمودار والد را برمی‌گرداند. |
| [getSlide()](#getSlide--) | اسلاید والد یک FillFormat را برمی‌گرداند. |
| [getPresentation()](#getPresentation--) | ارائه مادر یک FillFormat را برمی‌گرداند. |

### getTrendlineName() {#getTrendlineName--}
```
public final String getTrendlineName()
```

نام خط‌ روند را دریافت یا تنظیم می‌کند. قابل خواندن/قابل نوشتن String.

**بازگرداندن:**
java.lang.String

### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public final void setTrendlineName(String value)
```

نام خط‌ روند را دریافت یا تنظیم می‌کند. قابل خواندن/قابل نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getTrendlineType() {#getTrendlineType--}
```
public final int getTrendlineType()
```

نوع خط‌ روند را دریافت یا تنظیم می‌کند. قابل خواندن/قابل نوشتن [TrendlineType](../../com.aspose.slides/trendlinetype).

**بازگرداندن:**
int

### setTrendlineType(int value) {#setTrendlineType-int-}
```
public final void setTrendlineType(int value)
```

نوع خط‌ روند را دریافت یا تنظیم می‌کند. قابل خواندن/قابل نوشتن [TrendlineType](../../com.aspose.slides/trendlinetype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

فرمت خط‌ روند را نشان می‌دهد. قابل خواندن/قابل نوشتن [IFormat](../../com.aspose.slides/iformat).

**بازگرداندن:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

فرمت خط‌ روند را نشان می‌دهد. قابل خواندن/قابل نوشتن [IFormat](../../com.aspose.slides/iformat).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getBackward() {#getBackward--}
```
public final double getBackward()
```

تعداد دسته‌ها (یا واحدها در نمودار پراکنده) که خط‌ روند قبل از داده‌های سری مورد روند گسترش می‌یابد را مشخص می‌کند. در نمودارهای پراکنده و غیرپراکنده، مقدار می‌تواند هر مقدار غیرمنفی باشد. قابل خواندن/قابل نوشتن double.

**بازگرداندن:**
double

### setBackward(double value) {#setBackward-double-}
```
public final void setBackward(double value)
```

تعداد دسته‌ها (یا واحدها در نمودار پراکنده) که خط‌ روند قبل از داده‌های سری مورد روند گسترش می‌یابد را مشخص می‌کند. در نمودارهای پراکنده و غیرپراکنده، مقدار می‌تواند هر مقدار غیرمنفی باشد. قابل خواندن/قابل نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getForward() {#getForward--}
```
public final double getForward()
```

تعداد دسته‌ها (یا واحدها در نمودار پراکنده) که خط‌ روند پس از داده‌های سری مورد روند گسترش می‌یابد را مشخص می‌کند. در نمودارهای پراکنده و غیرپراکنده، مقدار می‌تواند هر مقدار غیرمنفی باشد. قابل خواندن/قابل نوشتن double.

**بازگرداندن:**
double

### setForward(double value) {#setForward-double-}
```
public final void setForward(double value)
```

تعداد دسته‌ها (یا واحدها در نمودار پراکنده) که خط‌ روند پس از داده‌های سری مورد روند گسترش می‌یابد را مشخص می‌کند. در نمودارهای پراکنده و غیرپراکنده، مقدار می‌تواند هر مقدار غیرمنفی باشد. قابل خواندن/قابل نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getIntercept() {#getIntercept--}
```
public final double getIntercept()
```

مقداری که خط‌ روند محور y را قطع می‌کند را مشخص می‌کند. این ویژگی فقط زمانی پشتیبانی می‌شود که نوع خط‌ روند exp، linear یا poly باشد. قابل خواندن/قابل نوشتن double.

**بازگرداندن:**
double

### setIntercept(double value) {#setIntercept-double-}
```
public final void setIntercept(double value)
```

مقداری که خط‌ روند محور y را قطع می‌کند را مشخص می‌کند. این ویژگی فقط زمانی پشتیبانی می‌شود که نوع خط‌ روند exp، linear یا poly باشد. قابل خواندن/قابل نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getDisplayEquation() {#getDisplayEquation--}
```
public final boolean getDisplayEquation()
```

مشخص می‌کند که معادله خط‌ روند بر روی نمودار نمایش داده شود (در همان برچسب که مقدار Rsquaredvalue قرار دارد). قابل خواندن/قابل نوشتن boolean.

**بازگرداندن:**
boolean

### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public final void setDisplayEquation(boolean value)
```

مشخص می‌کند که معادله خط‌ روند بر روی نمودار نمایش داده شود (در همان برچسب که مقدار Rsquaredvalue قرار دارد). قابل خواندن/قابل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getOrder() {#getOrder--}
```
public final byte getOrder()
```

مرتبه‌ی خط‌ روند چندجمله‌ای را مشخص می‌کند. برای سایر انواع خط‌ روند نادیده گرفته می‌شود. مقدار باید بین 2 و 6 باشد. قابل خواندن/قابل نوشتن byte.

**بازگرداندن:**
byte

### setOrder(byte value) {#setOrder-byte-}
```
public final void setOrder(byte value)
```

مرتبه‌ی خط‌ روند چندجمله‌ای را مشخص می‌کند. برای سایر انواع خط‌ روند نادیده گرفته می‌شود. مقدار باید بین 2 و 6 باشد. قابل خواندن/قابل نوشتن byte.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getPeriod() {#getPeriod--}
```
public final byte getPeriod()
```

دوره‌ی خط‌ روند برای خط‌ روند متوسط حرکتی را مشخص می‌کند. برای سایر گونه‌های خط‌ روند نادیده گرفته می‌شود. مقدار باید بین 2 و 255 باشد. قابل خواندن/قابل نوشتن byte.

**بازگرداندن:**
byte

### setPeriod(byte value) {#setPeriod-byte-}
```
public final void setPeriod(byte value)
```

دوره‌ی خط‌ روند برای خط‌ روند متوسط حرکتی را مشخص می‌کند. برای سایر گونه‌های خط‌ روند نادیده گرفته می‌شود. مقدار باید بین 2 و 255 باشد. قابل خواندن/قابل نوشتن byte.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public final boolean getDisplayRSquaredValue()
```

مشخص می‌کند که مقدار R-squared خط‌ روند بر روی نمودار نمایش داده شود (در همان برچسب که معادله قرار دارد). قابل خواندن/قابل نوشتن boolean.

**بازگرداندن:**
boolean

### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public final void setDisplayRSquaredValue(boolean value)
```

مشخص می‌کند که مقدار R-squared خط‌ روند بر روی نمودار نمایش داده شود (در همان برچسب که معادله قرار دارد). قابل خواندن/قابل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

ورودی افسانه مربوط به این خط‌ روند را نمایش می‌دهد (فقط‌خواندنی) [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**بازگرداندن:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

TextFrameForOverriding را با متنی که در پارامتر "text" است مقداردهی اولیه می‌کند. اگر TextFrameForOverriding قبلاً مقداردهی شده باشد، صرفاً متن آن را تغییر می‌دهد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متن برای یک TextFrameForOverriding جدید. |

**بازگرداندن:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

می‌تواند متنی با قالب‌بندی پیشرفته داشته باشد. اگر این ویژگی null نباشد، مقدار متنی قالب‌بندی‌شده آن متن تولید خودکار برچسب داده را نادیده می‌گیرد. متن تولید خودکار برچسب داده به متنی گفته می‌شود که توسط ویژگی‌های ShowSeriesName، ShowValue، ... مدیریت می‌شود و با ویژگی TextFormatManager.TextFormat قالب‌بندی می‌شود. فقط‌خواندنی [ITextFrame](../../com.aspose.slides/itextframe).

**بازگرداندن:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

قالب متن را برمی‌گرداند. فقط‌خواندنی [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**بازگرداندن:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getChart() {#getChart--}
```
public final IChart getChart()
```

نمودار والد را برمی‌گرداند. فقط‌خواندنی [IChart](../../com.aspose.slides/ichart).

**بازگرداندن:**
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

اسلاید والد یک FillFormat را برمی‌گرداند. فقط‌خواندنی [BaseSlide](../../com.aspose.slides/baseslide).

**بازگرداندن:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ارائه مادر یک FillFormat را برمی‌گرداند. فقط‌خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**بازگرداندن:**
[IPresentation](../../com.aspose.slides/ipresentation)