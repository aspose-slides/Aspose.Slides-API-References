---
title: to_jpeg method
second_title: Aspose.Slides для Python через .NET API Справочник
description: 
type: docs
url: /ru/aspose.slides.lowcode/convert/to_jpeg/
weight: 20
---
## to_jpeg(pres, output_file_name) {#presentation-str}
Преобразует входную презентацию в набор изображений в формате JPEG.  
Если имя выходного файла указано как "myPath/myFilename.jpeg", результат будет сохранён как набор файлов "myPath/myFilename_N.jpeg", где N — номер слайда.


```python
@staticmethod
def to_jpeg(pres, output_file_name):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/ru/aspose.slides/presentation) | Входная презентация. |
| output_file_name | **str** | Имя выходного файла. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_jpeg(pres, output_file_name, image_size) {#presentation-str-asposepydrawingsize}
Преобразует входную презентацию в набор изображений в формате JPEG.  
Если имя выходного файла указано как "myPath/myFilename.jpeg", результат будет сохранён как набор файлов "myPath/myFilename_N.jpeg", где N — номер слайда.


```python
@staticmethod
def to_jpeg(pres, output_file_name, image_size):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/ru/aspose.slides/presentation) | Входная презентация |
| output_file_name | **str** | Имя выходного файла. |
| image_size | **aspose.slides.Size** | Размер каждого сгенерированного изображения. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_jpeg(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
Преобразует входную презентацию в набор изображений в формате JPEG.  
Если имя выходного файла указано как "myPath/myFilename.jpeg", результат будет сохранён как набор файлов "myPath/myFilename_N.jpeg", где N — номер слайда.


```python
@staticmethod
def to_jpeg(pres, output_file_name, scale, options):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/ru/aspose.slides/presentation) | Входная презентация. |
| output_file_name | **str** | Имя выходного файла. |
| scale | **float** | Коэффициент масштабирования, применяемый к выходным изображениям относительно оригинального размера слайда. |
| options | [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions) | Опции рендеринга. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### См. также
* класс [`Convert`](/slides/python-net/ru/aspose.slides.lowcode/convert)
* класс [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions)
* класс [`Presentation`](/slides/python-net/ru/aspose.slides/presentation)
* модуль [`aspose.slides.lowcode`](/slides/python-net/ru/aspose.slides.lowcode)
* библиотека [`Aspose.Slides`](/slides/python-net)