---
title: TryParse()
second_title: Aspose.Slides для C++ API Справка
description: Пытается преобразовать указанную строку в объект DateTimeOffset.
type: docs
weight: 729
url: /ru/system/datetimeoffset/tryparse/
---
## DateTimeOffset::TryParse(const String\&, DateTimeOffset\&) method

Пытается преобразовать указанную строку в объект [DateTimeOffset](../).

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, DateTimeOffset &result)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) для преобразования. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) что эквивалентен **input**. |

### Возвращаемое значение

true если **input** успешно преобразован, иначе - false.

## DateTimeOffset::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) method

Пытается преобразовать указанную строку в объект [DateTimeOffset](../) с использованием указанного поставщика формата и стиля форматирования.

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) для преобразования. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Поставщик формата. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Стили форматирования даты и времени. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) что эквивалентен **input**. |

### Возвращаемое значение

true если **input** успешно преобразован, иначе - false.

## См. также

* Перечисление [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Типовое определение [SharedPtr](../../sharedptr/)
* Класс [String](../../string/)
* Класс [DateTimeOffset](../)
* Класс [IFormatProvider](../../iformatprovider/)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)