---
title: IChartCategory class
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.charts/ichartcategory/
---
## IChartCategory فئة

يمثل فئات المخطط.

نوع IChartCategory يعرض الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`use_cell`](/slides/python-net/ar/aspose.slides.charts/ichartcategory/use_cell/) | إذا كان true فإن خاصية AsCell هي الفعلية. بمعنى آخر، يتم استخدام ورقة العمل لـ <br/>            تخزين الفئة (هذا الحالة تدعم فئة متعددة المستويات).<br/>            إذا كان false فإن خاصية AsLiteral هي الفعلية. بمعنى آخر، لا يتم استخدام ورقة العمل <br/>            لتخزين الفئة (وهذا الحالة لا تدعم فئات متعددة المستويات).<br/>            قراءة فقط **bool**. |
| [`as_cell`](/slides/python-net/ar/aspose.slides.charts/ichartcategory/as_cell/) | إرجاع أو تعيين كائن IChartDataCell.<br/>            إذا كانت الفئة متعددة المستويات فسيتم استخدام كائن IChartDataCell للمستوى "0".<br/>            قراءة/كتابة [`IChartDataCell`](/slides/python-net/ar/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/ar/aspose.slides.charts/ichartcategory/as_literal/) | إرجاع أو تعيين AsLiteral إذا كان UseCell false.<br/>            قراءة/كتابة **any**. |
| [`value`](/slides/python-net/ar/aspose.slides.charts/ichartcategory/value/) | إذا كان UseCell true فإن هذه الخاصية تمثل خاصية AsCell.Value.<br/>            إذا كان UseCell false فإن هذه الخاصية تمثل خاصية AsLiteral.<br/>            قراءة/كتابة **any**. |
| [`grouping_levels`](/slides/python-net/ar/aspose.slides.charts/ichartcategory/grouping_levels/) | حاوية مُدارة لقيم مستويات تجميع فئة المخطط.<br/>            الفئة متعددة المستويات تحتوي على أكثر من مستوى تجميع واحد.<br/>            فهرسة مستويات التجميع تبدأ من الصفر.<br/>            قراءة فقط [`IChartCategoryLevelsManager`](/slides/python-net/ar/aspose.slides.charts/ichartcategorylevelsmanager). |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`remove(self)`](/slides/python-net/ar/aspose.slides.charts/ichartcategory/remove/#) | يزيل الفئة من المخطط. |

### انظر أيضًا
* الوحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* المكتبة [`Aspose.Slides`](/slides/python-net)