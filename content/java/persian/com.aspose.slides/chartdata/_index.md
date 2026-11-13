---
title: ChartData
second_title: Aspose.Slides برای مرجع API جاوا
description: داده‌هایی را که برای رسم نمودار استفاده می‌شود، نمایان می‌کند.
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

نمایانگر داده‌های استفاده‌شده برای ترسیم نمودار است.

## متدها

| Method | Description |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | کارخانه سلول‌ها را برای ایجاد سلول‌های مورد استفاده در سری‌ها یا دسته‌های نمودار برمی‌گرداند. |
| [getSeries()](#getSeries--) | سری‌ها را برمی‌گرداند. |
| [getSeriesGroups()](#getSeriesGroups--) | گروه‌های سری‌ها را برمی‌گرداند. |
| [getCategories()](#getCategories--) | دسته‌های اولیه (یا هر دو دسته اولیه و ثانویه اگر ویژگی \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) برابر false باشد) را برمی‌گرداند. |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | اگر false باشد، ویژگی \#getSecondaryCategories.getSecondaryCategories مقدار null برمی‌گرداند و داده‌های موجود در ویژگی \#getCategories.getCategories برای هر دو سری اولیه و ثانویه استفاده می‌شود. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | اگر false باشد، ویژگی \#getSecondaryCategories.getSecondaryCategories مقدار null برمی‌گرداند و داده‌های موجود در ویژگی \#getCategories.getCategories برای هر دو سری اولیه و ثانویه استفاده می‌شود. |
| [getSecondaryCategories()](#getSecondaryCategories--) | دسته‌های ثانویه را برمی‌گرداند اگر ویژگی \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) برابر true باشد. |
| [readWorkbookStream()](#readWorkbookStream--) | کتاب‌خانه‌ی Excel داخلی را در یک جریان حافظه-موقت می‌نویسد. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | کتاب‌خانه‌ی Excel داخلی را با مقدار مشخص‌شده توسط کاربر مقداردهی اولیه می‌کند. |
| [getDataSourceType()](#getDataSourceType--) | مسیر کتاب‌خانه‌ی خارجی را اگر منبع داده خارجی باشد، در غیر این صورت مقدار null را نشان می‌دهد. |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | منبع دادهٔ نمودار را نشان می‌دهد. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | نوع کتاب‌خانه‌ی توکار را برمی‌گرداند. |
| [getRange()](#getRange--) | محدوده داده‌های نمودار را برمی‌گرداند. |
| [setRange(String formula)](#setRange-java.lang.String-) | تنظیم محدوده داده‌های نمودار. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | کتاب‌خانه‌ی خارجی را به عنوان منبع داده برای نمودار تنظیم می‌کند. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | کتاب‌خانه‌ی خارجی را به عنوان منبع داده برای نمودار تنظیم می‌کند. |
| [refreshData()](#refreshData--) | داده‌های نمودار را با بارگذاری دوباره از کتاب‌خانه‌ی منبع به‌روزرسانی می‌کند. |
| [switchRowColumn()](#switchRowColumn--) | داده‌ها را بر روی محورها جابجا می‌کند. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

کارخانه سلول‌ها را برای ایجاد سلول‌های مورد استفاده در سری‌ها یا دسته‌های نمودار برمی‌گرداند. فقط-خواندنی [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**بازگشت:**  
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

سری‌ها را برمی‌گرداند. فقط-خواندنی [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**بازگشت:**  
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

گروه‌های سری‌ها را برمی‌گرداند. فقط-خواندنی [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) هر گروه از سری‌ها شامل سری‌هایی با انواع ترکیبی می‌شود. گروه‌های انواع ترکیبی سری‌ها با استفاده از enum `CombinableSeriesTypesGroup` تعریف و توصیف شده‌اند. همچنین هر گروه شامل سری‌هایی است که بر روی محورهای اولیه یا ثانویه (نه هر دو در یک گروه) ترسیم می‌شوند. بنابراین، اصل گروه‌بندی سری‌ها، گروه‌بندی بر اساس انواع گروه‌های فوق و نوع ترسیم اولیه/ثانویه است. 2) گروه سری‌ها شامل برخی از ویژگی‌های مشترک برای هر سری در گروه است («ویژگی‌های گروه سری»). «ویژگی‌های گروه سری» در کلاس `ChartSeriesGroup` قابل‌خواندن/قابل‌نوشتن است. هر یک از این ویژگی‌ها می‌تواند نمایی فقط-خواندنی در کلاس `ChartSeries` داشته باشد.

**بازگشت:**  
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

دسته‌های اولیه (یا هر دو دسته اولیه و ثانویه اگر ویژگی \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) برابر false باشد) را برمی‌گرداند. فقط-خواندنی [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

اگر ویژگی \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) برابر false باشد، ویژگی (\#getSecondaryCategories.getSecondaryCategories) مقدار null برمی‌گرداند و داده‌های موجود در ویژگی \#getCategories.getCategories برای هر دو سری اولیه و ثانویه استفاده می‌شود. اگر این ویژگی برابر true باشد، داده‌های موجود در ویژگی (\#getSecondaryCategories.getSecondaryCategories) برای سری‌های ثانویه و داده‌های موجود در ویژگی \#getCategories.getCategories برای سری‌های اولیه استفاده می‌شود.

**بازگشت:**  
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

اگر false باشد، ویژگی \#getSecondaryCategories.getSecondaryCategories مقدار null برمی‌گرداند و داده‌های موجود در ویژگی \#getCategories.getCategories برای هر دو سری اولیه و ثانویه استفاده می‌شود. اگر true باشد، داده‌های موجود در ویژگی \#getSecondaryCategories.getSecondaryCategories برای سری‌های ثانویه و داده‌های موجود در ویژگی \#getCategories.getCategories برای سری‌های اولیه استفاده می‌شود. بولی قابل‌خواندن/قابل‌نوشتن.

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

اگر false باشد، ویژگی \#getSecondaryCategories.getSecondaryCategories مقدار null برمی‌گرداند و داده‌های موجود در ویژگی \#getCategories.getCategories برای هر دو سری اولیه و ثانویه استفاده می‌شود. اگر true باشد، داده‌های موجود در ویژگی \#getSecondaryCategories.getSecondaryCategories برای سری‌های ثانویه و داده‌های موجود در ویژگی \#getCategories.getCategories برای سری‌های اولیه استفاده می‌شود. بولی قابل‌خواندن/قابل‌نوشتن.

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

دسته‌های ثانویه را برمی‌گرداند اگر ویژگی \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) برابر true باشد. فقط-خواندنی [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

اگر ویژگی \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) برابر false باشد، این ویژگی (\#getSecondaryCategories.getSecondaryCategories) مقدار null برمی‌گرداند و داده‌های موجود در ویژگی \#getCategories.getCategories برای هر دو سری اولیه و ثانویه استفاده می‌شود. اگر این ویژگی برابر true باشد، داده‌های موجود در این \#getSecondaryCategories.getSecondaryCategories برای سری‌های ثانویه و داده‌های موجود در \#getCategories.getCategories برای سری‌های اولیه استفاده می‌شود.

**بازگشت:**  
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

کتاب‌خانه‌ی Excel داخلی را در یک جریان حافظه-موقت می‌نویسد.

**بازگشت:**  
byte[] - یک نمونهٔ آرایهٔ بایت حاوی کپی‌ای از کتاب‌خانه‌ی Excel داخلی را برمی‌گرداند.

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

کتاب‌خانه‌ی Excel داخلی را با مقدار مشخص‌شده توسط کاربر مقداردهی اولیه می‌کند.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| ms | byte[] | جریان بایتی ارائه‌شده توسط کاربر که شامل تمام کتاب‌خانه‌ی Excel می‌باشد. |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

مسیر کتاب‌خانه‌ی خارجی را اگر منبع داده خارجی باشد، در غیر این صورت مقدار null را نشان می‌دهد.

**بازگشت:**  
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public final String getExternalWorkbookPath()
```

منبع دادهٔ نمودار را نشان می‌دهد.

**بازگشت:**  
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```

نوع کتاب‌خانه‌ی توکار را برمی‌گرداند. اگر `DataSourceType` (\#getDataSourceType.getDataSourceType) برابر [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook) باشد، مقدار [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) برگردانده می‌شود. فقط-خواندنی [WorkbookType](../../com.aspose.slides/workbooktype).

**بازگشت:**  
int

### getRange() {#getRange--}
```
public final String getRange()
```

محدوده داده‌های نمودار را برمی‌گرداند.

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
java.lang.String - فرمول محدوده داده‌های سلول‌ها. مثال: "Sheet1!$A$1:$C$4"

### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

محدوده داده‌های نمودار را تنظیم می‌کند. سری‌ها و دسته‌ها بر اساس محدوده دادهٔ جدید به‌روز می‌شوند. اگر تعداد سری‌ها در محدوده داده بیشتر از تعداد سری‌های موجود در داده‌های نمودار باشد، سری‌های اضافی با همان نوع سری آخر در مجموعهٔ فعلی به انتهای مجموعه اضافه می‌شوند.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| formula | java.lang.String | فرمول محدوده داده‌های سلول‌ها. مثال: "Sheet1!$A$1:$C$4" ، "SomeSheetName!A1:B100" ، "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
```

کتاب‌خانه‌ی خارجی را به عنوان منبع داده برای نمودار تنظیم می‌کند. داده‌های نمودار از کتاب‌خانهٔ هدف به‌روزرسانی می‌شوند.

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
| workbookPath | java.lang.String | مسیر کتاب‌خانهٔ هدف |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public final void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

کتاب‌خانه‌ی خارجی را به عنوان منبع داده برای نمودار تنظیم می‌کند.

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
| workbookPath | java.lang.String | مسیر کتاب‌خانهٔ هدف |
| updateChartData | boolean | اگر مقدار false باشد، فقط مسیر کتاب‌خانه به‌روزرسانی می‌شود. داده‌های نمودار از کتاب‌خانهٔ هدف بارگذاری و به‌روزرسانی نمی‌شوند. می‌تواند زمانی استفاده شود که کتاب‌خانهٔ هدف وجود نداشته باشد یا در دسترس نباشد. اگر مقدار true باشد، داده‌های نمودار از کتاب‌خانهٔ هدف به‌روزرسانی می‌شوند. |

### refreshData() {#refreshData--}
```
public final void refreshData()
```

داده‌های نمودار را با بارگذاری دوباره از کتاب‌خانهٔ منبع به‌روزرسانی می‌کند.

--------------------

> ```
> Presentation presentation = new Presentation("presentationWithChart.pptx");
>  try {
>      IChart chart = (IChart)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      chart.getChartData().refreshData();
>  } finally {
>      presentation.dispose();
>  }
> ```

### switchRowColumn() {#switchRowColumn--}
```
public final void switchRowColumn()
```

داده‌ها را بر روی محورها جابجا می‌کند. داده‌های ترسیم‌شده بر روی محور X به محور Y منتقل می‌شوند و بالعکس.