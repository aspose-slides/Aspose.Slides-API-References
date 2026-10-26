---
title: insert_auto_shape method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/shapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
یک شکل خودکار جدید ایجاد می‌کند و آن را در مجموعهٔ اشکال در ایندکس مشخص وارد می‌کند، قالب‌بندی پیش‌فرض الگو را اعمال می‌کند.

### بازگشت

The newly created [`IAutoShape`](/slides/python-net/fa/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | اندیس صفر-مبنایی که در آن شکل خودکار جدید وارد می‌شود. |
| shape_type | [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype) شکل خودکار برای درج. |
| x | **float** | مختصات x چارچوب شکل، بر حسب پوینت. |
| y | **float** | مختصات y چارچوب شکل، بر حسب پوینت. |
| width | **float** | عرض چارچوب شکل، بر حسب پوینت. |
| height | **float** | ارتفاع چارچوب شکل، بر حسب پوینت. |


## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
یک شکل خودکار جدید ایجاد می‌کند و آن را در مجموعهٔ اشکال در ایندکس مشخص وارد می‌کند، به‌صورت اختیاری با استایل پیش‌فرض الگو مقداردهی اولیه می‌کند.

### بازگشت

The newly created [`IAutoShape`](/slides/python-net/fa/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | اندیس صفر-مبنایی که در آن شکل خودکار وارد می‌شود. |
| shape_type | [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype) شکل خودکار برای درج. |
| x | **float** | مختصات x چارچوب شکل، بر حسب پوینت. |
| y | **float** | مختصات y چارچوب شکل، بر حسب پوینت. |
| width | **float** | عرض چارچوب شکل، بر حسب پوینت. |
| height | **float** | ارتفاع چارچوب شکل، بر حسب پوینت. |
| create_from_template | **bool** | True برای اعمال استایل پیش‌فرض الگو (شامل نام غیر خالی، استایل ساده و متن وسط‌چین); <br/><br/> false برای ایجاد شکل با تمام ویژگی‌ها به مقدار پیش‌فرضشان. |



### موارد مرتبط
* کلاس [`IAutoShape`](/slides/python-net/fa/aspose.slides/iautoshape)
* کلاس [`ShapeCollection`](/slides/python-net/fa/aspose.slides/shapecollection)
* شمارش [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)