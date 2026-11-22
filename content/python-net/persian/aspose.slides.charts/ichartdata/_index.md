---
title: IChartData class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.charts/ichartdata/
---
## IChartData کلاس

داده‌هایی را که برای رسم نمودار استفاده می‌شود، نشان می‌دهد.

نوع IChartData اعضای زیر را ارائه می‌دهد:

## خصوصیات

| Property | Description |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/fa/aspose.slides.charts/ichartdata/chart_data_workbook/) | فابریک سلول‌ها را برای ایجاد سلول‌های مورد استفاده در سری‌ها یا دسته‌های نمودار دریافت می‌کند.<br/>            فقط خواندنی [`IChartDataWorkbook`](/slides/python-net/fa/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/fa/aspose.slides.charts/ichartdata/series/) | سری‌ها را دریافت می‌کند.<br/>            فقط خواندنی [`IChartSeriesCollection`](/slides/python-net/fa/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/fa/aspose.slides.charts/ichartdata/series_groups/) | گروه‌های سری را دریافت می‌کند.<br/>            فقط خواندنی [`IChartSeriesGroupCollection`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/fa/aspose.slides.charts/ichartdata/categories/) | دسته‌بندی‌های اصلی (یا هم دسته‌بندی‌های اصلی و ثانویه <br/>            اگر [`IChartData.use_secondary_categories`](/slides/python-net/fa/aspose.slides.charts/ichartdata/use_secondary_categories) برابر false باشد).<br/>            فقط خواندنی [`IChartCategoryCollection`](/slides/python-net/fa/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/fa/aspose.slides.charts/ichartdata/use_secondary_categories/) | اگر false باشد، ویژگی [`IChartData.secondary_categories`](/slides/python-net/fa/aspose.slides.charts/ichartdata/secondary_categories) مقدار None را برمی‌گرداند و داده‌ها در ویژگی [`IChartData.categories`](/slides/python-net/fa/aspose.slides.charts/ichartdata/categories) برای هر دو مجموعه اصلی و ثانویه استفاده می‌شود.<br/>            اگر true باشد، داده‌ها در ویژگی [`IChartData.secondary_categories`](/slides/python-net/fa/aspose.slides.charts/ichartdata/secondary_categories) برای مجموعه‌های ثانویه و داده‌ها در ویژگی [`IChartData.categories`](/slides/python-net/fa/aspose.slides.charts/ichartdata/categories) برای مجموعه‌های اصلی استفاده می‌شود.<br/>            خواندن/نوشتن **bool**. |
| [`secondary_categories`](/slides/python-net/fa/aspose.slides.charts/ichartdata/secondary_categories/) | دسته‌بندی‌های ثانویه را دریافت می‌کند اگر ویژگی [`IChartData.use_secondary_categories`](/slides/python-net/fa/aspose.slides.charts/ichartdata/use_secondary_categories) برابر true باشد.<br/>            فقط خواندنی [`IChartCategoryCollection`](/slides/python-net/fa/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/fa/aspose.slides.charts/ichartdata/data_source_type/) | منبع داده‌ی نمودار را نشان می‌دهد |
| [`external_workbook_path`](/slides/python-net/fa/aspose.slides.charts/ichartdata/external_workbook_path/) | مسیر کتاب کار خارجی را نشان می‌دهد اگر منبع داده خارجی باشد، در غیر این صورت None |
| [`embedded_workbook_type`](/slides/python-net/fa/aspose.slides.charts/ichartdata/embedded_workbook_type/) | نوع کتاب کار تعبیه‌شده را دریافت می‌کند.<br/>            اگر [`IChartData.data_source_type`](/slides/python-net/fa/aspose.slides.charts/ichartdata/data_source_type) برابر <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/fa/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) باشد، [`WorkbookType.NOT_DEFINED`](/slides/python-net/fa/aspose.slides.charts/workbooktype/NOT_DEFINED) را برمی‌گرداند.<br/>            فقط خواندنی [`WorkbookType`](/slides/python-net/fa/aspose.slides.charts/workbooktype). |

## متدها

| Method | Description |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/fa/aspose.slides.charts/ichartdata/set_external_workbook/#str) | کتاب کار خارجی را به عنوان منبع داده برای نمودار تنظیم می‌کند. داده‌های نمودار از کتاب کار هدف به‌روز خواهند شد. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/fa/aspose.slides.charts/ichartdata/set_external_workbook/#str-bool) | کتاب کار خارجی را به عنوان منبع داده برای نمودار تنظیم می‌کند. |
| [`read_workbook_stream(self)`](/slides/python-net/fa/aspose.slides.charts/ichartdata/read_workbook_stream/#) | کتاب کار Excel داخلی را به یک جریان در حافظه می‌نویسد. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/fa/aspose.slides.charts/ichartdata/write_workbook_stream/#iorawiobase) | کتاب کار Excel داخلی را با مقدار مشخص‌شده توسط کاربر مقداردهی اولیه می‌کند. |
| [`set_range(self, formula)`](/slides/python-net/fa/aspose.slides.charts/ichartdata/set_range/#str) | محدوده داده‌های نمودار را تنظیم می‌کند. سری‌ها و دسته‌بندی‌ها بر اساس محدوده داده جدید به‌روز می‌شوند.<br/>            اگر تعداد سری‌ها در محدوده داده بیشتر از تعداد سری‌ها در داده‌های نمودار باشد، سری‌های اضافی با همان نوع<br/>            مانند آخرین سری در مجموعه فعلی به انتهای مجموعه اضافه می‌شوند. |
| [`get_range(self)`](/slides/python-net/fa/aspose.slides.charts/ichartdata/get_range/#) | محدوده داده‌های نمودار را دریافت می‌کند. |
| [`switch_row_column(self)`](/slides/python-net/fa/aspose.slides.charts/ichartdata/switch_row_column/#) | داده‌ها را روی محور جابجا می‌کند.<br/>            داده‌ای که در محور X نمودار شده است به محور Y منتقل می‌شود و بالعکس. |
| [`refresh_data(self)`](/slides/python-net/fa/aspose.slides.charts/ichartdata/refresh_data/#) | داده‌های نمودار را با بارگذاری مجدد از کتاب کار منبع، تازه‌سازی می‌کند. |


### مراجع
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)