---
title: add method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/captionscollection/add/
weight: 10
---
## add(self, label, file_path) {#str-str}
زیرنویس‌های بستهٔ WebVTT را به انتهای مجموعه اضافه می‌کند.

### مقدار بازگشتی

نمونهٔ اضافه شده [`ICaptions`](/slides/python-net/fa/aspose.slides/icaptions).



```python
def add(self, label, file_path):
    ...
```


| پارامتر | نوع | توضیحات |
| :- | :- | :- |
| label | **str** | برچسب زیرنویس‌های بسته. |
| file_path | **str** | مسیر فایل WebVTT. |

### استثناها

| استثنا | توضیحات |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | در صورتی که `file_path` برابر با `None` باشد، پرتاب می‌شود. |
| **RuntimeError(Proxy error(ArgumentException))** | در صورتی که `file_path` خالی باشد، پرتاب می‌شود. |


## add(self, label, stream) {#str-iorawiobase}
زیرنویس‌های بستهٔ WebVTT را از جریان به انتهای مجموعه اضافه می‌کند.

### مقدار بازگشتی

نمونهٔ اضافه شده [`ICaptions`](/slides/python-net/fa/aspose.slides/icaptions).



```python
def add(self, label, stream):
    ...
```


| پارامتر | نوع | توضیحات |
| :- | :- | :- |
| label | **str** | برچسب زیرنویس‌های بسته. |
| stream | **io.RawIOBase** | جریان ورودی حاوی داده‌ها با فرمت WebVTT. |

### استثناها

| استثنا | توضیحات |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | در صورتی که `stream` برابر با `None` باشد، پرتاب می‌شود. |
| **RuntimeError(Proxy error(ArgumentException))** | در صورتی که داده ورودی در فرمت WebVTT نباشد، پرتاب می‌شود. |



### همچنین ببینید
* کلاس [`CaptionsCollection`](/slides/python-net/fa/aspose.slides/captionscollection)
* کلاس [`ICaptions`](/slides/python-net/fa/aspose.slides/icaptions)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)