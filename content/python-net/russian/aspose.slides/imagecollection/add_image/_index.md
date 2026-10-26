---
title: add_image method
second_title: Aspose.Slides для Python через .NET API Справочник
description: 
type: docs
url: /ru/aspose.slides/imagecollection/add_image/
weight: 10
---
## add_image(self, image_source) {#ippimage}
Добавляет копию изображения из другой презентации.

### Возвращаемое значение

Добавленное изображение.



```python
def add_image(self, image_source):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| image_source | [`IPPImage`](/slides/python-net/ru/aspose.slides/ippimage) | Исходное изображение. |


## add_image(self, image) {#iimage}
Добавить изображение в презентацию.

### Возвращаемое значение

Добавленное изображение.



```python
def add_image(self, image):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [`IImage`](/slides/python-net/ru/aspose.slides/iimage) | Изображение для добавления. |

### Примечания

Этот метод конвертирует метафайлы WMF/EMF в растровое PNG-изображение перед вставкой в презентацию.


## add_image(self, stream) {#iorawiobase}
Добавить изображение в презентацию из потока.

### Возвращаемое значение

Добавленное изображение.



```python
def add_image(self, stream):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | **io.RawIOBase** | Поток, из которого добавляется изображение. |

### Примечания

Этот метод может добавить метафайлы WMF/EMF в презентацию без их конвертации в растровое PNG-изображение.


## add_image(self, buffer) {#bytes}
Добавляет изображение в презентацию из заданного буфера.

### Возвращаемое значение

Добавленное изображение.



```python
def add_image(self, buffer):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| buffer | **bytes** | Буфер. |


## add_image(self, svg_image) {#isvgimage}
Добавить изображение в презентацию из объекта Svg.

### Возвращаемое значение

Добавленное изображение.



```python
def add_image(self, svg_image):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/ru/aspose.slides/isvgimage) | Объект изображения Svg [`ISvgImage`](/slides/python-net/ru/aspose.slides/isvgimage) |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Когда параметр svgImage равен None. |


## add_image(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Создаёт и добавляет изображение в презентацию из потока.

### Возвращаемое значение

Добавлено [`IPPImage`](/slides/python-net/ru/aspose.slides/ippimage).



```python
def add_image(self, stream, loading_stream_behavior):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | **io.RawIOBase** | Поток, из которого добавляется файл изображения. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/ru/aspose.slides/loadingstreambehavior) | Поведение, которое будет применено к потоку. |



### См. также
* класс [`IImage`](/slides/python-net/ru/aspose.slides/iimage)
* класс [`ImageCollection`](/slides/python-net/ru/aspose.slides/imagecollection)
* класс [`IPPImage`](/slides/python-net/ru/aspose.slides/ippimage)
* класс [`ISvgImage`](/slides/python-net/ru/aspose.slides/isvgimage)
* перечисление [`LoadingStreamBehavior`](/slides/python-net/ru/aspose.slides/loadingstreambehavior)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)