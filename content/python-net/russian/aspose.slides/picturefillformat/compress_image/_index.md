---
title: compress_image method
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides/picturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
Сжимает изображение, уменьшая его размер в соответствии с размером фигуры и указанным разрешением. При необходимости также удаляет обрезанные области.

### Возвращаемое значение

Булево значение (**bool**), указывающее, было ли изображение успешно сжато. Возвращает **True**, если изображение было изменено в размере или обрезано, в противном случае **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Если **true**, метод удалит обрезанные области изображения, что может дополнительно уменьшить его размер. |
| resolution | [`PicturesCompression`](/slides/python-net/ru/aspose.slides.export/picturescompression) | Целевое разрешение для сжатия, указанное как значение перечисления [`PicturesCompression`](/slides/python-net/ru/aspose.slides.export/picturescompression). |

### Примечания

Этот метод изменяет размер и разрешение изображения, аналогично функции PowerPoint «Picture Format -> Compress Pictures».

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Генерируется, когда разрешение имеет недопустимое значение. |


## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
Сжимает изображение, уменьшая его размер в соответствии с размером фигуры и указанным разрешением. При необходимости также удаляет обрезанные области.

### Возвращаемое значение

Булево значение (**bool**), указывающее, было ли изображение успешно сжато. Возвращает **True**, если изображение было изменено в размере или обрезано, в противном случае **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Если **true**, метод удалит обрезанные области изображения, что может дополнительно уменьшить его размер. |
| resolution | **float** | Целевое разрешение в DPI. Это значение должно быть положительным и определяет, как будет изменён размер изображения. |

### Примечания

Этот метод изменяет размер и разрешение изображения, аналогично функции PowerPoint «Picture Format -> Compress Pictures».

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Генерируется, когда разрешение не является положительным значением. |



### См. также
* класс [`PictureFillFormat`](/slides/python-net/ru/aspose.slides/picturefillformat)
* перечисление [`PicturesCompression`](/slides/python-net/ru/aspose.slides.export/picturescompression)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)