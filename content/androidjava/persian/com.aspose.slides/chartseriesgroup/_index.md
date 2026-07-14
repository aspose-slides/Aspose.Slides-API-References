---
title: ChartSeriesGroup
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر گروهی از سری‌ها.
type: docs
url: /fa/com.aspose.slides/chartseriesgroup/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup), com.aspose.slides.IDOMObject
```
public class ChartSeriesGroup implements IChartSeriesGroup, IDOMObject
```

نمایندهٔ گروهی از سری‌ها.

--------------------

1) خلاصه و توضیحات کلاس ChartSeriesGroupCollection و enum CombinableSeriesTypesGroup را ببینید. 2) گروهی از سری‌ها دارای برخی ویژگی‌های سری است که برای هر سری در گروه مشترک است ("ویژگی‌های گروه سری"). "ویژگی‌های گروه سری" در کلاس ChartSeriesGroup قابل‌خواندن/نوشتن است. هر یک از "ویژگی‌های گروه سری" می‌تواند یک تصویر فقط-خواندنی در کلاس ChartSeries داشته باشد.
## متدها

| متد | توضیح |
| --- | --- |
| [getType()](#getType--) | نوع این گروه سری را بازمی‌گرداند. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | نشان می‌دهد آیا سری‌های این گروه بر روی محور ثانویه رسم می‌شوند. |
| [getSeries()](#getSeries--) | یک مجموعه از سری‌ها را بازمی‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | عنصر را در اندیس مشخص‌شده دریافت می‌کند. |
| [getUpDownBars()](#getUpDownBars--) | دسترسی به نوارهای بالا/پایین نمودار خط یا نمودار سهام را فراهم می‌کند. |
| [getGapWidth()](#getGapWidth--) | فضای بین خوشه‌های نوار یا ستون را به‌عنوان درصدی از عرض نوار یا ستون مشخص می‌کند. |
| [setGapWidth(int value)](#setGapWidth-int-) | فضای بین خوشه‌های نوار یا ستون را به‌عنوان درصدی از عرض نوار یا ستون مشخص می‌کند. |
| [getGapDepth()](#getGapDepth--) | فاصله را به‌عنوان درصدی از عرض علامت، بین سری‌های داده در نمودار سه‌بعدی بازمی‌گرداند یا تنظیم می‌کند. |
| [setGapDepth(int value)](#setGapDepth-int-) | فاصله را به‌عنوان درصدی از عرض علامت، بین سری‌های داده در نمودار سه‌بعدی بازمی‌گرداند یا تنظیم می‌کند. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | زاویهٔ اولین برش نمودار پای یا دونات را به درجه (در جهت ساعتگرد از بالا، از 0 تا 360 درجه) دریافت یا تنظیم می‌کند. |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | زاویهٔ اولین برش نمودار پای یا دونات را به درجه (در جهت ساعتگرد از بالا، از 0 تا 360 درجه) دریافت یا تنظیم می‌کند. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | اندازهٔ حفره در نمودار دونات را مشخص می‌کند (می‌تواند بین 0 و 90 درصد از اندازهٔ ناحیهٔ نمودار باشد). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | اندازهٔ حفره در نمودار دونات را مشخص می‌کند (می‌تواند بین 0 و 90 درصد از اندازهٔ ناحیهٔ نمودار باشد). |
| [getOverlap()](#getOverlap--) | مقدار همپوشانی نوارها و ستون‌ها در نمودارهای دو‌بعدی را به‌عنوان درصد (از -100٪ تا 100٪) مشخص می‌کند. |
| [setOverlap(byte value)](#setOverlap-byte-) | مقدار همپوشانی نوارها و ستون‌ها در نمودارهای دو‌بعدی را به‌عنوان درصد (از -100٪ تا 100٪) مشخص می‌کند. |
| [getSecondPieSize()](#getSecondPieSize--) | اندازهٔ دومین پای یا نوار در نمودار پای-از-پای یا نوار-از-پای را به‌عنوان درصدی از اندازهٔ اولین پای مشخص می‌کند (می‌تواند بین 5 تا 200 درصد باشد). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | اندازهٔ دومین پای یا نوار در نمودار پای-از-پای یا نوار-از-پای را به‌عنوان درصدی از اندازهٔ اولین پای مشخص می‌کند (می‌تواند بین 5 تا 200 درصد باشد). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | نحوهٔ نمایش مقادیر اندازهٔ حباب در نمودار حبابی را مشخص می‌کند. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | نحوهٔ نمایش مقادیر اندازهٔ حباب در نمودار حبابی را مشخص می‌کند. |
| [getPieSplitPosition()](#getPieSplitPosition--) | مقداری را که برای تعیین نقاط داده‌ای که در دومین پای یا نوار در نمودار پای-از-پای یا نوار-از-پای هستند، استفاده می‌شود، مشخص می‌کند. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | مقداری را که برای تعیین نقاط داده‌ای که در دومین پای یا نوار در نمودار پای-از-پای یا نوار-از-پای هستند، استفاده می‌شود، مشخص می‌کند. |
| [getPieSplitBy()](#getPieSplitBy--) | نحوه تعیین نقاط داده‌ای که در دومین پای یا نوار در نمودار پای-از-پای یا نوار-از-پای قرار دارند، را مشخص می‌کند. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | نحوه تعیین نقاط داده‌ای که در دومین پای یا نوار در نمودار پای-از-پای یا نوار-از-پای قرار دارند، را مشخص می‌کند. |
| [isColorVaried()](#isColorVaried--) | مشخص می‌کند که هر نشانگر داده در سری رنگ متفاوتی دارد. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | مشخص می‌کند که هر نشانگر داده در سری رنگ متفاوتی دارد. |
| [hasSeriesLines()](#hasSeriesLines--) | True اگر نمودار خطوط سری دارد. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | True اگر نمودار خطوط سری دارد. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | قالب HiLowLines را مشخص می‌کند. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | عامل مقیاس برای نمودار حبابی را مشخص می‌کند (می‌تواند بین 0 و 300 درصد از اندازهٔ پیش‌فرض باشد). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | عامل مقیاس برای نمودار حبابی را مشخص می‌کند (می‌تواند بین 0 و 300 درصد از اندازهٔ پیش‌فرض باشد). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | اطلاعات تقسیم سفارشی برای نمودار پای-از-پای یا نوار-از-پای با تقسیم سفارشی. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | نمودار والد را بازمی‌گرداند. |
| [getSlide()](#getSlide--) | اسلاید والد یک FillFormat را بازمی‌گرداند. |
| [getPresentation()](#getPresentation--) | ارائهٔ والد یک FillFormat را بازمی‌گرداند. |

### getType() {#getType--}
```
public final int getType()
```

نوع این گروه سری را بازمی‌گرداند. فقط-خواندنی [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**بازگرداندن:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

نشان می‌دهد آیا سری‌های این گروه بر روی محور ثانویه رسم می‌شوند. فقط-خواندنی boolean.

**بازگرداندن:**
boolean

### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

یک مجموعه از سری‌ها را بازمی‌گرداند. فقط-خواندنی [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**بازگرداندن:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

عنصر را در اندیس مشخص‌شده دریافت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگرداندن:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```

دسترسی به نوارهای بالا/پایین نمودار خط یا نمودار سهام را فراهم می‌کند. فقط-خواندنی [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**بازگرداندن:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

فضای بین خوشه‌های نوار یا ستون را به‌عنوان درصدی از عرض نوار یا ستون مشخص می‌کند. قابل‌خواندن/نوشتن int.

**بازگرداندن:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

فضای بین خوشه‌های نوار یا ستون را به‌عنوان درصدی از عرض نوار یا ستون مشخص می‌کند. قابل‌خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

فاصله را به‌عنوان درصدی از عرض علامت، بین سری‌های داده در نمودار سه‌بعدی بازمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/نوشتن int.

**بازگرداندن:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

فاصله را به‌عنوان درصدی از عرض علامت، بین سری‌های داده در نمودار سه‌بعدی بازمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

زاویهٔ اولین برش نمودار پای یا دونات را به درجه (در جهت ساعتگرد از بالا، از 0 تا 360 درجه) دریافت یا تنظیم می‌کند. قابل‌خواندن/نوشتن int.

**بازگرداندن:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

زاویهٔ اولین برش نمودار پای یا دونات را به درجه (در جهت ساعتگرد از بالا، از 0 تا 360 درجه) دریافت یا تنظیم می‌کند. قابل‌خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

اندازهٔ حفره در نمودار دونات را مشخص می‌کند (می‌تواند بین 0 و 90 درصد از اندازهٔ ناحیهٔ نمودار باشد). قابل‌خواندن/نوشتن byte.

**بازگرداندن:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

اندازهٔ حفره در نمودار دونات را مشخص می‌کند (می‌تواند بین 0 و 90 درصد از اندازهٔ ناحیهٔ نمودار باشد). قابل‌خواندن/نوشتن byte.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

مقدار همپوشانی نوارها و ستون‌ها در نمودارهای دو‌بعدی را به‌عنوان درصد (از -100% تا 100%) مشخص می‌کند. -100%: بیشترین فاصله (نوارها کاملا جدا هستند). -0%: نوارها بدون همپوشانی یا فاصله کنار هم قرار می‌گیرند. 100%: بیشترین همپوشانی (نوارها کاملا روی یکدیگر قرار می‌گیرند). این ویژگی قابل‌خواندن/نوشتن byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Set overlap to 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازگرداندن:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```

مقدار همپوشانی نوارها و ستون‌ها در نمودارهای دو‌بعدی را به‌عنوان درصد (از -100% تا 100%) مشخص می‌کند. -100%: بیشترین فاصله (نوارها کاملا جدا هستند). -0%: نوارها بدون همپوشانی یا فاصله کنار هم قرار می‌گیرند. 100%: بیشترین همپوشانی (نوارها کاملا روی یکدیگر قرار می‌گیرند). این ویژگی قابل‌خواندن/نوشتن byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // همپوشانی را به 55% تنظیم کنید
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

اندازهٔ دومین پای یا نوار در نمودار پای-از-پای یا نوار-از-پای را به‌عنوان درصدی از اندازهٔ اولین پای مشخص می‌کند (می‌تواند بین 5 تا 200 درصد باشد). قابل‌خواندن/نوشتن int.

**بازگرداندن:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

اندازهٔ دومین پای یا نوار در نمودار پای-از-پای یا نوار-از-پای را به‌عنوان درصدی از اندازهٔ اولین پای مشخص می‌کند (می‌تواند بین 5 تا 200 درصد باشد). قابل‌خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

نحوهٔ نمایش مقادیر اندازهٔ حباب در نمودار حبابی را مشخص می‌کند. قابل‌خواندن/نوشتن [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**بازگرداندن:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

نحوهٔ نمایش مقادیر اندازهٔ حباب در نمودار حبابی را مشخص می‌کند. قابل‌خواندن/نوشتن [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

مقداری را که برای تعیین نقاط داده‌ای که در دومین پای یا نوار در نمودار پای-از-پای یا نوار-از-پای هستند، استفاده می‌شود، مشخص می‌کند. همراه با ویژگی PieSplitBy استفاده می‌شود. قابل‌خواندن/نوشتن double.

**بازگرداندن:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

مقداری را که برای تعیین نقاط داده‌ای که در دومین پای یا نوار در نمودار پای-از-پای یا نوار-از-پای هستند، استفاده می‌شود، مشخص می‌کند. همراه با ویژگی PieSplitBy استفاده می‌شود. قابل‌خواندن/نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

نحوهٔ تعیین نقاط داده‌ای که در دومین پای یا نوار در نمودار پای-از-پای یا نوار-از-پای قرار دارند، را مشخص می‌کند. قابل‌خواندن/نوشتن [PieSplitType](../../com.aspose.slides/piesplittype).

**بازگرداندن:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

نحوهٔ تعیین نقاط داده‌ای که در دومین پای یا نوار در نمودار پای-از-پای یا نوار-از-پای قرار دارند، را مشخص می‌کند. قابل‌خواندن/نوشتن [PieSplitType](../../com.aspose.slides/piesplittype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

مشخص می‌کند که هر نشانگر داده در سری رنگ متفاوتی دارد. قابل‌خواندن/نوشتن boolean.

**بازگرداندن:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

مشخص می‌کند که هر نشانگر داده در سری رنگ متفاوتی دارد. قابل‌خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

True اگر نمودار خطوط سری دارد. برای نمودارهای بار پشته‌ای و OfPie اعمال می‌شود. قابل‌خواندن/نوشتن boolean.

**بازگرداندن:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

True اگر نمودار خطوط سری دارد. برای نمودارهای بار پشته‌ای و OfPie اعمال می‌شود. قابل‌خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

قالب HiLowLines را مشخص می‌کند. HiLowLines با انواع نمودار HiLowClose، OpenHiLowClose، VolumeHiLowClose و VolumeOpenHiLowClose اعمال می‌شود.

**بازگرداندن:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

عامل مقیاس برای نمودار حبابی را مشخص می‌کند (می‌تواند بین 0 و 300 درصد از اندازهٔ پیش‌فرض باشد). قابل‌خواندن/نوشتن int.

**بازگرداندن:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

عامل مقیاس برای نمودار حبابی را مشخص می‌کند (می‌تواند بین 0 و 300 درصد از اندازهٔ پیش‌فرض باشد). قابل‌خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

اطلاعات تقسیم سفارشی برای نمودار پای-از-پای یا نوار-از-پای با تقسیم سفارشی. شامل نقاط داده‌ای است که باید در دومین پای یا نوار در نمودار پای-از-پای یا نوار-از-پای رسم شوند. فقط-خواندنی [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**بازگرداندن:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را بازمی‌گرداند. فقط-خواندنی IDOMObject.

**بازگرداندن:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

نمودار والد را بازمی‌گرداند. فقط-خواندنی [IChart](../../com.aspose.slides/ichart).

**بازگرداندن:**
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

اسلاید والد یک FillFormat را بازمی‌گرداند. فقط-خواندنی [BaseSlide](../../com.aspose.slides/baseslide).

**بازگرداندن:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ارائهٔ والد یک FillFormat را بازمی‌گرداند. فقط-خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**بازگرداندن:**
[IPresentation](../../com.aspose.slides/ipresentation)