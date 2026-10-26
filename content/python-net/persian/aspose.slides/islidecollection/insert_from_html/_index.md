---
title: insert_from_html method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/islidecollection/insert_from_html/
weight: 80
---
## insert_from_html(self, index, html_text) {#int-str}
اسلایدها را از متن HTML ایجاد می‌کند و آنها را در مجموعه در موقعیت مشخص شده درج می‌کند.

### مقدار بازگشتی
اسلایدهای اضافه شده

```python
def insert_from_html(self, index, html_text):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | موقعیت درج. |
| html_text | **str** | HTML برای افزودن. |

## insert_from_html(self, index, html_stream) {#int-iorawiobase}
اسلایدها را از متن HTML ایجاد می‌کند و آنها را در مجموعه در موقعیت مشخص شده درج می‌کند.

### مقدار بازگشتی
اسلایدهای اضافه شده

```python
def insert_from_html(self, index, html_stream):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | موقعیت درج. |
| html_stream | **io.RawIOBase** | یک شیء Stream که به عنوان منبع یک فایل HTML استفاده خواهد شد. |

## insert_from_html(self, index, html_text, use_slide_with_index_as_start) {#int-str-bool}
اسلایدها را از متن HTML ایجاد می‌کند و آنها را در مجموعه در موقعیت مشخص شده درج می‌کند.

### مقدار بازگشتی
اسلایدهای اضافه شده

```python
def insert_from_html(self, index, html_text, use_slide_with_index_as_start):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | موقعیت درج. |
| html_text | **str** | HTML برای افزودن. |
| use_slide_with_index_as_start | **bool** | این پرچم تعیین می‌کند که درج از کجا آغاز شود: از یک اسلاید جدید یا از اسلایدی با ایندکس مشخص شده.<br/><br/>            اگر **true** باشد، درج داده‌ها از یک فضای خالی در اسلاید با ایندکس مشخص شده شروع می‌شود.<br/><br/>            اگر **false** باشد، داده‌ها به اسلایدهای ایجاد شده اضافه می‌شوند. |

## insert_from_html(self, index, html_stream, use_slide_with_index_as_start) {#int-iorawiobase-bool}
اسلایدها را از متن HTML ایجاد می‌کند و آنها را در مجموعه در موقعیت مشخص شده درج می‌کند.

### مقدار بازگشتی
اسلایدهای اضافه شده

```python
def insert_from_html(self, index, html_stream, use_slide_with_index_as_start):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | موقعیت درج. |
| html_stream | **io.RawIOBase** | یک شیء Stream که به عنوان منبع یک فایل HTML استفاده خواهد شد. |
| use_slide_with_index_as_start | **bool** | این پرچم تعیین می‌کند که درج از کجا آغاز شود: از یک اسلاید جدید یا از اسلایدی با ایندکس مشخص شده.<br/><br/>            اگر **true** باشد، درج داده‌ها از یک فضای خالی در اسلاید با ایندکس مشخص شده شروع می‌شود.<br/><br/>            اگر **false** باشد، داده‌ها به اسلایدهای ایجاد شده اضافه می‌شوند. |

## insert_from_html(self, index, html_text, resolver, uri) {#int-str-asposeslidesimportingiexternalresourceresolver-str}
اسلایدها را از متن HTML ایجاد می‌کند و آنها را در مجموعه در موقعیت مشخص شده درج می‌کند.

### مقدار بازگشتی
اسلایدهای اضافه شده.

```python
def insert_from_html(self, index, html_text, resolver, uri):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | موقعیت درج. |
| html_text | **str** | HTML برای افزودن. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/fa/aspose.slides.importing/iexternalresourceresolver) | یک شیء callback که برای دریافت اشیاء خارجی استفاده می‌شود. اگر این پارامتر None باشد، تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| uri | **str** | یک URI از HTML مشخص‌شده. برای حل پیوندهای نسبی استفاده می‌شود. |

## insert_from_html(self, index, html_stream, resolver, uri) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
اسلایدها را از متن HTML ایجاد می‌کند و آنها را در مجموعه در موقعیت مشخص شده درج می‌کند.

### مقدار بازگشتی
اسلایدهای اضافه شده.

```python
def insert_from_html(self, index, html_stream, resolver, uri):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | موقعیت درج. |
| html_stream | **io.RawIOBase** | یک شیء Stream که به عنوان منبع یک فایل HTML استفاده خواهد شد. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/fa/aspose.slides.importing/iexternalresourceresolver) | یک شیء callback که برای دریافت اشیاء خارجی استفاده می‌شود. اگر این پارامتر None باشد، تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| uri | **str** | یک URI از HTML مشخص‌شده. برای حل پیوندهای نسبی استفاده می‌شود. |

## insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start) {#int-str-asposeslidesimportingiexternalresourceresolver-str-bool}
اسلایدها را از متن HTML ایجاد می‌کند و آنها را در مجموعه در موقعیت مشخص شده درج می‌کند.

### مقدار بازگشتی
اسلایدهای اضافه شده.

```python
def insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | موقعیت درج. |
| html_text | **str** | HTML برای افزودن. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/fa/aspose.slides.importing/iexternalresourceresolver) | یک شیء callback که برای دریافت اشیاء خارجی استفاده می‌شود. اگر این پارامتر None باشد، تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| uri | **str** | یک URI از HTML مشخص‌شده. برای حل پیوندهای نسبی استفاده می‌شود. |
| use_slide_with_index_as_start | **bool** | این پرچم تعیین می‌کند که درج از کجا آغاز شود: از یک اسلاید جدید یا از اسلایدی با ایندکس مشخص شده.<br/><br/>            اگر **true** باشد، درج داده‌ها از یک فضای خالی در اسلاید با ایندکس مشخص شده شروع می‌شود.<br/><br/>            اگر **false** باشد، داده‌ها به اسلایدهای ایجاد شده اضافه می‌شوند. |

## insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool}
اسلایدها را از متن HTML ایجاد می‌کند و آنها را در مجموعه در موقعیت مشخص شده درج می‌کند.

### مقدار بازگشتی
اسلایدهای اضافه شده.

```python
def insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | موقعیت درج. |
| html_stream | **io.RawIOBase** | یک شیء Stream که به عنوان منبع یک فایل HTML استفاده خواهد شد. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/fa/aspose.slides.importing/iexternalresourceresolver) | یک شیء callback که برای دریافت اشیاء خارجی استفاده می‌شود. اگر این پارامتر None باشد، تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| uri | **str** | یک URI از HTML مشخص‌شده. برای حل پیوندهای نسبی استفاده می‌شود. |
| use_slide_with_index_as_start | **bool** | این پرچم تعیین می‌کند که درج از کجا آغاز شود: از یک اسلاید جدید یا از اسلایدی با ایندکس مشخص شده.<br/><br/>            اگر **true** باشد، درج داده‌ها از یک فضای خالی در اسلاید با ایندکس مشخص شده شروع می‌شود.<br/><br/>            اگر **false** باشد، داده‌ها به اسلایدهای ایجاد شده اضافه می‌شوند. |

### موارد مرتبط
* کلاس [`IExternalResourceResolver`](/slides/python-net/fa/aspose.slides.importing/iexternalresourceresolver)
* کلاس [`ISlideCollection`](/slides/python-net/fa/aspose.slides/islidecollection)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)