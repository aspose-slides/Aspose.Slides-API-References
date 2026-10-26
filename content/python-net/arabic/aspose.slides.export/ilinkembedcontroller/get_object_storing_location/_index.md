---
title: get_object_storing_location method
second_title: مرجع API Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/
weight: 10
---
## get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension) {#int-bytes-str-str-str}
يحدد أين يجب تخزين الكائن.
            يتم استدعاء هذه الطريقة مرة واحدة لكل معرّف الكائن id.
            ليس هناك ضمان بأنه لن يكون هناك كائنان ببيانات، semanticName و contentType متطابقة ولكن مع معرّف مختلف.

### الإرجاع

القرار



```python
def get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension):
    ...
```


| المعلمة | النوع | الوصف |
| :- | :- | :- |
| id | **int** | معرّف الكائن id. هذا id فريد على مستوى عملية الحفظ. |
| entity_data | **bytes** | بيانات ثنائية للكائن. يمكن أن تكون هذه المعلمة None إذا لم تُنشأ بيانات ثنائية للكائن بعد. |
| semantic_name | **str** | نص قصير يصف معنى الكائن. قد يستخدم المتحكم هذا كجزء من اسم الكائن الخارجي، لكن الأمر متروك للموزّع لضمان أن تكون الأسماء فريدة وتحتوي على الأحرف المسموح بها فقط. |
| content_type | **str** | نوع MIME للكائن. |
| recomended_extension | **str** | امتداد اسم الملف، الموصى به لهذا النوع MIME. |



### انظر أيضًا
* الفئة [`ILinkEmbedController`](/slides/python-net/ar/aspose.slides.export/ilinkembedcontroller)
* التعداد [`LinkEmbedDecision`](/slides/python-net/ar/aspose.slides.export/linkembeddecision)
* الوحدة [`aspose.slides.export`](/slides/python-net/ar/aspose.slides.export)
* المكتبة [`Aspose.Slides`](/slides/python-net)