---
title: IAxis
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: شیئی را که نمایانگر محور نمودار است دربر می‌گیرد.
type: docs
url: /fa/com.aspose.slides/iaxis/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IAxis extends IFormattedTextContainer
```

شیئی را که نمایانگر محور نمودار است در بر می‌گیرد.

## متدها

| متد | توضیح |
| --- | --- |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | نشان می‌دهد آیا محور مقدار بین دسته‌ها محور دسته‌بندی را قطع می‌کند. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | نشان می‌دهد آیا محور مقدار بین دسته‌ها محور دسته‌بندی را قطع می‌کند. |
| [getCrossAt()](#getCrossAt--) | نقطه‌ای بر روی محور که محور عمودی آن را قطع می‌کند را نشان می‌دهد. |
| [setCrossAt(float value)](#setCrossAt-float-) | نقطه‌ای بر روی محور که محور عمودی آن را قطع می‌کند را نشان می‌دهد. |
| [getDisplayUnit()](#getDisplayUnit--) | مقدار مقیاس واحدهای نمایش برای محور مقدار را مشخص می‌کند. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | مقدار مقیاس واحدهای نمایش برای محور مقدار را مشخص می‌کند. |
| [getActualMaxValue()](#getActualMaxValue--) | مقدار حداکثر واقعی بر روی محور را مشخص می‌کند. |
| [getActualMinValue()](#getActualMinValue--) | مقدار حداقل واقعی بر روی محور را مشخص می‌کند. |
| [getActualMajorUnit()](#getActualMajorUnit--) | واحد اصلی واقعی محور را مشخص می‌کند. |
| [getActualMinorUnit()](#getActualMinorUnit--) | واحد فرعی واقعی محور را مشخص می‌کند. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | مقیاس واحد اصلی واقعی محور را مشخص می‌کند. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | مقیاس واحد فرعی واقعی محور را مشخص می‌کند. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | نشان می‌دهد آیا مقدار حداکثر به‌صورت خودکار اختصاص داده می‌شود. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | نشان می‌دهد آیا مقدار حداکثر به‌صورت خودکار اختصاص داده می‌شود. |
| [getMaxValue()](#getMaxValue--) | نمایانگر مقدار حداکثر بر روی محور مقدار است. |
| [setMaxValue(double value)](#setMaxValue-double-) | نمایانگر مقدار حداکثر بر روی محور مقدار است. |
| [getMinorUnit()](#getMinorUnit--) | واحدهای فرعی برای محور تاریخ یا مقدار را نشان می‌دهد. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | واحدهای فرعی برای محور تاریخ یا مقدار را نشان می‌دهد. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | نشان می‌دهد آیا واحد فرعی محور به‌صورت خودکار اختصاص داده می‌شود. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | نشان می‌دهد آیا واحد فرعی محور به‌صورت خودکار اختصاص داده می‌شود. |
| [getMajorUnit()](#getMajorUnit--) | واحدهای اصلی برای محور تاریخ یا مقدار را نشان می‌دهد. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | واحدهای اصلی برای محور تاریخ یا مقدار را نشان می‌دهد. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | نشان می‌دهد آیا واحد اصلی محور به‌صورت خودکار اختصاص داده می‌شود. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | نشان می‌دهد آیا واحد اصلی محور به‌صورت خودکار اختصاص داده می‌شود. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | نشان می‌دهد آیا مقدار حداقل به‌صورت خودکار اختصاص داده می‌شود. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | نشان می‌دهد آیا مقدار حداقل به‌صورت خودکار اختصاص داده می‌شود. |
| [getMinValue()](#getMinValue--) | مقدار حداقل بر روی محور مقدار را نشان می‌دهد. |
| [setMinValue(double value)](#setMinValue-double-) | مقدار حداقل بر روی محور مقدار را نشان می‌دهد. |
| [isLogarithmic()](#isLogarithmic--) | نشان می‌دهد آیا نوع مقیاس محور مقدار لگاریتمی است یا خیر. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | نشان می‌دهد آیا نوع مقیاس محور مقدار لگاریتمی است یا خیر. |
| [getLogBase()](#getLogBase--) | پایه لگاریتمی را نشان می‌دهد. |
| [setLogBase(double value)](#setLogBase-double-) | پایه لگاریتمی را نشان می‌دهد. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | نشان می‌دهد آیا مایکروسافت پاورپوینت داده‌ها را از آخر به اولین رسم می‌کند. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | نشان می‌دهد آیا مایکروسافت پاورپوینت داده‌ها را از آخر به اولین رسم می‌کند. |
| [isVisible()](#isVisible--) | نشان می‌دهد آیا محور قابل مشاهده است. |
| [setVisible(boolean value)](#setVisible-boolean-) | نشان می‌دهد آیا محور قابل مشاهده است. |
| [getMajorTickMark()](#getMajorTickMark--) | نوع علامت تیک اصلی برای محور مشخص‌شده را نشان می‌دهد. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | نوع علامت تیک اصلی برای محور مشخص‌شده را نشان می‌دهد. |
| [getMinorTickMark()](#getMinorTickMark--) | نوع علامت تیک فرعی برای محور مشخص‌شده را نشان می‌دهد. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | نوع علامت تیک فرعی برای محور مشخص‌شده را نشان می‌دهد. |
| [getTickLabelPosition()](#getTickLabelPosition--) | موقعیت برچسب‌های تیک-مارک بر روی محور مشخص‌شده را نشان می‌دهد. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | موقعیت برچسب‌های تیک-مارک بر روی محور مشخص‌شده را نشان می‌دهد. |
| [getMajorUnitScale()](#getMajorUnitScale--) | مقیاس واحد اصلی برای محور تاریخ را نشان می‌دهد. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | مقیاس واحد اصلی برای محور تاریخ را نشان می‌دهد. |
| [getMinorUnitScale()](#getMinorUnitScale--) | مقیاس واحد اصلی برای محور تاریخ را نشان می‌دهد. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | مقیاس واحد اصلی برای محور تاریخ را نشان می‌دهد. |
| [getBaseUnitScale()](#getBaseUnitScale--) | کوچک‌ترین واحد زمانی که بر روی محور تاریخ نمایش داده می‌شود را مشخص می‌کند. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | کوچک‌ترین واحد زمانی که بر روی محور تاریخ نمایش داده می‌شود را مشخص می‌کند. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | قالب خطوط شبکه فرعی بر روی محور نمودار را نشان می‌دهد. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | قالب خطوط شبکه اصلی بر روی محور نمودار را نشان می‌دهد. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | نشان می‌دهد آیا خطوط شبکه فرعی نمایش داده می‌شوند. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | نشان می‌دهد آیا خطوط شبکه اصلی نمایش داده می‌شوند. |
| [getFormat()](#getFormat--) | قالب محور را نشان می‌دهد. |
| [getTitle()](#getTitle--) | عنوان محور را دریافت می‌کند. |
| [getCrossType()](#getCrossType--) | نوع CrossType بر روی محور مشخص‌شده که محور دیگر آن را قطع می‌کند را نشان می‌دهد. |
| [setCrossType(int value)](#setCrossType-int-) | نوع CrossType بر روی محور مشخص‌شده که محور دیگر آن را قطع می‌کند را نشان می‌دهد. |
| [getPosition()](#getPosition--) | موقعیت محور را نشان می‌دهد. |
| [setPosition(int value)](#setPosition-int-) | موقعیت محور را نشان می‌دهد. |
| [hasTitle()](#hasTitle--) | تعیین می‌کند آیا محور دارای عنوان قابل مشاهده است. |
| [setTitle(boolean value)](#setTitle-boolean-) | تعیین می‌کند آیا محور دارای عنوان قابل مشاهده است. |
| [getNumberFormat()](#getNumberFormat--) | قالب رشته‌ای برای برچسب‌های محور را نشان می‌دهد. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | قالب رشته‌ای برای برچسب‌های محور را نشان می‌دهد. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | نشان می‌دهد آیا قالب به داده منبع پیوسته است. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | نشان می‌دهد آیا قالب به داده منبع پیوسته است. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | زاویه چرخش برچسب‌های تیک را نشان می‌دهد. خواندنی/قابل نوشتن float. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | زاویه چرخش برچسب‌های تیک را نشان می‌دهد. خواندنی/قابل نوشتن float. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | تعداد برچسب‌های تیکی که بین دو برچسب کشیده‌شده رد می‌شوند را مشخص می‌کند. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | تعداد برچسب‌های تیکی که بین دو برچسب کشیده‌شده رد می‌شوند را مشخص می‌کند. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | مقدار فاصله خودکار برچسب‌های تیک را مشخص می‌کند. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | مقدار فاصله خودکار برچسب‌های تیک را مشخص می‌کند. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | تعداد علامت‌های تیک که قبل از رسم علامت بعدی رد می‌شوند را مشخص می‌کند. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | تعداد علامت‌های تیک که قبل از رسم علامت بعدی رد می‌شوند را مشخص می‌کند. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | مقدار فاصله خودکار علامت‌های تیک را مشخص می‌کند. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | مقدار فاصله خودکار علامت‌های تیک را مشخص می‌کند. |
| [getLabelOffset()](#getLabelOffset--) | فاصله برچسب‌ها از محور را مشخص می‌کند. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | فاصله برچسب‌ها از محور را مشخص می‌کند. |
| [getCategoryAxisType()](#getCategoryAxisType--) | نوع محور دسته‌بندی را مشخص می‌کند. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | نوع محور دسته‌بندی را مشخص می‌کند. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | ویژگی IAxis.CategoryAxisType را با مقداری که به‌صورت خودکار بر اساس داده‌های محور تعیین می‌شود تنظیم می‌کند. |
| [getAggregationType()](#getAggregationType--) | نوع تجمیع محور دسته‌بندی (بینی) را نشان می‌دهد. |
| [setAggregationType(int value)](#setAggregationType-int-) | نوع تجمیع محور دسته‌بندی (بینی) را نشان می‌دهد. |
| [getBinWidth()](#getBinWidth--) | عرض بین را هنگام مقدار ویژگی AggregationType به AxisAggregationType.ByBinWidth تنظیم می‌کند. |
| [setBinWidth(double value)](#setBinWidth-double-) | عرض بین را هنگام مقدار ویژگی AggregationType به AxisAggregationType.ByBinWidth تنظیم می‌کند. |
| [getNumberOfBins()](#getNumberOfBins--) | تعداد بین‌ها هنگام مقدار ویژگی AggregationType به AxisAggregationType.ByNumberOfBins تنظیم می‌شود. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | تعداد بین‌ها هنگام مقدار ویژگی AggregationType به AxisAggregationType.ByNumberOfBins تنظیم می‌شود. |
| [isOverflowBin()](#isOverflowBin--) | نشان می‌دهد آیا بین‌افشار (overflow) اعمال می‌شود. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | نشان می‌دهد آیا بین‌افشار (overflow) اعمال می‌شود. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | مقدار خودکار بین‌افشار را مشخص می‌کند. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | مقدار خودکار بین‌افشار را مشخص می‌کند. |
| [getOverflowBin()](#getOverflowBin--) | مقدار سفارشی بین‌افشار را مشخص می‌کند. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | مقدار سفارشی بین‌افشار را مشخص می‌کند. |
| [isUnderflowBin()](#isUnderflowBin--) | نشان می‌دهد آیا بین‌پایین (underflow) اعمال می‌شود. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | نشان می‌دهد آیا بین‌پایین (underflow) اعمال می‌شود. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | مقدار خودکار بین‌پایین را مشخص می‌کند. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | مقدار خودکار بین‌پایین را مشخص می‌کند. |
| [getUnderflowBin()](#getUnderflowBin--) | مقدار سفارشی بین‌پایین را مشخص می‌کند. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | مقدار سفارشی بین‌پایین را مشخص می‌کند. |

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```

