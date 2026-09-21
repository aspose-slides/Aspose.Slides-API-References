---
title: Hyperlink constructor
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/hyperlink/__init__/
weight: 10
---
## __init__(self, url) {#str}
یک نمونه از پیوند فرا‌نوردی ایجاد می‌کند.


```python
def __init__(self, url):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| url | **str** | آدرس URL پیوند فرا‌نوردی. |


## __init__(self, slide) {#islide}
یک نمونه از پیوند فرا‌نوردی که به اسلاید خاصی اشاره می‌کند ایجاد می‌کند.
توجه: پیوند فرا‌نوردی ایجاد شده باید به یک شیء از همان ارائه اختصاص داده شود، در غیر این صورت پیوند به عنوان NoAction ذخیره خواهد شد.


```python
def __init__(self, slide):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| slide | [`ISlide`](/slides/python-net/fa/aspose.slides/islide) | اسلاید هدف. |


## __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click) {#hyperlink-str-str-bool-bool-bool}
یک نمونه از پیوند فرا‌نوردی با استفاده از پیوند فرا‌نوردی دیگر به عنوان منبع ایجاد می‌کند و ویژگی‌های ثانویه را بازنویسی می‌کند.


```python
def __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| source | [`Hyperlink`](/slides/python-net/fa/aspose.slides/hyperlink) | پیوند فرا‌نوردی منبع |
| target_frame | **str** | فریم هدف |
| tooltip | **str** | متن نکتهٔ راهنما |
| history | **bool** |  |
| stop_sounds_on_click | **bool** |  |
| highlight_click | **bool** |  |


### موارد مرتبط
* کلاس [`Hyperlink`](/slides/python-net/fa/aspose.slides/hyperlink)
* کلاس [`ISlide`](/slides/python-net/fa/aspose.slides/islide)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)