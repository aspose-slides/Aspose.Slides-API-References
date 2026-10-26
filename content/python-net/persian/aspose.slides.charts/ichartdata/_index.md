---
title: IChartData class
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.charts/ichartdata/
---
## IChartData کلاس

داده‌های استفاده‌شده برای رسم نمودار را نمایش می‌دهد.

نوع IChartData اعضای زیر را در دسترس می‌گذارد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/fa/aspose.slides.charts/ichartdata/chart_data_workbook/) | کارگاه سلول‌ها را برای ایجاد سلول‌های استفاده‌شده در سری‌ها یا دسته‌بندهای نمودار برمی‌گرداند.<br/>            فقط خواندنی [`IChartDataWorkbook`](/slides/python-net/fa/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/fa/aspose.slides.charts/ichartdata/series/) | سری‌ها را برمی‌گرداند.<br/>            فقط خواندنی [`IChartSeriesCollection`](/slides/python-net/fa/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/fa/aspose.slides.charts/ichartdata/series_groups/) | گروه‌های سری‌ها را برمی‌گرداند.<br/>            فقط خواندنی [`IChartSeriesGroupCollection`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/fa/aspose.slides.charts/ichartdata/categories/) | دسته‌بندهای اصلی (یا هر دو دسته‌بند اصلی و ثانویه <br/>            اگر ویژگی [`IChartData.use_secondary_categories`](/slides/python-net/fa/aspose.slides.charts/ichartdata/use_secondary_categories) برابر false باشد) را برمی‌گرداند.<br/>            فقط خواندنی [`IChartCategoryCollection`](/slides/python-net/fa/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/fa/aspose.slides.charts/ichartdata/use_secondary_categories/) | اگر false باشد ویژگی [`IChartData.secondary_categories`](/slides/python-net/fa/aspose.slides.charts/ichartdata/secondary_categories) مقدار None را برمی‌گرداند و داده در<br/>            ویژگی [`IChartData.categories`](/slides/python-net/fa/aspose.slides.charts/ichartdata/categories) هم برای سری‌های اصلی و هم برای سری‌های ثانویه استفاده می‌شود.<br/>            اگر true باشد داده در ویژگی [`IChartData.secondary_categories`](/slides/python-net/fa/aspose.slides.charts/ichartdata/secondary_categories) برای سری‌های ثانویه و داده<br/>            در ویژگی [`IChartData.categories`](/slides/python-net/fa/aspose.slides.charts/ichartdata/categories) برای سری‌های اصلی استفاده می‌شود.<br/>            قابل نوشتن **bool**. |
| [`secondary_categories`](/slides/python-net/fa/aspose.slides.charts/ichartdata/secondary_categories/) | دسته‌بندهای ثانویه را اگر ویژگی [`IChartData.use_secondary_categories`](/slides/python-net/fa/aspose.slides.charts/ichartdata/use_secondary_categories) برابر true باشد برمی‌گرداند.<br/>            فقط خواندنی [`IChartCategoryCollection`](/slides/python-net/fa/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/fa/aspose.slides.charts/ichartdata/data_source_type/) | منبع داده‌های نمودار را نمایش می‌دهد |
| [`external_workbook_path`](/slides/python-net/fa/aspose.slides.charts/ichartdata/external_workbook_path/) | مسیر کتاب کار خارجی را نمایش می‌دهد اگر منبع داده خارجی باشد، در غیر این صورت None |
| [`embedded_workbook_type`](/slides/python-net/fa/aspose.slides.charts/ichartdata/embedded_workbook_type/) | نوع کتاب کار جاسازی‌شده را برمی‌گرداند.<br/>            اگر [`IChartData.data_source_type`](/slides/python-net/fa/aspose.slides.charts/ichartdata/data_source_type) [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/fa/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) باشد [`WorkbookType.NOT_DEFINED`](/slides/python-net/fa/aspose.slides.charts/workbooktype/NOT_DEFINED) را برمی‌گرداند.<br/>            فقط خواندنی [`WorkbookType`](/slides/python-net/fa/aspose.slides.charts/workbooktype). |

## متدها

| متد | توضیح |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/fa/aspose.slides.charts/ichartdata/set_external_workbook/#str) | کتاب کار خارجی را به عنوان منبع داده برای نمودار تنظیم می‌کند. داده‌های نمودار از کتاب کار هدف به‌روزرسانی خواهند شد. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/fa/aspose.slides.charts/ichartdata/set_external_workbook/#str-bool) | کتاب کار خارجی را به عنوان منبع داده برای نمودار تنظیم می‌کند. |
| [`read_workbook_stream(self)`](/slides/python-net/fa/aspose.slides.charts/ichartdata/read_workbook_stream/#) | کتاب کار Excel داخلی را به یک جریان در حافظه می‌نویسد. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/fa/aspose.slides.charts/ichartdata/write_workbook_stream/#iorawiobase) | کتاب کار Excel داخلی را با مقدار مشخص‌شده توسط کاربر مقداردهی اولیه می‌کند. |
| [`set_range(self, formula)`](/slides/python-net/fa/aspose.slides.charts/ichartdata/set_range/#str) | محدوده داده‌های نمودار را تنظیم می‌کند. سری‌ها و دسته‌بندها بر اساس محدوده داده جدید به‌روزرسانی می‌شوند.<br/>            اگر تعداد سری‌ها در محدوده داده بیش از تعداد سری‌های موجود در داده‌های نمودار باشد، سری‌های اضافی با همان نوع<br/>            که آخرین سری در مجموعه جاری دارد، به انتهای مجموعه اضافه می‌شوند. |
| [`get_range(self)`](/slides/python-net/fa/aspose.slides.charts/ichartdata/get_range/#) | محدوده داده‌های نمودار را برمی‌گرداند. |
| [`switch_row_column(self)`](/slides/python-net/fa/aspose.slides.charts/ichartdata/switch_row_column/#) | داده‌ها را روی محور جابجا می‌کند.<br/>            داده‌های نمودار شده بر محور X به محور Y منتقل می‌شوند و بالعکس. |

### همچنین ببینید
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)