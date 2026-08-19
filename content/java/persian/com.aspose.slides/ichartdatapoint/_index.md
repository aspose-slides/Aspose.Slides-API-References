---
title: IChartDataPoint
second_title: مرجع API Aspose.Slides برای Java
description: نماینده نقطه دادهٔ سری.
type: docs
url: /fa/com.aspose.slides/ichartdatapoint/
---
**همه رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

نماینده نقطه داده سری.
## متدها

| متد | توضیح |
| --- | --- |
| [getXValue()](#getXValue--) | مقدار x نقطه دادهٔ نمودار را برمی‌گرداند. |
| [getYValue()](#getYValue--) | مقدار y نقطه دادهٔ نمودار را برمی‌گرداند. |
| [getBubbleSize()](#getBubbleSize--) | اندازهٔ حباب نقطه دادهٔ نمودار را برمی‌گرداند. |
| [getValue()](#getValue--) | مقدار نقطه دادهٔ نمودار را برمی‌گرداند. |
| [getSizeValue()](#getSizeValue--) | مقدار اندازهٔ نقطه دادهٔ نمودار را برمی‌گرداند. |
| [getColorValue()](#getColorValue--) | مقدار رنگ نقطه دادهٔ نمودار را برمی‌گرداند. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | مقادیر نمودار خطای سری را در حالت نوع مقدار سفارشی نشان می‌دهد. |
| [getLabel()](#getLabel--) | برچسب نقطه دادهٔ نمودار را نشان می‌دهد. |
| [isBubble3D()](#isBubble3D--) | مشخص می‌کند که حباب‌ها اثر سه‌بعدی دارند. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | مشخص می‌کند که حباب‌ها اثر سه‌بعدی دارند. |
| [getExplosion()](#getExplosion--) | مقدار جابه‌جایی نقطه داده از مرکز کیک را مشخص می‌کند. |
| [setExplosion(int value)](#setExplosion-int-) | مقدار جابه‌جایی نقطه داده از مرکز کیک را مشخص می‌کند. |
| [getFormat()](#getFormat--) | ویژگی‌های قالب‌بندی را نشان می‌دهد. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | ویژگی‌های قالب‌بندی را نشان می‌دهد. |
| [getMarker()](#getMarker--) | یک نشانگر داده را مشخص می‌کند. |
| [remove()](#remove--) | نقطه داده را از سری نمودار حذف می‌کند. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | رنگ خودکار نقطه داده را بر اساس شاخص سری، شاخص نقطه داده، ویژگی ParentSeriesGroup.IsColorVaried و سبک نمودار برمی‌گرداند. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | ویژگی‌های ورودی افسانهٔ متناظر در صورت نوع نمودار از این فهرست: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | نقطه داده را به‌عنوان مجموع تنظیم می‌کند. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | نقطه داده را به‌عنوان مجموع تنظیم می‌کند. |
| [getInvertIfNegative()](#getInvertIfNegative--) | در صورت منفی بودن مقدار، رنگ‌های نقطه داده را معکوس می‌کند. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | در صورت منفی بودن مقدار، رنگ‌های نقطه داده را معکوس می‌کند. |
| [getDataPointLevels()](#getDataPointLevels--) | ظرف سطوح نقطه داده را برمی‌گرداند. |
| [getIndex()](#getIndex--) | تعیین می‌کند این نقطه داده به کدام مجموعهٔ فرزندان والد تعلق دارد. |

### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```

مقدار x نقطه دادهٔ نمودار را برمی‌گرداند. فقط خواندنی [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**بازگشت:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)

### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```

مقدار y نقطه دادهٔ نمودار را برمی‌گرداند. فقط خواندنی [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**بازگشت:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```

اندازهٔ حباب نقطه دادهٔ نمودار را برمی‌گرداند. فقط خواندنی [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**بازگشت:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```

مقدار نقطه دادهٔ نمودار را برمی‌گرداند. فقط خواندنی [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**بازگشت:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```

مقدار اندازهٔ نقطه دادهٔ نمودار را برمی‌گرداند. برای نمودارهای Treemap و Sunburst استفاده می‌شود. فقط خواندنی [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**بازگشت:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

مقدار رنگ نقطه دادهٔ نمودار را برمی‌گرداند. برای نمودارهای نقشه استفاده می‌شود. فقط خواندنی [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**بازگشت:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

مقادیری خطای سری را در حالت نوع مقدار سفارشی نشان می‌دهد. فقط خواندنی [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**بازگشت:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)

### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

برچسب نقطه دادهٔ نمودار را نشان می‌دهد. فقط خواندنی [IDataLabel](../../com.aspose.slides/idatalabel).

**بازگشت:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```

مشخص می‌کند که حباب‌ها اثر سه‌بعدی دارند. خواندنی/قابل نوشتن boolean.

**بازگشت:**
boolean

### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```

مشخص می‌کند که حباب‌ها اثر سه‌بعدی دارند. خواندنی/قابل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

مقداری که نقطه داده باید از مرکز کیک جابجا شود را مشخص می‌کند. خواندنی/قابل نوشتن int.

**بازگشت:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

مقداری که نقطه داده باید از مرکز کیک جابجا شود را مشخص می‌کند. خواندنی/قابل نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

ویژگی‌های قالب‌بندی را نشان می‌دهد. خواندنی/قابل نوشتن [IFormat](../../com.aspose.slides/iformat).

**بازگشت:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

ویژگی‌های قالب‌بندی را نشان می‌دهد. خواندنی/قابل نوشتن [IFormat](../../com.aspose.slides/iformat).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

یک نشانگر داده را مشخص می‌کند. فقط خواندنی [IMarker](../../com.aspose.slides/imarker).

**بازگشت:**
[IMarker](../../com.aspose.slides/imarker)

### remove() {#remove--}
```
public abstract void remove()
```

نقطه داده را از سری نمودار حذف می‌کند.

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Color getAutomaticDataPointColor()
```

یک رنگ خودکار برای نقطه داده بر اساس شاخص سری، شاخص نقطه داده، ویژگی ParentSeriesGroup.IsColorVaried و سبک نمودار برمی‌گرداند. این رنگ به‌صورت پیش‌فرض اگر FillType برابر NotDefined باشد استفاده می‌شود.

**بازگشت:**
java.awt.Color - رنگ خودکار نقطه داده java.awt.Color

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

ویژگی‌های ورودی افسانهٔ متناظر در صورت نوع نمودار از این فهرست: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. فقط خواندنی [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**بازگشت:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```

نقطه داده را به‌عنوان مجموع تنظیم می‌کند. فقط برای نوع سری Waterfall اعمال می‌شود.

**بازگشت:**
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```

نقطه داده را به‌عنوان مجموع تنظیم می‌کند. فقط برای نوع سری Waterfall اعمال می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

مشخص می‌کند که نقطه داده در صورت منفی بودن مقدار، رنگ‌های خود را معکوس می‌کند. خواندنی/قابل نوشتن boolean.

**بازگشت:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

مشخص می‌کند که نقطه داده در صورت منفی بودن مقدار، رنگ‌های خود را معکوس می‌کند. خواندنی/قابل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

ظرف سطوح نقطه داده را برمی‌گرداند. برای سری‌های Treeamp و Sunburst کاربرد دارد. ایندکس سطوح نقطه داده صفر‌مبنا است.

**بازگشت:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)

### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

تعیین می‌کند این نقطه داده به کدام مجموعهٔ فرزندان والد تعلق دارد. خواندنی long.

**بازگشت:**
long