---
title: series_groups property
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.charts/chartdata/series_groups/
weight: 150
---
## series_groups خاصية
يحصل على مجموعات السلاسل.
قراءة فقط [`IChartSeriesGroupCollection`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroupcollection).

### ملاحظات

1) كل مجموعة من السلاسل تحتوي على سلاسل بأنواع يمكن دمجها. يتم تعريف مجموعات أنواع السلاسل القابلة للدمج ووصفها باستخدام تعداد CombinableSeriesTypesGroup.
            أيضًا كل مجموعة من السلاسل تحتوي على سلاسل يتم رسمها إما على المحاور الرئيسية أو على المحاور الثانوية (ليس كليهما في مجموعة واحدة).
            لذلك، مبدأ تجميع السلاسل هو التجميع بحسب مجموعات الأنواع المذكورة أعلاه وبحسب نوع الرسم الرئيسي/الثانوي.

2) مجموعة السلاسل تحتوي على بعض خصائص السلسلة التي تكون مشتركة لكل سلسلة في المجموعة ("Series group properties").
            "Series group properties" في الفئة ChartSeriesGroup هي قراءة/كتابة.
            كل واحدة من "Series group properties" يمكن أن يكون لها تمثيل قراءة فقط في الفئة ChartSeries.

### التعريف:
```python
@property
def series_groups(self):
    ...
```

### انظر أيضًا
* فئة [`ChartData`](/slides/python-net/ar/aspose.slides.charts/chartdata)
* فئة [`IChartSeriesGroupCollection`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroupcollection)
* وحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* مكتبة [`Aspose.Slides`](/slides/python-net)