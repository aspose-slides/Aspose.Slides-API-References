---
title: ChartData class
second_title: Aspose.Slides للبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.charts/chartdata/
---
## فئة ChartData

يمثِّل البيانات المستخدمة في رسم المخططات.

نوع ChartData يُظهر الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/ar/aspose.slides.charts/chartdata/chart_data_workbook/) | يحصل على مصنع الخلايا لإنشاء الخلايا المستخدمة لسلاسل المخطط أو الفئات.<br/>            للقراءة فقط [`IChartDataWorkbook`](/slides/python-net/ar/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/ar/aspose.slides.charts/chartdata/series/) | يحصل على السلاسل.<br/>            للقراءة فقط [`IChartSeriesCollection`](/slides/python-net/ar/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/ar/aspose.slides.charts/chartdata/series_groups/) | يحصل على مجموعات السلاسل.<br/>            للقراءة فقط [`IChartSeriesGroupCollection`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/ar/aspose.slides.charts/chartdata/categories/) | يحصل على الفئات الأولية (أو كلًّا من الفئات الأولية والثانوية <br/>            إذا كانت الخاصية [`ChartData.use_secondary_categories`](/slides/python-net/ar/aspose.slides.charts/chartdata/use_secondary_categories) خاطئة).<br/>            للقراءة فقط [`IChartCategoryCollection`](/slides/python-net/ar/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/ar/aspose.slides.charts/chartdata/use_secondary_categories/) | إذا كانت خاطئة فإن الخاصية [`ChartData.secondary_categories`](/slides/python-net/ar/aspose.slides.charts/chartdata/secondary_categories) تُعيد None والبيانات <br/>            في الخاصية [`ChartData.categories`](/slides/python-net/ar/aspose.slides.charts/chartdata/categories) تُستَخدم لكلّ من السلاسل الأولية والثانوية.<br/>            إذا كانت صحيحة فإن البيانات في الخاصية [`ChartData.secondary_categories`](/slides/python-net/ar/aspose.slides.charts/chartdata/secondary_categories) تُستَخدم للسلاسل الثانوية والبيانات <br/>            في الخاصية [`ChartData.categories`](/slides/python-net/ar/aspose.slides.charts/chartdata/categories) تُستَخدم للسلاسل الأولية.<br/>            قابل للقراءة/الكتابة **bool**. |
| [`secondary_categories`](/slides/python-net/ar/aspose.slides.charts/chartdata/secondary_categories/) | يحصل على الفئات الثانوية إذا كانت الخاصية [`ChartData.use_secondary_categories`](/slides/python-net/ar/aspose.slides.charts/chartdata/use_secondary_categories) صحيحة.<br/>            للقراءة فقط [`IChartCategoryCollection`](/slides/python-net/ar/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/ar/aspose.slides.charts/chartdata/data_source_type/) | يمثِّل مسار المصنف الخارجي إذا كان مصدر البيانات خارجيًا، وإلا فهو None |
| [`external_workbook_path`](/slides/python-net/ar/aspose.slides.charts/chartdata/external_workbook_path/) | يمثِّل مصدر بيانات المخطط |
| [`embedded_workbook_type`](/slides/python-net/ar/aspose.slides.charts/chartdata/embedded_workbook_type/) | يحصل على نوع المصنف المدمج.<br/>            يُرجِع [`WorkbookType.NOT_DEFINED`](/slides/python-net/ar/aspose.slides.charts/workbooktype/NOT_DEFINED) إذا كان [`ChartData.data_source_type`](/slides/python-net/ar/aspose.slides.charts/chartdata/data_source_type) هو <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/ar/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/>            للقراءة فقط [`WorkbookType`](/slides/python-net/ar/aspose.slides.charts/workbooktype). |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/ar/aspose.slides.charts/chartdata/set_external_workbook/#str) | يحدد المصنف الخارجي كمصدر بيانات للمخطط. سيتم تحديث بيانات المخطط من المصنف الهدف. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/ar/aspose.slides.charts/chartdata/set_external_workbook/#str-bool) | يحدد المصنف الخارجي كمصدر بيانات للمخطط. |
| [`read_workbook_stream(self)`](/slides/python-net/ar/aspose.slides.charts/chartdata/read_workbook_stream/#) | يكتب المصنف Excel الداخلي إلى تدفق. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/ar/aspose.slides.charts/chartdata/write_workbook_stream/#iorawiobase) | يهيئ المصنف Excel الداخلي بالقيمة المحددة من قبل المستخدم. |
| [`get_range(self)`](/slides/python-net/ar/aspose.slides.charts/chartdata/get_range/#) | يحصل على نطاق بيانات المخطط. |
| [`set_range(self, formula)`](/slides/python-net/ar/aspose.slides.charts/chartdata/set_range/#str) | يحدد نطاق بيانات المخطط. ستُحدَّث السلاسل والفئات بناءً على النطاق الجديد.<br/>            إذا كان عدد السلاسل في النطاق أكبر من عدد السلاسل في بيانات المخطط، فسيُضاف سلسلة إضافية من نفس نوع <br/>            السلسلة الأخيرة في المجموعة الحالية إلى نهاية المجموعة. |
| [`switch_row_column(self)`](/slides/python-net/ar/aspose.slides.charts/chartdata/switch_row_column/#) | يبدّل البيانات عبر المحور.<br/>            البيانات المرسومة على المحور X ستنتقل إلى المحور Y والعكس بالعكس. |

### انظر أيضًا
* الوحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* المكتبة [`Aspose.Slides`](/slides/python-net)