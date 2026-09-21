---
title: get_or_create_data_point_by_idx method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.charts/chartdatapointcollection/get_or_create_data_point_by_idx/
weight: 190
---
## get_or_create_data_point_by_idx(self, index) {#int}
اگر مجموعه قبلاً نقطه داده‌ای با ایندکس `index` داشته باشد، همان نقطه داده را برمی‌گرداند.
اگر مجموعه نقطه داده‌ای با ایندکس `index`==N نداشته باشد
(زمانی که تعداد نقاط داده در این مجموعه کمتر یا مساوی N باشد)
آنگاه نقاط دادهٔ کمبود را اضافه می‌کند و آخرین نقطه (که ایندکس درخواست شده را دارد) را برمی‌گرداند.
به‌عنوان مثال، ایندکس‌های مجموعه {0, 1, 2} هستند و ایندکس درخواست‌شده 5 است.
در این حالت متد نقاط دادهٔ کمبود را اضافه می‌کند: {0, 1, 2, 3, 4, 5}. و نقطه دادهٔ با ایندکس 5 را برمی‌گرداند.

### بازگشت

نقطه داده با ایندکس درخواست شده را برمی‌گرداند.



```python
def get_or_create_data_point_by_idx(self, index):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | ایندکس. |



### موارد مرتبط
* کلاس [`ChartDataPointCollection`](/slides/python-net/fa/aspose.slides.charts/chartdatapointcollection)
* کلاس [`IChartDataPoint`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint)
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)