نشان می‌دهد آیا محور مقدار بین دسته‌ها محور دسته‌بندی را قطع می‌کند. این ویژگی فقط برای محورهای دسته‌بندی اعمال می‌شود و برای نمودارهای سه‌بعدی اعمال نمی‌شود. خواندنی/قابل نوشتن boolean.

**بازگشت:**  
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```

نشان می‌دهد آیا محور مقدار بین دسته‌ها محور دسته‌بندی را قطع می‌کند. این ویژگی فقط برای محورهای دسته‌بندی اعمال می‌شود و برای نمودارهای سه‌بعدی اعمال نمی‌شود. خواندنی/قابل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```

نقطه‌ای بر روی محور که محور عمودی آن را قطع می‌کند را نشان می‌دهد. خواندنی/قابل نوشتن float.

**بازگشت:**  
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```

نقطه‌ای بر روی محور که محور عمودی آن را قطع می‌کند را نشان می‌دهد. خواندنی/قابل نوشتن float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public abstract int getDisplayUnit()
```

مقدار مقیاس واحدهای نمایش برای محور مقدار را مشخص می‌کند. خواندنی/قابل نوشتن [DisplayUnitType](../../com.aspose.slides/displayunittype).

**بازگشت:**  
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public abstract void setDisplayUnit(int value)
```

مقدار مقیاس واحدهای نمایش برای محور مقدار را مشخص می‌کند. خواندنی/قابل نوشتن [DisplayUnitType](../../com.aspose.slides/displayunittype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public abstract double getActualMaxValue()
```

