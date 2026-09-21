---
title: save method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/iimage/save/
weight: 10
---
## save(self, filename) {#str}
تصویر را در یک فایل ذخیره می‌کند.


```python
def save(self, filename):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| filename | **str** | مسیر فایلی که تصویر در آن ذخیره می‌شود. |


## save(self, filename, format) {#str-imageformat}
تصویر را در یک فایل با قالب مشخص ذخیره می‌کند.


```python
def save(self, filename, format):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| filename | **str** | مسیر فایلی که تصویر در آن ذخیره می‌شود. |
| format | [`ImageFormat`](/slides/python-net/fa/aspose.slides/imageformat) | قالب تصویر. |


## save(self, stream, format) {#iorawiobase-imageformat}
تصویر را در یک جریان با قالب مشخص ذخیره می‌کند.


```python
def save(self, stream, format):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| stream | **io.RawIOBase** | جریانی که تصویر در آن ذخیره می‌شود. |
| format | [`ImageFormat`](/slides/python-net/fa/aspose.slides/imageformat) | قالب تصویر. |


## save(self, filename, format, quality) {#str-imageformat-int}
تصویر را در یک فایل با قالب و کیفیت مشخص ذخیره می‌کند.


```python
def save(self, filename, format, quality):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| filename | **str** | مسیر فایلی که تصویر در آن ذخیره می‌شود. |
| format | [`ImageFormat`](/slides/python-net/fa/aspose.slides/imageformat) | قالب تصویر. |
| quality | **int** | کیفیت تصویر ذخیره‌شده (۰ تا ۱۰۰).  <br/><br/>            این پارامتر فقط در ذخیره‌سازی با [`ImageFormat.JPEG`](/slides/python-net/fa/aspose.slides/imageformat/JPEG) تأثیر دارد؛ برای سایر قالب‌ها، نادیده گرفته می‌شود. |


## save(self, stream, format, quality) {#iorawiobase-imageformat-int}
تصویر را در یک جریان با قالب و کیفیت مشخص ذخیره می‌کند.


```python
def save(self, stream, format, quality):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| stream | **io.RawIOBase** | جریانی که تصویر در آن ذخیره می‌شود. |
| format | [`ImageFormat`](/slides/python-net/fa/aspose.slides/imageformat) | قالب تصویر. |
| quality | **int** | کیفیت تصویر ذخیره‌شده (۰ تا ۱۰۰).  <br/><br/>            این پارامتر فقط در ذخیره‌سازی با [`ImageFormat.JPEG`](/slides/python-net/fa/aspose.slides/imageformat/JPEG) تأثیر دارد؛ برای سایر قالب‌ها، نادیده گرفته می‌شود. |



### مراجع
* کلاس [`IImage`](/slides/python-net/fa/aspose.slides/iimage)
* enumeration [`ImageFormat`](/slides/python-net/fa/aspose.slides/imageformat)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)