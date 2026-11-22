---
title: IChartData class
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.charts/ichartdata/
---
## IChartData فئة

يمثل البيانات المستخدمة لرسم المخطط.

النوع IChartData يكشف عن الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/ar/aspose.slides.charts/ichartdata/chart_data_workbook/) | يحصل على مصنع الخلايا لإنشاء الخلايا المستخدمة في سلاسل المخطط أو الفئات.<br/>            قراءة فقط [`IChartDataWorkbook`](/slides/python-net/ar/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/ar/aspose.slides.charts/ichartdata/series/) | يحصل على السلاسل.<br/>            قراءة فقط [`IChartSeriesCollection`](/slides/python-net/ar/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/ar/aspose.slides.charts/ichartdata/series_groups/) | يحصل على مجموعات السلاسل.<br/>            قراءة فقط [`IChartSeriesGroupCollection`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/ar/aspose.slides.charts/ichartdata/categories/) | يحصل على الفئات الأولية (أو كل من الفئات الأولية والثانوية <br/>            إذا كانت الخاصية [`IChartData.use_secondary_categories`](/slides/python-net/ar/aspose.slides.charts/ichartdata/use_secondary_categories) خاطئة).<br/>            قراءة فقط [`IChartCategoryCollection`](/slides/python-net/ar/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/ar/aspose.slides.charts/ichartdata/use_secondary_categories/) | إذا كان false ثم تُعيد الخاصية [`IChartData.secondary_categories`](/slides/python-net/ar/aspose.slides.charts/ichartdata/secondary_categories) قيمة None وتُستخدم البيانات في الخاصية [`IChartData.categories`](/slides/python-net/ar/aspose.slides.charts/ichartdata/categories) لكل من السلاسل الأولية والثانوية.<br/>            إذا كان true تُستخدم البيانات في الخاصية [`IChartData.secondary_categories`](/slides/python-net/ar/aspose.slides.charts/ichartdata/secondary_categories) للسلاسل الثانوية والبيانات في الخاصية [`IChartData.categories`](/slides/python-net/ar/aspose.slides.charts/ichartdata/categories) للسلاسل الأولية.<br/>            قراءة/كتابة **bool**. |
| [`secondary_categories`](/slides/python-net/ar/aspose.slides.charts/ichartdata/secondary_categories/) | يحصل على الفئات الثانوية إذا كانت الخاصية [`IChartData.use_secondary_categories`](/slides/python-net/ar/aspose.slides.charts/ichartdata/use_secondary_categories) صحيحة.<br/>            قراءة فقط [`IChartCategoryCollection`](/slides/python-net/ar/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/ar/aspose.slides.charts/ichartdata/data_source_type/) | يمثل مصدر بيانات المخطط |
| [`external_workbook_path`](/slides/python-net/ar/aspose.slides.charts/ichartdata/external_workbook_path/) | يمثل مسار دفتر العمل الخارجي إذا كان مصدر البيانات خارجيًا، وإلا None |
| [`embedded_workbook_type`](/slides/python-net/ar/aspose.slides.charts/ichartdata/embedded_workbook_type/) | يحصل على نوع دفتر العمل المدمج.<br/>            يرجع [`WorkbookType.NOT_DEFINED`](/slides/python-net/ar/aspose.slides.charts/workbooktype/NOT_DEFINED) إذا كان [`IChartData.data_source_type`](/slides/python-net/ar/aspose.slides.charts/ichartdata/data_source_type) هو <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/ar/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/>            قراءة فقط [`WorkbookType`](/slides/python-net/ar/aspose.slides.charts/workbooktype). |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/ar/aspose.slides.charts/ichartdata/set_external_workbook/#str) | يضبط دفتر العمل الخارجي كمصدر بيانات للمخطط. سيتم تحديث بيانات المخطط من دفتر العمل الهدف. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/ar/aspose.slides.charts/ichartdata/set_external_workbook/#str-bool) | يضبط دفتر العمل الخارجي كمصدر بيانات للمخطط. |
| [`read_workbook_stream(self)`](/slides/python-net/ar/aspose.slides.charts/ichartdata/read_workbook_stream/#) | يكتب دفتر العمل Excel الموجود داخليًا إلى تدفق في الذاكرة. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/ar/aspose.slides.charts/ichartdata/write_workbook_stream/#iorawiobase) | يُهيئ دفتر العمل Excel الموجود داخليًا بالقيمة المحددة من قبل المستخدم. |
| [`set_range(self, formula)`](/slides/python-net/ar/aspose.slides.charts/ichartdata/set_range/#str) | تعيين نطاق بيانات المخطط. سيتم تحديث السلاسل والفئات بناءً على نطاق البيانات الجديد.<br/>            إذا كان عدد السلاسل في نطاق البيانات أكبر من عدد السلاسل في بيانات المخطط فستُضاف سلاسل إضافية من نفس النوع<br/>            كسلسلة الأخيرة في المجموعة الحالية إلى نهاية المجموعة. |
| [`get_range(self)`](/slides/python-net/ar/aspose.slides.charts/ichartdata/get_range/#) | يحصل على نطاق بيانات المخطط. |
| [`switch_row_column(self)`](/slides/python-net/ar/aspose.slides.charts/ichartdata/switch_row_column/#) | تبديل البيانات عبر المحور.<br/>            البيانات المرسومة على المحور X ستنتقل إلى المحور Y والعكس بالعكس. |
| [`refresh_data(self)`](/slides/python-net/ar/aspose.slides.charts/ichartdata/refresh_data/#) | تحديث بيانات المخطط بإعادة تحميلها من دفتر العمل المصدر. |

### انظر أيضًا
* الوحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* المكتبة [`Aspose.Slides`](/slides/python-net)