مقدار حداکثر واقعی بر روی محور را مشخص می‌کند. برای دریافت مقدار واقعی پیش از این باید متد IChart.ValidateChartLayout() را فراخوانی کنید.

**بازگشت:**  
double

### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```

مقدار حداقل واقعی بر روی محور را مشخص می‌کند. برای دریافت مقدار واقعی پیش از این باید متد IChart.ValidateChartLayout() را فراخوانی کنید.

**بازگشت:**  
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```

واحد اصلی واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی پیش از این باید متد IChart.ValidateChartLayout() را فراخوانی کنید.

**بازگشت:**  
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```

واحد فرعی واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی پیش از این باید متد IChart.ValidateChartLayout() را فراخوانی کنید.

**بازگشت:**  
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```

مقیاس واحد اصلی واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی پیش از این باید متد IChart.ValidateChartLayout() را فراخوانی کنید.

**بازگشت:**  
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```

مقیاس واحد فرعی واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی پیش از این باید متد IChart.ValidateChartLayout() را فراخوانی کنید.

**بازگشت:**  
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public abstract boolean isAutomaticMaxValue()
```

نشان می‌دهد آیا مقدار حداکثر به‌صورت خودکار اختصاص داده می‌شود. خواندنی/قابل نوشتن boolean.

**بازگشت:**  
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public abstract void setAutomaticMaxValue(boolean value)
```

