---
title: Zip64Mode enumeration
second_title: Справка API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides.export/zip64mode/
---
## Перечисление Zip64Mode

Указывает, когда следует использовать расширения формата ZIP64 для файла OpenXML.

Тип Zip64Mode содержит следующие члены:

## Поля

| Поле | Описание |
| :- | :- |
| NEVER | Не использовать расширения формата ZIP64. |
| IF_NECESSARY | Использовать расширения формата ZIP64 при необходимости. |
| ALWAYS | Всегда использовать расширения формата ZIP64. |


### Примечания

Файл OpenXML является ZIP-архивом, у которого есть ограничение в 4 ГБ (2^32 байт) на размер несжатого файла, размер сжатого файла и общий размер архива, а также ограничение в 65 535 (2^16-1) файлов в архиве. Расширения формата ZIP64 увеличивают эти ограничения до 2^64.


### См. также
* модуль [`aspose.slides.export`](/slides/python-net/ru/aspose.slides.export)
* библиотека [`Aspose.Slides`](/slides/python-net)