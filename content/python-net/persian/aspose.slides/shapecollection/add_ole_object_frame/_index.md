---
title: add_ole_object_frame method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/shapecollection/add_ole_object_frame/
weight: 100
---
## add_ole_object_frame(self, x, y, width, height, data_info) {#float-float-float-float-ioleembeddeddatainfo}
یک قاب شیء OLE جدید ایجاد می‌کند و آن را به انتهای مجموعه اشکال اضافه می‌نماید.

### بازگشت

[`IOleObjectFrame`](/slides/python-net/fa/aspose.slides/ioleobjectframe) جدید ایجاد شده.



```python
def add_ole_object_frame(self, x, y, width, height, data_info):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| x | **float** | مختصات x قاب OLE جدید، به واحد نقطه. |
| y | **float** | مختصات y قاب OLE جدید، به واحد نقطه. |
| width | **float** | عرض قاب OLE جدید، به واحد نقطه. |
| height | **float** | ارتفاع قاب OLE جدید، به واحد نقطه. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/fa/aspose.slides/ioleembeddeddatainfo) | اطلاعات درباره داده‌های OLE جاسازی شده ([`IOleEmbeddedDataInfo`](/slides/python-net/fa/aspose.slides/ioleembeddeddatainfo)). |


## add_ole_object_frame(self, x, y, width, height, class_name, path) {#float-float-float-float-str-str}
یک قاب شیء OLE جدید ایجاد می‌کند و آن را به انتهای مجموعه اشکال اضافه می‌نماید.

### بازگشت

[`IOleObjectFrame`](/slides/python-net/fa/aspose.slides/ioleobjectframe) جدید ایجاد شده.



```python
def add_ole_object_frame(self, x, y, width, height, class_name, path):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| x | **float** | مختصات x قاب OLE جدید، به واحد نقطه. |
| y | **float** | مختصات y قاب OLE جدید، به واحد نقطه. |
| width | **float** | عرض قاب OLE جدید، به واحد نقطه. |
| height | **float** | ارتفاع قاب OLE جدید، به واحد نقطه. |
| class_name | **str** | نام کلاس شیء OLE. |
| path | **str** | مسیر فایل مرتبط. <br/><br/>این مسیر به همان شکل در ارائه ذخیره می‌شود.<br/><br/>            اگر مسیر نسبی مشخص شود، فایل هنگام باز کردن<br/><br/>            ارائه از یک پوشهٔ متفاوت قابل دسترسی نخواهد بود. |



### مراجع
* کلاس [`IOleEmbeddedDataInfo`](/slides/python-net/fa/aspose.slides/ioleembeddeddatainfo)
* کلاس [`IOleObjectFrame`](/slides/python-net/fa/aspose.slides/ioleobjectframe)
* کلاس [`ShapeCollection`](/slides/python-net/fa/aspose.slides/shapecollection)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)