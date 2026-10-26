---
title: add method
second_title: مرجع API Aspose.Slides برای پایتون از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/icustomxmlpartcollection/add/
weight: 10
---
## add(self, xml_data) {#bytes}
یک بخش xml سفارشی جدید اضافه می‌کند.

### Returns
بخش xml سفارشی ایجاد شد.



```python
def add(self, xml_data):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| xml_data | **bytes** | داده xml بخش جدیدی که باید اضافه شود. |

### Exceptions
| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlData برابر `None` است. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlData خالی یا نامعتبر است. |


## add(self, xml_string) {#str}
یک بخش xml سفارشی جدید اضافه می‌کند.

### Returns
بخش xml سفارشی ایجاد شد.



```python
def add(self, xml_string):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| xml_string | **str** | رشته xml بخش جدیدی که باید اضافه شود. |

### Exceptions
| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlString برابر `None` است. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlString خالی یا xml-data نامعتبر است. |


## add(self, input_stream) {#iorawiobase}
یک بخش xml سفارشی جدید اضافه می‌کند.

### Returns
بخش xml سفارشی ایجاد شد.



```python
def add(self, input_stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| input_stream | **io.RawIOBase** | جریان ورودی (inputStream) حاوی داده xml بخش جدیدی که باید اضافه شود. |

### Exceptions
| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | inputStream برابر `None` است. |
| **RuntimeError(Proxy error(ArgumentException))** | داده در inputStream خالی یا Sinvalid است. |



### See Also
* کلاس [`ICustomXmlPart`](/slides/python-net/fa/aspose.slides/icustomxmlpart)
* کلاس [`ICustomXmlPartCollection`](/slides/python-net/fa/aspose.slides/icustomxmlpartcollection)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)