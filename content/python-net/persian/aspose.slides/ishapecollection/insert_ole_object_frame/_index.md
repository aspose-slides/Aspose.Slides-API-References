---
title: insert_ole_object_frame method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/ishapecollection/insert_ole_object_frame/
weight: 280
---
## insert_ole_object_frame(self, index, x, y, width, height, data_info) {#int-float-float-float-float-ioleembeddeddatainfo}
یک قاب شیء OLE جدید ایجاد می‌کند و آن را در shape collection در ایندکس مشخص شده قرار می‌دهد.

### بازگشت

مورد جدید ایجاد شده [`IOleObjectFrame`](/slides/python-net/fa/aspose.slides/ioleobjectframe).



```python
def insert_ole_object_frame(self, index, x, y, width, height, data_info):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | شاخص صفر-پایه‌ای که در آن OLE object frame قرار می‌گیرد. |
| x | **float** | مختصات x قاب جدید OLE، به نقطه. |
| y | **float** | مختصات y قاب جدید OLE، به نقطه. |
| width | **float** | عرض قاب جدید OLE، به نقطه. |
| height | **float** | ارتفاع قاب جدید OLE، به نقطه. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/fa/aspose.slides/ioleembeddeddatainfo) | اطلاعات داده‌های OLE جاسازی شده ([`IOleEmbeddedDataInfo`](/slides/python-net/fa/aspose.slides/ioleembeddeddatainfo)). |


## insert_ole_object_frame(self, index, x, y, width, height, class_name, path) {#int-float-float-float-float-str-str}
یک قاب شیء OLE جدید ایجاد می‌کند و آن را در shape collection در ایندکس مشخص شده قرار می‌دهد.

### بازگشت

مورد جدید ایجاد شده [`IOleObjectFrame`](/slides/python-net/fa/aspose.slides/ioleobjectframe).



```python
def insert_ole_object_frame(self, index, x, y, width, height, class_name, path):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | شاخص صفر-پایه‌ای که در آن OLE object frame قرار می‌گیرد. |
| x | **float** | مختصات x قاب جدید OLE، به نقطه. |
| y | **float** | مختصات y قاب جدید OLE، به نقطه. |
| width | **float** | عرض قاب جدید OLE، به نقطه. |
| height | **float** | ارتفاع قاب جدید OLE، به نقطه. |
| class_name | **str** | نام کلاس OLE object. |
| path | **str** | مسیر فایل لینک شده. <br/><br/>این مسیر به‌صورت دقیق در ارائه ذخیره می‌شود.<br/><br/>اگر مسیری نسبی مشخص شود، فایل هنگام باز کردن<br/><br/>ارائه از یک دایرکتوری متفاوت در دسترس نخواهد بود. |



### همچنین ببینید
* کلاس [`IOleEmbeddedDataInfo`](/slides/python-net/fa/aspose.slides/ioleembeddeddatainfo)
* کلاس [`IOleObjectFrame`](/slides/python-net/fa/aspose.slides/ioleobjectframe)
* کلاس [`IShapeCollection`](/slides/python-net/fa/aspose.slides/ishapecollection)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)