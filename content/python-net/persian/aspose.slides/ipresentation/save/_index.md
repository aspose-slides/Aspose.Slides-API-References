---
title: save method
second_title: مرجع API Aspose.Slides برای پایتون از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/ipresentation/save/
weight: 80
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
تمام اسلایدهای یک ارائه را در مجموعه‌ای از فایل‌ها که مارکاپ XAML را نشان می‌دهند، ذخیره می‌کند.


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
| fname | **str** | مسیر فایل ایجاد شده. |
| format | [`SaveFormat`](/slides/python-net/fa/aspose.slides.export/saveformat) | فرمت داده‌های استخراج‌شده. |


## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
تمام اسلایدهای یک ارائه را در یک جریان (stream) با فرمت مشخص ذخیره می‌کند.


```python
def save(self, stream, format):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | جریان خروجی. |
| format | [`SaveFormat`](/slides/python-net/fa/aspose.slides.export/saveformat) | فرمت داده‌های استخراج‌شده. |


## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
تمام اسلایدهای یک ارائه را در فایلی با فرمت مشخص و با گزینه‌های اضافی ذخیره می‌کند.


```python
def save(self, fname, format, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| fname | **str** | مسیر فایل ایجاد شده. |
| format | [`SaveFormat`](/slides/python-net/fa/aspose.slides.export/saveformat) | فرمت داده‌های استخراج‌شده. |
| options | [`ISaveOptions`](/slides/python-net/fa/aspose.slides.export/isaveoptions) | گزینه‌های اضافی فرمت. |


## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
تمام اسلایدهای یک ارائه را در یک جریان (stream) با فرمت مشخص و با گزینه‌های اضافی ذخیره می‌کند.


```python
def save(self, stream, format, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | جریان خروجی. |
| format | [`SaveFormat`](/slides/python-net/fa/aspose.slides.export/saveformat) | فرمت داده‌های استخراج‌شده. |
| options | [`ISaveOptions`](/slides/python-net/fa/aspose.slides.export/isaveoptions) | گزینه‌های اضافی فرمت. |

### استثناها

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | اگر سعی کنید فایلی رمزگذاری شده را در <br/>            فرمت غیر Office 2007-2010 ذخیره کنید. |


## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
اسلایدهای مشخص‌شده‌ی یک ارائه را در فایلی با فرمت تعیین‌شده ذخیره می‌کند.


```python
def save(self, fname, slides, format):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| fname | **str** | مسیر فایل ایجاد شده. |
| slides | **List[int]** | آرایه‌ای از موقعیت اسلایدها، شروع از 1. |
| format | [`SaveFormat`](/slides/python-net/fa/aspose.slides.export/saveformat) | فرمت داده‌های استخراج‌شده. |

### استثناها

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | وقتی پارامتر stream یا slides مقدار None باشد. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | وقتی پارامتر slides شامل شماره صفحات نادرست باشد. |
| **RuntimeError(Proxy error(InvalidOperationException))** | وقتی یک SaveFormat پشتیبانی‌نشده استفاده شود، مثلاً PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
اسلایدهای مشخص‌شده‌ی یک ارائه را در یک جریان (stream) با فرمت تعیین‌شده ذخیره می‌کند.


```python
def save(self, stream, slides, format):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | جریان خروجی. |
| slides | **List[int]** | آرایه‌ای از موقعیت اسلایدها، شروع از 1. |
| format | [`SaveFormat`](/slides/python-net/fa/aspose.slides.export/saveformat) | فرمت داده‌های استخراج‌شده. |

### استثناها

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | وقتی پارامتر stream یا slides مقدار None باشد. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | وقتی پارامتر slides شامل شماره صفحات نادرست باشد. |
| **RuntimeError(Proxy error(InvalidOperationException))** | وقتی یک SaveFormat پشتیبانی‌نشده استفاده شود، مثلاً PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
اسلایدهای مشخص‌شده‌ی یک ارائه را در فایلی با فرمت تعیین‌شده ذخیره می‌کند.


```python
def save(self, fname, slides, format, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| fname | **str** | مسیر فایل ایجاد شده. |
| slides | **List[int]** | آرایه‌ای از موقعیت اسلایدها، شروع از 1. |
| format | [`SaveFormat`](/slides/python-net/fa/aspose.slides.export/saveformat) | فرمت داده‌های استخراج‌شده. |
| options | [`ISaveOptions`](/slides/python-net/fa/aspose.slides.export/isaveoptions) | گزینه‌های اضافی فرمت. |

### استثناها

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | وقتی پارامتر stream یا slides مقدار None باشد. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | وقتی پارامتر slides شامل شماره صفحات نادرست باشد. |
| **RuntimeError(Proxy error(InvalidOperationException))** | وقتی یک SaveFormat پشتیبانی‌نشده استفاده شود، مثلاً PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
اسلایدهای مشخص‌شده‌ی یک ارائه را در یک جریان (stream) با فرمت تعیین‌شده ذخیره می‌کند.


```python
def save(self, stream, slides, format, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | جریان خروجی. |
| slides | **List[int]** | آرایه‌ای از موقعیت اسلایدها، شروع از 1. |
| format | [`SaveFormat`](/slides/python-net/fa/aspose.slides.export/saveformat) | فرمت داده‌های استخراج‌شده. |
| options | [`ISaveOptions`](/slides/python-net/fa/aspose.slides.export/isaveoptions) | گزینه‌های اضافی فرمت. |

### استثناها

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | وقتی پارامتر stream یا slides مقدار None باشد. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | وقتی پارامتر slides شامل شماره صفحات نادرست باشد. |
| **RuntimeError(Proxy error(InvalidOperationException))** | وقتی یک SaveFormat پشتیبانی‌نشده استفاده شود، مثلاً PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |



### ببینید همچنین
* کلاس [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation)
* کلاس [`ISaveOptions`](/slides/python-net/fa/aspose.slides.export/isaveoptions)
* کلاس [`IXamlOptions`](/slides/python-net/fa/aspose.slides.export.xaml/ixamloptions)
* شمارش [`SaveFormat`](/slides/python-net/fa/aspose.slides.export/saveformat)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)