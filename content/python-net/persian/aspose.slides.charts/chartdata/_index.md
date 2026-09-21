---
title: ChartData class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.charts/chartdata/
---
## ChartData کلاس

نمایش داده‌های استفاده‌شده برای رسم نمودار.

نوع ChartData اعضای زیر را ارائه می‌دهد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/fa/aspose.slides.charts/chartdata/chart_data_workbook/) | دریافت کارخانه‌ی سلول‌ها برای ایجاد سلول‌های استفاده‌شده برای سری‌های نمودار یا دسته‌ها.<br/> فقط-خواندنی [`IChartDataWorkbook`](/slides/python-net/fa/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/fa/aspose.slides.charts/chartdata/series/) | دریافت سری‌ها.<br/> فقط-خواندنی [`IChartSeriesCollection`](/slides/python-net/fa/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/fa/aspose.slides.charts/chartdata/series_groups/) | دریافت گروه‌های سری‌ها.<br/> فقط-خواندنی [`IChartSeriesGroupCollection`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/fa/aspose.slides.charts/chartdata/categories/) | دریافت دسته‌های اصلی (یا هر دو دستهٔ اصلی و ثانوی اگر ویژگی [`ChartData.use_secondary_categories`](/slides/python-net/fa/aspose.slides.charts/chartdata/use_secondary_categories) برابر false باشد).<br/> فقط-خواندنی [`IChartCategoryCollection`](/slides/python-net/fa/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/fa/aspose.slides.charts/chartdata/use_secondary_categories/) | اگر false باشد، ویژگی [`ChartData.secondary_categories`](/slides/python-net/fa/aspose.slides.charts/chartdata/secondary_categories) None برمی‌گرداند و داده در ویژگی [`ChartData.categories`](/slides/python-net/fa/aspose.slides.charts/chartdata/categories) برای هر دو سری اصلی و ثانوی استفاده می‌شود.<br/> اگر true باشد، داده در ویژگی [`ChartData.secondary_categories`](/slides/python-net/fa/aspose.slides.charts/chartdata/secondary_categories) برای سری‌های ثانوی و داده در ویژگی [`ChartData.categories`](/slides/python-net/fa/aspose.slides.charts/chartdata/categories) برای سری‌های اصلی استفاده می‌شود.<br/> خواندنی/قابل نوشتن **bool**. |
| [`secondary_categories`](/slides/python-net/fa/aspose.slides.charts/chartdata/secondary_categories/) | دریافت دسته‌های ثانوی اگر ویژگی [`ChartData.use_secondary_categories`](/slides/python-net/fa/aspose.slides.charts/chartdata/use_secondary_categories) برابر true باشد.<br/> فقط-خواندنی [`IChartCategoryCollection`](/slides/python-net/fa/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/fa/aspose.slides.charts/chartdata/data_source_type/) | نمایش مسیر کتاب‌کار خارجی اگر منبع داده خارجی باشد، در غیر این صورت None |
| [`external_workbook_path`](/slides/python-net/fa/aspose.slides.charts/chartdata/external_workbook_path/) | نمایش منبع دادهٔ نمودار |
| [`embedded_workbook_type`](/slides/python-net/fa/aspose.slides.charts/chartdata/embedded_workbook_type/) | دریافت نوع کتاب‌کار درون‌ریزی شده.<br/> باز می‌گرداند [`WorkbookType.NOT_DEFINED`](/slides/python-net/fa/aspose.slides.charts/workbooktype/NOT_DEFINED) اگر [`ChartData.data_source_type`](/slides/python-net/fa/aspose.slides.charts/chartdata/data_source_type) باشد <br/> [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/fa/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/> فقط-خواندنی [`WorkbookType`](/slides/python-net/fa/aspose.slides.charts/workbooktype). |

## متدها

| متد | توضیح |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/fa/aspose.slides.charts/chartdata/set_external_workbook/#str) | تنظیم کتاب‌کار خارجی به عنوان منبع داده برای نمودار. داده‌های نمودار از کتاب‌کار هدف به‌روز خواهد شد. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/fa/aspose.slides.charts/chartdata/set_external_workbook/#str-bool) | تنظیم کتاب‌کار خارجی به عنوان منبع داده برای نمودار. |
| [`read_workbook_stream(self)`](/slides/python-net/fa/aspose.slides.charts/chartdata/read_workbook_stream/#) | نوشتن کتاب‌کار Excel داخلی به یک جریان. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/fa/aspose.slides.charts/chartdata/write_workbook_stream/#iorawiobase) | مقداردهی اولیه کتاب‌کار Excel داخلی با مقدار مشخص‌شده توسط کاربر. |
| [`get_range(self)`](/slides/python-net/fa/aspose.slides.charts/chartdata/get_range/#) | دریافت بازهٔ دادهٔ نمودار. |
| [`set_range(self, formula)`](/slides/python-net/fa/aspose.slides.charts/chartdata/set_range/#str) | تنظیم بازهٔ دادهٔ نمودار. سری‌ها و دسته‌ها بر اساس بازهٔ دادهٔ جدید به‌روز خواهند شد.<br/> اگر تعداد سری‌ها در بازه داده بیشتر از تعداد سری‌ها در دادهٔ نمودار باشد، سری‌های اضافی با همان نوع همانند آخرین سری در مجموعهٔ فعلی، به انتهای مجموعه اضافه خواهند شد. |
| [`switch_row_column(self)`](/slides/python-net/fa/aspose.slides.charts/chartdata/switch_row_column/#) | جابه‌جایی داده‌ها در محور.<br/> داده‌های نمودار شده در محور X به محور Y منتقل می‌شوند و بالعکس. |

### مراجع
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)