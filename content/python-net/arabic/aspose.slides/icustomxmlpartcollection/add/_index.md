---
title: add method
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/icustomxmlpartcollection/add/
weight: 10
---
## add(self, xml_data) {#bytes}
يضيف جزء xml مخصص جديد.

### القيمة المرجعة

تم إنشاء جزء xml مخصص.



```python
def add(self, xml_data):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| xml_data | **bytes** | بيانات xml للجزء الجديد الذي سيُضاف. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlData هو `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlData فارغ أو غير صالح. |


## add(self, xml_string) {#str}
يضيف جزء xml مخصص جديد.

### القيمة المرجعة

تم إنشاء جزء xml مخصص.



```python
def add(self, xml_string):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| xml_string | **str** | سلسلة xml للجزء الجديد الذي سيُضاف. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlString هو `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlString فارغ أو بيانات xml غير صالحة. |


## add(self, input_stream) {#iorawiobase}
يضيف جزء xml مخصص جديد.

### القيمة المرجعة

تم إنشاء جزء xml مخصص.



```python
def add(self, input_stream):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| input_stream | **io.RawIOBase** | تدفق الإدخال مع بيانات xml للجزء الجديد الذي سيُضاف. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | inputStream هو `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | البيانات في inputStream فارغة أو غير صالحة. |



### انظر أيضًا
* الفئة [`ICustomXmlPart`](/slides/python-net/ar/aspose.slides/icustomxmlpart)
* الفئة [`ICustomXmlPartCollection`](/slides/python-net/ar/aspose.slides/icustomxmlpartcollection)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)