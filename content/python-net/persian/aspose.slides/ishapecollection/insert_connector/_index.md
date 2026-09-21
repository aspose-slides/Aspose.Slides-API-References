---
title: insert_connector method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/ishapecollection/insert_connector/
weight: 260
---
## insert_connector(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
یک شکل connector جدید ایجاد می‌کند و آن را در مجموعهٔ شکل‌ها در مقدار ایندکس مشخص‌شده وارد می‌سازد،
            همان‌طور که استایل پیش‌فرض قالب اعمال می‌شود.

### بازگشت

[`IConnector`](/slides/python-net/fa/aspose.slides/iconnector) تازه ایجاد شده.



```python
def insert_connector(self, index, shape_type, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | شاخص صفر مبنایی که شکل connector در آن وارد می‌شود. |
| shape_type | [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype) شکل connector برای وارد کردن. |
| x | **float** | مختصات x فریم connector، به نقطه. |
| y | **float** | مختصات y فریم connector، به نقطه. |
| width | **float** | عرض فریم connector، به نقطه. |
| height | **float** | ارتفاع فریم connector، به نقطه. |


## insert_connector(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
یک شکل connector جدید ایجاد می‌کند و آن را در مجموعهٔ شکل‌ها در مقدار ایندکس مشخص‌شده وارد می‌سازد،
            به‌صورت اختیاری استایل پیش‌فرض قالب را اعمال می‌کند.

### بازگشت

[`IConnector`](/slides/python-net/fa/aspose.slides/iconnector) تازه ایجاد شده.



```python
def insert_connector(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | شاخص صفر مبنایی که شکل connector در آن وارد می‌شود. |
| shape_type | [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype) شکل connector برای وارد کردن. |
| x | **float** | مختصات x فریم connector، به نقطه. |
| y | **float** | مختصات y فریم connector، به نقطه. |
| width | **float** | عرض فریم connector، به نقطه. |
| height | **float** | ارتفاع فریم connector، به نقطه. |
| create_from_template | **bool** | True برای اعمال استایل پیش‌فرض قالب (نام غیر خالی، سبک ساده);<br/><br/>false برای ایجاد connector با مقادیر پیش‌فرض خصوصیات. |



### موارد مرتبط
* class [`IConnector`](/slides/python-net/fa/aspose.slides/iconnector)
* class [`IShapeCollection`](/slides/python-net/fa/aspose.slides/ishapecollection)
* enumeration [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)