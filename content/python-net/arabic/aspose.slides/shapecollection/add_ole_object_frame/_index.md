---
title: add_ole_object_frame method
second_title: Aspose.Slides للـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/shapecollection/add_ole_object_frame/
weight: 100
---
## add_ole_object_frame(self, x, y, width, height, data_info) {#float-float-float-float-ioleembeddeddatainfo}
ينشئ إطار كائن OLE جديدًا ويضيفه إلى نهاية مجموعة الأشكال.

### القيمة المرجعة

الـ[`IOleObjectFrame`](/slides/python-net/ar/aspose.slides/ioleobjectframe) الذي تم إنشاؤه حديثًا.



```python
def add_ole_object_frame(self, x, y, width, height, data_info):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| x | **float** | الإحداثي x لإطار OLE الجديد، بالنقاط. |
| y | **float** | الإحداثي y لإطار OLE الجديد، بالنقاط. |
| width | **float** | عرض إطار OLE الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار OLE الجديد، بالنقاط. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/ar/aspose.slides/ioleembeddeddatainfo) | المعلومات حول بيانات OLE المضمنة ([`IOleEmbeddedDataInfo`](/slides/python-net/ar/aspose.slides/ioleembeddeddatainfo)). |


## add_ole_object_frame(self, x, y, width, height, class_name, path) {#float-float-float-float-str-str}
ينشئ إطار كائن OLE جديدًا ويضيفه إلى نهاية مجموعة الأشكال.

### القيمة المرجعة

الـ[`IOleObjectFrame`](/slides/python-net/ar/aspose.slides/ioleobjectframe) الذي تم إنشاؤه حديثًا.



```python
def add_ole_object_frame(self, x, y, width, height, class_name, path):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| x | **float** | الإحداثي x لإطار OLE الجديد، بالنقاط. |
| y | **float** | الإحداثي y لإطار OLE الجديد، بالنقاط. |
| width | **float** | عرض إطار OLE الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار OLE الجديد، بالنقاط. |
| class_name | **str** | اسم الفئة لكائن OLE. |
| path | **str** | مسار الملف المرتبط. <br/><br/>يُخزن هذا المسار كما هو في العرض التقديمي.<br/><br/>            إذا تم تحديد مسار نسبي، سيكون الملف غير قابل للوصول عند فتح<br/><br/>            العرض التقديمي من دليل مختلف. |



### انظر أيضًا
* الفئة [`IOleEmbeddedDataInfo`](/slides/python-net/ar/aspose.slides/ioleembeddeddatainfo)
* الفئة [`IOleObjectFrame`](/slides/python-net/ar/aspose.slides/ioleobjectframe)
* الفئة [`ShapeCollection`](/slides/python-net/ar/aspose.slides/shapecollection)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)