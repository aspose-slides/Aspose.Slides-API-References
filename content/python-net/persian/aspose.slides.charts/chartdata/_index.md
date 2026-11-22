---
title: ChartData class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.charts/chartdata/
---
## ChartData کلاس

داده‌هایی را که برای رسم نمودار استفاده می‌شود، نمایندگی می‌کند.

نوع ChartData اعضای زیر را در اختیار می‌گذارد:

## ویژگی‌ها

| Property | Description |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/fa/aspose.slides.charts/chartdata/chart_data_workbook/) | کارخانه سلول‌ها را برای ایجاد سلول‌های استفاده‌شده در سری‌های نمودار یا دسته‌ها دریافت می‌کند.<br/>            فقط-خواندنی [`IChartDataWorkbook`](/slides/python-net/fa/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/fa/aspose.slides.charts/chartdata/series/) | سری‌ها را دریافت می‌کند.<br/>            فقط-خواندنی [`IChartSeriesCollection`](/slides/python-net/fa/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/fa/aspose.slides.charts/chartdata/series_groups/) | گروه‌های سری‌ها را دریافت می‌کند.<br/>            فقط-خواندنی [`IChartSeriesGroupCollection`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/fa/aspose.slides.charts/chartdata/categories/) | دسته‌های اصلی را دریافت می‌کند (یا هر دو دستهٔ اصلی و ثانویه <br/>            اگر [`ChartData.use_secondary_categories`](/slides/python-net/fa/aspose.slides.charts/chartdata/use_secondary_categories) false باشد).<br/>            فقط-خواندنی [`IChartCategoryCollection`](/slides/python-net/fa/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/fa/aspose.slides.charts/chartdata/use_secondary_categories/) | اگر false باشد، ویژگی [`ChartData.secondary_categories`](/slides/python-net/fa/aspose.slides.charts/chartdata/secondary_categories) مقدار None برمی‌گرداند و داده در [`ChartData.categories`](/slides/python-net/fa/aspose.slides.charts/chartdata/categories) برای هر دو سری اصلی و ثانویه استفاده می‌شود.<br/>            اگر true باشد، داده در [`ChartData.secondary_categories`](/slides/python-net/fa/aspose.slides.charts/chartdata/secondary_categories) برای سری‌های ثانویه و داده در [`ChartData.categories`](/slides/python-net/fa/aspose.slides.charts/chartdata/categories) برای سری‌های اصلی استفاده می‌شود.<br/>            خواندن/نوشتن **bool**. |
| [`secondary_categories`](/slides/python-net/fa/aspose.slides.charts/chartdata/secondary_categories/) | دسته‌های ثانویه را دریافت می‌کند اگر [`ChartData.use_secondary_categories`](/slides/python-net/fa/aspose.slides.charts/chartdata/use_secondary_categories) true باشد.<br/>            فقط-خواندنی [`IChartCategoryCollection`](/slides/python-net/fa/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/fa/aspose.slides.charts/chartdata/data_source_type/) | مسیر کتاب‌کار خارجی را نمایندگی می‌کند اگر منبع داده خارجی باشد، در غیر این صورت None |
| [`external_workbook_path`](/slides/python-net/fa/aspose.slides.charts/chartdata/external_workbook_path/) | منبع دادهٔ نمودار را نمایندگی می‌کند |
| [`embedded_workbook_type`](/slides/python-net/fa/aspose.slides.charts/chartdata/embedded_workbook_type/) | نوع کتاب‌کار توکار را دریافت می‌کند.<br/>            اگر [`ChartData.data_source_type`](/slides/python-net/fa/aspose.slides.charts/chartdata/data_source_type) <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/fa/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) باشد، [`WorkbookType.NOT_DEFINED`](/slides/python-net/fa/aspose.slides.charts/workbooktype/NOT_DEFINED) برگردانده می‌شود.<br/>            فقط-خواندنی [`WorkbookType`](/slides/python-net/fa/aspose.slides.charts/workbooktype). |

## متدها

| Method | Description |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/fa/aspose.slides.charts/chartdata/set_external_workbook/#str) | کتاب‌کار خارجی را به عنوان منبع داده برای نمودار تنظیم می‌کند. داده‌های نمودار از کتاب‌کار هدف به‌روز خواهد شد. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/fa/aspose.slides.charts/chartdata/set_external_workbook/#str-bool) | کتاب‌کار خارجی را به عنوان منبع داده برای نمودار تنظیم می‌کند. |
| [`read_workbook_stream(self)`](/slides/python-net/fa/aspose.slides.charts/chartdata/read_workbook_stream/#) | کتاب‌کار Excel داخلی را به یک جریان می‌نویسد. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/fa/aspose.slides.charts/chartdata/write_workbook_stream/#iorawiobase) | کتاب‌کار Excel داخلی را با مقدار مشخص‌شده توسط کاربر مقداردهی اولیه می‌کند. |
| [`get_range(self)`](/slides/python-net/fa/aspose.slides.charts/chartdata/get_range/#) | محدودهٔ دادهٔ نمودار را دریافت می‌کند. |
| [`set_range(self, formula)`](/slides/python-net/fa/aspose.slides.charts/chartdata/set_range/#str) | محدودهٔ دادهٔ نمودار را تنظیم می‌کند. سری‌ها و دسته‌ها بر اساس محدودهٔ دادهٔ جدید به‌روز می‌شوند.<br/>            اگر تعداد سری‌ها در محدودهٔ داده بیشتر از تعداد سری‌ها در دادهٔ نمودار باشد، سری‌های اضافی با همان نوع<br/>            همانند آخرین سری در مجموعهٔ جاری به انتهای مجموعه اضافه می‌شوند. |
| [`refresh_data(self)`](/slides/python-net/fa/aspose.slides.charts/chartdata/refresh_data/#) | داده‌های نمودار را با بارگذاری مجدد از کتاب‌کار منبع تازه می‌کند. |
| [`switch_row_column(self)`](/slides/python-net/fa/aspose.slides.charts/chartdata/switch_row_column/#) | داده‌ها را بر روی محور جابه‌جا می‌کند.<br/>            داده‌های نمودار شده بر محور X به محور Y منتقل می‌شوند و بالعکس. |

### همچنین ببینید
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)