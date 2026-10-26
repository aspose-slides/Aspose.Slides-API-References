---
title: IVideo class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/ivideo/
---
## IVideo класс

Представляет видеоролик, встроенный в презентацию.

Тип IVideo предоставляет следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`content_type`](/slides/python-net/ru/aspose.slides/ivideo/content_type/) | Возвращает MIME-тип видеоролика, закодированный в [`IVideo.binary_data`](/slides/python-net/ru/aspose.slides/ivideo/binary_data).<br/> Только для чтения **str**. |
| [`binary_data`](/slides/python-net/ru/aspose.slides/ivideo/binary_data/) | Возвращает копию данных аудио. В случае большого объёма данных рекомендуется использовать метод [`IVideo.get_stream`](/slides/python-net/ru/aspose.slides/ivideo/get_stream), чтобы избежать ненужной загрузки данных видеоролика в память <br/> или даже исключения OutOfMemoryException.<br/> Только для чтения **int**[]. |

## Методы

| Метод | Описание |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/ru/aspose.slides/ivideo/get_stream/#) | Возвращает поток Stream для чтения.<br/> Используйте 'using' или закройте поток после использования. |


### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)