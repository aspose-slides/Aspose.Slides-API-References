---
title: get_image method
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides/slide/get_image/
weight: 40
---
## get_image(self) {#}
Возвращает объект Thumbnail Image (20% реального размера).


```python
def get_image(self):
    ...
```



## get_image(self, image_size) {#asposeslidessize}
Возвращает объект Thumbnail Image с указанным размером.

### Возвращаемое значение

Объект Image.



```python
def get_image(self, image_size):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| image_size | [`Size`](/slides/python-net/ru/aspose.slides/size) | Размер создаваемого изображения. |


## get_image(self, options) {#asposeslidesexportitiffoptions}
Возвращает объект Thumbnail tiff image с указанными параметрами.

### Возвращаемое значение

Объект Image.



```python
def get_image(self, options):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/ru/aspose.slides.export/itiffoptions) | Параметры Tiff. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Выбрасывается, когда options.SlideLayoutOption равно NotesCommentsLayoutingOptions и его свойство NotesPosition принимает значение NotesPositions.BottomFull. |


## get_image(self, options) {#asposeslidesexportirenderingoptions}
Возвращает объект Thumbnail Image.

### Возвращаемое значение

Объект Image.



```python
def get_image(self, options):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions) | Параметры рендеринга. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Выбрасывается, когда notesCommentsLayouting.NotesPosition принимает значение NotesPositions.BottomFull. |


## get_image(self, scale_x, scale_y) {#float-float}
Возвращает объект Thumbnail Image с пользовательским масштабированием.

### Возвращаемое значение

Объект IImage.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| scale_x | **float** | Значение, на которое нужно масштабировать этот Thumbnail по оси X. |
| scale_y | **float** | Значение, на которое нужно масштабировать этот Thumbnail по оси Y. |


## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
Возвращает объект Thumbnail Image с указанным размером.

### Возвращаемое значение

Объект Image.



```python
def get_image(self, options, image_size):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions) | Параметры рендеринга. |
| image_size | [`Size`](/slides/python-net/ru/aspose.slides/size) | Размер создаваемого изображения. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Выбрасывается, когда options.SlideLayoutOption равно NotesCommentsLayoutingOptions и его свойство NotesPosition принимает значение NotesPositions.BottomFull. |


## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Возвращает объект Thumbnail Image с пользовательским масштабированием.

### Возвращаемое значение

Объекты Bitmap.



```python
def get_image(self, options, scale_x, scale_y):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions) | Параметры рендеринга. |
| scale_x | **float** | Значение, на которое нужно масштабировать этот Thumbnail по оси X. |
| scale_y | **float** | Значение, на которое нужно масштабировать этот Thumbnail по оси Y. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Выбрасывается, когда notesCommentsLayouting.NotesPosition принимает значение NotesPositions.BottomFull. |



### См. также
* класс [`IImage`](/slides/python-net/ru/aspose.slides/iimage)
* класс [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions)
* класс [`ITiffOptions`](/slides/python-net/ru/aspose.slides.export/itiffoptions)
* класс [`Slide`](/slides/python-net/ru/aspose.slides/slide)
* класс [`Size`](/slides/python-net/ru/aspose.slides/size)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)