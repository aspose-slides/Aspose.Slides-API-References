---
title: Metered class
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides/metered/
---
## Класс Metered

Предоставляет методы для установки измеряемого ключа.

Тип Metered раскрывает следующие члены:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ru/aspose.slides/metered/__init__/#) | Инициализирует новый экземпляр этого класса. |

## Методы

| Метод | Описание |
| :- | :- |
| [`set_metered_key(self, public_key, private_key)`](/slides/python-net/ru/aspose.slides/metered/set_metered_key/#str-str) | Устанавливает измеряемый публичный и приватный ключ.<br/>Если вы приобрели лицензию metered, при запуске приложения этот API должен быть вызван, обычно этого достаточно.<br/>Однако если постоянно не удаётся загрузить данные о потреблении и прошло более 24 часов, лицензия будет переведена в статус оценки,<br/>чтобы избежать такой ситуации, вам следует регулярно проверять статус лицензии; если он находится в статусе оценки, вызовите этот API снова. |
| [`get_consumption_quantity()`](/slides/python-net/ru/aspose.slides/metered/get_consumption_quantity/#) | Получает размер файла потребления |
| [`get_consumption_credit()`](/slides/python-net/ru/aspose.slides/metered/get_consumption_credit/#) | Получает кредит потребления |
| [`get_product_name(self)`](/slides/python-net/ru/aspose.slides/metered/get_product_name/#) |  |
| [`is_metered_licensed()`](/slides/python-net/ru/aspose.slides/metered/is_metered_licensed/#) | Проверяет, лицензирован ли metered |


### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)