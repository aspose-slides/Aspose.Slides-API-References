---
title: get_image method
second_title: Aspose.Slides для Python через .NET API Справочник
description: 
type: docs
url: /ru/aspose.slides/islide/get_image/
weight: 40
---
## get_image(self) {#}
Возвращает объект миниатюрного изображения (20% от реального размера).

### Returns

Объект изображения **aspose.slides.Bitmap**



```python
def get_image(self):
    ...
```



## get_image(self, image_size) {#asposepydrawingsize}
Возвращает объект изображения с указанным размером.

### Returns

Объект Bitmap.



```python
def get_image(self, image_size):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| image_size | **aspose.slides.Size** | Размер изображения, которое нужно создать. |


## get_image(self, options) {#asposeslidesexportitiffoptions}
Возвращает объект Bitmap формата TIFF миниатюры с указанными параметрами.

### Returns

Объект изображения.



```python
def get_image(self, options):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/ru/aspose.slides.export/itiffoptions) | Параметры TIFF. |


## get_image(self, options) {#asposeslidesexportirenderingoptions}
Возвращает объект Bitmap миниатюры.

### Returns

Объекты Bitmap.



```python
def get_image(self, options):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions) | Параметры рендеринга. |


## get_image(self, scale_x, scale_y) {#float-float}
Возвращает объект изображения с пользовательским масштабированием.

### Returns

Объект изображения **aspose.slides.Bitmap**



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| scale_x | **float** | Значение, на которое масштабировать этот эскиз по оси x. |
| scale_y | **float** | Значение, на которое масштабировать этот эскиз по оси y. |


## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
Возвращает объект Bitmap миниатюры с указанным размером.

### Returns

Объекты Bitmap.



```python
def get_image(self, options, image_size):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions) | Параметры рендеринга. |
| image_size | **aspose.slides.Size** | Размер изображения, которое нужно создать. |


## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Возвращает объект Bitmap миниатюры с пользовательским масштабированием.

### Returns

Объекты Bitmap.



```python
def get_image(self, options, scale_x, scale_y):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions) | Параметры рендеринга. |
| scale_x | **float** | Значение, на которое масштабировать этот эскиз по оси x. |
| scale_y | **float** | Значение, на которое масштабировать этот эскиз по оси y. |



### See Also
* класс [`IImage`](/slides/python-net/ru/aspose.slides/iimage)
* класс [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions)
* класс [`ISlide`](/slides/python-net/ru/aspose.slides/islide)
* класс [`ITiffOptions`](/slides/python-net/ru/aspose.slides.export/itiffoptions)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)