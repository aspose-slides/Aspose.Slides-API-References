---
title: IChartData
second_title: Aspose.Slides برای Java API Reference
description: داده‌هایی را که برای رسم نمودار استفاده می‌شود، نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

داده‌هایی را که برای رسم نمودار استفاده می‌شود، نشان می‌دهد.
## متدها

| Method | Description |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | فابریکی برای سلول‌ها را برمی‌گرداند تا سلول‌های استفاده‌شده در سری‌ها یا دسته‌های نمودار را ایجاد کند. |
| [getSeries()](#getSeries--) | سری‌ها را برمی‌گرداند. |
| [getSeriesGroups()](#getSeriesGroups--) | گروه‌های سری‌ها را برمی‌گرداند. |
| [getCategories()](#getCategories--) | دسته‌های اصلی را برمی‌گرداند (یا هر دو دسته‌ی اصلی و ثانویه اگر ویژگی (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) برابر false باشد). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | اگر false باشد، ویژگی (\#getSecondaryCategories.getSecondaryCategories) مقدار null برمی‌گرداند و داده‌های موجود در ویژگی (\#getCategories.getCategories) برای هر دو سری اصلی و ثانویه استفاده می‌شود. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | اگر false باشد، ویژگی (\#getSecondaryCategories.getSecondaryCategories) مقدار null برمی‌گرداند و داده‌های موجود در ویژگی (\#getCategories.getCategories) برای هر دو سری اصلی و ثانویه استفاده می‌شود. |
| [getSecondaryCategories()](#getSecondaryCategories--) | دسته‌های ثانویه را برمی‌گرداند اگر ویژگی (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) برابر true باشد. |
| [readWorkbookStream()](#readWorkbookStream--) | دفتر کار Excel داخلی را به یک جریان در-حافظه می‌نویسد. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | دفتر کار Excel داخلی را با مقدار مشخص‌شده توسط کاربر مقداردهی اولیه می‌کند. |
| [setRange(String formula)](#setRange-java.lang.String-) | محدوده داده‌های نمودار را تنظیم می‌کند. |
| [getRange()](#getRange--) | محدوده داده‌های نمودار را برمی‌گرداند. |
| [getDataSourceType()](#getDataSourceType--) | منبع داده‌ای نمودار را نشان می‌دهد |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | مسیر دفتر کار خارجی را نشان می‌دهد اگر منبع داده خارجی باشد، در غیر این صورت null |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | نوع دفتر کار جاسازی‌شده را برمی‌گرداند. |
| [switchRowColumn()](#switchRowColumn--) | داده‌ها را بر روی محور جابجا می‌کند. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | دفتر کار خارجی را به عنوان منبع داده برای نمودار تنظیم می‌کند. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | دفتر کار خارجی را به عنوان منبع داده برای نمودار تنظیم می‌کند. |
| [refreshData()](#refreshData--) | داده‌های نمودار را با بارگذاری مجدد از دفتر کار منبع به‌روزرسانی می‌کند. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```

فابریکی برای سلول‌ها را برمی‌گرداند تا سلول‌های استفاده‌شده در سری‌ها یا دسته‌های نمودار را ایجاد کند. فقط خواندنی [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**بازگشت:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```

سری‌ها را برمی‌گرداند. فقط خواندنی [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**بازگشت:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```

گروه‌های سری‌ها را برمی‌گرداند. فقط خواندنی [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

هر گروهی از سری‌ها شامل سری‌هایی با انواع ترکیبی است. گروه‌های انواع سری ترکیبی با enum CombinableSeriesTypesGroup تعریف و توصیف شده‌اند. همچنین هر گروهی از سری‌ها شامل سری‌هایی است که روی محورهای اصلی یا ثانویه رسم می‌شوند (نه هر دو حالت در یک گروه). بنابراین، اصل گروه‌بندی سری‌ها بر اساس گروه‌های نوع ذکر شده در بالا و نوع رسم اصلی/ثانویه است.

**بازگشت:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```

دسته‌های اصلی را برمی‌گرداند (یا هر دو دسته‌ی اصلی و ثانویه اگر ویژگی (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) برابر false باشد). فقط خواندنی [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

اگر (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) برابر false باشد، ویژگی (\#getSecondaryCategories.getSecondaryCategories) مقدار null برمی‌گرداند و داده‌های موجود در این ویژگی (\#getCategories.getCategories) برای هر دو سری اصلی و ثانویه استفاده می‌شود. اگر (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) برابر true باشد، داده‌های موجود در ویژگی (\#getSecondaryCategories.getSecondaryCategories) برای سری‌های ثانویه و داده‌های موجود در این ویژگی (\#getCategories.getCategories) برای سری‌های اصلی استفاده می‌شود.

**بازگشت:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

اگر false باشد، ویژگی (\#getSecondaryCategories.getSecondaryCategories) مقدار null برمی‌گرداند و داده‌های موجود در ویژگی (\#getCategories.getCategories) برای هر دو سری اصلی و ثانویه استفاده می‌شود. اگر true باشد، داده‌های موجود در ویژگی (\#getSecondaryCategories.getSecondaryCategories) برای سری‌های ثانویه و داده‌های موجود در ویژگی (\#getCategories.getCategories) برای سری‌های اصلی استفاده می‌شود. قابل خواندن/نوشتن boolean.

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

**بازگشت:**
boolean

### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public abstract void setUseSecondaryCategories(boolean value)
```

اگر false باشد، ویژگی (\#getSecondaryCategories.getSecondaryCategories) مقدار null برمی‌گرداند و داده‌های موجود در ویژگی (\#getCategories.getCategories) برای هر دو سری اصلی و ثانویه استفاده می‌شود. اگر true باشد، داده‌های موجود در ویژگی (\#getSecondaryCategories.getSecondaryCategories) برای سری‌های ثانویه و داده‌های موجود در ویژگی (\#getCategories.getCategories) برای سری‌های اصلی استفاده می‌شود. قابل خواندن/نوشتن boolean.

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

دسته‌های ثانویه را برمی‌گرداند اگر ویژگی (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) برابر true باشد. فقط خواندنی [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

اگر (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) برابر false باشد، این ویژگی (\#getSecondaryCategories.getSecondaryCategories) مقدار null برمی‌گرداند و داده‌های موجود در ویژگی (\#getCategories.getCategories) برای هر دو سری اصلی و ثانویه استفاده می‌شود. اگر (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) برابر true باشد، داده‌های موجود در این ویژگی (\#getSecondaryCategories.getSecondaryCategories) برای سری‌های ثانویه و داده‌های موجود در ویژگی (\#getCategories.getCategories) برای سری‌های اصلی استفاده می‌شود.

**بازگشت:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```

دفتر کار Excel داخلی را به یک جریان در-حافظه می‌نویسد.

**بازگشت:**
byte[] - آرایه‌ای از بایت‌ها را برمی‌گرداند که شامل نسخه‌ای از دفتر کار داخلی Excel است.

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```

دفتر کار Excel داخلی را با مقدار مشخص‌شده توسط کاربر مقداردهی اولیه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| ms | byte[] | جریانی که توسط کاربر فراهم شده و شامل تمام دفتر کار Excel است. |

### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

محدوده داده‌های نمودار را تنظیم می‌کند. سری‌ها و دسته‌ها بر اساس محدوده داده جدید به‌روزرسانی می‌شوند. اگر تعداد سری‌ها در محدوده داده بیشتر از تعداد سری‌های موجود در داده‌های نمودار باشد، سری‌های اضافی با همان نوع سری آخرین سری در مجموعه فعلی به انتهای مجموعه اضافه می‌شوند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| formula | java.lang.String | فرمول محدوده داده‌های سلول‌ها. مثلا: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### getRange() {#getRange--}
```
public abstract String getRange()
```

محدوده داده‌های نمودار را برمی‌گرداند.

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```

**بازگشت:**
java.lang.String - فرمول محدوده داده‌های سلول‌ها. مثلا: "Sheet1!$A$1:$C$4"

### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

منبع داده‌ای نمودار را نشان می‌دهد

**بازگشت:**
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```

مسیر دفتر کار خارجی را نشان می‌دهد اگر منبع داده خارجی باشد، در غیر این صورت null

**بازگشت:**
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```

نوع دفتر کار جاسازی‌شده را برمی‌گرداند. اگر DataSourceType (\#getDataSourceType.getDataSourceType) برابر [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook) باشد، [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) را برمی‌گرداند. فقط خواندنی [WorkbookType](../../com.aspose.slides/workbooktype).

**بازگشت:**
int

### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```

داده‌ها را بر روی محور جابجا می‌کند. داده‌هایی که بر محور X نمودار شده‌اند به محور Y منتقل می‌شوند و برعکس.

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```

دفتر کار خارجی را به عنوان منبع داده برای نمودار تنظیم می‌کند. داده‌های نمودار از دفتر کار هدف به‌روزرسانی خواهند شد.

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
| workbookPath | java.lang.String | مسیر به دفتر کار هدف |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

دفتر کار خارجی را به عنوان منبع داده برای نمودار تنظیم می‌کند.

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
| workbookPath | java.lang.String | مسیر به دفتر کار هدف |
| updateChartData | boolean | اگر مقدار false باشد فقط مسیر دفتر کار به‌روزرسانی می‌شود. داده‌های نمودار بارگذاری و به‌روزرسانی نخواهند شد. می‌توان از آن وقتی دفتر کار هدف وجود نداشته باشد یا در دسترس نباشد استفاده کرد. اگر مقدار true باشد داده‌های نمودار از دفتر کار هدف به‌روزرسانی خواهند شد. |

### refreshData() {#refreshData--}
```
public abstract void refreshData()
```

داده‌های نمودار را با بارگذاری مجدد از دفتر کار منبع به‌روزرسانی می‌کند.

--------------------

> ```
> Presentation presentation = new Presentation("presentationWithChart.pptx");
>  try {
>      IChart chart = (IChart)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      chart.getChartData().refreshData();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```