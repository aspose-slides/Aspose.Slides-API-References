---
title: IAxis
second_title: مرجع API Aspose.Slides برای جاوا
description: شیئی را که محور نمودار را نشان می‌دهد، در بر می‌گیرد.
type: docs
url: /fa/com.aspose.slides/iaxis/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IAxis extends IFormattedTextContainer
```

شیء‌ای را در بر می‌گیرد که محور یک نمودار را نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | نشان می‌دهد آیا محور مقدار بین دسته‌ها محور دسته‌بندی را قطع می‌کند. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | نشان می‌دهد آیا محور مقدار بین دسته‌ها محور دسته‌بندی را قطع می‌کند. |
| [getCrossAt()](#getCrossAt--) | نقطه‌ای روی محور را نشان می‌دهد که محور عمود بر آن را قطع می‌کند. |
| [setCrossAt(float value)](#setCrossAt-float-) | نقطه‌ای روی محور را نشان می‌دهد که محور عمود بر آن را قطع می‌کند. |
| [getDisplayUnit()](#getDisplayUnit--) | مقدار مقیاس واحدهای نمایش برای محور مقدار را مشخص می‌کند. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | مقدار مقیاس واحدهای نمایش برای محور مقدار را مشخص می‌کند. |
| [getActualMaxValue()](#getActualMaxValue--) | حداکثر مقدار واقعی روی محور را مشخص می‌کند. |
| [getActualMinValue()](#getActualMinValue--) | حداقل مقدار واقعی روی محور را مشخص می‌کند. |
| [getActualMajorUnit()](#getActualMajorUnit--) | واحد اصلی واقعی محور را مشخص می‌کند. |
| [getActualMinorUnit()](#getActualMinorUnit--) | واحد جزئی واقعی محور را مشخص می‌کند. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | مقیاس واحد اصلی واقعی محور را مشخص می‌کند. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | مقیاس واحد جزئی واقعی محور را مشخص می‌کند. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | نشان می‌دهد آیا مقدار حداکثر به طور خودکار اختصاص داده می‌شود. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | نشان می‌دهد آیا مقدار حداکثر به طور خودکار اختصاص داده می‌شود. |
| [getMaxValue()](#getMaxValue--) | حداکثر مقدار روی محور مقدار را نشان می‌دهد. |
| [setMaxValue(double value)](#setMaxValue-double-) | حداکثر مقدار روی محور مقدار را نشان می‌دهد. |
| [getMinorUnit()](#getMinorUnit--) | واحدهای جزئی برای محور تاریخ یا مقدار را نشان می‌دهد. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | واحدهای جزئی برای محور تاریخ یا مقدار را نشان می‌دهد. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | نشان می‌دهد آیا واحد جزئی محور به طور خودکار اختصاص داده می‌شود. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | نشان می‌دهد آیا واحد جزئی محور به طور خودکار اختصاص داده می‌شود. |
| [getMajorUnit()](#getMajorUnit--) | واحدهای اصلی برای محور تاریخ یا مقدار را نشان می‌دهد. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | واحدهای اصلی برای محور تاریخ یا مقدار را نشان می‌دهد. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | نشان می‌دهد آیا واحد اصلی محور به طور خودکار اختصاص داده می‌شود. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | نشان می‌دهد آیا واحد اصلی محور به طور خودکار اختصاص داده می‌شود. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | نشان می‌دهد آیا مقدار حداقل به طور خودکار اختصاص داده می‌شود. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | نشان می‌دهد آیا مقدار حداقل به طور خودکار اختصاص داده می‌شود. |
| [getMinValue()](#getMinValue--) | حداقل مقدار روی محور مقدار را نشان می‌دهد. |
| [setMinValue(double value)](#setMinValue-double-) | حداقل مقدار روی محور مقدار را نشان می‌دهد. |
| [isLogarithmic()](#isLogarithmic--) | نشان می‌دهد آیا نوع مقیاس محور مقدار لگاریتمی است یا خیر. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | نشان می‌دهد آیا نوع مقیاس محور مقدار لگاریتمی است یا خیر. |
| [getLogBase()](#getLogBase--) | پایه لگاریتمی را نشان می‌دهد. |
| [setLogBase(double value)](#setLogBase-double-) | پایه لگاریتمی را نشان می‌دهد. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | نشان می‌دهد آیا مایکروسافت پاورپوینت نقاط داده را از آخر به اول رسم می‌کند. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | نشان می‌دهد آیا مایکروسافت پاورپوینت نقاط داده را از آخر به اول رسم می‌کند. |
| [isVisible()](#isVisible--) | نشان می‌دهد آیا محور قابل مشاهده است. |
| [setVisible(boolean value)](#setVisible-boolean-) | نشان می‌دهد آیا محور قابل مشاهده است. |
| [getMajorTickMark()](#getMajorTickMark--) | نوع علامت تیک اصلی برای محور مشخص‌شده را نشان می‌دهد. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | نوع علامت تیک اصلی برای محور مشخص‌شده را نشان می‌دهد. |
| [getMinorTickMark()](#getMinorTickMark--) | نوع علامت تیک جزئی برای محور مشخص‌شده را نشان می‌دهد. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | نوع علامت تیک جزئی برای محور مشخص‌شده را نشان می‌دهد. |
| [getTickLabelPosition()](#getTickLabelPosition--) | موقعیت برچسب‌های علامت تیک روی محور مشخص‌شده را نشان می‌دهد. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | موقعیت برچسب‌های علامت تیک روی محور مشخص‌شده را نشان می‌دهد. |
| [getMajorUnitScale()](#getMajorUnitScale--) | مقیاس واحد اصلی برای محور تاریخ را نشان می‌دهد. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | مقیاس واحد اصلی برای محور تاریخ را نشان می‌دهد. |
| [getMinorUnitScale()](#getMinorUnitScale--) | مقیاس واحد اصلی برای محور تاریخ را نشان می‌دهد. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | مقیاس واحد اصلی برای محور تاریخ را نشان می‌دهد. |
| [getBaseUnitScale()](#getBaseUnitScale--) | کوچک‌ترین واحد زمانی که بر روی محور تاریخ نمایش داده می‌شود را مشخص می‌کند. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | کوچک‌ترین واحد زمانی که بر روی محور تاریخ نمایش داده می‌شود را مشخص می‌کند. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | قالب خطوط شبکه جزئی روی محور نمودار را نشان می‌دهد. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | قالب خطوط شبکه اصلی روی محور نمودار را نشان می‌دهد. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | نشان می‌دهد آیا خطوط شبکه جزئی نمایش داده می‌شوند. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | نشان می‌دهد آیا خطوط شبکه اصلی نمایش داده می‌شوند. |
| [getFormat()](#getFormat--) | قالب محور را نشان می‌دهد. |
| [getTitle()](#getTitle--) | عنوان محور را دریافت می‌کند. |
| [getCrossType()](#getCrossType--) | نوع CrossType روی محور مشخص‌شده که محور دیگر از آن عبور می‌کند را نشان می‌دهد. |
| [setCrossType(int value)](#setCrossType-int-) | نوع CrossType روی محور مشخص‌شده که محور دیگر از آن عبور می‌کند را نشان می‌دهد. |
| [getPosition()](#getPosition--) | موقعیت محور را نشان می‌دهد. |
| [setPosition(int value)](#setPosition-int-) | موقعیت محور را نشان می‌دهد. |
| [hasTitle()](#hasTitle--) | تعیین می‌کند آیا محور عنوان قابل مشاهده‌ای دارد. |
| [setTitle(boolean value)](#setTitle-boolean-) | تعیین می‌کند آیا محور عنوان قابل مشاهده‌ای دارد. |
| [getNumberFormat()](#getNumberFormat--) | رشته قالب برای برچسب‌های محور را نشان می‌دهد. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | رشته قالب برای برچسب‌های محور را نشان می‌دهد. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | نشان می‌دهد آیا قالب به داده منبع مرتبط است. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | نشان می‌دهد آیا قالب به داده منبع مرتبط است. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | زاویه چرخش برچسب‌های تیک را نشان می‌دهد (خواندنی/نوشتنی float). |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | زاویه چرخش برچسب‌های تیک را نشان می‌دهد (خواندنی/نوشتنی float). |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | تعداد برچسب‌های تیک که باید بین برچسب‌های رسم‌شده رد شوند را مشخص می‌کند. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | تعداد برچسب‌های تیک که باید بین برچسب‌های رسم‌شده رد شوند را مشخص می‌کند. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | مقدار فاصله خودکار برچسب تیک را مشخص می‌کند. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | مقدار فاصله خودکار برچسب تیک را مشخص می‌کند. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | تعداد علامت‌های تیک که باید قبل از رسم علامت بعدی رد شوند را مشخص می‌کند. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | تعداد علامت‌های تیک که باید قبل از رسم علامت بعدی رد شوند را مشخص می‌کند. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | مقدار فاصله خودکار علامت‌های تیک را مشخص می‌کند. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | مقدار فاصله خودکار علامت‌های تیک را مشخص می‌کند. |
| [getLabelOffset()](#getLabelOffset--) | فاصله برچسب‌ها از محور را مشخص می‌کند. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | فاصله برچسب‌ها از محور را مشخص می‌کند. |
| [getCategoryAxisType()](#getCategoryAxisType--) | نوع محور دسته‌بندی را مشخص می‌کند. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | نوع محور دسته‌بندی را مشخص می‌کند. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | ویژگی IAxis.CategoryAxisType را با مقدار تعیین‌شده به‌صورت خودکار بر پایه داده‌های محور تنظیم می‌کند. |
| [getAggregationType()](#getAggregationType--) | نوع تجمیع محور دسته‌بندی (بینی) را نشان می‌دهد. |
| [setAggregationType(int value)](#setAggregationType-int-) | نوع تجمیع محور دسته‌بندی (بینی) را نشان می‌دهد. |
| [getBinWidth()](#getBinWidth--) | عرض بن را زمانی که مقدار ویژگی AggregationType بر AxisAggregationType.ByBinWidth تنظیم شده است، مشخص می‌کند. |
| [setBinWidth(double value)](#setBinWidth-double-) | عرض بن را زمانی که مقدار ویژگی AggregationType بر AxisAggregationType.ByBinWidth تنظیم شده است، مشخص می‌کند. |
| [getNumberOfBins()](#getNumberOfBins--) | تعداد بن‌ها را زمانی که مقدار ویژگی AggregationType بر AxisAggregationType.ByNumberOfBins تنظیم شده است، مشخص می‌کند. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | تعداد بن‌ها را زمانی که مقدار ویژگی AggregationType بر AxisAggregationType.ByNumberOfBins تنظیم شده است، مشخص می‌کند. |
| [isOverflowBin()](#isOverflowBin--) | نشان می‌دهد آیا بن سرریز اعمال می‌شود. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | نشان می‌دهد آیا بن سرریز اعمال می‌شود. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | مقدار خودکار بن سرریز را مشخص می‌کند. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | مقدار خودکار بن سرریز را مشخص می‌کند. |
| [getOverflowBin()](#getOverflowBin--) | مقدار سفارشی بن سرریز را مشخص می‌کند. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | مقدار سفارشی بن سرریز را مشخص می‌کند. |
| [isUnderflowBin()](#isUnderflowBin--) | نشان می‌دهد آیا بن زیر جریان اعمال می‌شود. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | نشان می‌دهد آیا بن زیر جریان اعمال می‌شود. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | مقدار خودکار بن زیر جریان را مشخص می‌کند. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | مقدار خودکار بن زیر جریان را مشخص می‌کند. |
| [getUnderflowBin()](#getUnderflowBin--) | مقدار سفارشی بن زیر جریان را مشخص می‌کند. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | مقدار سفارشی بن زیر جریان را مشخص می‌کند. |

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```

