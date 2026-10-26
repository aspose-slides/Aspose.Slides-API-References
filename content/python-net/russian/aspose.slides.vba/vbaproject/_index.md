---
title: VbaProject class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.vba/vbaproject/
---
## VbaProject класс

Представляет проект VBA с макросами презентации.

Тип VbaProject предоставляет следующие члены:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ru/aspose.slides.vba/vbaproject/__init__/#) | Этот конструктор создает новый проект VBA с нуля.<br/>            Проект будет создан в 1252 Windows Latin 1 (ANSI) codepage |
| [`__init__(self, data)`](/slides/python-net/ru/aspose.slides.vba/vbaproject/__init__/#bytes) | Этот конструктор загружает проект VBA из бинарного представления OLE контейнера. |

## Свойства

| Свойство | Описание |
| :- | :- |
| [`name`](/slides/python-net/ru/aspose.slides.vba/vbaproject/name/) | Возвращает имя проекта VBA.<br/>            Только для чтения **str**. |
| [`modules`](/slides/python-net/ru/aspose.slides.vba/vbaproject/modules/) | Возвращает список всех модулей, содержащихся в проекте VBA.<br/>            Только для чтения [`IVbaModuleCollection`](/slides/python-net/ru/aspose.slides.vba/ivbamodulecollection). |
| [`references`](/slides/python-net/ru/aspose.slides.vba/vbaproject/references/) | Возвращает список всех ссылок, содержащихся в проекте VBA.<br/>            Только для чтения [`IVbaReferenceCollection`](/slides/python-net/ru/aspose.slides.vba/ivbareferencecollection). |
| [`is_password_protected`](/slides/python-net/ru/aspose.slides.vba/vbaproject/is_password_protected/) | Указывает, защищён ли VBAProject паролем для просмотра свойств проекта.<br/>            Только для чтения **bool**. |

## Методы

| Метод | Описание |
| :- | :- |
| [`to_binary(self)`](/slides/python-net/ru/aspose.slides.vba/vbaproject/to_binary/#) | Возвращает бинарное представление проекта VBA как OLE контейнер |

### См. также
* модуль [`aspose.slides.vba`](/slides/python-net/ru/aspose.slides.vba)
* библиотека [`Aspose.Slides`](/slides/python-net)