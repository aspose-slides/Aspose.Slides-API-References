---
title: IChartDataPoint
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایانگر نقطه دادهٔ سری است.
type: docs
url: /fa/com.aspose.slides/ichartdatapoint/
---
**تمام واسط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

نمایانگر نقطه دادهٔ سری است.
## متدها

| متد | توضیح |
| --- | --- |
| [getXValue()](#getXValue--) | مقدار x نقطه دادهٔ نمودار را باز می‌گرداند. |
| [getYValue()](#getYValue--) | مقدار y نقطه دادهٔ نمودار را باز می‌گرداند. |
| [getBubbleSize()](#getBubbleSize--) | اندازه حباب نقطه دادهٔ نمودار را باز می‌گرداند. |
| [getValue()](#getValue--) | مقدار نقطه دادهٔ نمودار را باز می‌گرداند. |
| [getSizeValue()](#getSizeValue--) | مقدار اندازهٔ نقطه دادهٔ نمودار را باز می‌گرداند. |
| [getColorValue()](#getColorValue--) | مقدار رنگ نقطه دادهٔ نمودار را باز می‌گرداند. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | مقادیر نوارهای خطا برای سری در حالت مقدار سفارشی را نشان می‌دهد. |
| [getLabel()](#getLabel--) | نمایانگر برچسب نقطه دادهٔ نمودار است. |
| [isBubble3D()](#isBubble3D--) | مشخص می‌کند که حباب‌ها اثر سه‌بعدی دارند. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | مشخص می‌کند که حباب‌ها اثر سه‌بعدی دارند. |
| [getExplosion()](#getExplosion--) | مقدارى که نقطه داده باید از مرکز کیک جابجا شود را مشخص می‌کند. |
| [setExplosion(int value)](#setExplosion-int-) | مقدارى که نقطه داده باید از مرکز کیک جابجا شود را مشخص می‌کند. |
| [getFormat()](#getFormat--) | نمایانگر ویژگی‌های قالب‌بندی است. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | نمایانگر ویژگی‌های قالب‌بندی است. |
| [getMarker()](#getMarker--) | یک نشانگر داده را مشخص می‌کند. |
| [remove()](#remove--) | DataPoint را از سری نمودار حذف می‌کند. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | یک رنگ خودکار برای نقطه داده بر اساس ایندکس سری، ایندکس نقطه داده، ویژگی ParentSeriesGroup.IsColorVaried و سبک نمودار باز می‌گرداند. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | ویژگی‌های ورودی legend مربوطه در صورت نوع نمودار از این فهرست: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | نقطه داده را به عنوان مجموع تنظیم می‌کند. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | نقطه داده را به عنوان مجموع تنظیم می‌کند. |
| [getInvertIfNegative()](#getInvertIfNegative--) | مشخص می‌کند که اگر مقدار منفی باشد، نقطه داده رنگ‌های خود را معکوس می‌کند. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | مشخص می‌کند که اگر مقدار منفی باشد، نقطه داده رنگ‌های خود را معکوس می‌کند. |
| [getDataPointLevels()](#getDataPointLevels--) | مخزن سطوح نقطه داده را باز می‌گرداند. |
| [getIndex()](#getIndex--) | مشخص می‌کند این نقطه داده به کدام مجموعهٔ فرزندان والد تعلق دارد. |

### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```

مقدار x نقطه دادهٔ نمودار را باز می‌گرداند. فقط‌خواندنی [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**باز می‌گرداند:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```

مقدار y نقطه دادهٔ نمودار را باز می‌گرداند. فقط‌خواندنی [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**باز می‌گرداند:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```

اندازه حباب نقطه دادهٔ نمودار را باز می‌گرداند. فقط‌خواندنی [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**باز می‌گرداند:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```

مقدار نقطه دادهٔ نمودار را باز می‌گرداند. فقط‌خواندنی [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**باز می‌گرداند:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```

مقدار اندازهٔ نقطه دادهٔ نمودار را باز می‌گرداند. برای نمودارهای Treemap و Sunburst استفاده می‌شود. فقط‌خواندنی [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**باز می‌گرداند:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

مقدار رنگ نقطه دادهٔ نمودار را باز می‌گرداند. برای نمودارهای Map استفاده می‌شود. فقط‌خواندنی [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**باز می‌گرداند:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

مقادیر نوارهای خطا برای سری در حالت مقدار سفارشی را نشان می‌دهد. فقط‌خواندنی [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**باز می‌گرداند:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

نمایانگر برچسب نقطه دادهٔ نمودار است. فقط‌خواندنی [IDataLabel](../../com.aspose.slides/idatalabel).

**باز می‌گرداند:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```

مشخص می‌کند که حباب‌ها اثر سه‌بعدی دارند. خواندنی/نوشتنی boolean.

**باز می‌گرداند:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```

مشخص می‌کند که حباب‌ها اثر سه‌بعدی دارند. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

مقداری که نقطه داده باید از مرکز کیک جابجا شود را مشخص می‌کند. خواندنی/نوشتنی int.

**باز می‌گرداند:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

مقداری که نقطه داده باید از مرکز کیک جابجا شود را مشخص می‌کند. خواندنی/نوشتنی int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

نمایانگر ویژگی‌های قالب‌بندی است. خواندنی/نوشتنی [IFormat](../../com.aspose.slides/iformat).

**باز می‌گرداند:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

نمایانگر ویژگی‌های قالب‌بندی است. خواندنی/نوشتنی [IFormat](../../com.aspose.slides/iformat).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

یک نشانگر داده را مشخص می‌کند. فقط‌خواندنی [IMarker](../../com.aspose.slides/imarker).

**باز می‌گرداند:**
[IMarker](../../com.aspose.slides/imarker)
### remove() {#remove--}
```
public abstract void remove()
```

DataPoint را از سری نمودار حذف می‌کند.

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Integer getAutomaticDataPointColor()
```

یک رنگ خودکار برای نقطه داده بر اساس ایندکس سری، ایندکس نقطه داده، ویژگی ParentSeriesGroup.IsColorVaried و سبک نمودار باز می‌گرداند. این رنگ به‌طور پیش‌فرض استفاده می‌شود اگر FillType برابر NotDefined باشد.

**باز می‌گرداند:**
java.lang.Integer - Automatic color of data point java.lang.Integer
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

ویژگی‌های ورودی legend مربوطه در صورت نوع نمودار از این فهرست: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. فقط‌خواندنی [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**باز می‌گرداند:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```

نقطه داده را به عنوان مجموع تنظیم می‌کند. فقط برای نوع سری Waterfall اعمال می‌شود.

**باز می‌گرداند:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```

نقطه داده را به عنوان مجموع تنظیم می‌کند. فقط برای نوع سری Waterfall اعمال می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

مشخص می‌کند که اگر مقدار منفی باشد، نقطه داده رنگ‌های خود را معکوس می‌کند. خواندنی/نوشتنی boolean.

**باز می‌گرداند:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

مشخص می‌کند که اگر مقدار منفی باشد، نقطه داده رنگ‌های خود را معکوس می‌کند. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

مخزن سطوح نقطه داده را باز می‌گرداند. برای سری‌های Treeamp و Sunburst اعمال می‌شود. ایندکس سطوح نقطه داده صفر-مبنا است.

**باز می‌گرداند:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

مشخص می‌کند این نقطه داده به کدام مجموعهٔ فرزندان والد تعلق دارد. خواندنی long.

**باز می‌گرداند:**
long