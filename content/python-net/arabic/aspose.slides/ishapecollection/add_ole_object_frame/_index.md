---
title: add_ole_object_frame method
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/ishapecollection/add_ole_object_frame/
weight: 100
---
## add_ole_object_frame(self, x, y, width, height, data_info) {#float-float-float-float-ioleembeddeddatainfo}
يُنشئ إطار OLE جديدًا ويضيفه إلى نهاية مجموعة الأشكال.

### القيمة المرجعة

[`IOleObjectFrame`](/slides/python-net/ar/aspose.slides/ioleobjectframe) التي تم إنشاؤها حديثًا.

```python
def add_ole_object_frame(self, x, y, width, height, data_info):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | الإحداثي x لإطار OLE الجديد، بالنقاط. |
| y | **float** | الإحداثي y لإطار OLE الجديد، بالنقاط. |
| width | **float** | العرض لإطار OLE الجديد، بالنقاط. |
| height | **float** | الارتفاع لإطار OLE الجديد، بالنقاط. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/ar/aspose.slides/ioleembeddeddatainfo) | معلومات بيانات OLE المضمنة ([`IOleEmbeddedDataInfo`](/slides/python-net/ar/aspose.slides/ioleembeddeddatainfo)). |

## add_ole_object_frame(self, x, y, width, height, class_name, path) {#float-float-float-float-str-str}
يُنشئ إطار OLE جديدًا ويضيفه إلى نهاية مجموعة الأشكال.

### القيمة المرجعة

[`IOleObjectFrame`](/slides/python-net/ar/aspose.slides/ioleobjectframe) التي تم إنشاؤها حديثًا.

```python
def add_ole_object_frame(self, x, y, width, height, class_name, path):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | الإحداثي x لإطار OLE الجديد، بالنقاط. |
| y | **float** | الإحداثي y لإطار OLE الجديد، بالنقاط. |
| width | **float** | العرض لإطار OLE الجديد، بالنقاط. |
| height | **float** | الارتفاع لإطار OLE الجديد، بالنقاط. |
| class_name | **str** | اسم الفئة لكائن OLE. |
| path | **str** | المسار إلى الملف المرتبط.<br/><br/>يتم تخزين هذا المسار كما هو في العرض التقديمي.<br/><br/>إذا تم تحديد مسار نسبي، فإن الملف سيكون غير قابل للوصول عند فتح<br/><br/>العرض التقديمي من دليل مختلف. |

### أنظر أيضًا
* الفئة [`IOleEmbeddedDataInfo`](/slides/python-net/ar/aspose.slides/ioleembeddeddatainfo)
* الفئة [`IOleObjectFrame`](/slides/python-net/ar/aspose.slides/ioleobjectframe)
* الفئة [`IShapeCollection`](/slides/python-net/ar/aspose.slides/ishapecollection)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)