---
title: get_images method
second_title: مرجع API Aspose.Slides لـ Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides/presentation/get_images/
weight: 20
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
إرجاع كائنات Image لجميع شرائح العرض التقديمي.

### الإرجاع
كائنات Image.

```python
def get_images(self, options):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ar/aspose.slides.export/irenderingoptions) | خيارات Tiff. |

## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
إرجاع كائنات Image المصغرة للشرائح المحددة في العرض التقديمي.

### الإرجاع
كائنات Image.

```python
def get_images(self, options, slides):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ar/aspose.slides.export/irenderingoptions) | خيارات Tiff. |
| slides | **List[int]** | مصفوفة بمواقع الشرائح، تبدأ من 1. |

## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
إرجاع كائنات Image المصغرة لجميع شرائح العرض التقديمي بالحجم المحدد.

### الإرجاع
كائنات Image.

```python
def get_images(self, options, image_size):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ar/aspose.slides.export/irenderingoptions) | خيارات Tiff. |
| image_size | [`Size`](/slides/python-net/ar/aspose.slides/size) | حجم الصورة التي سيتم إنشاؤها. |

## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
إرجاع كائنات Image المصغرة لجميع شرائح العرض التقديمي بمقاس مخصص.

### الإرجاع
كائنات Image.

```python
def get_images(self, options, scale_x, scale_y):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ar/aspose.slides.export/irenderingoptions) | خيارات Tiff. |
| scale_x | **float** | القيمة التي يتم بها تكبير هذا Thumbnail في اتجاه المحور x. |
| scale_y | **float** | القيمة التي يتم بها تكبير هذا Thumbnail في اتجاه المحور y. |

## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposeslidessize}
إرجاع كائنات Image المصغرة للشرائح المحددة في العرض التقديمي بالحجم المحدد.

### الإرجاع
كائنات Image.

```python
def get_images(self, options, slides, image_size):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ar/aspose.slides.export/irenderingoptions) | خيارات Tiff. |
| slides | **List[int]** | مصفوفة بمواقع الشرائح، تبدأ من 1. |
| image_size | [`Size`](/slides/python-net/ar/aspose.slides/size) | حجم الصورة التي سيتم إنشاؤها. |

## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
إرجاع كائنات Image المصغرة للشرائح المحددة في العرض التقديمي بمقاس مخصص.

### الإرجاع
كائنات Image.

```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ar/aspose.slides.export/irenderingoptions) | خيارات Tiff. |
| slides | **List[int]** | مصفوفة بمواقع الشرائح، تبدأ من 1. |
| scale_x | **float** | القيمة التي يتم بها تكبير هذا Thumbnail في اتجاه المحور x. |
| scale_y | **float** | القيمة التي يتم بها تكبير هذا Thumbnail في اتجاه المحور y. |

### انظر أيضًا
* الفئة [`IRenderingOptions`](/slides/python-net/ar/aspose.slides.export/irenderingoptions)
* الفئة [`Presentation`](/slides/python-net/ar/aspose.slides/presentation)
* الفئة [`Size`](/slides/python-net/ar/aspose.slides/size)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)