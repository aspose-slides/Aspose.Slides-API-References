---
title: IChartSeriesGroup
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر یک گروه از سری‌ها.
type: docs
url: /fa/com.aspose.slides/ichartseriesgroup/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

نمایانگر یک گروه از سری‌ها است.

--------------------

1) خلاصه و نکات را برای کلاس ChartSeriesGroupCollection و enum CombinableSeriesTypesGroup ببینید. 2) گروه سری‌ها شامل برخی ویژگی‌های سری است که برای هر سری در گروه مشترک است ("series group properties"). «Series group properties» در کلاس ChartSeriesGroup قابل خواندن/نوشتن است. هر یک از «series group properties» می‌توانند یک نمایش فقط‌خواندنی در کلاس ChartSeries داشته باشند.
## متدها

| متد | توضیح |
| --- | --- |
| [getType()](#getType--) | نوع این گروه سری را برمی‌گرداند. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | مشخص می‌کند آیا سری‌های این گروه بر روی محور ثانویه ترسیم می‌شوند. |
| [getSeries()](#getSeries--) | مجموعه‌ای فقط‌خواندنی از سری‌های نمودار را برمی‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | عنصر موجود در اندیس مشخص شده را دریافت می‌کند. |
| [getUpDownBars()](#getUpDownBars--) | دسترسی به نوارهای بالا/پایین نمودار خطی یا سهام را فراهم می‌کند. |
| [getGapWidth()](#getGapWidth--) | فضای بین خوشه‌های نوار یا ستون را به عنوان درصدی از عرض نوار یا ستون دریافت یا تنظیم می‌کند. |
| [setGapWidth(int value)](#setGapWidth-int-) | فضای بین خوشه‌های نوار یا ستون را به عنوان درصدی از عرض نوار یا ستون دریافت یا تنظیم می‌کند. |
| [getGapDepth()](#getGapDepth--) | فاصله بین سری‌های داده در یک نمودار 3D را به عنوان درصدی از عرض نشانگر دریافت یا تنظیم می‌کند. |
| [setGapDepth(int value)](#setGapDepth-int-) | فاصله بین سری‌های داده در یک نمودار 3D را به عنوان درصدی از عرض نشانگر دریافت یا تنظیم می‌کند. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | زاویه برش اولین قطعه دایره یا دونات در درجه (از بالا به جهت ساعتگرد، از 0 تا 360 درجه) را دریافت یا تنظیم می‌کند. |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | زاویه برش اولین قطعه دایره یا دونات در درجه (از بالا به جهت ساعتگرد، از 0 تا 360 درجه) را دریافت یا تنظیم می‌کند. |
| [isColorVaried()](#isColorVaried--) | مشخص می‌کند که هر نشانگر داده در سری رنگ متفاوتی دارد. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | مشخص می‌کند که هر نشانگر داده در سری رنگ متفاوتی دارد. |
| [hasSeriesLines()](#hasSeriesLines--) | در صورتی که نمودار خطوط سری داشته باشد، صحیح است. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | در صورتی که نمودار خطوط سری داشته باشد، صحیح است. |
| [getOverlap()](#getOverlap--) | مشخص می‌کند که نوارها و ستون‌ها تا چه حد در نمودارهای دو-بعدی هم‌پوشانی داشته باشند، به صورت درصد (از -100٪ تا 100٪). |
| [setOverlap(byte value)](#setOverlap-byte-) | مشخص می‌کند که نوارها و ستون‌ها تا چه حد در نمودارهای دو-بعدی هم‌پوشانی داشته باشند، به صورت درصد (از -100٪ تا 100٪). |
| [getSecondPieSize()](#getSecondPieSize--) | اندازهٔ دومین دایره یا نوار در نمودار پای-از-پای یا نوار-از-پای را به عنوان درصدی از اندازهٔ اولین دایره مشخص می‌کند (می‌تواند بین 5 تا 200 درصد باشد). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | اندازهٔ دومین دایره یا نوار در نمودار پای-از-پای یا نوار-از-پای را به عنوان درصدی از اندازهٔ اولین دایره مشخص می‌کند (می‌تواند بین 5 تا 200 درصد باشد). |
| [getPieSplitPosition()](#getPieSplitPosition--) | مقداری را تعیین می‌کند که برای شناسایی نقاط داده در دومین دایره یا نوار در نمودار پای-از-پای یا نوار-از-پای استفاده می‌شود. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | مقداری را تعیین می‌کند که برای شناسایی نقاط داده در دومین دایره یا نوار در نمودار پای-از-پای یا نوار-از-پای استفاده می‌شود. |
| [getPieSplitBy()](#getPieSplitBy--) | نحوه تعیین نقاط داده‌ای که در دومین دایره یا نوار نمودار پای-از-پای یا نوار-از-پای قرار می‌گیرند را مشخص می‌کند. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | نحوه تعیین نقاط داده‌ای که در دومین دایره یا نوار نمودار پای-از-پای یا نوار-از-پای قرار می‌گیرند را مشخص می‌کند. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | اطلاعات تقسیم سفارشی برای یک نمودار پای-از-پای یا نوار-از-پای با تقسیم سفارشی. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | اندازهٔ سوراخ در یک نمودار دونات را مشخص می‌کند (می‌تواند بین 10 تا 90 درصد از اندازهٔ ناحیهٔ رسم باشد). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | اندازهٔ سوراخ در یک نمودار دونات را مشخص می‌کند (می‌تواند بین 10 تا 90 درصد از اندازهٔ ناحیهٔ رسم باشد). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | ضریب مقیاس برای نمودار حبابی را مشخص می‌کند (می‌تواند بین 0 تا 300 درصد از اندازهٔ پیش‌فرض باشد). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | ضریب مقیاس برای نمودار حبابی را مشخص می‌کند (می‌تواند بین 0 تا 300 درصد از اندازهٔ پیش‌فرض باشد). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | قالب HiLowLines را تعیین می‌کند. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | نحوه نمایش مقادیر اندازهٔ حباب‌ها در نمودار حبابی را تعیین می‌کند. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | نحوه نمایش مقادیر اندازهٔ حباب‌ها در نمودار حبابی را تعیین می‌کند. |

### getType() {#getType--}
```
public abstract int getType()
```

نوع این گروه سری را برمی‌گرداند. فقط‌خواندنی [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**باز می‌گرداند:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

مشخص می‌کند آیا سری‌های این گروه بر روی محور ثانویه ترسیم می‌شوند. فقط‌خواندنی boolean.

**باز می‌گرداند:**
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

مجموعه‌ای فقط‌خواندنی از سری‌های نمودار را برمی‌گرداند. فقط‌خواندنی [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**باز می‌گرداند:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

عنصر موجود در اندیس مشخص شده را دریافت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**باز می‌گرداند:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public abstract IUpDownBarsManager getUpDownBars()
```

دسترسی به نوارهای بالا/پایین نمودار خطی یا سهام را فراهم می‌کند. فقط‌خواندنی [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**باز می‌گرداند:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

فضای بین خوشه‌های نوار یا ستون را به عنوان درصدی از عرض نوار یا ستون دریافت یا تنظیم می‌کند. مقدار باید بین 0 تا 500 باشد. قابل خواندن/نوشتن int.

--------------------

این ویژگی برای سری‌های از انواع زیر اعمال می‌شود: همه زیرنوع‌های نوار و ستون، [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie)، [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie)، [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker)، [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel)، [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram)، [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**باز می‌گرداند:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

فضای بین خوشه‌های نوار یا ستون را به عنوان درصدی از عرض نوار یا ستون دریافت یا تنظیم می‌کند. مقدار باید بین 0 تا 500 باشد. قابل خواندن/نوشتن int.

--------------------

این ویژگی برای سری‌های از انواع زیر اعمال می‌شود: همه زیرنوع‌های نوار و ستون، [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie)، [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie)، [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker)، [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel)، [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram)، [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

فاصله بین سری‌های داده در یک نمودار 3D را به عنوان درصدی از عرض نشانگر دریافت یا تنظیم می‌کند. مقدار باید بین 0 تا 500 باشد. قابل خواندن/نوشتن int.

--------------------

این ویژگی برای سری‌های از انواع زیر اعمال می‌شود: زیرنوع‌های 3D نوار و ستون، [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D)، [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D)، [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D)، [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**باز می‌گرداند:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

فاصله بین سری‌های داده در یک نمودار 3D را به عنوان درصدی از عرض نشانگر دریافت یا تنظیم می‌کند. مقدار باید بین 0 تا 500 باشد. قابل خواندن/نوشتن int.

--------------------

این ویژگی برای سری‌های از انواع زیر اعمال می‌شود: زیرنوع‌های 3D نوار و ستون، [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D)، [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D)، [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D)، [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

زاویه برش اولین قطعه دایره یا دونات را در درجه (از بالا به جهت ساعتگرد، از 0 تا 360 درجه) دریافت یا تنظیم می‌کند. قابل خواندن/نوشتن int.

**باز می‌گرداند:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

زاویه برش اولین قطعه دایره یا دونات را در درجه (از بالا به جهت ساعتگرد، از 0 تا 360 درجه) دریافت یا تنظیم می‌کند. قابل خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

مشخص می‌کند که هر نشانگر داده در سری رنگ متفاوتی دارد. قابل خواندن/نوشتن boolean.

**باز می‌گرداند:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

مشخص می‌کند که هر نشانگر داده در سری رنگ متفاوتی دارد. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

در صورتی که نمودار خطوط سری داشته باشد، صحیح است. برای نمودارهای stacked bar و OfPie اعمال می‌شود. قابل خواندن/نوشتن boolean.

**باز می‌گرداند:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

در صورتی که نمودار خطوط سری داشته باشد، صحیح است. برای نمودارهای stacked bar و OfPie اعمال می‌شود. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

مشخص می‌کند که نوارها و ستون‌ها تا چه حد در نمودارهای دو-بعدی هم‌پوشانی داشته باشند، به صورت درصد (از -100٪ تا 100٪). -100٪: بیشترین فاصله (نوارها کاملاً جدا هستند). -0٪: نوارها بدون هم‌پوشانی یا فاصله کنار هم قرار می‌گیرند. 100٪: بیشترین هم‌پوشانی (نوارها کاملاً یک‌دیگر را می‌پوشانند). این ویژگی قابل خواندن/نوشتن byte.

--------------------

> ```
> مثال زیر نشان می‌دهد چگونه برای یک گروه سری نمودار همپوشانی را تنظیم کنیم 
>   و نمودار حاصل را روی یک فرم رندر می‌کند:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // تنظیم همپوشانی به 55٪
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**باز می‌گرداند:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public abstract void setOverlap(byte value)
```

مشخص می‌کند که نوارها و ستون‌ها تا چه حد در نمودارهای دو-بعدی هم‌پوشانی داشته باشند، به صورت درصد (از -100٪ تا 100٪). -100٪: بیشترین فاصله (نوارها کاملاً جدا هستند). -0٪: نوارها بدون هم‌پوشانی یا فاصله کنار هم قرار می‌گیرند. 100٪: بیشترین هم‌پوشانی (نوارها کاملاً یک‌دیگر را می‌پوشانند). این ویژگی قابل خواندن/نوشتن byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // تنظیم همپوشانی به 55٪
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

اندازهٔ دومین دایره یا نوار در نمودار پای-از-پای یا نوار-از-پای را به عنوان درصدی از اندازهٔ اولین دایره مشخص می‌کند (می‌تواند بین 5 تا 200 درصد باشد). قابل خواندن/نوشتن int.

**باز می‌گرداند:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

اندازهٔ دومین دایره یا نوار در نمودار پای-از-پای یا نوار-از-پای را به عنوان درصدی از اندازهٔ اولین دایره مشخص می‌کند (می‌تواند بین 5 تا 200 درصد باشد). قابل خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

مقداری را تعیین می‌کند که برای شناسایی نقاط داده در دومین دایره یا نوار در نمودار پای-از-پای یا نوار-از-پای استفاده می‌شود. همراه با ویژگی PieSplitBy استفاده می‌شود. قابل خواندن/نوشتن double.

**باز می‌گرداند:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

مقداری را تعیین می‌کند که برای شناسایی نقاط داده در دومین دایره یا نوار در نمودار پای-از-پای یا نوار-از-پای استفاده می‌شود. همراه با ویژگی PieSplitBy استفاده می‌شود. قابل خواندن/نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

نحوه تعیین نقاط داده‌ای که در دومین دایره یا نوار نمودار پای-از-پای یا نوار-از-پای قرار می‌گیرند را مشخص می‌کند. قابل خواندن/نوشتن [PieSplitType](../../com.aspose.slides/piesplittype).

**باز می‌گرداند:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

نحوه تعیین نقاط داده‌ای که در دومین دایره یا نوار نمودار پای-از-پای یا نوار-از-پای قرار می‌گیرند را مشخص می‌کند. قابل خواندن/نوشتن [PieSplitType](../../com.aspose.slides/piesplittype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

اطلاعات تقسیم سفارشی برای یک نمودار پای-از-پای یا نوار-از-پای با تقسیم سفارشی. شامل نقاط داده‌ای است که باید در دومین دایره یا نوار رسم شوند. فقط‌خواندنی [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**باز می‌گرداند:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

اندازهٔ سوراخ در یک نمودار دونات را مشخص می‌کند (می‌تواند بین 10 تا 90 درصد از اندازهٔ ناحیهٔ رسم باشد). قابل خواندن/نوشتن byte.

**باز می‌گرداند:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

اندازهٔ سوراخ در یک نمودار دونات را مشخص می‌کند (می‌تواند بین 10 تا 90 درصد از اندازهٔ ناحیهٔ رسم باشد). قابل خواندن/نوشتن byte.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

ضریب مقیاس برای نمودار حبابی را مشخص می‌کند (می‌تواند بین 0 تا 300 درصد از اندازهٔ پیش‌فرض باشد). قابل خواندن/نوشتن int.

**باز می‌گرداند:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

ضریب مقیاس برای نمودار حبابی را مشخص می‌کند (می‌تواند بین 0 تا 300 درصد از اندازهٔ پیش‌فرض باشد). قابل خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

قالب HiLowLines را تعیین می‌کند. HiLowLines برای انواع نمودارهای HiLowClose، OpenHiLowClose، VolumeHiLowClose و VolumeOpenHiLowClose اعمال می‌شود.

**باز می‌گرداند:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

نحوه نمایش مقادیر اندازهٔ حباب‌ها در نمودار حبابی را تعیین می‌کند. قابل خواندن/نوشتن [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**باز می‌گرداند:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

نحوه نمایش مقادیر اندازهٔ حباب‌ها در نمودار حبابی را تعیین می‌کند. قابل خواندن/نوشتن [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |