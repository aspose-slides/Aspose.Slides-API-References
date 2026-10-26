---
title: add_image method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/iimagecollection/add_image/
weight: 10
---
## add_image(self, image) {#iimage}
یک تصویر را به ارائه اضافه می‌کند.

### Returns
تصویر اضافه شد.

```python
def add_image(self, image):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| image | [`IImage`](/slides/python-net/fa/aspose.slides/iimage) | تصویر برای اضافه شدن. |

### Remarks
این متد فایل‌های متا WMF/EMF را قبل از درج به یک تصویر PNG نقطه‌پیکسل تبدیل می‌کند.

## add_image(self, stream) {#iorawiobase}
تصویری را از جریان به ارائه اضافه می‌کند.

### Returns
تصویر اضافه شد.

```python
def add_image(self, stream):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| stream | **io.RawIOBase** | جریانی که تصویر از آن اضافه می‌شود. |

### Remarks
این متد می‌تواند فایل‌های متا WMF/EMF را بدون تبدیل به تصویر PNG نقطه‌پیکسل به ارائه اضافه کند.

## add_image(self, buffer) {#bytes}
تصویری را از بافر مشخص به ارائه اضافه می‌کند.

### Returns
تصویر اضافه شد.

```python
def add_image(self, buffer):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| buffer | **bytes** | بافر. |

## add_image(self, image_source) {#ippimage}
یک کپی از تصویر را از ارائه دیگر اضافه می‌کند.

### Returns
تصویر اضافه شد.

```python
def add_image(self, image_source):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| image_source | [`IPPImage`](/slides/python-net/fa/aspose.slides/ippimage) | تصویر منبع. |

## add_image(self, svg_image) {#isvgimage}
تصویری را از شیء SVG به ارائه اضافه می‌کند.

### Returns
تصویر اضافه شد.

```python
def add_image(self, svg_image):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/fa/aspose.slides/isvgimage) | شیء تصویر SVG [`ISvgImage`](/slides/python-net/fa/aspose.slides/isvgimage) |

### Exceptions

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | هنگامی که پارامتر svgImage مقدار None دارد، پرتاب می‌شود. |

## add_image(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
یک تصویر ایجاد کرده و از جریان به ارائه اضافه می‌کند.

### Returns
[`IPPImage`](/slides/python-net/fa/aspose.slides/ippimage) اضافه شد.

```python
def add_image(self, stream, loading_stream_behavior):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| stream | **io.RawIOBase** | جریانی که فایل تصویر از آن اضافه می‌شود. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/fa/aspose.slides/loadingstreambehavior) | رفتاری که بر روی جریان اعمال خواهد شد. |

### See Also
* class [`IImage`](/slides/python-net/fa/aspose.slides/iimage)
* class [`IImageCollection`](/slides/python-net/fa/aspose.slides/iimagecollection)
* class [`IPPImage`](/slides/python-net/fa/aspose.slides/ippimage)
* class [`ISvgImage`](/slides/python-net/fa/aspose.slides/isvgimage)
* enumeration [`LoadingStreamBehavior`](/slides/python-net/fa/aspose.slides/loadingstreambehavior)
* module [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)