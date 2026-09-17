---
title: add method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/icaptionscollection/add/
weight: 10
---
## add(self, label, file_path) {#str-str}
يضيف تسميات توضيحية مغلقة بتنسيق WebVTT إلى نهاية المجموعة.

### القيمة المرجعة

الكائن [`ICaptions`](/slides/python-net/ar/aspose.slides/icaptions) المضاف.



```python
def add(self, label, file_path):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| label | **str** | العلامة الخاصة بالتعليقات المغلقة. |
| file_path | **str** | المسار إلى ملف WebVTT. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | يُلقى إذا كان `file_path` هو `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | يُلقى إذا كان `file_path` فارغًا. |


## add(self, label, stream) {#str-iorawiobase}
يضيف تسميات توضيحية مغلقة بتنسيق WebVTT إلى نهاية المجموعة من تدفق.

### القيمة المرجعة

الكائن [`ICaptions`](/slides/python-net/ar/aspose.slides/icaptions) المضاف.



```python
def add(self, label, stream):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| label | **str** | العلامة الخاصة بالتعليقات المغلقة. |
| stream | **io.RawIOBase** | تيار الإدخال الذي يحتوي على بيانات بتنسيق WebVTT. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | يُلقى إذا كان `stream` هو `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | يُلقى إذا لم تكن بيانات الإدخال بتنسيق WebVTT. |



### انظر أيضًا
* فئة [`ICaptions`](/slides/python-net/ar/aspose.slides/icaptions)
* فئة [`ICaptionsCollection`](/slides/python-net/ar/aspose.slides/icaptionscollection)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)