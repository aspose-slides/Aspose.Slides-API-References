---
title: add_connector method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/shapecollection/add_connector/
weight: 70
---
## add_connector(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
یک شکل اتصال جدید با استایل پیش‌فرض قالب ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید.

### مقدار بازگشتی
[`IConnector`](/slides/python-net/fa/aspose.slides/iconnector) جدید ایجاد شده.


```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype) شکل اتصال برای افزودن. |
| x | **float** | مختصات x قاب اتصال، برحسب نقطه. |
| y | **float** | مختصات y قاب اتصال، برحسب نقطه. |
| width | **float** | عرض قاب اتصال، برحسب نقطه. |
| height | **float** | ارتفاع قاب اتصال، برحسب نقطه. |


## add_connector(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
یک شکل اتصال جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید؛ در صورت تمایل استایل پیش‌فرض قالب را اعمال می‌کند.

### مقدار بازگشتی
[`IConnector`](/slides/python-net/fa/aspose.slides/iconnector) جدید ایجاد شده.


```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype) شکل اتصال برای ایجاد. |
| x | **float** | مختصات x قاب اتصال، برحسب نقطه. |
| y | **float** | مختصات y قاب اتصال، برحسب نقطه. |
| width | **float** | عرض قاب اتصال، برحسب نقطه. |
| height | **float** | ارتفاع قاب اتصال، برحسب نقطه. |
| create_from_template | **bool** | True برای اعمال استایل پیش‌فرض قالب (نام غیر خالی، استایل ساده)؛ <br/><br/>false برای ایجاد اتصال با مقادیر پیش‌فرض ویژگی‌ها. |



### موارد مرتبط
* کلاس [`IConnector`](/slides/python-net/fa/aspose.slides/iconnector)
* کلاس [`ShapeCollection`](/slides/python-net/fa/aspose.slides/shapecollection)
* شمارش [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)