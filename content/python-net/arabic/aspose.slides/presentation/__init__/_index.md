---
title: Presentation constructor
second_title: Aspose.Slides للبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/presentation/__init__/
weight: 10
---
## __init__(self) {#}
هذا المُنشئ يُنشئ عرضًا تقديميًا جديدًا من الصفر.
            العرض المُنشأ يحتوي على شريحة فارغة واحدة.


```python
def __init__(self):
    ...
```



## __init__(self, load_options) {#loadoptions}
هذا المُنشئ يُنشئ عرضًا تقديميًا جديدًا من الصفر.
            العرض المُنشأ يحتوي على شريحة فارغة واحدة.


```python
def __init__(self, load_options):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| load_options | [`LoadOptions`](/slides/python-net/ar/aspose.slides/loadoptions) | خيارات تحميل إضافية. |


## __init__(self, stream) {#iorawiobase}
هذا المُنشئ هو الآلية الأساسية لقراءة عرض تقديمي موجود بالفعل.


```python
def __init__(self, stream):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| stream | **io.RawIOBase** | دفق الإدخال. |


## __init__(self, file) {#str}
هذا المُنشئ يحصل على مسار ملف المصدر الذي تُقَرَأ منه محتويات العرض التقديمي.


```python
def __init__(self, file):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| file | **str** | ملف الإدخال. |

### استثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | يُطرح عندما يكون ملف الإدخال بطول صفر |


## __init__(self, stream, load_options) {#iorawiobase-loadoptions}
هذا المُنشئ هو الآلية الأساسية لقراءة عرض تقديمي موجود بالفعل.


```python
def __init__(self, stream, load_options):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| stream | **io.RawIOBase** | دفق الإدخال. |
| load_options | [`LoadOptions`](/slides/python-net/ar/aspose.slides/loadoptions) | خيارات تحميل إضافية. |


## __init__(self, file, load_options) {#str-loadoptions}
هذا المُنشئ يحصل على مسار ملف المصدر الذي تُقَرَأ منه محتويات العرض التقديمي.


```python
def __init__(self, file, load_options):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| file | **str** | ملف الإدخال. |
| load_options | [`LoadOptions`](/slides/python-net/ar/aspose.slides/loadoptions) | خيارات تحميل إضافية. |

### استثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | يُطرح عندما يكون ملف الإدخال بطول صفر |



### انظر أيضًا
* فئة [`LoadOptions`](/slides/python-net/ar/aspose.slides/loadoptions)
* فئة [`Presentation`](/slides/python-net/ar/aspose.slides/presentation)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)