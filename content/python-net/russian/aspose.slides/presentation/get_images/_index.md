---
title: get_images method
second_title: Aspose.Slides для Python через .NET API справка
description: 
type: docs
url: /ru/aspose.slides/presentation/get_images/
weight: 20
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
Возвращает объекты Image для всех слайдов презентации.

### Возвращаемое значение

Объекты Image.



```python
def get_images(self, options):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions) | Параметры Tiff. |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
Возвращает объекты Thumbnail Image для указанных слайдов презентации.

### Возвращаемое значение

Объекты Image.



```python
def get_images(self, options, slides):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions) | Параметры Tiff. |
| slides | **List[int]** | Массив позиций слайдов, начиная с 1. |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
Возвращает объекты Thumbnail Image для всех слайдов презентации с заданным размером.

### Возвращаемое значение

Объекты Image.



```python
def get_images(self, options, image_size):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions) | Параметры Tiff. |
| image_size | **aspose.slides.Size** | Размер создаваемого изображения. |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Возвращает объекты Thumbnail Image для всех слайдов презентации с пользовательским масштабированием.

### Возвращаемое значение

Объекты Image.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions) | Параметры Tiff. |
| scale_x | **float** | Значение, на которое следует масштабировать этот Thumbnail по оси x. |
| scale_y | **float** | Значение, на которое следует масштабировать этот Thumbnail по оси y. |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposepydrawingsize}
Возвращает объекты Thumbnail Image для указанных слайдов презентации с заданным размером.

### Возвращаемое значение

Объекты Image.



```python
def get_images(self, options, slides, image_size):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions) | Параметры Tiff. |
| slides | **List[int]** | Массив позиций слайдов, начиная с 1. |
| image_size | **aspose.slides.Size** | Размер создаваемого изображения. |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
Возвращает объекты Thumbnail Image для указанных слайдов презентации с пользовательским масштабированием.

### Возвращаемое значение

Объекты Image.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions) | Параметры Tiff. |
| slides | **List[int]** | Массив позиций слайдов, начиная с 1. |
| scale_x | **float** | Значение, на которое следует масштабировать этот Thumbnail по оси x. |
| scale_y | **float** | Значение, на которое следует масштабировать этот Thumbnail по оси y. |



### Смотрите также
* класс [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions)
* класс [`Presentation`](/slides/python-net/ru/aspose.slides/presentation)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)