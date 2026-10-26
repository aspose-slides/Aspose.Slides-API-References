---
title: get_image method
second_title: مرجع API لـ Aspose.Slides للغة Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides/slide/get_image/
weight: 40
---
## get_image(self) {#}
يرجع كائن Thumbnail Image (20% من الحجم الأصلي).


```python
def get_image(self):
    ...
```



## get_image(self, image_size) {#asposeslidessize}
يرجع كائن Thumbnail Image بالحجم المحدد.

### Returns
كائن Image.



```python
def get_image(self, image_size):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| image_size | [`Size`](/slides/python-net/ar/aspose.slides/size) | حجم الصورة المراد إنشاؤها. |


## get_image(self, options) {#asposeslidesexportitiffoptions}
يرجع كائن Thumbnail tiff image بالمعلمات المحددة.

### Returns
كائن Image.



```python
def get_image(self, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/ar/aspose.slides.export/itiffoptions) | خيارات Tiff. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | يُطرح عندما يكون options.SlideLayoutOption هو NotesCommentsLayoutingOptions وتكون خاصية NotesPosition لها القيمة NotesPositions.BottomFull. |


## get_image(self, options) {#asposeslidesexportirenderingoptions}
يرجع كائن Thumbnail Image.

### Returns
كائن Image.



```python
def get_image(self, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ar/aspose.slides.export/irenderingoptions) | خيارات العرض. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | يُطرح عندما تكون notesCommentsLayouting.NotesPosition لها القيمة NotesPositions.BottomFull. |


## get_image(self, scale_x, scale_y) {#float-float}
يرجع كائن Thumbnail Image مع تحجيم مخصص.

### Returns
كائن IImage.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| scale_x | **float** | القيمة التي يتم من خلالها تحجيم هذا Thumbnail في اتجاه محور x. |
| scale_y | **float** | القيمة التي يتم من خلالها تحجيم هذا Thumbnail في اتجاه محور y. |


## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
يرجع كائن Thumbnail Image بالحجم المحدد.

### Returns
كائن Image.



```python
def get_image(self, options, image_size):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ar/aspose.slides.export/irenderingoptions) | خيارات العرض. |
| image_size | [`Size`](/slides/python-net/ar/aspose.slides/size) | حجم الصورة المراد إنشاؤها. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | يُطرح عندما يكون options.SlideLayoutOption هو NotesCommentsLayoutingOptions وتكون خاصية NotesPosition لها القيمة NotesPositions.BottomFull. |


## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
يرجع كائن Thumbnail Image مع تحجيم مخصص.

### Returns
كائنات Bitmap.



```python
def get_image(self, options, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ar/aspose.slides.export/irenderingoptions) | خيارات العرض. |
| scale_x | **float** | القيمة التي يتم من خلالها تحجيم هذا Thumbnail في اتجاه محور x. |
| scale_y | **float** | القيمة التي يتم من خلالها تحجيم هذا Thumbnail في اتجاه محور y. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | يُطرح عندما تكون notesCommentsLayouting.NotesPosition لها القيمة NotesPositions.BottomFull. |



### See Also
* class [`IImage`](/slides/python-net/ar/aspose.slides/iimage)
* class [`IRenderingOptions`](/slides/python-net/ar/aspose.slides.export/irenderingoptions)
* class [`ITiffOptions`](/slides/python-net/ar/aspose.slides.export/itiffoptions)
* class [`Slide`](/slides/python-net/ar/aspose.slides/slide)
* class [`Size`](/slides/python-net/ar/aspose.slides/size)
* module [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)