نشان می‌دهد آیا محور مقدار بین دسته‌ها محور دسته‌بندی را قطع می‌کند. این ویژگی فقط برای محورهای دسته‌بندی کاربرد دارد و برای نمودارهای سه‌بعدی اعمال نمی‌شود. خواندنی/نوشتنی boolean.

**بازگشت:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```

نشان می‌دهد آیا محور مقدار بین دسته‌ها محور دسته‌بندی را قطع می‌کند. این ویژگی فقط برای محورهای دسته‌بندی کاربرد دارد و برای نمودارهای سه‌بعدی اعمال نمی‌شود. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```

نقطه‌ای روی محور را نشان می‌دهد که محور عمود بر آن را قطع می‌کند. خواندنی/نوشتنی float.

**بازگشت:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```

نقطه‌ای روی محور را نشان می‌دهد که محور عمود بر آن را قطع می‌کند. خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public abstract int getDisplayUnit()
```

مقدار مقیاس واحدهای نمایش برای محور مقدار را مشخص می‌کند. خواندنی/نوشتنی [DisplayUnitType](../../com.aspose.slides/displayunittype).

**بازگشت:**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public abstract void setDisplayUnit(int value)
```

مقدار مقیاس واحدهای نمایش برای محور مقدار را مشخص می‌کند. خواندنی/نوشتنی [DisplayUnitType](../../com.aspose.slides/displayunittype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public abstract double getActualMaxValue()
```

