---
title: IChartData
second_title: Aspose.Slides for Android via Java API Reference
description: Represents data used for a chart plotting.
type: docs
url: /fa/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

داده‌های استفاده‌شده برای رسم نمودار را نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | کارخانه سلول‌ها را برای ایجاد سلول‌های استفاده‌شده در سری‌های نمودار یا دسته‌ها دریافت می‌کند. |
| [getSeries()](#getSeries--) | سری‌ها را دریافت می‌کند. |
| [getSeriesGroups()](#getSeriesGroups--) | گروه‌های سری‌ها را دریافت می‌کند. |
| [getCategories()](#getCategories--) | دسته‌های اصلی (یا هر دو دستهٔ اصلی و ثانویه اگر ویژگی (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) برابر false باشد) را دریافت می‌کند. |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | اگر false باشد، ویژگی (\#getSecondaryCategories.getSecondaryCategories) مقدار null بر می‌گرداند و دادهٔ موجود در ویژگی (\#getCategories.getCategories) برای هر دو سری اصلی و ثانویه استفاده می‌شود. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | اگر false باشد، ویژگی (\#getSecondaryCategories.getSecondaryCategories) مقدار null بر می‌گرداند و دادهٔ موجود در ویژگی (\#getCategories.getCategories) برای هر دو سری اصلی و ثانویه استفاده می‌شود. |
| [getSecondaryCategories()](#getSecondaryCategories--) | اگر ویژگی (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) برابر true باشد، دسته‌های ثانویه را دریافت می‌کند. |
| [readWorkbookStream()](#readWorkbookStream--) | کاربرگ اکسل داخلی را به یک جریان در حافظه می‌نویسد. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | کاربرگ اکسل داخلی را با مقدار تعیین‌شده توسط کاربر مقداردهی اولیه می‌کند. |
| [setRange(String formula)](#setRange-java.lang.String-) | محدوده داده‌های نمودار را تنظیم می‌کند. |
| [getRange()](#getRange--) | محدوده داده‌های نمودار را دریافت می‌کند. |
| [getDataSourceType()](#getDataSourceType--) | منبع دادهٔ نمودار را نشان می‌دهد |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | مسیر کاربرگ خارجی را اگر منبع داده خارجی باشد نشان می‌دهد، در غیر این صورت null |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | نوع کاربرگ جاسازی‌شده را دریافت می‌کند. |
| [switchRowColumn()](#switchRowColumn--) | داده‌ها را بر محور‌ها جابجا می‌کند. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | کاربرگ خارجی را به‌عنوان منبع داده برای نمودار تنظیم می‌کند. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | کاربرگ خارجی را به‌عنوان منبع داده برای نمودار تنظیم می‌کند. |
### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```


فاکتوری سلول‌ها را برای ایجاد سلول‌های استفاده‌شده در سری‌های نمودار یا دسته‌ها دریافت می‌کند. فقط-خواندنی [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**بازگرداندن:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```


سری‌ها را دریافت می‌کند. فقط-خواندنی [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**بازگرداندن:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```


گروه‌های سری را دریافت می‌کند. فقط-خواندنی [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) هر گروه سری شامل سری‌هایی با انواع ترکیب‌پذیر است. گروه‌های انواع سری ترکیب‌پذیر با enum ‎CombinableSeriesTypesGroup‎ تعریف و توصیف می‌شوند. همچنین هر گروه سری شامل سری‌هایی است که یا روی محورهای اصلی یا روی محورهای ثانویه (نه هر دو) رسم می‌شوند. بنابراین اصل گروه‌بندی سری بر پایهٔ نوع گروه‌ها و نوع رسم اصلی/ثانویه است. 2) گروه سری شامل برخی ویژگی‌های سری است که برای هر سری در گروه مشترک است («ویژگی‌های گروه سری»). «ویژگی‌های گروه سری» در کلاس ‎ChartSeriesGroup‎ قابل‌خواندن/نوشتن است. هر یک از این ویژگی‌ها می‌تواند نگاشت فقط-خواندنی در کلاس ‎ChartSeries‎ داشته باشد.

**بازگرداندن:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```


دسته‌های اصلی (یا هر دو دستهٔ اصلی و ثانویه اگر ویژگی (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) برابر false باشد) را دریافت می‌کند. فقط-خواندنی [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // دسته‌های مرتبط series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // دسته‌های مرتبط series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

اگر ویژگی (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) برابر false باشد، ویژگی (\#getSecondaryCategories.getSecondaryCategories) مقدار null بر می‌گرداند و دادهٔ موجود در این ویژگی (\#getCategories.getCategories) برای هر دو سری اصلی و ثانویه استفاده می‌شود. اگر ویژگی مذکور برابر true باشد، دادهٔ موجود در ویژگی (\#getSecondaryCategories.getSecondaryCategories) برای سری‌های ثانویه و دادهٔ موجود در این ویژگی (\#getCategories.getCategories) برای سری‌های اصلی استفاده می‌شود.

**بازگرداندن:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```


اگر false باشد، ویژگی (\#getSecondaryCategories.getSecondaryCategories) مقدار null بر می‌گرداند و دادهٔ موجود در ویژگی (\#getCategories.getCategories) برای هر دو سری اصلی و ثانویه استفاده می‌شود. اگر true باشد، دادهٔ موجود در ویژگی (\#getSecondaryCategories.getSecondaryCategories) برای سری‌های ثانویه و دادهٔ موجود در این ویژگی (\#getCategories.getCategories) برای سری‌های اصلی استفاده می‌شود. بولی قابل‌خواندن/نوشتن.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // دسته‌های مرتبط series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // دسته‌های مرتبط series.getChart().getChartData().getCategories()
>  }
> ```

**بازگرداندن:**
boolean
### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public abstract void setUseSecondaryCategories(boolean value)
```


اگر false باشد، ویژگی (\#getSecondaryCategories.getSecondaryCategories) مقدار null بر می‌گرداند و دادهٔ موجود در ویژگی (\#getCategories.getCategories) برای هر دو سری اصلی و ثانویه استفاده می‌شود. اگر true باشد، دادهٔ موجود در ویژگی (\#getSecondaryCategories.getSecondaryCategories) برای سری‌های ثانویه و دادهٔ موجود در این ویژگی (\#getCategories.getCategories) برای سری‌های اصلی استفاده می‌شود. بولی قابل‌خواندن/نوشتن.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // دسته‌های مرتبط series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // دسته‌های مرتبط series.getChart().getChartData().getCategories()
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


دسته‌های ثانویه را اگر ویژگی (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) برابر true باشد، دریافت می‌کند. فقط-خواندنی [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // دسته‌های مرتبط series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // دسته‌های مرتبط series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

اگر ویژگی (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) برابر false باشد، این ویژگی (\#getSecondaryCategories.getSecondaryCategories) مقدار null بر می‌گرداند و دادهٔ موجود در ویژگی (\#getCategories.getCategories) برای هر دو سری اصلی و ثانویه استفاده می‌شود. اگر این ویژگی برابر true باشد، دادهٔ موجود در این ویژگی (\#getSecondaryCategories.getSecondaryCategories) برای سری‌های ثانویه و دادهٔ موجود در ویژگی (\#getCategories.getCategories) برای سری‌های اصلی استفاده می‌شود.

**بازگرداندن:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```


کاربرگ اکسل داخلی را به یک جریان در حافظه می‌نویسد.

**بازگرداندن:**
byte[] - آرایه‌ای از بایت‌ها که نسخه‌ای کپی شده از کاربرگ اکسل داخلی را شامل می‌شود.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```


کاربرگ اکسل داخلی را با مقدار تعیین‌شده توسط کاربر مقداردهی اولیه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| ms | byte[] | جریان ارائه‌شده توسط کاربر که شامل کل کاربرگ اکسل است. |

### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```


محدوده داده‌های نمودار را تنظیم می‌کند. سری‌ها و دسته‌ها بر اساس محدوده داده جدید به‌روزرسانی می‌شوند. اگر تعداد سری‌ها در محدوده داده بیشتر از تعداد سری‌های موجود در دادهٔ نمودار باشد، سری‌های اضافی با همان نوع سری آخر در مجموعهٔ فعلی به انتهای مجموعه اضافه می‌شوند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| formula | java.lang.String | فرمول محدوده داده‌های سلول‌ها. مثال: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### getRange() {#getRange--}
```
public abstract String getRange()
```


محدوده داده‌های نمودار را دریافت می‌کند.

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```

**بازگرداندن:**
java.lang.String - فرمول محدوده داده‌های سلول‌ها. مثال: "Sheet1!$A$1:$C$4"
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```


منبع دادهٔ نمودار را نشان می‌دهد

**بازگرداندن:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```


مسیر کاربرگ خارجی را اگر منبع داده خارجی باشد نشان می‌دهد، در غیر این صورت null

**بازگرداندن:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```


نوع کاربرگ جاسازی‌شده را دریافت می‌کند. اگر ‎DataSourceType‎ (\#getDataSourceType.getDataSourceType) برابر [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook) باشد، ‎[WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined)‎ بر می‌گردد. فقط-خواندنی [WorkbookType](../../com.aspose.slides/workbooktype).

**بازگرداندن:**
int
### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```


داده‌ها را بر محور‌ها جابجا می‌کند. داده‌های نمایش‌داده‌شده بر محور X به محور Y و برعکس منتقل می‌شوند.

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```


کاربرگ خارجی را به‌عنوان منبع داده برای نمودار تنظیم می‌کند. داده‌های نمودار از کاربرگ هدف به‌روزرسانی می‌شوند.

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
| workbookPath | java.lang.String | مسیر به کاربرگ هدف |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```


کاربرگ خارجی را به‌عنوان منبع داده برای نمودار تنظیم می‌کند.

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
| workbookPath | java.lang.String | مسیر به کاربرگ هدف |
| updateChartData | boolean | اگر مقدار false باشد، فقط مسیر کاربرگ به‌روزرسانی می‌شود. داده‌های نمودار بارگذاری و به‌روزرسانی نمی‌شوند. می‌توان هنگام عدم وجود یا عدم دسترس بودن کاربرگ هدف از این گزینه استفاده کرد. اگر مقدار true باشد، داده‌های نمودار از کاربرگ هدف به‌روزرسانی می‌شوند. |