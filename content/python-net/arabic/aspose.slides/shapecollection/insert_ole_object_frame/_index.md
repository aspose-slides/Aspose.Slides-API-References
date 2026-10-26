---
title: insert_ole_object_frame method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/shapecollection/insert_ole_object_frame/
weight: 280
---
## insert_ole_object_frame(self, index, x, y, width, height, data_info) {#int-float-float-float-float-ioleembeddeddatainfo}
إنشاء إطار كائن OLE جديد وإدراجه في مجموعة الأشكال في الفهرس المحدد.

### إرجاع

الكائن الجديد [`IOleObjectFrame`](/slides/python-net/ar/aspose.slides/ioleobjectframe).



```python
def insert_ole_object_frame(self, index, x, y, width, height, data_info):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| index | **int** | الفهرس الصفري الذي يُدرج فيه إطار كائن OLE. |
| x | **float** | الإحداثي السيني لإطار OLE الجديد، بالنقاط. |
| y | **float** | الإحداثي الصادي لإطار OLE الجديد، بالنقاط. |
| width | **float** | عرض إطار OLE الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار OLE الجديد، بالنقاط. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/ar/aspose.slides/ioleembeddeddatainfo) | معلومات بيانات OLE المدمجة ([`IOleEmbeddedDataInfo`](/slides/python-net/ar/aspose.slides/ioleembeddeddatainfo)). |


## insert_ole_object_frame(self, index, x, y, width, height, class_name, path) {#int-float-float-float-float-str-str}
إنشاء إطار كائن OLE جديد وإدراجه في مجموعة الأشكال في الفهرس المحدد.

### إرجاع

إطار كائن OLE المُنشأ حديثًا.



```python
def insert_ole_object_frame(self, index, x, y, width, height, class_name, path):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| index | **int** | الفهرس الصفري الذي يُدرج فيه إطار كائن OLE. |
| x | **float** | الإحداثي السيني لإطار OLE الجديد، بالنقاط. |
| y | **float** | الإحداثي الصادي لإطار OLE الجديد، بالنقاط. |
| width | **float** | عرض إطار OLE الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار OLE الجديد، بالنقاط. |
| class_name | **str** | اسم الفئة لكائن OLE. |
| path | **str** | مسار الملف المرتبط. <br/><br/>يُحفظ هذا المسار كما هو في العرض التقديمي.<br/><br/>            إذا تم تحديد مسار نسبي، فإن الملف سيصبح غير قابل للوصول عند فتح<br/><br/>            العرض التقديمي من دليل مختلف. |



### انظر أيضا
* الفئة [`IOleEmbeddedDataInfo`](/slides/python-net/ar/aspose.slides/ioleembeddeddatainfo)
* الفئة [`IOleObjectFrame`](/slides/python-net/ar/aspose.slides/ioleobjectframe)
* الفئة [`ShapeCollection`](/slides/python-net/ar/aspose.slides/shapecollection)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)