---
title: Audio class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/audio/
---
## Audio класс

Представляет встроенный аудиофайл.

Тип Audio предоставляет следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`content_type`](/slides/python-net/ru/aspose.slides/audio/content_type/) | Возвращает MIME-тип аудио, закодированный в [`Audio.binary_data`](/slides/python-net/ru/aspose.slides/audio/binary_data).<br/>            Только для чтения **str**. |
| [`binary_data`](/slides/python-net/ru/aspose.slides/audio/binary_data/) | Возвращает копию данных аудио. В случае большого объёма данных рассмотрите <br/>            использование метода [`Audio.get_stream`](/slides/python-net/ru/aspose.slides/audio/get_stream) для предотвращения ненужной загрузки данных аудио<br/>            в память или даже возникновения OutOfMemoryException.<br/>            Только для чтения **int**[]. |

## Методы

| Метод | Описание |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/ru/aspose.slides/audio/get_stream/#) | Возвращает поток Stream для чтения.<br/>            Используйте 'using' или закройте поток после использования. |


### Смотрите также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)