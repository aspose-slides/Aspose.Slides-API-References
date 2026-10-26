---
title: add_image method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/imagecollection/add_image/
weight: 10
---
## add_image(self, image_source) {#ippimage}
یک نسخه از تصویر را از ارائه‌ای دیگر اضافه می‌کند.

### Returns
بازگشت

تصویر اضافه‌شده.



```python
def add_image(self, image_source):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| image_source | [`IPPImage`](/slides/python-net/fa/aspose.slides/ippimage) | تصویر منبع. |


## add_image(self, image) {#iimage}
یک تصویر را به یک ارائه اضافه می‌کند.

### Returns
بازگشت

تصویر اضافه‌شده.



```python
def add_image(self, image):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| image | [`IImage`](/slides/python-net/fa/aspose.slides/iimage) | تصویر برای افزودن. |

### Remarks
این متد فایل‌های متافایل WMF/EMF را قبل از درج به ارائه به تصویر PNG رستر تبدیل می‌کند.


## add_image(self, stream) {#iorawiobase}
یک تصویر را از stream به ارائه اضافه می‌کند.

### Returns
بازگشت

تصویر اضافه‌شده.



```python
def add_image(self, stream):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| stream | **io.RawIOBase** | جریان برای افزودن تصویر. |

### Remarks
این متد می‌تواند فایل‌های متافایل WMF/EMF را بدون تبدیل به تصویر PNG رستر به ارائه اضافه کند.


## add_image(self, buffer) {#bytes}
یک تصویر را از buffer مشخص شده به ارائه اضافه می‌کند.

### Returns
بازگشت

تصویر اضافه‌شده.



```python
def add_image(self, buffer):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| buffer | **bytes** | بافر. |


## add_image(self, svg_image) {#isvgimage}
یک تصویر را از شیء Svg به ارائه اضافه می‌کند.

### Returns
بازگشت

تصویر اضافه‌شده.



```python
def add_image(self, svg_image):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/fa/aspose.slides/isvgimage) | شیء تصویر Svg [`ISvgImage`](/slides/python-net/fa/aspose.slides/isvgimage) |

### Exceptions

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | زمانی که پارامتر svgImage برابر None باشد. |


## add_image(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
یک تصویر را از stream ایجاد و به ارائه اضافه می‌کند.

### Returns
بازگشت

Added [`IPPImage`](/slides/python-net/fa/aspose.slides/ippimage).



```python
def add_image(self, stream, loading_stream_behavior):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| stream | **io.RawIOBase** | جریان برای افزودن فایل تصویر. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/fa/aspose.slides/loadingstreambehavior) | رفتار که بر روی جریان اعمال خواهد شد. |



### See Also
* کلاس [`IImage`](/slides/python-net/fa/aspose.slides/iimage)
* کلاس [`ImageCollection`](/slides/python-net/fa/aspose.slides/imagecollection)
* کلاس [`IPPImage`](/slides/python-net/fa/aspose.slides/ippimage)
* کلاس [`ISvgImage`](/slides/python-net/fa/aspose.slides/isvgimage)
* شمارش [`LoadingStreamBehavior`](/slides/python-net/fa/aspose.slides/loadingstreambehavior)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)