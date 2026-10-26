---
title: IChartData
second_title: Aspose.Slides for Java API Reference
description: داده‌های استفاده شده برای ترسیم یک نمودار.
type: docs
url: /fa/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

داده‌های استفاده شده برای ترسیم یک نمودار.
## متدها

| متد | توضیح |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | فاکتور سلول‌ها را برای ایجاد سلول‌های استفاده‌شده در سری یا دسته‌بندی‌های نمودار برمی‌گرداند. |
| [getSeries()](#getSeries--) | سری‌ها را باز می‌گرداند. |
| [getSeriesGroups()](#getSeriesGroups--) | گروه‌های سری را باز می‌گرداند. |
| [getCategories()](#getCategories--) | دسته‌بندی‌های اصلی را باز می‌گرداند (یا هر دو دسته‌بندی اصلی و ثانویه اگر ویژگی (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) برابر false باشد). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | اگر مقدار false باشد، ویژگی (\#getSecondaryCategories.getSecondaryCategories) مقدار null باز می‌گرداند و داده‌های موجود در ویژگی (\#getCategories.getCategories) برای هر دو سری اصلی و ثانویه استفاده می‌شود. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | اگر مقدار false باشد، ویژگی (\#getSecondaryCategories.getSecondaryCategories) مقدار null باز می‌گرداند و داده‌های موجود در ویژگی (\#getCategories.getCategories) برای هر دو سری اصلی و ثانویه استفاده می‌شود. |
| [getSecondaryCategories()](#getSecondaryCategories--) | دسته‌بندی‌های ثانویه را باز می‌گرداند اگر ویژگی (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) برابر true باشد. |
| [readWorkbookStream()](#readWorkbookStream--) | پوشه Excel داخلی را به یک جریان در حافظه می‌نویسد. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | پوشه Excel داخلی را با مقدار تعیین‌شده توسط کاربر مقداردهی اولیه می‌کند. |
| [setRange(String formula)](#setRange-java.lang.String-) | محدوده داده‌های نمودار را تنظیم می‌کند. |
| [getRange()](#getRange--) | محدوده داده‌های نمودار را باز می‌گرداند. |
| [getDataSourceType()](#getDataSourceType--) | منبع داده نمودار را نمایندگی می‌کند |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | مسیر ورک‌بوک خارجی را اگر منبع داده خارجی باشد نمایندگی می‌کند، در غیر اینصورت null. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | نوع ورک‌بوک توکار را باز می‌گرداند. |
| [switchRowColumn()](#switchRowColumn--) | داده‌ها را بر روی محور جابجا می‌کند. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | یک ورک‌بوک خارجی را به عنوان منبع داده برای نمودار تنظیم می‌کند. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | یک ورک‌بوک خارجی را به عنوان منبع داده برای نمودار تنظیم می‌کند. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```

فاکتور سلول‌ها را برای ایجاد سلول‌های استفاده‌شده در سری یا دسته‌بندی‌های نمودار باز می‌گرداند. فقط-خواندنی [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**بازگشت:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```

سری‌ها را باز می‌گرداند. فقط-خواندنی [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**بازگشت:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```

گروه‌های سری را باز می‌گرداند. فقط-خواندنی [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) هر گروه سری شامل سری‌های با انواع قابل ترکیب است. گروه‌های انواع سری‌های ترکیب‌پذیر با enum ‎CombinableSeriesTypesGroup‎ تعریف و توضیح داده شده‌اند. همچنین هر گروه سری شامل سری‌هایی است که یا روی محورهای اصلی یا روی محورهای ثانویه ترسیم می‌شوند (نه هر دو به‌صورت همزمان در یک گروه). بنابراین اصل گروه‌بندی سری‌ها بر پایهٔ گروه‌های نوع فوق و نوع ترسیم اصلی/ثانویه است. 2) یک گروه سری ممکن است شامل برخی ویژگی‌های مشترک برای تمام سری‌های داخل گروه باشد («ویژگی‌های گروه سری»). «ویژگی‌های گروه سری» در کلاس ‎ChartSeriesGroup‎ خواندنی/قابل‌نوشتن است. هر یک از «ویژگی‌های گروه سری» می‌تواند یک پیش‌نمایش فقط-خواندنی در کلاس ‎ChartSeries‎ داشته باشد.

**بازگشت:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```

دسته‌بندی‌های اصلی را باز می‌گرداند (یا هر دو دسته‌بندی اصلی و ثانویه اگر ویژگی (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) برابر false باشد). فقط-خواندنی [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // دسته‌بندی‌های مرتبط عبارتند از series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // دسته‌بندی‌های مرتبط عبارتند از series.getChart().getChartData().getCategories()
>  }
> ```


--------------------

اگر ویژگی (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) برابر false باشد، ویژگی (\#getSecondaryCategories.getSecondaryCategories) مقدار null باز می‌گرداند و داده‌های موجود در این ویژگی (\#getCategories.getCategories) برای هر دو سری اصلی و ثانویه استفاده می‌شود. اگر ویژگی فوق برابر true باشد، داده‌های موجود در ویژگی (\#getSecondaryCategories.getSecondaryCategories) برای سری‌های ثانویه و داده‌های موجود در این ویژگی (\#getCategories.getCategories) برای سری‌های اصلی استفاده می‌شود.

**بازگشت:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

اگر مقدار false باشد، ویژگی (\#getSecondaryCategories.getSecondaryCategories) مقدار null باز می‌گرداند و داده‌های موجود در ویژگی (\#getCategories.getCategories) برای هر دو سری اصلی و ثانویه استفاده می‌شود. اگر مقدار true باشد، داده‌های موجود در ویژگی (\#getSecondaryCategories.getSecondaryCategories) برای سری‌های ثانویه و داده‌های موجود در ویژگی (\#getCategories.getCategories) برای سری‌های اصلی استفاده می‌شود. بولی خواندنی/قابل‌نوشتن.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // دسته‌بندی‌های مرتبط عبارتند از series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // دسته‌بندی‌های مرتبط عبارتند از series.getChart().getChartData().getCategories()
>  }
> ```


**بازگشت:**
boolean

### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public abstract void setUseSecondaryCategories(boolean value)
```

اگر مقدار false باشد، ویژگی (\#getSecondaryCategories.getSecondaryCategories) مقدار null باز می‌گرداند و داده‌های موجود در ویژگی (\#getCategories.getCategories) برای هر دو سری اصلی و ثانویه استفاده می‌شود. اگر مقدار true باشد، داده‌های موجود در ویژگی (\#getSecondaryCategories.getSecondaryCategories) برای سری‌های ثانویه و داده‌های موجود در ویژگی (\#getCategories.getCategories) برای سری‌های اصلی استفاده می‌شود. بولی خواندنی/قابل‌نوشتن.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // دسته‌بندی‌های مرتبط عبارتند از series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // دسته‌بندی‌های مرتبط عبارتند از series.getChart().getChartData().getCategories()
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public abstract IChartCategoryCollection getSecondaryCategories()
```

دسته‌بندی‌های ثانویه را باز می‌گرداند اگر ویژگی (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) برابر true باشد. فقط-خواندنی [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // دسته‌بندی‌های مرتبط عبارتند از series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // دسته‌بندی‌های مرتبط عبارتند از series.getChart().getChartData().getCategories()
>  }
> ```


--------------------

اگر ویژگی (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) برابر false باشد، این ویژگی (\#getSecondaryCategories.getSecondaryCategories) مقدار null باز می‌گرداند و داده‌های موجود در ویژگی (\#getCategories.getCategories) برای هر دو سری اصلی و ثانویه استفاده می‌شود. اگر ویژگی فوق برابر true باشد، داده‌های موجود در این ویژگی (\#getSecondaryCategories.getSecondaryCategories) برای سری‌های ثانویه و داده‌های موجود در ویژگی (\#getCategories.getCategories) برای سری‌های اصلی استفاده می‌شود.

**بازگشت:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```

پوشه Excel داخلی را به یک جریان در حافظه می‌نویسد.

**بازگشت:**
byte[] - آرایه‌ای از بایت‌ها که نسخه‌ای کپی از پوشه Excel داخلی را شامل می‌شود.

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```

پوشه Excel داخلی را با مقدار تعیین‌شده توسط کاربر مقداردهی اولیه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| ms | byte[] | جریان فراهم‌شده توسط کاربر که شامل کل ورک‌بوک Excel است. |

### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

محدوده داده‌های نمودار را تنظیم می‌کند. سری‌ها و دسته‌بندی‌ها بر اساس محدوده داده جدید به‌روزرسانی می‌شوند. اگر تعداد سری‌ها در محدوده داده بیش از تعداد سری‌های موجود در داده‌های نمودار باشد، سری‌های اضافی با همان نوع سری آخرین سری موجود به انتهای مجموعه اضافه می‌شوند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| formula | java.lang.String | فرمول محدوده داده‌های سلول‌ها. مثال: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### getRange() {#getRange--}
```
public abstract String getRange()
```

محدوده داده‌های نمودار را باز می‌گرداند.

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```

**بازگشت:**
java.lang.String - فرمول محدوده داده‌های سلول‌ها. مثال: "Sheet1!$A$1:$C$4"

### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

منبع داده نمودار را نمایندگی می‌کند

**بازگشت:**
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```

مسیر ورک‌بوک خارجی را اگر منبع داده خارجی باشد نمایندگی می‌کند، در غیر اینصورت null

**بازگشت:**
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```

نوع ورک‌بوک توکار را باز می‌گرداند. اگر ‎DataSourceType‎ (\#getDataSourceType.getDataSourceType) برابر [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook) باشد ‎[WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined)‎ باز می‌گردد. فقط-خواندنی [WorkbookType](../../com.aspose.slides/workbooktype).

**بازگشت:**
int

### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```

داده‌ها را بر روی محور جابجا می‌کند. داده‌های ترسیم‌شده روی محور X به محور Y منتقل می‌شوند و بالعکس.

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```

یک ورک‌بوک خارجی را به عنوان منبع داده برای نمودار تنظیم می‌کند. داده‌های نمودار از ورک‌بوک هدف به‌روزرسانی می‌شوند.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>     IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>     IChartData chartData = chart.getChartData();
>     ((ChartData)chartData).setExternalWorkbook("../../workbook.xlsx");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| workbookPath | java.lang.String | مسیر به ورک‌بوک هدف |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

یک ورک‌بوک خارجی را به عنوان منبع داده برای نمودار تنظیم می‌کند.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>     IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>     IChartData chartData = chart.getChartData();
>     ((ChartData)chartData).setExternalWorkbook("http://path/doesnt/exists", false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| workbookPath | java.lang.String | مسیر به ورک‌بوک هدف |
| updateChartData | boolean | اگر مقدار false باشد، فقط مسیر ورک‌بوک به‌روز می‌شود. داده‌های نمودار بارگذاری و به‌روزرسانی نمی‌شوند. می‌تواند زمانی استفاده شود که ورک‌بوک هدف موجود نباشد یا در دسترس نباشد. اگر مقدار true باشد، داده‌های نمودار از ورک‌بوک هدف به‌روزرسانی می‌شوند. |