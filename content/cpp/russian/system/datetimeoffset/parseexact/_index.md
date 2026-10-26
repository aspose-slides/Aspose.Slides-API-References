---
title: ParseExact()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует указанную строку в объект DateTimeOffset, используя указанный формат, поставщик формата и стиль форматирования.
type: docs
weight: 716
url: /ru/system/datetimeoffset/parseexact/
---
## DateTimeOffset::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) метод


Преобразует указанную строку в объект [DateTimeOffset](../) с использованием указанного формата, поставщика формата и стиля форматирования.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) для преобразования. |
| format | const [String](../../string/)\& | Строка формата. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Поставщик формата. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Стили форматирования даты и времени. |

### Возвращаемое значение

[DateTimeOffset](../), эквивалентный **input**.

## DateTimeOffset::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) метод


Преобразует указанную строку в объект [DateTimeOffset](../) с использованием указанных форматов, поставщика формата и стиля форматирования.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) для преобразования. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) строк форматов. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Поставщик формата. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Стили форматирования даты и времени. |

### Возвращаемое значение

[DateTimeOffset](../), эквивалентный **input**.

## См. также

* Перечисление [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Тип [SharedPtr](../../sharedptr/)
* Тип [ArrayPtr](../../arrayptr/)
* Класс [DateTimeOffset](../)
* Класс [String](../../string/)
* Класс [IFormatProvider](../../iformatprovider/)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)