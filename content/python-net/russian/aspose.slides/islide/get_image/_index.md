---
title: get_image method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/islide/get_image/
weight: 40
---
## get_image(self) {#}
Возвращает объект изображения-миниатюры (20% реального размера).

### Возвращаемое значение

Объект изображения **aspose.slides.IImage**



```python
def get_image(self):
    ...
```



## get_image(self, image_size) {#asposeslidessize}
Возвращает объект изображения с указанным размером.

### Возвращаемое значение

Объект Bitmap.



```python
def get_image(self, image_size):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| image_size | [`Size`](/slides/python-net/ru/aspose.slides/size) | Размер создаваемого изображения. |


## get_image(self, options) {#asposeslidesexportitiffoptions}
Возвращает объект Thumbnail tiff bitmap с указанными параметрами.

### Возвращаемое значение

Объект изображения.



```python
def get_image(self, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/ru/aspose.slides.export/itiffoptions) | Параметры Tiff. |


## get_image(self, options) {#asposeslidesexportirenderingoptions}
Возвращает объект Thumbnail Bitmap.

### Возвращаемое значение

Объекты Bitmap.



```python
def get_image(self, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions) | Параметры визуализации. |


## get_image(self, scale_x, scale_y) {#float-float}
Возвращает объект изображения с пользовательским масштабированием.

### Возвращаемое значение

Объект изображения **aspose.slides.IImage**



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| scale_x | **float** | Значение, на которое следует масштабировать эту миниатюру вдоль оси X. |
| scale_y | **float** | Значение, на которое следует масштабировать эту миниатюру вдоль оси Y. |


## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
Возвращает объект Thumbnail Bitmap с указанным размером.

### Возвращаемое значение

Объекты Bitmap.



```python
def get_image(self, options, image_size):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions) | Параметры визуализации. |
| image_size | [`Size`](/slides/python-net/ru/aspose.slides/size) | Размер создаваемого изображения. |


## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Возвращает объект Thumbnail Bitmap с пользовательским масштабированием.

### Возвращаемое значение

Объекты Bitmap.



```python
def get_image(self, options, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions) | Параметры визуализации. |
| scale_x | **float** | Значение, на которое следует масштабировать эту миниатюру вдоль оси X. |
| scale_y | **float** | Значение, на которое следует масштабировать эту миниатюру вдоль оси Y. |


### Смотрите также
* класс [`IImage`](/slides/python-net/ru/aspose.slides/iimage)
* класс [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions)
* класс [`ISlide`](/slides/python-net/ru/aspose.slides/islide)
* класс [`ITiffOptions`](/slides/python-net/ru/aspose.slides.export/itiffoptions)
* класс [`Size`](/slides/python-net/ru/aspose.slides/size)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)