نشان می‌دهد آیا مقدار حداکثر به‌صورت خودکار اختصاص داده می‌شود. خواندنی/قابل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public abstract double getMaxValue()
```

نمایانگر مقدار حداکثر بر روی محور مقدار است. خواندنی/قابل نوشتن double.

**بازگشت:**  
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public abstract void setMaxValue(double value)
```

نمایانگر مقدار حداکثر بر روی محور مقدار است. خواندنی/قابل نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public abstract double getMinorUnit()
```

واحدهای فرعی برای محور تاریخ یا مقدار را نشان می‌دهد. خواندنی/قابل نوشتن double.

**بازگشت:**  
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```

واحدهای فرعی برای محور تاریخ یا مقدار را نشان می‌دهد. خواندنی/قابل نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```

نشان می‌دهد آیا واحد فرعی محور به‌صورت خودکار اختصاص داده می‌شود. خواندنی/قابل نوشتن boolean.

**بازگشت:**  
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```

نشان می‌دهد آیا واحد فرعی محور به‌صورت خودکار اختصاص داده می‌شود. خواندنی/قابل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```

واحدهای اصلی برای محور تاریخ یا مقدار را نشان می‌دهد. خواندنی/قابل نوشتن double.

**بازگشت:**  
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```

واحدهای اصلی برای محور تاریخ یا مقدار را نشان می‌دهد. خواندنی/قابل نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```

نشان می‌دهد آیا واحد اصلی محور به‌صورت خودکار اختصاص داده می‌شود. خواندنی/قابل نوشتن boolean.

**بازگشت:**  
boolean

### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public abstract void setAutomaticMajorUnit(boolean value)
```

