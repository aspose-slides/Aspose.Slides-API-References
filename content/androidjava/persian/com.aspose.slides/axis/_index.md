---
title: Axis
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: شیئی را که محور نمودارها را نشان می‌دهد، در بر می‌گیرد.
type: docs
url: /fa/com.aspose.slides/axis/
---
**Inheritance:** ارث‌بری: java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:** همه رابط‌های پیاده‌سازی‌شده: [com.aspose.slides.IAxis](../../com.aspose.slides/iaxis) ```
public class Axis extends DomObject<AxesManager> implements IAxis
```

Encapsulates the object that represents a chart's axis. شیئی را که محور نمودار را نشان می‌دهد، در بر می‌گیرد.

## متدها

| متد | توضیح |
| --- | --- |
| [getChart()](#getChart--) | نمودار والد را بازمی‌گرداند. |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | نشان می‌دهد که آیا محور مقدار محور دسته‌بندی را بین دسته‌ها قطع می‌کند. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | نشان می‌دهد که آیا محور مقدار محور دسته‌بندی را بین دسته‌ها قطع می‌کند. |
| [getCategoryAxisType()](#getCategoryAxisType--) | نوع محور دسته‌بندی را مشخص می‌کند. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | نوع محور دسته‌بندی را مشخص می‌کند. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | ویژگی IAxis.CategoryAxisType را با مقداری که به‌صورت خودکار بر اساس داده‌های محور تعیین می‌شود، تنظیم می‌کند. |
| [getCrossAt()](#getCrossAt--) | نقطه‌ای روی محور که محور عمودی آن را قطع می‌کند، را نشان می‌دهد. |
| [setCrossAt(float value)](#setCrossAt-float-) | نقطه‌ای روی محور که محور عمودی آن را قطع می‌کند، را نشان می‌دهد. |
| [getDisplayUnit()](#getDisplayUnit--) | مقدار مقیاس واحدهای نمایش برای محور مقدار را مشخص می‌کند. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | مقدار مقیاس واحدهای نمایش برای محور مقدار را مشخص می‌کند. |
| [getActualMaxValue()](#getActualMaxValue--) | حداکثر مقدار واقعی روی محور را مشخص می‌کند. |
| [getActualMinValue()](#getActualMinValue--) | حداقل مقدار واقعی روی محور را مشخص می‌کند. |
| [getActualMajorUnit()](#getActualMajorUnit--) | واحد اصلی واقعی محور را مشخص می‌کند. |
| [getActualMinorUnit()](#getActualMinorUnit--) | واحد فرعی واقعی محور را مشخص می‌کند. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | مقیاس واحد اصلی واقعی محور را مشخص می‌کند. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | مقیاس واحد فرعی واقعی محور را مشخص می‌کند. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | نشان می‌دهد که آیا مقدار حداکثر به‌صورت خودکار اختصاص داده می‌شود. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | نشان می‌دهد که آیا مقدار حداکثر به‌صورت خودکار اختصاص داده می‌شود. |
| [getMaxValue()](#getMaxValue--) | حداکثر مقدار روی محور مقدار را نشان می‌دهد. |
| [setMaxValue(double value)](#setMaxValue-double-) | حداکثر مقدار روی محور مقدار را نشان می‌دهد. |
| [getMinorUnit()](#getMinorUnit--) | واحدهای جزئی برای محور تاریخ یا مقدار را نشان می‌دهد. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | واحدهای جزئی برای محور تاریخ یا مقدار را نشان می‌دهد. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | نشان می‌دهد که آیا واحد فرعی محور به‌صورت خودکار اختصاص داده می‌شود. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | نشان می‌دهد که آیا واحد فرعی محور به‌صورت خودکار اختصاص داده می‌شود. |
| [getMajorUnit()](#getMajorUnit--) | واحدهای اصلی برای محور تاریخ یا مقدار را نشان می‌دهد. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | واحدهای اصلی برای محور تاریخ یا مقدار را نشان می‌دهد. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | نشان می‌دهد که آیا واحد اصلی محور به‌صورت خودکار اختصاص داده می‌شود. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | نشان می‌دهد که آیا واحد اصلی محور به‌صورت خودکار اختصاص داده می‌شود. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | نشان می‌دهد که آیا مقدار حداقل به‌صورت خودکار اختصاص داده می‌شود. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | نشان می‌دهد که آیا مقدار حداقل به‌صورت خودکار اختصاص داده می‌شود. |
| [getMinValue()](#getMinValue--) | حداقل مقدار روی محور مقدار را نشان می‌دهد. |
| [setMinValue(double value)](#setMinValue-double-) | حداقل مقدار روی محور مقدار را نشان می‌دهد. |
| [isLogarithmic()](#isLogarithmic--) | نشان می‌دهد که آیا نوع مقیاس محور مقدار لگاریتمی است یا نه. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | نشان می‌دهد که آیا نوع مقیاس محور مقدار لگاریتمی است یا نه. |
| [getLogBase()](#getLogBase--) | پایه لگاریتمی را نشان می‌دهد. |
| [setLogBase(double value)](#setLogBase-double-) | پایه لگاریتمی را نشان می‌دهد. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | نشان می‌دهد که آیا PowerPoint داده‌ها را از آخر به اولین رسم می‌کند. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | نشان می‌دهد که آیا PowerPoint داده‌ها را از آخر به اولین رسم می‌کند. |
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
| [getBaseUnitScale()](#getBaseUnitScale--) | کوچک‌ترین واحد زمانی که روی محور تاریخ نمایان می‌شود را مشخص می‌کند. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | کوچک‌ترین واحد زمانی که روی محور تاریخ نمایان می‌شود را مشخص می‌کند. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | قالب خطوط شبکه جزئی روی محور نمودار را نشان می‌دهد. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | قالب خطوط شبکه اصلی روی محور نمودار را نشان می‌دهد. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | برای پنهان کردن خطوط شبکه جزئی، ویژگی MinorGridLinesFormat.Line.FillFormat.FillType را به FillType.NoFill تنظیم کنید. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | برای پنهان کردن خطوط شبکه اصلی، ویژگی MajorGridLinesFormat.Line.FillFormat.FillType را به FillType.NoFill تنظیم کنید. |
| [getFormat()](#getFormat--) | قالب محور را نشان می‌دهد. |
| [getTextFormat()](#getTextFormat--) | قالب متن را نشان می‌دهد. |
| [getTitle()](#getTitle--) | عنوان محور را دریافت می‌کند. |
| [getCrossType()](#getCrossType--) | نوع CrossType بر روی محور مشخص‌شده که محور دیگر آن را قطع می‌کند را نشان می‌دهد. |
| [setCrossType(int value)](#setCrossType-int-) | نوع CrossType بر روی محور مشخص‌شده که محور دیگر آن را قطع می‌کند را نشان می‌دهد. |
| [getPosition()](#getPosition--) | موقعیت محور را نشان می‌دهد. |
| [setPosition(int value)](#setPosition-int-) | موقعیت محور را نشان می‌دهد. |
| [hasTitle()](#hasTitle--) | تعیین می‌کند که آیا محور عنوان قابل مشاهده‌ای دارد یا نه. |
| [setTitle(boolean value)](#setTitle-boolean-) | تعیین می‌کند که آیا محور عنوان قابل مشاهده‌ای دارد یا نه. |
| [getNumberFormat()](#getNumberFormat--) | رشته قالب برای برچسب‌های محور را نشان می‌دهد. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | رشته قالب برای برچسب‌های محور را نشان می‌دهد. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | نشان می‌دهد که آیا قالب به داده منبع لینک شده است. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | نشان می‌دهد که آیا قالب به داده منبع لینک شده است. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | زاویه چرخش برچسب‌های علامت‌گذاری را نشان می‌دهد. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | زاویه چرخش برچسب‌های علامت‌گذاری را نشان می‌دهد. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | تعداد برچسب‌های علامت‌گذاری که بین دو برچسب رسم‌شده عبور می‌کند را مشخص می‌کند. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | تعداد برچسب‌های علامت‌گذاری که بین دو برچسب رسم‌شده عبور می‌کند را مشخص می‌کند. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | مقدار فاصله خودکار برچسب‌های علامت‌گذاری را مشخص می‌کند. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | مقدار فاصله خودکار برچسب‌های علامت‌گذاری را مشخص می‌کند. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | تعداد علامت‌گذاری‌هایی که قبل از علامت بعدی باید عبور شوند را مشخص می‌کند. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | تعداد علامت‌گذاری‌هایی که قبل از علامت بعدی باید عبور شوند را مشخص می‌کند. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | مقدار فاصله خودکار علامت‌گذاری‌ها را مشخص می‌کند. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | مقدار فاصله خودکار علامت‌گذاری‌ها را مشخص می‌کند. |
| [getLabelOffset()](#getLabelOffset--) | فاصله برچسب‌ها از محور را مشخص می‌کند. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | فاصله برچسب‌ها از محور را مشخص می‌کند. |
| [getAggregationType()](#getAggregationType--) | نوع تجمیع محور دسته‌بندی (بینیگ) را نشان می‌دهد. |
| [setAggregationType(int value)](#setAggregationType-int-) | نوع تجمیع محور دسته‌بندی (بینیگ) را نشان می‌دهد. |
| [getBinWidth()](#getBinWidth--) | عرض بین هنگامی که مقدار ویژگی AggregationType برابر AxisAggregationType.ByBinWidth تنظیم شده باشد، را مشخص می‌کند. |
| [setBinWidth(double value)](#setBinWidth-double-) | عرض بین هنگامی که مقدار ویژگی AggregationType برابر AxisAggregationType.ByBinWidth تنظیم شده باشد، را مشخص می‌کند. |
| [getNumberOfBins()](#getNumberOfBins--) | تعداد بین‌ها هنگامی که مقدار ویژگی AggregationType برابر AxisAggregationType.ByNumberOfBins تنظیم شده باشد، را مشخص می‌کند. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | تعداد بین‌ها هنگامی که مقدار ویژگی AggregationType برابر AxisAggregationType.ByNumberOfBins تنظیم شده باشد، را مشخص می‌کند. |
| [isOverflowBin()](#isOverflowBin--) | نشان می‌دهد که آیا بین اضافه‌بار اعمال شده است. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | نشان می‌دهد که آیا بین اضافه‌بار اعمال شده است. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | مقدار خودکار بین اضافه‌بار را مشخص می‌کند. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | مقدار خودکار بین اضافه‌بار را مشخص می‌کند. |
| [getOverflowBin()](#getOverflowBin--) | مقدار سفارشی بین اضافه‌بار را مشخص می‌کند. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | مقدار سفارشی بین اضافه‌بار را مشخص می‌کند. |
| [isUnderflowBin()](#isUnderflowBin--) | نشان می‌دهد که آیا بین کمبود اعمال شده است. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | نشان می‌دهد که آیا بین کمبود اعمال شده است. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | مقدار خودکار بین کمبود را مشخص می‌کند. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | مقدار خودکار بین کمبود را مشخص می‌کند. |
| [getUnderflowBin()](#getUnderflowBin--) | مقدار سفارشی بین کمبود را مشخص می‌کند. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | مقدار سفارشی بین کمبود را مشخص می‌کند. |
| [getSlide()](#getSlide--) | اسلاید والد یک FillFormat را بازمی‌گرداند. |
| [getPresentation()](#getPresentation--) | ارائه (presentation) والد یک FillFormat را بازمی‌گرداند. |

### getChart() {#getChart--}
```
public final IChart getChart()
```

نمودار والد را بازمی‌گرداند. فقط خواندنی [IChart](../../com.aspose.slides/ichart).

**Returns:**  
[IChart](../../com.aspose.slides/ichart)

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public final boolean getAxisBetweenCategories()
```

نشان می‌دهد که آیا محور مقدار محور دسته‌بندی را بین دسته‌ها قطع می‌کند. این ویژگی فقط برای محورهای دسته‌بندی اعمال می‌شود و در نمودارهای سه‌بعدی کاربرد ندارد. قابل خواندن/نوشتن boolean.

**Returns:**  
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public final void setAxisBetweenCategories(boolean value)
```

نشان می‌دهد که آیا محور مقدار محور دسته‌بندی را بین دسته‌ها قطع می‌کند. این ویژگی فقط برای محورهای دسته‌بندی اعمال می‌شود و در نمودارهای سه‌بعدی کاربرد ندارد. قابل خواندن/نوشتن boolean.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public final int getCategoryAxisType()
```

نوع محور دسته‌بندی را مشخص می‌کند. قابل خواندن/نوشتن [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Returns:**  
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public final void setCategoryAxisType(int value)
```

نوع محور دسته‌بندی را مشخص می‌کند. قابل خواندن/نوشتن [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public final void setCategoryAxisTypeAutomatically()
```

ویژگی IAxis.CategoryAxisType را با مقداری که به‌صورت خودکار بر اساس داده‌های محور تعیین می‌شود، تنظیم می‌کند.

### getCrossAt() {#getCrossAt--}
```
public final float getCrossAt()
```

نقطه‌ای روی محور که محور عمودی آن را قطع می‌کند، را نشان می‌دهد. قابل خواندن/نوشتن float.

**Returns:**  
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public final void setCrossAt(float value)
```

نقطه‌ای روی محور که محور عمودی آن را قطع می‌کند، را نشان می‌دهد. قابل خواندن/نوشتن float.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public final int getDisplayUnit()
```

مقدار مقیاس واحدهای نمایش برای محور مقدار را مشخص می‌کند. قابل خواندن/نوشتن [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Returns:**  
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public final void setDisplayUnit(int value)
```

مقدار مقیاس واحدهای نمایش برای محور مقدار را مشخص می‌کند. قابل خواندن/نوشتن [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public final double getActualMaxValue()
```

حداکثر مقدار واقعی روی محور را مشخص می‌کند. برای دریافت مقدار واقعی پیش از این، متد IChart.ValidateChartLayout() را فراخوانی کنید.

**Returns:**  
double

### getActualMinValue() {#getActualMinValue--}
```
public final double getActualMinValue()
```

حداقل مقدار واقعی روی محور را مشخص می‌کند. برای دریافت مقدار واقعی پیش از این، متد IChart.ValidateChartLayout() را فراخوانی کنید.

**Returns:**  
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public final double getActualMajorUnit()
```

واحد اصلی واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی پیش از این، متد IChart.ValidateChartLayout() را فراخوانی کنید.

**Returns:**  
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public final double getActualMinorUnit()
```

واحد فرعی واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی پیش از این، متد IChart.ValidateChartLayout() را فراخوانی کنید.

**Returns:**  
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public final int getActualMajorUnitScale()
```

مقیاس واحد اصلی واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی پیش از این، متد IChart.ValidateChartLayout() را فراخوانی کنید.

**Returns:**  
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public final int getActualMinorUnitScale()
```

مقیاس واحد فرعی واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی پیش از این، متد IChart.ValidateChartLayout() را فراخوانی کنید.

**Returns:**  
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public final boolean isAutomaticMaxValue()
```

نشان می‌دهد که آیا مقدار حداکثر به‌صورت خودکار اختصاص داده می‌شود. قابل خواندن/نوشتن boolean.

**Returns:**  
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public final void setAutomaticMaxValue(boolean value)
```

نشان می‌دهد که آیا مقدار حداکثر به‌صورت خودکار اختصاص داده می‌شود. قابل خواندن/نوشتن boolean.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public final double getMaxValue()
```

حداکثر مقدار روی محور مقدار را نشان می‌دهد. قابل خواندن/نوشتن double.

**Returns:**  
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public final void setMaxValue(double value)
```

حداکثر مقدار روی محور مقدار را نشان می‌دهد. قابل خواندن/نوشتن double.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public final double getMinorUnit()
```

واحدهای جزئی برای محور تاریخ یا مقدار را نشان می‌دهد. قابل خواندن/نوشتن double.

**Returns:**  
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public final void setMinorUnit(double value)
```

واحدهای جزئی برای محور تاریخ یا مقدار را نشان می‌دهد. قابل خواندن/نوشتن double.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public final boolean isAutomaticMinorUnit()
```

نشان می‌دهد که آیا واحد فرعی محور به‌صورت خودکار اختصاص داده می‌شود. قابل خواندن/نوشتن boolean.

**Returns:**  
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public final void setAutomaticMinorUnit(boolean value)
```

نشان می‌دهد که آیا واحد فرعی محور به‌صورت خودکار اختصاص داده می‌شود. قابل خواندن/نوشتن boolean.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public final double getMajorUnit()
```

واحدهای اصلی برای محور تاریخ یا مقدار را نشان می‌دهد. قابل خواندن/نوشتن double.

**Returns:**  
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public final void setMajorUnit(double value)
```

واحدهای اصلی برای محور تاریخ یا مقدار را نشان می‌دهد. قابل خواندن/نوشتن double.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public final boolean isAutomaticMajorUnit()
```

نشان می‌دهد که آیا واحد اصلی محور به‌صورت خودکار اختصاص داده می‌شود. قابل خواندن/نوشتن boolean.

**Returns:**  
boolean

### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public final void setAutomaticMajorUnit(boolean value)
```

نشان می‌دهد که آیا واحد اصلی محور به‌صورت خودکار اختصاص داده می‌شود. قابل خواندن/نوشتن boolean.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public final boolean isAutomaticMinValue()
```

نشان می‌دهد که آیا مقدار حداقل به‌صورت خودکار اختصاص داده می‌شود. قابل خواندن/نوشتن boolean.

**Returns:**  
boolean

### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public final void setAutomaticMinValue(boolean value)
```

نشان می‌دهد که آیا مقدار حداقل به‌صورت خودکار اختصاص داده می‌شود. قابل خواندن/نوشتن boolean.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public final double getMinValue()
```

حداقل مقدار روی محور مقدار را نشان می‌دهد. قابل خواندن/نوشتن double.

**Returns:**  
double

### setMinValue(double value) {#setMinValue-double-}
```
public final void setMinValue(double value)
```

حداقل مقدار روی محور مقدار را نشان می‌دهد. قابل خواندن/نوشتن double.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public final boolean isLogarithmic()
```

نشان می‌دهد که آیا نوع مقیاس محور مقدار لگاریتمی است یا نه. قابل خواندن/نوشتن boolean.

**Returns:**  
boolean

### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public final void setLogarithmic(boolean value)
```

نشان می‌دهد که آیا نوع مقیاس محور مقدار لگاریتمی است یا نه. قابل خواندن/نوشتن boolean.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public final double getLogBase()
```

پایه لگاریتمی را نشان می‌دهد. مقدار پیش‌فرض 10 است. قابل خواندن/نوشتن double.

**Returns:**  
double

### setLogBase(double value) {#setLogBase-double-}
```
public final void setLogBase(double value)
```

پایه لگاریتمی را نشان می‌دهد. مقدار پیش‌فرض 10 است. قابل خواندن/نوشتن double.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public final boolean isPlotOrderReversed()
```

نشان می‌دهد که آیا PowerPoint داده‌ها را از آخر به اولین رسم می‌کند. قابل خواندن/نوشتن boolean.

**Returns:**  
boolean

### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public  



```

نشان می‌دهد که آیا PowerPoint داده‌ها را از آخر به اولین رسم می‌کند. قابل خواندن/نوشتن boolean.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

نشان می‌دهد که آیا محور قابل مشاهده است. قابل خواندن/نوشتن boolean.

**Returns:**  
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

نشان می‌دهد که آیا محور قابل مشاهده است. قابل خواندن/نوشتن boolean.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public final int getMajorTickMark()
```

نوع علامت‌گذاری اصلی برای محور مشخص‌شده را نشان می‌دهد. قابل خواندن/نوشتن [TickMarkType](../../com.aspose.slides/tickmarktype).

**Returns:**  
int

### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public final void setMajorTickMark(int value)
```

نوع علامت‌گذاری اصلی برای محور مشخص‌شده را نشان می‌دهد. قابل خواندن/نوشتن [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public final int getMinorTickMark()
```

نوع علامت‌گذاری فرعی برای محور مشخص‌شده را نشان می‌دهد. قابل خواندن/نوشتن [TickMarkType](../../com.aspose.slides/tickmarktype).

**Returns:**  
int

### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public final void setMinorTickMark(int value)
```

نوع علامت‌گذاری فرعی برای محور مشخص‌شده را نشان می‌دهد. قابل خواندن/نوشتن [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public final int getTickLabelPosition()
```

موقعیت برچسب‌های علامت‌گذاری روی محور مشخص‌شده را نشان می‌دهد. قابل خواندن/نوشتن [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Returns:**  
int

### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public final void setTickLabelPosition(int value)
```

موقعیت برچسب‌های علامت‌گذاری روی محور مشخص‌شده را نشان می‌دهد. قابل خواندن/نوشتن [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public final int getMajorUnitScale()
```

مقیاس واحد اصلی برای محور تاریخ را نشان می‌دهد. قابل خواندن/نوشتن [TimeUnitType](../../com.aspose.slides/timeunittype).

**Returns:**  
int

### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public final void setMajorUnitScale(int value)
```

مقیاس واحد اصلی برای محور تاریخ را نشان می‌دهد. قابل خواندن/نوشتن [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public final int getMinorUnitScale()
```

مقیاس واحد اصلی برای محور تاریخ را نشان می‌دهد. قابل خواندن/نوشتن [TimeUnitType](../../com.aspose.slides/timeunittype).

**Returns:**  
int

### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public final void setMinorUnitScale(int value)
```

مقیاس واحد اصلی برای محور تاریخ را نشان می‌دهد. قابل خواندن/نوشتن [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public final int getBaseUnitScale()
```

کوچک‌ترین واحد زمانی که روی محور تاریخ نمایان می‌شود را مشخص می‌کند. قابل خواندن/نوشتن [TimeUnitType](../../com.aspose.slides/timeunittype).

**Returns:**  
int

### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public final void setBaseUnitScale(int value)
```

کوچک‌ترین واحد زمانی که روی محور تاریخ نمایان می‌شود را مشخص می‌کند. قابل خواندن/نوشتن [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```

قالب خطوط شبکه جزئی روی محور نمودار را نشان می‌دهد. فقط خواندنی [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Returns:**  
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public final IChartLinesFormat getMajorGridLinesFormat()
```

قالب خطوط شبکه اصلی روی محور نمودار را نشان می‌دهد. فقط خواندنی [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Returns:**  
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public final boolean getShowMinorGridLines()
```

برای پنهان کردن خطوط شبکه جزئی، ویژگی MinorGridLinesFormat.Line.FillFormat.FillType را به FillType.NoFill تنظیم کنید. فقط خواندنی boolean.

**Returns:**  
boolean

### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public final boolean getShowMajorGridLines()
```

برای پنهان کردن خطوط شبکه اصلی، ویژگی MajorGridLinesFormat.Line.FillFormat.FillType را به FillType.NoFill تنظیم کنید. فقط خواندنی boolean.

**Returns:**  
boolean

### getFormat() {#getFormat--}
```
public final IAxisFormat getFormat()
```

قالب محور را نشان می‌دهد. فقط خواندنی [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Returns:**  
[IAxisFormat](../../com.aspose.slides/iaxisformat)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

قالب متن را نشان می‌دهد. فقط خواندنی [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Returns:**  
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getTitle() {#getTitle--}
```
public final IChartTitle getTitle()
```

عنوان محور را دریافت می‌کند. فقط خواندنی [IChartTitle](../../com.aspose.slides/icharttitle).

**Returns:**  
[IChartTitle](../../com.aspose.slides/icharttitle)

### getCrossType() {#getCrossType--}
```
public final int getCrossType()
```

نوع CrossType بر روی محور مشخص‌شده که محور دیگر آن را قطع می‌کند را نشان می‌دهد. قابل خواندن/نوشتن [CrossesType](../../com.aspose.slides/crossestype).

**Returns:**  
int

### setCrossType(int value) {#setCrossType-int-}
```
public final void setCrossType(int value)
```

نوع CrossType بر روی محور مشخص‌شده که محور دیگر آن را قطع می‌کند را نشان می‌دهد. قابل خواندن/نوشتن [CrossesType](../../com.aspose.slides/crossestype).

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```

موقعیت محور را نشان می‌دهد. قابل خواندن/نوشتن [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Returns:**  
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

موقعیت محور را نشان می‌دهد. قابل خواندن/نوشتن [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

تعیین می‌کند که آیا محور عنوان قابل مشاهده‌ای دارد یا نه. قابل خواندن/نوشتن boolean.

**Returns:**  
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

تعیین می‌کند که آیا محور عنوان قابل مشاهده‌ای دارد یا نه. قابل خواندن/نوشتن boolean.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

رشته قالب برای برچسب‌های محور را نشان می‌دهد. قابل خواندن/نوشتن String.

**Returns:**  
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

رشته قالب برای برچسب‌های محور را نشان می‌دهد. قابل خواندن/نوشتن String.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

نشان می‌دهد که آیا قالب به داده منبع لینک شده است. قابل خواندن/نوشتن boolean.

**Returns:**  
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

نشان می‌دهد که آیا قالب به داده منبع لینک شده است. قابل خواندن/نوشتن boolean.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public final float getTickLabelRotationAngle()
```

زاویه چرخش برچسب‌های علامت‌گذاری را نشان می‌دهد. قابل خواندن/نوشتن float.

**Returns:**  
float

### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public final void setTickLabelRotationAngle(float value)
```

زاویه چرخش برچسب‌های علامت‌گذاری را نشان می‌دهد. قابل خواندن/نوشتن float.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public final long getTickLabelSpacing()
```

تعداد برچسب‌های علامت‌گذاری که بین دو برچسب رسم‌شده عبور می‌کند را مشخص می‌کند. برای محور دسته یا سری اعمال می‌شود. قابل خواندن/نوشتن long.

**Returns:**  
long

### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public final void setTickLabelSpacing(long value)
```

تعداد برچسب‌های علامت‌گذاری که بین دو برچسب رسم‌شده عبور می‌کند را مشخص می‌کند. برای محور دسته یا سری اعمال می‌شود. قابل خواندن/نوشتن long.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public final boolean isAutomaticTickLabelSpacing()
```

مقدار فاصله خودکار برچسب‌های علامت‌گذاری را مشخص می‌کند. اگر false باشد: از ویژگی TickLabelSpacing استفاده می‌شود. قابل خواندن/نوشتن boolean.

**Returns:**  
boolean

### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public final void setAutomaticTickLabelSpacing(boolean value)
```

مقدار فاصله خودکار برچسب‌های علامت‌گذاری را مشخص می‌کند. اگر false باشد: از ویژگی TickLabelSpacing استفاده می‌شود. قابل خواندن/نوشتن boolean.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public final long getTickMarksSpacing()
```

تعداد علامت‌گذاری‌هایی که قبل از علامت بعدی باید عبور شوند را مشخص می‌کند. برای محور دسته یا سری اعمال می‌شود. قابل خواندن/نوشتن int.

**Returns:**  
long

### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public final void setTickMarksSpacing(long value)
```

تعداد علامت‌گذاری‌هایی که قبل از علامت بعدی باید عبور شوند را مشخص می‌کند. برای محور دسته یا سری اعمال می‌شود. قابل خواندن/نوشتن int.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public final boolean isAutomaticTickMarksSpacing()
```

مقدار فاصله خودکار علامت‌گذاری‌ها را مشخص می‌کند. اگر false باشد: از ویژگی TickMarksSpacing استفاده می‌شود. قابل خواندن/نوشتن boolean.

**Returns:**  
boolean

### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public final void setAutomaticTickMarksSpacing(boolean value)
```

مقدار فاصله خودکار علامت‌گذاری‌ها را مشخص می‌کند. اگر false باشد: از ویژگی TickMarksSpacing استفاده می‌شود. قابل خواندن/نوشتن boolean.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public final int getLabelOffset()
```

فاصله برچسب‌ها از محور را مشخص می‌کند. برای محور دسته یا تاریخ اعمال می‌شود. مقدار باید بین 0% و 1000% باشد. قابل خواندن/نوشتن int.

**Returns:**  
int

### setLabelOffset(int value) {#setLabelOffset-int-}
```
public final void setLabelOffset(int value)
```

فاصله برچسب‌ها از محور را مشخص می‌کند. برای محور دسته یا تاریخ اعمال می‌شود. مقدار باید بین 0% و 1000% باشد. قابل خواندن/نوشتن int.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getAggregationType() {#getAggregationType--}
```
public final int getAggregationType()
```

نوع تجمیع محور دسته‌بندی (بینیگ) را نشان می‌دهد. برای محور دسته اعمال می‌شود. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود.

**Returns:**  
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public final void setAggregationType(int value)
```

نوع تجمیع محور دسته‌بندی (بینیگ) را نشان می‌دهد. برای محور دسته اعمال می‌شود. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public final double getBinWidth()
```

عرض بین هنگامی که مقدار ویژگی AggregationType برابر AxisAggregationType.ByBinWidth تنظیم شده باشد، را مشخص می‌کند. برای محورهای دسته اعمال می‌شود. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود.

**Returns:**  
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public final void setBinWidth(double value)
```

عرض بین هنگامی که مقدار ویژگی AggregationType برابر AxisAggregationType.ByBinWidth تنظیم شده باشد، را مشخص می‌کند. برای محورهای دسته اعمال می‌شود. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public final long getNumberOfBins()
```

تعداد بین‌ها هنگامی که مقدار ویژگی AggregationType برابر AxisAggregationType.ByNumberOfBins تنظیم شده باشد، را مشخص می‌کند. برای محورهای دسته اعمال می‌شود. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود.

**Returns:**  
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public final void setNumberOfBins(long value)
```

تعداد بین‌ها هنگامی که مقدار ویژگی AggregationType برابر AxisAggregationType.ByNumberOfBins تنظیم شده باشد، را مشخص می‌کند. برای محورهای دسته اعمال می‌شود. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public final boolean isOverflowBin()
```

نشان می‌دهد که آیا بین اضافه‌بار اعمال شده است. برای تنظیم مقدار بین اضافه‌بار از IsAutomaticOverflowBin و OverflowBin استفاده کنید.

**Returns:**  
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public final void setOverflowBin(boolean value)
```

نشان می‌دهد که آیا بین اضافه‌بار اعمال شده است. برای تنظیم مقدار بین اضافه‌بار از IsAutomaticOverflowBin و OverflowBin استفاده کنید.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public final boolean isAutomaticOverflowBin()
```

مقدار خودکار بین اضافه‌بار را مشخص می‌کند. اگر false باشد: از ویژگی OverflowBin استفاده می‌شود.

**Returns:**  
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public final void setAutomaticOverflowBin(boolean value)
```

مقدار خودکار بین اضافه‌بار را مشخص می‌کند. اگر false باشد: از ویژگی OverflowBin استفاده می‌شود.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public final double getOverflowBin()
```

مقدار سفارشی بین اضافه‌بار را مشخص می‌کند. هنگامی که ویژگی IsAutomaticOverflowBin برابر false باشد و IsOverflowBin برابر true باشد، اعمال می‌شود.

**Returns:**  
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public final void setOverflowBin(double value)
```

مقدار سفارشی بین اضافه‌بار را مشخص می‌کند. هنگامی که ویژگی IsAutomaticOverflowBin برابر false باشد و IsOverflowBin برابر true باشد، اعمال می‌شود.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public final boolean isUnderflowBin()
```

نشان می‌دهد که آیا بین کمبود اعمال شده است. برای تنظیم مقدار بین کمبود از IsAutomaticUnderflowBin و UnderflowBin استفاده کنید.

**Returns:**  
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public final void setUnderflowBin(boolean value)
```

نشان می‌دهد که آیا بین کمبود اعمال شده است. برای تنظیم مقدار بین کمبود از IsAutomaticUnderflowBin و UnderflowBin استفاده کنید.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public final boolean isAutomaticUnderflowBin()
```

مقدار خودکار بین کمبود را مشخص می‌کند. اگر false باشد: از ویژگی UnderflowBin استفاده می‌شود.

**Returns:**  
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public final void setAutomaticUnderflowBin(boolean value)
```

مقدار خودکار بین کمبود را مشخص می‌کند. اگر false باشد: از ویژگی UnderflowBin استفاده می‌شود.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public final double getUnderflowBin()
```

مقدار سفارشی بین کمبود را مشخص می‌کند. هنگامی که ویژگی IsAutomaticUnderflowBin برابر false باشد و IsUnderflowBin برابر true باشد، اعمال می‌شود.

**Returns:**  
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public final void setUnderflowBin(double value)
```

مقدار سفارشی بین کمبود را مشخص می‌کند. هنگامی که ویژگی IsAutomaticUnderflowBin برابر false باشد و IsUnderflowBin برابر true باشد، اعمال می‌شود.

**Parameters:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

اسلاید والد یک FillFormat را بازمی‌گرداند. فقط خواندنی [BaseSlide](../../com.aspose.slides/baseslide).

**Returns:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ارائه (presentation) والد یک FillFormat را بازمی‌گرداند. فقط خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**  
[IPresentation](../../com.aspose.slides/ipresentation)