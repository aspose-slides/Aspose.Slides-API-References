---
title: save method
second_title: مرجع API Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/iimage/save/
weight: 10
---
## save(self, filename) {#str}
يحفظ الصورة إلى ملف.


```python
def save(self, filename):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| filename | **str** | المسار إلى الملف حيث سيتم حفظ الصورة. |


## save(self, filename, format) {#str-imageformat}
يحفظ الصورة إلى ملف بالتنسيق المحدد.


```python
def save(self, filename, format):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| filename | **str** | المسار إلى الملف حيث سيتم حفظ الصورة. |
| format | [`ImageFormat`](/slides/python-net/ar/aspose.slides/imageformat) | تنسيق الصورة. |


## save(self, stream, format) {#iorawiobase-imageformat}
يحفظ الصورة إلى تدفق بالتنسيق المحدد.


```python
def save(self, stream, format):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| stream | **io.RawIOBase** | التدفق حيث سيتم حفظ الصورة. |
| format | [`ImageFormat`](/slides/python-net/ar/aspose.slides/imageformat) | تنسيق الصورة. |


## save(self, filename, format, quality) {#str-imageformat-int}
يحفظ الصورة إلى ملف بالتنسيق المحدد والجودة.


```python
def save(self, filename, format, quality):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| filename | **str** | المسار إلى الملف حيث سيتم حفظ الصورة. |
| format | [`ImageFormat`](/slides/python-net/ar/aspose.slides/imageformat) | تنسيق الصورة. |
| quality | **int** | جودة الصورة المحفوظة (0 إلى 100).  <br/><br/>            هذا المعامل يؤثر فقط على الحفظ في [`ImageFormat.JPEG`](/slides/python-net/ar/aspose.slides/imageformat/JPEG)؛ بالنسبة لجميع التنسيقات الأخرى، يتم تجاهله. |


## save(self, stream, format, quality) {#iorawiobase-imageformat-int}
يحفظ الصورة إلى تدفق بالتنسيق المحدد والجودة.


```python
def save(self, stream, format, quality):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| stream | **io.RawIOBase** | التدفق حيث سيتم حفظ الصورة. |
| format | [`ImageFormat`](/slides/python-net/ar/aspose.slides/imageformat) | تنسيق الصورة. |
| quality | **int** | جودة الصورة المحفوظة (0 إلى 100).  <br/><br/>            هذا المعامل يؤثر فقط على الحفظ في [`ImageFormat.JPEG`](/slides/python-net/ar/aspose.slides/imageformat/JPEG)؛ بالنسبة لجميع التنسيقات الأخرى، يتم تجاهله. |



### انظر أيضاً
* الفئة [`IImage`](/slides/python-net/ar/aspose.slides/iimage)
* التعداد [`ImageFormat`](/slides/python-net/ar/aspose.slides/imageformat)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)