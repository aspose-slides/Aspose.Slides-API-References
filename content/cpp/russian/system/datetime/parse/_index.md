---
title: Parse()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует указанное строковое представление значения даты и времени в эквивалентный объект DateTime.
type: docs
weight: 859
url: /ru/system/datetime/parse/
---
## DateTime::Parse(const String\&) метод

Преобразует указанное строковое представление значения даты и времени в эквивалентный объект [DateTime](../).

```cpp
static DateTime System::DateTime::Parse(const String &s)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const [String](../../string/)\& | Строковое представление значения даты и времени для преобразования. |

### Return Value

Новый экземпляр класса [DateTime](../), представляющий значение даты и времени, эквивалентное тому, которое представлено указанной строкой.

## DateTime::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) метод

Преобразует указанное строковое представление значения даты и времени в эквивалентный объект [DateTime](../) с использованием специфичной для культуры информации о формате.

```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const [String](../../string/)\& | Строковое представление значения даты и времени для преобразования. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Объект [IFormatProvider](../../iformatprovider/), предоставляющий информацию о формате, специфичную для культуры. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Побитовая комбинация значений перечисления, предоставляющая дополнительную информацию о **s**, о стилевых элементах, которые могут присутствовать в **s**, или о преобразовании **s** в объект [DateTime](../). |

### Return Value

Новый экземпляр класса [DateTime](../), представляющий значение даты и времени, эквивалентное тому, которое представлено указанной строкой.

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) метод




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) метод




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, std::nullptr_t, Globalization::DateTimeStyles) метод




```cpp
static DateTime System::DateTime::Parse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## См. также

* Перечисление [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Определение типа [SharedPtr](../../sharedptr/)
* Класс [DateTime](../)
* Класс [String](../../string/)
* Класс [IFormatProvider](../../iformatprovider/)
* Класс [CultureInfo](../../../system.globalization/cultureinfo/)
* Класс [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)