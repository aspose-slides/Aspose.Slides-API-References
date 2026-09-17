---
title: add method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.charts/ichartcategorycollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
إذا كان الفئة موجودة في المجموعة، يتم إرجاعها. وإلا يتم إنشاء فئة مخطط جديدة من [`IChartDataCell`](/slides/python-net/ar/aspose.slides.charts/ichartdatacell) وإضافتها إلى المجموعة.

### الإرجاع

الفئة المضافة أو الموجودة.

```python
def add(self, chart_data_cell):
    ...
```

| معامل | نوع | وصف |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/ar/aspose.slides.charts/ichartdatacell) | الخلية المستخدمة لإنشاء فئة المخطط. |

## add(self, value) {#any}
إنشاء [`IChartCategory`](/slides/python-net/ar/aspose.slides.charts/ichartcategory) جديد من القيمة وإضافته إلى المجموعة.

### الإرجاع

تمت إضافة [`IChartCategory`](/slides/python-net/ar/aspose.slides.charts/ichartcategory).

```python
def add(self, value):
    ...
```

| معامل | نوع | وصف |
| :- | :- | :- |
| value | **any** | القيمة. |

### ملاحظات

هذه الطريقة تُضيف ورقة عمل بالاسم AUTO_DATA وتضيف جميع القيم هناك. إذا استخدمت [`IChartDataWorkbook`](/slides/python-net/ar/aspose.slides.charts/ichartdataworkbook) لإضافة أو تعديل قيم الخلايا، تأكد من عدم استخدام هذه ورقة العمل.
الحد الأقصى لعدد القيم المضافة باستخدام هذه الطريقة يجب ألا يتجاوز 16711680

### الاستثناءات

| استثناء | وصف |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | في حال تجاوز الحد |

### انظر أيضًا
* الفئة [`IChartCategory`](/slides/python-net/ar/aspose.slides.charts/ichartcategory)
* الفئة [`IChartCategoryCollection`](/slides/python-net/ar/aspose.slides.charts/ichartcategorycollection)
* الفئة [`IChartDataCell`](/slides/python-net/ar/aspose.slides.charts/ichartdatacell)
* الفئة [`IChartDataWorkbook`](/slides/python-net/ar/aspose.slides.charts/ichartdataworkbook)
* الوحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* المكتبة [`Aspose.Slides`](/slides/python-net)