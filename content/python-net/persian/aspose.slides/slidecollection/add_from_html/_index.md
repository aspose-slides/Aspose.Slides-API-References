---
title: add_from_html method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/slidecollection/add_from_html/
weight: 30
---
## add_from_html(self, html_text) {#str}
اسلایدها را از متن HTML ایجاد می‌کند و به انتهای مجموعه اضافه می‌دهد.

### بازگشت

اسلایدهای اضافه شده



```python
def add_from_html(self, html_text):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| html_text | **str** | HTML برای اضافه کردن. |


## add_from_html(self, html_stream) {#iorawiobase}
اسلایدها را از متن HTML ایجاد می‌کند و به انتهای مجموعه اضافه می‌دهد.

### بازگشت

اسلایدهای اضافه شده



```python
def add_from_html(self, html_stream):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | یک شیء Stream که به عنوان منبع یک فایل HTML استفاده خواهد شد. |


## add_from_html(self, html_text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
اسلایدها را از متن HTML ایجاد می‌کند و به انتهای مجموعه اضافه می‌دهد.

### بازگشت

اسلایدهای اضافه شده.



```python
def add_from_html(self, html_text, resolver, uri):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| html_text | **str** | HTML برای اضافه کردن. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/fa/aspose.slides.importing/iexternalresourceresolver) | یک شیء callback که برای دریافت اشیای خارجی استفاده می‌شود. اگر این پارامتر None باشد تمام اشیای خارجی نادیده گرفته می‌شوند. |
| uri | **str** | یک URI از HTML مشخص شده. برای حل پیوندهای نسبی استفاده می‌شود. |


## add_from_html(self, html_stream, resolver, uri) {#iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
اسلایدها را از متن HTML ایجاد می‌کند و به انتهای مجموعه اضافه می‌دهد.

### بازگشت

اسلایدهای اضافه شده.



```python
def add_from_html(self, html_stream, resolver, uri):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | یک شیء Stream که به عنوان منبع یک فایل HTML استفاده خواهد شد. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/fa/aspose.slides.importing/iexternalresourceresolver) | یک شیء callback که برای دریافت اشیای خارجی استفاده می‌شود. اگر این پارامتر None باشد تمام اشیای خارجی نادیده گرفته می‌شوند. |
| uri | **str** | یک URI از HTML مشخص شده. برای حل پیوندهای نسبی استفاده می‌شود. |



### موارد مرتبط
* کلاس [`IExternalResourceResolver`](/slides/python-net/fa/aspose.slides.importing/iexternalresourceresolver)
* کلاس [`SlideCollection`](/slides/python-net/fa/aspose.slides/slidecollection)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)