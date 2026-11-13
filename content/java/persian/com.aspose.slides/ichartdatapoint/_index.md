---
title: IChartDataPoint
second_title: مرجع API Aspose.Slides برای جاوا
description: نقطه داده‌ای سری را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/ichartdatapoint/
---
**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

نقطه داده‌ای سری را نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getXValue()](#getXValue--) | مقدار x یک نقطه داده نمودار را می‌گیرد. |
| [getYValue()](#getYValue--) | مقدار y یک نقطه داده نمودار را می‌گیرد. |
| [getBubbleSize()](#getBubbleSize--) | اندازه حباب یک نقطه داده نمودار را می‌گیرد. |
| [getValue()](#getValue--) | مقدار یک نقطه داده نمودار را می‌گیرد. |
| [getCachedXValue()](#getCachedXValue--) | مقدار X کش‌شده یک نقطه داده نمودار را می‌گیرد. |
| [getCachedYValue()](#getCachedYValue--) | مقدار Y کش‌شده یک نقطه داده نمودار را می‌گیرد. |
| [getCachedValue()](#getCachedValue--) | مقدار کش‌شده یک نقطه داده نمودار را می‌گیرد. |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | اندازه حباب کش‌شده یک نقطه داده نمودار را می‌گیرد. |
| [getSizeValue()](#getSizeValue--) | مقدار اندازه یک نقطه داده نمودار را می‌گیرد. |
| [getColorValue()](#getColorValue--) | مقدار رنگ یک نقطه داده نمودار را می‌گیرد. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | مقدارهای نوارهای خطای سری را در حالت نوع مقدار سفارشی نشان می‌دهد. |
| [getLabel()](#getLabel--) | برچسب یک نقطه داده نمودار را نشان می‌دهد. |
| [isBubble3D()](#isBubble3D--) | مشخص می‌کند که حباب‌ها اثر ۳-بعدی دارند. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | مشخص می‌کند که حباب‌ها اثر ۳-بعدی دارند. |
| [getExplosion()](#getExplosion--) | مقدار جابه‌جایی نقطه داده از مرکز قطاع را مشخص می‌کند. |
| [setExplosion(int value)](#setExplosion-int-) | مقدار جابه‌جایی نقطه داده از مرکز قطاع را مشخص می‌کند. |
| [getFormat()](#getFormat--) | ویژگی‌های قالب‌بندی را نشان می‌دهد. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | ویژگی‌های قالب‌بندی را نشان می‌دهد. |
| [getMarker()](#getMarker--) | یک نشانگر داده را مشخص می‌کند. |
| [remove()](#remove--) | نقطه داده را از سری نمودار حذف می‌کند. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | یک رنگ خودکار برای نقطه داده بر اساس ایندکس سری، ایندکس نقطه داده، ویژگی ParentSeriesGroup.IsColorVaried و سبک نمودار برمی‌گرداند. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | خواص مورد مرتبط در لیجند برای نوع نمودارهای این فهرست: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | نقطه داده را به عنوان مجموع تنظیم می‌کند. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | نقطه داده را به عنوان مجموع تنظیم می‌کند. |
| [getInvertIfNegative()](#getInvertIfNegative--) | مشخص می‌کند که نقطه داده در صورت منفی بودن مقدار، رنگ‌های خود را معکوس کند. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | مشخص می‌کند که نقطه داده در صورت منفی بودن مقدار، رنگ‌های خود را معکوس کند. |
| [getDataPointLevels()](#getDataPointLevels--) | محفظهٔ سطوح نقاط داده را برمی‌گرداند. |
| [getIndex()](#getIndex--) | تعیین می‌کند این نقطه داده به کدام مجموعهٔ فرزندان والد تعلق دارد. |

### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```

مقدار x یک نقطه داده نمودار را می‌گیرد. فقط‌خواندنی [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**بازگشت:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)

### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```

مقدار y یک نقطه داده نمودار را می‌گیرد. فقط‌خواندنی [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**بازگشت:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```

اندازه حباب یک نقطه داده نمودار را می‌گیرد. فقط‌خواندنی [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**بازگشت:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```

مقدار یک نقطه داده نمودار را می‌گیرد. فقط‌خواندنی [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**بازگشت:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getCachedXValue() {#getCachedXValue--}
```
public abstract ICachedChartValue getCachedXValue()
```

مقدار X کش‌شده یک نقطه داده نمودار را می‌گیرد. فقط‌خواندنی [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // تمام مقادیر X کش‌شده سری نمودار را چاپ می‌کند.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedXValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازگشت:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getCachedYValue() {#getCachedYValue--}
```
public abstract ICachedChartValue getCachedYValue()
```

مقدار Y کش‌شده یک نقطه داده نمودار را می‌گیرد. فقط‌خواندنی [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // تمام مقادیر Y کش‌شده سری نمودار را چاپ می‌کند.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedYValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازگشت:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
```

مقدار کش‌شده یک نقطه داده نمودار را می‌گیرد. فقط‌خواندنی [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // تمام مقادیر کش‌شده سری نمودار را چاپ می‌کند.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازگشت:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public abstract ICachedChartValue getCachedBubbleSize()
```

اندازه حباب کش‌شده یک نقطه داده نمودار را می‌گیرد. فقط‌خواندنی [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // تمام مقادیر حجم حباب کش‌شده سری نمودار را چاپ می‌کند.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedBubbleSize().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازگشت:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```

مقدار اندازه یک نقطه داده نمودار را می‌گیرد. برای نمودارهای Treemap و Sunburst استفاده می‌شود. فقط‌خواندنی [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**بازگشت:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

مقدار رنگ یک نقطه داده نمودار را می‌گیرد. برای نمودارهای نقشه استفاده می‌شود. فقط‌خواندنی [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**بازگشت:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

مقدارهای نوارهای خطای سری را در حالت نوع مقدار سفارشی نشان می‌دهد. فقط‌خواندنی [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**بازگشت:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)

### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

برچسب یک نقطه داده نمودار را نشان می‌دهد. فقط‌خواندنی [IDataLabel](../../com.aspose.slides/idatalabel).

**بازگشت:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```

مشخص می‌کند که حباب‌ها اثر ۳-بعدی دارند. قابل‌خواندن/نوشتن بولی.

**بازگشت:**
boolean

### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```

مشخص می‌کند که حباب‌ها اثر ۳-بعدی دارند. قابل‌خواندن/نوشتن بولی.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

مقدار جابه‌جایی نقطه داده از مرکز قطاع را مشخص می‌کند. قابل‌خواندن/نوشتن عدد صحیح.

**بازگشت:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

مقدار جابه‌جایی نقطه داده از مرکز قطاع را مشخص می‌کند. قابل‌خواندن/نوشتن عدد صحیح.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

ویژگی‌های قالب‌بندی را نشان می‌دهد. قابل‌خواندن/نوشتن [IFormat](../../com.aspose.slides/iformat).

**بازگشت:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

ویژگی‌های قالب‌بندی را نشان می‌دهد. قابل‌خواندن/نوشتن [IFormat](../../com.aspose.slides/iformat).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

یک نشانگر داده را مشخص می‌کند. فقط‌خواندنی [IMarker](../../com.aspose.slides/imarker).

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

یک رنگ خودکار برای نقطه داده بر اساس ایندکس سری، ایندکس نقطه داده، ویژگی ParentSeriesGroup.IsColorVaried و سبک نمودار برمی‌گرداند. این رنگ به‌صورت پیش‌فرض استفاده می‌شود اگر FillType برابر NotDefined باشد.

**بازگشت:**
java.awt.Color - رنگ خودکار نقطه داده java.awt.Color

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

خواص مورد مرتبط در لیجند برای نوع نمودارهای این فهرست: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. فقط‌خواندنی [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**بازگشت:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```

نقطه داده را به عنوان مجموع تنظیم می‌کند. برای نوع سری Waterfall فقط اعمال می‌شود.

**بازگشت:**
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```

نقطه داده را به عنوان مجموع تنظیم می‌کند. برای نوع سری Waterfall فقط اعمال می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

مشخص می‌کند که نقطه داده در صورت منفی بودن مقدار، رنگ‌های خود را معکوس کند. قابل‌خواندن/نوشتن بولی.

**بازگشت:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

مشخص می‌کند که نقطه داده در صورت منفی بودن مقدار، رنگ‌های خود را معکوس کند. قابل‌خواندن/نوشتن بولی.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

محفظهٔ سطوح نقاط داده را برمی‌گرداند. برای سری‌های Treeamp و Sunburst اعمال می‌شود. شاخص‌بندی سطوح نقطه داده از صفر شروع می‌شود.

**بازگشت:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)

### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

تعیین می‌کند این نقطه داده به کدام مجموعهٔ فرزندان والد تعلق دارد. فقط عدد صحیح طول.

**بازگشت:**
long