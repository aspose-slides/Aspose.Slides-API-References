---
title: get_or_create_data_point_by_idx method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.charts/chartdatapointcollection/get_or_create_data_point_by_idx/
weight: 190
---
## get_or_create_data_point_by_idx(self, index) {#int}
إذا كانت المجموعة تحتوي بالفعل على نقطة بيانات بالرقم `index` فتُرجع هذه النقطة.
إذا كانت المجموعة لا تحتوي على نقطة بيانات بالرقم `index`==N (عند كون عدد نقاط البيانات في هذه المجموعة أقل أو يساوي N) فتضيف نقاط بيانات ناقصة وتُرجع الأخيرة (التي لها الرقم المطلوب).
على سبيل المثال، مؤشرات المجموعة هي {0, 1, 2}، والرقم المطلوب هو 5.
ثم تقوم الطريقة بإضافة نقاط بيانات ناقصة: {0, 1, 2, 3, 4, 5}. وتُرجع نقطة البيانات بالرقم 5.

### القيمة المرجعة

تُرجع نقطة البيانات بالرقم المطلوب.



```python
def get_or_create_data_point_by_idx(self, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | الفهرس. |



### انظر أيضًا
* فئة [`ChartDataPointCollection`](/slides/python-net/ar/aspose.slides.charts/chartdatapointcollection)
* فئة [`IChartDataPoint`](/slides/python-net/ar/aspose.slides.charts/ichartdatapoint)
* وحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* مكتبة [`Aspose.Slides`](/slides/python-net)