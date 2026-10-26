---
title: add method
second_title: Aspose.Slides للغة Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.charts/chartcellcollection/add/
weight: 10
---
## add(self, cell) {#ichartdatacell}
إضافة خلية جديدة إلى المجموعة.

```python
def add(self, cell):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| cell | [`IChartDataCell`](/slides/python-net/ar/aspose.slides.charts/ichartdatacell) | خلية جديدة للإضافة. |

## add(self, value) {#any}
ينشئ [`ChartDataCell`](/slides/python-net/ar/aspose.slides.charts/chartdatacell) من القيمة المحددة ويضيفه إلى المجموعة.

```python
def add(self, value):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| value | **any** | القيمة. |

### ملاحظات
تضيف هذه الطريقة ورقة عمل بالاسم AUTO_DATA وتضيف جميع القيم هناك.  
إذا استخدمت [`ChartDataWorkbook`](/slides/python-net/ar/aspose.slides.charts/chartdataworkbook) لإضافة أو تحرير قيم Cell، تأكد من عدم استخدام هذه ورقة العمل
يجب ألا يتجاوز الحد الأقصى لعدد القيم المضافة باستخدام هذه الطريقة 16711680

### الاستثناءات
| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | إذا تم تجاوز الحد |

### انظر أيضًا
* فئة [`ChartCellCollection`](/slides/python-net/ar/aspose.slides.charts/chartcellcollection)
* فئة [`ChartDataCell`](/slides/python-net/ar/aspose.slides.charts/chartdatacell)
* فئة [`ChartDataWorkbook`](/slides/python-net/ar/aspose.slides.charts/chartdataworkbook)
* فئة [`IChartDataCell`](/slides/python-net/ar/aspose.slides.charts/ichartdatacell)
* وحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* مكتبة [`Aspose.Slides`](/slides/python-net)