---
title: ChartData class
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.charts/chartdata/
---
## ChartData فئة

يمثل البيانات المستخدمة لتخطيط المخطط.

يعرض نوع ChartData الأعضاء التالية:

## الخصائص

| Property | Description |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/ar/aspose.slides.charts/chartdata/chart_data_workbook/) | يحصل على مصنع الخلايا لإنشاء الخلايا المستخدمة لسلاسل المخطط أو الفئات.<br/>            للقراءة فقط [`IChartDataWorkbook`](/slides/python-net/ar/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/ar/aspose.slides.charts/chartdata/series/) | يحصل على السلاسل.<br/>            للقراءة فقط [`IChartSeriesCollection`](/slides/python-net/ar/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/ar/aspose.slides.charts/chartdata/series_groups/) | يحصل على مجموعات السلاسل.<br/>            للقراءة فقط [`IChartSeriesGroupCollection`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/ar/aspose.slides.charts/chartdata/categories/) | يحصل على الفئات الأساسية (أو كل من الفئات الأساسية والثانوية <br/>            إذا كانت خاصية [`ChartData.use_secondary_categories`](/slides/python-net/ar/aspose.slides.charts/chartdata/use_secondary_categories) خاطئة).<br/>            للقراءة فقط [`IChartCategoryCollection`](/slides/python-net/ar/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/ar/aspose.slides.charts/chartdata/use_secondary_categories/) | إذا كان خاطئًا فإن خاصية [`ChartData.secondary_categories`](/slides/python-net/ar/aspose.slides.charts/chartdata/secondary_categories) تُعيد None وتُستخدم البيانات <br/>            في خاصية [`ChartData.categories`](/slides/python-net/ar/aspose.slides.charts/chartdata/categories) لكل من السلاسل الأساسية والثانوية.<br/>            إذا كان صحيحًا فإن البيانات في خاصية [`ChartData.secondary_categories`](/slides/python-net/ar/aspose.slides.charts/chartdata/secondary_categories) تُستخدم للسلاسل الثانوية والبيانات <br/>            في خاصية [`ChartData.categories`](/slides/python-net/ar/aspose.slides.charts/chartdata/categories) تُستخدم للسلاسل الأساسية.<br/>            قراءة/كتابة **bool**. |
| [`secondary_categories`](/slides/python-net/ar/aspose.slides.charts/chartdata/secondary_categories/) | يحصل على الفئات الثانوية إذا كانت خاصية [`ChartData.use_secondary_categories`](/slides/python-net/ar/aspose.slides.charts/chartdata/use_secondary_categories) صحيحة.<br/>            للقراءة فقط [`IChartCategoryCollection`](/slides/python-net/ar/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/ar/aspose.slides.charts/chartdata/data_source_type/) | يمثل مسار دفتر العمل الخارجي إذا كان مصدر بيانات خارجي، وإلا None |
| [`external_workbook_path`](/slides/python-net/ar/aspose.slides.charts/chartdata/external_workbook_path/) | يمثل مصدر بيانات المخطط |
| [`embedded_workbook_type`](/slides/python-net/ar/aspose.slides.charts/chartdata/embedded_workbook_type/) | يحصل على نوع دفتر العمل المضمن.<br/>            يُرجع [`WorkbookType.NOT_DEFINED`](/slides/python-net/ar/aspose.slides.charts/workbooktype/NOT_DEFINED) إذا كان [`ChartData.data_source_type`](/slides/python-net/ar/aspose.slides.charts/chartdata/data_source_type) <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/ar/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/>            للقراءة فقط [`WorkbookType`](/slides/python-net/ar/aspose.slides.charts/workbooktype). |

## الطرق

| Method | Description |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/ar/aspose.slides.charts/chartdata/set_external_workbook/#str) | يقوم بتعيين دفتر العمل الخارجي كمصدر بيانات للمخطط. سيتم تحديث بيانات المخطط من دفتر العمل الهدف. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/ar/aspose.slides.charts/chartdata/set_external_workbook/#str-bool) | يقوم بتعيين دفتر العمل الخارجي كمصدر بيانات للمخطط. |
| [`read_workbook_stream(self)`](/slides/python-net/ar/aspose.slides.charts/chartdata/read_workbook_stream/#) | يكتب دفتر عمل Excel المتضمن داخليًا إلى تدفق. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/ar/aspose.slides.charts/chartdata/write_workbook_stream/#iorawiobase) | يقوم بتهيئة دفتر عمل Excel المتضمن داخليًا بالقيمة المحددة من قبل المستخدم. |
| [`get_range(self)`](/slides/python-net/ar/aspose.slides.charts/chartdata/get_range/#) | يحصل على نطاق بيانات المخطط. |
| [`set_range(self, formula)`](/slides/python-net/ar/aspose.slides.charts/chartdata/set_range/#str) | يضبط نطاق بيانات المخطط. سيتم تحديث السلاسل والفئات بناءً على نطاق البيانات الجديد.<br/>            إذا كان عدد السلاسل في نطاق البيانات أكبر من عدد السلاسل في بيانات المخطط فستتم إضافة سلاسل إضافية من نفس النوع<br/>            كسلسلة الأخيرة في المجموعة الحالية إلى نهاية المجموعة. |
| [`refresh_data(self)`](/slides/python-net/ar/aspose.slides.charts/chartdata/refresh_data/#) | يقوم بتحديث بيانات المخطط بإعادة تحميلها من دفتر العمل المصدر. |
| [`switch_row_column(self)`](/slides/python-net/ar/aspose.slides.charts/chartdata/switch_row_column/#) | تبديل البيانات عبر المحور.<br/>            البيانات المرسومة على المحور X ستنتقل إلى المحور Y والعكس بالعكس. |


### انظر أيضًا
* الوحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* المكتبة [`Aspose.Slides`](/slides/python-net)