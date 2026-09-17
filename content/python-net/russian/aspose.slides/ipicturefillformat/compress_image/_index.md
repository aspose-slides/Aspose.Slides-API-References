---
title: compress_image method
second_title: Aspose.Slides для Python через .NET Справочник API
description: 
type: docs
url: /ru/aspose.slides/ipicturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
Сжимает изображение, уменьшая его размер в зависимости от размеров формы и указанного разрешения. При желании также удаляет обрезанные участки.

### Возвращаемое значение

Булево значение, указывающее, было ли изображение успешно сжато. Возвращает **True**, если изображение было изменено по размеру или обрезано, в противном случае **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Если true, метод удалит обрезанные области изображения, потенциально дополнительно уменьшая его размер. |
| resolution | [`PicturesCompression`](/slides/python-net/ru/aspose.slides.export/picturescompression) | Целевое разрешение для сжатия, указанное как значение [`PicturesCompression`](/slides/python-net/ru/aspose.slides.export/picturescompression). |

### Замечания

Этот метод изменяет размер и разрешение изображения аналогично функции PowerPoint «Picture Format -> Compress Pictures».

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Выбрасывается, когда разрешение имеет недопустимое значение. |


## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
Сжимает изображение, уменьшая его размер в зависимости от размеров формы и указанного разрешения. При желании также удаляет обрезанные участки.

### Возвращаемое значение

Булево значение, указывающее, было ли изображение успешно сжито. Возвращает **True**, если изображение было изменено по размеру или обрезано, в противном случае **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Если true, метод удалит обрезанные области изображения, потенциально дополнительно уменьшая его размер. |
| resolution | **float** | Целевое разрешение в DPI. Это значение должно быть положительным и определяет, как будет изменён размер изображения. |

### Замечания

Этот метод изменяет размер и разрешение изображения аналогично функции PowerPoint «Picture Format -> Compress Pictures».

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Выбрасывается, когда разрешение не является положительным значением. |



### См. также
* класс [`IPictureFillFormat`](/slides/python-net/ru/aspose.slides/ipicturefillformat)
* перечисление [`PicturesCompression`](/slides/python-net/ru/aspose.slides.export/picturescompression)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)