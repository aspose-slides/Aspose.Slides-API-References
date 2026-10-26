---
title: to_png method
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides.lowcode/convert/to_png/
weight: 40
---
## to_png(pres, output_file_name) {#presentation-str}
Преобразует входную презентацию в набор изображений формата PNG.  
            Если имя выходного файла указано как "myPath/myFilename.png", 
            результат будет сохранён как набор файлов "myPath/myFilename_N.png", где N – номер слайда.


```python
@staticmethod
def to_png(pres, output_file_name):
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


## to_png(pres, output_file_name, image_size) {#presentation-str-asposeslidessize}
Преобразует входную презентацию в набор изображений формата PNG.  
            Если имя выходного файла указано как "myPath/myFilename.png", 
            результат будет сохранён как набор файлов "myPath/myFilename_N.png", где N – номер слайда.


```python
@staticmethod
def to_png(pres, output_file_name, image_size):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/ru/aspose.slides/presentation) | Входная презентация |
| output_file_name | **str** | Имя выходного файла. |
| image_size | [`Size`](/slides/python-net/ru/aspose.slides/size) | Размер каждого создаваемого изображения. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
Преобразует входную презентацию в набор изображений формата PNG.  
            Если имя выходного файла указано как "myPath/myFilename.png", 
            результат будет сохранён как набор файлов "myPath/myFilename_N.png", где N – номер слайда.


```python
@staticmethod
def to_png(pres, output_file_name, scale, options):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/ru/aspose.slides/presentation) | Входная презентация. |
| output_file_name | **str** | Имя выходного файла. |
| scale | **float** | Коэффициент масштабирования, применяемый к выходным изображениям относительно оригинального размера слайда. |
| options | [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions) | Параметры рендеринга. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### См. также
* класс [`Convert`](/slides/python-net/ru/aspose.slides.lowcode/convert)
* класс [`IRenderingOptions`](/slides/python-net/ru/aspose.slides.export/irenderingoptions)
* класс [`Presentation`](/slides/python-net/ru/aspose.slides/presentation)
* класс [`Size`](/slides/python-net/ru/aspose.slides/size)
* модуль [`aspose.slides.lowcode`](/slides/python-net/ru/aspose.slides.lowcode)
* библиотека [`Aspose.Slides`](/slides/python-net)