حداکثر مقدار واقعی روی محور را مشخص می‌کند. برای دریافت مقدار واقعی پیش از آن متد IChart.ValidateChartLayout() را فراخوانی کنید.

**بازگشت:**
double

### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```

حداقل مقدار واقعی روی محور را مشخص می‌کند. برای دریافت مقدار واقعی پیش از آن متد IChart.ValidateChartLayout() را فراخوانی کنید.

**بازگشت:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```

واحد اصلی واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی پیش از آن متد IChart.ValidateChartLayout() را فراخوانی کنید.

**بازگشت:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```

واحد جزئی واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی پیش از آن متد IChart.ValidateChartLayout() را فراخوانی کنید.

**بازگشت:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```

مقیاس واحد اصلی واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی پیش از آن متد IChart.ValidateChartLayout() را فراخوانی کنید.

**بازگشت:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```

مقیاس واحد جزئی واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی پیش از آن متد IChart.ValidateChartLayout() را فراخوانی کنید.

**بازگشت:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public abstract boolean isAutomaticMaxValue()
```

نشان می‌دهد آیا حداکثر مقدار به طور خودکار اختصاص داده می‌شود. خواندنی/نوشتنی boolean.

**بازگشت:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public abstract void setAutomaticMaxValue(boolean value)
```

