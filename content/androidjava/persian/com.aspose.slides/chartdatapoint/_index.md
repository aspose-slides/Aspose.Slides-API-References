---
title: ChartDataPoint
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایانگر نقطه دادهٔ سری.
type: docs
url: /fa/com.aspose.slides/chartdatapoint/
---
**ارث‌بری:**  
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IChartDataPoint](../../com.aspose.slides/ichartdatapoint), com.aspose.slides.IDOMObject  
```
public class ChartDataPoint implements IChartDataPoint, IDOMObject
```

نمایانگر نقطه دادهٔ سری.

## متدها

| متد | توضیح |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | مقدار اندازهٔ نقطه دادهٔ نمودار را بر می‌گرداند. |
| [getColorValue()](#getColorValue--) | مقدار رنگ نقطه دادهٔ نمودار را بر می‌گرداند. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | مقادیر نوارهای خطای سری را در صورت نوع مقدار سفارشی نشان می‌دهد. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | مشخص می‌کند که حباب‌ها اثر سه‌بعدی دارند. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | مشخص می‌کند که حباب‌ها اثر سه‌بعدی دارند. |
| [getExplosion()](#getExplosion--) | مقداری که نقطه داده باید از مرکز دایره‌کیک جابجا شود را مشخص می‌کند. |
| [setExplosion(int value)](#setExplosion-int-) | مقداری که نقطه داده باید از مرکز دایره‌کیک جابجا شود را مشخص می‌کند. |
| [getFormat()](#getFormat--) | ویژگی‌های قالب‌بندی را نشان می‌دهد. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | ویژگی‌های قالب‌بندی را نشان می‌دهد. |
| [getMarker()](#getMarker--) | یک علامت داده‌ای را مشخص می‌کند. |
| [getSetAsTotal()](#getSetAsTotal--) | نقطه داده را به‌عنوان مجموع تنظیم می‌کند. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | نقطه داده را به‌عنوان مجموع تنظیم می‌کند. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | ویژگی‌های ورودی مربوط به ورودی افسانه در مورد نوع نمودار از این فهرست: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | DataPoint را از سری نمودار حذف می‌کند. |
| [getDataPointLevels()](#getDataPointLevels--) | محفظهٔ سطوح نقطه داده را بر می‌گرداند. |
| [getIndex()](#getIndex--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | یک رنگ خودکار برای نقطه داده بر اساس شاخص سری، شاخص نقطه داده، ویژگی ParentSeriesGroup.IsColorVaried و سبک نمودار بر می‌گرداند. |
| [getInvertIfNegative()](#getInvertIfNegative--) | مشخص می‌کند که نقطه داده در صورت منفی بودن مقدار، رنگ‌های خود را معکوس می‌کند. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | مشخص می‌کند که نقطه داده در صورت منفی بودن مقدار، رنگ‌های خود را معکوس می‌کند. |
| [getActualX()](#getActualX--) | موقعیت واقعی x (چپ) عنصر نمودار را نسبت به گوشهٔ چپ-بالای نمودار مشخص می‌کند. |
| [getActualY()](#getActualY--) | بالای واقعی عنصر نمودار را نسبت به گوشهٔ چپ-بالای نمودار مشخص می‌کند. |
| [getActualWidth()](#getActualWidth--) | عرض واقعی عنصر نمودار را مشخص می‌کند. |
| [getActualHeight()](#getActualHeight--) | ارتفاع واقعی عنصر نمودار را مشخص می‌کند. |

### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```

XValue. فقط-خواندنی [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**بر می‌گرداند:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)

### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```

YValue. فقط-خواندنی [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**بر می‌گرداند:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```

BubbleSize. فقط-خواندنی [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**بر می‌گرداند:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```

Value. فقط-خواندنی [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**بر می‌گرداند:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```

مقدار اندازهٔ نقطه دادهٔ نمودار را بر می‌گرداند. در نمودارهای Treemap و Sunburst استفاده می‌شود. فقط-خواندنی [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**بر می‌گرداند:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```

مقدار رنگ نقطه دادهٔ نمودار را بر می‌گرداند. در نمودارهای Map استفاده می‌شود. فقط-خواندنی [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**بر می‌گرداند:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```

مقادیر نوارهای خطای سری را در صورت نوع مقدار سفارشی نشان می‌دهد. فقط-خواندنی [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**بر می‌گرداند:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)

### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```

Label. فقط-خواندنی [IDataLabel](../../com.aspose.slides/idatalabel).

**بر می‌گرداند:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```

مشخص می‌کند که حباب‌ها اثر سه‌بعدی دارند. قابل‌خواندن/نوشتن boolean.

**بر می‌گرداند:**
boolean

### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```

مشخص می‌کند که حباب‌ها اثر سه‌بعدی دارند. قابل‌خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

مقداری که نقطه داده باید از مرکز دایره‌کیک جابجا شود را مشخص می‌کند. قابل‌خواندن/نوشتن int.

**بر می‌گرداند:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

مقداری که نقطه داده باید از مرکز دایره‌کیک جابجا شود را مشخص می‌کند. قابل‌خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

ویژگی‌های قالب‌بندی را نشان می‌دهد. قابل‌خواندن/نوشتن [IFormat](../../com.aspose.slides/iformat).

**بر می‌گرداند:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

ویژگی‌های قالب‌بندی را نشان می‌دهد. قابل‌خواندن/نوشتن [IFormat](../../com.aspose.slides/iformat).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

یک علامت داده‌ای را مشخص می‌کند. فقط-خواندنی [IMarker](../../com.aspose.slides/imarker).

**بر می‌گرداند:**
[IMarker](../../com.aspose.slides/imarker)

### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```

نقطه داده را به‌عنوان مجموع تنظیم می‌کند. فقط برای نوع سری Waterfall اعمال می‌شود.

**بر می‌گرداند:**
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```

نقطه داده را به‌عنوان مجموع تنظیم می‌کند. فقط برای نوع سری Waterfall اعمال می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

ویژگی‌های ورودی مربوط به ورودی افسانه در مورد نوع نمودار از این فهرست: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. فقط-خواندنی [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**بر می‌گرداند:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### remove() {#remove--}
```
public final void remove()
```

DataPoint را از سری نمودار حذف می‌کند.

### getDataPointLevels() {#getDataPointLevels--}
```
public final IChartDataPointLevelsManager getDataPointLevels()
```

محفظهٔ سطوح نقطه داده را بر می‌گرداند. برای سری‌های Treeamp و Sunburst اعمال می‌شود. ایندکس‌گذاری سطوح نقطه داده از صفر شروع می‌شود.

**بر می‌گرداند:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)

### getIndex() {#getIndex--}
```
public final long getIndex()
```


**بر می‌گرداند:**
long

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شی Parent_Immediate را بر می‌گرداند. فقط-خواندنی IDOMObject.

**بر می‌گرداند:**
com.aspose.slides.IDOMObject

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Integer getAutomaticDataPointColor()
```

یک رنگ خودکار برای نقطه داده بر اساس شاخص سری، شاخص نقطه داده، ویژگی ParentSeriesGroup.IsColorVaried و سبک نمودار بر می‌گرداند. این رنگ به‌طور پیش‌فرض استفاده می‌شود اگر FillType برابر NotDefined باشد.

**بر می‌گرداند:**
java.lang.Integer

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

مشخص می‌کند که نقطه داده در صورت منفی بودن مقدار، رنگ‌های خود را معکوس می‌کند. قابل‌خواندن/نوشتن boolean.

**بر می‌گرداند:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

مشخص می‌کند که نقطه داده در صورت منفی بودن مقدار، رنگ‌های خود را معکوس می‌کند. قابل‌خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

موقعیت واقعی x (چپ) عنصر نمودار را نسبت به گوشهٔ چپ-بالای نمودار مشخص می‌کند. قبل از دریافت مقادیر واقعی، متد IChart.ValidateChartLayout() را فراخوانی کنید. فقط-خواندنی float.

**بر می‌گرداند:**
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

موقعیت واقعی y (بالا) عنصر نمودار را نسبت به گوشهٔ چپ-بالای نمودار مشخص می‌کند. قبل از دریافت مقادیر واقعی، متد IChart.ValidateChartLayout() را فراخوانی کنید. فقط-خواندنی float.

**بر می‌گرداند:**
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

عرض واقعی عنصر نمودار را مشخص می‌کند. قبل از دریافت مقادیر واقعی، متد IChart.ValidateChartLayout() را فراخوانی کنید. فقط-خواندنی float.

**بر می‌گرداند:**
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

ارتفاع واقعی عنصر نمودار را مشخص می‌کند. قبل از دریافت مقادیر واقعی، متد IChart.ValidateChartLayout() را فراخوانی کنید. فقط-خواندنی float.

**بر می‌گرداند:**
float