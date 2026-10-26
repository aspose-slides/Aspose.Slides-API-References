---
title: series_groups property
second_title: Aspose.Slides للغة Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.charts/chartdata/series_groups/
weight: 140
---
## series_groups خاصية
يحصل على مجموعات السلاسل.
            للقراءة فقط [`IChartSeriesGroupCollection`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroupcollection).


### ملاحظات

1) كل مجموعة من السلاسل تحتوي على سلاسل ذات أنواع يمكن دمجها. مجموعات 
            أنواع السلاسل القابلة للدمج معرفة ومُوصَفة باستخدام تعداد CombinableSeriesTypesGroup 
            enum.
            كما أن كل مجموعة من السلاسل تحتوي على سلاسل تُرسم سواء 
            على المحاور الأولية أو على المحاور الثانوية (ليس كلا الحالتين في مجموعة واحدة).
            لذا، مبدأ تجميع السلاسل هو التجميع حسب مجموعات الأنواع المذكورة 
            أعلاه وحسب نوع الرسم الأساسي/الثانوي.
            
2) مجموعة السلاسل تحتوي على بعض خصائص السلاسل التي هي مشتركة لكل 
            سلسلة في المجموعة ("خصائص مجموعة السلسلة").
            "خصائص مجموعة السلسلة" في الفئة ChartSeriesGroup هي قراءة/كتابة.
            كل من "خصائص مجموعة السلسلة" يمكن أن يكون لها إسقاط للقراءة فقط في الفئة ChartSeries.

### التعريف:
```python
@property
def series_groups(self):
    ...
```


### انظر أيضًا
* الفئة [`ChartData`](/slides/python-net/ar/aspose.slides.charts/chartdata)
* الفئة [`IChartSeriesGroupCollection`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroupcollection)
* الوحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* المكتبة [`Aspose.Slides`](/slides/python-net)