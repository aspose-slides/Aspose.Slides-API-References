---
title: ChartData
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: داده‌های مورد استفاده برای ترسیم نمودار را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/chartdata/
---
**ارث‌بری:**
java.lang.Object, com.aspose.slides.DomObject

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IChartData](../../com.aspose.slides/ichartdata)
```
public class ChartData extends DomObject<Chart> implements IChartData
```

داده‌های مورد استفاده برای رسم چارت را نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | فابریک سلول‌ها را برای ایجاد سلول‌های استفاده‌شده در سری‌های چارت یا دسته‌ها می‌گیرد. |
| [getSeries()](#getSeries--) | سری‌ها را می‌گیرد. |
| [getSeriesGroups()](#getSeriesGroups--) | گروه‌های سری‌ها را می‌گیرد. |
| [getCategories()](#getCategories--) | دسته‌های اصلی را می‌گیرد (یا هر دو دستهٔ اصلی و ثانویه اگر ویژگی \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) برابر false باشد). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | اگر false باشد، ویژگی \#getSecondaryCategories.getSecondaryCategories مقدار null برمی‌گرداند و داده‌های موجود در ویژگی \#getCategories.getCategories برای هر دو سری اصلی و ثانویه استفاده می‌شود. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | اگر false باشد، ویژگی \#getSecondaryCategories.getSecondaryCategories مقدار null برمی‌گرداند و داده‌های موجود در ویژگی \#getCategories.getCategories برای هر دو سری اصلی و ثانویه استفاده می‌شود. |
| [getSecondaryCategories()](#getSecondaryCategories--) | دسته‌های ثانویه را می‌گیرد اگر ویژگی \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) برابر true باشد. |
| [readWorkbookStream()](#readWorkbookStream--) | Workbook داخلی Excel را به یک جریان درون‌حافظه‌ای می‌نویسد. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Workbook داخلی Excel را با مقدار مشخص‌شده توسط کاربر مقداردهی اولیه می‌کند. |
| [getDataSourceType()](#getDataSourceType--) | مسیر کتاب‌کار خارجی را نشان می‌دهد اگر منبع داده خارجی باشد، در غیر اینصورت null. |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | منبع دادهٔ چارت را نشان می‌دهد. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | نوع کتاب‌کار جاسازی‌شده را می‌گیرد. |
| [getRange()](#getRange--) | بازهٔ دادهٔ چارت را می‌گیرد. |
| [setRange(String formula)](#setRange-java.lang.String-) | بازهٔ دادهٔ چارت را تنظیم می‌کند. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | کتاب‌کار خارجی را به عنوان منبع داده برای چارت تنظیم می‌کند. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | کتاب‌کار خارجی را به عنوان منبع داده برای چارت تنظیم می‌کند. |
| [switchRowColumn()](#switchRowColumn--) | داده‌ها را بر محور معاوضه می‌کند. |
### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

فابریک سلول‌ها را برای ایجاد سلول‌های استفاده‌شده در سری‌ها یا دسته‌های چارت می‌گیرد. فقط-خواندنی [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**بازگشت:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

سری‌ها را می‌گیرد. فقط-خواندنی [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**بازگشت:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

گروه‌های سری را می‌گیرد. فقط-خواندنی [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) هر گروه سری شامل سری‌هایی با انواع ترکیبی است. انواع ترکیبی سری‌ها با enum CombinableSeriesTypesGroup تعریف و توصیف می‌شوند. همچنین هر گروه سری شامل سری‌هایی است که بر روی محور اصلی یا محور ثانویه (نه هر دو) رسم می‌شوند. بنابراین، اصل گروه‌بندی سری‌ها بر پایهٔ گروه‌های نوع فوق و نوع رسم اصلی/ثانویه است. 2) گروه سری شامل برخی ویژگی‌های مشترک برای هر سری در گروه است («ویژگی‌های گروه سری»). «ویژگی‌های گروه سری» در کلاس ChartSeriesGroup قابل‌خواندن/نوشتن است. هر یک از «ویژگی‌های گروه سری» می‌تواند پیش‌نمایش فقط-خواندنی در کلاس ChartSeries داشته باشد.

**بازگشت:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

دسته‌های اصلی را می‌گیرد (یا هر دو دستهٔ اصلی و ثانویه اگر ویژگی \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) برابر false باشد). فقط-خواندنی [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // دسته‌های مرتبط series.getChart().getChartData().getSecondaryCategories() هستند
>  }
>  else
>  {
>      // دسته‌های مرتبط series.getChart().getChartData().getCategories() هستند
>  }
> ```

--------------------

اگر ویژگی \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) برابر false باشد، ویژگی (\#getSecondaryCategories.getSecondaryCategories) مقدار null برمی‌گرداند و داده‌های موجود در این ویژگی \#getCategories.getCategories برای هر دو سری اصلی و ثانویه استفاده می‌شود. اگر ویژگی \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) برابر true باشد، داده‌های موجود در ویژگی (\#getSecondaryCategories.getSecondaryCategories) برای سلسله‌های ثانویه و داده‌های این ویژگی \#getCategories.getCategories برای سلسله‌های اصلی استفاده می‌شود.

**بازگشت:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

اگر false باشد، ویژگی \#getSecondaryCategories.getSecondaryCategories مقدار null برمی‌گرداند و داده‌های موجود در ویژگی \#getCategories.getCategories برای هر دو سلسله اصلی و ثانویه استفاده می‌شود. اگر true باشد، داده‌های موجود در ویژگی \#getSecondaryCategories.getSecondaryCategories برای سلسله‌های ثانویه و داده‌های موجود در ویژگی \#getCategories.getCategories برای سلسله‌های اصلی استفاده می‌شود. قابل‌خواندن/نوشتن boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // دسته‌های مرتبط series.getChart().getChartData().getSecondaryCategories() هستند
>  }
>  else
>  {
>      // دسته‌های مرتبط series.getChart().getChartData().getCategories() هستند
>  }
> ```


**بازگشت:**
boolean
### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public final void setUseSecondaryCategories(boolean value)
```

اگر false باشد، ویژگی \#getSecondaryCategories.getSecondaryCategories مقدار null برمی‌گرداند و داده‌های موجود در ویژگی \#getCategories.getCategories برای هر دو سلسله اصلی و ثانویه استفاده می‌شود. اگر true باشد، داده‌های موجود در ویژگی \#getSecondaryCategories.getSecondaryCategories برای سلسله‌های ثانویه و داده‌های موجود در ویژگی \#getCategories.getCategories برای سلسله‌های اصلی استفاده می‌شود. قابل‌خواندن/نوشتن boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // دسته‌های مرتبط series.getChart().getChartData().getSecondaryCategories() هستند
>  }
>  else
>  {
>      // دسته‌های مرتبط series.getChart().getChartData().getCategories() هستند
>  }
> ```

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public final IChartCategoryCollection getSecondaryCategories()
```

دسته‌های ثانویه را می‌گیرد اگر ویژگی \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) برابر true باشد. فقط-خواندنی [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // دسته‌های مرتبط series.getChart().getChartData().getSecondaryCategories() هستند
>  }
>  else
>  {
>      // دسته‌های مرتبط series.getChart().getChartData().getCategories() هستند
>  }
> ```


--------------------

اگر ویژگی \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) برابر false باشد، این ویژگی (\#getSecondaryCategories.getSecondaryCategories) مقدار null برمی‌گرداند و داده‌های موجود در ویژگی \#getCategories.getCategories برای هر دو سلسله اصلی و ثانویه استفاده می‌شود. اگر ویژگی \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) برابر true باشد، داده‌های موجود در این ویژگی \#getSecondaryCategories.getSecondaryCategories برای سلسله‌های ثانویه و داده‌های موجود در ویژگی \#getCategories.getCategories برای سلسله‌های اصلی استفاده می‌شود.

**بازگشت:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

Workbook داخلی Excel را به یک جریان درون‌حافظه‌ای می‌نویسد.

**بازگشت:**
byte[] - یک نمونهٔ آرایهٔ بایت حاوی کپی‌ای از Workbook داخلی Excel را بر می‌گرداند.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

Workbook داخلی Excel را با مقدار مشخص‌شده توسط کاربر مقداردهی اولیه می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| ms | byte[] | جریان ارائه‌شده توسط کاربر که شامل تمام Workbook Excel است. |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

مسیر کتاب‌کار خارجی را نشان می‌دهد اگر منبع داده خارجی باشد، در غیر اینصورت null.

**بازگشت:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public final String getExternalWorkbookPath()
```

منبع دادهٔ چارت را نشان می‌دهد.

**بازگشت:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```

نوع کتاب‌کار جاسازی‌شده را می‌گیرد. اگر DataSourceType (\#getDataSourceType.getDataSourceType) برابر [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook) باشد، [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) بر می‌گردد. فقط-خواندنی [WorkbookType](../../com.aspose.slides/workbooktype).

**بازگشت:**
int
### getRange() {#getRange--}
```
public final String getRange()
```

بازهٔ دادهٔ چارت را می‌گیرد.

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 0, 0, 100, 100);
>       String result = ((ChartData)chart.getChartData()).getRange();
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**بازگشت:**
java.lang.String - فرمول بازهٔ دادهٔ سلول‌ها. مثال: "Sheet1!$A$1:$C$4"
### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

بازهٔ دادهٔ چارت را تنظیم می‌کند. سری‌ها و دسته‌ها بر اساس بازهٔ دادهٔ جدید به‌روزرسانی می‌شوند. اگر تعداد سری‌ها در بازهٔ داده بیش از تعداد سری‌های موجود در چارت باشد، سری‌های اضافی با همان نوع سری آخرین سری در مجموعهٔ فعلی به انتهای مجموعه اضافه می‌شوند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| formula | java.lang.String | فرمول بازهٔ دادهٔ سلول‌ها. مثال: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
```

کتاب‌کار خارجی را به عنوان منبع داده برای چارت تنظیم می‌کند. داده‌های چارت از کتاب‌کار هدف به‌روزرسانی خواهند شد.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>     IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>     IChartData chartData = chart.getChartData();
>     ((ChartData)chartData).setExternalWorkbook("../../workbook.xlsx");
>  } finally {
>     if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| workbookPath | java.lang.String | مسیر به کتاب‌کار هدف |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public final void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

کتاب‌کار خارجی را به عنوان منبع داده برای چارت تنظیم می‌کند.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>      IChartData chartData = chart.getChartData();
>      ((ChartData).setExternalWorkbook("http://path/doesnt/exists", false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| workbookPath | java.lang.String | مسیر به کتاب‌کار هدف |
| updateChartData | boolean | اگر مقدار false باشد، تنها مسیر کتاب‌کار به‌روزرسانی می‌شود. داده‌های چارت بارگذاری و به‌روزرسانی نمی‌شوند. می‌توان وقتی کتاب‌کار هدف وجود ندارد یا در دسترس نیست از این گزینه استفاده کرد. اگر مقدار true باشد، داده‌های چارت از کتاب‌کار هدف به‌روزرسانی می‌شوند. |

### switchRowColumn() {#switchRowColumn--}
```
public final void switchRowColumn()
```

داده‌ها را بر محور معاوضه می‌کند. داده‌های نمودار شده بر محور X به محور Y منتقل می‌شوند و برعکس.