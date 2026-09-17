---
title: get_image method
second_title: مرجع API Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/slide/get_image/
weight: 40
---
## get_image(self) {#}
يرجع كائن Thumbnail Image (20٪ من الحجم الفعلي).

```python
def get_image(self):
    ...
```

## get_image(self, image_size) {#asposepydrawingsize}
يرجع كائن Thumbnail Image بالحجم المحدد.

### القيمة المرجعة

كائن Image.

```python
def get_image(self, image_size):
    ...
```

| معامل | النوع | الوصف |
| :- | :- | :- |
| image_size | **aspose.slides.Size** | حجم الـ image لإنشائه. |

## get_image(self, options) {#asposeslidesexportitiffoptions}
يرجع كائن Thumbnail tiff image بالمعلمات المحددة.

### القيمة المرجعة

كائن Image.

```python
def get_image(self, options):
    ...
```

| معامل | النوع | الوصف |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/ar/aspose.slides.export/itiffoptions) | خيارات Tiff. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | يتم إطلاق الاستثناء عندما يكون options.SlideLayoutOption هو NotesCommentsLayoutingOptions وتكون الخاصية NotesPosition لها القيمة NotesPositions.BottomFull. |

## get_image(self, options) {#asposeslidesexportirenderingoptions}
يرجع كائن Thumbnail Image.

### القيمة المرجعة

كائن Image.

```python
def get_image(self, options):
    ...
```

| معامل | النوع | الوصف |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ar/aspose.slides.export/irenderingoptions) | خيارات Rendering. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | يتم إطلاق الاستثناء عندما تكون notesCommentsLayouting.NotesPosition لها القيمة NotesPositions.BottomFull. |

## get_image(self, scale_x, scale_y) {#float-float}
يرجع كائن Thumbnail Image بتدرج مخصص.

### القيمة المرجعة

كائن IImage.

```python
def get_image(self, scale_x, scale_y):
    ...
```

| معامل | النوع | الوصف |
| :- | :- | :- |
| scale_x | **float** | القيمة التي يتم تعديل حجم هذا Thumbnail بها في اتجاه المحور x. |
| scale_y | **float** | القيمة التي يتم تعديل حجم هذا Thumbnail بها في اتجاه المحور y. |

## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
يرجع كائن Thumbnail Image بالحجم المحدد.

### القيمة المرجعة

كائن Image.

```python
def get_image(self, options, image_size):
    ...
```

| معامل | النوع | الوصف |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ar/aspose.slides.export/irenderingoptions) | خيارات Rendering. |
| image_size | **aspose.slides.Size** | حجم الـ image لإنشائه. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | يتم إطلاق الاستثناء عندما يكون options.SlideLayoutOption هو NotesCommentsLayoutingOptions وتكون الخاصية NotesPosition لها القيمة NotesPositions.BottomFull. |

## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
يرجع كائن Thumbnail Image بتدرج مخصص.

### القيمة المرجعة

كائنات Bitmap.

```python
def get_image(self, options, scale_x, scale_y):
    ...
```

| معامل | النوع | الوصف |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ar/aspose.slides.export/irenderingoptions) | خيارات Rendering. |
| scale_x | **float** | القيمة التي يتم تعديل حجم هذا Thumbnail بها في اتجاه المحور x. |
| scale_y | **float** | القيمة التي يتم تعديل حجم هذا Thumbnail بها في اتجاه المحور y. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | يتم إطلاق الاستثناء عندما تكون notesCommentsLayouting.NotesPosition لها القيمة NotesPositions.BottomFull. |

### انظر أيضًا
* فئة [`IImage`](/slides/python-net/ar/aspose.slides/iimage)
* فئة [`IRenderingOptions`](/slides/python-net/ar/aspose.slides.export/irenderingoptions)
* فئة [`ITiffOptions`](/slides/python-net/ar/aspose.slides.export/itiffoptions)
* فئة [`Slide`](/slides/python-net/ar/aspose.slides/slide)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)