نشان می‌دهد آیا حداکثر مقدار به طور خودکار اختصاص داده می‌شود. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public abstract double getMaxValue()
```

حداکثر مقدار روی محور مقدار را نشان می‌دهد. خواندنی/نوشتنی double.

**بازگشت:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public abstract void setMaxValue(double value)
```

حداکثر مقدار روی محور مقدار را نشان می‌دهد. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public abstract double getMinorUnit()
```

واحدهای جزئی برای محور تاریخ یا مقدار را نشان می‌دهد. خواندنی/نوشتنی double.

**بازگشت:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```

واحدهای جزئی برای محور تاریخ یا مقدار را نشان می‌دهد. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```

نشان می‌دهد آیا واحد جزئی محور به طور خودکار اختصاص داده می‌شود. خواندنی/نوشتنی boolean.

**بازگشت:**
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```

نشان می‌دهد آیا واحد جزئی محور به طور خودکار اختصاص داده می‌شود. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```

واحدهای اصلی برای محور تاریخ یا مقدار را نشان می‌دهد. خواندنی/نوشتنی double.

**بازگشت:**
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```

واحدهای اصلی برای محور تاریخ یا مقدار را نشان می‌دهد. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```

نشان می‌دهد آیا واحد اصلی محور به طور خودکار اختصاص داده می‌شود. خواندنی/نوشتنی boolean.

**بازگشت:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public abstract void setAutomaticMajorUnit(boolean value)
```

