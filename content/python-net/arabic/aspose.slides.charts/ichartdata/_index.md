---
title: IChartData class
second_title: Aspose.Slides للـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.charts/ichartdata/
---
# IChartData فئة

يمثل البيانات المستخدمة لرسم المخطط.

نوع IChartData يعرض الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/ar/aspose.slides.charts/ichartdata/chart_data_workbook/) | يجلب مصنع الخلايا لإنشاء خلايا تُستخدم في سلاسل المخطط أو الفئات.<br/>            قراءة فقط [`IChartDataWorkbook`](/slides/python-net/ar/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/ar/aspose.slides.charts/ichartdata/series/) | يجلب السلاسل.<br/>            قراءة فقط [`IChartSeriesCollection`](/slides/python-net/ar/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/ar/aspose.slides.charts/ichartdata/series_groups/) | يجلب مجموعات السلاسل.<br/>            قراءة فقط [`IChartSeriesGroupCollection`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/ar/aspose.slides.charts/ichartdata/categories/) | يجلب الفئات الأساسية (أو الفئات الأساسية والثانوية معًا <br/>            إذا كانت الخاصية [`IChartData.use_secondary_categories`](/slides/python-net/ar/aspose.slides.charts/ichartdata/use_secondary_categories) خاطئة).<br/>            قراءة فقط [`IChartCategoryCollection`](/slides/python-net/ar/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/ar/aspose.slides.charts/ichartdata/use_secondary_categories/) | إذا كانت القيمة خاطئة فإن الخاصية [`IChartData.secondary_categories`](/slides/python-net/ar/aspose.slides.charts/ichartdata/secondary_categories) تُعيد None وبيانات الخاصية [`IChartData.categories`](/slides/python-net/ar/aspose.slides.charts/ichartdata/categories) تُستخدم لكل من السلاسل الأساسية والثانوية.<br/>            إذا كانت القيمة صحيحة فإن بيانات الخاصية [`IChartData.secondary_categories`](/slides/python-net/ar/aspose.slides.charts/ichartdata/secondary_categories) تُستخدم للسلاسل الثانوية وبيانات الخاصية [`IChartData.categories`](/slides/python-net/ar/aspose.slides.charts/ichartdata/categories) تُستخدم للسلاسل الأساسية.<br/>            قراءة/كتابة **bool**. |
| [`secondary_categories`](/slides/python-net/ar/aspose.slides.charts/ichartdata/secondary_categories/) | يجلب الفئات الثانوية إذا كانت الخاصية [`IChartData.use_secondary_categories`](/slides/python-net/ar/aspose.slides.charts/ichartdata/use_secondary_categories) صحيحة.<br/>            قراءة فقط [`IChartCategoryCollection`](/slides/python-net/ar/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/ar/aspose.slides.charts/ichartdata/data_source_type/) | يمثل مصدر بيانات المخطط |
| [`external_workbook_path`](/slides/python-net/ar/aspose.slides.charts/ichartdata/external_workbook_path/) | يمثل مسار المصنف الخارجي إذا كان مصدر البيانات خارجيًا، وإلا يكون None |
| [`embedded_workbook_type`](/slides/python-net/ar/aspose.slides.charts/ichartdata/embedded_workbook_type/) | يجلب نوع المصنف المضمّن.<br/>            يُعيد [`WorkbookType.NOT_DEFINED`](/slides/python-net/ar/aspose.slides.charts/workbooktype/NOT_DEFINED) إذا كان [`IChartData.data_source_type`](/slides/python-net/ar/aspose.slides.charts/ichartdata/data_source_type) هو <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/ar/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/>            قراءة فقط [`WorkbookType`](/slides/python-net/ar/aspose.slides.charts/workbooktype). |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/ar/aspose.slides.charts/ichartdata/set_external_workbook/#str) |يضبط المصنف الخارجي كمصدر بيانات للمخطط. سيتم تحديث بيانات المخطط من المصنف الهدف. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/ar/aspose.slides.charts/ichartdata/set_external_workbook/#str-bool) |يضبط المصنف الخارجي كمصدر بيانات للمخطط. |
| [`read_workbook_stream(self)`](/slides/python-net/ar/aspose.slides.charts/ichartdata/read_workbook_stream/#) |يكتب المصنف الداخلي من نوع Excel إلى تدفق في الذاكرة. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/ar/aspose.slides.charts/ichartdata/write_workbook_stream/#iorawiobase) |يُهيئ المصنف الداخلي من نوع Excel بالقيمة المحددة من قبل المستخدم. |
| [`set_range(self, formula)`](/slides/python-net/ar/aspose.slides.charts/ichartdata/set_range/#str) |يضبط نطاق بيانات المخطط. سيتم تحديث السلاسل والفئات بناءً على نطاق البيانات الجديد.<br/>            إذا كان عدد السلاسل في نطاق البيانات أكبر من عدد السلاسل في بيانات المخطط فسيتم إضافة سلاسل إضافية من نفس النوع<br/>            كسلسلة الأخيرة في المجموعة الحالية إلى نهاية المجموعة. |
| [`get_range(self)`](/slides/python-net/ar/aspose.slides.charts/ichartdata/get_range/#) |يجلب نطاق بيانات المخطط. |
| [`switch_row_column(self)`](/slides/python-net/ar/aspose.slides.charts/ichartdata/switch_row_column/#) |تبديل البيانات عبر المحور.<br/>            البيانات التي تُرسم على المحور X ستنتقل إلى المحور Y والعكس بالعكس. |

### انظر أيضًا
* الوحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* المكتبة [`Aspose.Slides`](/slides/python-net)