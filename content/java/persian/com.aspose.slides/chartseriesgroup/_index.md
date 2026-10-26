---
title: ChartSeriesGroup
second_title: مرجع API Aspose.Slides برای جاوا
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

نمایانگر گروهی از سری‌ها.

--------------------

1) خلاصه و توضیحات مربوط به کلاس ChartSeriesGroupCollection و enum CombinableSeriesTypesGroup را ببینید. 2) گروهی از سری‌ها شامل برخی ویژگی‌های سری است که برای هر سری در گروه مشترک است ("series group properties"). ویژگی‌های "series group properties" در کلاس ChartSeriesGroup قابل خواندن/نوشتن است. هر یک از "series group properties" می‌تواند یک نسخه فقط-خواندنی در کلاس ChartSeries داشته باشد.

## متدها

| متد | توضیح |
| --- | --- |
| [getType()](#getType--) | یک نوع از این گروه سری را برمی‌گرداند. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | نشان می‌دهد آیا سری‌های این گروه بر محور ثانویه رسم می‌شوند. |
| [getSeries()](#getSeries--) | یک مجموعه از سری‌ها را برمی‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | عنصر در ایندکس مشخص‌شده را دریافت می‌کند. |
| [getUpDownBars()](#getUpDownBars--) | دسترسی به نوارهای بالا/پایین نمودار Line یا Stock را فراهم می‌کند. |
| [getGapWidth()](#getGapWidth--) | فضای بین خوشه‌های نوار یا ستون را به‌عنوان درصدی از عرض نوار یا ستون مشخص می‌کند. |
| [setGapWidth(int value)](#setGapWidth-int-) | فضای بین خوشه‌های نوار یا ستون را به‌عنوان درصدی از عرض نورد یا ستون مشخص می‌کند. |
| [getGapDepth()](#getGapDepth--) | فاصله، به‌صورت درصدی از عرض نشانگر، بین سری‌های داده در نمودار سه‌بعدی را برمی‌گرداند یا تنظیم می‌کند. |
| [setGapDepth(int value)](#setGapDepth-int-) | فاصله، به‌صورت درصدی از عرض نشانگر، بین سری‌های داده در نمودار سه‌بعدی را برمی‌گرداند یا تنظیم می‌کند. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | زاویه اولین برش کیک یا دونات را به‌صورت درجه (از ۰ تا ۳۶۰ درجه، ساعتگرد از بالا) دریافت یا تنظیم می‌کند. |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | زاویه اولین برش کیک یا دونات را به‌صورت درجه (از ۰ تا ۳۶۰ درجه، ساعتگرد از بالا) دریافت یا تنظیم می‌کند. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | اندازه سوراخ در نمودار دونات را مشخص می‌کند (می‌تواند بین ۰ تا ۹۰ درصد از اندازه ناحیه‌نقشه باشد). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | اندازه سوراخ در نمودار دونات را مشخص می‌کند (می‌تواند بین ۰ تا ۹۰ درصد از اندازه ناحیه‌نقشه باشد). |
| [getOverlap()](#getOverlap--) | درصد همپوشانی نوارها و ستون‌ها در نمودارهای دو‌بعدی را مشخص می‌کند (از -۱۰۰٪ تا ۱۰۰٪). |
| [setOverlap(byte value)](#setOverlap-byte-) | درصد همپوشانی نوارها و ستون‌ها در نمودارهای دو‌بعدی را مشخص می‌کند (از -۱۰۰٪ تا ۱۰۰٪). |
| [getSecondPieSize()](#getSecondPieSize--) | اندازه دومین کیک یا نوار در نمودار pie-of-pie یا bar-of-pie را به‌صورت درصدی از اندازه کیک اول مشخص می‌کند (می‌تواند بین ۵ تا ۲۰۰ درصد باشد). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | اندازه دومین کیک یا نوار در نمودار pie-of-pie یا bar-of-pie را به‌صورت درصدی از اندازه کیک اول مشخص می‌کند (می‌تواند بین ۵ تا ۲۰۰ درصد باشد). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | نحوه نمایش مقادیر اندازه حباب‌ها را در نمودار حبابی مشخص می‌کند. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | نحوه نمایش مقادیر اندازه حباب‌ها را در نمودار حبابی مشخص می‌کند. |
| [getPieSplitPosition()](#getPieSplitPosition--) | مقداری را تعیین می‌کند که برای شناسایی نقاط داده‌ای که در کیک یا نوار دوم در نمودار pie-of-pie یا bar-of-pie قرار می‌گیرند، استفاده می‌شود. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | مقداری را تعیین می‌کند که برای شناسایی نقاط داده‌ای که در کیک یا نوار دوم در نمودار pie-of-pie یا bar-of-pie قرار می‌گیرند، استفاده می‌شود. |
| [getPieSplitBy()](#getPieSplitBy--) | نحوه تعیین نقاط داده‌ای که در کیک یا نوار دوم در نمودار pie-of-pie یا bar-of-pie قرار می‌گیرند را مشخص می‌کند. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | نحوه تعیین نقاط داده‌ای که در کیک یا نوار دوم در نمودار pie-of-pie یا bar-of-pie قرار می‌گیرند را مشخص می‌کند. |
| [isColorVaried()](#isColorVaried--) | مشخص می‌کند که هر مارکر داده در سری دارای رنگ متفاوتی باشد. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | مشخص می‌کند که هر مارکر داده در سری دارای رنگ متفاوتی باشد. |
| [hasSeriesLines()](#hasSeriesLines--) | اگر نمودار خطوط سری داشته باشد مقدار true برمی‌گرداند. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | اگر نمودار خطوط سری داشته باشد مقدار true برمی‌گرداند. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | قالب HiLowLines را تعیین می‌کند. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | عامل مقیاس برای نمودار حبابی را تعیین می‌کند (می‌تواند بین ۰ تا ۳۰۰ درصد از اندازه پیش‌فرض باشد). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | عامل مقیاس برای نمودار حبابی را تعیین می‌کند (می‌تواند بین ۰ تا ۳۰۰ درصد از اندازه پیش‌فرض باشد). |
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

**برگشت:**  
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

نشان می‌دهد آیا سری‌های این گروه بر محور ثانویه رسم می‌شوند. فقط-خواندنی boolean.

**برگشت:**  
boolean

### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

یک مجموعه از سری‌ها را برمی‌گرداند. فقط-خواندنی [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**برگشت:**  
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

عنصر در ایندکس مشخص‌شده را دریافت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**برگشت:**  
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```

دستیابی به نوارهای بالا/پایین نمودار Line یا Stock را فراهم می‌کند. فقط-خواندنی [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**برگشت:**  
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

فضای بین خوشه‌های نوار یا ستون را به‌عنوان درصدی از عرض نورد یا ستون مشخص می‌کند. خواندن/نوشتن int.

**برگشت:**  
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

فضای بین خوشه‌های نوار یا ستون را به‌عنوان درصدی از عرض نورد یا ستون مشخص می‌کند. خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

فاصله، به‌صورت درصدی از عرض نشانگر، بین سری‌های داده در نمودار سه‌بعدی را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن int.

**برگشت:**  
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

فاصله، به‌صورت درصدی از عرض نشانگر، بین سری‌های داده در نمودار سه‌بعدی را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

زاویه اولین برش کیک یا دونات را به‌صورت درجه (از ۰ تا ۳۶۰ درجه، ساعتگرد از بالا) دریافت یا تنظیم می‌کند. خواندن/نوشتن int.

**برگشت:**  
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

زاویه اولین برش کیک یا دونات را به‌صورت درجه (از ۰ تا ۳۶۰ درجه، ساعتگرد از بالا) دریافت یا تنظیم می‌کند. خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

اندازه سوراخ در نمودار دونات را مشخص می‌کند (می‌تواند بین ۰ تا ۹۰ درصد از اندازه ناحیه‌نقشه باشد). خواندن/نوشتن byte.

**برگشت:**  
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

اندازه سوراخ در نمودار دونات را مشخص می‌کند (می‌تواند بین ۰ تا ۹۰ درصد از اندازه ناحیه‌نقشه باشد). خواندن/نوشتن byte.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

مشخص می‌کند که نوارها و ستون‌ها در نمودارهای دو‌بعدی با چه درصدی همپوشانی داشته باشند (از -۱۰۰٪ تا ۱۰۰٪). - -۱۰۰٪: بیشترین فاصله (نوارها کاملاً جدا هستند). - ۰٪: نوارها بدون همپوشانی یا فاصله کنار هم قرار می‌گیرند. - ۱۰۰٪: بیشترین همپوشانی (نوارها کاملاً روی هم هستند). این ویژگی خواندن/نوشتن byte.

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


**برگشت:**  
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```

مشخص می‌کند که نوارها و ستون‌ها در نمودارهای دو‌بعدی با چه درصدی همپوشانی داشته باشند (از -۱۰۰٪ تا ۱۰۰٪). - -۱۰۰٪: بیشترین فاصله (نوارها کاملاً جدا هستند). - ۰٪: نوارها بدون همپوشانی یا فاصله کنار هم قرار می‌گیرند. - ۱۰۰٪: بیشترین همپوشانی (نوارها کاملاً روی هم هستند). این ویژگی خواندن/نوشتن byte.

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

اندازه دومین کیک یا نوار در نمودار pie-of-pie یا bar-of-pie را به‌صورت درصدی از اندازه کیک اول مشخص می‌کند (می‌تواند بین ۵ تا ۲۰۰ درصد باشد). خواندن/نوشتن int.

**برگشت:**  
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

اندازه دومین کیک یا نوار در نمودار pie-of-pie یا bar-of-pie را به‌صورت درصدی از اندازه کیک اول مشخص می‌کند (می‌تواند بین ۵ تا ۲۰۰ درصد باشد). خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

نحوه نمایش مقادیر اندازه حباب‌ها را در نمودار حبابی مشخص می‌کند. خواندن/نوشتن [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**برگشت:**  
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

نحوه نمایش مقادیر اندازه حباب‌ها را در نمودار حبابی مشخص می‌کند. خواندن/نوشتن [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

مقداری را تعیین می‌کند که برای شناسایی نقاط داده‌ای که در کیک یا نوار دوم در نمودار pie-of-pie یا bar-of-pie قرار می‌گیرند، استفاده می‌شود. همراه با خصوصیت PieSplitBy استفاده می‌شود. خواندن/نوشتن double.

**برگشت:**  
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

مقداری را تعیین می‌کند که برای شناسایی نقاط داده‌ای که در کیک یا نوار دوم در نمودار pie-of-pie یا bar-of-pie قرار می‌گیرند، استفاده می‌شود. همراه با خصوصیت PieSplitBy استفاده می‌شود. خواندن/نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

نحوه تعیین نقاط داده‌ای که در کیک یا نوار دوم در نمودار pie-of-pie یا bar-of-pie قرار می‌گیرند را مشخص می‌کند. خواندن/نوشتن [PieSplitType](../../com.aspose.slides/piesplittype).

**برگشت:**  
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

نحوه تعیین نقاط داده‌ای که در کیک یا نوار دوم در نمودار pie-of-pie یا bar-of-pie قرار می‌گیرند را مشخص می‌کند. خواندن/نوشتن [PieSplitType](../../com.aspose.slides/piesplittype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

مشخص می‌کند که هر مارکر داده در سری دارای رنگ متفاوتی باشد. خواندن/نوشتن boolean.

**برگشت:**  
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

مشخص می‌کند که هر مارکر داده در سری دارای رنگ متفاوتی باشد. خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

اگر نمودار خطوط سری داشته باشد مقدار true برمی‌گرداند. برای نمودارهای stacked bar و OfPie اعمال می‌شود. خواندن/نوشتن boolean.

**برگشت:**  
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

اگر نمودار خطوط سری داشته باشد مقدار true برمی‌گرداند. برای نمودارهای stacked bar و OfPie اعمال می‌شود. خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

قالب HiLowLines را تعیین می‌کند. HiLowLines با انواع نمودار HiLowClose, OpenHiLowClose, VolumeHiLowClose و VolumeOpenHiLowClose اعمال می‌شود.

**برگشت:**  
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

عامل مقیاس برای نمودار حبابی را تعیین می‌کند (می‌تواند بین ۰ تا ۳۰۰ درصد از اندازه پیش‌فرض باشد). خواندن/نوشتن int.

**برگشت:**  
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

عامل مقیاس برای نمودار حبابی را تعیین می‌کند (می‌تواند بین ۰ تا ۳۰۰ درصد از اندازه پیش‌فرض باشد). خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

اطلاعات تقسیم سفارشی برای نمودار pie-of-pie یا bar-of-pie با تقسیم سفارشی. شامل نقاط داده‌ای است که باید در کیک یا نوار دوم رسم شوند. فقط-خواندنی [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**برگشت:**  
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را برمی‌گرداند. فقط-خواندنی IDOMObject.

**برگشت:**  
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

نمودار والد را برمی‌گرداند. فقط-خواندنی [IChart](../../com.aspose.slides/ichart).

**برگشت:**  
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

اسلاید والد یک FillFormat را برمی‌گرداند. فقط-خواندنی [BaseSlide](../../com.aspose.slides/baseslide).

**برگشت:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ارائه والد یک FillFormat را برمی‌گرداند. فقط-خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**برگشت:**  
[IPresentation](../../com.aspose.slides/ipresentation)