---
title: add method
second_title: Aspose.Slides للغة بايثون عبر .NET – مرجع API
description: 
type: docs
url: /ar/aspose.slides/customxmlpartcollection/add/
weight: 10
---
## add(self, xml_string) {#str}
يضيف جزء XML مخصص جديد.

### Returns
القيمة المرجعة

Created custom xml part.



```python
def add(self, xml_string):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| xml_string | **str** | سلسلة XML للجزء الجديد الذي سيُضاف. |

### Exceptions
| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlString هو `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlString فارغ أو بيانات XML غير صالحة. |


## add(self, xml_data) {#bytes}
يضيف جزء XML مخصص جديد.

### Returns
القيمة المرجعة

Created custom xml part.



```python
def add(self, xml_data):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| xml_data | **bytes** | بيانات XML للجزء الجديد الذي سيُضاف. |

### Exceptions
| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlData هو `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlData فارغ أو غير صالح. |


## add(self, input_stream) {#iorawiobase}
يضيف جزء XML مخصص جديد.

### Returns
القيمة المرجعة

Created custom xml part.



```python
def add(self, input_stream):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| input_stream | **io.RawIOBase** | دفق الإدخال inputStream يحتوي على بيانات XML للجزء الجديد الذي سيُضاف. |

### Exceptions
| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | inputStream هو `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | البيانات في inputStream فارغة أو غير صالحة. |



### See Also
* الفئة [`CustomXmlPartCollection`](/slides/python-net/ar/aspose.slides/customxmlpartcollection)
* الفئة [`ICustomXmlPart`](/slides/python-net/ar/aspose.slides/icustomxmlpart)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)