---
title: ExternalResourceResolver class
second_title: Aspose.Slides для Python через .NET справка API
description: 
type: docs
url: /ru/aspose.slides.importing/externalresourceresolver/
---
## ExternalResourceResolver класс

Callback класс, используемый для разрешения внешних ресурсов во время импорта документов Html, Svg.  
Использование этого резольвера может создать уязвимость, когда клиент предоставляет файл HTML или SVG, заставляя серверное программное обеспечение получать локальный или сетевой файл. Используйте с осторожностью. Рекомендуется вовсе не указывать ExternalResourceResolver (будут прочитаны только встроенные объекты) или создать подкласс, который проверяет, является ли указанный uri действительным.

Тип ExternalResourceResolver раскрывает следующие члены:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ru/aspose.slides.importing/externalresourceresolver/__init__/#) |  |

## Методы

| Метод | Описание |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/ru/aspose.slides.importing/externalresourceresolver/resolve_uri/#str-str) | Разрешает абсолютный URI из базового и относительного URI. |
| [`get_entity(self, absolute_uri)`](/slides/python-net/ru/aspose.slides.importing/externalresourceresolver/get_entity/#str) | Преобразует URI в объект, содержащий фактический ресурс. |


### См. также
* модуль [`aspose.slides.importing`](/slides/python-net/ru/aspose.slides.importing)
* библиотека [`Aspose.Slides`](/slides/python-net)