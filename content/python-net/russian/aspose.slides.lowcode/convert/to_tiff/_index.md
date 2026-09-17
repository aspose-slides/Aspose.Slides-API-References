---
title: to_tiff method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.lowcode/convert/to_tiff/
weight: 60
---
## to_tiff(pres, output_file_name) {#presentation-str}
Преобразует входную презентацию в набор изображений формата TIFF.  
            Если имя выходного файла указано как "myPath/myFilename.tiff", результат будет сохранён как набор файлов "myPath/myFilename_N.tiff", где N — номер слайда.


```python
@staticmethod
def to_tiff(pres, output_file_name):
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


## to_tiff(pres, output_file_name, options, multipage) {#presentation-str-asposeslidesexportitiffoptions-bool}
Преобразует входную презентацию в формат TIFF с пользовательскими параметрами.  
            Если имя выходного файла указано как "myPath/myFilename.tiff" и `multipage` равно `false`, результат будет сохранён как набор файлов "myPath/myFilename_N.tiff", где N — номер слайда.  
            В противном случае, если `multipage` равно `true`, результат будет представлять собой многостраничный документ "myPath/myFilename.tiff".


```python
@staticmethod
def to_tiff(pres, output_file_name, options, multipage):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/ru/aspose.slides/presentation) | Входная презентация. |
| output_file_name | **str** | Имя выходного файла. |
| options | [`ITiffOptions`](/slides/python-net/ru/aspose.slides.export/itiffoptions) | Параметры сохранения TIFF. |
| multipage | **bool** | Указывает, следует ли генерировать многостраничный документ TIFF. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### См. также
* класс [`Convert`](/slides/python-net/ru/aspose.slides.lowcode/convert)
* класс [`ITiffOptions`](/slides/python-net/ru/aspose.slides.export/itiffoptions)
* класс [`Presentation`](/slides/python-net/ru/aspose.slides/presentation)
* модуль [`aspose.slides.lowcode`](/slides/python-net/ru/aspose.slides.lowcode)
* библиотека [`Aspose.Slides`](/slides/python-net)