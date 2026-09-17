---
title: save method
second_title: Aspose.Slides для Python через .NET API Справочник
description: 
type: docs
url: /ru/aspose.slides/iimage/save/
weight: 10
---
## save(self, filename) {#str}
Сохраняет изображение в файл.

```python
def save(self, filename):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| filename | **str** | Путь к файлу, в котором будет сохранено изображение. |

## save(self, filename, format) {#str-imageformat}
Сохраняет изображение в файл в указанном формате.

```python
def save(self, filename, format):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| filename | **str** | Путь к файлу, в котором будет сохранено изображение. |
| format | [`ImageFormat`](/slides/python-net/ru/aspose.slides/imageformat) | Формат изображения. |

## save(self, stream, format) {#iorawiobase-imageformat}
Сохраняет изображение в поток в указанном формате.

```python
def save(self, stream, format):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | **io.RawIOBase** | Поток, в который будет сохранено изображение. |
| format | [`ImageFormat`](/slides/python-net/ru/aspose.slides/imageformat) | Формат изображения. |

## save(self, filename, format, quality) {#str-imageformat-int}
Сохраняет изображение в файл в указанном формате и качестве.

```python
def save(self, filename, format, quality):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| filename | **str** | Путь к файлу, в котором будет сохранено изображение. |
| format | [`ImageFormat`](/slides/python-net/ru/aspose.slides/imageformat) | Формат изображения. |
| quality | **int** | Качество сохраняемого изображения (0 до 100).  <br/><br/>            Этот параметр влияет только на сохранение в [`ImageFormat.JPEG`](/slides/python-net/ru/aspose.slides/imageformat/JPEG); для всех остальных форматов он игнорируется. |

## save(self, stream, format, quality) {#iorawiobase-imageformat-int}
Сохраняет изображение в поток в указанном формате и качестве.

```python
def save(self, stream, format, quality):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | **io.RawIOBase** | Поток, в который будет сохранено изображение. |
| format | [`ImageFormat`](/slides/python-net/ru/aspose.slides/imageformat) | Формат изображения. |
| quality | **int** | Качество сохраняемого изображения (0 до 100).  <br/><br/>            Этот параметр влияет только на сохранение в [`ImageFormat.JPEG`](/slides/python-net/ru/aspose.slides/imageformat/JPEG); для всех остальных форматов он игнорируется. |

### See Also
* класс [`IImage`](/slides/python-net/ru/aspose.slides/iimage)
* перечисление [`ImageFormat`](/slides/python-net/ru/aspose.slides/imageformat)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)