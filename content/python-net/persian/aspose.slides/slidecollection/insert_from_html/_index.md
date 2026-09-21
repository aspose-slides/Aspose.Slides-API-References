---
title: insert_from_html method
second_title: مرجع API Aspose.Slides برای پایتون از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/slidecollection/insert_from_html/
weight: 80
---
## insert_from_html(self, index, html_text) {#int-str}
این متد اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص شده به مجموعه اضافه می‌کند.

### بازگشت

اسلایدهای اضافه شده



```python
def insert_from_html(self, index, html_text):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | موقعیت برای درج. |
| html_text | **str** | HTML برای افزودن. |


## insert_from_html(self, index, html_stream) {#int-iorawiobase}
این متد اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص شده به مجموعه اضافه می‌کند.

### بازگشت

اسلایدهای اضافه شده



```python
def insert_from_html(self, index, html_stream):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | موقعیت برای درج. |
| html_stream | **io.RawIOBase** | یک شیء Stream که به عنوان منبع یک فایل HTML استفاده خواهد شد. |


## insert_from_html(self, index, html_text, use_slide_with_index_as_start) {#int-str-bool}
این متد اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص شده به مجموعه اضافه می‌کند.

### بازگشت

اسلایدهای اضافه شده



```python
def insert_from_html(self, index, html_text, use_slide_with_index_as_start):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | موقعیت برای درج. |
| html_text | **str** | HTML برای افزودن. |
| use_slide_with_index_as_start | **bool** | این پرچم تعیین می‌کند که درج از کجا شروع شود: از یک اسلاید جدید یا از اسلاید با اندیس مشخص شده.<br/><br/>اگر **true** باشد، درج داده‌ها از یک فضای خالی در اسلاید با اندیس مشخص شده آغاز می‌شود.<br/><br/>اگر **false** باشد، داده‌ها به اسلایدهای ایجاد شده اضافه می‌شوند. |


## insert_from_html(self, index, html_stream, use_slide_with_index_as_start) {#int-iorawiobase-bool}
این متد اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص شده به مجموعه اضافه می‌کند.

### بازگشت

اسلایدهای اضافه شده



```python
def insert_from_html(self, index, html_stream, use_slide_with_index_as_start):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | موقعیت برای درج. |
| html_stream | **io.RawIOBase** | یک شیء Stream که به عنوان منبع یک فایل HTML استفاده خواهد شد. |
| use_slide_with_index_as_start | **bool** | این پرچم تعیین می‌کند که درج از کجا شروع شود: از یک اسلاید جدید یا از اسلید با اندیس مشخص شده.<br/><br/>اگر **true** باشد، درج داده‌ها از یک فضای خالی در اسلاید با اندیس مشخص شده آغاز می‌شود.<br/><br/>اگر **false** باشد، داده‌ها به اسلایدهای ایجاد شده اضافه می‌شوند. |


## insert_from_html(self, index, html_text, resolver, uri) {#int-str-asposeslidesimportingiexternalresourceresolver-str}
این متد اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص شده به مجموعه اضافه می‌کند.

### بازگشت

اسلایدهای اضافه شده.



```python
def insert_from_html(self, index, html_text, resolver, uri):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | موقعیت برای درج. |
| html_text | **str** | HTML برای افزودن. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/fa/aspose.slides.importing/iexternalresourceresolver) | یک شیء callback برای دریافت اشیای خارجی. اگر این پارامتر None باشد تمام اشیای خارجی نادیده گرفته می‌شوند. |
| uri | **str** | یک URI از HTML مشخص شده. برای حل لینک‌های نسبی استفاده می‌شود. |


## insert_from_html(self, index, html_stream, resolver, uri) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
این متد اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص شده به مجموعه اضافه می‌کند.

### بازگشت

اسلایدهای اضافه شده.



```python
def insert_from_html(self, index, html_stream, resolver, uri):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | موقعیت برای درج. |
| html_stream | **io.RawIOBase** | یک شیء Stream که به عنوان منبع یک فایل HTML استفاده خواهد شد. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/fa/aspose.slides.importing/iexternalresourceresolver) | یک شیء callback برای دریافت اشیای خارجی. اگر این پارامتر None باشد تمام اشیای خارجی نادیده گرفته می‌شوند. |
| uri | **str** | یک URI از HTML مشخص شده. برای حل لینک‌های نسبی استفاده می‌شود. |


## insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start) {#int-str-asposeslidesimportingiexternalresourceresolver-str-bool}
این متد اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص شده به مجموعه اضافه می‌کند.

### بازگشت

اسلایدهای اضافه شده.



```python
def insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | موقعیت برای درج. |
| html_text | **str** | HTML برای افزودن. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/fa/aspose.slides.importing/iexternalresourceresolver) | یک شیء callback برای دریافت اشیای خارجی. اگر این پارامتر None باشد تمام اشیای خارجی نادیده گرفته می‌شوند. |
| uri | **str** | یک URI از HTML مشخص شده. برای حل لینک‌های نسبی استفاده می‌شود. |
| use_slide_with_index_as_start | **bool** | این پرچم تعیین می‌کند که درج از کجا شروع شود: از یک اسلاید جدید یا از اسلاید با اندیس مشخص شده.<br/><br/>اگر **true** باشد، درج داده‌ها از یک فضای خالی در اسلید با اندیس مشخص شده آغاز می‌شود.<br/><br/>اگر **false** باشد، داده‌ها به اسلایدهای ایجاد شده اضافه می‌شوند. |


## insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool}
این متد اسلایدها را از متن HTML ایجاد کرده و در موقعیت مشخص شده به مجموعه اضافه می‌کند.

### بازگشت

اسلایدهای اضافه شده.



```python
def insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | موقعیت برای درج. |
| html_stream | **io.RawIOBase** | یک شیء Stream که به عنوان منبع یک فایل HTML استفاده خواهد شد. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/fa/aspose.slides.importing/iexternalresourceresolver) | یک شیء callback برای دریافت اشیای خارجی. اگر این پارامتر None باشد تمام اشیای خارجی نادیده گرفته می‌شوند. |
| uri | **str** | یک URI از HTML مشخص شده. برای حل لینک‌های نسبی استفاده می‌شود. |
| use_slide_with_index_as_start | **bool** | این پرچم تعیین می‌کند که درج از کجا شروع شود: از یک اسلاید جدید یا از اسلاید با اندیس مشخص شده.<br/><br/>اگر **true** باشد، درج داده‌ها از یک فضای خالی در اسلید با اندیس مشخص شده آغاز می‌شود.<br/><br/>اگر **false** باشد، داده‌ها به اسلایدهای ایجاد شده اضافه می‌شوند. |



### موارد مرتبط
* کلاس [`IExternalResourceResolver`](/slides/python-net/fa/aspose.slides.importing/iexternalresourceresolver)
* کلاس [`SlideCollection`](/slides/python-net/fa/aspose.slides/slidecollection)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)