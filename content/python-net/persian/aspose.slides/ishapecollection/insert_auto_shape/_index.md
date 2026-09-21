---
title: insert_auto_shape method
second_title: Aspose.Slides برای پایتون از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/ishapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
یک شکل خودکار جدید ایجاد می‌کند و آن را در مجموعهٔ شکل‌ها در اندیس مشخص شده درج می‌نماید،
            با اعمال قالب پیش‌فرض.

### بازگشت

[`IAutoShape`](/slides/python-net/fa/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```



| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | اندیس صفر-مبنا که در آن شکل خودکار جدید درج می‌شود. |
| shape_type | [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype) شکل خودکار برای درج. |
| x | **float** | مختصات x چارچوب شکل، بر حسب پوینت. |
| y | **float** | مختصات y چارچوب شکل، بر حسب پوینت. |
| width | **float** | عرض چارچوب شکل، بر حسب پوینت. |
| height | **float** | ارتفاع چارچوب شکل، بر حسب پوینت. |


## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
یک شکل خودکار جدید ایجاد می‌کند و آن را در مجموعهٔ شکل‌ها در اندیس مشخص شده درج می‌نماید،
            به‌صورت اختیاری با استایل قالب پیش‌فرض مقداردهی اولیه می‌کند.

### بازگشت

[`IAutoShape`](/slides/python-net/fa/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | اندیس صفر-مبنا که در آن شکل خودکار درج می‌شود. |
| shape_type | [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype) شکل خودکار برای درج. |
| x | **float** | مختصات x چارچوب شکل، بر حسب پوینت. |
| y | **float** | مختصات y چارچوب شکل، بر حسب پوینت. |
| width | **float** | عرض چارچوب شکل، بر حسب پوینت. |
| height | **float** | ارتفاع چارچوب شکل، بر حسب پوینت. |
| create_from_template | **bool** | True برای اعمال استایل قالب پیش‌فرض (شامل نام غیرخالی، سبک ساده و متن مرکز‌وار); <br/><br/>            false برای ایجاد شکل با همهٔ ویژگی‌ها به مقادیر پیش‌فرضشان. |



### موارد مرتبط
* class [`IAutoShape`](/slides/python-net/fa/aspose.slides/iautoshape)
* class [`IShapeCollection`](/slides/python-net/fa/aspose.slides/ishapecollection)
* enumeration [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)