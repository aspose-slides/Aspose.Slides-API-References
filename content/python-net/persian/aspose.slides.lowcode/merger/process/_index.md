---
title: process method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.lowcode/merger/process/
weight: 10
---
## process(input_file_names, output_file_name) {#liststr-str}
ارائه‌های PowerPoint چندتایی با فرمت یکسان را در یک فایل ارائه ترکیب می‌کند.

```python
@staticmethod
def process(input_file_names, output_file_name):
    ...
```

| پارامتر | نوع | توضیحات |
| :- | :- | :- |
| input_file_names | **List[str]** | آرایه‌ای از نام‌های فایل ارائه‌های ورودی. |
| output_file_name | **str**** | نام فایل خروجی ارائه ترکیبی حاصل شده. |

### استثناها

| استثنا | توضیحات |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | در صورتی که نام‌های فایل ورودی نامعتبر باشند یا فرمت‌ها مطابقت نداشته باشند، پرتاب می‌شود. |

## process(input_file_names, output_stream) {#liststr-iorawiobase}
ارائه‌های PowerPoint چندتایی با فرمت یکسان را در یک فایل ارائه ترکیب می‌کند.

```python
@staticmethod
def process(input_file_names, output_stream):
    ...
```

| پارامتر | نوع | توضیحات |
| :- | :- | :- |
| input_file_names | **List[str]** | آرایه‌ای از نام‌های فایل ارائه‌های ورودی. |
| output_stream | **io.RawIOBase** | جریان خروجی. |

### استثناها

| استثنا | توضیحات |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | در صورتی که نام‌های فایل ورودی نامعتبر باشند یا فرمت‌ها مطابقت نداشته باشند، پرتاب می‌شود. |

## process(input_file_names, output_file_name, options) {#liststr-str-asposeslidesexportisaveoptions}
ارائه‌های PowerPoint چندتایی با فرمت یکسان را در یک فایل ارائه ترکیب می‌کند.

```python
@staticmethod
def process(input_file_names, output_file_name, options):
    ...
```

| پارامتر | نوع | توضیحات |
| :- | :- | :- |
| input_file_names | **List[str]** | آرایه‌ای از نام‌های فایل ارائه‌های ورودی. |
| output_file_name | **str** | نام فایل خروجی ارائه ترکیبی حاصل شده. |
| options | [`ISaveOptions`](/slides/python-net/fa/aspose.slides.export/isaveoptions) | گزینه‌های اضافی که نحوه ذخیره‌سازی ارائه ترکیبی را تعریف می‌کنند. |

### استثناها

| استثنا | توضیحات |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | در صورتی که نام‌های فایل ورودی نامعتبر باشند یا فرمت‌ها مطابقت نداشته باشند، پرتاب می‌شود. |

## process(input_file_names, output_stream, options) {#liststr-iorawiobase-asposeslidesexportisaveoptions}
ارائه‌های PowerPoint چندتایی با فرمت یکسان را در یک فایل ارائه ترکیب می‌کند.

```python
@staticmethod
def process(input_file_names, output_stream, options):
    ...
```

| پارامتر | نوع | توضیحات |
| :- | :- | :- |
| input_file_names | **List[str]** | آرایه‌ای از نام‌های فایل ارائه‌های ورودی. |
| output_stream | **io.RawIOBase** | جریان خروجی. |
| options | [`ISaveOptions`](/slides/python-net/fa/aspose.slides.export/isaveoptions) | گزینه‌های اضافی که نحوه ذخیره‌سازی ارائه ترکیبی را تعریف می‌کنند. |

### استثناها

| استثنا | توضیحات |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | در صورتی که نام‌های فایل ورودی نامعتبر باشند یا فرمت‌ها مطابقت نداشته باشند، پرتاب می‌شود. |

### موارد مرتبط
* کلاس [`ISaveOptions`](/slides/python-net/fa/aspose.slides.export/isaveoptions)
* کلاس [`Merger`](/slides/python-net/fa/aspose.slides.lowcode/merger)
* ماژول [`aspose.slides.lowcode`](/slides/python-net/fa/aspose.slides.lowcode)
* کتابخانه [`Aspose.Slides`](/slides/python-net)