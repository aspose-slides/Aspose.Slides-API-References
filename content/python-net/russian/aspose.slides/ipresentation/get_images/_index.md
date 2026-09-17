---
title: get_images method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/ipresentation/get_images/
weight: 10
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
Возвращает объекты Thumbnail Image для всех слайдов презентации.

### Возвращаемое значение

Bitmap objects.



```python
def get_images(self, options):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions) | Rendering options. |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
Возвращает объекты Thumbnail Bitmap для указанных слайдов презентации.

### Возвращаемое значение

Bitmap objects.



```python
def get_images(self, options, slides):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions) | Rendering options. |
| slides | **List[int]** | Array with slide positions, starting from 1. |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
Возвращает объекты Thumbnail Image для всех слайдов презентации с указанным размером.

### Возвращаемое значение

Bitmap objects.



```python
def get_images(self, options, image_size):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions) | Rendering options. |
| image_size | **aspose.slides.Size** | Size of the image to create. |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Возвращает объекты Thumbnail Image для всех слайдов презентации с пользовательским масштабированием.

### Возвращаемое значение

Bitmap objects.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions) | Rendering options. |
| scale_x | **float** | The value by which to scale this Thumbnail in the x-axis direction. |
| scale_y | **float** | The value by which to scale this Thumbnail in the y-axis direction. |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposepydrawingsize}
Возвращает объекты Thumbnail Image для указанных слайдов презентации с указанным размером.

### Возвращаемое значение

Bitmap objects.



```python
def get_images(self, options, slides, image_size):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions) | Rendering options. |
| slides | **List[int]** | Array with slide positions, starting from 1. |
| image_size | **aspose.slides.Size** | Size of the image to create. |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
Возвращает объекты Thumbnail Image для указанных слайдов презентации с пользовательским масштабированием.

### Возвращаемое значение

Bitmap objects.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions) | Rendering options. |
| slides | **List[int]** | Array with slide positions, starting from 1. |
| scale_x | **float** | The value by which to scale this Thumbnail in the x-axis direction. |
| scale_y | **float** | The value by which to scale this Thumbnail in the y-axis direction. |



### См. также
* класс [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation)
* класс [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)