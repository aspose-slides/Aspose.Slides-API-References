---
title: Video class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/video/
---
## Video класс

Представляет изображение, встроенное в презентацию.

Тип Video раскрывает следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`content_type`](/slides/python-net/ru/aspose.slides/video/content_type/) | Возвращает MIME-тип видео, закодированный в [`Video.binary_data`](/slides/python-net/ru/aspose.slides/video/binary_data).<br/>            Только для чтения **str**. |
| [`binary_data`](/slides/python-net/ru/aspose.slides/video/binary_data/) | Возвращает копию данных аудио. В случае большого объёма данных рекомендуется использовать <br/>            метод [`Video.get_stream`](/slides/python-net/ru/aspose.slides/video/get_stream) для предотвращения ненужной загрузки данных видео в память <br/>            или даже исключения OutOfMemoryException.<br/>            Только для чтения **int**[]. |

## Методы

| Метод | Описание |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/ru/aspose.slides/video/get_stream/#) | Возвращает поток Stream для чтения.<br/>            Используйте 'using' или закройте поток после использования. |


### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)