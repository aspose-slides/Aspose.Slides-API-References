---
title: ChartCategory class
second_title: Aspose.Slides للبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.charts/chartcategory/
---
## فئة ChartCategory

تمثّل فئات المخطط.

نوع ChartCategory يكشف عن الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`use_cell`](/slides/python-net/ar/aspose.slides.charts/chartcategory/use_cell/) | إذا كان true فإن خاصية AsCell سارية. بعبارة أخرى، يتم استخدام ورقة العمل لتخزين الفئة (هذا الحالة تدعم فئة متعددة المستويات).<br/> إذا كان false فإن خاصية AsLiteral سارية. بعبارة أخرى، لا يتم استخدام ورقة العمل لتخزين الفئة (وهذه الحالة لا تدعم الفئات متعددة المستويات).<br/> للقراءة فقط **bool**. |
| [`as_cell`](/slides/python-net/ar/aspose.slides.charts/chartcategory/as_cell/) | يعيد أو يعيّن كائن IChartDataCell.<br/> إذا كانت الفئة متعددة المستويات فسيتم استخدام كائن IChartDataCell للمستوى "0".<br/> قراءة/كتابة [`IChartDataCell`](/slides/python-net/ar/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/ar/aspose.slides.charts/chartcategory/as_literal/) | يعيد أو يعيّن كائن AsLiteral.<br/> قراءة/كتابة **any**. |
| [`value`](/slides/python-net/ar/aspose.slides.charts/chartcategory/value/) | إذا كان UseCell true فتمثل هذه الخاصية خاصية AsCell.Value.<br/> إذا كان UseCell false فتمثل هذه الخاصية خاصية AsLiteral.<br/> قراءة/كتابة **any**. |
| [`grouping_levels`](/slides/python-net/ar/aspose.slides.charts/chartcategory/grouping_levels/) | حاوية مُدارة لقيم مستويات تجميع فئات المخطط.<br/> الفئة متعددة المستويات تحتوي على أكثر من مستوى تجميع واحد.<br/> فهرسة مستويات التجميع تبدأ من الصفر.<br/> للقراءة فقط [`IChartCategoryLevelsManager`](/slides/python-net/ar/aspose.slides.charts/ichartcategorylevelsmanager). |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`remove(self)`](/slides/python-net/ar/aspose.slides.charts/chartcategory/remove/#) | يزيل الفئة من المخطط. |

### أنظر أيضًا
* الوحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* المكتبة [`Aspose.Slides`](/slides/python-net)