---
title: insert_ole_object_frame method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/shapecollection/insert_ole_object_frame/
weight: 280
---
## insert_ole_object_frame(self, index, x, y, width, height, data_info) {#int-float-float-float-float-ioleembeddeddatainfo}
یک قاب شیء OLE جدید ایجاد می‌کند و آن را در مجموعه اشکال در ایندکس مشخص شده درج می‌دارد.

### Returns

قاب جدید ایجاد شده [`IOleObjectFrame`](/slides/python-net/fa/aspose.slides/ioleobjectframe).



```python
def insert_ole_object_frame(self, index, x, y, width, height, data_info):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | اندیس صفر-پایه‌ای که قرار است فریم شیء OLE در آن وارد شود. |
| x | **float** | مختصات x فریم OLE جدید، به واحد نقاط. |
| y | **float** | مختصات y فریم OLE جدید، به واحد نقاط. |
| width | **float** | عرض فریم OLE جدید، به واحد نقاط. |
| height | **float** | ارتفاع فریم OLE جدید، به واحد نقاط. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/fa/aspose.slides/ioleembeddeddatainfo) | اطلاعات داده‌های توکار OLE ([`IOleEmbeddedDataInfo`](/slides/python-net/fa/aspose.slides/ioleembeddeddatainfo)). |


## insert_ole_object_frame(self, index, x, y, width, height, class_name, path) {#int-float-float-float-float-str-str}
یک قاب شیء OLE جدید ایجاد می‌کند و آن را در مجموعه اشکال در ایندکس مشخص شده درج می‌دارد.

### Returns

فریم شیء OLE جدید ایجاد شده.



```python
def insert_ole_object_frame(self, index, x, y, width, height, class_name, path):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | اندیس صفر-پایه‌ای که قرار است فریم شیء OLE در آن وارد شود. |
| x | **float** | مختصات x فریم OLE جدید، به واحد نقاط. |
| y | **float** | مختصات y فریم OLE جدید، به واحد نقاط. |
| width | **float** | عرض فریم OLE جدید، به واحد نقاط. |
| height | **float** | ارتفاع فریم OLE جدید، به واحد نقاط. |
| class_name | **str** | نام کلاس شیء OLE. |
| path | **str** | مسیر فایل لینک‌شده. <br/><br/>این مسیر به همان صورت در ارائه ذخیره می‌شود.<br/><br/>اگر مسیر نسبی مشخص شود، هنگام باز کردن ارائه از یک دایرکتوری متفاوت، فایل قابل دسترسی نخواهد بود. |



### مراجع
* کلاس [`IOleEmbeddedDataInfo`](/slides/python-net/fa/aspose.slides/ioleembeddeddatainfo)
* کلاس [`IOleObjectFrame`](/slides/python-net/fa/aspose.slides/ioleobjectframe)
* کلاس [`ShapeCollection`](/slides/python-net/fa/aspose.slides/shapecollection)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)