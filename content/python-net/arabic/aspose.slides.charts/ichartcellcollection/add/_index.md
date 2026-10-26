---
title: add method
second_title: مرجع API Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides.charts/ichartcellcollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
إضافة خلية جديدة إلى المجموعة.

```python
def add(self, chart_data_cell):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/ar/aspose.slides.charts/ichartdatacell) | خلية جديدة للإضافة. |

## add(self, value) {#any}
ينشئ [`IChartDataCell`](/slides/python-net/ar/aspose.slides.charts/ichartdatacell) من القيمة المحددة ويضيفه إلى المجموعة.

```python
def add(self, value):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| value | **any** | القيمة. |

### ملاحظات
تضيف هذه الطريقة ورقة عمل بالاسم AUTO_DATA وتضيف جميع القيم هناك. إذا استخدمت [`IChartDataWorkbook`](/slides/python-net/ar/aspose.slides.charts/ichartdataworkbook) لإضافة أو تعديل قيم Cell، تأكد من عدم استخدام هذه ورقة العمل. يجب ألا يتجاوز العدد الأقصى للقيم المضافة باستخدام هذه الطريقة 16711680

### الاستثناءات
| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | إذا تم تجاوز الحد |

### انظر أيضًا
* فئة [`IChartCellCollection`](/slides/python-net/ar/aspose.slides.charts/ichartcellcollection)
* فئة [`IChartDataCell`](/slides/python-net/ar/aspose.slides.charts/ichartdatacell)
* فئة [`IChartDataWorkbook`](/slides/python-net/ar/aspose.slides.charts/ichartdataworkbook)
* وحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* مكتبة [`Aspose.Slides`](/slides/python-net)