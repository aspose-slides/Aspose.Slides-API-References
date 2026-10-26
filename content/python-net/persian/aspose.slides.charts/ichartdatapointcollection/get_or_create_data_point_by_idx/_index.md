---
title: get_or_create_data_point_by_idx method
second_title: Aspose.Slides برای پایتون از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.charts/ichartdatapointcollection/get_or_create_data_point_by_idx/
weight: 190
---
## get_or_create_data_point_by_idx(self, index) {#int}
اگر مجموعه قبلاً شامل نقطه داده‌ای با ایندکس `index` باشد، این نقطه داده را بازمی‌گرداند.
اگر مجموعه شامل نقطه داده‌ای با ایندکس `index`==N نباشد
(وقتی تعداد نقطه‌های داده در این مجموعه کمتر یا برابر N باشد)
آنگاه نقاط داده کمبود را اضافه می‌کند و آخرین را بازمی‌گرداند (که ایندکس درخواستی را دارد).
به عنوان مثال، ایندکس‌های مجموعه {0, 1, 2} هستند و ایندکس درخواستی 5 است.
در این صورت متد نقاط داده کمبود را اضافه می‌کند: {0, 1, 2, 3, 4, 5}. و نقطه داده با ایندکس 5 را بازمی‌گرداند.

### بازگشت

نقطه داده با ایندکس درخواست‌شده را بازمی‌گرداند.



```python
def get_or_create_data_point_by_idx(self, index):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | شاخص. |



### موارد مرتبط
* کلاس [`IChartDataPoint`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint)
* کلاس [`IChartDataPointCollection`](/slides/python-net/fa/aspose.slides.charts/ichartdatapointcollection)
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)