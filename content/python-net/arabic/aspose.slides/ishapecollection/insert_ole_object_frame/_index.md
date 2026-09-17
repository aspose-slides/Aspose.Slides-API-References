---
title: insert_ole_object_frame method
second_title: Aspose.Slides للـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/ishapecollection/insert_ole_object_frame/
weight: 280
---
## insert_ole_object_frame(self, index, x, y, width, height, data_info) {#int-float-float-float-float-ioleembeddeddatainfo}
ينشئ إطار OLE جديدًا ويضيفه إلى مجموعة الأشكال في الفهرس المحدد.

### القيمة المرجعة

الكائن المُنشأ حديثًا [`IOleObjectFrame`](/slides/python-net/ar/aspose.slides/ioleobjectframe).



```python
def insert_ole_object_frame(self, index, x, y, width, height, data_info):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| index | **int** | الفهرس الصفري الذي يُدرج فيه إطار OLE. |
| x | **float** | إحداثي x لإطار OLE الجديد، بوحدات النقاط. |
| y | **float** | إحداثي y لإطار OLE الجديد، بوحدات النقاط. |
| width | **float** | عرض إطار OLE الجديد، بوحدات النقاط. |
| height | **float** | ارتفاع إطار OLE الجديد، بوحدات النقاط. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/ar/aspose.slides/ioleembeddeddatainfo) | معلومات بيانات OLE المضمنة ([`IOleEmbeddedDataInfo`](/slides/python-net/ar/aspose.slides/ioleembeddeddatainfo)). |


## insert_ole_object_frame(self, index, x, y, width, height, class_name, path) {#int-float-float-float-float-str-str}
ينشئ إطار OLE جديدًا ويضيفه إلى مجموعة الأشكال في الفهرس المحدد.

### القيمة المرجعة

الكائن المُنشأ حديثًا [`IOleObjectFrame`](/slides/python-net/ar/aspose.slides/ioleobjectframe).



```python
def insert_ole_object_frame(self, index, x, y, width, height, class_name, path):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| index | **int** | الفهرس الصفري الذي يُدرج فيه إطار OLE. |
| x | **float** | إحداثي x لإطار OLE الجديد، بوحدات النقاط. |
| y | **float** | إحداثي y لإطار OLE الجديد، بوحدات النقاط. |
| width | **float** | عرض إطار OLE الجديد، بوحدات النقاط. |
| height | **float** | ارتفاع إطار OLE الجديد، بوحدات النقاط. |
| class_name | **str** | اسم الفئة لكائن OLE. |
| path | **str** | مسار الملف المرتبط.<br/><br/>يتم حفظ هذا المسار كما هو في العرض التقديمي.<br/><br/>            إذا تم تحديد مسار نسبي، سيصبح الملف غير قابل للوصول عند فتح<br/><br/>            العرض التقديمي من دليل مختلف. |



### انظر أيضًا
* الفئة [`IOleEmbeddedDataInfo`](/slides/python-net/ar/aspose.slides/ioleembeddeddatainfo)
* الفئة [`IOleObjectFrame`](/slides/python-net/ar/aspose.slides/ioleobjectframe)
* الفئة [`IShapeCollection`](/slides/python-net/ar/aspose.slides/ishapecollection)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)