---
title: IChartSeriesGroup
second_title: مرجع API Java برای Aspose.Slides
description: نمایانگر یک گروه از سری‌ها.
type: docs
url: /fa/com.aspose.slides/ichartseriesgroup/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

نمایانگر یک گروه از سری‌ها است.

--------------------

1) خلاصه و توضیحات مربوط به کلاس ChartSeriesGroupCollection و enum CombinableSeriesTypesGroup را ببینید. 2) گروه سری‌ها شامل برخی ویژگی‌های سری است که برای هر سری در گروه مشترک است ("series group properties"). ویژگی‌های "series group properties" در کلاس ChartSeriesGroup قابل‌خواندن/قابل‌نوشتن است. هر یک از "series group properties" می‌تواند یک تصویر فقط‌خواندنی در کلاس ChartSeries داشته باشد.

## متدها

| متد | توضیح |
| --- | --- |
| [getType()](#getType--) | یک نوع از این گروه سری را باز می‌گرداند. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | نشان می‌دهد که آیا سری‌های این گروه روی محور ثانویه رسم می‌شوند یا خیر. |
| [getSeries()](#getSeries--) | یک مجموعه فقط‌خواندنی از سری‌های نمودار را باز می‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | عنصر موجود در ایندکس مشخص‌شده را دریافت می‌کند. |
| [getUpDownBars()](#getUpDownBars--) | دسترسی به نوارهای بالا/پایین نمودار خط یا سهام را فراهم می‌کند. |
| [getGapWidth()](#getGapWidth--) | فاصله بین خوشه‌های میله یا ستون را به‌صورت درصدی از عرض میله یا ستون مشخص می‌کند. |
| [setGapWidth(int value)](#setGapWidth-int-) | فاصله بین خوشه‌های میله یا ستون را به‌صورت درصدی از عرض میله یا ستون مشخص می‌کند. |
| [getGapDepth()](#getGapDepth--) | فاصله را به‌صورت درصدی از عرض نشانگر بین سری‌های داده در یک نمودار سه‌بعدی برمی‌گرداند یا تنظیم می‌کند. |
| [setGapDepth(int value)](#setGapDepth-int-) | فاصله را به‌صورت درصدی از عرض نشانگر بین سری‌های داده در یک نمودار سه‌بعدی برمی‌گرداند یا تنظیم می‌کند. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | زاویه برش اولین قطعه پای یا دونات را به‌صورت درجه (ساعتگرد از بالا، از 0 تا 360 درجه) دریافت یا تنظیم می‌کند. |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | زاویه برش اولین قطعه پای یا دونات را به‌صورت درجه (ساعتگرد از بالا، از 0 تا 360 درجه) دریافت یا تنظیم می‌کند. |
| [isColorVaried()](#isColorVaried--) | مشخص می‌کند که هر نشانگر داده در سری رنگ متفاوتی دارد. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | مشخص می‌کند که هر نشانگر داده در سری رنگ متفاوتی دارد. |
| [hasSeriesLines()](#hasSeriesLines--) | صحیح اگر نمودار خطوط سری داشته باشد. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | صحیح اگر نمودار خطوط سری داشته باشد. |
| [getOverlap()](#getOverlap--) | میزان هم‌پوشانی میله‌ها و ستون‌ها در نمودارهای دو‌بعدی را به‌صورت درصد (از -100% تا 100%) مشخص می‌کند. |
| [setOverlap(byte value)](#setOverlap-byte-) | میزان هم‌پوشانی میله‌ها و ستون‌ها در نمودارهای دو‌بعدی را به‌صورت درصد (از -100% تا 100%) مشخص می‌کند. |
| [getSecondPieSize()](#getSecondPieSize--) | اندازه پی یا میله دوم در نمودار pie-of-pie یا bar-of-pie را به‌صورت درصدی از اندازه پی اول مشخص می‌کند (می‌تواند بین 5 تا 200 درصد باشد). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | اندازه پی یا میله دوم در نمودار pie-of-pie یا bar-of-pie را به‌صورت درصدی از اندازه پی اول مشخص می‌کند (می‌تواند بین 5 تا 200 درصد باشد). |
| [getPieSplitPosition()](#getPieSplitPosition--) | مقداری را مشخص می‌کند که برای تعیین نقاط داده‌ای که در پی یا میله دوم در نمودار pie-of-pie یا bar-of-pie قرار می‌گیرند، استفاده می‌شود. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | مقداری را مشخص می‌کند که برای تعیین نقاط داده‌ای که در پی یا میله دوم در نمودار pie-of-pie یا bar-of-pie قرار می‌گیرند، استفاده می‌شود. |
| [getPieSplitBy()](#getPieSplitBy--) | نحوه تعیین نقاط داده‌ای که در پی یا میله دوم در نمودار pie-of-pie یا bar-of-pie قرار می‌گیرند، مشخص می‌کند. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | نحوه تعیین نقاط داده‌ای که در پی یا میله دوم در نمودار pie-of-pie یا bar-of-pie قرار می‌گیرند، مشخص می‌کند. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | اطلاعات تقسیم سفارشی برای نمودار pie-of-pie یا bar-of-pie با تقسیم سفارشی. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | اندازه سوراخ در نمودار دونات را مشخص می‌کند (می‌تواند بین 10 تا 90 درصد از اندازه ناحیه رسم باشد). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | اندازه سوراخ در نمودار دونات را مشخص می‌کند (می‌تواند بین 10 تا 90 درصد از اندازه ناحیه رسم باشد). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | میزان مقیاس برای نمودار حبابی را مشخص می‌کند (می‌تواند بین 0 تا 300 درصد از اندازه پیش‌فرض باشد). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | میزان مقیاس برای نمودار حبابی را مشخص می‌کند (می‌تواند بین 0 تا 300 درصد از اندازه پیش‌فرض باشد). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | قالب HiLowLines را مشخص می‌کند. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | نحوه نمایش مقادیر اندازه حباب در نمودار حبابی را مشخص می‌کند. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | نحوه نمایش مقادیر اندازه حباب در نمودار حبابی را مشخص می‌کند. |

### getType() {#getType--}
```
public abstract int getType()
```

یک نوع از این گروه سری را باز می‌گرداند. فقط‌خواندنی [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**بازمی‌گرداند:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

نشان می‌دهد که آیا سری‌های این گروه روی محور ثانویه رسم می‌شوند یا خیر. فقط‌خواندنی boolean.

**بازمی‌گرداند:**
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

یک مجموعه فقط‌خواندنی از سری‌های نمودار را باز می‌گرداند. فقط‌خواندنی [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**بازمی‌گرداند:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

عنصر موجود در ایندکس مشخص‌شده را دریافت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازمی‌گرداند:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public abstract IUpDownBarsManager getUpDownBars()
```

دسترسی به نوارهای بالا/پایین نمودار خط یا سهام را فراهم می‌کند. فقط‌خواندنی [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**بازمی‌گرداند:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

فاصله بین خوشه‌های میله یا ستون را به‌صورت درصدی از عرض میله یا ستون مشخص می‌کند. قابل‌خواندن/قابل‌نوشتن int.

**بازمی‌گرداند:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

فاصله بین خوشه‌های میله یا ستون را به‌صورت درصدی از عرض میله یا ستون مشخص می‌کند. قابل‌خواندن/قابل‌نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

فاصله را به‌صورت درصدی از عرض نشانگر بین سری‌های داده در یک نمودار سه‌بعدی برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن int.

**بازمی‌گرداند:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

فاصله را به‌صورت درصدی از عرض نشانگر بین سری‌های داده در یک نمودار سه‌بعدی برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

زاویه برش اولین قطعه پای یا دونات را به‌صورت درجه (ساعتگرد از بالا، از 0 تا 360 درجه) دریافت یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن int.

**بازمی‌گرداند:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

زاویه برش اولین قطعه پای یا دونات را به‌صورت درجه (ساعتگرد از بالا، از 0 تا 360 درجه) دریافت یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

مشخص می‌کند که هر نشانگر داده در سری رنگ متفاوتی دارد. قابل‌خواندن/قابل‌نوشتن boolean.

**بازمی‌گرداند:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

مشخص می‌کند که هر نشانگر داده در سری رنگ متفاوتی دارد. قابل‌خواندن/قابل‌نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

صحیح اگر نمودار خطوط سری داشته باشد. برای نمودارهای stacked bar و OfPie اعمال می‌شود. قابل‌خواندن/قابل‌نوشتن boolean.

**بازمی‌گرداند:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

صحیح اگر نمودار خطوط سری داشته باشد. برای نمودارهای stacked bar و OfPie اعمال می‌شود. قابل‌خواندن/قابل‌نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

مشخص می‌کند که میله‌ها و ستون‌ها در نمودارهای دو‌بعدی تا چه حد هم‌پوشانی داشته باشند، به‌صورت درصد (از -100% تا 100%). - -100%: بیشترین فاصله (میله‌ها کاملاً جدا هستند). - 0%: میله‌ها کنار هم بدون هم‌پوشانی یا فاصله قرار می‌گیرند. - 100%: بیشترین هم‌پوشانی (میله‌ها کاملاً یکدیگر را پوشش می‌دهند). این ویژگی قابل‌خواندن/قابل‌نوشتن byte.

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
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازمی‌گرداند:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public abstract void setOverlap(byte value)
```

مشخص می‌کند که میله‌ها و ستون‌ها در نمودارهای دو‌بعدی تا چه حد هم‌پوشانی داشته باشند، به‌صورت درصد (از -100% تا 100%). - -100%: بیشترین فاصله (میله‌ها کاملاً جدا هستند). - 0%: میله‌ها کنار هم بدون هم‌پوشانی یا فاصله قرار می‌گیرند. - 100%: بیشترین هم‌پوشانی (میله‌ها کاملاً یکدیگر را پوشش می‌دهند). این ویژگی قابل‌خواندن/قابل‌نوشتن byte.

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
public abstract int getSecondPieSize()
```

اندازه پی یا میله دوم در نمودار pie-of-pie یا bar-of-pie را به‌صورت درصدی از اندازه پی اول مشخص می‌کند (می‌تواند بین 5 تا 200 درصد باشد). قابل‌خواندن/قابل‌نوشتن int.

**بازمی‌گرداند:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

اندازه پی یا میله دوم در نمودار pie-of-pie یا bar-of-pie را به‌صورت درصدی از اندازه پی اول مشخص می‌کند (می‌تواند بین 5 تا 200 درصد باشد). قابل‌خواندن/قابل‌نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

مقداری را مشخص می‌کند که برای تعیین نقاط داده‌ای که در پی یا میله دوم در نمودار pie-of-pie یا bar-of-pie قرار می‌گیرند، استفاده می‌شود. با ویژگی PieSplitBy استفاده می‌شود. قابل‌خواندن/قابل‌نوشتن double.

**بازمی‌گرداند:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

مقداری را مشخص می‌کند که برای تعیین نقاط داده‌ای که در پی یا میله دوم در نمودار pie-of-pie یا bar-of-pie قرار می‌گیرند، استفاده می‌شود. با ویژگی PieSplitBy استفاده می‌شود. قابل‌خواندن/قابل‌نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

نحوه تعیین نقاط داده‌ای که در پی یا میله دوم در نمودار pie-of-pie یا bar-of-pie قرار می‌گیرند، مشخص می‌کند. قابل‌خواندن/قابل‌نوشتن [PieSplitType](../../com.aspose.slides/piesplittype).

**بازمی‌گرداند:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

نحوه تعیین نقاط داده‌ای که در پی یا میله دوم در نمودار pie-of-pie یا bar-of-pie قرار می‌گیرند، مشخص می‌کند. قابل‌خواندن/قابل‌نوشتن [PieSplitType](../../com.aspose.slides/piesplittype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

اطلاعات تقسیم سفارشی برای نمودار pie-of-pie یا bar-of-pie با تقسیم سفارشی. شامل نقاط داده‌ای است که باید در پی یا میله دوم در یک نمودار pie-of-pie یا بار-of-pie رسم شوند. فقط‌خواندنی [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**بازمی‌گرداند:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

اندازه سوراخ در نمودار دونات را مشخص می‌کند (می‌تواند بین 10 تا 90 درصد از اندازه ناحیه رسم باشد). قابل‌خواندن/قابل‌نوشتن byte.

**بازمی‌گرداند:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

اندازه سوراخ در نمودار دونات را مشخص می‌کند (می‌تواند بین 10 تا 90 درصد از اندازه ناحیه رسم باشد). قابل‌خواندن/قابل‌نوشتن byte.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

میزان مقیاس برای نمودار حبابی را مشخص می‌کند (می‌تواند بین 0 تا 300 درصد از اندازه پیش‌فرض باشد). قابل‌خواندن/قابل‌نوشتن int.

**بازمی‌گرداند:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

میزان مقیاس برای نمودار حبابی را مشخص می‌کند (می‌تواند بین 0 تا 300 درصد از اندازه پیش‌فرض باشد). قابل‌خواندن/قابل‌نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

قالب HiLowLines را مشخص می‌کند. HiLowLines برای انواع نمودار HiLowClose، OpenHiLowClose، VolumeHiLowClose و VolumeOpenHiLowClose اعمال می‌شود.

**بازمی‌گرداند:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

نحوه نمایش مقادیر اندازه حباب در نمودار حبابی را مشخص می‌کند. قابل‌خواندن/قابل‌نوشتن [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**بازمی‌گرداند:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

نحوه نمایش مقادیر اندازه حباب در نمودار حبابی را مشخص می‌کند. قابل‌خواندن/قابل‌نوشتن [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |