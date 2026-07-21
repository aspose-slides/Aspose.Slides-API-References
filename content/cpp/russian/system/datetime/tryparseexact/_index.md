---
title: TryParseExact()
second_title: Aspose.Slides для C++ справочник API
description: Преобразует указанное строковое представление значения даты и времени в эквивалентный объект DateTime, используя указанный формат, сведения о культуре и стиль. Формат строкового представления должен точно соответствовать указанному формату.
type: docs
weight: 898
url: /ru/system/datetime/tryparseexact/
---
## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) method

Преобразует указанное строковое представление значения даты и времени в эквивалентный объект [DateTime](../), используя указанный формат, сведения о культуре и стиль. Формат строкового представления должен точно соответствовать указанному формату.

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const [String](../../string/)\& | Строковое представление значения даты и времени для преобразования. |
| format | const [String](../../string/)\& | Строковый формат. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Объект [IFormatProvider](../../iformatprovider/), предоставляющий сведения о культуре. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Битовая комбинация значений перечисления, предоставляющая дополнительную информацию о **s**, о стилистических элементах, которые могут присутствовать в **s**, или о преобразовании **s** в объект [DateTime](../). |
| result | [DateTime](../)\& | Выходной аргумент, который при успешном преобразовании содержит результат. |

### Возвращаемое значение

True, если преобразование успешно, иначе — false.

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) method

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) method

Преобразует указанное строковое представление значения даты и времени в эквивалентный объект [DateTime](../), используя указанные форматы, сведения о культуре и стиль. Формат строкового представления должен точно соответствовать одному или нескольким из указанных форматов.

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const [String](../../string/)\& | Строковое представление значения даты и времени для преобразования. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | Массив строковых форматов. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Объект [IFormatProvider](../../iformatprovider/), предоставляющий сведения о культуре. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Битовая комбинация значений перечисления, предоставляющая дополнительную информацию о **s**, о стилистических элементах, которые могут присутствовать в **s**, или о преобразовании **s** в объект [DateTime](../). |
| result | [DateTime](../)\& | Выходной аргумент, который при успешном преобразовании содержит результат. |

### Возвращаемое значение

True, если преобразование успешно, иначе — false.

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) method

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## Смотрите также

* Перечисление [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Тип [SharedPtr](../../sharedptr/)
* Тип [ArrayPtr](../../arrayptr/)
* Класс [String](../../string/)
* Класс [IFormatProvider](../../iformatprovider/)
* Класс [DateTime](../)
* Класс [CultureInfo](../../../system.globalization/cultureinfo/)
* Класс [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)