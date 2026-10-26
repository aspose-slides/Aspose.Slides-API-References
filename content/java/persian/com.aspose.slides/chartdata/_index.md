---
title: ChartData
second_title: مرجع API Aspose.Slides برای جاوا
description: داده‌های استفاده‌شده برای ترسیم یک نمودار را نمایندگی می‌کند.
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

داده‌های مورد استفاده برای ترسیم نمودار را نمایندگی می‌کند.
## متدها

| متد | توضیح |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | کارخانهٔ سلول‌ها را برای ایجاد سلول‌های مورد استفاده برای سری‌های نمودار یا دسته‌ها دریافت می‌کند. |
| [getSeries()](#getSeries--) | سری‌ها را دریافت می‌کند. |
| [getSeriesGroups()](#getSeriesGroups--) | گروه‌های سری را دریافت می‌کند. |
| [getCategories()](#getCategories--) | دسته‌های اصلی را دریافت می‌کند (یا هر دو دستهٔ اصلی و ثانوی اگر ویژگی \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) برابر false باشد). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | اگر false باشد، ویژگی \#getSecondaryCategories.getSecondaryCategories مقدار null برمی‌گرداند و داده‌های موجود در ویژگی \#getCategories.getCategories برای هر دو سری اصلی و ثانوی استفاده می‌شود. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | اگر false باشد، ویژگی \#getSecondaryCategories.getSecondaryCategories مقدار null برمی‌گرداند و داده‌های موجود در ویژگی \#getCategories.getCategories برای هر دو سری اصلی و ثانوی استفاده می‌شود. |
| [getSecondaryCategories()](#getSecondaryCategories--) | دسته‌های فرعی را دریافت می‌کند اگر ویژگی \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) برابر true باشد. |
| [readWorkbookStream()](#readWorkbookStream--) | کتاب‌کار Excel داخلی را در یک جریان حافظه‌موقتی می‌نویسد. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | کتاب‌کار Excel داخلی را با مقدار مشخص‌شده توسط کاربر مقداردهی اولیه می‌کند. |
| [getDataSourceType()](#getDataSourceType--) | مسیر کتاب‌کار خارجی را اگر منبع داده خارجی باشد، در غیر این صورت null نمایندگی می‌کند. |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | منبع دادهٔ نمودار را نمایندگی می‌کند. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | نوع کتاب‌کار جاسازی‌شده را دریافت می‌کند. |
| [getRange()](#getRange--) | محدودۀ دادهٔ نمودار را دریافت می‌کند. |
| [setRange(String formula)](#setRange-java.lang.String-) | محدودۀ دادهٔ نمودار را تنظیم می‌کند. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | کتاب‌کار خارجی را به عنوان منبع داده برای نمودار تنظیم می‌کند. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | کتاب‌کار خارجی را به عنوان منبع داده برای نمودار تنظیم می‌کند. |
| [switchRowColumn()](#switchRowColumn--) | داده‌ها را از یک محور به محور دیگر جابجا می‌کند. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

کارخانهٔ سلول‌ها را برای ایجاد سلول‌های استفاده‌شده در سری‌های نمودار یا دسته‌ها دریافت می‌کند. فقط-خواندنی [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**بازگشت:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

سری‌ها را دریافت می‌کند. فقط-خواندنی [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**بازگشت:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

گروه‌های سری را دریافت می‌کند. فقط-خواندنی [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) هر گروه از سری‌ها شامل سری‌هایی با انواع ترکیبی است. گروه‌های انواع سری‌های ترکیبی با استفاده از enum CombinableSeriesTypesGroup تعریف و توصیف می‌شوند. همچنین هر گروه از سری‌ها شامل سری‌هایی است که بر روی محور اصلی یا محور ثانوی ترسیم می‌شوند (نه هر دو حالت در یک گروه). بنابراین، اصل گروه‌بندی سری‌ها، گروه‌بندی بر اساس نوع‌های ذکر شده در بالا و بر اساس نوع نمایش اصلی/ثانوی است. 2) گروهی از سری‌ها شامل برخی ویژگی‌های سری است که برای هر سری در گروه مشترک است («ویژگی‌های گروه سری»). «ویژگی‌های گروه سری» در کلاس ChartSeriesGroup قابل خواندن/نوشتن است. هر یک از «ویژگی‌های گروه سری» می‌تواند یک نمایش فقط-خواندنی در کلاس ChartSeries داشته باشد.

**بازگشت:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

دسته‌های اصلی را دریافت می‌کند (یا هر دو دستهٔ اصلی و ثانوی اگر ویژگی \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) برابر false باشد). فقط-خواندنی [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // دسته‌های مرتبط عبارتند از series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // دسته‌های مرتبط عبارتند از series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

اگر ویژگی \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) برابر false باشد، ویژگی (\#getSecondaryCategories.getSecondaryCategories) مقدار null برمی‌گرداند و داده‌های موجود در این ویژگی \#getCategories.getCategories برای هر دو سری اصلی و ثانوی استفاده می‌شود. اگر ویژگی \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) برابر true باشد، داده‌های موجود در ویژگی (\#getSecondaryCategories.getSecondaryCategories) برای سری‌های ثانوی استفاده می‌شود و داده‌های موجود در این ویژگی \#getCategories.getCategories برای سری‌های اصلی استفاده می‌شود.

**بازگشت:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

اگر false باشد، ویژگی \#getSecondaryCategories.getSecondaryCategories مقدار null برمی‌گرداند و داده‌های موجود در ویژگی \#getCategories.getCategories برای هر دو سری اصلی و ثانوی استفاده می‌شود. اگر true باشد، داده‌های موجود در ویژگی \#getSecondaryCategories.getSecondaryCategories برای سری‌های ثانوی استفاده می‌شود و داده‌های موجود در ویژگی \#getCategories.getCategories برای سری‌های اصلی استفاده می‌شود. قابل خواندن/نوشتن بولی.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // دسته‌های مرتبط عبارتند از series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // دسته‌های مرتبط عبارتند از series.getChart().getChartData().getCategories()
>  }
> ```

**بازگشت:**
boolean

### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public final void setUseSecondaryCategories(boolean value)
```

اگر false باشد، ویژگی \#getSecondaryCategories.getSecondaryCategories مقدار null برمی‌گرداند و داده‌های موجود در ویژگی \#getCategories.getCategories برای هر دو سری اصلی و ثانوی استفاده می‌شود. اگر true باشد، داده‌های موجود در ویژگی \#getSecondaryCategories.getSecondaryCategories برای سری‌های ثانوی استفاده می‌شود و داده‌های موجود در ویژگی \#getCategories.getCategories برای سری‌های اصلی استفاده می‌شود. قابل خواندن/نوشتن بولی.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // دسته‌های مرتبط عبارتند از series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // دسته‌های مرتبط عبارتند از series.getChart().getChartData().getCategories()
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public final IChartCategoryCollection getSecondaryCategories()
```

دسته‌های ثانوی را دریافت می‌کند اگر ویژگی \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) برابر true باشد. فقط-خواندنی [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // دسته‌های مرتبط عبارتند از series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // دسته‌های مرتبط عبارتند از series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

اگر ویژگی \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) برابر false باشد، این ویژگی (\#getSecondaryCategories.getSecondaryCategories) مقدار null برمی‌گرداند و داده‌های موجود در ویژگی \#getCategories.getCategories برای هر دو سری اصلی و ثانوی استفاده می‌شود. اگر ویژگی \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) برابر true باشد، داده‌های موجود در این ویژگی \#getSecondaryCategories.getSecondaryCategories برای سری‌های ثانوی استفاده می‌شود و داده‌های موجود در ویژگی \#getCategories.getCategories برای سری‌های اصلی استفاده می‌شود.

**بازگشت:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

کتاب‌کار Excel داخلی را در یک جریان حافظه‌موقتی می‌نویسد.

**بازگشت:**
byte[] - یک نمونهٔ آرایه بایت که شامل نسخه‌ای از کتاب‌کار Excel داخلی است، باز می‌گرداند.

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

کتاب‌کار Excel داخلی را با مقدار مشخص‌شده توسط کاربر مقداردهی اولیه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| ms | byte[] | جریان ارائه‌شده توسط کاربر که شامل کل کتاب‌کار Excel است. |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

مسیر کتاب‌کار خارجی را اگر منبع داده خارجی باشد، در غیر این صورت null نمایندگی می‌کند.

**بازگشت:**
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public final String getExternalWorkbookPath()
```

منبع دادهٔ نمودار را نمایندگی می‌کند.

**بازگشت:**
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```

نوع کتاب‌کار جاسازی‌شده را دریافت می‌کند. اگر DataSourceType (\#getDataSourceType.getDataSourceType) برابر [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook) باشد، [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) باز می‌گرداند. فقط-خواندنی [WorkbookType](../../com.aspose.slides/workbooktype).

**بازگشت:**
int

### getRange() {#getRange--}
```
public final String getRange()
```

محدودۀ دادهٔ نمودار را دریافت می‌کند.

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
java.lang.String - فرمول محدوده دادهٔ سلول‌ها. به عنوان مثال: "Sheet1!$A$1:$C$4"

### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

محدودۀ دادهٔ نمودار را تنظیم می‌کند. سری‌ها و دسته‌ها بر اساس محدودهٔ دادهٔ جدید به‌روزرسانی می‌شوند. اگر تعداد سری‌ها در محدودهٔ داده بیش از تعداد سری‌ها در دادهٔ نمودار باشد، سری‌های اضافی با همان نوع سری آخر مجموعهٔ فعلی به انتهای مجموعه اضافه می‌شوند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| formula | java.lang.String | فرمول محدودهٔ دادهٔ سلول‌ها. به عنوان مثال: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
```

کتاب‌کار خارجی را به عنوان منبع داده برای نمودار تنظیم می‌کند. داده‌های نمودار از کتاب‌کار هدف به‌روزرسانی می‌شوند.

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
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| workbookPath | java.lang.String | مسیر به کتاب‌کار هدف |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public final void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

کتاب‌کار خارجی را به عنوان منبع داده برای نمودار تنظیم می‌کند.

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
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| workbookPath | java.lang.String | مسیر به کتاب‌کار هدف |
| updateChartData | boolean | اگر مقدار false باشد فقط مسیر کتاب‌کار به‌روزرسانی می‌شود. داده‌های نمودار بارگذاری و به‌روزرسانی نمی‌شوند. می‌توان هنگام عدم وجود یا در دسترس نبودن کتاب‌کار هدف از این گزینه استفاده کرد. اگر مقدار true باشد داده‌های نمودار از کتاب‌کار هدف به‌روزرسانی می‌شوند. |

### switchRowColumn() {#switchRowColumn--}
```
public final void switchRowColumn()
```

داده‌ها را از یک محور به محور دیگر جابجا می‌کند. داده‌های ترسیم‌شده بر محور X به محور Y منتقل می‌شوند و بالعکس.