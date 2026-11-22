---
title: IChartCategory class
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.charts/ichartcategory/
---
## IChartCategory فئة

يمثل فئات المخطط.

يعرض نوع IChartCategory الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`use_cell`](/slides/python-net/ar/aspose.slides.charts/ichartcategory/use_cell/) | إذا كان true فإن خاصية AsCell هي الفعلية. بعبارة أخرى، يتم استخدام ورقة العمل لـ <br/>            تخزين الفئة (يدعم هذا السيناريو فئة متعددة المستويات).<br/>            إذا كان false فإن خاصية AsLiteral هي الفعلية. بعبارة أخرى، لا يتم استخدام ورقة العمل <br/>            لتخزين الفئة (وهذا السيناريو لا يدعم الفئات متعددة المستويات).<br/>            للقراءة فقط **bool**. |
| [`as_cell`](/slides/python-net/ar/aspose.slides.charts/ichartcategory/as_cell/) | إرجاع أو تعيين كائن IChartDataCell.<br/>            إذا كانت الفئة متعددة المستويات فسيتم استخدام كائن IChartDataCell للمستوى "0".<br/>            قراءة/كتابة [`IChartDataCell`](/slides/python-net/ar/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/ar/aspose.slides.charts/ichartcategory/as_literal/) | إرجاع أو تعيين AsLiteral إذا كان UseCell false.<br/>            قراءة/كتابة **any**. |
| [`value`](/slides/python-net/ar/aspose.slides.charts/ichartcategory/value/) | إذا كان UseCell true فإن هذه الخاصية تمثل خاصية AsCell.Value.<br/>            إذا كان UseCell false فإن هذه الخاصية تمثل خاصية AsLiteral.<br/>            قراءة/كتابة **any**. |
| [`cached_value`](/slides/python-net/ar/aspose.slides.charts/ichartcategory/cached_value/) | يحصل على القيمة المخزنة مؤقتًا لفئة المخطط.<br/>            للقراءة فقط [`ICachedChartValue`](/slides/python-net/ar/aspose.slides.charts/icachedchartvalue). |
| [`grouping_levels`](/slides/python-net/ar/aspose.slides.charts/ichartcategory/grouping_levels/) | حاوية مُدارة لقيم مستويات تجميع فئة المخطط.<br/>            الفئة متعددة المستويات تحتوي على أكثر من مستوى تجميع.<br/>            فهرسة مستويات التجميع تبدأ من الصفر.<br/>            للقراءة فقط [`IChartCategoryLevelsManager`](/slides/python-net/ar/aspose.slides.charts/ichartcategorylevelsmanager). |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`remove(self)`](/slides/python-net/ar/aspose.slides.charts/ichartcategory/remove/#) | يزيل الفئة من المخطط. |

### انظر أيضًا
* الوحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* المكتبة [`Aspose.Slides`](/slides/python-net)