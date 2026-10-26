---
title: series_groups property
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides.charts/ichartdata/series_groups/
weight: 140
---
## series_groups خاصية
Gets the groups of series.
            Read-only [`IChartSeriesGroupCollection`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroupcollection).

### ملاحظات

1) كل مجموعة من السلاسل تحتوي على سلاسل ذات أنواع قابلة للدمج.
مجموعات أنواع السلاسل القابلة للدمج معرفة وموصوفة باستخدام CombinableSeriesTypesGroup enum.
أيضًا كل مجموعة من السلاسل تحتوي على سلاسل يتم رسمها إما على المحاور الأساسية أو على المحاور الثانوية (ليس كلا الحالتين في مجموعة واحدة).
إذن، مبدأ تجميع السلاسل هو التجميع حسب مجموعات الأنواع المذكورة أعلاه وحسب نوع الرسم الأساسي/الثانوي.

2) مجموعة السلاسل تحتوي على بعض خصائص السلاسل التي تكون مشتركة لكل سلسلة في المجموعة ("series group properties").
"Series group properties" في فئة ChartSeriesGroup هي read/write.
كل من "series group properties" يمكن أن يكون له إسقاط read-only في فئة ChartSeries.

### التعريف:
```python
@property
def series_groups(self):
    ...
```

### انظر أيضًا
* فئة [`IChartData`](/slides/python-net/ar/aspose.slides.charts/ichartdata)
* فئة [`IChartSeriesGroupCollection`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroupcollection)
* وحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* مكتبة [`Aspose.Slides`](/slides/python-net)