نشان می‌دهد که آیا واحد اصلی محور به‌طور خودکار اختصاص یافته است. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public abstract boolean isAutomaticMinValue()
```

نشان می‌دهد که آیا مقدار حداقل به‌طور خودکار اختصاص یافته است. قابل خواندن/نوشتن boolean.

**بازگشت:**
boolean

### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```

نشان می‌دهد که آیا مقدار حداقل به‌طور خودکار اختصاص یافته است. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public abstract double getMinValue()
```

نمایش مقدار حداقل بر روی محور مقدار. قابل خواندن/نوشتن double.

**بازگشت:**
double

### setMinValue(double value) {#setMinValue-double-}
```
public abstract void setMinValue(double value)
```

نمایش مقدار حداقل بر روی محور مقدار. قابل خواندن/نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```

نمایشگر این است که آیا نوع مقیاس محور مقدار لگاریتمی است یا نه. قابل خواندن/نوشتن boolean.

**بازگشت:**
boolean

### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```

نمایشگر این است که آیا نوع مقیاس محور مقدار لگاریتمی است یا نه. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public abstract double getLogBase()
```

نمایش پایه لگاریتمی. مقدار پیش‌فرض 10 است. قابل خواندن/نوشتن double.

**بازگشت:**
double

### setLogBase(double value) {#setLogBase-double-}
```
public abstract void setLogBase(double value)
```

نمایش پایه لگاریتمی. مقدار پیش‌فرض 10 است. قابل خواندن/نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotOrderReversed()
```

نمایشگر این است که آیا PowerPoint داده‌ها را از آخر به ابتدا ترسیم می‌کند یا نه. قابل خواندن/نوشتن boolean.

**بازگشت:**
boolean

### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```

نمایشگر این است که آیا PowerPoint داده‌ها را از آخر به ابتدا ترسیم می‌کند یا نه. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

نمایشگر این است که آیا محور قابل مشاهده است یا نه. قابل خواندن/نوشتن boolean.

**بازگشت:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

نمایشگر این است که آیا محور قابل مشاهده است یا نه. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public abstract int getMajorTickMark()
```

نمایش نوع علامت تیک اصلی برای محور مشخص شده. قابل خواندن/نوشتن [TickMarkType](../../com.aspose.slides/tickmarktype).

**بازگشت:**
int

### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public abstract void setMajorTickMark(int value)
```

