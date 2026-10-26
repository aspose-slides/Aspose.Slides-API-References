---
title: ChartDataPoint
second_title: مرجع API Aspose.Slides برای Java
description: نقطه دادهٔ سری را نمایان می‌کند.
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

نمایش‌گر نقطه داده سری.
## روش‌ها

| متد | توضیحات |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | مقدار اندازه نقطه داده نمودار را برمی‌گرداند. |
| [getColorValue()](#getColorValue--) | مقدار رنگ نقطه داده نمودار را برمی‌گرداند. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | مقادیر نوارهای خطای سری را در صورت نوع مقدار سفارشی نمایش می‌دهد. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | مشخص می‌کند که حباب‌ها اثر سه‌بعدی دارند. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | مشخص می‌کند که حباب‌ها اثر سه‌بعدی دارند. |
| [getExplosion()](#getExplosion--) | مقدار جابجایی نقطه داده از مرکز پای چارت را تعیین می‌کند. |
| [setExplosion(int value)](#setExplosion-int-) | مقدار جابجایی نقطه داده از مرکز پای چارت را تعیین می‌کند. |
| [getFormat()](#getFormat--) | ویژگی‌های قالب‌بندی را نمایش می‌دهد. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | ویژگی‌های قالب‌بندی را نمایش می‌دهد. |
| [getMarker()](#getMarker--) | یک نشانگر داده را مشخص می‌کند. |
| [getSetAsTotal()](#getSetAsTotal--) | نقطه داده را به عنوان مجموع تنظیم می‌کند. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | نقطه داده را به عنوان مجموع تنظیم می‌کند. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | ویژگی‌های ورودی افسانه مرتبط در صورت نوع نمودارهای زیر: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | نقطه داده را از سری نمودار حذف می‌کند. |
| [getDataPointLevels()](#getDataPointLevels--) | مخزنی از سطوح نقطه داده را برمی‌گرداند. |
| [getIndex()](#getIndex--) |    |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | یک رنگ خودکار برای نقطه داده بر پایه شماره سری، شماره نقطه داده، ویژگی ParentSeriesGroup.IsColorVaried و سبک نمودار برمی‌گرداند. |
| [getInvertIfNegative()](#getInvertIfNegative--) | مشخص می‌کند که نقطه داده در صورت مقدار منفی رنگ‌هایش را معکوس کند. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | مشخص می‌کند که نقطه داده در صورت مقدار منفی رنگ‌هایش را معکوس کند. |
| [getActualX()](#getActualX--) | موقعیت واقعی x (چپ) عنصر نمودار را نسبت به گوشهٔ بالا-چپ نمودار تعیین می‌کند. |
| [getActualY()](#getActualY--) | موقعیت واقعی بالای عنصر نمودار را نسبت به گوشهٔ بالا-چپ نمودار تعیین می‌کند. |
| [getActualWidth()](#getActualWidth--) | عرض واقعی عنصر نمودار را تعیین می‌کند. |
| [getActualHeight()](#getActualHeight--) | ارتفاع واقعی عنصر نمودار را تعیین می‌کند. |
### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```

XValue. فقط-خواندنی [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**باز می‌گرداند:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```

YValue. فقط-خواندنی [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**باز می‌گرداند:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```

BubbleSize. فقط-خواندنی [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**باز می‌گرداند:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```

Value. فقط-خواندنی [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**باز می‌گرداند:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```

مقدار اندازه نقطه داده نمودار را برمی‌گرداند. برای چارت‌های Treemap و Sunburst استفاده می‌شود. فقط-خواندنی [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**باز می‌گرداند:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```

مقدار رنگ نقطه داده نمودار را برمی‌گرداند. برای چارت‌های Map استفاده می‌شود. فقط-خواندنی [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**باز می‌گرداند:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```

نمایش‌گر مقادیر نوارهای خطای سری در صورت نوع مقدار سفارشی. فقط-خواندنی [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**باز می‌گرداند:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```

Label. فقط-خواندنی [IDataLabel](../../com.aspose.slides/idatalabel).

**باز می‌گرداند:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```

مشخص می‌کند که حباب‌ها اثر سه‌بعدی دارند. خواندنی/نوشتنی بولی.

**باز می‌گرداند:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```

مشخص می‌کند که حباب‌ها اثر سه‌بعدی دارند. خواندنی/نوشتنی بولی.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

مقدار جابجایی نقطه داده از مرکز پای چارت را تعیین می‌کند. خواندنی/نوشتنی عدد صحیح.

**باز می‌گرداند:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

مقدار جابجایی نقطه داده از مرکز پای چارت را تعیین می‌کند. خواندنی/نوشتنی عدد صحیح.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

ویژگی‌های قالب‌بندی را نمایش می‌دهد. خواندنی/نوشتنی [IFormat](../../com.aspose.slides/iformat).

**باز می‌گرداند:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

ویژگی‌های قالب‌بندی را نمایش می‌دهد. خواندنی/نوشتنی [IFormat](../../com.aspose.slides/iformat).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

یک نشانگر داده را مشخص می‌کند. فقط-خواندنی [IMarker](../../com.aspose.slides/imarker).

**باز می‌گرداند:**
[IMarker](../../com.aspose.slides/imarker)
### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```

نقطه داده را به عنوان مجموع تنظیم می‌کند. فقط برای نوع سری Waterfall اعمال می‌شود.

**باز می‌گرداند:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```

نقطه داده را به عنوان مجموع تنظیم می‌کند. فقط برای نوع سری Waterfall اعمال می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

ویژگی‌های ورودی افسانهٔ مرتبط در صورت نوع نمودارهای زیر: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. فقط-خواندنی [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**باز می‌گرداند:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### remove() {#remove--}
```
public final void remove()
```

نقطه داده را از سری نمودار حذف می‌کند.
### getDataPointLevels() {#getDataPointLevels--}
```
public final IChartDataPointLevelsManager getDataPointLevels()
```

مخزنی از سطوح نقطه داده را برمی‌گرداند. برای سری‌های Treeamp و Sunburst اعمال می‌شود. ایندکس‌گذاری سطوح نقطه داده از صفر شروع می‌شود.

**باز می‌گرداند:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public final long getIndex()
```

  

**باز می‌گرداند:**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را برمی‌گرداند. فقط-خواندنی IDOMObject.

**باز می‌گرداند:**
com.aspose.slides.IDOMObject
### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Color getAutomaticDataPointColor()
```

یک رنگ خودکار برای نقطه داده بر پایه شماره سری، شماره نقطه داده، ویژگی ParentSeriesGroup.IsColorVaried و سبک نمودار برمی‌گرداند. این رنگ به‌طور پیش‌فرض وقتی FillType برابر NotDefined باشد استفاده می‌شود.

**باز می‌گرداند:**
java.awt.Color
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

مشخص می‌کند که نقطه داده در صورت مقدار منفی رنگ‌هایش را معکوس کند. خواندنی/نوشتنی بولی.

**باز می‌گرداند:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

مشخص می‌کند که نقطه داده در صورت مقدار منفی رنگ‌هایش را معکوس کند. خواندنی/نوشتنی بولی.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getActualX() {#getActualX--}
```
public final float getActualX()
```

موقعیت واقعی x (چپ) عنصر نمودار را نسبت به گوشهٔ بالا-چپ نمودار تعیین می‌کند. قبل از دریافت مقادیر واقعی، متد IChart.ValidateChartLayout() را صدا بزنید. خواندنی عدد شناور.

**باز می‌گرداند:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

موقعیت واقعی بالای عنصر نمودار را نسبت به گوشهٔ بالا-چپ نمودار تعیین می‌کند. قبل از دریافت مقادیر واقعی، متد IChart.ValidateChartLayout() را صدا بزنید. خواندنی عدد شناور.

**باز می‌گرداند:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

عرض واقعی عنصر نمودار را تعیین می‌کند. قبل از دریافت مقادیر واقعی، متد IChart.ValidateChartLayout() را صدا بزنید. خواندنی عدد شناور.

**باز می‌گرداند:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

ارتفاع واقعی عنصر نمودار را تعیین می‌کند. قبل از دریافت مقادیر واقعی، متد IChart.ValidateChartLayout() را صدا بزنید. خواندنی عدد شناور.

**باز می‌گرداند:**
float