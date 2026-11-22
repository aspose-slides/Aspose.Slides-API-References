---
title: save method
second_title: راهنمای API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/presentation/save/
weight: 100
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
تمام اسلایدهای یک ارائه را در مجموعه‌ای از فایل‌ها که markup XAML را نشان می‌دهند، ذخیره می‌کند.

```python
def save(self, options):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/fa/aspose.slides.export.xaml/ixamloptions) | گزینه‌های فرمت XAML. |

## save(self, fname, format) {#str-asposeslidesexportsaveformat}
تمام اسلایدهای یک ارائه را در فایلی با فرمت مشخص ذخیره می‌کند.

```python
def save(self, fname, format):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| fname | **str** | مسیر فایل ایجاد شده. |
| format | [`SaveFormat`](/slides/python-net/fa/aspose.slides.export/saveformat) | فرمت داده‌های صادر شده. |

## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
تمام اسلایدهای یک ارائه را در یک جریان با فرمت مشخص ذخیره می‌کند.

```python
def save(self, stream, format):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| stream | **io.RawIOBase** | جریان خروجی. |
| format | [`SaveFormat`](/slides/python-net/fa/aspose.slides.export/saveformat) | فرمت داده‌های صادر شده. |

## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}

```python
def save(self, fname, format, options):
    ...
```

| پارامتر | نوع | توضیح |
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

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| stream | **io.RawIOBase** | جریان خروجی. |
| format | [`SaveFormat`](/slides/python-net/fa/aspose.slides.export/saveformat) | فرمت داده‌های صادر شده. |
| options | [`ISaveOptions`](/slides/python-net/fa/aspose.slides.export/isaveoptions) | گزینه‌های فرمت اضافی. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | اگر سعی کنید فایلی رمزنگاری شده را در <br/>            قالبی غیر Office 2007-2010 ذخیره کنید. |

## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
اسلایدهای مشخص شده‌ی یک ارائه را در فایلی با فرمت مشخص، با حفظ شماره صفحه، ذخیره می‌کند.

```python
def save(self, fname, slides, format):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| fname | **str** | مسیر فایل ایجاد شده. |
| slides | **List[int]** | آرایه‌ای از موقعیت اسلایدها، شروع از 1. |
| format | [`SaveFormat`](/slides/python-net/fa/aspose.slides.export/saveformat) | فرمت داده‌های صادر شده. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | زمانی که پارامتر stream یا slides مقدار None دارد. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | زمانی که پارامتر slides شامل شماره صفحات نادرست باشد. |
| **RuntimeError(Proxy error(InvalidOperationException))** | زمانی که یک SaveFormat پشتیبانی نشده استفاده شود، مانند PPTX، PPTM، PPSX، PPSM، POTX، POTM، PPT، ODP. |

## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
اسلایدهای مشخص شده‌ی یک ارائه را در یک جریان با فرمت مشخص، با حفظ شماره صفحه، ذخیره می‌کند.

```python
def save(self, stream, slides, format):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| stream | **io.RawIOBase** | جریان خروجی. |
| slides | **List[int]** | آرایه‌ای از موقعیت اسلایدها، شروع از 1. |
| format | [`SaveFormat`](/slides/python-net/fa/aspose.slides.export/saveformat) | فرمت داده‌های صادر شده. |

## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
اسلایدهای مشخص شده‌ی یک ارائه را در فایلی با فرمت مشخص، با حفظ شماره صفحه، ذخیره می‌کند.

```python
def save(self, fname, slides, format, options):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| fname | **str** | مسیر فایل ایجاد شده. |
| slides | **List[int]** | آرایه‌ای از موقعیت اسلایدها، شروع از 1. |
| format | [`SaveFormat`](/slides/python-net/fa/aspose.slides.export/saveformat) | فرمت داده‌های صادر شده. |
| options | [`ISaveOptions`](/slides/python-net/fa/aspose.slides.export/isaveoptions) | گزینه‌های فرمت اضافی. |

## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
اسلایدهای مشخص شده‌ی یک ارائه را در یک جریان با فرمت مشخص، با حفظ شماره صفحه، ذخیره می‌کند.

```python
def save(self, stream, slides, format, options):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| stream | **io.RawIOBase** | جریان خروجی. |
| slides | **List[int]** | آرایه‌ای از موقعیت اسلایدها، شروع از 1. |
| format | [`SaveFormat`](/slides/python-net/fa/aspose.slides.export/saveformat) | فرمت داده‌های صادر شده. |
| options | [`ISaveOptions`](/slides/python-net/fa/aspose.slides.export/isaveoptions) | گزینه‌های فرمت اضافی. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | زمانی که پارامتر stream یا slides مقدار None دارد. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | زمانی که پارامتر slides شامل شماره صفحات نادرست باشد. |
| **RuntimeError(Proxy error(InvalidOperationException))** | زمانی که یک SaveFormat پشتیبانی نشده استفاده شود، مانند PPTX، PPTM، PPSX، PPSM، POTX، POTM، PPT، ODP. |

### مراجع
* کلاس [`ISaveOptions`](/slides/python-net/fa/aspose.slides.export/isaveoptions)
* کلاس [`IXamlOptions`](/slides/python-net/fa/aspose.slides.export.xaml/ixamloptions)
* کلاس [`Presentation`](/slides/python-net/fa/aspose.slides/presentation)
* enumeration [`SaveFormat`](/slides/python-net/fa/aspose.slides.export/saveformat)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)