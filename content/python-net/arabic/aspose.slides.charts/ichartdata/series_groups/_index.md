---
title: series_groups property
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.charts/ichartdata/series_groups/
weight: 150
---
## series_groups الخاصية
يعيد مجموعات السلاسل.
            قراءة فقط [`IChartSeriesGroupCollection`](/slides/python-net/ar/aspose.slides.charts/ichartseriesgroupcollection).

### ملاحظات

1) كل مجموعة من السلاسل تحتوي على سلاسل بأنواع يمكن دمجها. المجموعات من 
            أنواع السلاسل القابلة للدمج معرفة ومُوصَّفة بالعدد 
            CombinableSeriesTypesGroup enum.
            أيضًا كل مجموعة من السلاسل تشمل سلاسل تُرسم إما 
            على المحاور الأولية أو على المحاور الثانوية (ليس كلا الحالتين في مجموعة واحدة).
            لذلك مبدأ تجميع السلاسل هو التجميع حسب مجموعات الأنواع المذكورة أعلاه
            وبحسب نوع الرسم الأساسي/الثاني.
            
2) مجموعة السلاسل تحتوي بعض خصائص السلاسل التي تكون مشتركة لكل سلسلة في المجموعة ("خصائص مجموعة السلاسل").
"خصائص مجموعة السلاسل" في ChartSeriesGroup فئة هي قراءة/كتابة.
كل من "خصائص مجموعة السلاسل" يمكن أن يكون له إسقاط للقراءة فقط في ChartSeries فئة.

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