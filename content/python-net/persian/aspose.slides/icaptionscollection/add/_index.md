---
title: add method
second_title: Aspose.Slides برای پایتون از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/icaptionscollection/add/
weight: 10
---
## add(self, label, file_path) {#str-str}
کپشن‌های بسته‌شده WebVQT را به انتهای مجموعه اضافه می‌کند.

### بازگشت

نمونه [`ICaptions`](/slides/python-net/fa/aspose.slides/icaptions) افزوده شده.



```python
def add(self, label, file_path):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| label | **str** | برچسب کپشن‌های بسته‌شده. |
| file_path | **str** | مسیر فایل WebVTT. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | در صورتی که `file_path` برابر `None` باشد، پرتاب می‌شود. |
| **RuntimeError(Proxy error(ArgumentException))** | در صورتی که `file_path` خالی باشد، پرتاب می‌شود. |


## add(self, label, stream) {#str-iorawiobase}
کپشن‌های بسته‌شده WebVQT را از یک جریان به انتهای مجموعه اضافه می‌کند.

### بازگشت

نمونه [`ICaptions`](/slides/python-net/fa/aspose.slides/icaptions) افزوده شده.



```python
def add(self, label, stream):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| label | **str** | برچسب کپشن‌های بسته‌شده. |
| stream | **io.RawIOBase** | جریان ورودی حاوی داده‌ها با فرمت WebVTT. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | در صورتی که `stream` برابر `None` باشد، پرتاب می‌شود. |
| **RuntimeError(Proxy error(ArgumentException))** | در صورتی که داده‌های ورودی در فرمت WebVTT نباشند، پرتاب می‌شود. |



### موارد مرتبط
* کلاس [`ICaptions`](/slides/python-net/fa/aspose.slides/icaptions)
* کلاس [`ICaptionsCollection`](/slides/python-net/fa/aspose.slides/icaptionscollection)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)