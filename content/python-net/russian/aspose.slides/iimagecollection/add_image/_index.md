---
title: add_image method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/iimagecollection/add_image/
weight: 10
---
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

Этот метод преобразует метафайлы WMF/EMF в растровое PNG-изображение перед вставкой в презентацию.


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

Этот метод может добавить метафайлы WMF/EMF в презентацию без преобразования их в растровое PNG-изображение.


## add_image(self, buffer) {#bytes}
Добавляет изображение в презентацию из указанного буфера.

### Возвращаемое значение

Добавленное изображение.



```python
def add_image(self, buffer):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| buffer | **bytes** | Буфер. |


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


## add_image(self, svg_image) {#isvgimage}
Добавить изображение в презентацию из SVG-объекта.

### Возвращаемое значение

Добавленное изображение.



```python
def add_image(self, svg_image):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/ru/aspose.slides/isvgimage) | Объект SVG-изображения [`ISvgImage`](/slides/python-net/ru/aspose.slides/isvgimage) |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Выбрасывается, когда параметр svgImage равен None. |


## add_image(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Создаёт и добавляет изображение в презентацию из потока.

### Возвращаемое значение

Добавлен [`IPPImage`](/slides/python-net/ru/aspose.slides/ippimage).



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
* класс [`IImageCollection`](/slides/python-net/ru/aspose.slides/iimagecollection)
* класс [`IPPImage`](/slides/python-net/ru/aspose.slides/ippimage)
* класс [`ISvgImage`](/slides/python-net/ru/aspose.slides/isvgimage)
* перечисление [`LoadingStreamBehavior`](/slides/python-net/ru/aspose.slides/loadingstreambehavior)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)