---
title: add_image method
second_title: Aspose.Slides للـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/imagecollection/add_image/
weight: 10
---
## add_image(self, image_source) {#ippimage}
يضيف نسخة من صورة من عرض تقديمي آخر.

### القيمة المرجعة

الصورة المضافة.



```python
def add_image(self, image_source):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| image_source | [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage) | صورة المصدر. |


## add_image(self, image) {#iimage}
يضيف صورة إلى عرض تقديمي.

### القيمة المرجعة

الصورة المضافة.



```python
def add_image(self, image):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| image | [`IImage`](/slides/python-net/ar/aspose.slides/iimage) | الصورة المراد إضافتها. |

### ملاحظات

تحول هذه الطريقة ملفات WMF/EMF الميتا إلى صورة PNG نقطية قبل إدراجها في عرض تقديمي.


## add_image(self, stream) {#iorawiobase}
يضيف صورة إلى عرض تقديمي من دفق.

### القيمة المرجعة

الصورة المضافة.



```python
def add_image(self, stream):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| stream | **io.RawIOBase** | الدفق لإضافة الصورة منه. |

### ملاحظات

يمكن لهذه الطريقة إضافة ملفات WMF/EMF الميتا إلى عرض تقديمي دون تحويلها إلى صورة PNG نقطية.


## add_image(self, buffer) {#bytes}
يضيف صورة إلى عرض تقديمي من المخزن المؤقت المحدد.

### القيمة المرجعة

الصورة المضافة.



```python
def add_image(self, buffer):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| buffer | **bytes** | المخزن المؤقت. |


## add_image(self, svg_image) {#isvgimage}
يضيف صورة إلى عرض تقديمي من كائن Svg.

### القيمة المرجعة

الصورة المضافة.



```python
def add_image(self, svg_image):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/ar/aspose.slides/isvgimage) | كائن صورة Svg [`ISvgImage`](/slides/python-net/ar/aspose.slides/isvgimage) |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | عندما يكون معامل svgImage فارغًا. |


## add_image(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
ينشئ ويضيف صورة إلى عرض تقديمي من دفق.

### القيمة المرجعة

تمت إضافة [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage).



```python
def add_image(self, stream, loading_stream_behavior):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| stream | **io.RawIOBase** | الدفق لإضافة ملف الصورة منه. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/ar/aspose.slides/loadingstreambehavior) | السلوك الذي سيُطبق على الدفق. |



### انظر أيضًا
* الصنف [`IImage`](/slides/python-net/ar/aspose.slides/iimage)
* الصنف [`ImageCollection`](/slides/python-net/ar/aspose.slides/imagecollection)
* الصنف [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage)
* الصنف [`ISvgImage`](/slides/python-net/ar/aspose.slides/isvgimage)
* التعداد [`LoadingStreamBehavior`](/slides/python-net/ar/aspose.slides/loadingstreambehavior)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)