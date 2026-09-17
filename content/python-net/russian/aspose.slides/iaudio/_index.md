---
title: IAudio class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/iaudio/
---
## IAudio класс

Представляет встроенный аудиофайл.

Тип IAudio предоставляет следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`content_type`](/slides/python-net/ru/aspose.slides/iaudio/content_type/) | Returns a MIME type of an audio, encoded in [`IAudio.binary_data`](/slides/python-net/ru/aspose.slides/iaudio/binary_data).<br/>            Только для чтения **str**. |
| [`binary_data`](/slides/python-net/ru/aspose.slides/iaudio/binary_data/) | Returns the copy of an audio's data. In case of large amount of data consider <br/>            using of [`IAudio.get_stream`](/slides/python-net/ru/aspose.slides/iaudio/get_stream) method to prevent unnecessary  loading of audio's<br/>            data into memory or even OutOfMemoryException.<br/>            Только для чтения **int**[]. |

## Методы

| Метод | Описание |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/ru/aspose.slides/iaudio/get_stream/#) | Returns Stream stream for reading.<br/>            Use 'using' or close stream after using. |


### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)