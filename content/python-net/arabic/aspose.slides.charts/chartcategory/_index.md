---
title: ChartCategory class
second_title: Aspose.Slides للبايثون عبر .NET – مرجع API
description: 
type: docs
url: /ar/aspose.slides.charts/chartcategory/
---
## فئة ChartCategory

يمثل فئات المخطط.

يعرض نوع ChartCategory الأعضاء التالية:

## الخصائص

| Property | Description |
| :- | :- |
| [`use_cell`](/slides/python-net/ar/aspose.slides.charts/chartcategory/use_cell/) | إذا كان true فإن خاصية AsCell هي الفعلية. بمعنى آخر، تُستخدم ورقة العمل لـ <br/>            تخزين الفئة (هذه الحالة تدعم فئة متعددة المستويات).<br/>            إذا كان false فإن خاصية AsLiteral هي الفعلية. بمعنى آخر، لا تُستخدم ورقة العمل <br/>            لتخزين الفئة (وهذه الحالة لا تدعم فئات متعددة المستويات).<br/>            قراءة فقط **bool**. |
| [`as_cell`](/slides/python-net/ar/aspose.slides.charts/chartcategory/as_cell/) | يعيد أو يضبط كائن IChartDataCell.<br/>            إذا كانت الفئة متعددة المستويات فسيتم استخدام كائن IChartDataCell للمستوى "0".<br/>            قراءة/كتابة [`IChartDataCell`](/slides/python-net/ar/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/ar/aspose.slides.charts/chartcategory/as_literal/) | يعيد أو يضبط كائن AsLiteral.<br/>            قراءة/كتابة **any**. |
| [`value`](/slides/python-net/ar/aspose.slides.charts/chartcategory/value/) | إذا كان UseCell true فإن هذه الخاصية تمثل خاصية AsCell.Value.<br/>            إذا كان UseCell false فإن هذه الخاصية تمثل خاصية AsLiteral.<br/>            قراءة/كتابة **any**. |
| [`grouping_levels`](/slides/python-net/ar/aspose.slides.charts/chartcategory/grouping_levels/) | حاوية مُدارة لقيم مستويات تجميع فئة المخطط.<br/>            الفئة متعددة المستويات تحتوي على أكثر من مستوى تجميع واحد.<br/>            فهرسة مستويات التجميع تبدأ من الصفر.<br/>            قراءة فقط [`IChartCategoryLevelsManager`](/slides/python-net/ar/aspose.slides.charts/ichartcategorylevelsmanager). |
| [`cached_value`](/slides/python-net/ar/aspose.slides.charts/chartcategory/cached_value/) | يحصل على القيمة المخزنة مؤقتًا لفئة المخطط.<br/>            قراءة فقط [`ICachedChartValue`](/slides/python-net/ar/aspose.slides.charts/icachedchartvalue). |

## الطرق

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/ar/aspose.slides.charts/chartcategory/remove/#) | يزيل الفئة من المخطط. |

### انظر أيضًا
* الوحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* المكتبة [`Aspose.Slides`](/slides/python-net)