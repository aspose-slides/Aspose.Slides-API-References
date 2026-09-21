---
title: save method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/presentation/save/
weight: 90
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
تمام اسلایدهای یک ارائه را به مجموعه‌ای از فایل‌ها که نشانگر نشانه‌گذاری XAML هستند، ذخیره می‌کند.


```python
def save(self, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/fa/aspose.slides.export.xaml/ixamloptions) | گزینه‌های فرمت XAML. |


## save(self, fname, format) {#str-asposeslidesexportsaveformat}
تمام اسلایدهای یک ارائه را در فایلی با فرمت مشخص ذخیره می‌کند.


```python
def save(self, fname, format):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| fname | **str** | مسیر به فایلی که ایجاد می‌شود. |
| format | [`SaveFormat`](/slides/python-net/fa/aspose.slides.export/saveformat) | فرمت داده‌های صادر شده. |


## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
تمام اسلایدهای یک ارائه را در یک جریان با فرمت مشخص ذخیره می‌کند.


```python
def save(self, stream, format):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | جریان خروجی. |
| format | [`SaveFormat`](/slides/python-net/fa/aspose.slides.export/saveformat) | فرمت داده‌های صادر شده. |


## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}



```python
def save(self, fname, format, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| fname | **str** |  |
| format | [`SaveFormat`](/slides/python-net/fa/aspose.slides.export/saveformat) |  |
| options | [`ISaveOptions`](/slides/python-net/fa/aspose.slides.export/isaveoptions) |  |


## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
تمام اسلایدهای یک ارائه را در یک جریان با فرمت مشخص و با گزینه‌های اضافی ذخیره می‌کند.


```python
def save(self, stream, format, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | جریان خروجی. |
| format | [`SaveFormat`](/slides/python-net/fa/aspose.slides.export/saveformat) | فرمت داده‌های صادر شده. |
| options | [`ISaveOptions`](/slides/python-net/fa/aspose.slides.export/isaveoptions) | گزینه‌های فرمت اضافی. |

### استثناها

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | اگر سعی کنید فایلی رمزگذاری‌شده را در قالبی غیر از Office 2007-2010 ذخیره کنید. |


## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
اسلایدهای مشخص‌شده‌ی یک ارائه را در فایلی با فرمت تعیین‌شده ذخیره می‌کند و شمارهٔ صفحات را حفظ می‌کند.


```python
def save(self, fname, slides, format):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| fname | **str** | مسیر به فایلی که ایجاد می‌شود. |
| slides | **List[int]** | آرایه‌ای از موقعیت‌های اسلاید، شروع از 1. |
| format | [`SaveFormat`](/slides/python-net/fa/aspose.slides.export/saveformat) | فرمت داده‌های صادر شده. |

### استثناها

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | هنگامی که پارامتر stream یا slides مقدار None داشته باشد. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | هنگامی که پارامتر slides شامل شمارهٔ صفحات نادرست باشد. |
| **RuntimeError(Proxy error(InvalidOperationException))** | هنگامی که از SaveFormat پشتیبانی‌نشده‌ای استفاده شود، مثلاً PPTX، PPTM، PPSX، PPSM، POTX، POTM، PPT، ODP. |


## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
اسلایدهای مشخص‌شده‌ی یک ارائه را در یک جریان با فرمت تعیین‌شده ذخیره می‌کند و شمارهٔ صفحات را حفظ می‌کند.


```python
def save(self, stream, slides, format):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | جریان خروجی. |
| slides | **List[int]** | آرایه‌ای از موقعیت‌های اسلاید، شروع از 1. |
| format | [`SaveFormat`](/slides/python-net/fa/aspose.slides.export/saveformat) | فرمت داده‌های صادر شده. |


## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
اسلایدهای مشخص‌شده‌ی یک ارائه را در فایلی با فرمت تعیین‌شده ذخیره می‌کند و شمارهٔ صفحات را حفظ می‌کند.


```python
def save(self, fname, slides, format, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| fname | **str** | مسیر به فایلی که ایجاد می‌شود. |
| slides | **List[int]** | آرایه‌ای از موقعیت‌های اسلاید، شروع از 1. |
| format | [`SaveFormat`](/slides/python-net/fa/aspose.slides.export/saveformat) | فرمت داده‌های صادر شده. |
| options | [`ISaveOptions`](/slides/python-net/fa/aspose.slides.export/isaveoptions) | گزینه‌های فرمت اضافی. |


## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
اسلایدهای مشخص‌شده‌ی یک ارائه را در یک جریان با فرمت تعیین‌شده ذخیره می‌کند و شمارهٔ صفحات را حفظ می‌کند.


```python
def save(self, stream, slides, format, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | جریان خروجی. |
| slides | **List[int]** | آرایه‌ای از موقعیت‌های اسلاید، شروع از 1. |
| format | [`SaveFormat`](/slides/python-net/fa/aspose.slides.export/saveformat) | فرمت داده‌های صادر شده. |
| options | [`ISaveOptions`](/slides/python-net/fa/aspose.slides.export/isaveoptions) | گزینه‌های فرمت اضافی. |

### استثناها

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | هنگامی که پارامتر stream یا slides مقدار None داشته باشد. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | هنگامی که پارامتر slides شامل شمارهٔ صفحات نادرست باشد. |
| **RuntimeError(Proxy error(InvalidOperationException))** | هنگامی که از SaveFormat پشتیبانی‌نشده‌ای استفاده شود، مثلاً PPTX، PPTM، PPSX، PPSM، POTX، POTM، PPT، ODP. |



### موارد مرتبط
* کلاس [`ISaveOptions`](/slides/python-net/fa/aspose.slides.export/isaveoptions)
* کلاس [`IXamlOptions`](/slides/python-net/fa/aspose.slides.export.xaml/ixamloptions)
* کلاس [`Presentation`](/slides/python-net/fa/aspose.slides/presentation)
* شمارش [`SaveFormat`](/slides/python-net/fa/aspose.slides.export/saveformat)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)