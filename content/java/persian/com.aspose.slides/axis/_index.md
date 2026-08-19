---
title: Axis
second_title: مستندات API Aspose.Slides برای Java
description: شیئی را که نمایانگر محور نمودارها است، در بر می‌گیرد.
type: docs
url: /fa/com.aspose.slides/axis/
---
**ارث‌بری:**  
java.lang.Object, com.aspose.slides.DomObject

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IAxis](../../com.aspose.slides/iaxis)  
```
public class Axis extends DomObject<AxesManager> implements IAxis
```

شیئی که نمایانگر محور یک نمودار است را در بر می‌گیرد.

## متدها

| متد | توضیح |
| --- | --- |
| [getChart()](#getChart--) | چارت والد را برمی‌گرداند. |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | نشان می‌دهد که آیا محور مقدار، محور دسته‌بندی را بین دسته‌ها عبور می‌دهد. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | نشان می‌دهد که آیا محور مقدار، محور دسته‌بندی را بین دسته‌ها عبور می‌دهد. |
| [getCategoryAxisType()](#getCategoryAxisType--) | نوع محور دسته‌بندی را مشخص می‌کند. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | نوع محور دسته‌بندی را مشخص می‌کند. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | خصوصیت IAxis.CategoryAxisType را با مقداری که به‌طور خودکار بر اساس داده‌های محور تعیین می‌شود، تنظیم می‌کند. |
| [getCrossAt()](#getCrossAt--) | نقطه‌ای روی محور که محور عمود بر آن عبور می‌کند را نشان می‌دهد. |
| [setCrossAt(float value)](#setCrossAt-float-) | نقطه‌ای روی محور که محور عمود بر آن عبور می‌کند را نشان می‌دهد. |
| [getDisplayUnit()](#getDisplayUnit--) | مقدار مقیاس واحدهای نمایش برای محور مقدار را مشخص می‌کند. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | مقدار مقیاس واحدهای نمایش برای محور مقدار را مشخص می‌کند. |
| [getActualMaxValue()](#getActualMaxValue--) | حداکثر مقدار واقعی روی محور را مشخص می‌کند. |
| [getActualMinValue()](#getActualMinValue--) | حداقل مقدار واقعی روی محور را مشخص می‌کند. |
| [getActualMajorUnit()](#getActualMajorUnit--) | واحد اصلی واقعی محور را مشخص می‌کند. |
| [getActualMinorUnit()](#getActualMinorUnit--) | واحد فرعی واقعی محور را مشخص می‌کند. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | مقیاس واحد اصلی واقعی محور را مشخص می‌کند. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | مقیاس واحد فرعی واقعی محور را مشخص می‌کند. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | نشان می‌دهد که آیا حداکثر مقدار به‌صورت خودکار اختصاص داده می‌شود. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | نشان می‌دهد که آیا حداکثر مقدار به‌صورت خودکار اختصاص داده می‌شود. |
| [getMaxValue()](#getMaxValue--) | حداکثر مقدار روی محور مقدار را نشان می‌دهد. |
| [setMaxValue(double value)](#setMaxValue-double-) | حداکثر مقدار روی محور مقدار را نشان می‌دهد. |
| [getMinorUnit()](#getMinorUnit--) | واحدهای فرعی برای محور تاریخ یا مقدار را نشان می‌دهد. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | واحدهای فرعی برای محور تاریخ یا مقدار را نشان می‌دهد. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | نشان می‌دهد که آیا واحد فرعی محور به‌صورت خودکار اختصاص داده می‌شود. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | نشان می‌دهد که آیا واحد فرعی محور به‌صورت خودکار اختصاص داده می‌شود. |
| [getMajorUnit()](#getMajorUnit--) | واحدهای اصلی برای محور تاریخ یا مقدار را نشان می‌دهد. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | واحدهای اصلی برای محور تاریخ یا مقدار را نشان می‌دهد. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | نشان می‌دهد که آیا واحد اصلی محور به‌صورت خودکار اختصاص داده می‌شود. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | نشان می‌دهد که آیا واحد اصلی محور به‌صورت خودکار اختصاص داده می‌شود. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | نشان می‌دهد که آیا حداقل مقدار به‌صورت خودکار اختصاص داده می‌شود. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | نشان می‌دهد که آیا حداقل مقدار به‌صورت خودکار اختصاص داده می‌شود. |
| [getMinValue()](#getMinValue--) | حداقل مقدار روی محور مقدار را نشان می‌دهد. |
| [setMinValue(double value)](#setMinValue-double-) | حداقل مقدار روی محور مقدار را نشان می‌دهد. |
| [isLogarithmic()](#isLogarithmic--) | نشان می‌دهد که آیا نوع مقیاس محور مقدار لگاریتمی است یا خیر. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | نشان می‌دهد که آیا نوع مقیاس محور مقدار لگاریتمی است یا خیر. |
| [getLogBase()](#getLogBase--) | پایه لگاریتمی را نشان می‌دهد. |
| [setLogBase(double value)](#setLogBase-double-) | پایه لگاریتمی را نشان می‌دهد. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | نشان می‌دهد که آیا مایکروسافت پاورپوینت نقاط داده را از آخر به اول ترسیم می‌کند. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | نشان می‌دهد که آیا مایکروسافت پاورپوینت نقاط داده را از آخر به اول ترسیم می‌کند. |
| [isVisible()](#isVisible--) | نشان می‌دهد که آیا محور قابل مشاهده است. |
| [setVisible(boolean value)](#setVisible-boolean-) | نشان می‌دهد که آیا محور قابل مشاهده است. |
| [getMajorTickMark()](#getMajorTickMark--) | نوع علامت‌گذاری اصلی برای محور مشخص‌شده را نشان می‌دهد. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | نوع علامت‌گذاری اصلی برای محور مشخص‌شده را نشان می‌دهد. |
| [getMinorTickMark()](#getMinorTickMark--) | نوع علامت‌گذاری فرعی برای محور مشخص‌شده را نشان می‌دهد. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | نوع علامت‌گذاری فرعی برای محور مشخص‌شده را نشان می‌دهد. |
| [getTickLabelPosition()](#getTickLabelPosition--) | موقعیت برچسب‌های علامت‌گذاری روی محور مشخص‌شده را نشان می‌دهد. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | موقعیت برچسب‌های علامت‌گذاری روی محور مشخص‌شده را نشان می‌دهد. |
| [getMajorUnitScale()](#getMajorUnitScale--) | مقیاس واحد اصلی برای محور تاریخ را نشان می‌دهد. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | مقیاس واحد اصلی برای محور تاریخ را نشان می‌دهد. |
| [getMinorUnitScale()](#getMinorUnitScale--) | مقیاس واحد اصلی برای محور تاریخ را نشان می‌دهد. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | مقیاس واحد اصلی برای محور تاریخ را نشان می‌دهد. |
| [getBaseUnitScale()](#getBaseUnitScale--) | کوچک‌ترین واحد زمانی که بر روی محور تاریخ نشان داده می‌شود را مشخص می‌کند. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | کوچک‌ترین واحد زمانی که بر روی محور تاریخ نشان داده می‌شود را مشخص می‌کند. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | قالب خطوط شبکه فرعی روی محور نمودار را نشان می‌دهد. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | قالب خطوط شبکه اصلی روی محور نمودار را نشان می‌دهد. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | برای مخفی کردن خط شبکه فرعی، MinorGridLinesFormat.Line.FillFormat.FillType را به FillType.NoFill تنظیم کنید. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | برای مخفی کردن خط شبکه اصلی، MajorGridLinesFormat.Line.FillFormat.FillType را به FillType.NoFill تنظیم کنید. |
| [getFormat()](#getFormat--) | قالب محور را نشان می‌دهد. |
| [getTextFormat()](#getTextFormat--) | قالب متن را نشان می‌دهد. |
| [getTitle()](#getTitle--) | عنوان محور را می‌گیرد. |
| [getCrossType()](#getCrossType--) | نوع CrossType روی محور مشخص‌شده را که محور دیگر در آن عبور می‌کند، نشان می‌دهد. |
| [setCrossType(int value)](#setCrossType-int-) | نوع CrossType روی محور مشخص‌شده را که محور دیگر در آن عبور می‌کند، نشان می‌دهد. |
| [getPosition()](#getPosition--) | موقعیت محور را نشان می‌دهد. |
| [setPosition(int value)](#setPosition-int-) | موقعیت محور را نشان می‌دهد. |
| [hasTitle()](#hasTitle--) | تعیین می‌کند که آیا محور عنوان قابل مشاهده دارد یا نه. |
| [setTitle(boolean value)](#setTitle-boolean-) | تعیین می‌کند که آیا محور عنوان قابل مشاهده دارد یا نه. |
| [getNumberFormat()](#getNumberFormat--) | رشته قالب برای برچسب‌های محور را نشان می‌دهد. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | رشته قالب برای برچسب‌های محور را نشان می‌دهد. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | نشان می‌دهد که آیا قالب به داده‌های منبع لینک شده است. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | نشان می‌دهد که آیا قالب به داده‌های منبع لینک شده است. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | زاویه چرخش برچسب‌های علامت‌گذاری را نشان می‌دهد. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | زاویه چرخش برچسب‌های علامت‌گذاری را نشان می‌دهد. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | تعداد برچسب‌های علامت‌گذاری که باید بین برچسب‌های رسم‌شده رد شوند را مشخص می‌کند. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | تعداد برچسب‌های علامت‌گذاری که باید بین برچسب‌های رسم‌شده رد شوند را مشخص می‌کند. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | مقدار فاصله خودکار بین برچسب‌های علامت‌گذاری را مشخص می‌کند. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | مقدار فاصله خودکار بین برچسب‌های علامت‌گذاری را مشخص می‌کند. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | تعداد علامت‌گذاری‌هایی که قبل از رسم علامت بعدی باید رد شوند را مشخص می‌کند. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | تعداد علامت‌گذاری‌هایی که قبل از رسم علامت بعدی باید رد شوند را مشخص می‌کند. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | مقدار فاصله خودکار بین علامت‌گذاری‌ها را مشخص می‌کند. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | مقدار فاصله خودکار بین علامت‌گذاری‌ها را مشخص می‌کند. |
| [getLabelOffset()](#getLabelOffset--) | فاصله برچسب‌ها از محور را مشخص می‌کند. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | فاصله برچسب‌ها از محور را مشخص می‌کند. |
| [getAggregationType()](#getAggregationType--) | نوع تجمیع محور دسته‌بندی (باینینگ) را نشان می‌دهد. |
| [setAggregationType(int value)](#setAggregationType-int-) | نوع تجمیع محور دسته‌بندی (باینینگ) را نشان می‌دهد. |
| [getBinWidth()](#getBinWidth--) | عرض باین را زمانی که مقدار خصوصیت AggregationType برابر AxisAggregationType.ByBinWidth تنظیم شده باشد، مشخص می‌کند. |
| [setBinWidth(double value)](#setBinWidth-double-) | عرض باین را زمانی که مقدار خصوصیت AggregationType برابر AxisAggregationType.ByBinWidth تنظیم شده باشد، مشخص می‌کند. |
| [getNumberOfBins()](#getNumberOfBins--) | تعداد باین‌ها را زمانی که مقدار خصوصیت AggregationType برابر AxisAggregationType.ByNumberOfBins تنظیم شده باشد، مشخص می‌کند. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | تعداد باین‌ها را زمانی که مقدار خصوصیت AggregationType برابر AxisAggregationType.ByNumberOfBins تنظیم شده باشد، مشخص می‌کند. |
| [isOverflowBin()](#isOverflowBin--) | نشان می‌دهد که آیا باین سرریز اعمال شده است. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | نشان می‌دهد که آیا باین سرریز اعمال شده است. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | مقدار خودکار باین سرریز را مشخص می‌کند. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | مقدار خودکار باین سرریز را مشخص می‌کند. |
| [getOverflowBin()](#getOverflowBin--) | مقدار سفارشی باین سرریز را مشخص می‌کند. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | مقدار سفارشی باین سرریز را مشخص می‌کند. |
| [isUnderflowBin()](#isUnderflowBin--) | نشان می‌دهد که آیا باین زیرریز اعمال شده است. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | نشان می‌دهد که آیا باین زیرریز اعمال شده است. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | مقدار خودکار باین زیرریز را مشخص می‌کند. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | مقدار خودکار باین زیرریز را مشخص می‌کند. |
| [getUnderflowBin()](#getUnderflowBin--) | مقدار سفارشی باین زیرریز را مشخص می‌کند. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | مقدار سفارشی باین زیرریز را مشخص می‌کند. |
| [getSlide()](#getSlide--) | اسلاید والد FillFormat را برمی‌گرداند. |
| [getPresentation()](#getPresentation--) | ارائه والد FillFormat را برمی‌گرداند. |

### getChart() {#getChart--}
```
public final IChart getChart()
```

چارت والد را برمی‌گرداند. فقط-خواندنی [IChart](../../com.aspose.slides/ichart).

**بازمی‌گرداند:**
[IChart](../../com.aspose.slides/ichart)

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public final boolean getAxisBetweenCategories()
```

نمایش می‌دهد که آیا محور مقدار، محور دسته‌بندی را بین دسته‌ها عبور می‌دهد. این ویژگی فقط برای محورهای دسته‌بندی اعمال می‌شود و برای نمودارهای سه‌بعدی اعمال نمی‌شود. خواندن/نوشتن boolean.

**بازمی‌گرداند:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public final void setAxisBetweenCategories(boolean value)
```

نمایش می‌دهد که آیا محور مقدار، محور دسته‌بندی را بین دسته‌ها عبور می‌دهد. این ویژگی فقط برای محورهای دسته‌بندی اعمال می‌شود و برای نمودارهای سه‌بعدی اعمال نمی‌شود. خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public final int getCategoryAxisType()
```

نوع محور دسته‌بندی را مشخص می‌کند. خواندن/نوشتن [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**بازمی‌گرداند:**
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public final void setCategoryAxisType(int value)
```

نوع محور دسته‌بندی را مشخص می‌کند. خواندن/نوشتن [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public final void setCategoryAxisTypeAutomatically()
```

خصوصیت IAxis.CategoryAxisType را با مقداری که به‌طور خودکار بر اساس داده‌های محور تعیین می‌شود، تنظیم می‌کند.

### getCrossAt() {#getCrossAt--}
```
public final float getCrossAt()
```

نقطه‌ای روی محور که محور عمود بر آن عبور می‌کند را نشان می‌دهد. خواندن/نوشتن float.

**بازمی‌گرداند:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public final void setCrossAt(float value)
```

نقطه‌ای روی محور که محور عمود بر آن عبور می‌کند را نشان می‌دهد. خواندن/نوشتن float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public final int getDisplayUnit()
```

مقدار مقیاس واحدهای نمایش برای محور مقدار را مشخص می‌کند. خواندن/نوشتن [DisplayUnitType](../../com.aspose.slides/displayunittype).

**بازمی‌گرداند:**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public final void setDisplayUnit(int value)
```

مقدار مقیاس واحدهای نمایش برای محور مقدار را مشخص می‌کند. خواندن/نوشتن [DisplayUnitType](../../com.aspose.slides/displayunittype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public final double getActualMaxValue()
```

حداکثر مقدار واقعی روی محور را مشخص می‌کند. برای دریافت مقدار واقعی، پیش از آن متد IChart.ValidateChartLayout() را صدا بزنید.

**بازمی‌گرداند:**
double

### getActualMinValue() {#getActualMinValue--}
```
public final double getActualMinValue()
```

حداقل مقدار واقعی روی محور را مشخص می‌کند. برای دریافت مقدار واقعی، پیش از آن متد IChart.ValidateChartLayout() را صدا بزنید.

**بازمی‌گرداند:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public final double getActualMajorUnit()
```

واحد اصلی واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی، پیش از آن متد IChart.ValidateChartLayout() را صدا بزنید.

**بازمی‌گرداند:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public final double getActualMinorUnit()
```

واحد فرعی واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی، پیش از آن متد IChart.ValidateChartLayout() را صدا بزنید.

**بازمی‌گرداند:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public final int getActualMajorUnitScale()
```

مقیاس واحد اصلی واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی، پیش از آن متد IChart.ValidateChartLayout() را صدا بزنید.

**بازمی‌گرداند:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public final int getActualMinorUnitScale()
```

مقیاس واحد فرعی واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی، پیش از آن متد IChart.ValidateChartLayout() را صدا بزنید.

**بازمی‌گرداند:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public final boolean isAutomaticMaxValue()
```

نشان می‌دهد که آیا حداکثر مقدار به‌صورت خودکار اختصاص داده می‌شود. خواندن/نوشتن boolean.

**بازمی‌گرداند:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public final void setAutomaticMaxValue(boolean value)
```

نشان می‌دهد که آیا حداکثر مقدار به‌صورت خودکار اختصاص داده می‌شود. خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public final double getMaxValue()
```

حداکثر مقدار روی محور مقدار را نشان می‌دهد. خواندن/نوشتن double.

**بازمی‌گرداند:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public final void setMaxValue(double value)
```

حداکثر مقدار روی محور مقدار را نشان می‌دهد. خواندن/نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public final double getMinorUnit()
```

واحدهای فرعی برای محور تاریخ یا مقدار را نشان می‌دهد. خواندن/نوشتن double.

**بازمی‌گرداند:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public final void setMinorUnit(double value)
```

واحدهای فرعی برای محور تاریخ یا مقدار را نشان می‌دهد. خواندن/نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public final boolean isAutomaticMinorUnit()
```
نشان می‌دهد که آیا واحد جزئی محور به‌صورت خودکار اختصاص داده می‌شود. قابل‌خواندن/قابل‌نوشتن boolean.

**بازگشت:**
boolean
### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public final void setAutomaticMinorUnit(boolean value)
```

نشان می‌دهد که آیا واحد جزئی محور به‌صورت خودکار اختصاص داده می‌شود. قابل‌خواندن/قابل‌نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public final double getMajorUnit()
```

نمایش می‌دهد که واحدهای بزرگ برای محور تاریخ یا مقدار چیست. قابل‌خواندن/قابِل نوشتن double.

**بازگشت:**
double
### setMajorUnit(double value) {#setMajorUnit-double-}
```
public final void setMajorUnit(double value)
```

نمایش می‌دهد که واحدهای بزرگ برای محور تاریخ یا مقدار چیست. قابل‌خواندن/قابِل نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public final boolean isAutomaticMajorUnit()
```

نشان می‌دهد که آیا واحد بزرگ محور به‌صورت خودکار اختصاص داده می‌شود. قابل‌خواندن/قابِل نوشتن boolean.

**بازگشت:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public final void setAutomaticMajorUnit(boolean value)
```

نشان می‌دهد که آیا واحد بزرگ محور به‌صورت خودکار اختصاص داده می‌شود. قابل‌خواندن/قابِل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public final boolean isAutomaticMinValue()
```

نشان می‌دهد که آیا مقدار کمینه به‌صورت خودکار اختصاص داده می‌شود. قابل‌خواندن/قابِل نوشتن boolean.

**بازگشت:**
boolean
### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public final void setAutomaticMinValue(boolean value)
```

نشان می‌دهد که آیا مقدار کمینه به‌صورت خودکار اختصاص داده می‌شود. قابل‌خواندن/قابِل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public final double getMinValue()
```

نمایش می‌دهد که مقدار کمینه روی محور مقدار چیست. قابل‌خواندن/قابِل نوشتن double.

**بازگشت:**
double
### setMinValue(double value) {#setMinValue-double-}
```
public final void setMinValue(double value)
```

نمایش می‌دهد که مقدار کمینه روی محور مقدار چیست. قابل‌خواندن/قابِل نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public final boolean isLogarithmic()
```

نمایش می‌دهد که آیا نوع مقیاس محور مقدار لگاریتمی است یا نه. قابل‌خواندن/قابِل نوشتن boolean.

**بازگشت:**
boolean
### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public final void setLogarithmic(boolean value)
```

نمایش می‌دهد که آیا نوع مقیاس محور مقدار لگاریتمی است یا نه. قابل‌خواندن/قابِل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public final double getLogBase()
```

نمایش می‌دهد که پایه لگاریتمی چیست. مقدار پیش‌فرض 10 است. قابل‌خواندن/قابِل نوشتن double.

**بازگشت:**
double
### setLogBase(double value) {#setLogBase-double-}
```
public final void setLogBase(double value)
```

نمایش می‌دهد که پایه لگاریتمی چیست. مقدار پیش‌فرض 10 است. قابل‌خواندن/قابِل نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public final boolean isPlotOrderReversed()
```

نمایش می‌دهد که آیا PowerPoint داده‌ها را از انتها به ابتدا ترسیم می‌کند. قابل‌خواندن/قابِل نوشتن boolean.

**بازگشت:**
boolean
### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public final void setPlotOrderReversed(boolean value)
```

نمایش می‌دهد که آیا PowerPoint داده‌ها را از انتها به ابتدا ترسیم می‌کند. قابل‌خواندن/قابِل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

نمایش می‌دهد که آیا محور قابل مشاهده است. قابل‌خواندن/قابِل نوشتن boolean.

**بازگشت:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

نمایش می‌دهد که آیا محور قابل مشاهده است. قابل‌خواندن/قابِل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public final int getMajorTickMark()
```

نمایش می‌دهد که نوع علامت تیک بزرگ برای محور مشخص شده چیست. قابل‌خواندن/قابِل نوشتن [TickMarkType](../../com.aspose.slides/tickmarktype).

**بازگشت:**
int
### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public final void setMajorTickMark(int value)
```

نمایش می‌دهد که نوع علامت تیک بزرگ برای محور مشخص شده چیست. قابل‌خواندن/قابِل نوشتن [TickMarkType](../../com.aspose.slides/tickmarktype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public final int getMinorTickMark()
```

نمایش می‌دهد که نوع علامت تیک جزئی برای محور مشخص شده چیست. قابل‌خواندن/قابِل نوشتن [TickMarkType](../../com.aspose.slides/tickmarktype).

**بازگشت:**
int
### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public final void setMinorTickMark(int value)
```

نمایش می‌دهد که نوع علامت تیک جزئی برای محور مشخص شده چیست. قابل‌خواندن/قابِل نوشتن [TickMarkType](../../com.aspose.slides/tickmarktype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public final int getTickLabelPosition()
```

نمایش می‌دهد که موقعیت برچسب‌های تیک روی محور مشخص شده چیست. قابل‌خواندن/قابِل نوشتن [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**بازگشت:**
int
### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public final void setTickLabelPosition(int value)
```

نمایش می‌دهد که موقعیت برچسب‌های تیک روی محور مشخص شده چیست. قابل‌خواندن/قابِل نوشتن [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public final int getMajorUnitScale()
```

نمایش می‌دهد که مقیاس واحد بزرگ برای محور تاریخ چیست. قابل‌خواندن/قابِل نوشتن [TimeUnitType](../../com.aspose.slides/timeunittype).

**بازگشت:**
int
### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public final void setMajorUnitScale(int value)
```

نمایش می‌دهد که مقیاس واحد بزرگ برای محور تاریخ چیست. قابل‌خواندن/قابِل نوشتن [TimeUnitType](../../com.aspose.slides/timeunittype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public final int getMinorUnitScale()
```

نمایش می‌دهد که مقیاس واحد بزرگ برای محور تاریخ چیست. قابل‌خواندن/قابِل نوشتن [TimeUnitType](../../com.aspose.slides/timeunittype).

**بازگشت:**
int
### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public final void setMinorUnitScale(int value)
```

نمایش می‌دهد که مقیاس واحد بزرگ برای محور تاریخ چیست. قابل‌خواندن/قابِل نوشتن [TimeUnitType](../../com.aspose.slides/timeunittype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public final int getBaseUnitScale()
```

مشخص می‌کند که کوچک‌ترین واحد زمان که بر روی محور تاریخ نمایش داده می‌شود چیست. قابل‌خواندن/قابِل نوشتن [TimeUnitType](../../com.aspose.slides/timeunittype).

**بازگشت:**
int
### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public final void setBaseUnitScale(int value)
```

مشخص می‌کند که کوچک‌ترین واحد زمان که بر روی محور تاریخ نمایش داده می‌شود چیست. قابل‌خواندن/قابِل نوشتن [TimeUnitType](../../com.aspose.slides/timeunittype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```

نمایش می‌دهد که قالب خطوط شبکه جزئی روی محور نمودار چیست. فقط‌خواندنی [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**بازگشت:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public final IChartLinesFormat getMajorGridLinesFormat()
```

نمایش می‌دهد که قالب خطوط شبکه بزرگ روی محور نمودار چیست. فقط‌خواندنی [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**بازگشت:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public final boolean getShowMinorGridLines()
```

برای مخفی‌سازی خطوط شبکه جزئی، ویژگی MinorGridLinesFormat.Line.FillFormat.FillType را به FillType.NoFill تنظیم کنید. فقط‌خواندنی boolean.

**بازگشت:**
boolean
### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public final boolean getShowMajorGridLines()
```

برای مخفی‌سازی خطوط شبکه بزرگ، ویژگی MajorGridLinesFormat.Line.FillFormat.FillType را به FillType.NoFill تنظیم کنید. فقط‌خواندنی boolean.

**بازگشت:**
boolean
### getFormat() {#getFormat--}
```
public final IAxisFormat getFormat()
```

نمایش می‌دهد که قالب محور چیست. فقط‌خواندنی [IAxisFormat](../../com.aspose.slides/iaxisformat).

**بازگشت:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

نمایش می‌دهد که قالب متن چیست. فقط‌خواندنی [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**بازگشت:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getTitle() {#getTitle--}
```
public final IChartTitle getTitle()
```

دریافت عنوان محور. فقط‌خواندنی [IChartTitle](../../com.aspose.slides/icharttitle).

**بازگشت:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### getCrossType() {#getCrossType--}
```
public final int getCrossType()
```

نمایش می‌دهد که CrossType روی محور مشخص شده چه مقدار است که محور دیگر از آن عبور می‌کند. قابل‌خواندن/قابِل نوشتن [CrossesType](../../com.aspose.slides/crossestype).

**بازگشت:**
int
### setCrossType(int value) {#setCrossType-int-}
```
public final void setCrossType(int value)
```

نمایش می‌دهد که CrossType روی محور مشخص شده چه مقدار است که محور دیگر از آن عبور می‌کند. قابل‌خواندن/قابِل نوشتن [CrossesType](../../com.aspose.slides/crossestype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```

نمایش می‌دهد که موقعیت محور چیست. قابل‌خواندن/قابِل نوشتن [AxisPositionType](../../com.aspose.slides/axispositiontype).

**بازگشت:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

نمایش می‌دهد که موقعیت محور چیست. قابل‌خواندن/قابِل نوشتن [AxisPositionType](../../com.aspose.slides/axispositiontype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

تعیین می‌کند که آیا محور دارای عنوان قابل مشاهده است یا خیر. قابل‌خواندن/قابِل نوشتن boolean.

**بازگشت:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

تعیین می‌کند که آیا محور دارای عنوان قابل مشاهده است یا خیر. قابل‌خواندن/قابِل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

نمایش می‌دهد که رشته قالب برای برچسب‌های محور چیست. قابل‌خواندن/قابِل نوشتن String.

**بازگشت:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

نمایش می‌دهد که رشته قالب برای برچسب‌های محور چیست. قابل‌خواندن/قابِل نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

نشان می‌دهد که آیا قالب به داده منبع پیوند دارد. قابل‌خواندن/قابِل نوشتن boolean.

**بازگشت:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

نشان می‌دهد که آیا قالب به داده منبع پیوند دارد. قابل‌خواندن/قابِل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public final float getTickLabelRotationAngle()
```

نمایش می‌دهد که زاویه چرخش برچسب‌های تیک چیست. قابل‌خواندن/قابِل نوشتن float.

**بازگشت:**
float
### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public final void setTickLabelRotationAngle(float value)
```

نمایش می‌دهد که زاویه چرخش برچسب‌های تیک چیست. قابل‌خواندن/قابِل نوشتن float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public final long getTickLabelSpacing()
```

مشخص می‌کند که بین برچسب‌های رسم‌شده چه تعداد برچسب باید صرف‌نظر شود. برای محور دسته یا سری اعمال می‌شود. قابل‌خواندن/قابِل نوشتن long.

**بازگشت:**
long
### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public final void setTickLabelSpacing(long value)
```

مشخص می‌کند که بین برچسب‌های رسم‌شده چه تعداد برچسب باید صرف‌نظر شود. برای محور دسته یا سری اعمال می‌شود. قابل‌خواندن/قابِل نوشتن long.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public final boolean isAutomaticTickLabelSpacing()
```

مقدار خودکار فاصله برچسب‌های تیک را مشخص می‌کند. اگر false باشد: از ویژگی TickLabelSpacing استفاده می‌شود. قابل‌خواندن/قابِل نوشتن boolean.

**بازگشت:**
boolean
### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public final void setAutomaticTickLabelSpacing(boolean value)
```

مقدار خودکار فاصله برچسب‌های تیک را مشخص می‌کند. اگر false باشد: از ویژگی TickLabelSpacing استفاده می‌شود. قابل‌خواندن/قابِل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public final long getTickMarksSpacing()
```

مشخص می‌کند که قبل از رسم تیک بعدی چند تیک باید کنار گذاشته شود. برای محور دسته یا سری اعمال می‌شود. قابل‌خواندن/قابِل نوشتن int.

**بازگشت:**
long
### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public final void setTickMarksSpacing(long value)
```

مشخص می‌کند که قبل از رسم تیک بعدی چند تیک باید کنار گذاشته شود. برای محور دسته یا سری اعمال می‌شود. قابل‌خواندن/قابِل نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public final boolean isAutomaticTickMarksSpacing()
```

مقدار خودکار فاصله تیک‌ها را مشخص می‌کند. اگر false باشد: از ویژگی TickMarksSpacing استفاده می‌شود. قابل‌خواندن/قابِل نوشتن boolean.

**بازگشت:**
boolean
### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public final void setAutomaticTickMarksSpacing(boolean value)
```

مقدار خودکار فاصله تیک‌ها را مشخص می‌کند. اگر false باشد: از ویژگی TickMarksSpacing استفاده می‌شود. قابل‌خواندن/قابِل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public final int getLabelOffset()
```

فاصله برچسب‌ها از محور را مشخص می‌کند. برای محور دسته یا تاریخ اعمال می‌شود. مقدار باید بین 0٪ و 1000٪ باشد. قابل‌خواندن/قابِل نوشتن int.

**بازگشت:**
int
### setLabelOffset(int value) {#setLabelOffset-int-}
```
public final void setLabelOffset(int value)
```

فاصله برچسب‌ها از محور را مشخص می‌کند. برای محور دسته یا تاریخ اعمال می‌شود. مقدار باید بین 0٪ و 1000٪ باشد. قابل‌خواندن/قابِل نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getAggregationType() {#getAggregationType--}
```
public final int getAggregationType()
```

نمایانگر نوع تجمیع محور دسته (باینینگ) است. برای دسته اعمال می‌شود. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود.

**باز می‌گرداند:**
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public final void setAggregationType(int value)
```

نمایانگر نوع تجمیع محور دسته (باینینگ) است. برای دسته اعمال می‌شود. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public final double getBinWidth()
```

عرض بِن را زمانی که مقدار ویژگی AggregationType روی AxisAggregationType.ByBinWidth تنظیم شده باشد، مشخص می‌کند. برای محورهای دسته اعمال می‌شود. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود.

**باز می‌گرداند:**
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public final void setBinWidth(double value)
```

عرض بِن را زمانی که مقدار ویژگی AggregationType روی AxisAggregationType.ByBinWidth تنظیم شده باشد، مشخص می‌کند. برای محورهای دسته اعمال می‌شود. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public final long getNumberOfBins()
```

تعداد بِن‌ها را زمانی که مقدار ویژگی AggregationType روی AxisAggregationType.ByNumberOfBins تنظیم شده باشد، مشخص می‌کند. برای محورهای دسته اعمال می‌شود. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود.

**باز می‌گرداند:**
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public final void setNumberOfBins(long value)
```

تعداد بِن‌ها را زمانی که مقدار ویژگی AggregationType روی AxisAggregationType.ByNumberOfBins تنظیم شده باشد، مشخص می‌کند. برای محورهای دسته اعمال می‌شود. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public final boolean isOverflowBin()
```

مشخص می‌کند که بِن اضافه‌شده (overflow) اعمال شده است یا نه. برای تنظیم مقدار بِن اضافه‌شده از IsAutomaticOverflowBin و OverflowBin استفاده کنید.

**باز می‌گرداند:**
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public final void setOverflowBin(boolean value)
```

مشخص می‌کند که بِن اضافه‌شده (overflow) اعمال شده است یا نه. برای تنظیم مقدار بِن اضافه‌شده از IsAutomaticOverflowBin و OverflowBin استفاده کنید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public final boolean isAutomaticOverflowBin()
```

مقدار خودکار بِن اضافه‌شده را تعیین می‌کند. اگر false باشد از ویژگی OverflowBin استفاده کنید.

**باز می‌گرداند:**
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public final void setAutomaticOverflowBin(boolean value)
```

مقدار خودکار بِن اضافه‌شده را تعیین می‌کند. اگر false باشد از ویژگی OverflowBin استفاده کنید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public final double getOverflowBin()
```

مقدار سفارشی بِن اضافه‌شده را مشخص می‌کند. وقتی ویژگی IsAutomaticOverflowBin روی false تنظیم شده و ویژگی IsOverflowBin برابر true باشد، اعمال می‌شود.

**باز می‌گرداند:**
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public final void setOverflowBin(double value)
```

مقدار سفارشی بِن اضافه‌شده را مشخص می‌کند. وقتی ویژگی IsAutomaticOverflowBin روی false تنظیم شده و ویژگی IsOverflowBin برابر true باشد، اعمال می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public final boolean isUnderflowBin()
```

مشخص می‌کند که بِن کمبود (underflow) اعمال شده است یا نه. برای تنظیم مقدار بِن کمبود از IsAutomaticUnderflowBin و UnderflowBin استفاده کنید.

**باز می‌گرداند:**
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public final void setUnderflowBin(boolean value)
```

مشخص می‌کند که بِن کمبود (underflow) اعمال شده است یا نه. برای تنظیم مقدار بِن کمبود از IsAutomaticUnderflowBin و UnderflowBin استفاده کنید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public final boolean isAutomaticUnderflowBin()
```

مقدار خودکار بِن کمبود را تعیین می‌کند. اگر false باشد از ویژگی UnderflowBin استفاده کنید.

**باز می‌گرداند:**
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public final void setAutomaticUnderflowBin(boolean value)
```

مقدار خودکار بِن کمبود را تعیین می‌کند. اگر false باشد از ویژگی UnderflowBin استفاده کنید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public final double getUnderflowBin()
```

مقدار سفارشی بِن کمبود را مشخص می‌کند. وقتی ویژگی IsAutomaticUnderflowBin روی false تنظیم شده و ویژگی IsUnderflowBin برابر true باشد، اعمال می‌شود.

**باز می‌گرداند:**
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public final void setUnderflowBin(double value)
```

مقدار سفارشی بِن کمبود را مشخص می‌کند. وقتی ویژگی IsAutomaticUnderflowBin روی false تنظیم شده و ویژگی IsUnderflowBin برابر true باشد، اعمال می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

اسلاید والد یک FillFormat را برمی‌گرداند. فقط-خواندنی [BaseSlide](../../com.aspose.slides/baseslide).

**باز می‌گرداند:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ارائهٔ والد یک FillFormat را برمی‌گرداند. فقط-خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**باز می‌گرداند:**
[IPresentation](../../com.aspose.slides/ipresentation)