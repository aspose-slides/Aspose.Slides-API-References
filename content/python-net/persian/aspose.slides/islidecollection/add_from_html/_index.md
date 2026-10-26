---
title: add_from_html method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/islidecollection/add_from_html/
weight: 30
---
## add_from_html(self, html_text) {#str}
اسلایدها را از متن HTML ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید.

### بازگشت

اسلایدهای اضافه شده



```python
def add_from_html(self, html_text):
    ...
```


| پارامتر | نوع | توضیحات |
| :- | :- | :- |
| html_text | **str** | HTML برای افزودن. |


## add_from_html(self, html_stream) {#iorawiobase}
اسلایدها را از متن HTML ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید.

### بازگشت

اسلایدهای اضافه شده



```python
def add_from_html(self, html_stream):
    ...
```


| پارامتر | نوع | توضیحات |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | یک شیء Stream که به عنوان منبع یک فایل HTML استفاده خواهد شد. |


## add_from_html(self, html_text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
اسلایدها را از متن HTML ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید.

### بازگشت

اسلایدهای اضافه شده.



```python
def add_from_html(self, html_text, resolver, uri):
    ...
```


| پارامتر | نوع | توضیحات |
| :- | :- | :- |
| html_text | **str** | HTML برای افزودن. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/fa/aspose.slides.importing/iexternalresourceresolver) | یک شیء callback که برای دریافت اشیاء خارجی استفاده می‌شود. اگر این پارامتر None باشد تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| uri | **str** | یک URI از HTML مشخص شده. برای حل لینک‌های نسبی استفاده می‌شود. |


## add_from_html(self, html_stream, resolver, uri) {#iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
اسلایدها را از متن HTML ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید.

### بازگشت

اسلایدهای اضافه شده.



```python
def add_from_html(self, html_stream, resolver, uri):
    ...
```


| پارامتر | نوع | توضیحات |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | یک شیء Stream که به عنوان منبع یک فایل HTML استفاده خواهد شد. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/fa/aspose.slides.importing/iexternalresourceresolver) | یک شیء callback که برای دریافت اشیاء خارجی استفاده می‌شود. اگر این پارامتر None باشد تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| uri | **str** | یک URI از HTML مشخص شده. برای حل لینک‌های نسبی استفاده می‌شود. |



### موارد مرتبط
* کلاس [`IExternalResourceResolver`](/slides/python-net/fa/aspose.slides.importing/iexternalresourceresolver)
* کلاس [`ISlideCollection`](/slides/python-net/fa/aspose.slides/islidecollection)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)