نمایش نوع علامت تیک اصلی برای محور مشخص شده. قابل خواندن/نوشتن [TickMarkType](../../com.aspose.slides/tickmarktype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public abstract int getMinorTickMark()
```

نمایش نوع علامت تیک فرعی برای محور مشخص شده. قابل خواندن/نوشتن [TickMarkType](../../com.aspose.slides/tickmarktype).

**بازگشت:**
int

### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public abstract void setMinorTickMark(int value)
```

نمایش نوع علامت تیک فرعی برای محور مشخص شده. قابل خواندن/نوشتن [TickMarkType](../../com.aspose.slides/tickmarktype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```

نمایش موقعیت برچسب‌های علامت تیک بر روی محور مشخص شده. قابل خواندن/نوشتن [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**بازگشت:**
int

### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```

نمایش موقعیت برچسب‌های علامت تیک بر روی محور مشخص شده. قابل خواندن/نوشتن [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public abstract int getMajorUnitScale()
```

نمایش مقیاس واحد اصلی برای محور تاریخ. قابل خواندن/نوشتن [TimeUnitType](../../com.aspose.slides/timeunittype).

**بازگشت:**
int

### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public abstract void setMajorUnitScale(int value)
```

نمایش مقیاس واحد اصلی برای محور تاریخ. قابل خواندن/نوشتن [TimeUnitType](../../com.aspose.slides/timeunittype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public abstract int getMinorUnitScale()
```

نمایش مقیاس واحد اصلی برای محور تاریخ. قابل خواندن/نوشتن [TimeUnitType](../../com.aspose.slides/timeunittype).

**بازگشت:**
int

### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public abstract void setMinorUnitScale(int value)
```

نمایش مقیاس واحد اصلی برای محور تاریخ. قابل خواندن/نوشتن [TimeUnitType](../../com.aspose.slides/timeunittype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public abstract int getBaseUnitScale()
```

مشخص می‌کند کوچک‌ترین واحد زمانی که در محور تاریخ نشان داده می‌شود. قابل خواندن/نوشتن [TimeUnitType](../../com.aspose.slides/timeunittype).

**بازگشت:**
int

### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public abstract void setBaseUnitScale(int value)
```

مشخص می‌کند کوچک‌ترین واحد زمانی که در محور تاریخ نشان داده می‌شود. قابل خواندن/نوشتن [TimeUnitType](../../com.aspose.slides/timeunittype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

نمایش فرمت خطوط شبکه فرعی بر روی محور نمودار. فقط-خواندنی [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**بازگشت:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

نمایش فرمت خطوط شبکه اصلی بر روی محور نمودار. فقط-خواندنی [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**بازگشت:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

نمایشگر این است که آیا خطوط شبکه فرعی نشان داده می‌شوند یا نه. فقط-خواندنی boolean.

**بازگشت:**
boolean

### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public abstract boolean getShowMajorGridLines()
```

نمایشگر این است که آیا خطوط شبکه اصلی نشان داده می‌شوند یا نه. فقط-خواندنی boolean.

**بازگشت:**
boolean

### getFormat() {#getFormat--}
```
public abstract IAxisFormat getFormat()
```

نمایش فرمت محور. فقط-خواندنی [IAxisFormat](../../com.aspose.slides/iaxisformat).

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

نمایش CrossType بر روی محور مشخص شده که محور دیگر در آن عبور می‌کند. قابل خواندن/نوشتن [CrossesType](../../com.aspose.slides/crossestype).

**بازگشت:**
int

### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```

نمایش CrossType بر روی محور مشخص شده که محور دیگر در آن عبور می‌کند. قابل خواندن/نوشتن [CrossesType](../../com.aspose.slides/crossestype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

نمایش موقعیت محور. قابل خواندن/نوشتن [AxisPositionType](../../com.aspose.slides/axispositiontype).

**بازگشت:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

نمایش موقعیت محور. قابل خواندن/نوشتن [AxisPositionType](../../com.aspose.slides/axispositiontype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

تعیین می‌کند که آیا محور دارای عنوان قابل مشاهده است یا نه. قابل خواندن/نوشتن boolean.

**بازگشت:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

تعیین می‌کند که آیا محور دارای عنوان قابل مشاهده است یا نه. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

نمایش رشته فرمت برای برچسب‌های محور. قابل خواندن/نوشتن String.

**بازگشت:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

نمایش رشته فرمت برای برچسب‌های محور. قابل خواندن/نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

نشان می‌دهد که آیا فرمت به داده منبع پیوند خورده است. قابل خواندن/نوشتن boolean.

**بازگشت:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

نشان می‌دهد که آیا فرمت به داده منبع پیوند خورده است. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public abstract float getTickLabelRotationAngle()
```

نمایش زاویه چرخش برچسب‌های تیک. قابل خواندن/نوشتن float.

**بازگشت:**
float

### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public abstract void setTickLabelRotationAngle(float value)
```

نمایش زاویه چرخش برچسب‌های تیک. قابل خواندن/نوشتن float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```

مشخص می‌کند چند برچسب تیک باید بین برچسب‌های ترسیم شده رد شود. قابل خواندن/نوشتن long.

**بازگشت:**
long

### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public abstract void setTickLabelSpacing(long value)
```

مشخص می‌کند چند برچسب تیک باید بین برچسب‌های ترسیم شده رد شود. قابل خواندن/نوشتن long.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public abstract boolean isAutomaticTickLabelSpacing()
```

مشخص می‌کند مقدار فاصله خودکار برچسب تیک. اگر false باشد: از ویژگی TickLabelSpacing استفاده می‌شود. قابل خواندن/نوشتن boolean.

**بازگشت:**
boolean

### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public abstract void setAutomaticTickLabelSpacing(boolean value)
```

مشخص می‌کند مقدار فاصله خودکار برچسب تیک. اگر false باشد: از ویژگی TickLabelSpacing استفاده می‌شود. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public abstract long getTickMarksSpacing()
```

مشخص می‌کند چند علامت تیک باید قبل از علامت بعدی رد شود. اعمال به محور دسته یا سری. قابل خواندن/نوشتن int.

**بازگشت:**
long

### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```

مشخص می‌کند چند علامت تیک باید قبل از علامت بعدی رد شود. اعمال به محور دسته یا سری. قابل خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public abstract boolean isAutomaticTickMarksSpacing()
```

مشخص می‌کند مقدار فاصله خودکار علامت‌های تیک. اگر false باشد: از ویژگی TickMarksSpacing استفاده می‌شود. قابل خواندن/نوشتن boolean.

**بازگشت:**
boolean

### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public abstract void setAutomaticTickMarksSpacing(boolean value)
```

مشخص می‌کند مقدار فاصله خودکار علامت‌های تیک. اگر false باشد: از ویژگی TickMarksSpacing استفاده می‌شود. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public abstract int getLabelOffset()
```

مشخص می‌کند فاصله برچسب‌ها از محور چقدر است. اعمال به محور دسته یا تاریخ. مقدار باید بین 0% و 1000% باشد. قابل خواندن/نوشتن int.

**بازگشت:**
int

### setLabelOffset(int value) {#setLabelOffset-int-}
```
public abstract void setLabelOffset(int value)
```

مشخص می‌کند فاصله برچسب‌ها از محور چقدر است. اعمال به محور دسته یا تاریخ. مقدار باید بین 0% و 1000% باشد. قابل خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public abstract int getCategoryAxisType()
```

مشخص می‌کند نوع محور دسته چیست. قابل خواندن/نوشتن [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**بازگشت:**
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public abstract void setCategoryAxisType(int value)
```

مشخص می‌کند نوع محور دسته چیست. قابل خواندن/نوشتن [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public abstract void setCategoryAxisTypeAutomatically()
```

خصیصه IAxis.CategoryAxisType را با مقداری که به‌صورت خودکار بر اساس داده‌های محور تعیین می‌شود تنظیم می‌کند.

### getAggregationType() {#getAggregationType--}
```
public abstract int getAggregationType()
```

نمایش نوع تجمیع محور دسته (باینینگ). اعمال به دسته. فقط برای سری‌های Histogram یا HistogramPareto استفاده می‌شود.

**بازگشت:**
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```

نمایش نوع تجمیع محور دسته (باینینگ). اعمال به دسته. فقط برای سری‌های Histogram یا HistogramPareto استفاده می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```

مشخص می‌کند عرض باین زمانی که مقدار ویژگی AggregationType بر روی AxisAggregationType.ByBinWidth تنظیم شده است، چه باشد. برای محورهای دسته‌ای اعمال می‌شود. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود.

**بازگشت:**
double
### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```

مشخص می‌کند عرض باین زمانی که مقدار ویژگی AggregationType بر روی AxisAggregationType.ByBinWidth تنظیم شده است، چه باشد. برای محورهای دسته‌ای اعمال می‌شود. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```

مشخص می‌کند تعداد باین‌ها زمانی که مقدار ویژگی AggregationType بر روی AxisAggregationType.ByNumberOfBins تنظیم شده است، چه باشد. برای محورهای دسته‌ای اعمال می‌شود. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود.

**بازگشت:**
long
### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public abstract void setNumberOfBins(long value)
```

مشخص می‌کند تعداد باین‌ها زمانی که مقدار ویژگی AggregationType بر روی AxisAggregationType.ByNumberOfBins تنظیم شده است، چه باشد. برای محورهای دسته‌ای اعمال می‌شود. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```

مشخص می‌کند آیا باین سرریز اعمال می‌شود یا خیر. برای تنظیم مقدار باین سرریز از IsAutomaticOverflowBin و OverflowBin استفاده کنید.

**بازگشت:**
boolean
### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public abstract void setOverflowBin(boolean value)
```

مشخص می‌کند آیا باین سرریز اعمال می‌شود یا خیر. برای تنظیم مقدار باین سرریز از IsAutomaticOverflowBin و OverflowBin استفاده کنید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public abstract boolean isAutomaticOverflowBin()
```

مقدار خودکار باین سرریز را مشخص می‌کند. اگر مقدار false باشد: از ویژگی OverflowBin استفاده کنید.

**بازگشت:**
boolean
### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public abstract void setAutomaticOverflowBin(boolean value)
```

مقدار خودکار باین سرریز را مشخص می‌کند. اگر مقدار false باشد: از ویژگی OverflowBin استفاده کنید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public abstract double getOverflowBin()
```

مقدار سفارشی باین سرریز را مشخص می‌کند. زمانی که ویژگی IsAutomaticOverflowBin بر روی false تنظیم شده باشد و ویژگی IsOverflowBin برابر true باشد، اعمال می‌شود.

**بازگشت:**
double
### setOverflowBin(double value) {#setOverflowBin-double-}
```
public abstract void setOverflowBin(double value)
```

مقدار سفارشی باین سرریز را مشخص می‌کند. زمانی که ویژگی IsAutomaticOverflowBin بر روی false تنظیم شده باشد و ویژگی IsOverflowBin برابر true باشد، اعمال می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public abstract boolean isUnderflowBin()
```

مشخص می‌کند آیا باین زیرریز اعمال می‌شود یا خیر. برای تنظیم مقدار باین زیرریز از IsAutomaticUnderflowBin و UnderflowBin استفاده کنید.

**بازگشت:**
boolean
### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```

مشخص می‌کند آیا باین زیرریز اعمال می‌شود یا خیر. برای تنظیم مقدار باین زیرریز از IsAutomaticUnderflowBin و UnderflowBin استفاده کنید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public abstract boolean isAutomaticUnderflowBin()
```

مقدار خودکار باین زیرریز را مشخص می‌کند. اگر مقدار false باشد: از ویژگی UnderflowBin استفاده کنید.

**بازگشت:**
boolean
### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public abstract void setAutomaticUnderflowBin(boolean value)
```

مقدار خودکار باین زیرریز را مشخص می‌کند. اگر مقدار false باشد: از ویژگی UnderflowBin استفاده کنید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public abstract double getUnderflowBin()
```

مقدار سفارشی باین زیرریز را مشخص می‌کند. زمانی که ویژگی IsAutomaticUnderflowBin بر روی false تنظیم شده باشد و ویژگی IsUnderflowBin برابر true باشد، اعمال می‌شود.

**بازگشت:**
double
### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```

مقدار سفارشی باین زیرریز را مشخص می‌کند. زمانی که ویژگی IsAutomaticUnderflowBin بر روی false تنظیم شده باشد و ویژگی IsUnderflowBin برابر true باشد، اعمال می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |