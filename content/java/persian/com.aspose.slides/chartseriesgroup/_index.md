---
title: ChartSeriesGroup
second_title: Aspose.Slides برای مرجع API جاوا
description: نمایانگر گروهی از سری‌ها.
type: docs
url: /fa/com.aspose.slides/chartseriesgroup/
---
**وراثت:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup), com.aspose.slides.IDOMObject
```
public class ChartSeriesGroup implements IChartSeriesGroup, IDOMObject
```

نمایشگر گروهی از سری‌ها.

--------------------

1) خلاصه و ملاحظات را برای کلاس ChartSeriesGroupCollection و شمارش CombinableSeriesTypesGroup مشاهده کنید. 2) گروهی از سری‌ها شامل برخی ویژگی‌های سری است که برای هر سری در گروه مشترک است ("ویژگی‌های گروه سری"). "ویژگی‌های گروه سری" در کلاس ChartSeriesGroup خواندنی/نوشتنی است. هر یک از "ویژگی‌های گروه سری" می‌تواند یک پیش‌نمایش فقط-خواندنی در کلاس ChartSeries داشته باشد.
## متدها

| متد | توضیح |
| --- | --- |
| [getType()](#getType--) | یک نوع از این گروه سری را برمی‌گرداند. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | نشان می‌دهد که آیا سری‌های این گروه روی محور ثانویه رسم می‌شوند یا نه. |
| [getSeries()](#getSeries--) | یک مجموعه از سری‌ها را برمی‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | عنصر در اندیس مشخص شده را دریافت می‌کند. |
| [getUpDownBars()](#getUpDownBars--) | دسترسی به نوارهای بالا/پایین نمودار خطی یا سهام را فراهم می‌کند. |
| [getGapWidth()](#getGapWidth--) | فاصله بین خوشه‌های میله یا ستون را به عنوان درصدی از عرض میله یا ستون دریافت یا تنظیم می‌کند. |
| [setGapWidth(int value)](#setGapWidth-int-) | فاصله بین خوشه‌های میله یا ستون را به عنوان درصدی از عرض میله یا ستون دریافت یا تنظیم می‌کند. |
| [getGapDepth()](#getGapDepth--) | فاصله بین سری‌های داده در یک نمودار 3بعدی را به عنوان درصدی از عرض نشانگر دریافت یا تنظیم می‌کند. |
| [setGapDepth(int value)](#setGapDepth-int-) | فاصله بین سری‌های داده در یک نمودار 3بعدی را به عنوان درصدی از عرض نشانگر دریافت یا تنظیم می‌کند. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | زاویهٔ اولین برش نمودار دایره یا دونات را به درجه دریافت یا تنظیم می‌کند (ساعتگرد از بالا، از 0 تا 360 درجه). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | زاویهٔ اولین برش نمودار دایره یا دونات را به درجه دریافت یا تنظیم می‌کند (ساعتگرد از بالا، از 0 تا 360 درجه). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | اندازهٔ سوراخ در نمودار دونات را مشخص می‌کند (می‌تواند بین 0 تا 90 درصد از اندازهٔ ناحیهٔ طرح باشد). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | اندازهٔ سوراخ در نمودار دونات را مشخص می‌کند (می‌تواند بین 0 تا 90 درصد از اندازهٔ ناحیهٔ طرح باشد). |
| [getOverlap()](#getOverlap--) | مشخص می‌کند که میله‌ها و ستون‌ها تا چه حد بر روی نمودارهای دو-بعدی همپوشانی داشته باشند، به صورت درصد (از -100٪ تا 100٪). |
| [setOverlap(byte value)](#setOverlap-byte-) | مشخص می‌کند که میله‌ها و ستون‌ها تا چه حد بر روی نمودارهای دو-بعدی همپوشانی داشته باشند، به صورت درصد (از -100٪ تا 100٪). |
| [getSecondPieSize()](#getSecondPieSize--) | اندازهٔ دومین دایره یا میله در نمودار pie-of-pie یا bar-of-pie را به عنوان درصدی از اندازهٔ اولین دایره مشخص می‌کند (می‌تواند بین 5 تا 200 درصد باشد). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | اندازهٔ دومین دایره یا میله در نمودار pie-of-pie یا bar-of-pie را به عنوان درصدی از اندازهٔ اولین دایره مشخص می‌کند (می‌تواند بین 5 تا 200 درصد باشد). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | نحوهٔ نمایش مقادیر اندازهٔ حباب در نمودار حبابی را مشخص می‌کند. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | نحوهٔ نمایش مقادیر اندازهٔ حباب در نمودار حبابی را مشخص می‌کند. |
| [getPieSplitPosition()](#getPieSplitPosition--) | مقداری را که برای تعیین نقاط داده در دومین دایره یا میله در نمودار pie-of-pie یا bar-of-pie استفاده می‌شود، مشخص می‌کند. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | مقداری را که برای تعیین نقاط داده در دومین دایره یا میله در نمودار pie-of-pie یا bar-of-pie استفاده می‌شود، مشخص می‌کند. |
| [getPieSplitBy()](#getPieSplitBy--) | نحوهٔ تعیین نقاط داده در دومین دایره یا میله در نمودار pie-of-pie یا bar-of-pie را مشخص می‌کند. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | نحوهٔ تعیین نقاط داده در دومین دایره یا میله در نمودار pie-of-pie یا bar-of-pie را مشخص می‌کند. |
| [isColorVaried()](#isColorVaried--) | مشخص می‌کند که هر نشانگر داده در سری رنگ متفاوتی دارد. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | مشخص می‌کند که هر نشانگر داده در سری رنگ متفاوتی دارد. |
| [hasSeriesLines()](#hasSeriesLines--) | درست اگر نمودار خطوط سری داشته باشد. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | درست اگر نمودار خطوط سری داشته باشد. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | قالب HiLowLines را مشخص می‌کند. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | ضریب مقیاس برای نمودار حبابی را مشخص می‌کند (می‌تواند بین 0 تا 300 درصد از اندازهٔ پیش‌فرض باشد). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | ضریب مقیاس برای نمودار حبابی را مشخص می‌کند (می‌تواند بین 0 تا 300 درصد از اندازهٔ پیش‌فرض باشد). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | اطلاعات تقسیم سفارشی برای نمودار pie-of-pie یا bar-of-pie با تقسیم سفارشی. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | نمودار والد را برمی‌گرداند. |
| [getSlide()](#getSlide--) | اسلاید والد یک FillFormat را برمی‌گرداند. |
| [getPresentation()](#getPresentation--) | ارائه والد یک FillFormat را برمی‌گرداند. |

### getType() {#getType--}
```
public final int getType()
```

یک نوع از این گروه سری را برمی‌گرداند. فقط-خواندنی [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**بازگشت:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

نشان می‌دهد که آیا سری‌های این گروه روی محور ثانویه رسم می‌شوند یا نه. فقط-خواندنی boolean.

**بازگشت:**
boolean

### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

یک مجموعه از سری‌ها را برمی‌گرداند. فقط-خواندنی [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**بازگشت:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

عنصر در اندیس مشخص شده را دریافت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```

دسترسی به نوارهای بالا/پایین نمودار خطی یا سهام را فراهم می‌کند. فقط-خواندنی [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**بازگشت:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

فاصله بین خوشه‌های میله یا ستون را به عنوان درصدی از عرض میله یا ستون دریافت یا تنظیم می‌کند. مقدار باید بین 0 و 500 باشد. خواندن/نوشتن int.

--------------------

این ویژگی برای سری‌های از انواع زیر اعمال می‌شود: زیرنوع‌های Bar (همچنین به متد [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) مراجعه کنید)، زیرنوع‌های Column (همچنین به متد [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) مراجعه کنید)، [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie)، [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie)، [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker)، [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel)، [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram)، [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**بازگشت:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

فاصله بین خوشه‌های میله یا ستون را به عنوان درصدی از عرض میله یا ستون دریافت یا تنظیم می‌کند. مقدار باید بین 0 و 500 باشد. خواندن/نوشتن int.

--------------------

این ویژگی برای سری‌های از انواع زیر اعمال می‌شود: زیرنوع‌های Bar (همچنین به متد [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) مراجعه کنید)، زیرنوع‌های Column (همچنین به متد [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) مراجعه کنید)، [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie)، [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie)، [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker)، [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel)، [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram)، [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

فاصله بین سری‌های داده در یک نمودار 3بعدی را به عنوان درصدی از عرض نشانگر دریافت یا تنظیم می‌کند. مقدار باید بین 0 و 500 باشد. خواندن/نوشتن int.

--------------------

این ویژگی برای سری‌های از انواع زیر اعمال می‌شود: زیرنوع‌های 3D Bar و Column (همچنین به متد [ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-) مراجعه کنید)، [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D)، [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D)، [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D)، [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**بازگشت:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

فاصله بین سری‌های داده در یک نمودار 3بعدی را به عنوان درصدی از عرض نشانگر دریافت یا تنظیم می‌کند. مقدار باید بین 0 و 500 باشد. خواندن/نوشتن int.

--------------------

این ویژگی برای سری‌های از انواع زیر اعمال می‌شود: زیرنوع‌های 3D Bar و Column (همچنین به متد [ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-) مراجعه کنید)، [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D)، [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D)، [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D)، [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

زاویهٔ اولین برش نمودار دایره یا دونات را به درجه دریافت یا تنظیم می‌کند (ساعتگرد از بالا، از 0 تا 360 درجه). خواندن/نوشتن int.

**بازگشت:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

زاویهٔ اولین برش نمودار دایره یا دونات را به درجه دریافت یا تنظیم می‌کند (ساعتگرد از بالا، از 0 تا 360 درجه). خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

اندازهٔ سوراخ در نمودار دونات را مشخص می‌کند (می‌تواند بین 0 تا 90 درصد از اندازهٔ ناحیهٔ طرح باشد). خواندن/نوشتن byte.

**بازگشت:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

اندازهٔ سوراخ در نمودار دونات را مشخص می‌کند (می‌تواند بین 0 تا 90 درصد از اندازهٔ ناحیهٔ طرح باشد). خواندن/نوشتن byte.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

مشخص می‌کند که میله‌ها و ستون‌ها تا چه حد بر روی نمودارهای دو-بعدی همپوشانی داشته باشند، به صورت درصد (از -100٪ تا 100٪). - -100٪: حداکثر فاصله (میله‌ها کاملاً جدا هستند). - 0٪: میله‌ها بدون همپوشانی یا فاصله کنار هم قرار می‌گیرند. - 100٪: حداکثر همپوشانی (میله‌ها کاملاً روی هم قرار می‌گیرند). این ویژگی خواندن/نوشتن byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // تنظیم همپوشانی به 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازگشت:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```

مشخص می‌کند که میله‌ها و ستون‌ها تا چه حد بر روی نمودارهای دو-بعدی همپوشانی داشته باشند، به صورت درصد (از -100٪ تا 100٪). - -100٪: حداکثر فاصله (میله‌ها کاملاً جدا هستند). - 0٪: میله‌ها بدون همپوشانی یا فاصله کنار هم قرار می‌گیرند. - 100٪: حداکثر همپوشانی (میله‌ها کاملاً روی هم قرار می‌گیرند). این ویژگی خواندن/نوشتن byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // تنظیم همپوشانی به 55%
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
public final int getSecondPieSize()
```

اندازهٔ دومین دایره یا میله در نمودار pie-of-pie یا bar-of-pie را به عنوان درصدی از اندازهٔ اولین دایره مشخص می‌کند (می‌تواند بین 5 تا 200 درصد باشد). خواندن/نوشتن int.

**بازگشت:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

اندازهٔ دومین دایره یا میله در نمودار pie-of-pie یا bar-of-pie را به عنوان درصدی از اندازهٔ اولین دایره مشخص می‌کند (می‌تواند بین 5 تا 200 درصد باشد). خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

نحوهٔ نمایش مقادیر اندازهٔ حباب در نمودار حبابی را مشخص می‌کند. خواندن/نوشتن [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**بازگشت:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

نحوهٔ نمایش مقادیر اندازهٔ حباب در نمودار حبابی را مشخص می‌کند. خواندن/نوشتن [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

مقداری را که برای تعیین نقاط داده در دومین دایره یا میله در نمودار pie-of-pie یا bar-of-pie استفاده می‌شود، مشخص می‌کند. همراه با ویژگی PieSplitBy استفاده می‌شود. خواندن/نوشتن double.

**بازگشت:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

مقداری را که برای تعیین نقاط داده در دومین دایره یا میله در نمودار pie-of-pie یا bar-of-pie استفاده می‌شود، مشخص می‌کند. همراه با ویژگی PieSplitBy استفاده می‌شود. خواندن/نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

نحوهٔ تعیین نقاط داده در دومین دایره یا میله در نمودار pie-of-pie یا bar-of-pie را مشخص می‌کند. خواندن/نوشتن [PieSplitType](../../com.aspose.slides/piesplittype).

**بازگشت:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

نحوهٔ تعیین نقاط داده در دومین دایره یا میله در نمودار pie-of-pie یا bar-of-pie را مشخص می‌کند. خواندن/نوشتن [PieSplitType](../../com.aspose.slides/piesplittype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

مشخص می‌کند که هر نشانگر داده در سری رنگ متفاوتی دارد. خواندن/نوشتن boolean.

**بازگشت:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

مشخص می‌کند که هر نشانگر داده در سری رنگ متفاوتی دارد. خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

درست اگر نمودار خطوط سری داشته باشد. برای نمودارهای stacked bar و OfPie اعمال می‌شود. خواندن/نوشتن boolean.

**بازگشت:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

درست اگر نمودار خطوط سری داشته باشد. برای نمودارهای stacked bar و OfPie اعمال می‌شود. خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

قالب HiLowLines را مشخص می‌کند. HiLowLines همراه با انواع نمودار HiLowClose، OpenHiLowClose، VolumeHiLowClose و VolumeOpenHiLowClose اعمال می‌شود.

**بازگشت:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

ضریب مقیاس برای نمودار حبابی را مشخص می‌کند (می‌تواند بین 0 تا 300 درصد از اندازهٔ پیش‌فرض باشد). خواندن/نوشتن int.

**بازگشت:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

ضریب مقیاس برای نمودار حبابی را مشخص می‌کند (می‌تواند بین 0 تا 300 درصد از اندازهٔ پیش‌فرض باشد). خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

اطلاعات تقسیم سفارشی برای نمودار pie-of-pie یا bar-of-pie با تقسیم سفارشی. شامل نقاط داده‌ای است که باید در دومین دایره یا میله در نمودار pie-of-pie یا bar-of-pie رسم شوند. فقط-خواندنی [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**بازگشت:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را برمی‌گرداند. فقط-خواندنی IDOMObject.

**بازگشت:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

نمودار والد را برمی‌گرداند. فقط-خواندنی [IChart](../../com.aspose.slides/ichart).

**بازگشت:**
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

اسلاید والد یک FillFormat را برمی‌گرداند. فقط-خواندنی [BaseSlide](../../com.aspose.slides/baseslide).

**بازگشت:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ارائه والد یک FillFormat را برمی‌گرداند. فقط-خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**بازگشت:**
[IPresentation](../../com.aspose.slides/ipresentation)