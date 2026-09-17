---
title: get_image method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/slide/get_image/
weight: 40
---
## get_image(self) {#}
Возвращает объект Thumbnail Image (20 % реального размера).


```python
def get_image(self):
    ...
```



## get_image(self, image_size) {#asposepydrawingsize}
Возвращает объект Thumbnail Image с указанным размером.

### Возвращаемое значение

Объект Image.



```python
def get_image(self, image_size):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| image_size | **aspose.slides.Size** | Размер изображения для создания. |


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
| **RuntimeError(Proxy error(InvalidOperationException))** | Выбрасается, когда options.SlideLayoutOption имеет значение NotesCommentsLayoutingOptions, а его свойство NotesPosition принимает значение NotesPositions.BottomFull. |


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
| options | [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions) | Параметры Rendering. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Выбрасается, когда notesCommentsLayouting.NotesPosition принимает значение NotesPositions.BottomFull. |


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
| scale_x | **float** | Значение, на которое следует масштабировать этот Thumbnail по оси x. |
| scale_y | **float** | Значение, на которое следует масштабировать этот Thumbnail по оси y. |


## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
Возвращает объект Thumbnail Image с указанным размером.

### Возвращаемое значение

Объект Image.



```python
def get_image(self, options, image_size):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions) | Параметры Rendering. |
| image_size | **aspose.slides.Size** | Размер изображения для создания. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Выбрасается, когда options.SlideLayoutOption имеет значение NotesCommentsLayoutingOptions, а его свойство NotesPosition принимает значение NotesPositions.BottomFull. |


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
| options | [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions) | Параметры Rendering. |
| scale_x | **float** | Значение, на которое следует масштабировать этот Thumbnail по оси x. |
| scale_y | **float** | Значение, на которое следует масштабировать этот Thumbnail по оси y. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Выбрасается, когда notesCommentsLayouting.NotesPosition принимает значение NotesPositions.BottomFull. |



### Смотрите также
* класс [`IImage`](/slides/python-net/ru/aspose.slides/iimage)
* класс [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions)
* класс [`ITiffOptions`](/slides/python-net/ru/aspose.slides.export/itiffoptions)
* класс [`Slide`](/slides/python-net/ru/aspose.slides/slide)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)