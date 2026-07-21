---
title: TryParseExact()
second_title: Aspose.Slides для C++ справка API
description: Пытается преобразовать указанную строку в объект DateTimeOffset, используя указанные форматы, поставщик форматов и стиль форматирования.
type: docs
weight: 742
url: /ru/system/datetimeoffset/tryparseexact/
---
## DateTimeOffset::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) method

Пытается преобразовать указанную строку в объект [DateTimeOffset](../) с использованием указанных форматов, поставщика форматов и стиля форматирования.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) для преобразования. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | Массивы строк форматов. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Поставщик форматов. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Стили форматирования даты и времени. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../), эквивалентный **input**. |

### Возвращаемое значение

true если **input** успешно преобразовано, иначе - false.

## DateTimeOffset::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) method

Пытается преобразовать указанную строку в объект [DateTimeOffset](../) с использованием указанного формата, поставщика форматов и стиля форматирования.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) для преобразования. |
| format | const [String](../../string/)\& | Строка формата. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Поставщик форматов. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Стили форматирования даты и времени. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../), эквивалентный **input**. |

### Возвращаемое значение

true если **input** успешно преобразовано, иначе - false.

## См. также

* Перечисление [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Класс [String](../../string/)
* Класс [IFormatProvider](../../iformatprovider/)
* Класс [DateTimeOffset](../)
* Пространство имён [System](../../)
* Library [Aspose.Slides](../../../)