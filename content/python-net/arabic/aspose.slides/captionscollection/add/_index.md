---
title: add method
second_title: Aspose.Slides للـ Python عبر .NET API Reference
description: 
type: docs
url: /ar/aspose.slides/captionscollection/add/
weight: 10
---
## add(self, label, file_path) {#str-str}
يضيف ترجمات WebVTT المغلقة إلى نهاية المجموعة.

### القيم المرجعة

The added [`ICaptions`](/slides/python-net/ar/aspose.slides/icaptions) instance.



```python
def add(self, label, file_path):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| label | **str** | العلامة للترجمات المغلقة. |
| file_path | **str** | المسار إلى ملف WebVTT. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | يتم رميه إذا كان `file_path` هو `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | يتم رميه إذا كان `file_path` فارغًا. |


## add(self, label, stream) {#str-iorawiobase}
يضيف ترجمات WebVTT المغلقة إلى نهاية المجموعة من stream.

### القيم المرجعة

The added [`ICaptions`](/slides/python-net/ar/aspose.slides/icaptions) instance.



```python
def add(self, label, stream):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| label | **str** | العلامة للترجمات المغلقة. |
| stream | **io.RawIOBase** | دفق الإدخال الذي يحتوي على بيانات بصيغة WebVTT. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | يتم رميه إذا كان `stream` هو `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | يتم رميه إذا لم تكن بيانات الإدخال بتنسيق WebVTT. |



### انظر أيضًا
* الفئة [`CaptionsCollection`](/slides/python-net/ar/aspose.slides/captionscollection)
* الفئة [`ICaptions`](/slides/python-net/ar/aspose.slides/icaptions)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)