---
title: get_images method
second_title: Aspose.Slides لـ Python عبر .NET API Reference
description: 
type: docs
url: /ar/aspose.slides/ipresentation/get_images/
weight: 10
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
يرجع كائنات صورة مصغرة لجميع شرائح العرض التقديمي.

### القيمة المرجعة

كائنات Bitmap.



```python
def get_images(self, options):
    ...
```


| المُعامل | النوع | الوصف |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ar/aspose.slides.export/irenderingoptions) | خيارات التصيير. |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
يرجع كائنات Bitmap مصغرة للشرائح المحددة في العرض التقديمي.

### القيمة المرجعة

كائنات Bitmap.



```python
def get_images(self, options, slides):
    ...
```


| المُعامل | النوع | الوصف |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ar/aspose.slides.export/irenderingoptions) | خيارات التصيير. |
| slides | **List[int]** | مصفوفة بمواقع الشرائح، بدءًا من 1. |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
يرجع كائنات صورة مصغرة لجميع شرائح العرض التقديمي بالحجم المحدد.

### القيمة المرجعة

كائنات Bitmap.



```python
def get_images(self, options, image_size):
    ...
```


| المُعامل | النوع | الوصف |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ar/aspose.slides.export/irenderingoptions) | خيارات التصيير. |
| image_size | **aspose.slides.Size** | حجم الصورة المراد إنشاؤها. |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
يرجع كائنات صورة مصغرة لجميع شرائح العرض التقديمي مع مقياس مخصص.

### القيمة المرجعة

كائنات Bitmap.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| المُعامل | النوع | الوصف |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ar/aspose.slides.export/irenderingoptions) | خيارات التصيير. |
| scale_x | **float** | القيمة التي يتم بمقابلتها تحجيم هذه الصورة المصغرة في اتجاه المحور السيني. |
| scale_y | **float** | القيمة التي يتم بمقابلتها تحجيم هذه الصورة المصغرة في اتجاه المحور الصادي. |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposepydrawingsize}
يرجع كائنات صورة مصغرة للشرائح المحددة في العرض التقديمي بالحجم المحدد.

### القيمة المرجعة

كائنات Bitmap.



```python
def get_images(self, options, slides, image_size):
    ...
```


| المُعامل | النوع | الوصف |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ar/aspose.slides.export/irenderingoptions) | خيارات التصيير. |
| slides | **List[int]** | مصفوفة بمواقع الشرائح، بدءًا من 1. |
| image_size | **aspose.slides.Size** | حجم الصورة المراد إنشاؤها. |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
يرجع كائنات صورة مصغرة للشرائح المحددة في العرض التقديمي مع مقياس مخصص.

### القيمة المرجعة

كائنات Bitmap.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| المُعامل | النوع | الوصف |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ar/aspose.slides.export/irenderingoptions) | خيارات التصيير. |
| slides | **List[int]** | مصفوفة بمواقع الشرائح، بدءًا من 1. |
| scale_x | **float** | القيمة التي يتم بمقابلتها تحجيم هذه الصورة المصغرة في اتجاه المحور السيني. |
| scale_y | **float** | القيمة التي يتم بمقابلتها تحجيم هذه الصورة المصغرة في اتجاه المحور الصادي. |



### أنظر أيضًا
* الفئة [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation)
* الفئة [`IRenderingOptions`](/slides/python-net/ar/aspose.slides.export/irenderingoptions)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)