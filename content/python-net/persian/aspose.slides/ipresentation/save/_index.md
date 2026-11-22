---
title: save method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/ipresentation/save/
weight: 90
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
تمام اسلایدهای یک ارائه را در مجموعه‌ای از فایل‌ها که markup XAML را نشان می‌دهند ذخیره می‌کند.


```python
def save(self, options):
    ...
```


| پارامتر | نوع | شرح |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/fa/aspose.slides.export.xaml/ixamloptions) | گزینه‌های فرمت XAML. |


## save(self, fname, format) {#str-asposeslidesexportsaveformat}
تمام اسلایدهای یک ارائه را در فایلی با قالب مشخص ذخیره می‌کند.


```python
def save(self, fname, format):
    ...
```


| پارامتر | نوع | شرح |
| :- | :- | :- |
| fname | **str** | مسیر به فایل ایجاد شده. |
| format | [`SaveFormat`](/slides/python-net/fa/aspose.slides.export/saveformat) | قالب داده‌های صادرشده. |


## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
تمام اسلایدهای یک ارائه را در یک جریان با قالب مشخص ذخیره می‌کند.


```python
def save(self, stream, format):
    ...
```


| پارامتر | نوع | شرح |
| :- | :- | :- |
| stream | **io.RawIOBase** | جریان خروجی. |
| format | [`SaveFormat`](/slides/python-net/fa/aspose.slides.export/saveformat) | قالب داده‌های صادرشده. |


## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
تمام اسلایدهای یک ارائه را در فایلی با قالب مشخص و با گزینه‌های اضافی ذخیره می‌کند.


```python
def save(self, fname, format, options):
    ...
```


| پارامتر | نوع | شرح |
| :- | :- | :- |
| fname | **str** | مسیر به فایل ایجاد شده. |
| format | [`SaveFormat`](/slides/python-net/fa/aspose.slides.export/saveformat) | قالب داده‌های صادرشده. |
| options | [`ISaveOptions`](/slides/python-net/fa/aspose.slides.export/isaveoptions) | گزینه‌های فرمت اضافی. |


## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
تمام اسلایدهای یک ارائه را در یک جریان با قالب مشخص و با گزینه‌های اضافی ذخیره می‌کند.


```python
def save(self, stream, format, options):
    ...
```


| پارامتر | نوع | شرح |
| :- | :- | :- |
| stream | **io.RawIOBase** | جریان خروجی. |
| format | [`SaveFormat`](/slides/python-net/fa/aspose.slides.export/saveformat) | قالب داده‌های صادرشده. |
| options | [`ISaveOptions`](/slides/python-net/fa/aspose.slides.export/isaveoptions) | گزینه‌های فرمت اضافی. |

### Exceptions

| استثنا | شرح |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | اگر سعی کنید فایلی رمزنگاری‌شده را در <br/>            قالب غیر Office 2007-2010 ذخیره کنید |


## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
اسلایدهای مشخص‌شده‌ی یک ارائه را در فایلی با قالب مشخص ذخیره می‌کند.


```python
def save(self, fname, slides, format):
    ...
```


| پارامتر | نوع | شرح |
| :- | :- | :- |
| fname | **str** | مسیر به فایل ایجاد شده. |
| slides | **List[int]** | آرایه‌ای با موقعیت اسلایدها، شروع از 1. |
| format | [`SaveFormat`](/slides/python-net/fa/aspose.slides.export/saveformat) | قالب داده‌های صادرشده. |

### Exceptions

| استثنا | شرح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | زمانی که پارامتر stream یا slides مقدار None داشته باشد. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | زمانی که پارامتر slides شامل شماره‌های صفحهٔ نادرست باشد. |
| **RuntimeError(Proxy error(InvalidOperationException))** | زمانی که از SaveFormat پشتیبانی‌نشده‌ای استفاده شود، مثلاً PPTX، PPTM، PPSX، PPSM، POTX، POTM، PPT، ODP. |


## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
اس لایدهای مشخص‌شده‌ی یک ارائه را در یک جریان با قالب مشخص ذخیره می‌کند.


```python
def save(self, stream, slides, format):
    ...
```


| پارامتر | نوع | شرح |
| :- | :- | :- |
| stream | **io.RawIOBase** | جریان خروجی. |
| slides | **List[int]** | آرایه‌ای با موقعیت اسلایدها، شروع از 1. |
| format | [`SaveFormat`](/slides/python-net/fa/aspose.slides.export/saveformat) | قالب داده‌های صادرشده. |

### Exceptions

| استثنا | شرح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | زمانی که پارامتر stream یا slides مقدار None داشته باشد. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | زمانی که پارامتر slides شامل شماره‌های صفحهٔ نادرست باشد. |
| **RuntimeError(Proxy error(InvalidOperationException))** | زمانی که از SaveFormat پشتیبانی‌نشده‌ای استفاده شود، مثلاً PPTX، PPTM، PPSX، PPSM، POTX، POTM، PPT، ODP. |


## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
اسلایدهای مشخص‌شده‌ی یک ارائه را در فایلی با قالب مشخص ذخیره می‌کند.


```python
def save(self, fname, slides, format, options):
    ...
```


| پارامتر | نوع | شرح |
| :- | :- | :- |
| fname | **str** | مسیر به فایل ایجاد شده. |
| slides | **List[int]** | آرایه‌ای با موقعیت اسلایدها، شروع از 1. |
| format | [`SaveFormat`](/slides/python-net/fa/aspose.slides.export/saveformat) | قالب داده‌های صادرشده. |
| options | [`ISaveOptions`](/slides/python-net/fa/aspose.slides.export/isaveoptions) | گزینه‌های فرمت اضافی. |

### Exceptions

| استثنا | شرح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | زمانی که پارامتر stream یا slides مقدار None داشته باشد. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | زمانی که پارامتر slides شامل شماره‌های صفحهٔ نادرست باشد. |
| **RuntimeError(Proxy error(InvalidOperationException))** | زمانی که از SaveFormat پشتیبانی‌نشده‌ای استفاده شود، مثلاً PPTX، PPTM، PPSX، PPSM، POTX، POTM، PPT، ODP. |


## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
اسلایدهای مشخص‌شده‌ی یک ارائه را در یک جریان با قالب مشخص ذخیره می‌کند.


```python
def save(self, stream, slides, format, options):
    ...
```


| پارامتر | نوع | شرح |
| :- | :- | :- |
| stream | **io.RawIOBase** | جریان خروجی. |
| slides | **List[int]** | آرایه‌ای با موقعیت اسلایدها، شروع از 1. |
| format | [`SaveFormat`](/slides/python-net/fa/aspose.slides.export/saveformat) | قالب داده‌های صادرشده. |
| options | [`ISaveOptions`](/slides/python-net/fa/aspose.slides.export/isaveoptions) | گزینه‌های فرمت اضافی. |

### Exceptions

| استثنا | شرح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | زمانی که پارامتر stream یا slides مقدار None داشته باشد. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | زمانی که پارامتر slides شامل شماره‌های صفحهٔ نادرست باشد. |
| **RuntimeError(Proxy error(InvalidOperationException))** | زمانی که از SaveFormat پشتیبانی‌نشده‌ای استفاده شود، مثلاً PPTX، PPTM، PPSX، PPSM، POTX، POTM، PPT، ODP. |



### See Also
* کلاس [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation)
* کلاس [`ISaveOptions`](/slides/python-net/fa/aspose.slides.export/isaveoptions)
* کلاس [`IXamlOptions`](/slides/python-net/fa/aspose.slides.export.xaml/ixamloptions)
* enumeration [`SaveFormat`](/slides/python-net/fa/aspose.slides.export/saveformat)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)