نشان می‌دهد آیا واحد اصلی محور به‌صورت خودکار اختصاص داده می‌شود. خواندنی/قابل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public abstract boolean isAutomaticMinValue()
```

نشان می‌دهد آیا مقدار حداقل به‌صورت خودکار اختصاص داده می‌شود. خواندنی/قابل نوشتن boolean.

**بازگشت:**  
boolean

### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```

نشان می‌دهد آیا مقدار حداقل به‌صورت خودکار اختصاص داده می‌شود. خواندنی/قابل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public abstract double getMinValue()
```

مقدار حداقل بر روی محور مقدار را نشان می‌دهد. خواندنی/قابل نوشتن double.

**بازگشت:**  
double

### setMinValue(double value) {#setMinValue-double-}
```
public abstract void setMinValue(double value)
```

مقدار حداقل بر روی محور مقدار را نشان می‌دهد. خواندنی/قابل نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```

نشان می‌دهد آیا نوع مقیاس محور مقدار لگاریتمی است یا خیر. خواندنی/قابل نوشتن boolean.

**بازگشت:**  
boolean

### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```

نشان می‌دهد آیا نوع مقیاس محور مقدار لگاریتمی است یا خیر. خواندنی/قابل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public abstract double getLogBase()
```

پایه لگاریتمی را نشان می‌دهد. مقدار پیش‌فرض 10 است. خواندنی/قابل نوشتن double.

**بازگشت:**  
double

### setLogBase(double value) {#setLogBase-double-}
```
public abstract void setLogBase(double value)
```

پایه لگاریتمی را نشان می‌دهد. مقدار پیش‌فرض 10 است. خواندنی/قابل نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotOrderReversed()
```

نشان می‌دهد آیا مایکروسافت پاورپوینت داده‌ها را از آخر به اولین رسم می‌کند. خواندنی/قابل نوشتن boolean.

**بازگشت:**  
boolean

### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```

نشان می‌دهد آیا مایکروسافت پاورپوینت داده‌ها را از آخر به اولین رسم می‌کند. خواندنی/قابل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

نشان می‌دهد آیا محور قابل مشاهده است. خواندنی/قابل نوشتن boolean.

**بازگشت:**  
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

نشان می‌دهد آیا محور قابل مشاهده است. خواندنی/قابل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public abstract int getMajorTickMark()
```

نوع علامت تیک اصلی برای محور مشخص‌شده را نشان می‌دهد. خواندنی/قابل نوشتن [TickMarkType](../../com.aspose.slides/tickmarktype).

**بازگشت:**  
int

### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public abstract void setMajorTickMark(int value)
```

