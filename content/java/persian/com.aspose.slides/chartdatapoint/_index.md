---
title: ChartDataPoint
second_title: Aspose.Slides برای مرجع API جاوا
description: نمایندهٔ نقطهٔ دادهٔ سری است.
type: docs
url: /fa/com.aspose.slides/chartdatapoint/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IChartDataPoint](../../com.aspose.slides/ichartdatapoint), com.aspose.slides.IDOMObject
```
public class ChartDataPoint implements IChartDataPoint, IDOMObject
```

Represents series data point.
## متدها

| متد | توضیح |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | مقدار اندازه نقطهٔ دادهٔ نمودار را برمی‌گرداند. |
| [getColorValue()](#getColorValue--) | مقدار رنگ نقطهٔ دادهٔ نمودار را برمی‌گرداند. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | مقادیر نوارهای خطای سری را در حالت مقدار سفارشی نشان می‌دهد. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | مشخص می‌کند که حباب‌ها اثر سه‌بعدی دارند. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | مشخص می‌کند که حباب‌ها اثر سه‌بعدی دارند. |
| [getExplosion()](#getExplosion--) | مقدار جابجایی نقطهٔ داده از مرکز کیک را مشخص می‌کند. |
| [setExplosion(int value)](#setExplosion-int-) | مقدار جابجایی نقطهٔ داده از مرکز کیک را مشخص می‌کند. |
| [getFormat()](#getFormat--) | ویژگی‌های قالب‌بندی را نشان می‌دهد. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | ویژگی‌های قالب‌بندی را نشان می‌دهد. |
| [getMarker()](#getMarker--) | یک علامت داده را مشخص می‌کند. |
| [getSetAsTotal()](#getSetAsTotal--) | نقطهٔ داده را به‌عنوان مجموع تنظیم می‌کند. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | نقطهٔ داده را به‌عنوان مجموع تنظیم می‌کند. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | ویژگی‌های ورودی مربوط به legend entry در موارد ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. فقط-خواندنی. |
| [remove()](#remove--) | DataPoint را از سری نمودار حذف می‌کند. |
| [getDataPointLevels()](#getDataPointLevels--) | محفظهٔ سطوح نقطهٔ داده را برمی‌گرداند. |
| [getIndex()](#getIndex--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | یک رنگ خودکار برای نقطهٔ داده بر پایهٔ ایندکس سری، ایندکس نقطهٔ داده، ویژگی ParentSeriesGroup.IsColorVaried و سبک نمودار برمی‌گرداند. |
| [getInvertIfNegative()](#getInvertIfNegative--) | مشخص می‌کند که DataPoint رنگ‌های خود را در صورت مقدار منفی معکوس می‌کند. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | مشخص می‌کند که DataPoint رنگ‌های خود را در صورت مقدار منفی معکوس می‌کند. |
| [getCachedValue()](#getCachedValue--) | مقدار کشیده‌شدهٔ یک نقطهٔ دادهٔ نمودار را دریافت می‌کند. |
| [getCachedXValue()](#getCachedXValue--) | مقدار X کشیده‌شدهٔ یک نقطهٔ دادهٔ نمودار را دریافت می‌کند. |
| [getCachedYValue()](#getCachedYValue--) | مقدار Y کشیده‌شدهٔ یک نقطهٔ دادهٔ نمودار را دریافت می‌کند. |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | اندازهٔ حباب کشیده‌شدهٔ یک نقطهٔ دادهٔ نمودار را دریافت می‌کند. |
| [getActualX()](#getActualX--) | موقعیت حقیقی x (چپ) عنصر نمودار نسبت به گوشهٔ چپ-بالای نمودار را مشخص می‌کند. |
| [getActualY()](#getActualY--) | موقعیت حقیقی بالا سمت عنصر نمودار نسبت به گوشهٔ چپ-بالای نمودار را مشخص می‌کند. |
| [getActualWidth()](#getActualWidth--) | عرض حقیقی عنصر نمودار را مشخص می‌کند. |
| [getActualHeight()](#getActualHeight--) | ارتفاع حقیقی عنصر نمودار را مشخص می‌کند. |
### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```

XValue. فقط-خواندنی [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**بازمی‌گرداند:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```

YValue. فقط-خواندنی [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**بازمی‌گرداند:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```

BubbleSize. فقط-خواندنی [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**بازمی‌گرداند:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```

Value. فقط-خواندنی [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**بازمی‌گرداند:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```

مقدار اندازه نقطهٔ دادهٔ نمودار را برمی‌گرداند. برای نمودارهای Treemap و Sunburst استفاده می‌شود. فقط-خواندنی [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**بازمی‌گرداند:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```

مقدار رنگ نقطهٔ دادهٔ نمودار را برمی‌گرداند. برای نمودارهای Map استفاده می‌شود. فقط-خواندنی [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**بازمی‌گرداند:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```

مقادیر نوارهای خطای سری را در حالت مقدار سفارشی نشان می‌دهد. فقط-خواندنی [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**بازمی‌گرداند:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```

Label. فقط-خواندنی [IDataLabel](../../com.aspose.slides/idatalabel).

**بازمی‌گرداند:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```

مشخص می‌کند که حباب‌ها اثر سه‌بعدی دارند. قابل‌خواندن/نوشتن بولی.

**بازمی‌گرداند:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```

مشخص می‌کند که حباب‌ها اثر سه‌بعدی دارند. قابل‌خواندن/نوشتن بولی.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

مقدار جابجایی نقطهٔ داده از مرکز کیک را مشخص می‌کند. قابل‌خواندن/نوشتن عدد صحیح.

**بازمی‌گرداند:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

مقدار جابجایی نقطهٔ داده از مرکز کیک را مشخص می‌کند. قابل‌خواندن/نوشتن عدد صحیح.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

ویژگی‌های قالب‌بندی را نشان می‌دهد. قابل‌خواندن/نوشتن [IFormat](../../com.aspose.slides/iformat).

**بازمی‌گرداند:**
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

یک علامت داده را مشخص می‌کند. فقط-خواندنی [IMarker](../../com.aspose.slides/imarker).

**بازمی‌گرداند:**
[IMarker](../../com.aspose.slides/imarker)
### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```

نقطهٔ داده را به‌عنوان مجموع تنظیم می‌کند. فقط برای نوع سری Waterfall اعمال می‌شود.

**بازمی‌گرداند:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```

نقطهٔ داده را به‌عنوان مجموع تنظیم می‌کند. فقط برای نوع سری Waterfall اعمال می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

ویژگی‌های ورودی مربوط به legend entry در موارد ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. فقط-خواندنی [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**بازمی‌گرداند:**
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

محفظهٔ سطوح نقطهٔ داده را برمی‌گرداند. برای سری‌های Treeamp و Sunburst اعمال می‌شود. ایندکس سطوح نقطهٔ داده صفر-مبنایی است.

**بازمی‌گرداند:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public final long getIndex()
```

  

**بازمی‌گرداند:**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را برمی‌گرداند. فقط-خواندنی IDOMObject.

**بازمی‌گرداند:**
com.aspose.slides.IDOMObject
### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Color getAutomaticDataPointColor()
```

یک رنگ خودکار برای نقطهٔ داده بر پایهٔ ایندکس سری، ایندکس نقطهٔ داده، ویژگی ParentSeriesGroup.IsColorVaried و سبک نمودار برمی‌گرداند. این رنگ به‌صورت پیش‌فرض استفاده می‌شود اگر FillType برابر NotDefined باشد.

**بازمی‌گرداند:**
java.awt.Color
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

مشخص می‌کند که DataPoint رنگ‌های خود را در صورت مقدار منفی معکوس می‌کند. قابل‌خواندن/نوشتن بولی.

**بازمی‌گرداند:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

مشخص می‌کند که DataPoint رنگ‌های خود را در صورت مقدار منفی معکوس می‌کند. قابل‌خواندن/نوشتن بولی.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getCachedValue() {#getCachedValue--}
```
public final ICachedChartValue getCachedValue()
```

مقدار کشیده‌شدهٔ یک نقطهٔ دادهٔ نمودار را دریافت می‌کند. فقط-خواندنی [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Print all cached values of the chart series.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازمی‌گرداند:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedXValue() {#getCachedXValue--}
```
public final ICachedChartValue getCachedXValue()
```

مقدار X کشیده‌شدهٔ یک نقطهٔ دادهٔ نمودار را دریافت می‌کند. فقط-خواندنی [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Print all cached X values of the chart series.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedXValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازمی‌گرداند:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedYValue() {#getCachedYValue--}
```
public final ICachedChartValue getCachedYValue()
```

مقدار Y کشیده‌شدهٔ یک نقطهٔ دادهٔ نمودار را دریافت می‌کند. فقط-خواندنی [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // چاپ تمام مقادیر کش‌شدهٔ Y سری نمودار.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedYValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازمی‌گرداند:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public final ICachedChartValue getCachedBubbleSize()
```

اندازهٔ حباب کشیده‌شدهٔ یک نقطهٔ دادهٔ نمودار را دریافت می‌کند. فقط-خواندنی [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // چاپ تمام مقادیر کش‌شدهٔ اندازهٔ حباب سری نمودار.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedBubbleSize().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازمی‌گرداند:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getActualX() {#getActualX--}
```
public final float getActualX()
```

موقعیت حقیقی x (چپ) عنصر نمودار نسبت به گوشهٔ چپ-بالای نمودار را مشخص می‌کند. قبل از دریافت مقادیر حقیقی، متد IChart.ValidateChartLayout() را صدا بزنید. قابل‌خواندن عدد اعشاری.

**بازمی‌گرداند:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

موقعیت حقیقی بالا سمت عنصر نمودار نسبت به گوشهٔ چپ-بالای نمودار را مشخص می‌کند. قبل از دریافت مقادیر حقیقی، متد IChart.ValidateChartLayout() را صدا بزنید. قابل‌خواندن عدد اعشاری.

**بازمی‌گرداند:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

عرض حقیقی عنصر نمودار را مشخص می‌کند. قبل از دریافت مقادیر حقیقی، متد IChart.ValidateChartLayout() را صدا بزنید. قابل‌خواندن عدد اعشاری.

**بازمی‌گرداند:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

ارتفاع حقیقی عنصر نمودار را مشخص می‌کند. قبل از دریافت مقادیر حقیقی، متد IChart.ValidateChartLayout() را صدا بزنید. قابل‌خواندن عدد اعشاری.

**بازمی‌گرداند:**
float