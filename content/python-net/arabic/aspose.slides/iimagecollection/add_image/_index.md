---
title: add_image method
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/iimagecollection/add_image/
weight: 10
---
## add_image(self, image) {#iimage}
إضافة صورة إلى عرض تقديمي.

### Returns
الصورة المضافة.



```python
def add_image(self, image):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| image | [`IImage`](/slides/python-net/ar/aspose.slides/iimage) | الصورة المراد إضافتها. |

### Remarks
يقوم هذا الأسلوب بتحويل ملفات الميتا WMF/EMF إلى صورة PNG نقطية قبل إدراجها في العرض التقديمي.


## add_image(self, stream) {#iorawiobase}
إضافة صورة إلى عرض تقديمي من流.

### Returns
الصورة المضافة.



```python
def add_image(self, stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | التدفق الذي تُضاف الصورة منه. |

### Remarks
يمكن لهذا الأسلوب إضافة ملفات الميتا WMF/EMF إلى عرض تقديمي دون تحويلها إلى صورة PNG نقطية.


## add_image(self, buffer) {#bytes}
إضافة صورة إلى عرض تقديمي من المخزن المؤقت المحدد.

### Returns
الصورة المضافة.



```python
def add_image(self, buffer):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| buffer | **bytes** | المخزن المؤقت. |


## add_image(self, image_source) {#ippimage}
إضافة نسخة من صورة موجودة في عرض تقديمي آخر.

### Returns
الصورة المضافة.



```python
def add_image(self, image_source):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| image_source | [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage) | صورة المصدر. |


## add_image(self, svg_image) {#isvgimage}
إضافة صورة إلى عرض تقديمي من كائن SVG.

### Returns
الصورة المضافة.



```python
def add_image(self, svg_image):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/ar/aspose.slides/isvgimage) | كائن صورة SVG [`ISvgImage`](/slides/python-net/ar/aspose.slides/isvgimage) |

### Exceptions
| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | يُثار عندما يكون معامل svgImage يساوي None. |


## add_image(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
إنشاء وإضافة صورة إلى عرض تقديمي من تدفق.

### Returns
تم إضافة [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage).



```python
def add_image(self, stream, loading_stream_behavior):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | التدفق الذي تُضاف منه ملف الصورة. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/ar/aspose.slides/loadingstreambehavior) | السلوك الذي سيطبق على التدفق. |



### See Also
* class [`IImage`](/slides/python-net/ar/aspose.slides/iimage)
* class [`IImageCollection`](/slides/python-net/ar/aspose.slides/iimagecollection)
* class [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage)
* class [`ISvgImage`](/slides/python-net/ar/aspose.slides/isvgimage)
* enumeration [`LoadingStreamBehavior`](/slides/python-net/ar/aspose.slides/loadingstreambehavior)
* module [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)