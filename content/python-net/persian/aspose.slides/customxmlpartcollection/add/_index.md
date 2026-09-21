---
title: add method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/customxmlpartcollection/add/
weight: 10
---
## add(self, xml_string) {#str}
یک قسمت XML سفارشی جدید اضافه می‌کند.

### بازگشت

قسمت XML سفارشی ایجاد شد.



```python
def add(self, xml_string):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| xml_string | **str** | رشتهٔ XML قسمت جدید برای اضافه شدن. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlString برابر با `None` است. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlString خالی است یا داده‌های xml نامعتبر هستند. |


## add(self, xml_data) {#bytes}
یک قسمت XML سفارشی جدید اضافه می‌کند.

### بازگشت

قسمت XML سفارشی ایجاد شد.



```python
def add(self, xml_data):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| xml_data | **bytes** | دادهٔ XML قسمت جدید برای اضافه شدن. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlData برابر با `None` است. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlData خالی است یا نامعتبر است. |


## add(self, input_stream) {#iorawiobase}
یک قسمت XML سفارشی جدید اضافه می‌کند.

### بازگشت

قسمت XML سفارشی ایجاد شد.



```python
def add(self, input_stream):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| input_stream | **io.RawIOBase** | جریان ورودی با دادهٔ XML قسمت جدید برای اضافه شدن. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | inputStream برابر با `None` است. |
| **RuntimeError(Proxy error(ArgumentException))** | داده‌های موجود در inputStream خالی یا نامعتبر هستند. |



### موارد مرتبط
* کلاس [`CustomXmlPartCollection`](/slides/python-net/fa/aspose.slides/customxmlpartcollection)
* کلاس [`ICustomXmlPart`](/slides/python-net/fa/aspose.slides/icustomxmlpart)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)