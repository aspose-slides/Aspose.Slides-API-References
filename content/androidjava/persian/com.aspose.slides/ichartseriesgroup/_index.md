---
title: IChartSeriesGroup
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نماینده گروهی از سری‌ها.
type: docs
url: /fa/com.aspose.slides/ichartseriesgroup/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

نمایشگر گروهی از سری‌ها.

--------------------

1) See summary and remarks for ChartSeriesGroupCollection class and CombinableSeriesTypesGroup enum. 2) Group of series contains some series properies whitch is common for each series in group ("series group properties"). "Series group properties" in ChartSeriesGroup class is read/write. Each of "series group properties" can have a read-only projection in ChartSeries class.
## متدها

| متد | توضیح |
| --- | --- |
| [getType()](#getType--) | یک نوع از این گروه سری را برمی‌گرداند. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | نشان می‌دهد آیا سری‌های این گروه بر روی محور ثانویه رسم می‌شوند. |
| [getSeries()](#getSeries--) | یک مجموعه فقط‌قابل خواندن از سری‌های نمودار را برمی‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | عنصر موجود در اندیس مشخص شده را دریافت می‌کند. |
| [getUpDownBars()](#getUpDownBars--) | دسترسی به نوارهای بالا/پایین نمودار خط یا سهام را فراهم می‌کند. |
| [getGapWidth()](#getGapWidth--) | فضای بین خوشه‌های میله یا ستون را به عنوان درصدی از عرض میله یا ستون مشخص می‌کند. |
| [setGapWidth(int value)](#setGapWidth-int-) | فضای بین خوشه‌های میله یا ستون را به عنوان درصدی از عرض میله یا ستون مشخص می‌کند. |
| [getGapDepth()](#getGapDepth--) | فاصله بین سری‌های داده در یک نمودار سه‌بعدی را به عنوان درصدی از عرض مارکر برمی‌گرداند یا تنظیم می‌کند. |
| [setGapDepth(int value)](#setGapDepth-int-) | فاصله بین سری‌های داده در یک نمودار سه‌بعدی را به عنوان درصدی از عرض مارکر برمی‌گرداند یا تنظیم می‌کند. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | زاویه اولین بخش کیک یا دونات را به درجه (ساعت‌گرد از بالا، از 0 تا 360 درجه) دریافت یا تنظیم می‌کند. |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | زاویه اولین بخش کیک یا دونات را به درجه (ساعت‌گرد از بالا، از 0 تا 360 درجه) دریافت یا تنظیم می‌کند. |
| [isColorVaried()](#isColorVaried--) | مشخص می‌کند که هر مارکر داده در سری رنگ متفاوتی داشته باشد. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | مشخص می‌کند که هر مارکر داده در سری رنگ متفاوتی داشته باشد. |
| [hasSeriesLines()](#hasSeriesLines--) | درست اگر نمودار خطوط سری دارد. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | درست اگر نمودار خطوط سری دارد. |
| [getOverlap()](#getOverlap--) | مشخص می‌کند میله‌ها و ستون‌ها در نمودارهای 2-بعدی چه مقدار همپوشانی داشته باشند، به عنوان درصد (از -100% تا 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | مشخص می‌کند میله‌ها و ستون‌ها در نمودارهای 2-بعدی چه مقدار همپوشانی داشته باشند، به عنوان درصد (از -100% تا 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | اندازه کیک یا میله دوم در نمودار کیک-از-کیک یا میله-از-کیک را به عنوان درصدی از اندازه کیک اول مشخص می‌کند (می‌تواند بین 5 و 200 درصد باشد). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | اندازه کیک یا میله دوم در نمودار کیک-از-کیک یا میله-از-کیک را به عنوان درصدی از اندازه کیک اول مشخص می‌کند (می‌تواند بین 5 و 200 درصد باشد). |
| [getPieSplitPosition()](#getPieSplitPosition--) | مقداری را مشخص می‌کند که برای تعیین اینکه کدام نقاط داده در کیک یا میله دوم در نمودار کیک-از-کیک یا میله-از-کیک قرار گیرند، استفاده می‌شود. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | مقداری را مشخص می‌کند که برای تعیین اینکه کدام نقاط داده در کیک یا میله دوم در نمودار کیک-از-کیک یا میله-از-کیک قرار گیرند، استفاده می‌شود. |
| [getPieSplitBy()](#getPieSplitBy--) | روش تعیین اینکه کدام نقاط داده در کیک یا میله دوم در نمودار کیک-از-کیک یا میله-از-کیک قرار گیرند را مشخص می‌کند. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | روش تعیین اینکه کدام نقاط داده در کیک یا میله دوم در نمودار کیک-از-کیک یا میله-از-کیک قرار گیرند را مشخص می‌کند. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | اطلاعات تقسیم سفارشی برای نمودار کیک-از-کیک یا میله-از-کیک با تقسیم سفارشی. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | اندازه حفره در نمودار دونات را مشخص می‌کند (می‌تواند بین 10 و 90 درصد از اندازه ناحیه رسم باشد). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | اندازه حفره در نمودار دونات را مشخص می‌کند (می‌تواند بین 10 و 90 درصد از اندازه ناحیه رسم باشد). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | عامل مقیاس برای نمودار حبابی را مشخص می‌کند (می‌تواند بین 0 و 300 درصد از اندازه پیش‌فرض باشد). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | عامل مقیاس برای نمودار حبابی را مشخص می‌کند (می‌تواند بین 0 و 300 درصد از اندازه پیش‌فرض باشد). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | قالب HiLowLines را مشخص می‌کند. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | نحوه نمایش مقادیر اندازه حباب در نمودار حبابی را مشخص می‌کند. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | نحوه نمایش مقادیر اندازه حباب در نمودار حبابی را مشخص می‌کند. |

### getType() {#getType--}
```
public abstract int getType()
```

یک نوع از این گروه سری را برمی‌گرداند. فقط‌قابل خواندن [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**برگشت:**  
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

نشان می‌دهد آیا سری‌های این گروه بر روی محور ثانویه رسم می‌شوند. فقط‌قابل خواندن boolean.

**برگشت:**  
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

یک مجموعه فقط‌قابل خواندن از سری‌های نمودار را برمی‌گرداند. فقط‌قابل خواندن [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**برگشت:**  
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

**برگشت:**  
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public abstract IUpDownBarsManager getUpDownBars()
```

دسترسی به نوارهای بالا/پایین نمودار خط یا سهام را فراهم می‌کند. فقط‌قابل خواندن [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**برگشت:**  
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

فضای بین خوشه‌های میله یا ستون را به عنوان درصدی از عرض میله یا ستون مشخص می‌کند. قابل خواندن و نوشتن int.

**برگشت:**  
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

فضای بین خوشه‌های میله یا ستون را به عنوان درصدی از عرض میله یا ستون مشخص می‌کند. قابل خواندن و نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

فاصله بین سری‌های داده در یک نمودار سه‌بعدی را به عنوان درصدی از عرض مارکر برمی‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن int.

**برگشت:**  
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

فاصله بین سری‌های داده در یک نمودار سه‌بعدی را به عنوان درصدی از عرض مارکر برمی‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

زاویه اولین بخش کیک یا دونات را به درجه (ساعت‌گرد از بالا، از 0 تا 360 درجه) دریافت یا تنظیم می‌کند. قابل خواندن و نوشتن int.

**برگشت:**  
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

زاویه اولین بخش کیک یا دونات را به درجه (ساعت‌گرد از بالا، از 0 تا 360 درجه) دریافت یا تنظیم می‌کند. قابل خواندن و نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

مشخص می‌کند که هر مارکر داده در سری رنگ متفاوتی داشته باشد. قابل خواندن و نوشتن boolean.

**برگشت:**  
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

مشخص می‌کند که هر مارکر داده در سری رنگ متفاوتی داشته باشد. قابل خواندن و نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

درست اگر نمودار خطوط سری دارد. برای نمودارهای stacked bar و OfPie اعمال می‌شود. قابل خواندن و نوشتن boolean.

**برگشت:**  
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

درست اگر نمودار خطوط سری دارد. برای نمودارهای stacked bar و OfPie اعمال می‌شود. قابل خواندن و نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

مشخص می‌کند میله‌ها و ستون‌ها در نمودارهای 2-بعدی چه مقدار همپوشانی داشته باشند، به عنوان درصد (از -100% تا 100%). -100%: حداکثر فاصله (میله‌ها کاملاً جدا هستند). -0%: میله‌ها کنار هم بدون همپوشانی یا فاصله قرار می‌گیرند. 100%: حداکثر همپوشانی (میله‌ها کاملاً روی هم هستند). این ویژگی قابل خواندن و نوشتن byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // همپوشانی را به 55٪ تنظیم کنید
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**برگشت:**  
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public abstract void setOverlap(byte value)
```

مشخص می‌کند میله‌ها و ستون‌ها در نمودارهای 2-بعدی چه مقدار همپوشانی داشته باشند، به عنوان درصد (از -100% تا 100%). -100%: حداکثر فاصله (میله‌ها کاملاً جدا هستند). -0%: میله‌ها کنار هم بدون همپوشانی یا فاصله قرار می‌گیرند. 100%: حداکثر همپوشانی (میله‌ها کاملاً روی هم هستند). این ویژگی قابل خواندن و نوشتن byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // همپوشانی را به 55٪ تنظیم کنید
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

اندازه کیک یا میله دوم در نمودار کیک-از-کیک یا میله-از-کیک را به عنوان درصدی از اندازه کیک اول مشخص می‌کند (می‌تواند بین 5 و 200 درصد باشد). قابل خواندن و نوشتن int.

**برگشت:**  
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

اندازه کیک یا میله دوم در نمودار کیک-از-کیک یا میله-از-کیک را به عنوان درصدی از اندازه کیک اول مشخص می‌کند (می‌تواند بین 5 و 200 درصد باشد). قابل خواندن و نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

مقداری را مشخص می‌کند که برای تعیین اینکه کدام نقاط داده در کیک یا میله دوم در نمودار کیک-از-کیک یا میله-از-کیک قرار گیرند، استفاده می‌شود. همراه با ویژگی PieSplitBy استفاده می‌شود. قابل خواندن و نوشتن double.

**برگشت:**  
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

مقداری را مشخص می‌کند که برای تعیین اینکه کدام نقاط داده در کیک یا میله دوم در نمودار کیک-از-کیک یا میله-از-کیک قرار گیرند، استفاده می‌شود. همراه با ویژگی PieSplitBy استفاده می‌شود. قابل خواندن و نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

روش تعیین اینکه کدام نقاط داده در کیک یا میله دوم در نمودار کیک-از-کیک یا میله-از-کیک قرار گیرند را مشخص می‌کند. قابل خواندن و نوشتن [PieSplitType](../../com.aspose.slides/piesplittype).

**برگشت:**  
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

روش تعیین اینکه کدام نقاط داده در کیک یا میله دوم در نمودار کیک-از-کیک یا میله-از-کیک قرار گیرند را مشخص می‌کند. قابل خواندن و نوشتن [PieSplitType](../../com.aspose.slides/piesplittype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

اطلاعات تقسیم سفارشی برای نمودار کیک-از-کیک یا میله-از-کیک با تقسیم سفارشی. شامل نقاط داده‌ای است که باید در کیک یا میله دوم رسم شوند. فقط‌قابل خواندن [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**برگشت:**  
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

اندازه حفره در نمودار دونات را مشخص می‌کند (می‌تواند بین 10 و 90 درصد از اندازه ناحیه رسم باشد). قابل خواندن و نوشتن byte.

**برگشت:**  
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

اندازه حفره در نمودار دونات را مشخص می‌کند (می‌تواند بین 10 و 90 درصد از اندازه ناحیه رسم باشد). قابل خواندن و نوشتن byte.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

عامل مقیاس برای نمودار حبابی را مشخص می‌کند (می‌تواند بین 0 و 300 درصد از اندازه پیش‌فرض باشد). قابل خواندن و نوشتن int.

**برگشت:**  
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

عامل مقیاس برای نمودار حبابی را مشخص می‌کند (می‌تواند بین 0 و 300 درصد از اندازه پیش‌فرض باشد). قابل خواندن و نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

قالب HiLowLines را مشخص می‌کند. HiLowLines در انواع نمودار HiLowClose، OpenHiLowClose، VolumeHiLowClose و VolumeOpenHiLowClose به کار می‌رود.

**برگشت:**  
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

نحوه نمایش مقادیر اندازه حباب در نمودار حبابی را مشخص می‌کند. قابل خواندن و نوشتن [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**برگشت:**  
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

نحوه نمایش مقادیر اندازه حباب در نمودار حبابی را مشخص می‌کند. قابل خواندن و نوشتن [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |