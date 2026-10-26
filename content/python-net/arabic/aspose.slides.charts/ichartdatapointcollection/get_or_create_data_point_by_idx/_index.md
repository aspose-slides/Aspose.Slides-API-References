---
title: get_or_create_data_point_by_idx method
second_title: Aspose.Slides للغة Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.charts/ichartdatapointcollection/get_or_create_data_point_by_idx/
weight: 190
---
## get_or_create_data_point_by_idx(self, index) {#int}
إذا كان التجميع يحتوي بالفعل على نقطة بيانات ذات الفهرس `index` فستُعيد هذه النقطة.
            إذا كان التجميع لا يحتوي على نقطة بيانات ذات الفهرس `index`==N (عندما يكون عدد نقاط البيانات في هذا التج aggregation أقل أو يساوي N) فسيضيف نقاط بيانات مفقودة ويعيد الأخيرة (التي لها الفهرس المطلوب).
            على سبيل المثال، فهارس التجميع هي {0, 1, 2}، والفهرس المطلوب هو 5.
            ثم تضيف الطريقة نقاط البيانات المفقودة: {0, 1, 2, 3, 4, 5}. وتُعيد نقطة البيانات ذات الفهرس 5.

### القيمة المرجعة

تُعيد نقطة البيانات ذات الفهرس المطلوب.



```python
def get_or_create_data_point_by_idx(self, index):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| index | **int** | الفهرس. |



### انظر أيضًا
* الفئة [`IChartDataPoint`](/slides/python-net/ar/aspose.slides.charts/ichartdatapoint)
* الفئة [`IChartDataPointCollection`](/slides/python-net/ar/aspose.slides.charts/ichartdatapointcollection)
* الوحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* المكتبة [`Aspose.Slides`](/slides/python-net)