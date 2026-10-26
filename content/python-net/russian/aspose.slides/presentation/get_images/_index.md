---
title: get_images method
second_title: Aspose.Slides для Python через .NET справка по API
description: 
type: docs
url: /ru/aspose.slides/presentation/get_images/
weight: 20
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
Возвращает объекты Image для всех слайдов презентации.

### Возвращает

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

### Возвращает

Объекты Image.



```python
def get_images(self, options, slides):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions) | Параметры Tiff. |
| slides | **List[int]** | Массив позиций слайдов, начиная с 1. |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
Возвращает объекты Thumbnail Image для всех слайдов презентации с указанным размером.

### Возвращает

Объекты Image.



```python
def get_images(self, options, image_size):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions) | Параметры Tiff. |
| image_size | [`Size`](/slides/python-net/ru/aspose.slides/size) | Размер изображения для создания. |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Возвращает объекты Thumbnail Image для всех слайдов презентации с пользовательским масштабированием.

### Возвращает

Объекты Image.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions) | Параметры Tiff. |
| scale_x | **float** | Значение, на которое масштабировать этот Thumbnail по оси x. |
| scale_y | **float** | Значение, на которое масштабировать этот Thumbnail по оси y. |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposeslidessize}
Возвращает объекты Thumbnail Image для указанных слайдов презентации с указанным размером.

### Возвращает

Объекты Image.



```python
def get_images(self, options, slides, image_size):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions) | Параметры Tiff. |
| slides | **List[int]** | Массив позиций слайдов, начиная с 1. |
| image_size | [`Size`](/slides/python-net/ru/aspose.slides/size) | Размер изображения для создания. |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
Возвращает объекты Thumbnail Image для указанных слайдов презентации с пользовательским масштабированием.

### Возвращает

Объекты Image.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions) | Параметры Tiff. |
| slides | **List[int]** | Массив позиций слайдов, начиная с 1. |
| scale_x | **float** | Значение, на которое масштабировать этот Thumbnail по оси x. |
| scale_y | **float** | Значение, на которое масштабировать этот Thumbnail по оси y. |



### См. также
* класс [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions)
* класс [`Presentation`](/slides/python-net/ru/aspose.slides/presentation)
* класс [`Size`](/slides/python-net/ru/aspose.slides/size)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)