نوع علامت تیک اصلی برای محور مشخص‌شده را نشان می‌دهد. خواندنی/قابل نوشتن [TickMarkType](../../com.aspose.slides/tickmarktype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public abstract int getMinorTickMark()
```

نوع علامت تیک فرعی برای محور مشخص‌شده را نشان می‌دهد. خواندنی/قابل نوشتن [TickMarkType](../../com.aspose.slides/tickmarktype).

**بازگشت:**  
int

### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public abstract void setMinorTickMark(int value)
```

نوع علامت تیک فرعی برای محور مشخص‌شده را نشان می‌دهد. خواندنی/قابل نوشتن [TickMarkType](../../com.aspose.slides/tickmarktype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```

موقعیت برچسب‌های تیک-مارک بر روی محور مشخص‌شده را نشان می‌دهد. خواندنی/قابل نوشتن [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**بازگشت:**  
int

### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```

موقعیت برچسب‌های تیک-مارک بر روی محور مشخص‌شده را نشان می‌دهد. خواندنی/قابل نوشتن [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public abstract int getMajorUnitScale()
```

مقیاس واحد اصلی برای محور تاریخ را نشان می‌دهد. خواندنی/قابل نوشتن [TimeUnitType](../../com.aspose.slides/timeunittype).

**بازگشت:**  
int

### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public abstract void setMajorUnitScale(int value)
```

مقیاس واحد اصلی برای محور تاریخ را نشان می‌دهد. خواندنی/قابل نوشتن [TimeUnitType](../../com.aspose.slides/timeunittype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public abstract int getMinorUnitScale()
```

مقیاس واحد اصلی برای محور تاریخ را نشان می‌دهد. خواندنی/قابل نوشتن [TimeUnitType](../../com.aspose.slides/timeunittype).

**بازگشت:**  
int

### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public abstract void setMinorUnitScale(int value)
```

مقیاس واحد اصلی برای محور تاریخ را نشان می‌دهد. خواندنی/قابل نوشتن [TimeUnitType](../../com.aspose.slides/timeunittype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public abstract int getBaseUnitScale()
```

کوچک‌ترین واحد زمانی که بر روی محور تاریخ نمایش داده می‌شود را مشخص می‌کند. خواندنی/قابل نوشتن [TimeUnitType](../../com.aspose.slides/timeunittype).

**بازگشت:**  
int

### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public abstract void setBaseUnitScale(int value)
```

کوچک‌ترین واحد زمانی که بر روی محور تاریخ نمایش داده می‌شود را مشخص می‌کند. خواندنی/قابل نوشتن [TimeUnitType](../../com.aspose.slides/timeunittype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

قالب خطوط شبکه فرعی بر روی محور نمودار را نشان می‌دهد. فقط-خواندنی [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**بازگشت:**  
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public abstract IChartLinesFormat getMajorGridLinesFormat()
```

قالب خطوط شبکه اصلی بر روی محور نمودار را نشان می‌دهد. فقط-خواندنی [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**بازگشت:**  
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

نشان می‌دهد آیا خطوط شبکه فرعی نمایش داده می‌شوند. فقط-خواندنی boolean.

**بازگشت:**  
boolean

### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public abstract boolean getShowMajorGridLines()
```

نشان می‌دهد آیا خطوط شبکه اصلی نمایش داده می‌شوند. فقط-خواندنی boolean.

**بازگشت:**  
boolean

### getFormat() {#getFormat--}
```
public abstract IAxisFormat getFormat()
```

قالب محور را نشان می‌دهد. فقط-خواندنی [IAxisFormat](../../com.aspose.slides/iaxisformat).

**بازگشت:**  
[IAxisFormat](../../com.aspose.slides/iaxisformat)

### getTitle() {#getTitle--}
```
public abstract IChartTitle getTitle()
```

عنوان محور را دریافت می‌کند. فقط-خواندنی [IChartTitle](../../com.aspose.slides/icharttitle).

**بازگشت:**  
[IChartTitle](../../com.aspose.slides/icharttitle)

### getCrossType() {#getCrossType--}
```
public abstract int getCrossType()
```

نوع CrossType بر روی محور مشخص‌شده که محور دیگر آن را قطع می‌کند را نشان می‌دهد. خواندنی/قابل نوشتن [CrossesType](../../com.aspose.slides/crossestype).

**بازگشت:**  
int

### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```

نوع CrossType بر روی محور مشخص‌شده که محور دیگر آن را قطع می‌کند را نشان می‌دهد. خواندنی/قابل نوشتن [CrossesType](../../com.aspose.slides/crossestype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

موقعیت محور را نشان می‌دهد. خواندنی/قابل نوشتن [AxisPositionType](../../com.aspose.slides/axispositiontype).

**بازگشت:**  
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

موقعیت محور را نشان می‌دهد. خواندنی/قاب

ل نوشتن [AxisPositionType](../../com.aspose.slides/axispositiontype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

تعیین می‌کند آیا محور دارای عنوان قابل مشاهده است. خواندنی/قابل نوشتن boolean.

**بازگشت:**  
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

تعیین می‌کند آیا محور دارای عنوان قابل مشاهده است. خواندنی/قابل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

قالب رشته‌ای برای برچسب‌های محور را نشان می‌دهد. خواندنی/قابل نوشتن String.

**بازگشت:**  
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

قالب رشته‌ای برای برچسب‌های محور را نشان می‌دهد. خواندنی/قابل نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

نشان می‌دهد آیا قالب به داده منبع پیوسته است. خواندنی/قابل نوشتن boolean.

**بازگشت:**  
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

نشان می‌دهد آیا قالب به داده منبع پیوسته است. خواندنی/قابل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public abstract float getTickLabelRotationAngle()
```

زاویه چرخش برچسب‌های تیک را نشان می‌دهد. خواندنی/قابل نوشتن float.

**بازگشت:**  
float

### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public abstract void setTickLabelRotationAngle(float value)
```

زاویه چرخش برچسب‌های تیک را نشان می‌دهد. خواندنی/قابل نوشتن float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```

تعداد برچسب‌های تیکی که بین دو برچسب کشیده‌شده رد می‌شوند را مشخص می‌کند. خواندنی/قابل نوشتن long.

**بازگشت:**  
long

### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public abstract void setTickLabelSpacing(long value)
```

تعداد برچسب‌های تیکی که بین دو برچسب کشیده‌شده رد می‌شوند را مشخص می‌کند. خواندنی/قابل نوشتن long.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public abstract boolean isAutomaticTickLabelSpacing()
```

مقدار فاصله خودکار برچسب‌های تیک را مشخص می‌کند. اگر false باشد از ویژگی TickLabelSpacing استفاده می‌شود. خواندنی/قابل نوشتن boolean.

**بازگشت:**  
boolean

### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public abstract void setAutomaticTickLabelSpacing(boolean value)
```

مقدار فاصله خودکار برچسب‌های تیک را مشخص می‌کند. اگر false باشد از ویژگی TickLabelSpacing استفاده می‌شود. خواندنی/قابل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public abstract long getTickMarksSpacing()
```

تعداد علامت‌های تیک که قبل از رسم علامت بعدی رد می‌شوند را مشخص می‌کند. برای محورهای دسته یا سری اعمال می‌شود. خواندنی/قابل نوشتن int.

**بازگشت:**  
long

### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```

تعداد علامت‌های تیک که قبل از رسم علامت بعدی رد می‌شوند را مشخص می‌کند. برای محورهای دسته یا سری اعمال می‌شود. خواندنی/قابل نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public abstract boolean isAutomaticTickMarksSpacing()
```

مقدار فاصله خودکار علامت‌های تیک را مشخص می‌کند. اگر false باشد از ویژگی TickMarksSpacing استفاده می‌شود. خواندنی/قابل نوشتن boolean.

**بازگشت:**  
boolean

### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public abstract void setAutomaticTickMarksSpacing(boolean value)
```

مقدار فاصله خودکار علامت‌های تیک را مشخص می‌کند. اگر false باشد از ویژگی TickMarksSpacing استفاده می‌شود. خواندنی/قابل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public abstract int getLabelOffset()
```

فاصله برچسب‌ها از محور را مشخص می‌کند. برای محورهای دسته یا تاریخ اعمال می‌شود. مقدار باید بین 0٪ و 1000٪ باشد. خواندنی/قابل نوشتن int.

**بازگشت:**  
int

### setLabelOffset(int value) {#setLabelOffset-int-}
```
public abstract void setLabelOffset(int value)
```

فاصله برچسب‌ها از محور را مشخص می‌کند. برای محورهای دسته یا تاریخ اعمال می‌شود. مقدار باید بین 0٪ و 1000٪ باشد. خواندنی/قابل نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public abstract int getCategoryAxisType()
```

نوع محور دسته‌بندی را مشخص می‌کند. خواندنی/قابل نوشتن [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**بازگشت:**  
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public abstract void setCategoryAxisType(int value)
```

نوع محور دسته‌بندی را مشخص می‌کند. خواندنی/قابل نوشتن [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public abstract void setCategoryAxisTypeAutomatically()
```

ویژگی IAxis.CategoryAxisType را با مقداری که به‌صورت خودکار بر اساس داده‌های محور تعیین می‌شود تنظیم می‌کند.

### getAggregationType() {#getAggregationType--}
```
public abstract int getAggregationType()
```

نوع تجمیع محور دسته‌بندی (بینی) را نشان می‌دهد. برای دسته اعمال می‌شود. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود.

**بازگشت:**  
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```

نوع تجمیع محور دسته‌بندی (بینی) را نشان می‌دهد. برای دسته اعمال می‌شود. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```

عرض بین را هنگام مقدار ویژگی AggregationType به AxisAggregationType.ByBinWidth تنظیم می‌کند. برای محورهای دسته اعمال می‌شود. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود.

**بازگشت:**  
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```

عرض بین را هنگام مقدار ویژگی AggregationType به AxisAggregationType.ByBinWidth تنظیم می‌کند. برای محورهای دسته اعمال می‌شود. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```

تعداد بین‌ها هنگام مقدار ویژگی AggregationType به AxisAggregationType.ByNumberOfBins تنظیم می‌شود. برای محورهای دسته اعمال می‌شود. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود.

**بازگشت:**  
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public abstract void setNumberOfBins(long value)
```

تعداد بین‌ها هنگام مقدار ویژگی AggregationType به AxisAggregationType.ByNumberOfBins تنظیم می‌شود. برای محورهای دسته اعمال می‌شود. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```

نشان می‌دهد آیا بین‌افشار (overflow) اعمال می‌شود. از IsAutomaticOverflowBin و OverflowBin برای تنظیم مقدار بین‌افشار استفاده کنید.

**بازگشت:**  
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public abstract void setOverflowBin(boolean value)
```

نشان می‌دهد آیا بین‌افشار (overflow) اعمال می‌شود. از IsAutomaticOverflowBin و OverflowBin برای تنظیم مقدار بین‌افشار استفاده کنید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public abstract boolean isAutomaticOverflowBin()
```

مقدار خودکار بین‌افشار را مشخص می‌کند. اگر false باشد از ویژگی OverflowBin استفاده می‌شود.

**بازگشت:**  
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public abstract void setAutomaticOverflowBin(boolean value)
```

مقدار خودکار بین‌افشار را مشخص می‌کند. اگر false باشد از ویژگی OverflowBin استفاده می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public abstract double getOverflowBin()
```

مقدار سفارشی بین‌افشار را مشخص می‌کند. زمانی که ویژگی IsAutomaticOverflowBin برابر false باشد و IsOverflowBin برابر true باشد اعمال می‌شود.

**بازگشت:**  
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public abstract void setOverflowBin(double value)
```

مقدار سفارشی بین‌افشار را مشخص می‌کند. زمانی که ویژگی IsAutomaticOverflowBin برابر false باشد و IsOverflowBin برابر true باشد اعمال می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public abstract boolean isUnderflowBin()
```

نشان می‌دهد آیا بین‌پایین (underflow) اعمال می‌شود. از IsAutomaticUnderflowBin و UnderflowBin برای تنظیم مقدار بین‌پایین استفاده کنید.

**بازگشت:**  
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```

نشان می‌دهد آیا بین‌پایین (underflow) اعمال می‌شود. از IsAutomaticUnderflowBin و UnderflowBin برای تنظیم مقدار بین‌پایین استفاده کنید.

**پارامترها:**
| پارامهر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public abstract boolean isAutomaticUnderflowBin()
```

مقدار خودکار بین‌پایین را مشخص می‌کند. اگر false باشد از ویژگی UnderflowBin استفاده می‌شود.

**بازگشت:**  
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public abstract void setAutomaticUnderflowBin(boolean value)
```

مقدار خودکار بین‌پایین را مشخص می‌کند. اگر false باشد از ویژگی UnderflowBin استفاده می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public abstract double getUnderflowBin()
```

مقدار سفارشی بین‌پایین را مشخص می‌کند. زمانی که ویژگی IsAutomaticUnderflowBin برابر false باشد و IsUnderflowBin برابر true باشد اعمال می‌شود.

**بازگشت:**  
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```

مقدار سفارشی بین‌پایین را مشخص می‌کند. زمانی که ویژگی IsAutomaticUnderflowBin برابر false باشد و IsUnderflowBin برابر true باشد اعمال می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |