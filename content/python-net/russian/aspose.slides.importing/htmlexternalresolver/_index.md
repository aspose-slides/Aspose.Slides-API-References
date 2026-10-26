---
title: HtmlExternalResolver class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.importing/htmlexternalresolver/
---
## HtmlExternalResolver класс

Объект обратного вызова, используемый процедурой импорта HTML для получения ссылочных объектов, таких как изображения.  
Использование этого резольвера может создать уязвимость, когда предоставленный клиентом файл HTML заставит серверное программное обеспечение получить локальный или сетевой файл. Используйте с осторожностью. Рекомендуется не указывать HtmlExternalResolver вовсе (будут прочитаны только встроенные объекты) или создать подкласс, который проверяет правильность указанного URI.

Тип HtmlExternalResolver предоставляет следующие члены:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ru/aspose.slides.importing/htmlexternalresolver/__init__/#) |  |

## Методы

| Метод | Описание |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/ru/aspose.slides.importing/htmlexternalresolver/resolve_uri/#str-str) | Разрешает абсолютный URI на основе базового и относительных URI. |
| [`get_entity(self, absolute_uri)`](/slides/python-net/ru/aspose.slides.importing/htmlexternalresolver/get_entity/#str) | Преобразует URI в объект, содержащий реальный ресурс. |


### См. также
* модуль [`aspose.slides.importing`](/slides/python-net/ru/aspose.slides.importing)
* библиотека [`Aspose.Slides`](/slides/python-net)